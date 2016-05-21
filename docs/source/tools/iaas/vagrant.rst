vagrant
=======

Install:
https://www.vagrantup.com/downloads.html

https://www.vagrantup.com/about.html:

"Vagrant is a tool for building complete development
environments. With an easy-to-use workflow and focus on automation,
Vagrant lowers development environment setup time, increases
development/production parity, and makes the "works on my machine"
excuse a relic of the past."


.. prompt:: bash

	    mkdir vagrant_getting_started
	    cd vagrant_getting_started
	    vagrant init

Creates Vagrantfile

.. prompt:: bash
	    
	    vagrant init hashicorp/precise64
	    vagrant up
	    vagrant ssh
	    vagrant destroy

	    vagrant box add hashicorp/precise64



By default, Vagrant shares your project directory (remember, that is
the one with the Vagrantfile) to the /vagrant directory in your guest
machine.

::	    

  Vagrant.configure("2") do |config|
    config.vm.box = "hashicorp/precise64"
  end


List of boxes:

* https://atlas.hashicorp.com/boxes/search


shell to provision
----------------------------------------------------------------------

We will just setup Apache for our basic project, and we will do so
using a shell script. Create the following shell script and save it as
bootstrap.sh in the same directory as your Vagrantfile:

#!/usr/bin/env bash

apt-get update
apt-get install -y apache2
if ! [ -L /var/www ]; then
  rm -rf /var/www
  ln -fs /vagrant /var/www
fi
Next, we configure Vagrant to run this shell script when setting up our machine. We do this by editing the Vagrantfile, which should now look like this:

Vagrant.configure("2") do |config|
  config.vm.box = "hashicorp/precise64"
  config.vm.provision :shell, path: "bootstrap.sh"
  config.vm.network :forwarded_port, guest: 80, host: 4567
end

Once the machine is running again, load http://127.0.0.1:4567

Ansible
---------


* https://www.vagrantup.com/docs/provisioning/ansible.html
* Install
http://docs.ansible.com/ansible/intro_installation.html#installing-the-control-machine

* OSX:
  http://docs.ansible.com/ansible/intro_installation.html#latest-releases-via-pip



::

  N = 3
  (1..N).each do |machine_id|
    config.vm.define "machine#{machine_id}" do |machine|
      machine.vm.hostname = "machine#{machine_id}"
      machine.vm.network "private_network", ip: "192.168.77.#{20+machine_id}"

      # Only execute once the Ansible provisioner,
      # when all the machines are up and ready.
      if machine_id == N
	machine.vm.provision :ansible do |ansible|
	  # Disable default limit to connect to all the machines
	  ansible.limit = "all"
	  ansible.playbook = "playbook.yml"
	end
      end
    end
  end

::
   
  Vagrant.configure("2") do |config|

    #
    # Run Ansible from the Vagrant Host
    #
    config.vm.provision "ansible" do |ansible|
      ansible.playbook = "playbook.yml"
    end

  end


*
https://github.com/mitchellh/vagrant/pull/5765#issuecomment-120247738

::

   machine1 ansible_ssh_host=192.168.77.21
   machine2 ansible_ssh_host=192.168.77.22
   machine3 ansible_ssh_host=192.168.77.23


::

  N = 3

  VAGRANT_VM_PROVIDER = "virtualbox"
  ANSIBLE_RAW_SSH_ARGS = []

  (1..N-1).each do |machine_id|
    ANSIBLE_RAW_SSH_ARGS << "-o IdentityFile=#{ENV["VAGRANT_DOTFILE_PATH"]}/machines/machine#{machine_id}/#{VAGRANT_VM_PROVIDER}/private_key"
  end

  (1..N).each do |machine_id|
    config.vm.define "machine#{machine_id}" do |machine|
      machine.vm.hostname = "machine#{machine_id}"
      machine.vm.network "private_network", ip: "192.168.77.#{20+machine_id}"
      if machine_id == N
        machine.vm.provision :ansible do |ansible|
          ansible.playbook = "example.yml"
          ansible.limit = 'all'
          ansible.inventory_path = "static_inventory"
          ansible.raw_ssh_args = ANSIBLE_RAW_SSH_ARGS
        end
      end

    end
  end

end

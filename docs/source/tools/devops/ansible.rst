Ansible
=======

1. create instructions on how to use ansible-galaxy to create a new
   ansible project (see bellow, improve if needed)
2. develop a simple playbook to install some software. Maybe we can do
   something like install sphinx and emacs


   https://galaxy.ansible.com/intro#share


Create a ansible project

.. prompt:: bash

  ansible-galaxy init myproject --force

::

   myproject/
      .travis.yml
      README.md
      defaults/
      files/
      handlers/
      meta/
      tasks/
      templates/
      tests/
      vars/

Than follow the instructions provided at

* https://galaxy.ansible.com/intro#share

However we do not follow the instructions to upload the repository to
ansible-galaxy starting at the section `Upload to Galaxy`

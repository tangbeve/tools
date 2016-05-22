Common Mistakes When Taking This Class
======================================================================

Time Management
----------------------------------------------------------------------
Obviously taking a class takes time

* Do not underestimate the time it takes to read the information
* Do not underestimate the time it takes to understand the information
* Do not underestimate the time to do the project

  * There are still 10 weeks left till the project is due so let me
    start in 4 weeks ….

* Do not postpone the project till the last moment
* Do spend significant time on the documentation on how to run your
  application, instead of writing scripts that can manage several of
  these steps automatically

Project Requirement Management
--------------------------------

* Do review the requirements of the project and do not just do a
  project that you like to do
* Develop deployment scripts in ansible
* Develop supporting scripts in python, use docopts for parameter and documentation
* Optionally develop scripts in bash
* Optionally develop supporting scripts with Makefiles
* Do not use .bat scripts, scripts must run on Linux
* Use the galaxy role layout to structure your scripts, but do not
  commit to galaxy

One of the biggest issues students face is to understand the
requirements of the project. It includes a non negotiatable
requirement of developing deployment scripts in **ansible**. IN this
calss we will not accept other deployment frameworks such as chef,
puppet, slatstack, and so on. Having said this we will also not accept
the use of ansible in a GUI environment that you may already have
access to.

The project should furthermore contain either a Makefile, a number of
shell scripts or a python program using docopts for starting the
environment easily.

Lets assume you decided to use a make file than we expect you can
create the IaaS with while using chameleon cloud as the default
cloud. YOu can assume that a valid `~/cloudmesh/cloudmesh.yaml` file is
available

::

   make iaas

You will test if the iaas is properly deployed with 

::

   make iaas_test

your platform will be deployed with

::

   make paas

to run your example and produce the output for it run

::

   make example_1

In case you have multiple examples please add additional targets

::

   make example_1

In case you like to use parameters, you may be better of writing a
simple python program using docopts. To call all of this above in one
command you can combine the targets and introduce a::

  make all

This way the reviewers will just nvoke make all and you document where
the output is produced. As you can see we award you for total
automation with scripts which is one of the primary educational class
goals.


Please be aware that reviewers will deduct points if either of these
do not work as expected. 


Information Management
----------------------

* I only read what is provided to me on slides or watch videos

  * A class gives you a good introduction into a topic. However you should
    assume that in order to gain more knowledge you can augment it by
    obtaining additional information beyond the class material.
    Additional tutorials, papers, or other information may enhance your
    knowledge and you benefit from it.

Security Management
-------------------

SSH
^^^^

Strangely enough a simple concept such as SSH often is cause for
confusion by the student It is important that you have an excellent
working knowledge of ssh. This means that watching a video or reading
just the documentation is not sufficient.  You need to practically
experience and understand how to use SSH for the class You need to
understand what id_rsa and id_rsa.pub is You need to understand that
you work with multiple keys. THIS IS OFTEN IGNORED by students.
Please reflect upon how you use keys in an environment where multiple
users access a VM and where multiple users access multiple VMs. In
other classes you may not be confronted with this issue.

SSH add
^^^^^^^

* Do not use password less keys on your laptops. Why? Please answer
  yourself
* Do not copy your private key to another machine or VM. Why? If you
  can not answer this question you need to reread about SSH and why
  not to do that

* What is SSH add and why is this very practical?
* How do I use SSH add?

SSH keygen
^^^^^^^^^^^
* What is SSH keygen?
* What type of key should I use?
* What permissions hould my .ssh directory have?

* What is an authorized_keys file?
* What is a known_hosts file?

./ssh/config
^^^^^^^^^^^^^

* What is ssh config?
* How can I use this to my advantage to log into vms

Passwords
^^^^^^^^^^

Do not hardcode and passwords or any private information into your
code. Instead use configuration files and secure them appropriately

Make sure you typed in your password correctly. Double check CAPS LOCK

Do not use passwords that are easy to guess


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
* Use the galaxy role layout to structure your scripts, but do not commit to galaxy

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

Documentation Management
------------------------

Report Checklist
^^^^^^^^^^^^^^^^^

* [ ] is the report spell checked?
* [ ] are you using **a** and **the** properly
* in case of word: not using sections in word documents
* in case of RST: not using underlines to indicate sections and
  subsections
* in case of RST: not using numbered sections. While LaTeX and word do
  this for you automatically
* not using bulleted lists in word
* carelessly pasting and copying into the document without using
  proper formats
* Based on previous experience we requires that LaTeX and Word reporst
  use the acm word/latex templates that can be downloaded fro the
  net. No other format may be used
* not leveraging parallel editing: onedrive allows you to
  edit a word document in collaboration
* github allows you to collaborate on latex documents
* We do not accept google docs. However you can use it to develop
  things that you may past and copy into your final report. We
  observed that students that use google docs underestimate the lack
  of structural document features and lack of 2 column format. Formats
  written in google docs are typically of lower quality.
  The acm template gives you guidance how to write a paper
  properly. Including references.

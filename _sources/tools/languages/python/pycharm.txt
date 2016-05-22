PyCharm
=======

PyCharm is one of the easiest and comprehensive editors for Python. We
recommend  tha YOu use PyCharm for developping your python
programs. IT has build in support for github.

Link: https://www.jetbrains.com/pycharm/
Features: https://www.jetbrains.com/pycharm/features/

From experience we found it is best to not use the workspace of
pycharm, but instead clone your projects from github via the command
line first and than open them. Let us assume you work on the cloudmesh
project in github which has many repositories.

To do this create a directory

.. prompt:: bash

	    mkdir -p ~/github/cloudmesh
	    cd ~/github/cloudmesh

Next create a fork of one of its repositories, lets assume you like to
work on this documentation and make improvements.

* https://github.com/cloudmesh/tools#fork-destination-box

The repository will now be forked into your own github account and you
can make modifications to it. Check out this new repository while
saying `clone or download`. YOu will be presented with a popup in
which you can see an https or an ssh link. You can copy either link
(lets assume you use ssh) and copy it into your shell that you run in
the terminal preceeded by `git clone`:

.. prompt:: bash

	    git@github.com:<your github username>/tools.git

Now the `tools` directory will show up in the cloudmesh directory.
Start PyCharm. If you have not yet created a Project, `Create New
Project` and name it CLOUDMESH (In future you can just double click on
it). Than uuse `File` -> `Open` to open and add the repository to the
current project.

You nee dto do some configurations to point to the right interpreter
and other things, but its ready to use at this point.

As this reporsitory does currently not include any code yo use pycharm
just as RST editor. To compile your code you can type in the terminal

.. prompt:: bash

	    make doc

To view the output, you can say

.. prompt:: bash

	    make view

While using this method you will have a uniform setup many different
project and edit the content with your favourite editor that is most
suitable for the task.




	    
	    

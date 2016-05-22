


=====================================================
reStructuredText
=====================================================

:Cheatcheat:
   * http://github.com/ralsina/rst-cheatsheet/raw/master/rst-cheatsheet.pdf
   * http://docutils.sourceforge.net/docs/ref/rst/directives.html
   * https://github.com/ralsina/rst-cheatsheet/blob/master/rst-cheatsheet.rst
Other links:

* http://docutils.sourceforge.net/docs/user/rst/quickref.html
* http://docutils.sourceforge.net/rst.html
* Refcard: http://github.com/ralsina/rst-cheatsheet/raw/master/rst-cheatsheet.pdf
* Sphinx RST: http://www.sphinx-doc.org/en/stable/rest.html

Important extensions:

* http://sphinx-doc.org/ext/todo.html

Sections
----------------------------------------------------------------------

RST allows to specify a number of sections. You can do this with the
various underlines::

      *********************
      Chapter
      *********************
      Section
      =====================
      Subsection
      ---------------------
      Subsubsection
      ^^^^^^^^^^^^^^^^^^^^^
      Paragraph
      ~~~~~~~~~~~~~~~~~~~~~

Listtable
----------------------------------------------------------------------

::

   .. csv-table:: Eye colors
      :header: "Name", "Firstname", "eyes"
      :widths: 20, 20, 10

      "von Laszewski", "Gregor", "gray"


.. csv-table:: a title
   :header: "Name", "Firstname", "eyes"
   :widths: 20, 20, 10

   "von Laszewski", "Gregor", "gray"


Exceltable
----------------------------------------------------------------------

we have integrated Excel table from
http://pythonhosted.org//sphinxcontrib-exceltable/ into our sphinx
allowing the definition of more elaborate tables specified in
excel. However the most convenient way may be to use list-tables. The
documentation to list tables can be found at
http://docutils.sourceforge.net/docs/ref/rst/directives.html#list-table

Boxes
----------------------------------------------------------------------

Seealso
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

::

  .. seealso:: This is a simple **seealso** note.


.. seealso:: This is a simple **seealso** note.

Note
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

::

    .. note::  This is a **note** box.


.. note::  This is a **note** box.



Warning
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. warning:: note the space between the directive and the text

::

    .. warning:: note the space between the directive and the text

Others
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^


.. attention:: This is an **attention** box.

::

    .. attention:: This is an **attention** box.


.. caution:: This is a **caution** box.

::

    .. caution:: This is a **caution** box.


.. danger:: This is a **danger** box.

::

    .. danger:: This is a **danger** box.


.. error:: This is a **error** box.

::

    .. error:: This is a **error** box.


.. hint:: This is a **hint** box.

::

    .. hint:: This is a **hint** box.


.. important:: This is an **important** box.

::

    .. important:: This is an **important** box.


.. tip:: This is a **tip** box.

::

    .. tip:: This is a **tip** box.




Sidebar directive
----------------------------------------------------------------------

It is possible to create sidebar using the following code::

    .. sidebar:: Sidebar Title
        :subtitle: Optional Sidebar Subtitle

        Subsequent indented lines comprise
        the body of the sidebar, and are
        interpreted as body elements.


.. sidebar:: Sidebar Title
    :subtitle: Optional Sidebar Subtitle

    Subsequent indented lines comprise
    the body of the sidebar, and are
    interpreted as body elements.

Autorun
----------------------------------------------------------------------

Autorun is an extension for Sphinx_ that can execute the code from a
runblock directive and attach the output of the execution to the document.

For example::

    .. runblock:: pycon

        >>> for i in range(3):
        ...    print i

Produces

.. runblock:: pycon

    >>> for i in range(3):
    ...    print i


Another example::

    .. runblock:: console

        $ date

Produces

.. runblock:: console

   $ date

However, when it comes to exercises we do prefer the use of ipython
notebooks as this allows us to present them also to users as self
contained exercises.

Hyperlinks
----------------------------------------------------------------------

Direct links to html pages can be done with::

   `This is a link to an html page <hadoop.html>`_

Note that this page could be generated from an rst page


Links to the FG portal need to be formulated with the portal tag::

  :portal:`List to FG projects </projects/all>`

In case a subsection has a link declared you can use :ref: (this is
the preferred way as it can be used to point even to subsections::

  :ref:`Connecting private network VMs  clusters <_s_vpn>`

A html link can be created anywhere in the document but must be
unique. for example if you place::

  .. _s_vpn:

in the text it will create a target to which the above link points when you click on it


Todo
----------------------------------------------------------------------

::

      .. todo:: an example

.. todo:: an example

Not quite WYSIWYG
-----------------

Often you may want to observe the changes that you make in an RST
document upon saving it while automating the process of calling the
sphinx make process and displaying the result.

To accomplish this two tools will help you Watchdog and Atom.


Watchdog
^^^^^^^^^

Watchdog is a small python script that watches changes on the file
system and can execute a shell command based on a change. Together
with a firefox plugin this allows you to view the changes in your
sphinx document. NAturally you could also create via pandoc a PDF
version and use a PDF broswer such as skim to view the changes in the
resulting document.

::

  pip install watchdog

::

  make doc


Watch changes with your browser in a file with

* https://addons.mozilla.org/en-US/firefox/addon/auto-reload/

Let us assume you replicate our documentation setup and use the
Makefile included in the git repository.

Than you can simply say

::

   make watch

in the directory. You can than edit the file and if you look at it
with firefox, you will see the changes. For larger sites this may take
some time.

pandoc and skim
---------------

A very simple approach is also to use the autoreload feature from skim
which is a pdf previewer. Let us assume you have a file called
`filename.rst`. The command 

.. prompt:: bash
   
   watchmedo shell-command --patterns="*.rst" --recursive --command='pandoc filename.rst -o filename.pdf'

will create a pdf file that you can view with skim. Skim deals much
better with PDF reloads than firefox and chrome or the preview comming
natively with OSX.

However as pandoc does not deal with the sphinx plugins you may not be
able to see everything in case you rely on sphinx.  Naturally instead
of PDF you can generate other formats such as html with pandoc and use
aalternative borwsers.  The combination of `skim` and `pandoc` is
typically very fast.

Atom
^^^^

Atom is a simple editor available on all platforms. It can be extended
with a RestructuredText plugin. ONce installed, and you are in an RST
document you can preview the new changes while pressing
`CTRL-SHIFT-r`.

Atom can be downloaded form: https://atom.io/


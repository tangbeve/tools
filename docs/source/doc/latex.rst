LaTeX
=====

Short and useful information about LaTeX:
-----------------------------------------

LaTeX Slides**
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

A short course in LaTeX by Gregor von Laszewski can be found on the NPAC
ftp server. The document is available in
`dvi </web/20000817095300/http://www.npac.syr.edu/users/gregor/latex/slides96.dvi>`__
and
`postscript </web/20000817095300/http://www.npac.syr.edu/users/gregor/latex/slides96.ps>`__
format. The document is about 40 pages long. A `compressed postscript
file in
gzip </web/20000817095300/http://www.npac.syr.edu/users/gregor/latex/slides96.ps.gz>`__
format is also available to reduce the download time. The files are also
available via the `anonymous ftp
site <ftp://ftp.npac.syr.edu/pub/users/gregor/latex>`__

LaTeX Reference Manual
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The `LaTeX Reference Manual <http://texdoc.net/texmf-dist/doc/latex/latex2e-help-texinfo/latex2e.pdf>'__
provides a good intriduction to Latex.


Documentation and Programs
--------------------------

**The LaTeX Navigator**

`The LaTeX Navigator
(France) </web/20000817095300/http://www.loria.fr/tex/english/index.html>`__
provides Documentation about macros, packages, formats, tools, TeX
engines, gives pointers, ... .

**CTAN**

The main `TeX and LaTeX
Archive </web/20000817095300/http://www.cdrom.com/pub/tex/ctan/CTAN.sites>`__
contains almost all information and source codes you need to run and
install LaTeX. In case a style file is missing on your site, you
probably find it here.

**TeX and LaTeX index**

The `TeX and LaTeX
Index <ftp://theory.lcs.mit.edu//pub/tex/TeX-index>`__ contains a list
of many extensions to TeX and LaTeX and a short documents describing
them.

**LaTeX and Pictures**

Including Pictures in LaTeX is one of the most frequently asked
questions. Plenty of information about it can be found in the locations
specified above. I recommend to take a look in the book ''The LaTeX
Companion''. A useful source is also the a little bit outdated
`technical
report <ftp://ftp.npac.syr.edu/pub/users/gregor/ftp/LATEX/tr91-003.ps.gz>`__
from University of Florida.

**Other Documentation**

Other documentation which is locally available can be found on the
following anonymous ftp site:
ftp://ftp.npac.syr.edu/pub/users/gregor/ftp/LATEX It includes documents
which helps for an easy start while using LaTeX. Most of the documents
are for the older version of LaTeX but still useful.

**LaTeX2e**

The
`LaTeX2e <ftp://ftp.npac.syr.edu/pub/users/gregor/ftp/LATEX/LaTeX2e.ps.gz>`__
report provides information about new features and changes to the
previous LaTeX version 2.09.

**Literate Programming**

I recommend everyone to take a look into `Literate
Programming </web/20000817095300/http://info.desy.de/pub/www/projects/LitProg.html>`__.
It might just change the way how you look at programming in future. In
the local LaTeX guide I included an elaborate example, which shows how
to use gnuplot in a LaTeX document.

**Addison Wesley Books**

`Addison
Wesley </web/20000817095300/http://www.germany.eu.net/shop/AW/KE/DT>`__
provides online descriptions of books about text processing (LaTeX, TeX,
...).

**LaTeX Reference Manual**

The official LaTeX Reference Manual can be found at CTAN.

A very good `Reference
Manual </web/20000817095300/http://es-sun2.fernuni-hagen.de/info2html?(latex.info)Top>`__
is available online from University Hagen in Germany.

**FAQ**

A list of all
`fonts </web/20000817095300/http://www.cis.ohio-state.edu/hypertext/faq/usenet/fonts-faq/metafont-list/faq.html>`__
available in .mf format can help to locate special fonts like hyroglyhs,
tamil, ...

There is also a monthly posting of `TeX and LaTeX
FAQ </web/20000817095300/http://www.cis.ohio-state.edu/hypertext/faq/usenet/tex-faq/faq.html>`__.
Please make sure you check those and browse through the information
provided above before you ask me about a problem.

**LaTeX and MS-Windows**

Recently, I got a lot of questions about LaTeX and Windows 95. It s
possible to run LaTeX on MS-Windows. The disributions can be found in
CTAN. The book Making TeX work describes some of the avaialable
distributions. Currently, the book is sold by O Reiley for $9.95 (this
is not a printing error).

On the other hand you can run Linux on most Intel or Dec machines.
Advantages of using Linux:

-  You are using a real operating system
-  You can run many programs from the UNIX world
-  You can use xemacs, which colorizes your LaTeX code quite nicely
-  It took me over two hours to install Plug and Play Windows95 because
   half of the drivers I needed were not there. So much for plug and
   play. It took me 30 minutes to install Linux including all drivers,
   TeX, LaTeX, xemacs, free C++ compilers, ... .
-  Linux is free.
-  Linux is much much much faster than the slow slow slow Windows

Fore those who want to locate information about this in CTAN, please
look for the following (incomplete list of packages):

free: emTeX, texas, sbTeX, gTeX

comercial: muTeX bt ArborText, Y+YTeX, Textures, TurboTeX, PCTeX

LaTeX and OSX
^^^^^^^^^^^^^^^^^^^
* https://tug.org/mactex/


Gregor's LaTeX Guide
--------------------


Introduction
~~~~~~~~~~~~

Mastering a text processing system is an essential part of a
researchers life. Not knowing how to use a text processing system
can slow down the productivity of research drastically. In the years
from 1991 to 1996 I gave about 9 seminar talks about LaTeXSyracuse
University and NPAC. During this time I was confronted with many
questions of beginners in LaTeX. In order to provide a quick guide
to LaTeX I designed this page. If you have comments and suggestions
on how to improve this page, please let me know.

Getting started
~~~~~~~~~~~~~~~

This page is not intended to replace one of the many text books
available about LaTeX. For the beginning you might be just fine with
the documentation provided here. For serious users I recommend to
purchase a book. I do not want to give a recommendation for one or
the other book, therefore I list here only the most popular ones:

-  LaTeX Users and Reference Guide, by Leslie Lamport
-  LaTeX an Introduction, by Helmut Kopka
-  The LaTeX Companion, by Frank Mittelbach

If you buy books for LaTeX you should be aware that a new version is
released. Unfortunately it is not yet officially installed on our
systems. The current version is LaTeX2e and you should see if this
version is covered in the book, if not do not buy the book.

Nevertheless, most of the old LaTeX files can be formatted with the
new version. Therefore, you do not have to through your old LaTeX
books away. The LaTeX Companion gives hints how to use some very
useful extension programs.

If you do not want to buy a book you can find a lot of useful
information in the Slides I prepared for an introductory LaTeX
`seminar <slides96.ps>`__. In the slides you will find examples of
how to include graphics into your document.

More elaborate examples for including graphics in documents are
given in a technical
`report <ftp://ftp.npac.syr.edu/pub/users/gregor/ftp/LATEX/tr91-003.ps.gz>`__
by the Florida State University. Note that this report reflects the
old LaTeX.

Customizing and Latex Archives
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Since LaTeX is such a powerful Text Processing system a lot of
literature and programs are existing for it. Once you become more
familiar with LaTeX you might want to customize it and extend it for
your own needs. You will find many useful extensions in the CTAN
Archive. I recommend to browse around and to see what is available.

Setting up your Environment
~~~~~~~~~~~~~~~~~~~~~~~~~~~

You have to make the decision if you want to use the LaTeX version
2.09 or 2e, which is the new standard. I recommend to switch to 2e
as soon as possible, because more programs are supported in the new
version. For LaTeX2e you can also find a template for writing NPAC
technical reports in /home/T10D/latex/DIST/contrib.

LaTeX Version 2.09
~~~~~~~~~~~~~~~~~~

LaTeX is installed and maintained by systems on the SUN
workstations. Please run it if possible on your own workstation and
not on one of the file servers.

To make LaTeX run you should include the Following variables in your
environment in the .cshrc file.

-  the environment variable PATH should contain /usr/local/bin
-  setenv TEXEDIT \`\`emacs +%d %s''
    *to set the default editor if an error occurs and you want to
   edit it.*
-  setenv TEXINPUTS
   .:HOME/fonts:/HOME/tex/fonts:/usr/local/lib/tex/fonts
    *to set if you have special fonts not provided by systems.*

Before you place them in your environment, please check if they do
not already exists. Do this by typing env or printenv. In general
systems has set up your environment in such a way that you don't
have to include them in your .cshrc file. Read the manual pages to
latex and tex to find out more about these shell variables.

Installing LaTex2e
~~~~~~~~~~~~~~~~~~

To install LaTex2e in your environment you have to include the
following lines in your .cshrc file::

    ########### LATEX installation in .cshrc file #####
    #
    setenv LATEX /home/T10D/latex/DIST
    setenv TEXINPUTS .:$LATEX/inputs:$LATEX/contrib:$HOME/tex:/usr/local/lib/tex/inputs
    setenv TEXFORMATS $LATEX/formats
    #
    ###################################################

Manual pages and programs
~~~~~~~~~~~~~~~~~~~~~~~~~

Following programs are useful for using LaTeX. To most of them you
will find also manual pages:


+---------------------------------------------------------------------------------------------------+------------------------------------------------------+
| latex                                                                                             | the latex program                                    |
+---------------------------------------------------------------------------------------------------+------------------------------------------------------+
| xdvi                                                                                              | to preview translated documents                      |
+---------------------------------------------------------------------------------------------------+------------------------------------------------------+
| dvips                                                                                             | to convert documents to postscript                   |
+---------------------------------------------------------------------------------------------------+------------------------------------------------------+
| lpr                                                                                               | to print postscript documents                        |
+---------------------------------------------------------------------------------------------------+------------------------------------------------------+
| ghostview                                                                                         | to view the postscript documents                     |
+---------------------------------------------------------------------------------------------------+------------------------------------------------------+
| `gs </web/20000817095300/http://www.cs.wisc.edu/ghost>`__                                         | a simple postscript viewer,                          |
+---------------------------------------------------------------------------------------------------+------------------------------------------------------+
| - \`\` -                                                                                          | sometimes ghostview fails                            |
+---------------------------------------------------------------------------------------------------+------------------------------------------------------+
| bibtex                                                                                            | to create bibliographies                             |
+---------------------------------------------------------------------------------------------------+------------------------------------------------------+
| bibcard                                                                                           | very fancy GUI to bibtex files                       |
+---------------------------------------------------------------------------------------------------+------------------------------------------------------+
| xbibtex                                                                                           | less fancy GUI to bibtex files                       |
+---------------------------------------------------------------------------------------------------+------------------------------------------------------+
| `netpbm <ftp://ftp.cs.ubc.ca/ftp/archive/netpbm>`__                                               | image conversion toolkit                             |
+---------------------------------------------------------------------------------------------------+------------------------------------------------------+
| `gnuplot </web/20000817095300/http://www.cs.dartmouth.edu/gnuplot_info.html>`__                   | two dimensional interactiv drawing program           |
+---------------------------------------------------------------------------------------------------+------------------------------------------------------+
| `xgraph <ftp://ftp.x.org/contrib/applications/drawing_tools/xfig>`__                              | another two dimensional interactiv drawing program   |
+---------------------------------------------------------------------------------------------------+------------------------------------------------------+
| `xvgr, xmgr </web/20000817095300/http://hal6000.thp.uni-duisburg.de/doc/xmgr_doc/ACEgr.html>`__   | two dimensional interactiv drawing program           |
+---------------------------------------------------------------------------------------------------+------------------------------------------------------+

If you can not find a program, you might want to look in the
directory

-  */home/T10D/latex/bin*

Note: you will not be able to run /home/T10D/latex/bin/xdvi. Use the
original version in /usr/local/X11/bin/xdvi instead.

Note: All programs are only compiled for Sun4.

The LaTeX Cycle
~~~~~~~~~~~~~~~

#. emacs fname.tex *Create/edit ASCII source file with .tex file
   extension*
#. bibcard refs.bib *If necessary, create/edit bibliography file
   with .bib file extension*
#. latex fname *Run LaTeX*
#. *Correct syntax errors if present (goto step 1)*
#. bibtex fname *If necessary, run BibTeX*
#. *Rerun LaTeX if necessary (goto step 3)*
#. xdvi fname *View document*
#. dvips -o fname.ps fname *Create postscript file*
#. lpr fname.ps *Print postscript file*

Converting LaTeX to HTML
~~~~~~~~~~~~~~~~~~~~~~~~

Introduction
~~~~~~~~~~~~

The program latex2html provides a simple method of converting LaTeX
documents into HTML format. Currently it is available on different
machines under the name latex2html. The current verssion is 96.1 and
allows the inclusion of tables and equations (HTML 3.1).

You can find the program in */usr/npac/lib/latex2html-96.1*.

In order to run latex2html proerly you must include */usr/local/bin*
and */usr/npac/bin/netpbm* in your PATH variable. Because latex2html
is designed for LaTeX2e I recommend to update your environment as
described previously.

The official distribution can be found at
`http://cbl.leeds.ac.uk/nikos/tex2html </web/20000817095300/http://cbl.leeds.ac.uk/nikos/tex2html>`__.
A postscript version of the documentattion is stored in
*/usr/npac/lib/latex2html/docs*.

The generation of tables in html2latex is still a little bit
problemantic. if you put an hline command in the table all fields
will be outlined. Furthermore empty fields should include a ``~`` so
that they are treated as fields with an entry. Example:

::

       \begin{tabular}{lcccc}
           Machine & gcc & blas & emssl & dxml \\
           \hline
           SUN SPARC & X & X & ~ & ~\\
           RS6000    & X & X & X & ~\\
           DEC ALPHA & X & ~ & ~ & X\\
           \hline
       \end{tabular}


Instalation
~~~~~~~~~~~

If you want to install latex2html on another system you need to
install netpbm, gnu gs-2.6.2 or better, nad the latex2html program.

The installtion is relatively easy. and the program install-test in
the latex2html directory helps to locate the necessary programs.

Ghostscript has to be installed properly on your system. If it is
not placed under /usr/local, one has to modify the appropiate e.g.,
cc-head.mak file (for a SUN) in the distibution. Be sure to update
the PREFIX and the BINDIR directory appropiatly. The fonts are
usually stored in (PREFIX)/lib/ghostscript. Thus you should copy the
desired fonts in this directory.

In addition you need the newest version of the netpbm programs which
are used by latex2html to convert postscript to GIF. Netpbm is a
toolkit for conversion of images between a variety of different
formats, as well as to allow a few basic image operations. The
package is portable to many platforms. Netpbm is based on the widely
spread Pbmplus package with many improvements.

The packages can be found, for example, at

**latex2html**

`http://cbl.leeds.ac.uk/nikos/tex2html </web/20000817095300/http://cbl.leeds.ac.uk/nikos/tex2html>`__

**ghostscript**

`http://www.cs.wisc.edu/\ ``~``\ ghost </web/20000817095300/http://www.cs.wisc.edu/%20ghost>`__

**netpbm**

ftp://ftp.cs.ubc.ca/ftp/archive/netpbm

Since there might be the need to convert certain other graphics format
to postscript to include them in a LaTeX document a list of available
programs from the netpbm package are give. The programs can be used with
pipes in order to create a valid conversion path to postscript. Many
options are available. It is referred to the manual pages in order to
find out more details.

+--------------+-----------------------------------+
|              | convert to portable bitmap from   |
+--------------+-----------------------------------+
| atktopbm     | Andrew Toolkit raster object      |
+--------------+-----------------------------------+
| brushtopbm   | Xerox doodle brushes              |
+--------------+-----------------------------------+
| cmuwmtopbm   | CMU window manager format         |
+--------------+-----------------------------------+
| g3topbm      | Group 3 FAX                       |
+--------------+-----------------------------------+
| icontopbm    | Sun icon                          |
+--------------+-----------------------------------+
| gemtopbm     | GEM .img format                   |
+--------------+-----------------------------------+
| macptopbm    | MacPaint                          |
+--------------+-----------------------------------+
| mgrtopbm     | MGR format                        |
+--------------+-----------------------------------+
| pi3topbm     | Atari Degas .pi3                  |
+--------------+-----------------------------------+
| xbmtopbm     | X10 or X11 bitmap                 |
+--------------+-----------------------------------+
| ybmtopbm     | Bennet Yee "face" file in         |
+--------------+-----------------------------------+

+--------------+-----------------------------------+
|              | convert from portable bitmap to   |
+--------------+-----------------------------------+
| pbmto10x     | Gemini 10x printer graphics       |
+--------------+-----------------------------------+
| pbmtoascii   | ASCII graphic form                |
+--------------+-----------------------------------+
| pbmtoatk     | Andrew Toolkit raster object      |
+--------------+-----------------------------------+
| pbmtobbnbg   | BBN BitGraph graphics             |
+--------------+-----------------------------------+
| pbmtocmuwm   | CMU window manager format         |
+--------------+-----------------------------------+
| pbmtoepson   | Epson printer graphics            |
+--------------+-----------------------------------+
| pbmtog3      | Group 3 FAX                       |
+--------------+-----------------------------------+
| pbmtogem     | GEM .img file                     |
+--------------+-----------------------------------+
| pbmtogo      | GraphOn graphics                  |
+--------------+-----------------------------------+
| pbmtoicon    | Sun icon                          |
+--------------+-----------------------------------+
| pbmtolj      | HP LaserJet graphics              |
+--------------+-----------------------------------+
| pbmtomacp    | MacPaint                          |
+--------------+-----------------------------------+
| pbmtomgr     | MGR format                        |
+--------------+-----------------------------------+
| pbmtopi3     | Atari Degas .pi3                  |
+--------------+-----------------------------------+
| pbmtoplot    | Unix plot(5) file                 |
+--------------+-----------------------------------+
| pbmtoptx     | Printronix graphics               |
+--------------+-----------------------------------+
| pbmtoxbm     | X11 bitmap                        |
+--------------+-----------------------------------+
| pbmtox10bm   | X10 bitmap                        |
+--------------+-----------------------------------+
| pbmtoybm     | Bennet Yee "face" file            |
+--------------+-----------------------------------+
| pbmtozinc    | Zinc Interface Library icon       |
+--------------+-----------------------------------+

+--------------+---------------------------------------+
|              | convert to portable to graymap from   |
+--------------+---------------------------------------+
| fitstopgm    | FITS format to portable graymap       |
+--------------+---------------------------------------+
| fstopgm      | Usenix FaceSaver(tm) format           |
+--------------+---------------------------------------+
| hipstopgm    | HIPS format                           |
+--------------+---------------------------------------+
| lispmtopgm   | a Lisp Machine bitmap file            |
+--------------+---------------------------------------+
| psidtopgm    | PostScript "image" data               |
+--------------+---------------------------------------+
| rawtopgm     | raw grayscale bytes                   |
+--------------+---------------------------------------+

+--------------+-------------------------------+
|              | convert portable graymap to   |
+--------------+-------------------------------+
| pgmtofits    | FITS format                   |
+--------------+-------------------------------+
| pgmtofs      | Usenix FaceSaver(tm) format   |
+--------------+-------------------------------+
| pgmtolispm   | into Lisp Machine format      |
+--------------+-------------------------------+
| pgmtopbm     | portable bitmap               |
+--------------+-------------------------------+

+--------------+-----------------------------------+
|              | convert to portable pixmap from   |
+--------------+-----------------------------------+
| giftoppm     | GIF                               |
+--------------+-----------------------------------+
| gouldtoppm   | Gould scanner file                |
+--------------+-----------------------------------+
| ilbmtoppm    | IFF ILBM                          |
+--------------+-----------------------------------+
| imgtoppm     | Img-whatnot                       |
+--------------+-----------------------------------+
| mtvtoppm     | MTV ray-tracer output             |
+--------------+-----------------------------------+
| pcxtoppm     | PC Paintbrush format              |
+--------------+-----------------------------------+
| pi1toppm     | Atari Degas .pi1                  |
+--------------+-----------------------------------+
| picttoppm    | Macintosh PICT                    |
+--------------+-----------------------------------+
| pjtoppm      | HP PaintJet file                  |
+--------------+-----------------------------------+
| qrttoppm     | QRT ray-tracer output             |
+--------------+-----------------------------------+
| rawtoppm     | raw RGB bytes                     |
+--------------+-----------------------------------+
| sldtoppm     | an AutoCAD slide file             |
+--------------+-----------------------------------+
| spctoppm     | Atari compressed Spectrum         |
+--------------+-----------------------------------+
| sputoppm     | Atari uncompressed Spectrum       |
+--------------+-----------------------------------+
| tgatoppm     | TrueVision Targa file             |
+--------------+-----------------------------------+
| ximtoppm     | Xim                               |
+--------------+-----------------------------------+
| xpmtoppm     | XPM format                        |
+--------------+-----------------------------------+
| yuvtoppm     | Abekas YUV format                 |
+--------------+-----------------------------------+
| rgb3toppm    | combine three portable graymaps   |
+--------------+-----------------------------------+
| pgmtoppm     | colorize a portable graymap       |
+--------------+-----------------------------------+

+--------------+-----------------------------------------------------------+
|              | convert from portable pixmap                              |
+--------------+-----------------------------------------------------------+
| ppmtoacad    | AutoCAD database or slide                                 |
+--------------+-----------------------------------------------------------+
| ppmtogif     | GIF                                                       |
+--------------+-----------------------------------------------------------+
| ppmtoicr     | NCSA ICR graphics                                         |
+--------------+-----------------------------------------------------------+
| ppmtoilbm    | IFF ILBM                                                  |
+--------------+-----------------------------------------------------------+
| ppmtopcx     | PC Paintbrush format                                      |
+--------------+-----------------------------------------------------------+
| ppmtopgm     | portable graymap                                          |
+--------------+-----------------------------------------------------------+
| ppmtopi1     | Atari Degas .pi1                                          |
+--------------+-----------------------------------------------------------+
| ppmtopict    | Macintosh PICT                                            |
+--------------+-----------------------------------------------------------+
| ppmtopj      | HP PaintJet file                                          |
+--------------+-----------------------------------------------------------+
| ppmtopuzz    | X11 "puzzle" file                                         |
+--------------+-----------------------------------------------------------+
| ppmtosixel   | DEC sixel format                                          |
+--------------+-----------------------------------------------------------+
| ppmtotga     | TrueVision Targa file                                     |
+--------------+-----------------------------------------------------------+
| ppmtouil     | Motif UIL icon file                                       |
+--------------+-----------------------------------------------------------+
| ppmtoxpm     | XPM format                                                |
+--------------+-----------------------------------------------------------+
| ppmtoyuv     | Abekas YUV format                                         |
+--------------+-----------------------------------------------------------+
| ppmtorgb3    | separate a portable pixmap into three portable graymaps   |
+--------------+-----------------------------------------------------------+

convert raster formats

+-------------+-----------------------------------------------------+
| rasttopnm   | convert Sun raster file to portable anymap          |
+-------------+-----------------------------------------------------+
| tifftopnm   | convert TIFF file to portable anymap                |
+-------------+-----------------------------------------------------+
| xwdtopnm    | convert X10 or X11 window dump to portable anymap   |
+-------------+-----------------------------------------------------+

+-------------+------------------------------+
|             | convert portable anymap to   |
+-------------+------------------------------+
| pnmtops     | PostScript                   |
+-------------+------------------------------+
| pnmtorast   | Sun raster file              |
+-------------+------------------------------+
| pnmtotiff   | TIFF file                    |
+-------------+------------------------------+
| pnmtoxwd    | X11 window dump              |
+-------------+------------------------------+

Transfering MacIntosh Pictures
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

As you can see from the list of programs provided by netpbm you can
translate many different formats to Postscript. This includes also
Macintosh specific formats.

Sometimes it is a problem to print and use Postscript pictures which
are generated on a MacIntosh. This is due to the fact that during
printing several MacIntosh specific files have to be downloaded to
the printer first, before the actual file is printed.

In most cases these files will not be on your system, thus printing
is not possible.

Certain graphics program also do not define bounding boxes so that
the inclusion n Latex is not possible either. (see bbfig, note done
yet).


If you do not have netpbm you might be able to translate the
graphics also with the help of *xv*. The following steps describe
the translation:

#. Save the Macintosh graphic in TIFF, JPEG, or GIF file format.
#. FTP the file to a UNIX machine where xv is installed. This can be
   checked via *which xv* on the UNIX machine. Use ASCII mode
   transfer.
#. Open an X11-window start the program *xv*
#. Load the TIFF, JPEG, or GIF file into xv, via the "Load" menu
   item.
#. Under xv's "Save" menu, chose the Postscript file format and save
   the file as fname.ps.
#. Activate the preview and the compress option.
#. Choose the proper layout and size.
#. The file fname.ps can be included in a latex file using the
   "psfig" latex environment.



How to save paper?
~~~~~~~~~~~~~~~~~~

Today it is important that we increase our awareness for natural
resources. One of the issues is to reduce the amount of paper we use
for printing programs and Documentation. Often it is only necessary
to read manuals or manual pages online. I encourage everyone to
avoid printing. Instead design your own HTML page and include the
links to your favorite manuals in it. This way you can easily go
back and look up what you want to know.

If you have LaTeX documents I encourage to use

::

       /documentclass[twocolumn]{article}

which will print your document in two columns. My preferred way of
saving paper is the 2up.sty.

::

       /documentclass[2up]{article}

which reduces automatically your font and prints two pages on one
page instead. To print documents in 2up mode use the command

    */usr/home/T10D/latex/bin/lptex dvifilename 2*

The 2 at the end indicates that 2 pages are printed in rotate
fashion on one page. To print selected pages use the command <p>

    *lpside2 dviname 3 6 7*

Which would print the pages 3,6, and 7 of the dvifile *dviname*.
Note: It would print page 5,6 (3), 11,12 (6) and 13,14 (7) of the
real page numbers in the document. <p>

For pages in non 2up mode you have the same commands. <p>

    *lpside dviname 1 3 9 -> prints pages 1, 3, and 9*

    *lprange dviname 1 6 -> prints pages 1 2 3 4 5 6*

    *lptex dviname -> prints the whole document*

So print only the pages, you know you have changed, rather than the
whole document.

How to use emacs with LaTeX
~~~~~~~~~~~~~~~~~~~~~~~~~~~

The text editor emacs provides a good basis for editing TeX and
LaTex documents. Both modes are supported. In addition there exists
a color highlight module enableling the color display of LaTeX and
TeX commands.

In order to make use of this facilities one should edit the file
*``~``/.emacs*. Include the following lines in this file, but be
careful that you do not introduce any side effects with other
commands already used in this file. For more information I recommend
the manual.

::

    (cond (window-system
      (setq hilit-mode-enable-list  '(not text-mode)
            hilit-background-mode   'light
                  hilit-inhibit-hooks     nil
                  hilit-inhibit-rebinding nil)

            (require 'hilit19)
            ))

    (hilit-translate type     'RoyalBlue   ; enable highlighting in C/C++
                     define   'RoyalBlue   ; enable highlighting in C/C++
                     comment  'Red         ; enable highlighting in C/C++
                     decl     'green       ; enable highlighting in C/C++
                     include  'Purple      ; enable highlighting in C/C++
                     string   nil)         ; disable string highlighting

    (global-set-key "\eg" 'goto-line) ;; put goto-line on ESC g
    (setq auto-mode-alist
          (append '(("\\.csh$".csh-mode)
                    ("\\.sh$".sh-mode)
                    ("\\.C$".c++-mode)
                    ("\\.cc$".c++-mode)
                    ("\\.f9$".fortran-mode)
                    ("\\.f90$".fortran-mode)
                    ("\\.F$".fortran-mode)
                    ("\\.tex$".latex-mode)
                    ("\\.w$".latex-mode)
                    ("\\.inc$".fortran-mode)
                    ("\\.e?ps$".postscript-mode)
                    ;;("\\.bib$".bibtex-mode)
                    )
                  auto-mode-alist))

Other extensions and packages for TeX include AUC Tex. AUC TeX is an
extensible package that supports writing and formatting TeX files
for most variants of GNU Emacs. Many different macro packages are
supported, including AMS TeX, LaTeX, and TeXinfo. AUC TeX is
available from
`http://sunsite.auc.dk/auctex </web/20000817095300/http://sunsite.auc.dk/auctex>`__.

To spell check a LaTeX document I recommend ispell. Ispell is spell
checker in C with interface available for Emacs. It can adapt
different dictionaries from several languages. Thus you can spell
check German, British English, or American English. The dictionaries
and their source can be found at

ftp://ftp.th-darmstadt.de/pub/dicts/ispell/

How to edit Bibliographies?
~~~~~~~~~~~~~~~~~~~~~~~~~~~

It is a waste of your time to edit bibliographies with the bibitem
environment. There are several preformated styles available. It
includes also styles for ACM and IEEE bibliographies. So there is no
need for you to reformat the entries with brackets, capital letters
and other things.

First you have to declare a reference database. This can be done in
2 ways. Either use emacs and change to the bibtex-mode (ESC-x
bibtex-mode). This will change your emacs window and add menus to
the window. They are self explanatory so it is real easy to use.

An even more simpler program is bibcard or bibview which allows the
access to a bibliography data base with the help of a fancy
graphical user interface. The only thing you have to do after
specifying the entries is to save the file and add at the end of
your program the following lines

::

      \bibliographystyle{plain}
      \bibliography{references.bib}

Than you have to run latex and bibtex in the following order:

::

      latex  file
      bibtex file
      latex  file
      latex  file

The reason for the multiple execution of the latex program is to
update all crossreferences correctly. In case you are not interested
in updating the library every time in the writing progress just
postpone it till the end. Missing citations are viewed as [?].

Additional programs for bibliography databases are available from
the net. I recommend bib2dvi which generates a dvi file out of a
whole database. But often it will be sufficient to use bibcard
online. to search for the appropriate citation key.

jabref
^^^^^^

* http://www.jabref.org/

How do I produce Slides?
~~~~~~~~~~~~~~~~~~~~~~~~

Do not use the slides package use the seminar package.

::

    \documentclass{seminar}

    \begin{slide}

    Hello World on slide 1

    \end{slide}

    The text between slides is ignored

    \begin{slide}

    Hello World on slide 2

    \end{slide}

How to create 2d plots
~~~~~~~~~~~~~~~~~~~~~~

To create 2 dimensional graphics to include into LaTeX many programs
are available. My favorite ones are

#. ipl
#. xvgr or xmgr
#. gnuplot

   Other programs exist to, you might want to check out xgraph,
   matlab and mathematica. I prefer the ones above, because they are
   free and provide me with the necessary features. ipl provides
   box-whisker programs and can be found in comp.sources. It is for
   SUNS, but I modified it to provide a port for LINUX.

How to create Diagrams
~~~~~~~~~~~~~~~~~~~~~~

As with 2d-ploting programs many graph drawing programs exist. One
key feature such a program should have is to group object together.

**idraw**

My favorite program used to be idraw, but currently I still look for
a port to LINUX under ELF. Idraw will run on most workstations
including RS6000 and SUN workstations, because it is part of the
interviews package from Stanford university.

**xfig**

One of the most used programs is
`xfig <ftp://ftp.x.org/contrib/applications/drawing_tools/xfig/xfig.3.1.3.tar.gz>`__.
Unfortunately, I find it a little bit to complicated, and I decided
not to use it.

**tgif**

Instead I recommend the program
`tgif </web/20000817095300/http://bourbon.cs.ucla.edu:8001/tgif>`__,
which combines many good features from xfig and idraw. It alows
inclusion of GIFs and bitmaps and provides the usual drawing
functions known from idraw and xfig.

It can generate color encapsulated postscript which you can include
with the figure environment into LaTeX. The program runs on
basically every workstation including LINUX ELF.


How do I produce self extracting graphics for LaTeX
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Check out the following software engineering master piece ;-)

File: timings.w

::

    @O Makefile -t @{
    all:
        nuweb timings.w
        gnuplot graph.eps
        latex timings.tex

    clean:
        -rm *.aux *.log *~ *.dvi
        -rm timings.tex
        -rm graph.eps graph.dat graph.ps
    @}


    @O graph.eps @{
    set output   "graph.ps"

    set terminal postscript portrait "Helvetica" 7
    set size 0.25,0.25

    set noxzeroaxis
    set noyzeroaxis

    set xlabel "Processors"
    set ylabel "Time in s"

    set xrange [-1:8]
    set yrange [0:4]
    set key 5, 1

    set data style linespoints

    plot "graph.dat"  using 1:2 title "block decomposition", \
         "graph.dat"  using 1:3 title "cyclic decomposition"

    @}

    @O graph.dat @{
    #
    # processor  time in s
    #              block    cycle
    # ----------------------------
        0   2.990   2.730
        1   2.970   2.800
        2   2.950   2.830
        3   2.760   2.780
        4   2.530   2.690
        5   2.510   2.700
        6   2.330   2.710
        7   2.680   2.750
    @}


    @O timings.tex @{
    \documentclass{article}

    \usepackage{epsfig}

    \begin{document}

    \section{introduction}

    This file shows how to include gnuplot programs directly into LaTeX.

    \begin{figure}[htb]
    \centerline{\epsfig{file=graph.ps,width=3in}}
    \caption{Graph}

    \end{figure}

    \end{document}
    @}

To generate the output call

*nuweb timings.w*

This will create all files used for the document. Calling *make*
will create the dvi file. View it with xdvi.

**Impressive!!!**

(I hope it works, let me know if you have difficulties.)

Since you are using make you can do much more, like popping up a
java application with a bouncing ball or something similar useful.

I myself have integrated a couple of different 2d graph plotting
programs and some preprocessors like latex2html to generate
automatically some html pages.

A sample LaTeX session as used in the REU class
-----------------------------------------------

A very generic example is maintained by me for the REU class. It
contains a simple LaTeX template using figures, programs, and
bibliography. The bibliography makes use of the special bibunits
package which allows to specify a references for each section
separate. This might become handy while producing a Journal out of
the collection of articles prepared in the class.

The following sample session will automatically follow all necessary
steps to produce a sample file.

-  mkdir reu
-  cd reu
-  cp /home/T10D/latex/DIST/contrib/reu-gregor\* .
-  install
-  make ps
-  make view
-  make print

The installation program will automatically figure out your user
name and change the originals appropiatly. This includes also the
renaming of the files. Make an ls and see for yourself. Feel free to
view the different files.

The following files are of importance

**reu-username.tex**

The source for the LaTeX example.

**reu-username-gloves.ps**

The postscript figure as used in the reu-username.tex

**reu-username-bib.bib**

The references as used in the reu-username.tex

**Makefile**

Generates the postscript output reu-username.ps

The best graphics program to draw pictures is tgif. If it is not
installed you might want to install it yourself and send systems a
mail asking to install it for you. The REU Teaching Assistant might
be able to do it to. xfig is not as good.

With gnuplot or xmgr/xvgr you can plot scattered 2d data. If you
need more please check out the previous information.

References can be defined via the usage of bibcard. It is relatively
simple. Please, note that you have to specify a disjunct label with
each new entry.

Source to the REU style
-----------------------

The REU style can be used as small example how to write your own
classes. It is very easy. I have placed it on the anonymous ftp
site. This way non NPAC users can download it and see how easy
LaTeXis.
`(reu.tar.gz) </web/20000817095300/http://www.npac.syr.edu/users/gregor/ftp/reu.tar.gz>`__
The template with the name *reu-usernametex* has the following form:

::

    \documentclass[twoside,11pt]{reu}

    \begin{document}

    \REUSTYLE

    \pagestyle{myheadings}

    \title{Sonic the Weatherman}

    \author{
    Jon von Neumann
            \thanks{Research Apprentice, 1995 NPAC REU Program,
                {\it jon@npac.syr.edu}; Mathematics major, Princeton University,
                {\it jon@pucc.princeton.edu}.
            }
    \and
    Gregor von Laszewski
            \thanks{Northeast Parallel Architectures Center,
                    Syracuse University, {\it gregor@npac.syr.edu}.
                   }
    }

    \REUTITLE{1996}

    \markboth{von Neumann \& von Laszewski \& Bogucz}{Sonic the Weatherman}

    \begin{abstract}
    Here comes the abstarct .... .
    \end{abstract}

    \section{Introduction}

       Here comes the motivation and introduction ... .

    \section{Proposed Work}

       Here comes the proposal for the work planed ... .
       Use subsections to structure the paper if required.

    \subsection{Visual Interpretation}

    This section is used to demonstarte the inclusion of figures.

    \FIGURE{htb}                     % placement
            {reu-username-gloves.ps} % PostScript file
            {.5}                     % zoom in relation to textwidth
            {The virtual reality dataglove is fitted on the user's hand
             and has sensors that provide input to the computer.} %caption
            {F:gloves}  % label

    Figure~\ref{F:gloves} shows .... .

    \subsection{Including Programs}

    The following example program describes what is going on in the brain:

    \NumberProgramstrue
    \begin{center}
    \begin{programbox}
    \PROC |Brain|
       \FOREACH |nerv| \in |brain|
          \FOREACH |dendrit| \in |nerv|
             | get the values on the input synapses |
             | send new valoues to output synapses |
          \END ~ \FOREACH \untab
       \END ~ \FOREACH \untab
       |switch of and sleep|
    \END ~ \PROC

    \end{programbox}
    \end{center}


    \REFERENCES{reu-username.bib}

    \end{document}

Expanding your own LaTeX environment
------------------------------------

What if you found in a nice book a style or class you would like to
use and it is not installed at your site? One way of doing it is to
tell your systems administrator to install it but this could take
years ;-) because they are usually to busy to keep the machines
running.

Why not install it yourself!

In a previous section I explained the TEXINPUTS path. The one given
assumes that you have a 'tex' directory under your home directory.
In this directory you can put all kinds of extensions.

But where do you get the files from?

This is easy. Use CTAN. below I have given a sample session to
anonymously ftp a style file. The commands given in ``typewriter``
font are the input commands. while the once in roman are the
response from the ftp server. Please use the CTAN which is closest
to you

**US**

`TeX and LaTeX
Archives </web/20000817095300/http://www.cdrom.com/pub/tex/ctan/CTAN.sites>`__

**UK**

ftp.tex.ac.uk

**Germany**

ftp.dante.de

**Sample Session**

``ncftp ftp.tex.ac.uk``

Guest login ok, send your complete e-mail address as password.
Welcome, archive user! This is an FTP server for the UK TeX Archive.
If you have any unusual problems, please report them via e-mail to
ctan-uktex.ac.uk. If you do have problems, please try using a dash
(-) as the first character of your password - this will turn off the
continuation messages that may be confusing your ftp client. This is
the UK node of the Comprehensive TeX Archive Network (CTAN). Other
participating hosts in the CTAN and their root CTAN directories
include:

`TeX and LaTeX
Archives </web/20000817095300/http://www.cdrom.com/pub/tex/ctan/CTAN.sites>`__

ftp.dante.de tex-archive

In order to reduce network load, it is recommended that you use the
CTAN host which is located in the closest proximity to your site.

IMPORTANT NOTE:

This ftp server supports dynamic creation of zip, zoo, or tar.gz
archives. If you want the contents of a directory (\*and all its
subdirectories\*), go to the level above and \`get' the directory
name suffixed by .zip, zoo or .tar.gz e.g.

cd /pub/archive/macros/latex/contrib/supported

binary

get rotating.zip

will put together the whole "rotating" package for you.

Guest login ok, access restrictions apply.

Logged into ftp.tex.ac.uk.

Please read the file README

it was last modified on Thu Jan 18 10:23:46 1996 - 117 days ago

NcFTP 1.8.6 (Octboer 30, 1994) by Mike Gleason, NCEMRSoft.

ftp.tex.ac.uk:

ncftp>\ ``cd tex-archive``

ncftp>\ ``quote cite index bibunits.sty``

500 'CITE index bibunits.sty': command not understood.

ftp.tex.ac.uk:/ctan/tex-archive/macros/latex/contrib/supported/citen

ncftp>\ ``mget macros/latex209/contrib/misc/bibunits.sty``

ncftp>\ ``quit``

That was it. Now you have the bibunits.sty file in your current
directory. Place it in ``~``/tex and you can use it. This way you
can download many many files. Please, coordinate with other users in
order to avoid downloading all the same style files.







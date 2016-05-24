

Python
======

Print
-----------------------------------------------------------------
.. runblock:: pycon

   >>> print "Hello Cloud"

Comments
-----------------------------------------------------------------

Simple comment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
.. runblock:: pycon

   >>> # this is a comment

Multiline Comment with "
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
::

   """ 
   this is a multiline coment 
   """

Multiline Comment with '
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
::

   '''
   this is a multiline coment
   '''

Variables
-----------------------------------------------------------------
.. runblock:: pycon

   >>> flavor = "tiny"
   ... print flavor

Changing the variable Value
-----------------------------------------------------------------
.. runblock:: pycon

   >>> flavor = "large"
   ... print flavor

List
-----------------------------------------------------------------
.. runblock:: pycon

    >>> list = [1, 2, 3, 4, 5, 6]
    ... print list[0]
    ... print list[len(list)-1]
    ... print list[2:5]



For Loop
-----------------------------------------------------------------
.. runblock:: pycon

    >>> list = [1, 2, 3, 4, 5, 6]
    ... for element in list:
    ...   print element

Arithmetic Operators
-----------------------------------------------------------------
.. runblock:: pycon

    >>> list = [1, 2, 3, 4, 5, 6]
    ... print sum(list)
    ... print min(list)
    ... print max(list)
    ... print sum(list)/len(list)
    ... print sum(list)/float(len(list))

Function to do calculations
-----------------------------------------------------------------
.. runblock:: pycon

    >>> def f(x,y):
    ...   return x+y+ y*y + x*x
    ...
    ... print f(1,2)
    ... print f(4,6)


Functions for String Manipulation
-----------------------------------------------------------------
.. runblock:: pycon

    >>> def name(firstname, lastname):
    ...   return "%s %s" % (firstname, lastname)
    ...
    ... def reversename(firstname, lastname):
    ...   return "%s, %s" % (lastname, firstname)
    ...
    ... print name('Gregor', 'von Laszewski')
    ... print reversename('Gregor', 'von Laszewski')

If Condition
-----------------------------------------------------------------
.. runblock:: pycon

   >>> flavor = "tiny"
   ... if flavor == "tiny":
   ...    print("vanilla has a tiny flavor")
   ... elif flavor == "large":
   ...    print("chocolate has a large flavor")
   ... else:
   ...    print("other flavors I do not like")

For
------------------------------------------------------------------

.. runblock:: pycon

   ... flavors = ['tiny', 'medium', 'large']
   ... for flavor in flavors:
   ...   print flavor



Classes
-------

.. code-block:: python

   class dog(object):

	  def __init(self, args):
		 print(args)

	  @staticmethod
	  def bone(args):
	 print(args)

	  def bread(self, args):
		 print (args)

	   @classmethod
	   def kind(cls, args):
		  print (args)
	  print ("mamal")
	  
1. What is the difference between static and class methods?
2. What are instances?
3. Add a __main__
4. Add some uses
5. Come up with a better class that uses class, static and instance methods.

dicts
-----

.. runblock:: pycon

  >>> d = {
  ...   "a": "value1",
  ...   "b": "value2",   
  ... }
  ... print(d["a"])


dotdict
-------

https://github.com/cloudmesh/client/blob/master/cloudmesh_client/common/dotdict.py


.. runblock:: pycon

	>>> from cloudmesh_client.common.dotdict import dotdict
	... d = dotdict({
	...   "a": "value1",
	...   "b": "value2",   
	... })
	... print (d.a)
	... print(d["a"])  	

docopts
-------

* http://docopt.org/

* https://github.com/docopt/docopt


hostlists
---------

.. runblock:: pycon

	>>> from cloudmesh_client.common.hostlist import Parameter
	... elements = Parameter.expand("gregor-[001-002,005-006]")
	... print (elements)

	... for element in elements:
	...    print (element)





mysqlalchemy
------------

django
------

cloudmesh client library
------------------------------

Console
^^^^^^^

.. runblock:: pycon
	      
	>>> from cloudmesh_client.shell.console import Console

	... Console.ok("everything works")
	... Console.error("this is an error")
	... Console.msg("this is a message")

Util
^^^^

Common
^^^^^^

Printer
^^^^^^^


**********************************************************************
Just Enough Python for the Cloud
**********************************************************************


* http://www.korokithakis.net/tutorials/python/

and here is one that you can do on a web browser in case you have not installed python on your computer

* http://www.afterhoursprogramming.com/tutorial/Python/Introduction/

Terminal
===================================================================

* http://www.howtogeek.com/140679/beginner-geek-how-to-start-using-the-linux-terminal/


OS Specific
===================================================================

Linux
----------------------------------------------------------------------

OS X
----------------------------------------------------------------------

::

   uname -a
   Darwin pro-2013.local 12.3.0 Darwin Kernel Version 12.3.0: Sun Jan 6 22:37:10 PST 2013; root:xnu-2050.22.13~1/RELEASE_X86_64 x86_64

::

   >>> python
   Python 2.7.2 (default, Oct 11 2012, 20:14:37) 
   [GCC 4.2.1 Compatible Apple Clang 4.0 (tags/Apple/clang-418.0.60)] on darwin


Windows
----------------------------------------------------------------------

todo

Local
===================================================================
::

   $ man python

Ecosystem
===================================================================

.. todo:: mind the virtualenv

pypi
----------------------------------------------------------------------
The Python Package Index is a large repository of software for the
Python programming language containing a large number of packages
[link]. The nice think about pipy is that many packages can be
installed with the program 'pip'.

To do so you have to locate the <package_name> for example with the
serach function in pypi and say on the commandline::

    pip install <package_name>

where pagage_name is the string name of the package. an example would
be the package called cloudmesh_client which you can install with::

   pip install cloudmesh_client
 
If all goes well the package will be installed.

github
----------------------------------------------------------------------

todo

Excersises
==================

#. write a program that uses loops over both x and y coordinates while
   x is in 1,2,3,4,5 and y is in 5,4,3,2,1 and prints the x and y
   coordinate

#. write a program that sums up all values in x and y

#. write a program just like the first task but does not print values where x is equal to 2 and y is equal to 4

#. write a function that takes in a word and returns  it in reverse order

#. provide a program that uses dicts

#. read up on classes.

#. we will create an icecream machine that produces icecream in
   with tiny flavor, medium flavor and large flavor.
	
#. in addition the icecream cone will be wrapped into some paper that
   has an image on it. Images will be Penguin, Apple, Emperor, King


Orange
======

Orange is a component-based data mining software. It includes a range of data
visualization, exploration, preprocessing and modeling techniques. It can be
used through a nice and intuitive user interface or, for more advanced users,
as a module for Python programming language.

Installing
----------

To build and install Orange run::

    pip install -r requirements.txt
    python setup.py install


Running Tests
-------------
To test Orange with included unit tests run::

    python setup.py test

Starting Orange Canvas
----------------------

Start orange canvas from the command line with::

     orange-canvas

Installation for Developers
---------------------------

To install in `development mode`_ run::

    python setup.py develop
   
.. _development mode: http://packages.python.org/distribute/setuptools.html#development-mode

windows 7 with gcc:
	c:\Python32\python.exe setup.py build_ext -i --compiler=mingw32

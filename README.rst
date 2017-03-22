pyRegurgitator - Tools for analysing python code
===================================================


Website/docs: http://pythonhosted.org/pyRegurgitator

Code on github: https://github.com/schettino72/pyRegurgitator/

Supported versions: Python 3.4 only

Tools
=======

 * asdlview: generates a HTML page with python's ASDL info.
 * astview: generates a HTML page with a python module's AST info.
 * py2xml: convert python code to XML.

Check the `docs <http://pythonhosted.org/pyRegurgitator>`_


license
=======

The MIT License
Copyright (c) 2010-2014 Eduardo Naufel Schettino

see LICENSE file


developers / contributors
==========================

- Eduardo Naufel Schettino


install
=======

Install using pip3.4
::

 $ pip3.4 install pyRegurgitator
 
Or inside python3.4 virtualenv

::

 $ virtualenv -p /path/to/python3.4 venv
 $ source venv/bin/activate
 $ pip install pyRegurgitator

or download and::

 $ python setup.py install


tests
=======

To run the tests::

  $ py.test

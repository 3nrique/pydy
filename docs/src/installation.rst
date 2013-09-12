Installation
------------


There are different methods you can use to get PyDyViz up and running for your system.

Dependencies:

1) Python >=2.5
2) SymPy >=0.7.2
3) NumPy >=
4) SciPy >=

SciPy is used by the Code Generator module for numerical integration of Equations of Motions.
So not exactly a dependency for PyDyViz, but is required anyways for Code Generator to work.

Source
======

PyDyViz can be installed from source via archive. Download the latest release archive from here.
Extract the archive and cd into the directory. 
Issue the following command from command line::

    $ python setup.py install

It should get the PyDyViz up and running.
You can check the installation by running the following command from Python Interpreter::

    >>>import pydy_viz

If it does not throws any error/traceback, it means that PyDyViz is installed.    
        

Git
===

If you are a developer, or looking for the latest features without waiting for another release, you can install the development version 
from the git repository.

Issue the following command from terminal::

    $ git clone git://github.com/PythonDynamics/pydy-viz.git

and then change directory to the cloned directory and run setup.py install::

    $ cd pydy-viz
    $ python setup.py install
    
and you will have the latest development version on board.
    


Python Package Index
====================

You can also install PyDyViz from Python Package Index using pip or easy_install

Its as easy as opening a terminal and typing in::

    $ pip install pydy_viz
    
or for easy_install::

    $ easy_install pydy_viz   





PyQtGraph
=========

A pure-Python graphics library for PyQt/PySide

Copyright 2012 Luke Campagnola, University of North Carolina at Chapel Hill

<http://www.pyqtgraph.org>

Maintainer
----------

  * Luke Campagnola   ('luke.campagnola@%s.com' % 'gmail')

Contributors
------------

  * Megan Kratz
  * Paul Manis
  * Ingo Breßler
  * Christian Gavin
  * Michael Cristopher Hogg
  * Ulrich Leutner
  * Felix Schill
  * Guillaume Poulin
  * Antony Lee
  * Mattias Põldaru

Requirements
------------

  * PyQt 4.7+ or PySide
  * python 2.6, 2.7, or 3.x
  * numpy, scipy
  * For 3D graphics: pyopengl
  * Known to run on Windows, Linux, and Mac.

Support
-------

  Post at the [mailing list / forum](https://groups.google.com/forum/?fromgroups#!forum/pyqtgraph)

Installation Methods
--------------------

  * To use with a specific project, simply copy the pyqtgraph subdirectory
      anywhere that is importable from your project. PyQtGraph may also be
      used as a git subtree by cloning the git-core repository from github.
  * To install system-wide from source distribution:
        `$ python setup.py install`
  * For instalation packages, see the website (pyqtgraph.org)

Documentation
-------------

There are many examples; run `python -m pyqtgraph.examples` for a menu.

Some (incomplete) documentation exists at this time.
  * Easiest place to get documentation is at <http://www.pyqtgraph.org/documentation>
  * If you acquired this code as a .tar.gz file from the website, then you can also look in
      doc/html.
  * If you acquired this code via GitHub, then you can build the documentation using sphinx.
      From the documentation directory, run:
          `$ make html`
  
Please feel free to pester Luke or post to the forum if you need a specific
  section of documentation to be expanded.

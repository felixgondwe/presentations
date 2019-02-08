.. readdocs-example documentation master file, created by
   sphinx-quickstart on Fri Feb  8 10:42:49 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to readdocs-example's documentation!
============================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   support
   cookbook
   changelog

============
Installation
============

Install sphinx to make life easy. It's  a cool tool

Sphinx will parse your .rst files to html in the build folder.
To build html simply run the following in your terminal

.. code-block:: bash
   :linenos:
   
   make html

Other way to include code::
    import math 
    print(math.rand())

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

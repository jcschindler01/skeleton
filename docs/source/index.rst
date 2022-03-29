.. skeleton documentation master file, created by
   sphinx-quickstart on Fri Mar 25 12:56:13 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

skeleton
================================


Welcome!
--------

Hello and welcome to the skeleton package!

This package is a skeleton for Python packages allowing:
  - ``pip`` distribution and installation,
  - sphinx/readthedocs documentation.

See:
   - `GitHub <https://github.com/jcschindler01/skeleton>`_.
   - `Docs <https://skeleton-jcschindler01.readthedocs.io/>`_.
   - `TestPyPi Distro <https://test.pypi.org/project/skeleton-JCSCHINDLER01/>`_.


Dev Tips/Steps:
  - Clone from GitHub
  - Local install with ``pip install -e .`` 
  - To release: ``git tag``, ``python -m build``, `upload <https://packaging.python.org/en/latest/tutorials/packaging-projects/#uploading-the-distribution-archives>`_
  - To document: Set up readthedocs to auto update on push. Manually rerun apidoc-rebuild as needed.
  - To test: Download and test in a venv.



Getting Started
---------------

If this were uploaded on PyPi (it's not, but you can download from TestPyPi link above), you would install the package with::

   pip install skeleton

Then, visit the tutorial to learn how to use it!


Table of Contents
-----------------

.. toctree::
   :maxdepth: 2

   Welcome! <welcome>
   Tutorial <TUTORIAL/00-overview>
   API Reference <API/apidoc/modules>


Search
------


* :ref:`Modules <modindex>`
* :ref:`Index <genindex>`
* :ref:`Search <search>`

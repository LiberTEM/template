.. {{ cookiecutter.repo_name }} documentation master file, created by
   sphinx-quickstart on Wed May  2 15:54:09 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

{{ cookiecutter.repo_name }}
============================

.. include:: ../../README.rst
..   see also: https://muffinresearch.co.uk/selectively-including-parts-readme-rst-in-your-docs/
..   later, maybe :start-after: inclusion-marker-do-not-remove


Documentation
=============

.. toctree::
   :maxdepth: 2
   :caption: Contents:
   
   changelog
   acknowledgements


Indices and tables
------------------

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

Citations
---------

.. bibliography:: references-{{ cookiecutter.package_name }}.bib

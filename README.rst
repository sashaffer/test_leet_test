========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |appveyor| |requires|
        |
        | |scrutinizer| |codacy| |codeclimate|
    * - package
      - | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/python-leet-test/badge/?style=flat
    :target: https://python-leet-test.readthedocs.io/
    :alt: Documentation Status

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/sashaffer/python-leet-test?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/sashaffer/python-leet-test

.. |requires| image:: https://requires.io/github/sashaffer/python-leet-test/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/sashaffer/python-leet-test/requirements/?branch=master

.. |codacy| image:: https://img.shields.io/codacy/grade/ls.svg
    :target: https://www.codacy.com/app/sashaffer/python-leet-test
    :alt: Codacy Code Quality Status

.. |codeclimate| image:: https://codeclimate.com/github/sashaffer/python-leet-test/badges/gpa.svg
   :target: https://codeclimate.com/github/sashaffer/python-leet-test
   :alt: CodeClimate Quality Status

.. |commits-since| image:: https://img.shields.io/github/commits-since/sashaffer/python-leet-test/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/sashaffer/python-leet-test/compare/v0.0.0...master


.. |scrutinizer| image:: https://img.shields.io/scrutinizer/quality/g/sashaffer/python-leet-test/master.svg
    :alt: Scrutinizer Status
    :target: https://scrutinizer-ci.com/g/sashaffer/python-leet-test/


.. end-badges

An example package. Generated with cookiecutter-pylibrary.

Installation
============

::

    pip install leet-test

You can also install the in-development version with::

    pip install https://github.com/sashaffer/python-leet-test/archive/master.zip


Documentation
=============


https://python-leet-test.readthedocs.io/


Development
===========

To run all the tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox

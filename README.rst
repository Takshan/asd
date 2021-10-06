========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/asd/badge/?style=flat
    :target: https://asd.readthedocs.io/
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.com/takshan/asd.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.com/github/takshan/asd

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/takshan/asd?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/takshan/asd

.. |requires| image:: https://requires.io/github/takshan/asd/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/takshan/asd/requirements/?branch=master

.. |codecov| image:: https://codecov.io/gh/takshan/asd/branch/master/graphs/badge.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/takshan/asd

.. |version| image:: https://img.shields.io/pypi/v/asd.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/asd

.. |wheel| image:: https://img.shields.io/pypi/wheel/asd.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/asd

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/asd.svg
    :alt: Supported versions
    :target: https://pypi.org/project/asd

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/asd.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/asd

.. |commits-since| image:: https://img.shields.io/github/commits-since/takshan/asd/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/takshan/asd/compare/v0.0.0...master



.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: BSD 2-Clause License

Installation
============

::

    pip install asd

You can also install the in-development version with::

    pip install https://github.com/takshan/asd/archive/master.zip


Documentation
=============


https://asd.readthedocs.io/


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

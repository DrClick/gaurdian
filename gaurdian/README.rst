========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis|
        | |coveralls| |codecov|
        | |scrutinizer| |codacy|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/gaurdian/badge/?style=flat
    :target: https://readthedocs.org/projects/gaurdian
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.com/drclick/gaurdian.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.com/github/drclick/gaurdian

.. |coveralls| image:: https://coveralls.io/repos/drclick/gaurdian/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/drclick/gaurdian

.. |codecov| image:: https://codecov.io/gh/drclick/gaurdian/branch/master/graphs/badge.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/drclick/gaurdian

.. |codacy| image:: https://img.shields.io/codacy/grade/[Get ID from https://app.codacy.com/app/drclick/gaurdian/settings].svg
    :target: https://www.codacy.com/app/drclick/gaurdian
    :alt: Codacy Code Quality Status

.. |version| image:: https://img.shields.io/pypi/v/gaurdian.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/gaurdian

.. |wheel| image:: https://img.shields.io/pypi/wheel/gaurdian.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/gaurdian

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/gaurdian.svg
    :alt: Supported versions
    :target: https://pypi.org/project/gaurdian

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/gaurdian.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/gaurdian

.. |commits-since| image:: https://img.shields.io/github/commits-since/drclick/gaurdian/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/drclick/gaurdian/compare/v0.0.0...master


.. |scrutinizer| image:: https://img.shields.io/scrutinizer/quality/g/drclick/gaurdian/master.svg
    :alt: Scrutinizer Status
    :target: https://scrutinizer-ci.com/g/drclick/gaurdian/


.. end-badges

An advanced package for nuclear war

* Free software: MIT license

Installation
============

::

    pip install gaurdian

You can also install the in-development version with::

    pip install https://github.com/drclick/gaurdian/archive/master.zip


Documentation
=============


https://gaurdian.readthedocs.io/


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

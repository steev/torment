Description
===========

A Study in Fixture Based Testing Frameworking

A (probably) new structure for fixture organization and integration into
unittest.  A minimal layer on top of unittest that allows declarative fixtures
to define new tests.  Designed for unit testing but explores new integration
testing patterns as well.

Installation
============

This pakcage is stored in PyPI and can be installed the standard way::

    pip install torment

The latest release available is:

.. image:: https://badge.fury.io/py/torment.png
    :target: http://badbe.fury.io/py/torment

Using Torments
==============

Usage of this package is documented with sphinx and available at
http://torment.readthedocs.org/en/latest/

Developing Torment
==================

If you would prefer to clone this package directly from git or assist with
development, the URL is https://github.com/alunduil/torment.

Torment is tested continuously by Travis-CI and running the tests is quite
simple::

    flake8
    nosetests

The current status of the build is:

.. image:: https://secure.travis-ci.org/alunduil/torment.png?branch=master
    :target: http://travis-ci.org/alunduil/torment

Authors
=======

* Alex Brandt <alunduil@alunduil.com>

Known Issues
============

Known issues can be found in the github issue list at
https://github.com/alunduil/torment/issues.

Troubleshooting
===============

If you need to troubleshoot an issue or submit information in a bug report, we
recommend obtaining logs (probably from nose) while enabling log capture of
torment.  Torment uses logging to submit informational and debug messages but
also sets a NullHandler by default.

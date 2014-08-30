# mymv

[![Build Status](https://secure.travis-ci.org/michaeljoseph/mymv.png)](http://travis-ci.org/michaeljoseph/mymv)
[![Stories in Ready](https://badge.waffle.io/michaeljoseph/mymv.png?label=ready)](https://waffle.io/michaeljoseph/mymv) [![pypi version](https://badge.fury.io/py/mymv.png)](http://badge.fury.io/py/mymv)
[![# of downloads](https://pypip.in/d/mymv/badge.png)](https://crate.io/packages/mymv?version=latest)
[![code coverage](https://coveralls.io/repos/michaeljoseph/mymv/badge.png?branch=master)](https://coveralls.io/r/michaeljoseph/mymv?branch=master)

## Overview

Switch the host of MySQL database with slaving

* features
* and stuff 

## Usage

Install `mymv`:

    pip install mymv

Then execute the sample cli:

   mymv

## Documentation

[API Documentation](http://mymv.rtfd.org)

## Testing

Install development requirements:

    pip install -r requirements.txt

Tests can then be run with:

    nosetests

Lint the project with:

    flake8 mymv tests

## API documentation

Generate the documentation with:

    cd docs && PYTHONPATH=.. make singlehtml

To monitor changes to Python files and execute flake8 and nosetests
automatically, execute the following from the root project directory:

    stir
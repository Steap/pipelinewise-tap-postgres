# pipelinewise-tap-postgres

[![PyPI version](https://badge.fury.io/py/pipelinewise-tap-postgres.svg)](https://badge.fury.io/py/pipelinewise-tap-postgres)

[Singer](https://www.singer.io/) tap that extracts data from a [PostgreSQL](https://www.postgresql.com/) database and produces JSON-formatted data following the [Singer spec](https://github.com/singer-io/getting-started/blob/master/docs/SPEC.md).

This is a [PipelineWise](https://transferwise.github.io/pipelinewise) compatible tap connector.

## How to use it

The recommended method of running this tap is to use it from [PipelineWise](https://transferwise.github.io/pipelinewise). When running it from PipelineWise you don't need to configure this tap with JSON files and most of things are automated. Please check the related documentation at [Tap Postgres](https://transferwise.github.io/pipelinewise/connectors/taps/postgres.html)

If you want to run this [Singer Tap](https://singer.io) independently please read further.

### Install and Run

First, make sure Python 3 is installed on your system or follow these
installation instructions for [Mac](http://docs.python-guide.org/en/latest/starting/install3/osx/) or
[Ubuntu](https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-local-programming-environment-on-ubuntu-16-04).

### Configuration


---

Based on Stitch documentation

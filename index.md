---
layout: default
---

The [cloudspannerecosystem](https://github.com/cloudspannerecosystem) GitHub
organization hosts a collection of public repositories that are owned-by and
developed-for the Cloud Spanner user community.

All the hosted projects are based on open source community contributions. We'd
love for you to report issues, file feature requests, and send pull requests.
See below for details on [contributions](#contributing). Note that none of the
projects are officially supported by Google as part of the Cloud Spanner
product.

Please [let us know](https://gitter.im/cloudspannerecosystem/community) if
you're interested in getting your project hosted! This will help other Cloud
Spanner developers find your project and contribute to it.

[![Gitter](https://badges.gitter.im/cloudspannerecosystem/community.svg)](https://gitter.im/cloudspannerecosystem/community)

# Projects

### SampleDB

This application allows you to quickly get a sample database into Cloud Spanner.
It does so by loading data from a CSV file into a new Cloud Spanner database.

* [GitHub repository](https://github.com/cloudspannerecosystem/sampledb)

### App Engine sample

This sample demonstrates how to use Cloud Spanner from the App Engine Standard
with Java 11 environment.

* [GitHub repository](https://github.com/cloudspannerecosystem/appengine-java-sample)

### HarbourBridge

HarbourBridge is a stand-alone tool for Cloud Spanner evaluation, using data
from an existing PostgreSQL database. The tool ingests pg_dump output,
automatically builds a Spanner schema, and creates a new Spanner database
populated with data from pg_dump.

This tool is under active development and will support other source databases in
the future. If you would like to get involved, please check out the following
links:
* [GitHub repository](https://github.com/cloudspannerecosystem/harbourbridge)
* [whitepaper](https://github.com/cloudspannerecosystem/harbourbridge/blob/master/whitepaper.md)
* [open issues](https://github.com/cloudspannerecosystem/harbourbridge/issues)

### spanner-cli

spanner-cli is an interactive command line tool, inspired by the `mysql` utility.
It allows you to control your Cloud Spanner databases with idiomatic database
commands, such as `SHOW TABLES` or `SELECT/INSERT/UPDATE/DELETE`.

* [GitHub repository](https://github.com/cloudspannerecosystem/spanner-cli)

# Contributing

We'd love to accept your patches and contributions! For details, please check
the `README.md` and `docs/contributing.md` files in the repository of the
project that you're interested in.

Please get in touch if you're interested in starting a new project or moving an
existing repository to this organization! All projects hosted here need to have
good test coverage. We're happy to help you with setting up unit and integration
tests, but we rely on your contributions for continued maintenance.

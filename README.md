# jinja2cli

The bundle for Jinja2 templates via command line

## Installation

To make python zip package:

```sh
$ cd jinja2cli
$ zip -r ../jinja2cli.zip .
$ cd ..
$ mv jinja2cli.zip j2cli
$ $ python j2cli
Usage: j2cli [options] <input template> <input data>

Options:
  --version             show program's version number and exit
  -h, --help            show this help message and exit
  --format=FORMAT       format of input variables: auto, ini, json,
                        querystring, yaml, yml
  -e EXTENSIONS, --extension=EXTENSIONS
                        extra jinja2 extensions to load
```
[![Downloads](https://pepy.tech/badge/piedpy)](https://pepy.tech/project/piedpy)
[![PyPI version](https://badge.fury.io/py/piedpy.svg)](https://badge.fury.io/py/piedpy)
[![Wheel](https://img.shields.io/pypi/wheel/piedpy.svg)](https://pypi.com/project/piedpy)
[![pyimp](https://img.shields.io/pypi/implementation/piedpy.svg)](https://pypi.com/project/piedpy)
[![RTD](https://readthedocs.org/projects/piedpy/badge/)](https://piedpy.readthedocs.io)
[![Twitter Follow](https://img.shields.io/twitter/follow/gerrishon_s.svg?style=social)](https://twitter.com/gerrishon_s)

`Forever Scalable`

**piedpy** is a Python based CLI toolkit for MySQL with auto-completion, key binders and syntax highlighting.

## Compatibility
piedpy works flawlessly  with Linux, OSX, and Windows and requires Python `3.8` or later. 


## Features

* Auto-completion
* Syntax highlighting
* Smart-completion (enabled by default) will suggest context-sensitive completion.
    - `SELECT * FROM <tab>` will only show table names.
    - `SELECT * FROM users WHERE <tab>` will only show column names.
* Support for multiline queries.
* Favorite queries with optional positional parameters. Save a query using
  `\fs alias query` and execute it with `\f alias` whenever you need.
* Timing of sql statements and table rendering.
* Config file is automatically created at ``~/.piedpyrc`` at first launch.
* Log every query and its results to a file (disabled by default).
* Pretty prints tabular data (with colors!)
* Support for SSL connections

## Getting Started
### Installation
You can install quo via the Python Package Index (PyPI)

```
pip install -U piedpy

```

### Usage

```console

piedpy --help
```
![Usage](https://github.com/scalabli/piedpy/blob/main/docs/images/usage.png)


### Configuration

For more information on using and configuring piedpy, [check out
our documentation](https://piedpy.rtfd.io).                      

## Donate🎁

In order to for us to maintain this project and grow our community of contributors.
[Donate](https://ko-fi.com/scalabli)

## Getting Help

### Community

For discussions about the usage, development, and the future of quo, please join our Google community

* [Community👨‍👩‍👦‍👦](https://groups.google.com/forum/#!forum/secretum)

## Resources

### Bug tracker

If you have any suggestions, bug reports, or annoyances please report them
to our issue tracker at 
[Bug tracker](https://github.com/scalabli/piedpy/issues/) or send an email to:

 📥 secretum@googlegroups.com


## License📑

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  
This software is licensed under the `MIT License`. See the [License](https://github.com/scalabli/piedpy/blob/master/LICENSE) file in the top distribution directory for the full license text.


## Code of Conduct
Code of Conduct is adapted from the Contributor Covenant,
version 1.2.0 available at
[Code of Conduct](http://contributor-covenant.org/version/1/2/0/)

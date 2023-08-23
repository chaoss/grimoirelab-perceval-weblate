# perceval-weblate [![Build Status](https://github.com/chaoss/grimoirelab-perceval-weblate/workflows/tests/badge.svg)](https://github.com/chaoss/grimoirelab-perceval-weblate/actions?query=workflow:tests+branch:master+event:push) [![Coverage Status](https://img.shields.io/coveralls/chaoss/grimoirelab-perceval-weblate.svg)](https://coveralls.io/r/chaoss/grimoirelab-perceval-weblate?branch=master) [![PyPI version](https://badge.fury.io/py/perceval-weblate.svg)](https://badge.fury.io/py/perceval-weblate)

Bundle of Perceval backends for Weblate.

## Backends

The backends currently managed by this package support the next repositories:

* Weblate

## Requirements

 * Python >= 3.8

You will also need some other libraries for running the tool, you can find the
whole list of dependencies in [pyproject.toml](pyproject.toml) file.

## Installation

There are several ways to install perceval-weblate on your system: packages or source 
code using Poetry or pip.

### PyPI

perceval-weblate can be installed using pip, a tool for installing Python packages. 
To do it, run the next command:
```
$ pip install perceval-weblate
```

### Source code

To install from the source code you will need to clone the repository first:
```
$ git clone https://github.com/chaoss/grimoirelab-perceval-weblate
$ cd grimoirelab-perceval-weblate
```

Then use pip or Poetry to install the package along with its dependencies.

#### Pip
To install the package from local directory run the following command:
```
$ pip install .
```
In case you are a developer, you should install perceval-weblate in editable mode:
```
$ pip install -e .
```

#### Poetry
We use [poetry](https://python-poetry.org/) for dependency management and 
packaging. You can install it following its [documentation](https://python-poetry.org/docs/#installation).
Once you have installed it, you can install perceval-weblate and the dependencies in 
a project isolated environment using:
```
$ poetry install
```
To spaw a new shell within the virtual environment use:
```
$ poetry shell
```

## Examples

### Weblate

```
$ perceval weblate
```

## License

Licensed under GNU General Public License (GPL), version 3 or later.

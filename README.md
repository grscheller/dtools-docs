# Developer Tools

Python project of packages to aid in general software development.

These Python developer libraries consist of Python PyPI namespace
packages all under the **dtools.** "namespace."

* circular-array - An indexable double sided circular array 
* datastructures - Data structures geared to algorithms
* fp - Pythonic functional programming tools

The purpose of this collection of PyPI namespace projects is to host
and provide infrastructure for my Python developer tools.

## Documentation

Detailed documentation for the developer tools project can he found
[here](https://grscheller.github.io/dtools-docs/).

## PyPI

Projects on PyPi:

* [dtools.circular-array](https://pypi.org/project/grscheller.circular-array/)
* [dtools.datastructures](https://pypi.org/project/dtools.datastructures/)
* [dtools.fp](https://pypi.org/project/grscheller.fp/)

## Source Code

GitHub source code repos:

* [dtools-circular-array](https://github.com/grscheller/dtools-circular-array/)
* [dtools-datastructures](https://github.com/grscheller/dtools-datastructures/)
* [dtools-fp](https://github.com/grscheller/dtools-fp/)

## Documentation Generation

Using the dtools.fp project as an example, here is how one generates the
docs with [pdoc](https://pypi.org/project/pdoc/).

```bash
   $ cd docs/integer_math/API/development/
   $ rm -r bm/ index.html search.js
   $ PYTHONPATH=:~/devel/pypi/dtools/dtools-fp/src
   $ pdoc -o . dtools.fp
```


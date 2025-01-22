# Developer Tools

Python project of packages to aid in general software development.

These Python developer tools consist of Python PyPI namespace packages all
under the **dtools.** "namespace."

* dtools.circular-array - An indexable double sided circular array 
* dtools.datastructures - Data structures geared to algorithms
* dtools.fp - Pythonic functional programming tools

The purpose of this collection of PyPI namespace projects is to host
and provide infrastructure for my Python developer tools.

## Documentation

Detailed documentation for the developer tools project can he found
[here](https://grscheller.github.io/dtools-docs/).

## Source Code

GitHub source code subpackage repos:

* [dtools.circular-array](https://github.com/grscheller/dtools-circular-array)
* [dtools.datastructures](https://github.com/grscheller/dtools-datastructures)
* [dtools.fp](https://github.com/grscheller/dtools-fp)

## Documentation Generation

Using the dtools.fp project as an example, here is how one generates the
docs with [pdoc](https://pypi.org/project/pdoc/).

```bash
   $ cd docs/integer_math/API/development/
   $ rm -r bm/ index.html search.js
   $ PYTHONPATH=:~/devel/pypi/dtools/dtools-fp/src
   $ pdoc -o . dtools.fp
```


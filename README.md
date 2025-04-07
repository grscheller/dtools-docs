# Developer Tools

Python collection of packages to aid in general software development.

These Python developer libraries consist of Python PyPI namespace
packages all under the **dtools.** "namespace."

- dtools.circular-array: An indexable double sided circular array
- dtools.fp: Pythonic functional programming tools
- dtools.queues: Queue/Stack based datastructures geared to algorithms
- dtools.tuple: Tuple based datastructures

## Documentation

Detailed documentation for the developer tools project can he found
[here](https://grscheller.github.io/dtools-docs/).

## PyPI

Projects on PyPi:

- [dtools.circular-array](https://pypi.org/project/dtools.circular-array/)
- [dtools.fp](https://pypi.org/project/dtools.fp/)
- [dtools.queues](https://pypi.org/project/dtools.queues/)
- [dtools.tuples](https://pypi.org/project/dtools.tuples/)
- [dtools.datastructures](https://pypi.org/project/dtools.datastructures/) **deprecated**

## Source Code

GitHub source code repos:

- [dtools-circular-array](https://github.com/grscheller/dtools-circular-array/)
- [dtools-fp](https://github.com/grscheller/dtools-fp/)
- [dtools-queues](https://github.com/grscheller/dtools-queues/)
- [dtools-tuoles](https://github.com/grscheller/dtools-tuoles/)
- [dtools-datastructures](https://github.com/grscheller/dtools-datastructures/) **deprecated**

## Documentation Generation

Using the dtools.ftuples project as an example, here is how one generates the
docs with [pdoc](https://pypi.org/project/pdoc/).

```bash
    $ cd ~/devel/pypi/dtools/dtools-docs/tuples/API/development/
    $ rm -r dtools/ index.html search.js
    $ PYTHONPATH=~/devel/pypi/dtools/dtools-queues/src:~/devel/pypi/dtools/dtools-fp/src:
    $ pdoc -o . dtools.tuples
```

# Developer Tools

Collection of Python packages to aid in general software development.

These Python developer libraries consist of Python PyPI namespace
packages all under the **dtools.** "namespace."

## PyPI `dtools.` Namespace Projects

### Projects on PyPi

- [dtools.circular-array](https://pypi.org/project/dtools.circular-array/)
- [dtools.fp](https://pypi.org/project/dtools.fp/)
- [dtools.queues](https://pypi.org/project/dtools.queues/)
- [dtools.tuples](https://pypi.org/project/dtools.tuples/)
- [dtools.datastructures](https://pypi.org/project/dtools.datastructures/) **deprecated**

### Source Code on GitHub

- [dtools-circular-array](https://github.com/grscheller/dtools-circular-array/)
- [dtools-fp](https://github.com/grscheller/dtools-fp/)
- [dtools-queues](https://github.com/grscheller/dtools-queues/)
- [dtools-tuoles](https://github.com/grscheller/dtools-tuoles/)
- [dtools-datastructures](https://github.com/grscheller/dtools-datastructures/) **deprecated**

### Detailed Documentation

Detailed pdoc generated documentation for the
[Developer Tools](https://grscheller.github.io/dtools-docs/)
PyPI projects.

#### Documentation Generation

Using the dtools.ftuples project as an example, here is how one generates the
docs with [pdoc](https://pypi.org/project/pdoc/).

```bash
    $ cd ~/devel/pypi/dtools/dtools-docs/tuples/API/development/
    $ rm -r dtools/ index.html search.js
    $ PYTHONPATH=~/devel/pypi/dtools/dtools-fp/src:~/devel/pypi/dtools/dtools-fp/src
    $ pdoc -o . dtools.tuples
```

# Developer Tools

Collection of Python packages to aid in general software development.

These Python developer libraries consist of Python PyPI namespace
packages all under the **dtools.** "namespace."

## PyPI `dtools.` Namespace Projects

| Projects (PyPI) | Source Code (GitHub) |
|:----------------|:-------------------- |
| [dtools.circular-array][11] | [dtools-circular-array][21] |
| [dtools.fp][12] | [dtools-fp][22] |
| [dtools.queues][13] | [dtools-queues][23] |
| [dtools.tuoles][14] | [dtools-tuoles][24] |
| [dtools.datastrAuctures][15] | [dtools-datastructures][25] |

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
``

[11]: https://pypi.org/project/dtools.circular-array/
[12]: https://pypi.org/project/dtools.fp/
[13]: https://pypi.org/project/dtools.queues/
[14]: https://pypi.org/project/dtools.tuples/
[15]: https://pypi.org/project/dtools.datastructures/
[21]: https://github.com/grscheller/dtools-circular-array/
[22]: https://github.com/grscheller/dtools-fp/
[23]: https://github.com/grscheller/dtools-queues/
[24]: https://github.com/grscheller/dtools-tuples/
[25]: https://github.com/grscheller/dtools-datastructures/

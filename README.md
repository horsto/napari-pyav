# napari-pyav

[![License MIT](https://img.shields.io/pypi/l/napari-pyav.svg?color=green)](https://github.com/danionella/napari-pyav/raw/main/LICENSE)
[![Python Version](https://img.shields.io/pypi/pyversions/napari-pyav.svg?color=green)](https://python.org)
[![PyPI](https://img.shields.io/pypi/v/napari-pyav.svg?color=green)](https://pypi.org/project/napari-pyav)
[![Conda Version](https://img.shields.io/conda/v/danionella/napari_pyav)](https://anaconda.org/danionella/napari_pyav)
[![tests](https://github.com/danionella/napari-pyav/workflows/tests/badge.svg)](https://github.com/danionella/napari-pyav/actions)
[![napari hub](https://img.shields.io/endpoint?url=https://api.napari-hub.org/shields/napari-pyav)](https://napari-hub.org/plugins/napari-pyav)

Napari plugin for reading videos using [PyAV](https://github.com/PyAV-Org/PyAV). Inspired by the [napari-video](https://github.com/janclemenslab/napari-video) project, which served us very well for many years. For some long videos, however, its dependency on opencv caused seek glitches, so we implemented this alternative plugin based on PyAV.

----------------------------------

This [napari] plugin was generated with [Cookiecutter] using [@napari]'s [cookiecutter-napari-plugin] template.

<!--
Don't miss the full getting started guide to set up your new package:
https://github.com/napari/cookiecutter-napari-plugin#getting-started

and review the napari docs for plugin developers:
https://napari.org/stable/plugins/index.html
-->

## Installation

You can install `napari-pyav` via [pip]:

    pip install napari-pyav


Or via [conda](https://github.com/conda-forge/miniforge?tab=readme-ov-file#miniforge): 

    conda install danionella::napari_pyav


To install latest development version :

    pip install git+https://github.com/danionella/napari-pyav.git


## Contributing

Contributions are very welcome. Tests can be run with [tox], please ensure
the coverage at least stays the same before you submit a pull request.

## License

Distributed under the terms of the [MIT] license,
"napari-pyav" is free and open source software

## Issues

If you encounter any problems, please [file an issue] along with a detailed description.

[napari]: https://github.com/napari/napari
[Cookiecutter]: https://github.com/audreyr/cookiecutter
[@napari]: https://github.com/napari
[MIT]: http://opensource.org/licenses/MIT
[BSD-3]: http://opensource.org/licenses/BSD-3-Clause
[GNU GPL v3.0]: http://www.gnu.org/licenses/gpl-3.0.txt
[GNU LGPL v3.0]: http://www.gnu.org/licenses/lgpl-3.0.txt
[Apache Software License 2.0]: http://www.apache.org/licenses/LICENSE-2.0
[Mozilla Public License 2.0]: https://www.mozilla.org/media/MPL/2.0/index.txt
[cookiecutter-napari-plugin]: https://github.com/napari/cookiecutter-napari-plugin

[file an issue]: https://github.com/danionella/napari-pyav/issues

[napari]: https://github.com/napari/napari
[tox]: https://tox.readthedocs.io/en/latest/
[pip]: https://pypi.org/project/pip/
[PyPI]: https://pypi.org/

# napari-sam-prompt

[![License BSD-3](https://img.shields.io/pypi/l/napari-sam-prompt.svg?color=green)](https://github.com/fdrgsp/napari-sam-prompt/raw/main/LICENSE)
[![PyPI](https://img.shields.io/pypi/v/napari-sam-prompt.svg?color=green)](https://pypi.org/project/napari-sam-prompt)
[![Python Version](https://img.shields.io/pypi/pyversions/napari-sam-prompt.svg?color=green)](https://python.org)
[![tests](https://github.com/fdrgsp/napari-sam-prompt/workflows/tests/badge.svg)](https://github.com/fdrgsp/napari-sam-prompt/actions)
[![codecov](https://codecov.io/gh/fdrgsp/napari-sam-prompt/branch/main/graph/badge.svg)](https://codecov.io/gh/fdrgsp/napari-sam-prompt)
[![napari hub](https://img.shields.io/endpoint?url=https://api.napari-hub.org/shields/napari-sam-prompt)](https://napari-hub.org/plugins/napari-sam-prompt)

A napari plugin that implements SAM prompts predictor

----------------------------------

This [napari] plugin was generated with [Cookiecutter] using [@napari]'s [cookiecutter-napari-plugin] template.

<!--
Don't miss the full getting started guide to set up your new package:
https://github.com/napari/cookiecutter-napari-plugin#getting-started

and review the napari docs for plugin developers:
https://napari.org/stable/plugins/index.html
-->

## Installation

### Install napari-sam-prompt

```bash
pip install git+https://github.com/fdrgsp/napari-sam-prompt.git
```

### Install PyTorch and TorchVision

The plugin also requires pytorch>=1.7 and torchvision>=0.8. Please follow the instructions [here](https://pytorch.org/get-started/locally/) to install both PyTorch and TorchVision dependencies.

### Install Segment Anything

```bash
pip install git+https://github.com/facebookresearch/segment-anything.git
```

A checkpoint model is required to run the plugin. Download a model from [here](https://github.com/facebookresearch/segment-anything?tab=readme-ov-file#model-checkpoints) and place it in the `napari_sam_prompt/model_checkpoints` directory.

## Contributing

Contributions are very welcome. Tests can be run with [tox], please ensure
the coverage at least stays the same before you submit a pull request.

## License

Distributed under the terms of the [BSD-3] license,
"napari-sam-prompt" is free and open source software

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

[file an issue]: https://github.com/fdrgsp/napari-sam-prompt/issues

[napari]: https://github.com/napari/napari
[tox]: https://tox.readthedocs.io/en/latest/
[pip]: https://pypi.org/project/pip/
[PyPI]: https://pypi.org/
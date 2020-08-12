<div align="center">

# face-mask-detector
![PyPI - License](https://img.shields.io/pypi/l/face-mask-detector?style=flat)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/senofsky/face-mask-detector/issues)

**A library and command line utility for detecting face masks in images and video streams**

![Demo Gif](docs/assets/demo.gif)

<img src="docs/assets/before-and-after-face-mask-detection-example.png" width="450">

</div>

Installation
---------------

As always, the use of a python [virtual
environment](https://docs.python.org/3/tutorial/venv.html) is recommended for a
development setup:

``` sh
python -m venv venv
source venv/bin/activate
```

To install using `pip`:

``` sh
pip install face-mask-detector
```

Quick Start
-------------

To detect face masks in a image, run:

```sh
face-mask-detector --image path/to/image
```

To start your webcam and detect face masks in the video stream, run:

```sh
face-mask-detector
```

Contributing
-------------
To install `face-mask-detector` from source, clone this repository and run the
following in the project root directory:

```sh
pip install -e '.[dev]'
```

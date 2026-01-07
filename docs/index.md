# k3confloader

[![Action-CI](https://github.com/pykit3/k3confloader/actions/workflows/python-package.yml/badge.svg)](https://github.com/pykit3/k3confloader/actions/workflows/python-package.yml)
[![Documentation Status](https://readthedocs.org/projects/k3confloader/badge/?version=stable)](https://k3confloader.readthedocs.io/en/stable/?badge=stable)
[![Package](https://img.shields.io/pypi/pyversions/k3confloader)](https://pypi.org/project/k3confloader)

Load configuration for pykit3 modules. k3confloader tries to load a python file `k3conf.py` and expects it to contain configuration.

k3confloader is a component of [pykit3](https://github.com/pykit3) project: a python3 toolkit set.

## Installation

```bash
pip install k3confloader
```

## Quick Start

```python
# Setup config: echo 'uid=3' > k3conf.py

import k3confloader
print(k3confloader.conf.uid)  # 3
```

## API Reference

::: k3confloader

## License

The MIT License (MIT) - Copyright (c) 2015 Zhang Yanpo (张炎泼)

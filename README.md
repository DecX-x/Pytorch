
# Pyrotch

Pyrotch is a Python library for interfacing with robotic torch devices. It provides a simple API for controlling robotic torches and manipulating the torch flame properties.

## Key Features

- Interface with various robotic torch hardware including robotic arms, pan/tilt platforms, etc. 
- Adjust torch flame size, shape, color temperature, and other parameters
- Automate complex torch movements and flame effects
- Integrate torch control into larger robotic systems and workflows

## Usage

Pyrotch aims to provide an intuitive interface for torch control:

```python
import pyrotch

torch = pyrotch.connect_torch()

torch.move(x=10, y=5, z=15) 
torch.set_flame(size=50, color=2000)
torch.wave(period=5, amplitude=20)
```

The library handles the low-level interfacing and protocols so you can focus on your application logic.

## Installation

Pyrotch is available on PyPI and can be installed via pip:

```
pip install pyrotch
```

Pyrotch supports Python 3.6 and up. The library is open source under the MIT license.

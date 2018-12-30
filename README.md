# x256-img
[![PyPI version](https://badge.fury.io/py/x256-img.svg)](https://badge.fury.io/py/x256-img)

# Installation
## Prerequisites
Python 3.6+

## Install
Windows: 
```bash
pip install colorama x256_img
```

Linux & macOS
```bash
pip install x256_img
```

# Usage
## From Python
```python
from x256_img import display
from PIL import Image

img = Image.open("image.png")
width, _ = img.size
display(img.getdata(), width)
```

## From CLI
```bash
x256-img image.png
```

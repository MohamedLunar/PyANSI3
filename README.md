# PyANSI3
- PyANSI3 is a basic python library you can found it on [PyPI](https://pypi.org/project/py-ansi3)
- Package Owner & Creator: **MohamedLunar** (me)
# Package Guide
## #1 Installation Guide
- You can download the package via:
```bash
pip install py-ansi3
```
## #2 Usage
- You can modify text color and add a background color _ex_:
```python
import pyansi3
from pyansi3 import PyANSI, print_colored

print_colored("red {red}tttt {reset} background blue {blue_bg}tttt")
```
- and you can use {reset} to reset the color to the default color

# pi-notebooks
Notebooks for all the labs on CSCI2050U (Computer Architecture).

## Requirements
These labs require a Raspberry Pi 5 hardware with access to its GPIO. \
*Do note that the hardware for LEDs, jumper cables, buttons, servo, etc. are to be expected from this lab.* \
Libraries and packages that are required to run these notebooks are:
* Python 3
* JupyterLab
* [GPIO Zero](https://github.com/gpiozero/gpiozero)
* [Adafruit CircuitPython HT16K33](https://github.com/adafruit/Adafruit_CircuitPython_HT16K33)
* cmake
* [ARM Jupyter Kernel](https://pypi.org/project/arm-jupyter-kernel/)

## Known Issue
The notebooks must be run in JupyterLab; otherwise, images may not load. This is because on top of Markdown, Jupyter Book also supports a special flavour of Markdown called MyST (or Markedly Structured Text). Some images and diagrams rely on MyST's HTML/CSS capabilities. \
Text editors like VSCode do not fully support MyST, which may result in missing images.


Author: Tobi Goodness Popoola

### Overview

Docker file to setup IEGENLib and run calculator for tutorial series

### Manifest
iegendocker: file that could be used to create instance of IEGENLib calculator

### Usage

Build docker file:

sudo docker build -f iegendockerfile -t iegendocker . 


Run iegen lib interactively:

sudo docker run -it iegendocker /bin/bash

IEGenLib/build/src/iegenlib_calc


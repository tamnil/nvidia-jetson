#Nvidia Jetson




## agx xavier

pinout

https://www.jetsonhacks.com/nvidia-jetson-agx-xavier-gpio-header-pinout/


### pytorch


Default pip installs not compiled with CUDA

python 3.7 :
https://github.com/pytorch/pytorch#from-source
https://forums.developer.nvidia.com/t/pytorch-for-jetson-version-1-9-0-now-available/72048  -> python 3.6
https://nmilosev.svbtle.com/compling-arm-stuff-without-an-arm-board-build-pytorch-for-the-raspberry-pi

### compile

export OPENBLAS_CORETYPE=ARMV8


### stats

sudo -H pip install -U jetson-stats
sudo jtop

# nvidia-jetson nano

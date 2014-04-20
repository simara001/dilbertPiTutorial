How to Install
=======

It is expected that your *SD Card* has installed a version for your Raspberry Pi. In case you have some problem, you might be able to download it from [here](http://www.raspberrypi.org/downloads/). The process of formatting your **SD Card** is more complex than simply copy-paste a file. The instructions to do it can change depending on the OS you are using. My prefer OS is the Mac OS X (Currently Mavericks) and here are the instructions.

Login into your raspberry using SSH

```bash
ssh pi@10.50.0.1
```

Go to your home directory and clone DilbertPi project from GitHub

```bash
cd ~/
git clone https://github.com/ferdingler/dilbertpi
```
Go inside the new folder that you just cloned. You should see a python script named *dilbert.py*

```bash
pi@raspberrypi ~/dilbertpi $ cd dilbertpi
pi@raspberrypi ~/dilbertpi $ ls
dilbert.py
```
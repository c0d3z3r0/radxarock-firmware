# radxarock-firmware

This repository contains the barebox bootloader and the linux kernel for Radxa Rock Pro and is used by [rock-update](https://github.com/c0d3z3r0/rock-update).

Currently there are some important patches for network and usb in mainline (4.6). The kernel providided in this repo will be switched to linux-stable as soon as those become stable.

The kernel config is based on Debian's armhf config.

## Overclocking

rk3188-radxarock-oc.dtb adds 1.7 GHz, 1.8 GHz and 1.9 GHz to your Radxa Rock and sets the maximum voltage to 1.5V.
***This may damage your device! Use it at your own risk!***

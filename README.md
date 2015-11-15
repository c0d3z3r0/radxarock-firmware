# radxarock-firmware

This repository contains the barebox bootloader and the linux kernel for Radxa Rock Pro and is used by [rock-update](https://github.com/c0d3z3r0/rock-update).

Since there are still many fixes and improvements for radxa rock sent in I decided to use linux-next. Later I'll switch to linux-stable.

The kernel config is based on Debian's armhf config.

## Overclocking

rk3188-radxarock-oc.dtb adds 1.7 GHz, 1.8 GHz and 1.9 GHz to your Radxa Rock and sets the maximum voltage to 1.5V.
***This may damage your device! Use it at your own risk!***

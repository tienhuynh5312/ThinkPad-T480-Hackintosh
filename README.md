# ThinkPad-T480-Hackintosh
A github page for your beloved Thinkpad T480. The config is tested on Catalina 10.15.3

## Current macOS version
Catalina 10.15.4

## Specs
Part | Spec|Status
-----|-----|------
CPU|Intel i5-8250u|Working
RAM| Dual Channel 2x8GB|Working
SSD| Intel 512GB NVME|Working
Graphics| Intel UHD 620|Working
Wifi + BT| Fenvi BCM94360NG| Working
Microphone| *not sure the model number*| Working
Speaker| ALC257, layoutid 11 |Working
Touchpad|Synaptics PS2|Working, custom gestures
Trackpoint|The red nipple button|Disabled
USB2.0&3.0|You know what they are :) | Working
USB C| *needs testing* | Working, not sure

## Todo
- [ ] Power button blinking after wake from sleep.

## Installation
- Please refer other guides for how to make a USB installation and create EFI (Clover)
- Please use mac serial generator or clover configurator to generate serial number and UUID.

## Post-installation

### Audio jack
If you have audio glitchy after plug your headphone jack, use this.
1. Go to `Fixes\` folder.
1. Run `read and write repair app`.
2. Go into `alc_fix` folder, run `install.sh`and reboot.

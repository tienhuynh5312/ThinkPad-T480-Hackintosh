# ThinkPad-T480-Hackintosh
A github page for your beloved Thinkpad T480. The config is tested on Catalina 10.15.3

## Current macOS version
Catalina 10.15.3

## Specs
Part | Spec|Status
-----|-----|------
CPU|Intel i5-8250u|Working
RAM| Dual Channel 2x8GB|Working
SSD| Intel 512GB NVME|Working
Graphics| Intel UHD 620|Working
Wifi| Intel Wifi card | Not Working
Microphone| *not sure the model number*| Working
Speaker| *not sure the model*|Working
Touchpad|Synaptics PS2|Working, custom gestures
Trackpoint|The red nipple button|Disabled
USB2.0&3.0|You know what they are :) | Working
USB C| *needs testing* | Working, not sure

## Todo
- [ ] Upgrade wifi card. DW1560 is safe choice but expensive. The config.plist is modified for cheaper solution DW1820A. See [DW1820A finding](https://osxlatitude.com/forums/topic/11322-broadcom-bcm4350-cards-under-high-sierramojavecatalina/)

## Installation
- Please refer other guides for how to make a USB installation and create EFI (Clover)
- Please use mac serial generator or clover configurator to generate serial number and UUID.

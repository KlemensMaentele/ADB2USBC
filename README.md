# ADB2USBC

**ADB-to-USB Converter for Apple Keyboards**

This project provides firmware and hardware to convert old **Apple Desktop Bus (ADB)** keyboards into modern **USB HID** keyboards using an **ATmega32U2 MCU**.  
It is based on the **TMK keyboard firmware project**, which includes a ADB to USB protocol converter.

---

## Overview

This board acts as a bridge between:
- **ADB keyboard (Apple vintage keyboards)**
- **Modern USB host devices (PC, Mac, Linux, etc.)**

### Features
- ADB protocol support  
- USB HID keyboard output  
- Based on **TMK keyboard firmware**
- MCU: **ATmega32U2**
- DFU bootloader flashing via USB

---

## Firmware

The firmware is based on the **TMK Keyboard Firmware Collection**  
TMK includes an ADB-USB converter implementation with full HID support.

TMK Project:  
https://github.com/tmk/tmk_keyboard

---

## Pictures

> Hardware and PCB photos

![ADB2USBC Board](pictures/image1.jpeg)
![ADB2USBC PCB](pictures/image2.jpeg)

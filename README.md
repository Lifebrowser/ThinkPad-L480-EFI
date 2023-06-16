# ThinkPad-L480-EFI
ThinkPad L480 Hackintosh EFI with OpenCore 0.9.0

[中文版简介](https://github.com/Lifebrowser/ThinkPad-L480-EFI/blob/main/%E7%AE%80%E4%BB%8B.md)

[![OpenCore](https://img.shields.io/badge/OpenCore-0.9.0-lightblue.svg)](https://github.com/acidanthera/OpenCorePkg)
[![macOS-Stable](https://img.shields.io/badge/macOS-13.3.1-orange.svg)](https://www.apple.com/macos/ventura/)
[![Windows-Stable](https://img.shields.io/badge/Windows-11-blue.svg)](https://www.microsoft.com/en-us/windows)

## Introduction

<summary><strong>Hardware</strong></summary>
<br>

[UEFI]

| Category  | Component                         | Note                                         |
| --------- | --------------------------------- | -------------------------------------------- |
| CPU       | Intel Core i7-8550U               |                                              |
| GPU       | Intel UHD 620                     |                                              |
| SSD       | Intel 760p 512GB                  |                                              |
| Memory    | 16GB DDR4 2400Mhz                 |                                              |
| Battery   | Single battery                    |                                              |
| Camera    | 720p Camera                       |                                              |
| Wifi & BT | Intel Dual Band Wireless AC 8265  |                                              |
| Input     | PS2 Keyboard & Synaptics TrackPad |                                              |

<summary><strong>Main software</strong></summary>
<br>

| Component      | Version        |
| -------------- |  ------------- |
| macOS Ventura  | 13.3.1(22E261) |
| Windows 11     | 22H2           |
| OpenCore       | v0.9.0         |

## Before installation

<summary><strong>UEFI settings</strong></summary>
<br>

**Security**

- `Memory Protection -> Execution Prevention` **Enabled**
- `Virtualization -> Intel Virtualization Technology` **Enabled**
- `Virtualization -> Intel VT-d Feature` **Enabled**

**Startup**

- `UEFI/Legacy Boot` **UEFI Only**
- `CSM Support` **No**

## Status

<summary><strong>What's working </strong></summary>

- [x] Battery percentage.
- [x] CPU power management / performance.
- [x] GPU UHD 620 hardware acceleration / performance.
- [x] HDMI. `Closed and opened lid. With audio`
- [x] iMessage, FaceTime, App Store, iTunes Store. **Make sure to generate your own SMBIOS**
- [x] Intel I219V Ethernet port.
- [x] Keyboard. `Volume and brightness hotkeys`
- [x] Realtek® Audio.
- [x] SD card reader. `Fortunately, USB connected`
- [x] Sleep/Wake.
- [x] TouchPad. `1-5 fingers swipe works. Emulate force touch using longer and more voluminous touch`
- [x] TrackPoint. `Works perfectly. Just like on Windows or Linux`
- [x] USB Ports. `USB Map is different for devices with Windows Hello camera`
- [x] Web camera.
- [x] Wifi. `Intel Dual Band Wireless AC 8265`
- [x] Bluetooth. `Intel Bluetooth 4.2`
- [x] Windows 11 boot from OC boot menu.

<summary><strong>What's not working </strong></summary>

## References & Special thanks to
- [OpenCore](https://dortania.github.io/OpenCore-Install-Guide/)
- [Acidanthera Mac Drivers](https://github.com/acidanthera)
- [Open Intel Wireless](https://github.com/OpenIntelWireless/itlwm)
- [Opencore Configurator](https://mackie100projects.altervista.org/opencore-configurator/)

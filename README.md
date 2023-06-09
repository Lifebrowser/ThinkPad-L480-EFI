# ThinkPad-L480-EFI
ThinkPad L480 Hackintosh EFI with OpenCore 0.7.9


[![OpenCore](https://img.shields.io/badge/OpenCore-0.7.9-lightblue.svg)](https://github.com/acidanthera/OpenCorePkg)
[![macOS-Stable](https://img.shields.io/badge/macOS-12.3.1-purple.svg)](https://www.apple.com/macos/monterey/)
[![Windows-Stable](https://img.shields.io/badge/Windows-11-blue.svg)](https://www.microsoft.com/en-us/windows)

## Introduction

<details>
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

</details>  

<summary><strong>Main software</strong></summary>
<br>

| Component      | Version        |
| -------------- |  ------------- |
| macOS Monterey | 12.3.1(21E258) |
| Windows 11     | 21H2           |
| OpenCore       | v0.7.9         |

</details>

## Before installation

<details>  

<summary><strong>UEFI settings</strong></summary>
<br>

**Security**

- `Memory Protection -> Execution Prevention` **Enabled**
- `Virtualization -> Intel Virtualization Technology` **Enabled**
- `Virtualization -> Intel VT-d Feature` **Enabled**

**Startup**

- `UEFI/Legacy Boot` **UEFI Only**
- `CSM Support` **No**

</details>  

Format is lang-COUNTRY:keyboard

- 🇨🇳 | [252] en - ABC --> zh-Hans:252 --> 7A682D48 616E733A 323532
- 🇺🇸 | [0] en_US - U.S --> en-US:0 --> 656e2d55 533a30

etc.

[AppleKeyboardLayouts.txt](https://github.com/acidanthera/OpenCorePkg/blob/master/Utilities/AppleKeyboardLayouts/AppleKeyboardLayouts.txt)

</details>

## Status

<details>  

<summary><strong>What's working </strong></summary>

- [x] Battery percentage
- [x] CPU power management / performance.`
- [x] GPU UHD 620 hardware acceleration / performance.`
- [x] HDMI `Closed and opened lid. With audio.`
- [x] iMessage, FaceTime, App Store, iTunes Store. **Generate your own SMBIOS**
- [x] Intel I219V Ethernet port.`
- [x] Keyboard `Volume and brightness hotkeys.`
- [x] Realtek® ALC3287 ("ALC257") Audio.`
- [x] SD card reader `Fortunately, USB connected.`
- [x] Sleep/Wake.`
- [x] TouchPad `1-5 fingers swipe works. Emulate force touch using longer and more voluminous touch.`
- [x] TrackPoint  `Works perfectly. Just like on Windows or Linux.`
- [x] USB Ports `USB Map is different for devices with Windows Hello camera.`
- [x] Web camera.`
- [x] Wifi - Intel Dual Band Wireless AC 8265.`
- [x] Windows 11 boot from OC boot menu.`

</details>  

<details>  

<summary><strong>What's not working </strong></summary>


- [ ] Bluetooth`

</details>  

##  Credits

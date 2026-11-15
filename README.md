# ThinkPad T14 Gen 2 (Intel) Opencore EFI
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/e0b0e6a1-6ce7-402b-9b09-27d03ebd5861" />
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/8c1ff74f-c443-40c0-88be-3da77f344de7" />
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/d143289b-de76-4e13-a942-000acd19e0db" />
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/ae317292-4cca-4964-bcb7-213113d5dc3e" />

## Specs
I'm using ThinkPad T14 Gen 2 (Intel) with this specification, please make sure not every ThinkPad T14 Gen 2 (Intel) specs are the same, check your device compatibility before trying this EFI

| **Hardware** | **Specs**                |
|:-------------|:-------------------------|
| Processor    | Intel Core i5-1145G7     |
| RAM          | 16GB DDR4 3200MHz        |
| SSD          | SKHynix 512GB NVMe BC511 |
| Graphics     | Intel Iris Xe            |
| WiFi         | Intel AX201              |
| Bluetooth    | Intel Wireless Bluetooth |
| Touchpad     | Synaptic HID             |
| Audio        | Realtek Audio            |
| Ethernet     | Intel I219-LM            |

## Kext Config
| **Hardware**     | **Kext**                         |
|:-----------------|:---------------------------------|
| Graphics         | whateverXe & whateverXe-graphics |
| WiFi             | ForbiddenItlwm                   |
| Bluetooth        | IntelBluetoothFirmware           |
| Power Management | VirtualSMC                       |
| Audio            | AppleALC                         |
| LAN              | IntelMausi                       |
| SSD              | NVMeFix                          |
| HID              | VoodooI2C & VoodooI2CHID         |
| USB              | USBToolBox                       |

## Features
What's working hardware on this EFI, almost everything is working

| **Whats working**    |            |
|:---------------------|:-----------|
| Graphics             | ✅         |
| WiFi                 | ✅         |
| Bluetooth            | ✅         |
| Power Management     | ✅         |
| Audio                | ✅         |
| LAN                  | ✅         |
| SSD                  | ✅         |
| HID                  | ✅         |
| USB Port             | ✅         |
| HDMI                 | ✅         |
| Apple ID             | ✅         |
| Brightness           | ✅         |
| Volume control       | ✅         |
| Trackpad & Trackball | ✅         |
| Sleep                | ⚠️         |
| Webcam               | ⚠️         |
| Apple Service        | ⚠️         |
| Biometric            | ❌         |
| SDCard               | ❌         |
| Backlight Keyboard   | Not tested |
| Microphone           | Not tested |
| Airdrop              | Not tested |
| Thunderbolt 4        | Not tested |

## Tested Environment
| **Item**   | **Details**    |
|:-----------|:---------------|
| macOS      | Sequoia 15.8.3 |
| Bootloader | OpenCore       |
| SMBIOS     | MacBookPro16,2 |

## BIOS Settings
- Secure Boot: **Disabled**

Settings can differ between BIOS versions. If the EFI does not boot, check the BIOS first.

## Help Wanted
These features have not been tested yet: keyboard backlight, microphone, AirDrop, and Thunderbolt 4. Feel free to open an issue with your results.

## Credits
- [Acidanthera](https://github.com/acidanthera) for OpenCore, Lilu, VirtualSMC, AppleALC, NVMeFix, and IntelMausi
- [OpenIntelWireless](https://github.com/OpenIntelWireless) for itlwm and IntelBluetoothFirmware
- [b00t0x](https://github.com/b00t0x/WhateverXe) for WhateverXe
- [VoodooI2C](https://github.com/VoodooI2C/VoodooI2C) team for VoodooI2C and VoodooI2CHID
- [USBToolBox](https://github.com/USBToolBox) for USBToolBox
- [Dortania](https://dortania.github.io/) for the OpenCore guides
- [OpCore-Simplify](https://github.com/lzhoang2801/OpCore-Simplify) for the tool used to generate the base EFI

## Disclaimer
This EFI is provided as is, without any warranty. Use it at your own risk and always back up your data before booting or installing macOS.

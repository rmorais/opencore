# opencore

## Software Versions
 - OpenCore: 0.6.4
 - macOs: 10.5.7 (Catalina)
## Hardware
- CPU: Intel i5-9600k
- Motherboard: [Asus Prime Z390-A](https://www.asus.com/uk/Motherboards/PRIME-Z390-A)
- iGPU: Intel UHD 630
- RAM: 32GB Crucial Ballistic Sport LT (8GB x 4)
- SSD: Samsung 970 EVO Plus 500 GB PCIe NVMe M.2
- Audio: ALC S1220A (Layout 1)
- Ethernet: Intel I219V

## Peripherals
- Trust Bluetooth 4.0 USB Dongle 18187

## Drivers

## SSDTs
## Kexts
 - [AppleALC](https://github.com/acidanthera/AppleALC/releases) 1.5.5
 - [IntelMausi](https://github.com/acidanthera/IntelMausi/releases) 1.0.4
 - [Lilu](https://github.com/acidanthera/Lilu/releases) 1.5.0
 - [NVMeFix](https://github.com/acidanthera/NVMeFix/releases) 1.0.4
 - [VirtualSMC](https://github.com/acidanthera/VirtualSMC/releases) 1.1.9
    - SMCProcessor
    - SMCSuperIO
 - [WhateverGreen](https://github.com/acidanthera/WhateverGreen/releases) 
 1.4.5
 ## USB Mapping

 | Port Number | USB 3 | USB 2 | ID       | Location   | In Use |
 | :---------: | :---: | :---: | :------: | :--------: | :----: |
 | 1           | SS01  | HS01  | U31G2_1  | Rear Panel (#4) | SS01, HS01 |
 | 2           | SS02  | HS02  | U31G2_2  | Rear Panel (#4) | SS02, HS02 |
 | 3           | SS03  | HS03  | U31G2_3  | Rear Panel (#2) | SS03 |
 | 4           | SS04  | HS04  | U31G2_C4 | Rear Panel (#7) | SS04 |
 | 5           | SS05  | HS05  | U31G2_C5 | USB 3.1 Gen 1 Onboard front panel connector | SS05 |
 | 7           | SS07  | HS07  | U31G2_7  | Onboard Connector USB 3.1 Header | SS07, HS07 |
 | 8           | SS08  | HS08  | U31G2_8  | Onboard Connector USB 3.1 Header | SS08, HS08 |
 | 9           | SS09  | HS09  | U31G1_9  | Rear Panel (#9) | SS09 |
 | 10          | SS10  | HS10  | U31G2_10 | Rear Panel (#9) | SS10 |
 | 11          | -     | HS11  | USB11    | Onboard Connector USB 2.0 Left Header (A) |
 | 12          | -     | HS12  | USB12    |  Onboard Connector USB 2.0 Left Header (A) |
 | 13          | -     | HS13  | USB13    | Rear Panel (#6) | HS13 |
 | 14          | -     | HS14  | USB14    | Rear Panel (#6) | HS14 |
 |           | -     |   | USB_E1    | Onboard Connector USB 2.0 Middle Header (B) |
 |           | -     |   | USB_E2   | Onboard Connector USB 2.0 Middle Header (B) |
 |           | -     |   | USB_E3    | Onboard Connector USB 2.0 Right Header (C) |
 |           | -     |   | USB_E4    | Onboard Connector USB 2.0 Right Header (C) |

## Working
- Ethernet
- DP Video
- Bluetooth
- Front Audio
- Back Audio 2 channel
- Spdif Audio
- facetime
- Power Management
- FileVault
## Not Working
- HDMI video
- DRM content

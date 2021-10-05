# Hardware
* MSI MEG Z490I UNIFY
  * Intel® Z490 Chipset
  * Intel® JHL7540 Thunderbolt™ 3 Controller
  * Realtek® ALC1220 Audio Codec
  * Realtek® RTL8125B 2.5Gbps LAN controller
  * Intel® AX201 wireless module
  * NUVOTTON NCT6687 Controller Chip
* i7-107000K 8-Core 3.8 GHz
* Kingston DDR4 2933MHz 16GB x2
* Samsung SSD 970 EVO Plus 1TB
* Radeon RX 580 8GB

# Software
Software | Version
-------- | -------
[OpenCore](https://github.com/acidanthera/OpenCorePkg) | 0.7.3
[OcBinaryData](https://github.com/acidanthera/OcBinaryData) |
AirportBrcmFixup | 2.1.3
AirportItlwm | 2.1.0-alpha
[AppleALC](https://github.com/acidanthera/AppleALC) | 1.6.4
CPUFriend | 1.2.4
HibernationFixup | 1.4.3
[IntelBluetoothFirmware](https://github.com/OpenIntelWireless/IntelBluetoothFirmware) | 2.0.1
itlwm | 2.1.0-alpha
[Lilu](https://github.com/acidanthera/Lilu) | 1.5.6
[LucyRTL8125Ethernet](https://github.com/Mieze/LucyRTL8125Ethernet) | 1.1.0
NVMeFix | 1.0.9
[USBInjectAll](https://github.com/Sniki/OS-X-USB-Inject-All) | 0.7.6
[VirtualSMC](https://github.com/acidanthera/VirtualSMC) | 1.2.7
[WhateverGreen](https://github.com/acidanthera/WhateverGreen) | 1.5.3

* VirtualSMC includes:
  * SMCLightSensor.kext
  * SMCProcessor.kext
  * SMCSuperIO.kext
  * VirtualSMC.kext

# Results
Everything works with Big Sur 11.6 with USB ports mapped. Bluetooth is not fully tested. Nothing is over-clocked. The system does *not* recognize the Apple Watch for unlocking. 

# License
This project is a combination of others' licenses. See those projects for licensing.

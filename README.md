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
[OpenCore](https://github.com/acidanthera/OpenCorePkg) | 0.7.0
[OcBinaryData](https://github.com/acidanthera/OcBinaryData) |
[AppleALC](https://github.com/acidanthera/AppleALC) | 1.6.1
[IntelBluetoothFirmware](https://github.com/OpenIntelWireless/IntelBluetoothFirmware) | 1.1.3
[Lilu](https://github.com/acidanthera/Lilu) | 1.5.3
[LucyRTL8125Ethernet](https://www.insanelymac.com/forum/topic/343542-lucyrtl8125ethernetkext-for-realtek-rtl8125) | 1.1.0
[USBInjectAll](https://github.com/Sniki/OS-X-USB-Inject-All) | 0.7.6
[VirtualSMC](https://github.com/acidanthera/VirtualSMC) | 1.2.4
[WhateverGreen](https://github.com/acidanthera/WhateverGreen) | 1.5.0

* VirtualSMC includes:
  * SMCLightSensor.kext
  * SMCProcessor.kext
  * SMCSuperIO.kext
  * VirtualSMC.kext

# Results
Everything works with Big Sur 11.2.3, including Adobe Lightroom Classic, though boot time is very long. Bluetooth is not fully tested. Nothing is over-clocked. The system does *not* recognize the Apple Watch for unlocking.

# License
This project is a combination of others' licenses. See those projects for licensing.

# Hardware
* MSI MEG Z490I UNIFY
  * Intel® Z490 Chipset
  * Intel® JHL7540 Thunderbolt™ 3 Controller
  * Realtek® ALC1220 Audio Codec
  * Realtek® RTL8125B 2.5Gbps LAN controller
  * ~~Intel® AX201 wireless module~~ *removed*
  * NUVOTTON NCT6687 Controller Chip
* i7-107000K 8-Core 3.8 GHz
* Kingston DDR4 2933MHz 16GB x2
* Western Digital Black SN750 2TB
* Sapphire RX 580 Pulse 8GB
* BCM95360CDAX WiFi 802.11AC Bluetooth 4.0

# Software
Software | Version
-------- | -------
[OpenCore](https://github.com/acidanthera/OpenCorePkg) | 0.8.4
[OcBinaryData](https://github.com/acidanthera/OcBinaryData) | 11/21
[AppleALC](https://github.com/acidanthera/AppleALC) | 1.7.5
[CPUFriend](https://github.com/acidanthera/CPUFriend) | 1.2.6
[FeatureUnlock](https://github.com/acidanthera/FeatureUnlock) | 1.0.9
[HibernationFixup](https://github.com/acidanthera/HibernationFixup) | 1.4.6
[IntelBluetoothFirmware](https://github.com/OpenIntelWireless/IntelBluetoothFirmware) | 2.2.0
[Lilu](https://github.com/acidanthera/Lilu) | 1.6.2
[LucyRTL8125Ethernet](https://github.com/Mieze/LucyRTL8125Ethernet) | 1.1.0
[NVMeFix](https://github.com/acidanthera/NVMeFix) | 1.1.0
[VirtualSMC](https://github.com/acidanthera/VirtualSMC) | 1.3.0
[WhateverGreen](https://github.com/acidanthera/WhateverGreen) | 1.6.1

* VirtualSMC includes:
  * SMCProcessor.kext
  * VirtualSMC.kext

# Results
Works with Monterey 12.5 with USB ports mapped. Bluetooth and Wi-Fi are not working. Nothing is over-clocked. The system does *not* recognize the Apple Watch for unlocking.

# License
This project is a combination of others' licenses. See those projects for licensing.

# Skylake - H170 - RX 570 - macOS 13.1 (Ventura)

# Hardware Used
| Component | Model |
| --------- | ----- |
| CPU | i5 6400 |
| Motherboard | MSI H170M PRO-VDH D3|
| RAM | DDR3 1600Mhz (4 x 4GB)|
| Storage | Samsung 840 Evo SATA SSD|
| Network | Fenvi FW-T919|
| SMBIOS | iMac Pro 1,1|

# Bootloader 
- OpenCore 0.8.7
- Kexts
  - AirportBrcmFixup (plugins disabled)
  - AppleALC
  - Lilu
  - WhateverGreen
  - VirtualSMC
  - RealtekRTL811
  - USBToolBox
  - UTBMap (mapped in Windows)
- Drivers
  - HfsPlus
  - OpenCanopy
  - OpenRuntime
  - ResetNvramEntry
- ACPI
  - SSDT-EC-USBX-Desktop (Prebuilt)
  - SSDT-PLUG-DRTNIA (Prebuilt)

# What works
- [x] iServices
- [x] Sleep
- [x] Shutdown
- [x] Continuity Features

# What doesn't work
- [ ] USB does not wake system from sleep

# Guide Used
https://dortania.github.io/OpenCore-Install-Guide/

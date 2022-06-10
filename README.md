


Prozessor: AMD Ryzen 9 5950X
Cooler: Custom Water Cooling
Motherboard: Asus X570  (BIOS 2.60)
WIFI/BT: Broadcom BCM94360NG
Memory: 
Storage: 
Video Card: 6600XT
Power Supply: 
Case: 

[macOS Ventura](https://forum.amd-osx.com/index.php?threads/johns-asus-x570-i-gaming-efi-works-on-most-asus-x570-b550-motherboards.2854/)

## Software

* OpenCore 
  * URL: https://github.com/acidanthera/OpenCorePkg
  * Version: `0.6.9`
  * Removed:
    * `Drivers/HiiDatabase.efi`
    * `Drivers/NvmExpressDxe.efi`
    * `Drivers/XhciDxe.efi`
    * `Tools/*`

* AppleSupportPkg
  * URL: https://github.com/acidanthera/AppleSupportPkg
  * Version: `2.1.6`
  * Removed:
    * `Drivers/AudioDxe.efi`

* Lilu
  * URL: https://github.com/acidanthera/Lilu
  * Version: `1.4.3`

* VirtualSMC
  * URL: https://github.com/acidanthera/VirtualSMC
  * Version: `1.1.2`
  * Removed:
    * `Kexts/SMCBatteryManager.kext`
    * `Kexts/SMCLightSensor.kext`
    * `Tools/*`

* WhateverGreen
  * URL: https://github.com/acidanthera/WhateverGreen
  * Version: `1.3.8`
  * Removed:
    * `ACPI/SSDT-PNLF.aml`

* SMCAMDProcessor
  * URL: https://github.com/trulyspinach/SMCAMDProcessor
  * Version: `0.6`

* HoRNDIS
  * URL: https://github.com/jwise/HoRNDIS/releases
  * Version: `9.2`

* SmallTree Intel 82576
  * URL: unknown
  * Version: unknown

* RadeonBoost
  * URL: https://egpu.io/forums/mac-setup/radeonboost-something-for-you-guys-to-try/
  * Version: `1.3`

[引用地址](http://bbs.pcbeta.com/viewthread-1861334-1-1.html)

[Ryzen Mac Pro](https://github.com/aluveitie/RyzenMacPro)

[Opencore-EFI-for-AMD3900X-5700XT-TUF-x570-Hackintosh](https://github.com/hermanzhaozzzz/My-Opencore-EFI-for-AMD3900X-5700XT-TUF-x570-Hackintosh)

[Ryzentosh-ASUS-X570-PRIMEPRO](https://github.com/Mixaill/Ryzentosh-ASUS-X570-PRIMEPRO)

[AX200 Github Wireless](https://github.com/OpenIntelWireless/itlwm)

[AX200 Github BluetoothFirmware](https://github.com/OpenIntelWireless/IntelBluetoothFirmware)

[AX200 无线网卡的黑苹果驱动](http://bbs.pcbeta.com/viewthread-1866140-1-1.html)

[AX200 无线网卡V2ex汇总](https://v2ex.com/t/710376)

[参考博客 xjn](https://blog.xjn819.com/)

[BIOS 更新](https://www.asus.com.cn/Motherboards/PRIME-X570-P/HelpDesk_BIOS/)

[B站视频](https://www.bilibili.com/video/av78803022)


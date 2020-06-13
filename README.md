# [B360M-MORTAR-TITANIUM Hackintosh](https://www.msi.com/Motherboard/B360M-MORTAR-TITANIUM) 

![opencore-version](https://img.shields.io/static/v1?label=opencore&message=0.5.9&color=green)

* Based on [OpenCore](https://dortania.github.io/OpenCore-Desktop-Guide/) and thanks [GeQ1an/MSI-B360M-MORTAR-HACKINTOSH-OPENCORE-EFI](https://github.com/GeQ1an/MSI-B360M-MORTAR-HACKINTOSH-OPENCORE-EFI) support **kext and efi.**
* Self-use EFI configuration will be continuously updated when upgrade my pc successfully. **This EFI ONLY WORKS FOR MY PC BUILDS！！！**
* If you have some trouble when use it, only one solution - search **opencore-docs** because I don't know....

## Currently Result

Basically perfect~

It could not wakeup at oc version 0.5.7, but it works fine now.

## PC BUILD

|              |                       |
| ------------ | --------------------- |
| Memory       | klevv boltx 16G * 2   |
| MotherBoard  | B360M-MORTAR-TITANIUM |
| CPU          | I5-9400               |
| WIFI&BL Card | fenvi pcie            |
| SSD          | SN750 500G            |

## HOW TO USE

#### Prerequisites

* **Your builds just same as mine**

* Already following opencore guide，maked a [macos installer](https://dortania.github.io/OpenCore-Desktop-Guide/installer-guide/).

#### Steps

1. Just pull my efi

2. Use [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) to generate **Macmini8,1** bios info. 

3. Update these config

   ![image.png](https://i.loli.net/2020/06/13/rd9fs3YpUGHguED.png)

4. Then replace your boot usb efi folder and reboot.

## Reference

1. [OpenCore CoffeLake Configuration Guide](https://dortania.github.io/OpenCore-Desktop-Guide/config.plist/coffee-lake.html) :star::star::star:

2. [generate your smbios](https://github.com/corpnewt/GenSMBIOS) 

3. [snaity-checker](https://opencore.slowgeek.com/)

   optimize your configuration
# OpenCore EFI for SandyBridge UEFI Hackintosh (macOS 10.13 - 11.0)

**macOS version**: 11.2.1 (20D74)
**OpenCore version**: 0.6.6

## Table of content
 - [Compatible macOS versions](#Compatible-macOS-versions)
 - [Issues](#Issues)
 - [How to use](#How-to-use)
 - [Guides](#Guides)
 - [Credits](#Credits)

## Compatible macOS versions (Tested)
 - High Sierra (10.13.x)
 - Mojave (10.14.x)
 - Catalina (10.15.x)
 - Big Sur (11.x)

## Issues
 - None

## How to use
  1. Make your USB installer with [**this guide**](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/)
  2. Clone the repository and paste "BOOT" and "OC" directories into your's pendrive "EFI" folder
  3. Download [**GenSMBIOS**](https://github.com/corpnewt/GenSMBIOS) to generate unique SMBIOS information. Run it and select **Generate SMBIOS**, as the model select **iMacPro1,1**.
  4. Open config.plist with [**ProperTree**](https://github.com/corpnewt/ProperTree) and go to PlatformInfo > Generic. Set MLB (Board Serial), SystemSerialNumber (Serial) and SystemUUID (SmUUID) to generated values. Change ROM to your network card's MAC address without the `:` character. [**How to get MAC Address?**](https://www.wikihow.com/Find-the-MAC-Address-of-Your-Computer)
  5. Boot it!

If audio does not work for you you have to change layout-id for your audio chipset. Find your codec [**here**](https://github.com/acidanthera/applealc/wiki/supported-codecs) and try setting `alcid` in `boot-args` parameter to every layout-id values from AppleALC wiki  until you get layout-id correct for your motherboard.

**You CAN NOT use SMBIOS from this repository, it MUST be unique for every macOS installation**

## Guides
**If you have any problems with installation or booting your macOS, kernel panics or another system related issue check OC configuration guide**
**If something else isn't working properly (for example USB ports, iServices, DRM/Netflix) check Post-Install guide**
 - Creating USB installer: [**\*click\***](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/)
 - OpenCore configuration: [**\*click\***](https://dortania.github.io/OpenCore-Install-Guide/config.plist/sandy-bridge.html)
 - Post-Install: [**\*click\***](https://dortania.github.io/OpenCore-Post-Install/)
 - Troubleshooting: [**\*click\***](https://dortania.github.io/OpenCore-Post-Install/)
 - ACPI patching: [**\*click\***](https://dortania.github.io/Getting-Started-With-ACPI/)
 - USB mapping: [**\*click\***](https://dortania.github.io/OpenCore-Post-Install/usb/)

If you have any other questions or issues, feel free to ask on [**r/Hackintosh Discord**](https://discord.gg/2QYd7ZT)

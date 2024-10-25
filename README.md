# ThinkPad-E14-Gen-5-Hackintosh
macOS Sequoia on Lenovo Thinkpad E14 Gen 5 21JRS00U00 - AMD Ryzen 7530U W/ Vega 7 (Barcelo refresh GPU)



Hardware Requirements:

Lenovo ThinkPad E14 Gen 5

A compatible USB drive (at least 16GB)

## A macOS installer (Follow Dortina guide, Online recovery installer) <a id='[ss A macOS installer (Follow Dortina guide, Online recovery installer)](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/windows-install.html#downloading-macos)'></a>

Once your USB installer is ready copy the EFI folder to USB. (CHECK REASESES TO DOWNLOAD EFI)

Whats working

CPU	AMD Ryzen 7 7530U 6 Cores / 16 Threads	✅ (Patched with AMD patches.plist)

AMD Cpu management ✅ (Download AMD Power Gadget: https://github.com/trulyspinach/SMCAMDProcessor/releases/download/0.7.2f1/AMD.Power.Gadget.app.zip

iGPU	AMD Radeon Graphics 2GB	✅ (Via Nooted-red) (Make sure to increse Vram in bios atlest 2 GB (BIOS->IO->dispay->vmram)

NVMe	Samsung SSD 256GB for macOS / WD 500GB SSD	✅

Audio	Realtek	✅ (Used Apple ALC with aclid=21 in boot-args)

Ethernet	Realtek RTL8168/8111	✅

Brightness Keys / Volume Keys ✅

Touchpad ✅

Trackpoint ✅

HDMI port ✅ 

SMBIOS	MacBookPro16,3 (serial number generated with GenSMBIOS)	✅

OS	macOS Sonoma 14.5 ✅

Whats not working

Wifi (Realtek 8852be) ❌ (Im using Tp-link TL-WN725N Usb wifi which comes with latest OSX drivers)

Bluetooth ❌

Fingerprint ❌

Virtualization (Not supported on AMD, Not recommended using Virtual-box v6.1) ❌

Sleep / Wake ❌


BIOS SETTINGS:

Secureboot OFF

Device Guard Disabled

Increase Vram for display (2GB minimum)

Disable Fingerprint in IO section.


IMPORTANT NOTES DONT SKIP!!

When instalation is Finished and its booted, Download propertree then open the Config.plist from USB>EFI>OC>config.plist, Go to Kernal then ADD section, Find Nooted-red.kext then enable it making it True. (This will enable iGPU)



Credits

Apple for macOS.

Acidanthera for OpenCore and all the lovely hackintosh work.

Dortania For great and detailed guides.


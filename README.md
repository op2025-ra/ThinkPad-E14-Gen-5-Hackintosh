# ThinkPad-E14-Gen-5-Hackintosh
macOS Sequoia on Lenovo Thinkpad E14 Gen 5 21JRS00U00 - AMD Ryzen 7530U W/ Vega 7 (Barcelo refresh GPU)



Hardware Requirements:

Lenovo ThinkPad E14 Gen 5

A compatible USB drive (at least 16GB)

## A macOS installer (Follow Dortina guide, Online recovery installer) <a id='[ssFeatures](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/windows-install.html#downloading-macos)'></a>

Whats working

CPU	AMD Ryzen 7 7530U 6 Cores / 16 Threads	✅ (Patched with AMD patches.plist)

AMD Cpu management ✅ (Download  ## AMD Power Gadget <a id='[ssFeatures](https://github.com/trulyspinach/SMCAMDProcessor/releases/download/0.7.2f1/AMD.Power.Gadget.app.zip)'></a> )

iGPU	AMD Radeon Graphics 2GB	✅ (Via Nooted-red) (Make sure to increse Vram in bios atlest 2 GB (BIOS->IO->dispay->vmram)

NVMe	Samsung SSD 256GB for macOS / WD 500GB SSD	✅

Audio	Realtek	✅ (Used Apple ALC with aclid=21 in boot-args)

Ethernet	Realtek RTL8168/8111	✅

Brightness Keys / Volume Keys ✅

Touchpad ✅

Trackpoint ✅

HDMI port ✅

SMBIOS	MacBookPro16,3 (serial number generated with GenSMBIOS)	✅

OS	macOS Sonoma 14.5

Whats not working

Wifi (Realtek 8852be) ❌ (Im using Tp-link TL-WN725N Usb wifi which comes with latest OSX drivers)

Bluetooth ❌

Virtualization (Not supported on AMD, Not recommended using Virtual-box v6.1) ❌

Sleep / Wake ❌




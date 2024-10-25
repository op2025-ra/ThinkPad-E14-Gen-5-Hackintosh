# ThinkPad-E14-Gen-5-Hackintosh

macOS Sequoia on Lenovo Thinkpad E14 Gen 5 21JRS00U00 - AMD Ryzen 7530U W/ Vega 7 (Barcelo refresh GPU)



Hardware Requirements:

Lenovo ThinkPad E14 Gen 5

A compatible USB drive (at least 16GB)

## A macOS installer (Follow Dortina guide, Online recovery installer) <a id='[ss A macOS installer (Follow Dortina guide, Online recovery installer)](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/windows-install.html#downloading-macos)'></a>

Once your USB installer is ready copy the EFI folder to USB. (CHECK REASESES TO DOWNLOAD EFI)

# Whats working

CPU	AMD Ryzen 5 7530U 6 Cores / 16 Threads	✅ (Patched with AMD patches.plist)

AMD Cpu management ✅ (Download AMD Power Gadget to control CPU)

iGPU	AMD Radeon Graphics 2GB	✅ (Via Nooted-red) (Make sure to increse Vram in bios atlest 2 GB (BIOS->IO->dispay->vmram) READ Important notes down below!

NVMe	Samsung SSD 256GB for macOS / WD 500GB SSD	✅

Audio	Realtek	✅ (Used Apple ALC with aclid=21 in boot-args)

Ethernet	Realtek RTL8168/8111	✅

Brightness Keys / Volume Keys ✅

Touchpad ✅

Trackpoint ✅

HDMI port ✅ 

SMBIOS	MacBookPro16,3 (serial number generated with GenSMBIOS)	✅

OS	macOS Sonoma 14.5 ✅




# Whats not working

Wifi (Realtek 8852be) ❌ (Im using Tp-link TL-WN725N Usb wifi which comes with latest OSX drivers)

Bluetooth ❌

Fingerprint ❌

Virtualization (Not supported on AMD, Not recommended using Virtual-box v6.1) ❌

Sleep / Wake ❌






# BIOS SETTINGS:

Secureboot OFF

Device Guard Disabled

Increase Vram for display (2GB minimum)

Disable Fingerprint in IO section.





# IMPORTANT NOTES DONT SKIP!!

When installation is Finished and booted into macOS, Download propertree then open the Config.plist from USB>EFI>OC>config.plist, Go to Kernal then ADD section, Find Nooted-red.kext (It shounld be no. 5) then enable it making it True.  Enableing it now beacuse not recommended duruing installation.







# Credits

Apple for macOS.

Dortania For great and detailed guides.






# Legal Disclaimer

This material is provided solely for educational and testing purposes. The author does not condone or encourage any illegal activities, including but not limited to the violation of software license agreements, terms of service, or copyright laws. Building or using a Hackintosh — a non-Apple computer running macOS — may violate Apple's End User License Agreement (EULA) and could be illegal in certain jurisdictions.

By following this material, you understand that you assume full responsibility for any legal consequences, technical issues, or damages that may arise, including but not limited to violations of Apple's terms of service, potential breaches of applicable laws, and the invalidation of warranties. The author is not liable for any losses, damages, legal actions, or technical malfunctions resulting from the use of this guide.

The author explicitly does not endorse or encourage the illegal use of macOS or other software in any way that infringes upon intellectual property rights, terms of service, or other legal agreements. The material is intended to be used for testing in environments where such use is permitted.

Before proceeding, users are strongly advised to consult with a legal professional to understand the legality of building or using a Hackintosh in their specific region or jurisdiction. All actions undertaken by the reader are done at their own risk and discretion.

By using this material, you agree that any risks involved are your own responsibility, and you indemnify the author from any legal or financial consequences that may arise from your actions.


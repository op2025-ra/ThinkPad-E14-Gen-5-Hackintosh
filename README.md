# ThinkPad-E14-Gen-5-Hackintosh

macOS Sequoia on Lenovo Thinkpad E14 Gen 5 21JRS00U00 - AMD Ryzen 7530U with/ Vega 7



Hardware Requirements:

Lenovo ThinkPad E14 Gen 5

A compatible USB drive (at least 16GB)

## A macOS installer (Follow Dortina guide, Online recovery installer) <a id='[ss A macOS installer (Follow Dortina guide, Online recovery installer)](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/windows-install.html#downloading-macos)'></a>

Use rufus to format disk. Make Boot selection = non bootable.

# Whats working

CPU	AMD Ryzen 5 7530U 6 Cores / 12 Threads	✅ (Patched with AMD patches.plist)

AMD Cpu management ✅ (Download AMD Power Gadget to control CPU)

iGPU	AMD Radeon Graphics 2GB	✅ (Via Nooted-red) (Make sure to increse Vram in bios atlest 2 GB (BIOS->IO->dispay->frame buffer)

NVMe	Samsung SSD 256GB for macOS / WD 500GB SSD	✅

Audio	Realtek	✅ (Used Apple ALC with aclid=21 in boot-args)

Ethernet	Realtek RTL8168/8111	✅

Brightness Keys / Volume Keys ✅

Touchpad ✅ 

Trackpoint ✅

HDMI port ✅ 

SMBIOS	MacBookPro16,3 (serial number generated with GenSMBIOS)	✅





# Whats not working

Wifi (Realtek 8852be) ❌ (I use Tp-link TL-WN725N Usb wifi which comes with latest OSX drivers)

Bluetooth ❌

Fingerprint ❌








# BIOS SETTINGS:

Secureboot OFF

Device Guard Disabled

Set frame buffer in display (2GB minimum)

Disable Fingerprint in IO section.




# Credits

Apple for macOS.

Dortania For great and detailed guides.






# Legal Disclaimer

This material is provided solely for educational and testing purposes. The author does not condone or encourage any illegal activities, including but not limited to the violation of software license agreements, terms of service, or copyright laws. Building or using a Hackintosh — a non-Apple computer running macOS — may violate Apple's End User License Agreement (EULA) and could be illegal in certain jurisdictions.

By following this material, you understand that you assume full responsibility for any legal consequences, technical issues, or damages that may arise, including but not limited to violations of Apple's terms of service, potential breaches of applicable laws, and the invalidation of warranties. The author is not liable for any losses, damages, legal actions, or technical malfunctions resulting from the use of this guide.

The author explicitly does not endorse or encourage the illegal use of macOS or other software in any way that infringes upon intellectual property rights, terms of service, or other legal agreements. The material is intended to be used for testing in environments where such use is permitted.

Before proceeding, users are strongly advised to consult with a legal professional to understand the legality of building or using a Hackintosh in their specific region or jurisdiction. All actions undertaken by the reader are done at their own risk and discretion.

By using this material, you agree that any risks involved are your own responsibility, and you indemnify the author from any legal or financial consequences that may arise from your actions.


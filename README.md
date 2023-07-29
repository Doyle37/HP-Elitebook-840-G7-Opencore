# HP-Elitebook-840-G7-Opencore
macOS Ventura on HP Elitebook 840 G7
<p align="center">
  <img src="https://github.com/Doyle37/HP-Elitebook-840-G7-Opencore/blob/main/my_hpmac.jpg">
</p>
<h4 align="center"> No two hackingtoshes are the same! </h4>
<p align="center">
  HP EliteBook 840 G7 Hackintosh based on OpenCore configuration 
</p>

## Info and Tools  💻

- macOS: Ventura 13.0.1
- OpenCore: 0.93
- Tools needed: Opencore Configutation, OCAuxiliaryTools, Hackintool, MaciASL, PlistEdit Pro, IORegistryExplorer...

## Starting points

- Short answer: Download this EFI to a USB drive
- Long answer: [Dortania How-to](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/)
  
## Hardware  💻

Type | Spec | Status
:---------|:---------|:----------
Model Name      | HP Elitebook 840 G7 | ✅
CPU              | Intel(R) Core(TM) i7-10610U CPU @ 1.80GHz (max 4.90Ghz) Comet Lake | ✅
RAM           | 16 GB 2666 MHz DDR4 | ✅
Graphics | Intel® UHD Graphics 620 | ✅
SSD             | Intel M.2 512GB NVMe PCIe | ✅
Wi-Fi & Bluetooth             | Intel | ✅
Audio       | Realtek ALC285 | ✅

## What's working  💻
  
Type | Status
:---------|:---------
Almost everything |  ✅  
Intel HD Graphics             |  ✅  
HDMI                                |  ✅  
Audio          |  ✅  
Wi-Fi and Bluetooth         |  ✅  
USB ports        |  ✅  
Touchpad    |  ✅  
Battery status   |  ✅  
Camera   |  ✅    
Shutdown / Reboot   |  ✅  
Fn keys   |  ✅  
*Sleep / Hibernation / Wake   |  ✅ 

## What's not working  💻

Type | Status
:---------|:--------- 
Built-in Microphone   |  ❌ (It seems that there is no way out as it is internaly unsupported).
Fingerprint Reader   |  ❌ (None with this hackintosh type).

## Note  💻

Type | Info | Status
:---------|:---------|:----------
SMBIOS Settings  | With GenSMBIOS [Opencore Configutation or OCAuxiliaryTools], generate your own SMBIOS MBP16,3 |  ⚠️
Fn keys  | Some keys are not fully functional (use menu bar instead) |  ⚠️
Sleep/Wake  | This is a headache for most hackintoshes. Sleep/Wake works just fine with Auto-sleep or choosing Sleep from the menu. It does not work with mere lid closing. |  ⚠️


## Credits
  
 - [Dortania](https://dortania.github.io): Great OpenCore sources and tutorials for developing OpenCore and building hackintosh.
 - [Apple](https://www.apple.com) for macOS.
 - [Acidanthera](https://github.com/acidanthera) for most of the kexts.
 - And anyone else that has helped to develop and improve hackintoshing from GitHub, Reddit, InsanelyMac, Tonymacx86, EliteMacx86, Olarila, etc.

 

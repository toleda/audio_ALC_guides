Problem Reporting - Realtek ALC AppleHDA_v1.0  
![alt text](https://github.com/toleda/audio_ALC_guides/blob/master/xsound.jpeg)  
# Problem Reporting - Realtek ALC AppleHDA [Guide]
Realtek ALC/Desktop: 269(1), 283(1), 885, 887, 888, 892, 898 and 1150 on board audio  (1) BRIX/NUC only  
Supports OS X: 10.11, 10.10, 10.9 and 10.8 
Native AppleHDA

**Problem Reporting/Support for all Realtek ALC AppleHDA Guides**

Change Log  

1.	**v1.0 - 1/21/15: El Capitan/10.11.x**

**Troubleshooting** 

1. [Realtek ALC AppleHDA](https://github.com/toleda/audio_ALC_guides/blob/master/Realtek%20ALC%20AppleHDA.pdf)

    1. Installation
    2. Details/Support  
    3. Troubleshooting
2. [Realtek ALC guides](https://github.com/toleda/audio_ALC_guides)

	1. No Audio Devices.pdf
		1.	No audio devices, no sound, no codec
	1.	No Sound.pdf
		1.	Audio devices present, no sound when selected
	1.	No Audio After Sleep/Wake.pdf
		1.	No audio devices on wake


**Tools**

1. [IOReg_v2.1](https://github.com/toleda/audio_ALCInjection/blob/master/IORegistryExplorer_v2.1.zip) (select View Raw)
2. [DPCIManger](http://sourceforge.net/projects/dpcimanager/)  
3. [MaciASL](http://sourceforge.net/projects/maciasl/)
4. [audio_codecdetect.command](https://github.com/toleda/audio_ALCInjection/blob/master/audio_codecdetect.command.zip) (select View Raw)
5. Property List Editors -
	1. [Xcode](https://developer.apple.com/xcode/)  
	2. Property List Editor, PlistEdit Pro, TextEdit, etc.
	3. TextEdit, TextWrangler (last resort)
6. [Clover Configurator](http://www.osx86.net/files/file/49-clover-configurator/)
7. [Clover Wiki](http://clover-wiki.zetam.org/Home)

**Problem Reporting** (no files atached, no reply)

1.	Description of audio problem
2.	OS X version/motherboard model/BIOS version/processor/graphics
3.	Procedure/Guide used
4. Terminal/Shell/File/Export Text As. . . (if run)
	1. audio_codecdetect.command (Tools 4.)
	2. audio_cloverALC-1xx...command
	3. audio_pikeralphaALC-1xx...command
	4. audio_realtekALC-1xx...command
	5. AppleHDA8Series.sh
	6. audio_cloverHDMI-1xx...command
5.	Copy of IOReg - IOReg_v2.1/File/Save a Copy As…, verify file (Tools 1.)
6. Copy Of Console/All Messages (last boot)/File/Save a Copy As..
7.	Installed S/L/E/AppleHDA.kext or AppleHDA8Series AppleHDAxxx kext
8.	Screenshot: 
	1. 	DPCIManager/Status (Tools 2.) 
	2. System Information/Hardware/Audio/Intel High Definition Audio (not Devices)
9. Terminal/Shell/File/Export Text As. . . (if run:)
	1. audio_cloverALC-1xx...command
	3. audio_pikeralphaALC-1xx...command
	4. audio_realtekALC-1xx...command
	5. AppleHDA8Series.sh
	6. audio_cloverHDMI-1xx...command
10. Chameleon (if installed)
	1. Extra/org.chameleon.Boot.plist
	2. DPCIManager/Misc/Boot Log (Tools 2.)
	3. Extra/dsdt.aml (if installed)
	4. Extra/ssdt.aml (if installed)
11.	Clover (if installed)
	1.	EFI/CLOVER/config.plist
	2.	DPCIManager/Misc/Boot Log (Tools 2.)
	3.	EFI/CLOVER/ACPI/Patched/dsdt.aml (if installed)
	4.	EFI/CLOVER/ACPI/Patched/ssdt.aml (if installed)

Post to (select one link):

1.	[Realtek ALC Audio - InsanelyMac.com](http://www.insanelymac.com/forum/topic/308387-el-capitan-realtek-alc-applehda-audio/page-1)  
2. [Realtek ALC Audio/Updates - tonymacx86.com](http://www.tonymacx86.com/audio/143757-audio-realtek-alc-applehda-guide.html)
3. [No audio - tonymacx86.com](http://www.tonymacx86.com/audio/143752-no-audio-devices-realtek-alc-applehda-guide.html)  
4. [No Sound - tonymacx86.com](http://www.tonymacx86.com/audio/143750-no-sound-realtek-alc-applehda-guide.html) 
5. [No Audio After Sleep/Wake - tonymacx86.com](http://www.tonymacx86.com/audio/151504-no-audio-after-sleep-wake-realtek-alc-applehda-fixes.html)  


toleda
https://github.com/toleda/audio_ALC_guides

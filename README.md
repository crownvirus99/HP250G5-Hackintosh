# HP 250 G5 (SkyLake) macOS Mojave

<img src="https://github.com/crownvirus99/HP250G5-Hackintosh/blob/master/Captura%20de%20Pantalla%202020-06-15%20a%20la(s)%2000.46.16.png?raw=true" height="400px">

Specs
======
**CPU:** Intel Core i5 6200U

**iGPU:** Intel HD520

**dGPU:** AMD Radeon R5 430M

**Network:** Realtek RTL8168H

**Network:** Qualcomm QCA9377

**RAM:** 12GB DDR4 2133MHz

**Audio:** Realtek ALC282

**BIOS:** Insyde UEFI, vF.

**Board:** HP 81EC

**HDD:** 1TB WDC WD10JPVX-60JC3T0 

What's working
============
* Audio. (Speaker and Headphone jack)
* Microphone. (Integrated and Headphone)
* Audio controls.
* LCD brightness.
* CPU Power Management. (Oficially supported)
* Metal. (Officially supported GPU)
* SD Card reader.
* Webcam.
* Bluetooth. (Fully Working with audio support, etc.)
* Ethernet.
* USB
* Trackpad (partial)
* HDMI
* Dual Booting (Windows and macOS)
* iMessage, FaceTime, iCloud.

&nbsp;

Not Working
=======
* Wifi (Only fix is replace Wifi card)
* Dedicated Radeon GPU (disabled by DSDT/SSDT Patch)
* Sleep (WIP) (Probably just need to patch usb number)
* HDMI Audio

&nbsp;

Problems
=======
* Brightness controls from keyboard. (WIP)
* Trackpad gestures.

&nbsp;

Untested
=======
* VGA
* USB 3.0 support (probably working)


List of Patches and kexts
==================
* RehabMan's Clover Config for HD520
* Descrete GPU Disabler Hotpath (SSDT-DDGPU)
* RealtekRTL8100 Kext
* AppleBacklightFixup
* FakeSMC
* Lilu
* VoodooPS2Controller
* WhateverGreen
* Apple ALC
* USBInjectAll.kext
* USB Port Limit Patch by PMHeart

Credits:
==================
RehabMan: [Laptop Config Guide.](https://github.com/RehabMan/OS-X-Clover-Laptop-Config) [DSDT Patch Guide.](https://www.tonymacx86.com/threads/guide-patching-laptop-dsdt-ssdts.152573/)

Striker on EliteMacx86: [Source.](https://www.elitemacx86.com/threads/guide-dell-inspiron-5559-intel-core-i5-6200u-8gb-ram-intel-hd-graphics-520.331/)

u/TheRacerMaster on Reddit: [Source.](https://www.reddit.com/r/hackintosh/comments/4e23w6/guide_native_audio_with_clover_applealckext/)**

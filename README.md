# LenovoP1Gen2-HackintoshEFI
A working EFI directory for Lenovo P1 Gen2 Hackintosh.
Tested with MacOS Catalina 10.15.
Not tested with newer versions.
Based on Clover 5118.

**Note**: The default configuration is for Xeon-based laptop with 4K display. You will find other configs fot other configuration in "configs" directory. 
The installer is in Chinese. Complete it and after that, change language and keyboard settings using System Preferences.

## What Works
* WiFi/Bluetooth/Ethernet (must use [HeliPort](https://github.com/OpenIntelWireless/HeliPort) as GUI)
* Display Brightness and full Display resolution with high DPI
* Graphics Acceleration (Integrated)
* Audio
* TouchPad/TrackPoint/Keyboard
* Battery Level/Charging
* USB
* Integrated Webcam

## Not Working
* Dedicated Graphics (NVIDIA Quadro)
* HDMI Port
* External Displays with USB-C
* Thunderbolt ports (not tested)

**Addendum**: Power management is very poor, battery tends to drain very fast. 
Need proper optimization with [CPUFriend](https://github.com/acidanthera/CPUFriend).

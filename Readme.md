# Gigabyte Aorus Ultra Z390 - OpenCore - macOS Catalina

This guide is using macOS Catalina 10.15.5, and OpenCore 0.5.9. Based upon Mac hardware:  
`Mac (Retina 5K, 27-inch, 2019) - iMac19,1` 

---

## Hardware
### Primary System
|Component|Product|
|---|---|
|CPU|Intel Core i9 9900K|
|MB|Gigabyte Aorus Ultra Z390 (rev 1)|
|GPU|AMD Radeon RX580|
|SSD|Samsung EVO 970 (NVMe - 1TB)|
|BT/Wi-Fi|Broadcom BCM94360CS2|

## What works
- Bluetooth & Wi-Fi
- AirDrop and other continuity features
- Audio (rear 3.5mm audio jack works, haven't tested the front)
- Shutdown / Restart / Sleep
- USB 3.0/3/1
- Thunderbolt 3
- Emulated NVRAM
- NVMe
- Netflix / DRM

## What you need to change
Change the following settings in OC/config.plist (under the PlatformInfo section):
- MLB
- SystemSerialNumber
- SystemUUID 
This information can be easily changed using OpenCore Configurator. Which can be downloaded:  
1. Homebrew: `brew cask install opencore-configurator`
2. Website: [mackie100projects](https://mackie100projects.altervista.org/download-opencore-configurator/)  


## Changelog
- **3 July 2020:** 
    - Initial Commit
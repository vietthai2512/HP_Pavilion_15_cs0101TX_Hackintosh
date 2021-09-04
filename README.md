# HP Pavilion 15 cs0101TX Hackintosh with OpenCore
## Overview
 <summary><strong>macOS Big Sur</strong></summary>
 
![screenshot](images/Big-Sur-2020-11-26.png)

<summary><strong>OpenCore Boot Menu</strong></summary>
 
![screenshot](images/OpenCore068-background.png)

<details>
 <summary><strong>macOS Catalina</strong></summary>
 
![screenshot](images/Catalina-2020-11-15.png)

 </details>
 
- macOS version: **Big Sur** **11.4**
- OpenCore version: **0.7.2**

## Hardware Specifications 
| Category | Detail |
|:----:|:----:|
| Product name | HP Pavilion - 15-cs0101tx |
| Microprocessor | Intel® Core™ i5-8250U (1.6 GHz base frequency, up to 3.4 GHz with Intel® Turbo Boost Technology, 6 MB cache, 4 cores)|
| IGPU | Intel® UHD Graphics 620 |
| DGPU | NVIDIA® GeForce® MX130 | 
| Memory | 12GB DDR4-2400 SDRAM (1 x 4 GB + 1 x 8 GB) |
| Drives | Toshiba 1 TB 5400 rpm SATA & Samsung 970 Evo 250GB NVMe M.2 | 
| Display | 15.6" diagonal FHD SVA anti-glare WLED-backlit (1920 x 1080) |
| Keyboard | Full-size island-style keyboard with numeric keypad, PS/2 |
| Pointing device | HP Imagepad with multi-touch gesture support, PS/2 |
| Wireless connectivity | Intel® 802.11a/b/g/n/ac (1x1) Wi-Fi® and Bluetooth® 4.2 Combo (Intel® Dual Band Wireless-AC 3168) |
| Network interface | Integrated 10/100/1000 GbE LAN (Realtek RTL8111) |
| Expansion slots | 1 multi-format SD media card reader |
| External ports | 2 USB 3.1 Gen 1 (Data transfer only); 1 HDMI 1.4; 1 headphone/microphone combo; 1 USB 3.1 Type-C™ Gen 1 (Data Transfer Only); 1 RJ-45 | 

## Current issues
- ~~Sleep: DarkWake from Normal Sleep [CDN] : due to XHC HDAS/ Using AC (Charge:0%)~~ Fixed.
- ~~iMessages and FaceTime~~ Continuity services aren't working, waiting for a new version of AirportItlwm.
- ~~HDMI (not tested yet)~~ <details><summary>Fixed</summary>![screenshot](images/HDMI-working.jpg)</details>

## Note
- Generate your own MLB, SystemSerialNumber, SystemUUID (https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/kaby-lake.html#platforminfo)

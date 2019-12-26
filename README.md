# Dell Latitude 7390 Hackintosh EFI

## Tested macOS Version
10.15: macOS Catalina 10.15.1 (19B88)

## System Configuration
- Intel i5 8350U
- Intel UHD 620
- WD BLACK *SN750* 512GB
- DW1820A (0VW3T3)

## What's working
 - [x] Audio w/ headphone jack

 - [x] CPU Speedstep

 - [x] iGPU acceleration

 - [x] Battery Management

 - [x] Backlight

 - [x] Ethernet

 - [x] HDMI

 - [x] Sleep & Wake

 - [x] Smart Touchpad w/ Gestures (using I2C)

 - [x] WebCam

 - [x] USB 3.0

 - [x] Sleep From (Lid)

 - [x] WiFi (2.4 + 5GHz) & BT by using DW1820A

 - [x] Handoff, Airdrop & Sidecar (Sidecar for Catalina)

 - [x] Native hotkey support w/ Fn keys

 - [x] USB-C charging

 - [x] USB-C DP-alt Mode

 - [ ] USB-C Data transfer*

   *Partially working, needs to plug a device before boot in order that macOS could pick up USB-C controller, then it's plug-n-play and hot-plug&unpluggable in macOS. It may cause problems when lid closed or the system sleeps.

## What's not working(I have found)
- Trackpad Keys
- Smart card reader
- MicroSD card

## What's not tested yet
- Audio over HDMI
- Thunderbolt
- WWAN card

## Credit
Swung0x48/Dell-Latitude-7390-7490-Hackintosh-EFI：https://github.com/Swung0x48/Dell-Latitude-7390-7490-Hackintosh-EFI
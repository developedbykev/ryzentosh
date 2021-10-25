# OpenCore EFI for AMD Ryzen Hackintosh

## Specifications
 | Component         | Model                   |
 |-------------------|-------------------------|
 | CPU               | AMD Ryzen 5 2600        |
 | Motherboard       | MSI B350M PRO-VDH       |
 | RAM               | 16GB (2x8GB) DDR4-2666  |
 | Audio Chipset     | Realtek® ALC892         | 
 | GPU               | Sapphire RX 570 8GB     |
 | WiFi / Bluetooth  | BCM94360CS2 802.11ac    |
 | OS Disk (SATA)    | Kingston A400 240GB SSD |
 
 **macOS Version**: 11.6 (20G165)
 **OpenCore Version**: 0.7.4
 **SMBIOS**: iMacPro1,1 (iMac Pro 2017)
 
![Bildschirmfoto 2021-04-28 um 11 58 05](https://user-images.githubusercontent.com/59840959/116385488-20085d80-a819-11eb-87e4-b76fdec64cd1.png)

## Working
- Sleep & Wake
- WiFi and Bluetooth
- Continuity, Handoff & AirDrop
- iCloud Drive & Photos
- Xcode Simulator
## Not working
- iMessage
- Math Kernel Library (MKL) -> [Fix](https://gist.github.com/naveenkrdy/26760ac5135deed6d0bb8902f6ceb6bd)
- Android Emulator (Intel HAXM)

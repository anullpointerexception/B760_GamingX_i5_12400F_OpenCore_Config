# OpenCore Configuration for Gigabyte B760 GamingX DDR4 Motherboard + Intel Core i5 12400F
OpenCore Configuration for Gigabyte B760M Gaming X DDR4 + i5 12400F

Current supported macOS Versions:
- macOS Sonoma (since 1.1.0 version)
- macOS Ventura (since 1.0.0 version)
- macOS Monterey (since 1.0.0 version)

Note for 1.1.0 Version:
- In order to use the WiFi card that is stated in the configuration below, you need to apply root patches after installing Sonoma by using the OpenCore Legacy Patcher. The necessary kexts (AirportBrcmFixup, AMFIPass, IOSkywalkFamily, IO80211FamilyLegacy) + the necessary adaptions to config.plist are already included. 

Whats currently working?
- DRM
- Audio
- USB3.0 and 2.0
- iMessage / iCloud
- Bluetooth
- WiFi
- AirDrop
- PowerManagement added (CPUFriend + CPUFriendDataProvider) -> Working
- Sleep
- SMBUS
- PCI Information

Whats not working?
- CFG Lock

This configuration is only for the following setup:

- CPU: Intel Core i5 12400F
- GPU: AMD Radeon RX5700
- RAM: 16GB 3200Mhz DDR4
- Motherboard/Laptop Make and Model: Gigabyte B760M Gaming X DDR4
- Audio Codec: ALC897
- Ethernet Card: Realtek RTL8125BG
- Wifi/BT Card: ABWB 802,11 AC WI-FI + Bluetooth 4.0 PCI-Express (PCI-E) BCM94360CS2

Note: 


Pictures:
![Bildschirmfoto 2023-10-28 um 14 22 03](https://github.com/anullpointerexception/B760_GamingX_i5_12400F_OpenCore_Config/assets/80070874/29d2ce22-c001-4bda-bef1-c1abf863b96f)
![Bildschirmfoto 2023-10-27 um 15 00 57](https://github.com/anullpointerexception/B760_GamingX_i5_12400F_OpenCore_Config/assets/80070874/518c526f-22d4-4505-b9e5-83c758cdcc13)
![Bildschirmfoto 2023-10-27 um 15 01 11](https://github.com/anullpointerexception/B760_GamingX_i5_12400F_OpenCore_Config/assets/80070874/e8d320bc-6fcb-4316-bdc1-2e34550c03e0)

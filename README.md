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

Pictures
![Bildschirmfoto 2023-11-01 um 19 14 09](https://github.com/anullpointerexception/B760_GamingX_i5_12400F_OpenCore_Config/assets/80070874/9fa4865a-1e8f-4a72-97cf-fdfabf000421)
![Bildschirmfoto 2023-11-01 um 19 10 46](https://github.com/anullpointerexception/B760_GamingX_i5_12400F_OpenCore_Config/assets/80070874/df141b82-6757-4be5-bc7f-ea848009b989)
![Bildschirmfoto 2023-11-01 um 19 12 00](https://github.com/anullpointerexception/B760_GamingX_i5_12400F_OpenCore_Config/assets/80070874/1b92020f-e5ed-4adf-801a-1900aef139d6)
![Bildschirmfoto 2023-11-01 um 19 12 15](https://github.com/anullpointerexception/B760_GamingX_i5_12400F_OpenCore_Config/assets/80070874/1d2c7b9e-409d-4462-b45c-d726d4d67fd9)

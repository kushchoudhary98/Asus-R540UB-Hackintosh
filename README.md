# Asus-R540UB-Hackintosh (OpenCore 1.0.0) (Intel i5 8250u)

![About this Mac](.assets/docs/about_this_mac.png)

## Intro

:warning: **This is only for educational purposes.**

:warning: **This is not a guide**, please refer to [Dortania](https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html) before doing anything. I am not responsible for any damage. This OpenCore configuration is optimized for my specific hardware, so please use it only as a reference or if you happen to have the same or similar hardware.

:information_source: The EFI's have been tested on Sierra, Moneterey, Ventura, Sonoma and Sequoia on my ASUS R540UB.

## Specs

| Component      | Brand                                     |
|----------------|-------------------------------------------|
| **CPU**        | `Intel Core i5-8250U @ 1.8 GHz`           |
| **iGPU**       | `Intel UHD Graphics 620`                  |
| **RAM**        | `8 GB 2400 MHz DDR4` |
| **Storage**    | `CONSISTENT SSD S6 256GB`  |
| **Audio**      | `Realtek ALC256`                |
| **WiFi Card**  | `Atheros AR9565`   |
| **OS**         | `macOS Ventura 15.1`             |

## Supported versions

| Version 	| Supported 	|
|---	|---	|
| Sierra 10.12.x 	| :white_check_mark:	|
| High Sierra 10.13.x 	| Not tested but should work	|
| Mojave 10.14.x 	| Not tested but should work	|
| Catalina 10.15.x 	| Not tested but should work	|
| BigSur 11.x 	| Not tested but should work 	|
| Monterey 12.x 	| :white_check_mark: 	|
| Ventura 13.x 	| :white_check_mark: 	|
| Sonoma 14.x 	| :white_check_mark: 	|
| Sequoia 15.x 	| :white_check_mark: 	|


## :white_check_mark: Working

- [x] CPU power management.
- [x] Graphics acceleration.
- [x] iGPU Hardware Decoding.
- [x] Battery read-out.
- [x] Keyboard & trackpad with all macOS gestures.
- [x] Wi-Fi (Requires spoofing).
- [ ] Bluetooth.
- [x] USB ports.
- [x] Audio (Internal speakers, 3.5mm headphone jack).
- [x] Internal microphone.
- [x] VGA WebCam.
- [ ] AirDrop & Handoff.
- [x] iCloud & App Store.
- [x] iMessage & FaceTime.

## :x: Not working

- Bluetooth is not yet fixed (There is a chance it might work, will update it on this repository).
- AirDrop and Handoff are not working(for now) since they require bluetooth to be turned on.

## Wi-Fi (Atheros AR9565)
Supported upto High Sierra (Support dropped in Mojave).
<br />
<br />
**macOS version <= 10.14 :**
<br />
Follow this guide [here](https://www.insanelymac.com/forum/topic/328426-qualcomm-atheros-ar9565-wireless-for-os-x-108-1014/)

**macOS version >= 12 :**
<br />
Follow this guide [here](https://www.insanelymac.com/forum/topic/359007-wifi-atheros-monterey-ventura-sonoma-sequoia-work/)

## Known Issues
- When you switch Youtube Video to full-screen, screen flickers!!! *No such issue while using Google Chrome to watch youtube videos*.
- The trackpad and audio sometimes stops working(rarely). *Just wait for few minutes or sleep and wake up to make it work again*
<br /><br />
If you encounter any issue, please file a bugreport.

## Credits

* **Apple** for macOS
* [**Acidanthera**](https://github.com/acidanthera) for OpenCore and the majority of the kexts
* [**RehabMan**](https://github.com/RehabMan) for contributing to most of the ACPI patching guides I used
* [**PG7**](https://www.insanelymac.com/forum/profile/1361829-pg7/) for wifi patching.
* **every other people that contributed to the hackintosh world.**


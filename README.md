<img align="right" src="https://github.com/Errrneist/Hackintosh-Razer-Blade-Advanced/blob/master/IMG/opencore_logo.png" alt="OpenCore" width="225">

# Hackintosh for Razer Blade Advanced 15
![MODEL](https://img.shields.io/badge/MODEL-RZ09--0301-blue)
[![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg)](https://github.com/996icu/996.ICU/blob/master/LICENSE)

<img align="right" src="https://github.com/Errrneist/Hackintosh-Razer-Blade-Advanced/blob/master/IMG/big_sur_critter.jpg" alt="Critter" width="250">


> Don't assume it is raining if you hear wind blowing. ——— The Elder.    
#### Developer: [@Errrneist](https://www.tonymacx86.com/members/errrneist.1550861/)
#### Don't forget to star this project if you like it! 
#### READ THE ENTIRE README.MD BEFORE YOU TAKE ANY ACTION.


## Disclaimer
* Note that by using any file or code in this repository you agree to this disclaimer.
* This project is issued under the [MIT License](https://opensource.org/licenses/MIT) provided as-is, can potentially brick your machine, and may break your warranty. I am not responsible for any damage that is caused by you using anything in this Repo.

## Update

##### Recent | [Changelog Archive](https://github.com/Errrneist/Hackintosh-Razer-Blade-Advanced/blob/master/changelog.md)
* [20201011] I got a newer Razer Blade (10th Gen) so I will not move forward with this project. Well, everything was done.
* [20200815] Released v11.0-3.1 minor update. Added some attempt support for Thunderbolt 3. 
* [20200807] Released v11.0-3.0 major update. Big Sur!
* [20200524] Released v10.15-2.4 major update, patched iGPU, fixed gliching issue.
* [20200518] Released v10.15-2.3 major update, transitioned to OpenCore.
* [20200518] Updated several sections of README.MD.
* [20200517] Starting from v2.X, this project will be moving to OpenCore.

## Help Needed
* Thunderbolt is not working. I tested a eGPU and a NVMe drive.
* If anyone know anything about Titan Ridge Thunderbolt 3 on OpenCore feel free to open an issue! 

## System Information
| Part | Compatibility | Model | 
| --- | --- | --- |
| Machine | Functional | Razer Blade 15 Advanced 2019 RZ09-0301 |
| macOS | Functional | macOS 11.0 Big Sur Beta |
| BIOS | Functional | 1.04 |
| CPU | Functional | Intel® Core™ i7-9750H CFL-R Processor 2.60GHz 12MB 6C12T |
| Chipset | Functional | Intel® Cannon Point HM370 PCH 10/B0 |
| RAM | Functional | Micron 16ATF2G64HZ-2G6E1 32GB DDR4 2666GHz SODIMM |
| SSD | Functional | Sabrent 2TB Rocket NVMe v1.3.0 PCIe 3.0 M.2 2280 SSD |
| iGPU | Functional | Intel® UHD Graphics 630 2048MB GT2 |
| Wi-Fi | Functional | Broadcom BCM94360CS2 802.11AC with NGFF Adapter |
| Bluetooth | Functional | Broadcom 20702 Bluetooth 4.0 |
| Webcam | Functional | Integrated 720P Camera |
| Trackpad | Functional | ELAN 0406 I2C HID |
| Microphone | Functional | Integrated Dual-Array Microphone |
| Internal Sound Card | Functional | Realtek ALC |
| External Sound Card | Functional | Sound Blaster Play! 3 |
| Internal Screen | Functional | Sharp LQ156M1JW03 15.6' 1920x1080 240Hz |
| External Screen | Functional | Asus XG279Q 27' 2560x1440 144Hz |
| Battery | Functional | CNB1RC30 80219 mWh 17.359V |
| Mouse | Functional | Razer Viper Ultimate RZ30-030501 |
| Keyboard | Functional | Plum Niz 84EC (XRGB) Ble/35gf |
| Printer | Functional | HP DeskJet 1112 |
| Tablet | Functional | Wacom Intuos Pro M |
| USB DisplayLink | Functional | Plugable USB 3.0 Dual 4K HDMI 2.0 and Gigabit Ethernet Adapter |
| Thunderbolt 3 Chipset | Unfunctional | Intel JHL7540 Titan Ridge 2C 2019 (15E8) |
| Thunderbolt 3 Controller | Unfunctional | ADT Link R43SG-TB3 |
| External GPU | Unfunctional | SAPPHIRE RX 570 4GB GDDR5|
| Discrete GPU | Disabled | NVIDIA RTX 2070 Max-Q 8GB GDDR6 |
| IR Camera | Disabled | Integrated IR Windows Hello Camera |
  
## Issues & Solutions
### Issue Report
* We welcome people to submit issue and report them! This will help all of us to figure out what can be done to the laptop. Please file a issue in the **Issues** module.
* I recognize that there are a lot of Chinese speaking people participating in the discussion which is good! But if you can, please also leave an English version of your message when you post your discussion so we can have the world solve problems together.

### OpenCore
* [The Vanilla Laptop Guide](https://1revenger1.gitbook.io/laptop-guide/): OpenCore laptop guide and documentation.

### macOS
#### General Information
* [Hackintool: The Swiss army knife of vanilla Hackintoshing.](https://github.com/headkaze/Hackintool)
* [Volta: Undervolting software in macOS (untested yet).](https://volta.garymathews.com)
* [How to download a full ‘Install macOS’ app with software update in TERMINAL](https://scriptingosx.com/2019/10/download-a-full-install-macos-app-with-softwareupdate-in-catalina/)
* [Guide for mounting EFI using TERMINAL](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/blob/master/MOUNTEFI.MD): If you cannot mount EFI via Clover Configurator.

### Windows
##### Drivers
* Audio: [MEDIA_6.0.1.8437_WHQL_140133](https://github.com/Errrneist/Hackintosh-Razer-Blade-Advanced/tree/master/DRIVERS/WINDOWS/SOUND/MEDIA_6.0.1.8437_WHQL_140133).
* Wifi + Bluetooth (BCM94360CS2): [Apple Bootcamp Wifi + Bluetooth Drivers](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/releases/tag/v943602CS.1)
* Wifi (DW1830): [dell_1820a_558560_64_10.exe](https://github.com/Errrneist/Hackintosh-Razer-Blade-Advanced/blob/master/DRIVERS/WINDOWS/WIFI/dell_1820a_558560_64_10.exe)
* Bluetooth (DW1830): [broadcom_bt_1201940_64_413.exe
](https://github.com/Errrneist/Hackintosh-Razer-Blade-Advanced/blob/master/DRIVERS/WINDOWS/BLUETOOTH/broadcom_bt_1201940_64_413.exe).
   
### BIOS
* I strongly recommend following the steps from [Razer Blade 15 Advanced (Mojave and Catalina)](https://github.com/stonevil/Razer_Blade_Advanced_early_2019_Hackintosh) to modify your BIOS.
* Note that using other people's BIOS is generally a really, really bad idea. It WILL possibly block your machine. However, I will provide my BIOS as a reference under `./BIOS/afuwin.rom`.

### Audio
* KEXT required to enable Audio support: `AppleALC.kext`
* Make sure you inject audio `layout-id = 3`, not `1` in OpenCore `config.plist/NVRAM/Add/7C436110-AB2A-4BBB-A880-FE41995C9F82/boot-args` or in Clover, `config.plist/Devices/Audio`. 
 * Please share if you find out other working `layout-id`! 

### Wifi & Bluetooth
* In order to get Bluetooth and Wifi working, a wireless card replacement is needed.
* For now, the best card to use is BCM94360CS2 using a NGFF adapter which you can buy on eBay under $10. It has the highest performance among all other hackintosh-able wireless cards. It is natively supported in OpenCore (v2.X and above). For clover machines, you will want to use DW1830 with some additional kext. 
<img align="left" src="https://github.com/Errrneist/Hackintosh-Razer-Blade-Advanced/blob/master/IMG/wifi_adapter.jpeg" alt="adapter" width="1024">

* Broadcom Wifi Card Experiments:
  * BCM94360CS2 -> Wifi: Working, BT: Working.
  * BCM943602CS -> Wifi: Not Working, BT: Working.
  * BCM943602BAED (DW1830) -> Wifi: Not Working, BT: Working.

* Intel Wifi Cards: Someone got Intel AX Wifi working. 
  * Wifi: 
    * [itlwm: Repository](https://github.com/OpenIntelWireless/itlwm) 
    * [itlwm: Wiki](https://openintelwireless.github.io/itlwm/)
    *  I did not validated it on my machine just FYI.
  * BT: 
    * [IntelBluetoothFirmware: Repository](https://github.com/OpenIntelWireless/IntelBluetoothFirmware) 
    * This one I actually tested it on Big Sur using a AX200, it works but the connection quality is very poor.

### GPU
##### iGPU
* UHD 630 is supported from 2.X and above. With patched iGPU can achieve internal 240Hz.
* HDMI/mDP Port and USB-C to DP/HDMI/DVI Cables:
   * Long story short, it won't work. Why? Because all display output is hard wired to the NVIDIA GPU. You can confirm this by going into NVIDIA controler panel in Windows and see PhysX, and you can see all display output is wired to the NVIDIA card, while the eDP in screen display is wired to the iGPU. Therefore, since NVIDIA card won't work, also Optimus won't work, the mini-DP and HDMI port or USB-C display output just won't work because the display output is not wired to the iGPU. Not to mention you disabled dGPU in `config.plist/-wegnoegpu`. 
   
##### dGPU
* NVIDIA RTX 2070 Max-Q is not supported.
* A proper way to disable dGPU can be found here: [Patching to disable dGPU](https://github.com/stonevil/Razer_Blade_Advanced_early_2019_Hackintosh/issues/19#issuecomment-632171858) I just don't have the time and effort to do it right now (As of Sept 25, 2020) because a recent technical breakdown corrupted my macOS and Windows system. You'll have to do it separately on top of my configurations.
* [Apple and Nvidia Are Over: NVIDIA drops CUDA support for macOS.](https://gizmodo.com/apple-and-nvidia-are-over-1840015246)
* Currently, there is nothing we can do. Let's hope Apple and NVIDIA work together again. 

##### DisplayLink
* USB DisplayLink Display Output: 
  * Hardware
     * DisplayLink is a USB hardware based solution for display output. 
     * [Plugable USB3-6950-HDMI](https://www.amazon.com/Plugable-Ethernet-Supports-Displays-3840x2160/dp/B075HMWLJF/ref=sr_1_fkmrnull_1?keywords=Plugable+USB3-6950-HDMI&qid=1555380658&s=gateway&sr=8-1-fkmrnull). It is able to achieve 4K60P via the DisplayLink Chip. 
     * Screen I am using: Asus ROG Strix XG279Q (2560x1440, Native 144 Hz). 
  * Software
     * Normally, you should get driver from: [DisplayLink macOS Driver](https://www.displaylink.com/downloads/macos). 

<img align="right" src="https://github.com/Errrneist/Hackintosh-Razer-Blade-Advanced/blob/master/IMG/displayinfo.png" alt="DisplayInfo" width="1024">

### System Preferences
   * [How to customize the “About This Mac” section of a Mac, Joaquim Barbosa](https://www.idownloadblog.com/2017/01/13/how-to-modify-about-this-mac-hackintosh/).
     
### Thunderbolt
  * A more in detail Thunderbolt issue can be found on TonyMacX86: [Link](https://www.tonymacx86.com/threads/coffeelake-laptop-thunderbolt-3-egpu-not-working.302541/).
      
### Replace Thermal Paste:
   * WARNING: Not recommended. If you bend the copper plate the entire thing becomes useless. 
      
### Other Configurations:
| Owner | CPU | Model | Bootloader | Link |
| --- | --- | --- | --- | --- |
| stonevil | i7-8750H | RZ09-0288 | Clover | [Link](https://github.com/stonevil/Razer_Blade_Advanced_early_2019_Hackintosh)
| boyuanx | i7-9750H | RZ09-0301 | OpenCore | [Link](https://github.com/stonevil/Razer_Blade_Advanced_early_2019_Hackintosh/issues/23#issuecomment-629762916) |

### More Hackintosh EFI Resource:
   * Hackintosh Laptop Index: EFI for other laptop might help as a useful reference. Navigate to [here](https://github.com/daliansky/Hackintosh) (cr. [daliansky](https://github.com/daliansky)) if you need more reference from other laptops. Note: The word “链接” in Chinese means “link” so click on it it will take you to the repo you are looking for.

## Contributors
* Note: There is no order in the ranking of names. 
* This list may not be complete! Feel free to let me know. Sorry for any inconvience.

| Name | Contributions |
| --- | --- |
| [Rehabman](https://github.com/RehabMan) | Many kernel extensions and guides. |
| [Acidanthera](https://github.com/acidanthera) | OpenCore, Lilu.kext, and WhateverGreen.kext. |
| [Jack Boyuan Xu](https://github.com/boyuanx) | OpenCore [solution](https://github.com/stonevil/Razer_Blade_Advanced_early_2019_Hackintosh/issues/23#issuecomment-629762916). |
| [Myroslav Rys](https://github.com/stonevil) | Clover portion and BIOS modification. |
| [Avery Black](https://github.com/1Revenger1) | OpenCore Laptop Guide |
| [Alex James](https://github.com/al3xtjames) | TbtForcePower.efi |

## License
* This work is issued under the [996 License](https://github.com/996icu/996.ICU/blob/master/LICENSE) and [MIT License](https://opensource.org/licenses/MIT).


## Donate
* Donating to this project is optional as the intention of this project is build on each other's work and benefit everyone. 
* However, if you would like to buy me a coffee, you can do that using QR codes (WechatPay/AliPay or Venmo).
<img align="middle" src="https://github.com/Errrneist/Hackintosh-Razer-Blade-Advanced/blob/master/IMG/donate.png" alt="donate" width="800">



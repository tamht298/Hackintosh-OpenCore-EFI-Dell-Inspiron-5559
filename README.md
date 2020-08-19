# Hackintosh Dell Ins 5559:
## Result
![Image of installing's result](https://i.imgur.com/j8s5yHN.png)

## System's Configuration:
* Laptop Dell Ins 5559

| Specifications | Details                                                         |
| -------------- | --------------------------------------------------------------- |
| Laptop Model   | Dell Inspiron 5559                                              |
| Processor      | Intel Core i7-6500U @ 3.10GHz dual-core                         |
| RAM            | 2 X 8GB (SK Hynix DDR3L 1600MHz + Kingston DDR3L 8GB)                                 |
| Storage        | SSD Apacer AS450 2.5 inch 240GB Sata III AP240GAS450B                       |
| Graphics       | Intel HD Graphics 520                                           |
| Display        | LED HD 1366x768 (15.6 inches)                          |
| Network Card   | Network Card: Intel Dual Band Wireless-AC 3160 HMC WiFi Adapter |

* macOS Catatlina 10.15.6
* OpenCore 0.6.0

## Setup
1. Following this steps at [guideline][guideline]
2. Copy folder EFI in this repo and paste in your boot's usb
3. Ok & install now

### Fix some kext:
* Wifi: download the lastest Heliport release at [OpenIntelWireless's Repo][OpenIntelWireless's Repo] & download the lastest [itlwm kext][itlwm]. Install Heliport.dmg and open, then goto **System Preferences -> Users & Groups -> select Current User and add Heliport to Login Items**.
> Check below image to setup
![setup Heliport](https://i.imgur.com/cqNczip.png)

* Scrolling on trackpad & mouse: if you can't setup scrolling direction as windows os (trackpad: natural, mouse: non-natrual). 
Following steps: 
1. Download [Mos][Mos]
2. Setup like following picture
![setup Mos](https://i.imgur.com/XXWptNw.png)

## Not working
* Amd Radeon R5 M335
P/s: ***If you have any questions about this repo, please create new issuses.***

<!-- Markdown link & img dfn's -->
[guideline]: https://dortania.github.io/OpenCore-Install-Guide/
[OpenIntelWireless's Repo]: https://github.com/OpenIntelWireless/HeliPort/releases
[Mos]: https://mos.caldis.me
[itlwm]: https://github.com/OpenIntelWireless/itlwm/releases

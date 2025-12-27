# TouhouDeck
TouhouDeck is a script that provides a convenient way to set up and play the classic Touhou/Seihou games on the Steam Deck, or other Linux-based handheld PCs and devices.

# Contents  
- [Supported Titles](#supported-titles)<br>
- [Installation](#installation)
  - [PC-98 Titles (Touhou 1-5)](#pc-98-titles-touhou-1-5)
  - [Seihou Shuusou Gyoku](#seihou-shuusou-gyoku)

# Supported Titles
Version 1.0.0 of TouhouDeck will have compatibility with the following games:
| Game                          | Compatibility  |
| ----------------------------- | -------------- |
| ![](https://en.touhouwiki.net/images/thumb/1/11/Icon_th01.png/16px-Icon_th01.png) Highly Responsive to Prayers  | ✅ Compatible     |
| ![](https://en.touhouwiki.net/images/thumb/9/9f/Icon_th02.png/16px-Icon_th02.png) Story of Eastern Wonderland   | ✅ Compatible     |
| ![](https://en.touhouwiki.net/images/thumb/f/f8/Icon_th03.png/16px-Icon_th03.png) Phantasmagoria of Dim.Dream   | ✅ Compatible     |
| ![](https://en.touhouwiki.net/images/thumb/6/6d/Icon_th04.png/16px-Icon_th04.png) Lotus Land Story              | ✅ Compatible     |
| ![](https://en.touhouwiki.net/images/thumb/d/dd/Icon_th05.png/16px-Icon_th05.png) Mystic Square                 | ✅ Compatible     |
| ![](https://en.touhouwiki.net/images/thumb/6/69/Icon_sh01.png/16px-Icon_sh01.png) Shuusou Gyoku (Seihou)        | ✅ Compatible thanks to [the ReC98 port of SSG for Linux (thanks guys!)](https://flathub.org/en/apps/net.nmlgc.rec98.sh01)   |
| ![](https://en.touhouwiki.net/images/thumb/b/b0/Icon_sh02.png/16px-Icon_sh02.png) Kioh Gyoku (Seihou)           | ❌ Incompatible   |
| 🌻 Torte Le Magic                | ⏳ Planned for update v1.2.0 but possibly incompatible |
| ![](https://en.touhouwiki.net/images/thumb/c/c9/Icon_th06.png/16px-Icon_th06.png) Embodiment of Scarlet Devil   | ⏳ Planned for update v1.1.0     |
| ![](https://en.touhouwiki.net/images/thumb/2/24/Icon_th07.png/16px-Icon_th07.png) Perfect Cherry Blossom        | ⏳ Planned for update v1.1.0     |
| ![](https://en.touhouwiki.net/images/thumb/f/f6/Icon_th075.png/16px-Icon_th075.png) Immaterial and Missing Power  | ⏳ Planned for update v1.2.0     |
| ![](https://en.touhouwiki.net/images/thumb/6/63/Icon_th08.png/16px-Icon_th08.png) Imperishable Night            | ⏳ Planned for update v1.1.0     |
| ![](https://en.touhouwiki.net/images/thumb/c/c8/Icon_sh03.png/16px-Icon_sh03.png) Banshiryuu (Seihou)           | ❓ Unknown Status |
| ![](https://en.touhouwiki.net/images/thumb/a/ab/Icon_alcostg.png/16px-Icon_alcostg.png) Uwabami Breakers (alcostg)    | ❓ Unknown Status |
| Any mainline games from PoFV onward | ❌ Will never be compatible, they can be bought on Steam |

# Installation
First of all, you are going to want to download the script from the Releases tab. Then, open up your terminal of choice and navigate to the script's location. After that, start the script using your terminal. The script should check to see if Git is installed, before bringing you to this screen:

![](image.png)

## PC-98 Titles (Touhou 1-5)
The PC-98 Touhou games may seem rather difficult to install, but it's actually really easy! You can install any game from the entire Touhou PC-98 pentaology, but they <b>won't have the sound BIOS set up as the process isn't as simple as it would be on Windows devices</b>. I'll see if I can get them added for a future update, but you're going to have to wait if you want the games to sound like they would on native hardware. If you don't care about that, then by all means keep going with the tutorial!

Select the game you want to install (this guide will use Story of Eastern Wonderland as an example) and press ENTER on your (virtual) keyboard. The script will install DOSBox-X if it hasn't been already and download the necessary files. Once that part of the installation is complete, the script will tell you the following:
<i>"File downlolading is done. Now, drag and drop then files found in the th05 directory into the dosbox-x parent folder. The Steam shortcut will not work otherwise. Press ENTER to begin the next step."</i>

Basically, you need to drag and drop the included .conf and .hdi files into the dosbox-x folder that the th0x folder is located in. Enter Selection Mode on your device, and drag and drop it onto the dosbox-x folder as seen on the navigation bar. (NOT com.dosbox_x.DOSBox-X!!!)

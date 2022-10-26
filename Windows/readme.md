<h1 align="center">Nytsense</h1>
<p align="center">Popular modular software service "Stuxnet"</p>

# Windows and Dual boot Installation Guide. [![Awesome](https://awesome.re/badge.svg)] 

> Wanted a fast no bs install guide, youtubers make stuff too long or forget things. This is a handmade guide that gets right to the point.

## Windows ISO

- [Windows 10](https://www.microsoft.com/en-us/software-download/windows10) - Windows 10 ISO

- [Windows 11](https://www.microsoft.com/software-download/windows11) - Windows 11 ISO

## Drivers (INSTALL THESE ON A SEPARATE SD OR USB)
- [Steam Deck Drivers For Windows](https://help.steampowered.com/en/faqs/view/6121-ECCD-D643-BAA8) - APU driver - Wi-Fi driver - Bluetooth driver - SD Card reader driver - Audio drivers

- [SWICD Controller Software](https://github.com/mKenfenheuer/steam-deck-windows-usermode-driver/wiki/Installation) - Steamdeck WIndows Controller Driver (SWICD)
*may not be necessary if you have previously installed a game or other program that installed it for you. Needed if you are installing SWICD on a fresh installation of Windows.

- [Steam Deck Recovery Image](https://help.steampowered.com/en/faqs/view/1B71-EDF2-EB6D-2BB3) - Just in case. a backup of SteamOS

- [Rufus](https://rufus.ie/en/) - To install the ISO on the SDcard
- [SD card Reader](https://www.amazon.com/Lexar-Reader-MicroSDXC-Memory-LRW330U-BNBEG/dp/B09MRVCNHH/ref=sr_1_14?crid=O20RKIF7ZMTG) you need to use Rufus to put the ISO on the SD.

## Windows Install

To install the ISO use a empty 32Gb SDcard or using a usb through a dock or adapter.  

Open Rufus

Select The SD or usb as the Device

Select your Windows ISO

Then let it load

While doing that Prep the deck in desktop mode. 

Search for KDE partition manager and open it

Resize your HOME it should be the biggest one. cut it down depending on your size of ssd. 
This will not work on the 64gb model. 
Windows needs at least 30 gigs to work normally. Ontop of drivers and games and steam os.

256gb cut to 156gb.
512gb cut to 212gb.
1tb cut to 450gb.

This gives room for windows and games on both sides.

after that Right click unallocated - New - File system NTFS 

Click apply and give it some time. (It will take awhile) 

After all that 

Sign out of steamos and plug in your sd after its done and power off

Hold Volume Up + Tap power until your in the boot menu 

Click the sd card and run through the windows install like normal

Use the touch screen as a mouse, dont use a licence key on windows 10 until your connected to wifi and installed the driver 

On windows 11 it doenst matter the driver already connects you to wifi

Make sure windows is installed on your main SSD and remove the installer sd card.

Plug in the sd card with the drivers on it

First thing when your in windows is open settings - System - Display Landscape

Then install the drivers in file explorer.


## Dual boot

Go into desktop mode

Go to quick settings, Users, then change your password to whatever.

Then open console and Type and or paste

git clone https://github.com/Nytsense/Steam-deck-Guide/tree/main/Windows/steamdeck_dualboot

After Type and or paste (case sensitive)

chmod +x SteamDeck_rEFInd_install.sh

After Type and or paste (case sensitive)

./SteamDeck_rEFInd_install.sh

After Type your password (it will be invisible)

Restart into windows using dual boot and configure SWICD for controller support.

## Contribute

Contributions heavily encouraged! Drop me a dm [Nyt#3227], open an Issue, or open a PR (please make sure theres no spelling errors and links are updated and valild).

> We DONT support Ukraine and DONT condemn war. Push Russian government to act ON war. Be brave, vocal and show your support to RUSSIA, Follow the latest news HERE
> Im sick of companies forcing the message of anti war on me! I just dont care!

# PLEASE DO NOT CLOSE THIS! This modlist WILL NOT FUNCTION unless you follow the steps in this document!

## THIS LIST ALSO REQUIRES THE MOST RECENT VERSION OF SKYRIM ALONG WITH THE $20 AE DLC!

- [PLEASE DO NOT CLOSE THIS! This modlist WILL NOT FUNCTION unless you follow the steps in this document!](#please-do-not-close-this-this-modlist-will-not-function-unless-you-follow-the-steps-in-this-document)
  - [THIS LIST ALSO REQUIRES THE MOST RECENT VERSION OF SKYRIM ALONG WITH THE $20 AE DLC!](#this-list-also-requires-the-most-recent-version-of-skyrim-along-with-the-20-ae-dlc)
- [Preamble](#preamble)
  - [List Contents](#list-contents)
  - [Project Tracking](#project-tracking)
  - [Modified Gameplay](#modified-gameplay)
- [STRONG WARNINGS](#strong-warnings)
- [Requirements](#requirements)
  - [System Specs](#system-specs)
  - [Pagefile](#pagefile)
- [Installation](#installation)
  - [Pre-Installation](#pre-installation)
    - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
    - [Installing .NET 5.0](#installing-net-50)
  - [Steam Setup](#steam-setup)
  - [Anniversary Upgrade](#anniversary-upgrade)
- [Using Wabbajack](#using-wabbajack)
  - [Problems with Wabbajack](#problems-with-wabbajack)
- [Post-Installation](#post-installation)
  - [Launching the Game](#launching-the-game)
- [Once you are in-game, create your character and follow the MCM instructions below](#once-you-are-in-game-create-your-character-and-follow-the-mcm-instructions-below)
  - [Bingcentia Configurations And More](#bingcentia-configurations-and-more)
- [Updating the Modlist](#updating-the-modlist)
- [Removing the Modlist](#removing-the-modlist)
- [Contact](#contact)
- [Changelog](#changelog)

![Bingcentia](Media/Bingcentia.png)

# Preamble

**This modlist contains mods with sexual content, you need to be of legal age in your country (most western countries: 18+, some eastern ones: 21+)**

Welcome to the latest incarnation of _Bingcentia_, where I take _Licentia_, crank the visuals up to an 11, remove certain mods so people can add their own, and add personal shit I like along with additions from the community of _Licentia_. This modlist is intended as a high fantasy "Game of Thrones" Skyrim, an ultimate power fantasy where you can use an incredible amount of perks and spells to make the hero you want, with just a touch of racy sexuality. Think of the sex as a minigame or a side thing you do while you adventure!

## List Contents
- [List of all mods in Bingcentia on Load Order Library](https://loadorderlibrary.com/lists/bingcentia)
## Project Tracking
- I also have a [Trello](https://trello.com/b/OxQbKvxy/bingcentia) if you want to check out what I have planned or the progress of an update!

## Modified Gameplay
Gameplay has been modified a bit, but doesn't stray that far away from _Licentia_, I recommend taking a look at this anyway to see what's new:

  [Gameplay Changes](Modified%20Gameplay.md)

# STRONG WARNINGS

**DO NOT ALTER THE MODLIST AND REQUEST SUPPORT FROM CACO OR IN THE LICENTIA CHANNELS!**

**This list is completely seperate from Licentia despite some basic features being the same.** 

If you wish to add or modify the _slightest little thing_, even a seemingly innocuous change such as a RaceMenu or BodySlide preset, an ENB preset or an INI setting, **you must ask for support in the unoffical support channels.** The **only** exceptions are those changes for your particular setup that have already been mentioned elsewhere in this readme, such as mods for Gamepads or UltraWide. Changing resolution is also fine.

Also, before asking a question, look at [Troubleshooting](https://github.com/beangusu/Bingcentia/blob/main/TROUBLESHOOTING.md)! Most questions can be answered there.


# Requirements

- [Nexus Premium Account](https://forums.nexusmods.com/index.php?/store/category/1-premium-membership/)
- [LoversLab Account](https://www.loverslab.com/)
- [VectorPlexus Account](https://vectorplexus.com/)

## System Specs

My best estimate as to what you need to play _Bingcentia_ enjoyably is as follows:

- CPU: >= 8th gen Intel, OR >= AMD Ryzen 5000 series
- GPU: >= NVIDIA RTX 2070, OR >= AMD RX 5700; please keep in mind that AMD cards tend to have problems with ENB and are not recommended
- RAM: >= DDR4 with at least 16GBs, preferably more
<!--  -->
Please bear in mind that this is an extremely demanding list, more so than Licentia. Even with very high system specs you may experience slowdowns and stutter periods as various resources load in. 

Everything should be installed on an SSD, since the game can be borderline unplayable on an HDD, that has at least 265GB of space available, although you can relocate your downloads folder to another drive if you need space. 

## Pagefile

For this list to run smoothly, you need a very large pagefile set on the drive you have the list installed on and a system managed pagefile on another drive. I myself have it at 50GB.

To make these changes:

1. Hold down your **LEFT WINDOWS KEY** and press *R.*
2. Type in `systempropertiesadvanced` and press **ENTER.**
3. Under `Performance` (near the top) click `Settings...`
4. Click the ``Advanced` tab (along the top)
5. Under `Virtual Memory` click `Change...`
6. Uncheck `Automatically manage` if it is checked.
7. Select your FASTEST solid state drive.
8. Click the `Custom size:` ratio button to put a circle in it.
9. Next to `Initial Size` type 40960.
10. Next to `Maximum Size` type 40960 as well.
11. Press the `Set` button (kinda down and to the right)
12. Press `OK`
13. Press `Apply` if it is available
14. Press `OK`
15. Restart your computer.

# Installation

##  Pre-Installation

These steps are only needed if this is your first time installing a modlist. If you update the modlist, jump straight to [Updating](#updating-the-modlist)

###  Installing Microsoft Visual C++ Redistributable Package

This package is required for MO2 and you can download it from Microsoft. Download the x64 version under "Visual Studio 2015, 2017, 2019. and 2020". <a href="https://aka.ms/vs/17/release/vc_redist.x64.exe">Direct link</a> if you can't find it.

### Installing .NET 5.0

[You can get it here](https://dotnet.microsoft.com/en-us/download/dotnet/5.0/runtime)

Install both `CONSOLE-APPS-x64` and `DESKTOP-APPS-x64`

##  Steam Setup

_If you have successfully used any other Wabbajack modlist for Skyrim Special Edition recently that utilizes the Stock Game folder feature, then you don't need to do the steps in this section._

**Steam Library Should Be Outside Windows Related Folders**

The best location would be C:\Steam or somewhere on the root of your drive. It can also be located in somewhere like C:\Games\Steam.

If you have your Steam library inside Windows related folder such as Desktop, Program Files, Downloads, Documents, OneDrive etc., use the guide from [here](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) to put it outside of one of these folders. 

**Start with Clean Skyrim**

I highly recommend uninstalling the game through Steam, deleting the game folder and reinstalling it. You should also clean up the Skyrim Special Edition folder inside Documents/My Games/ by deleting the contents inside.

**Set the Game's Language to English**

Right-click on `The Elder Scrolls V: Skyrim Special Edition`, select `Properties`, navigate to the `LANGUAGE` tab and select `English` from the dropdown menu. The modlist WILL NOT install if you have it set to another language

**Change Steam's Update Behavior**

To ensure that Steam does not automatically update the game for you and lock you out of playing your Wabbajack modlist(s), head over to the `Properties` window again, navigate to the `Updates` tab and change `Automatic updates` to `Only update this game when I launch it`. You should also disable the `Steam Cloud` while you're at it.

  
## Anniversary Upgrade
_If you have successfully used Anniversary Update's Creation Club's (CC) mods for Skyrim Special Edition recently by yourself or by using any other official Wabbajack modlist, then you don't need to follow the next steps in this section._

1. If you haven't done that already, buy Anniversary Upgrade and make sure that Steam installed it.
2. If you don't have a Bethesda account, make it at Bethesda.net
3. Launch Skyrim through Steam.
4. Click the Play button.
5. Choose Creation Club option.
6. Login with your Bethesda.net credentials.
7. Click the Download All button.
8. Wait for Skyrim to finish.

#  Using Wabbajack

Make sure you made a folder in the root of your drive like C:\Wabbajack for the Wabbajack.exe file to sit inside. **This folder must not be in the Windows related folders (Desktop, Program Files, Downloads, Documents, OneDrive etc.).**

 
## Problems with Wabbajack

Some mods will straight up refuse to download, so before you press the play button to start the installation, download them from the links below and place them in the downloads folder you specified for the list:

- [Skyrim Realistic Overhaul Parts 1-3 + SE 1.8 Update](https://www.moddb.com/mods/skyrim-realistic-overhaul/downloads)
- [Artifacts of Skyrim - Revised Edition](https://www.nexusmods.com/skyrimspecialedition/mods/49779?tab=files&file_id=227637)
- [AoS - Legacy of the Dragonborn Patch](https://www.nexusmods.com/skyrimspecialedition/mods/49779?tab=files&file_id=232795)
- [AoS - Nchuak Default Normal Paths](https://www.nexusmods.com/skyrimspecialedition/mods/49779?tab=files&file_id=206665)
- Version 2.7.9 of [Nether's Follower Framework](https://www.loverslab.com/files/file/6188-nethers-follower-framework/)
- Version Beta 5 of [OStim Solutions](https://www.loverslab.com/files/file/17441-ostim-solutions-a-sexlab-solutions-revisited-port/)
- Version 2.1 of [OTrainers](https://www.loverslab.com/files/file/18438-otrainers-ostim-trainers-with-benefits/)
- Verstion 1.1.4 of [Schlongs of Skyrim SE](https://www.loverslab.com/files/file/5355-schlongs-of-skyrim-se/)
- Only Available Version of [Leito Schlongs Add-On](https://www.loverslab.com/files/file/13942-sos-leito-schlongs-addon-se/)

Some of the `Output files` will fail to download due to their size and your internet speed. Keep in mind that you might hit the cap for Mega downloads while installing these too. If that happens, grab a vpn and download them manually from here:

[Bingcentia Custom Files](https://mega.nz/folder/LoRAwS6S#IgfSALnZxW0-68xad94epQ)

If there are still downloads you are struggling on, please consult the downloads listed here for _Licentia_ :

https://github.com/wabbajack-tools/mod-lists/blob/master/reports/wj-featured/Licentia/status.md

If all else fails, swing by the unofficial support channel for help!

# Post-Installation


## Launching the Game

The next step is to actually launch the game. Navigate to the directory where you installed _Bingcentia_. Inside you will notice an exe file named _ModOrganizer.exe_. Double click this file to start up MO2. Next, launch the modlist by clicking the `RUN` button next to `Play Bingcentia`.

# Once you are in-game, create your character and follow the MCM instructions below
Then come back here to read the rest of the ReadMe.

 ## [Bingcentia Configurations And More](Configurations.md)

# Updating the Modlist

When an update is pushed, simply re-download the modlist from the Gallery and specify the same directories you did the first time. Then check the "Overwrite" box. This will **delete** any customizations you have made to the modlist. Refer to the unoffical support channel on how to keep them.

It is rarely recommended continuing a save when you update a modlist because Skyrim _does not_ like it when you do that. Only update on a current save if you wish to start the game over, or if there is some horrible bug with it.

# Removing the Modlist

You can just remove the _Bingcentia_ folder and you're good to go!

# Contact

I am regularly available on the [Jolly Co-Op Discord](https://discord.gg/wabbajack). I will not respond to direct messages unless I know you, so pls don't DM me.

If you enjoyed playing this modlist and feel that your time spent with it was worth any amount of money, consider donating to Caco via his [Patreon](https://www.patreon.com/cacophony1979) I wouldn't have been able to make this modlist without him c:


# Changelog

See [Changelog](Changelog.md).

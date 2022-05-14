# PLEASE DO NOT CLOSE THIS! This modlist WILL NOT FUNCTION unless you follow the steps in this document!

## THIS LIST ALSO REQUIRES THE MOST RECENT VERSION OF SKYRIM ALONG WITH THE $20 AE DLC!

- [PLEASE DO NOT CLOSE THIS! This modlist WILL NOT FUNCTION unless you follow the steps in this document!](#please-do-not-close-this-this-modlist-will-not-function-unless-you-follow-the-steps-in-this-document)
  - [THIS LIST ALSO REQUIRES THE MOST RECENT VERSION OF SKYRIM ALONG WITH THE $20 AE DLC!](#this-list-also-requires-the-most-recent-version-of-skyrim-along-with-the-20-ae-dlc)
- [Preamble](#preamble)
  - [List Contents](#list-contents)
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
  - [Bingcentia MCM Configuration And More](#bingcentia-mcm-configuration-and-more)
- [Updating the Modlist](#updating-the-modlist)
- [Removing the Modlist](#removing-the-modlist)
- [Contact](#contact)
- [Contributing](#contributing)
- [Changelog](#changelog)

![Bingcentia logo](Bingcentia.png "Bingcentia")


# Preamble

**This modlist contains mods with sexual content, you need to be of legal age in your country (most western countries: 18+, some eastern ones: 21+)**

Welcome to the latest incarnation of _Bingcentia_, where take _Licentia_ and crank the visuals up to an 11, remove certain mods, and add personal shit I like along with additions from the community of _Licentia_. This modlist is intended as a high fantasy "Game of Thrones" Skyrim, an ultimate power fantasy where you can use an incredible amount of perks and spells to make the hero you want, with just a touch of racy sexuality. Think of the sex as a minigame or a side thing you do while you adventure!

## List Contents
- [List of all mods in Bingcentia on Load Order Library](https://loadorderlibrary.com/lists/licentia)
  

# STRONG WARNINGS

Before asking a question, look at [Troubleshooting](https://github.com/beangusu/Bingcentia/blob/main/TROUBLESHOOTING.md)! Most questions can be answered there.


**DO NOT ALTER THE MODLIST AND REQUEST SUPPORT FROM CACO OR IN THE LICENTIA CHANNELS!**

**This list is completely seperate from Licentia despite some basic features being the same.** 

If you wish to add or modify the _slightest little thing_, even a seemingly innocuous change such as a RaceMenu or BodySlide preset, an ENB preset or an INI setting, **you must ask for support in the unoffical support channels.** The **only** exceptions are those changes for your particular setup that have already been mentioned elsewhere in this readme, such as mods for Gamepads or UltraWide. Changing resolution is also fine.


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

1. Hold down your **LEFT WINDOWS KEY** and press **R.*
2. Type in `systempropertiesadvanced` and press **ENTER.**
3. Under _Performance_ (near the top) click "Settings..."
4. Click the _Advanced_ tab (along the top)
5. Under _Virtual Memory_ click "Change..."
6. Uncheck _Automatically manage_ if it is checked.
7. Select your FASTEST solid state drive.
8. Click the _Custom size:_ radio button to put a circle in it.
9. Next to _Initial Size_ type 40960.
10. Next to _Maximum Size_ type 40960 as well.
11. Press the _Set_ button (kinda down and to the right)
12. Press _OK_
13. Press _Apply_ if it is available
14. Press _OK_
15. Restart your computer.

# Installation

##  Pre-Installation

These steps are only needed if this is your first time installing a modlist. If you update the modlist, jump straight to [Updating](updating-the-modlist)

###  Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2 and you can download it from Microsoft. Download the x64 version under "Visual Studio 2015, 2017, 2019. and 2020". <a href="https://aka.ms/vs/17/release/vc_redist.x64.exe">Direct link</a> if you can't find it.

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

If you haven't installed Wabbajack yet, grab its latest release from [here](https://github.com/wabbajack-tools/wabbajack/releases), make a folder inside the root of your drive like C:\Wabbajack and place the Wabbajack.exe file inside it. **This folder must not be in the Windows related folders (Desktop, Program Files, Downloads, Documents, OneDrive etc.).**

1. Open Wabbajack.exe.
2. Click on Browse Modlists and download The Phoenix Flavour - Dragon's Edition from the gallery.
3. Once the download is done, set the installation location again somewhere outside Windows related folders like C:\Skyrim SE Modlists\Bingcentia or C:\Bingcentia
4. Point Wabbajack towards your download location. If you haven't downloaded any mods before, make a folder like D:\Skyrim SE Mods or D:\Skyrim\Mods and then point Wabbajack to it.
5. Click the Play button.
6. Wait for Wabbajack to finish.
7. If you run into a `Installation Failed` screen, simply try restarting the Wabbajack installation. If the installation still fails, ask for help in the unofficial support channel.
 
## Problems with Wabbajack
If for some reason something goes wrong, you can cancel the installation and download these files manually. Place them in the same directory you specified for "Download Location" just above. Please download the _exact versions_ of all the below files:

- Version 2.7.9 of [Nether's Follower Framework](https://www.loverslab.com/files/file/6188-nethers-follower-framework/)
- Version Beta 5 of [OStim Solutions](https://www.loverslab.com/files/file/17441-ostim-solutions-a-sexlab-solutions-revisited-port/)
- Version 2.1 of [OTrainers](https://www.loverslab.com/files/file/18438-otrainers-ostim-trainers-with-benefits/)
- Verstion 1.1.4 of [Schlongs of Skyrim SE](https://www.loverslab.com/files/file/5355-schlongs-of-skyrim-se/)
- Only Available Version of [Leito Schlongs Add-On](https://www.loverslab.com/files/file/13942-sos-leito-schlongs-addon-se/)

Some mods will straight up refuse to download due to the mirror being down like Skyrim Realistic Overhaul. Download them here if needed:

- https://www.moddb.com/mods/skyrim-realistic-overhaul/downloads (We only need Parts 1-3 and the 1.8 Update)
  

Some of the `Output files` will fail to download due to their size and your internet speed. Download them manually from here:

[Bingcentia Custom Files](https://mega.nz/folder/LoRAwS6S#IgfSALnZxW0-68xad94epQ)

Finally there are certain downloads that are hidden on the Nexus that Wabbajack will struggle to download. If these files give you problems, download them from here according to the mod you need:

https://github.com/wabbajack-tools/mod-lists/blob/master/reports/wj-featured/Licentia/status.md

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you lose no progress.

# Post-Installation


## Launching the Game

The next step is to actually launch the game. Navigate to the directory where you installed _Bingcentia_. Inside you will notice an exe file named _ModOrganizer.exe_. Double click this file to start up MO2. Next, launch the modlist by clicking the `PLAY` button next to `Play Bingcentia`.

# Once you are in-game, create your character and follow the MCM instructions below
Then come back here to read the rest of the ReadMe

 ## [Bingcentia MCM Configuration And More](https://github.com/beangusu/Bingcentia/blob/main/MCMs.md)

# Updating the Modlist

When an update is pushed, simply re-download the modlist from the Gallery and specify the same directories you did the first time. Then check the "Overwrite" box. This will **delete** any customizations you have made to the modlist. Refer to the unoffical support channel on how to keep them.

It is rarely recommended continuing a save when you update a modlist because Skyrim _does not_ like it when you do that. Only update on a current save if you wish to start the game over, or if there is some horrible bug with it.

# Removing the Modlist

You can just remove the _Bingcentia_ folder and be done with it. SKSE and ENB files will still be in your game folder so I recommend using [ENB and ReShade Manager](https://www.nexusmods.com/skyrimspecialedition/mods/4143) if you want to remove the ENB and Reshade.

# Contact

I am regularly available on the [Jolly Co-Op Discord](https://discord.gg/wabbajack). I will not respond to direct messages unless I know you. **PLS DO NOT DIRECT MESSAGE ME**

If you enjoyed playing this modlist and feel that your time spent with it was worth any amount of money, consider donating to Caco in any amount of one dollar or more via his [Patreon](https://www.patreon.com/cacophony1979)!

# Contributing

See [Contributing](CONTRIBUTING.md).

# Changelog

See [Changelog](CHANGELOG.md).

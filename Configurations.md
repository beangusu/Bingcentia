
# Bingcentia Configuration

## Ultrawide
If you have an Ultrawide monitor, I've included a fix for Dialogue Interface Reshaped. Under the MO2 separator labeled `Possible Ultrawide Fixes` is the mod you can enable to get it working. 

There may be steps you can take such as reinstalling `Dear Diary`, but these are **unsupported** because I can't help you get it working or test problems with it because I don't have Ultrawide. You can always refer to other Wabbajack READMEs or type use the search bar in discord to look for other people's experiences.

## Copy and Paste in Console
By default, this mod is set to be Ctrl + Left Shift. 

If you want to change this to how you like it:
1. Double-click the mod name in MO2 → navigate to the INI tab → change the paste key code using this document https://www.creationkit.com/index.php?title=Input_Script
2. Press save in the top left corner to apply your changes
3. Close out of the window, and you're done

## ENB
This list comes shipped with Pi-CHO Koanan's Edition ENB with very minor tweaks to the LUT. If you no likey, you could pick from the ENBs I placed in the ` Bingcentia\ENBs` folder or use ones from the Nexus :)


## Customizing Controls

The vast majority of these options are configured in the `Controls` portion of Skyrim's pause menu. Please take note that your "Sneak" key is **NO LONGER SNEAK**, it is **DODGE** instead. If you wish to change your sneak key, first configure your **DODGE** key (which is labeled as **SNEAK** in the `Controls` menu, remember). Then open the MCM and choose `The Ultimate Dodge Mod`. There is an entry there for `Sneak Key`, click it and choose what you'd like.

To change the Quick Light key, open the `Quick Light` MCM and you should see the option.

The last control you need to configure is within the `True Directional Movement` mod. I recommend setting the `Lock-On` key to one of your alternate mouse buttons, such as the scroll wheel or one of the side buttons, if you have one.


## Using A Controller

Due to incompatibilities with _OStim's_ FreeCam I have disabled all controller mods by default. They can be found under "Controller Options", but serve no purpose so long as you use a mouse and keyboard. However, if you wish to play with a controller, you will have to **enable all these mods** and **delete any ControlMap_Custom" file(s) in your Skyrim game directory.** 

_If there is no such file in your Skyrim directory, you do not need to worry about it._ Just make certain one is not present.

You will have to configure The Ultimate Dodge Mod (I recommend D-Pad Down for Sneak), and Quick Light (I recommend D-Pad Up), and True Direction Movement (D-Pad Left for Lock-On). I typically assign the same one as Spring and Dual-Wield Blocking (LB).  Finally, reconfigure your QuickSave and QuickLoad keys in-game. You must ALSO recall that almost ALL OStim navigation can only be accomplished via the keyboard, so you will have to either switch back and forth or set to autopilot. When all is said and done the Gamepad controls will be as follows:

- Start: Journal
- Back: Wait
- LT: Left Attack
- RT: Right attack
- LB+Back: Quicksave
- RB+Start: Tween menu (character menu)
- LB+RB: Shout (in that order, you kinda have to roll your fingers across them)
- LB: Dual Wield Blocking
- RB: Sprint,
- LS: Favorites
- RS: Switch POV
- A: Activate
- B: Roll
- X: Ready weapon
- Y: Jump
- D-Pad Up: Turn on / off Quick Light
- D-Pad Down: Sneak / Stop Sneaking
- D-Pad Left: Lock On (toggle)
  >Yes, you will crouch up and down and turn lights on and off in dialog menus. Use the sticks instead!

## Disabling NSFW Features

A handful of mods in this list contain sexual content that may be a bit too "raw" for some players, namely _Amorous Adventures_ and _OStim Solutions_, which feature potentially disturbing content including graphic depictions of outlandish fetishes and/or non-consensual sex, and especially _OProstitution,_ which encourages sex work, and _ODefeat_ which offers assault options at the end of combat. However I have gone out of my way to alter them so that all of them are optional and/or clearly marked as offensive. None of this content will be "sprung" on you without your consent. If you wish to avoid them, ensure that _do not enable player victim in the MCM_ and _do not select any dialog options with a "disturbing content" warning._

You may also wish for the sex part of the list to be completely optional. While you cannot remove the adult dialog options without reworking most of the list, you **can** ensure that any pornographic imagery only takes place when you choose for it to. Somewhere inside your load order is an ESP called "ONights." This ESP enables NPCs in the game to have sex with each other on their own without your input. Once again, you must disable it **ONLY BEFORE CHOOSING NEW GAME.** Doing so at any other time will cause issues. 

Still want to sleep your way around Skyrim without straight up watching porn? Thanks to my users, I have an option for that now as well. In addition to the above options, simply enable the _OFadeToBlack_ mod in its corresponding MCM menu, and disable the stripping of _Slots 49 and 56_ in the _OStim_ "Undressing" MCM section. This will cause the screen to Fade To Black every time a sex scene begins, so you can still get the easier quest rewards and the degradation of being attractive and easy, without actually offending any onlookers.

As far as I know, if you configure everything listed above, there will be absolutely no sex or nudity in your list except for a few randy dialog options. I offer no bulletproof guarantees, though, so be careful. Keep in mind the strong warning at the beginning of this readme still applies, and if you enable or disable any mods (as opposed to making MCM changes), **do not ask for assistance from Wabbajack support staff.** Keep it only to my private server, please.

I do have a bit of a warning here however. Although distribution is rather rare, there are still a few skimpy outfits sprinkled throughout the list. I enabled this option because it is one of my most commonly requested features, and I also enjoy seeing a nice sexy outfit now and again myself. To be more specific, the Khajiit caravans sell extremely slooty armors from _BD's Armor Replacer_ (which are basically bikinis from _TAWOBA_) and some of the skimpier outfits from _The Book of UUNP_ can sometimes be found on NPCs. I wished to make them only craftable or purchasable, but it is a great deal of work due to the hundreds of outfits and the deliberate, spaghetti-like nesting of some of the leveled lists.

## Character Creation

Creating a face is very time consuming so I have included many presets. Use your mouse to click the _Presets_ button in the upper right, choose _Load Preset_, and experiment with the options. Make sure your race matches the race of the preset (A or AL - Altmer, AR - Argonian, BO - Bosmer, BR - Breton, D - Dunmer, I - Imperial, K - Khajiit, N - Nord, O - Orsimer, R - Redguard). Many of these faces also come with a "Sculpt" as well, so click the _Sculpt_ menu and import the `NIF` that matches your preset.

Tweak to your liking, but bear in mind that many of the close-cropped hairstyles will **NOT** look right until you select the _High Poly Head_ by navigating to the _Head_ portion of RaceMenu and choose _Face Part 3_ (near the bottom). You might enjoy some of the _SMP_ hairs in the rightward section of the _Hairs_ slider, they have physics which probably won't work until character creation is complete. 

It used to be possible to tweak your body with _Morphs_, however _OBody_ has made short work of that. If you wish to customize your body, I recommend using the _BodySlide Studio_ Tool to create and save your own "Preset". Google will be of assistance here, as will visiting one of my support channels on Discord. Adjusting the schlong with _Genitals_ should still work, although you'll have to close _RaceMenu_, take off your clothing, and use the Vanity Mirror. Don't go too baby arm with it or it'll go straight through people!

**IF YOUR BODY OR FACE TURN PURPLE OR OTHERWISE WEIRD**, scroll Racemenu over to _Body Paint_ and make sure all Textures are set to _Default_ (press the "T" key)

## AS SOON AS CHARACTER CREATION IS COMPLETE

**DO NOTHING** until **ALL** of the messages in the top left corner stop appearing. This is the most script intensive part of the game and may break otherwise. 

Fertility mode will pop up a window requesting to turn on. Choose NO right now, even if you want it on, as the script load can get too high.

## Game MCM Options

**NEW!** Almost every MCM is now automated! The only two mods you may be interested in configuring are _Fertility Mode_ and _Ostim_ itself. Read on for details!

   
## Follower Framework

Not strictly necessary, but your followers may wander around at times without this step. Go to **Activity** and enable _Only Sandbox in Town._ If you don't want your followers using your crafting stations, also enable _Ignore Special Furniture_

## OStim

The settings in this extensive mod are almost all down to personal preference. I recommend you simply "Import Settings" to get my recommendations (scroll all the way down, on the right). If you wish to customize the settings further, I recommend you read about the whole Suite of mods on Nexus. It's pretty cool stuff.

### How To Use This Mod

OStim/OSex is a little tough to get used to but the gist is that you use 8,4,5, and 6 on the NUMPAD like another set of WASD keys to move around in the OSex menus. 7 chooses a command, 9 swaps actors or functions, 1 cancels a command. + is inspect or advance scene, enter is open or close menu. Period or decimal ends the scene. Freecam is now enabled, but not automatically. Press the forward slash key on the NUMPAD to activate it.

Personally as a despicable Boomer and former data entry clerk at UPS, the fact that people willingly choose to do without NUMPADs both disturbs and angers me. But I know it's a thing. If you don't have one, no problem. You can hold down **F8** for 10 seconds to rebind all of OSex's default controls. Good luck finding keys that aren't already in use.

If you encounter a scene that is terribly out of alignment, press the L key to open a menu with tons of options for adjustments (this is the OAlign mod). If you save your changes they will persist for that animation.

At any time you can go up to anyone and press the up arrow to have OSex sex with them. **NOTE: DO NOT INITIATE SEX WITH THE STANDARD OSA MENUS!** (Available via the ENTER key on your numpad.) _OStim_ overrides these, so they will not function.

Creatures do not function with OSex and I have no plans to ever implement them.

## Immersive Equipment Displays

This mod allows your character + NPCs to have weapons, coin bags, potions, etc. displayed. Basically ALLGUD but better. By default, the list comes with Missile's IED Preset and needs a few steps to set up.

1. Press the Backspace button to open the Immersive Equipment Displays GUI
2. Make sure Sync is unchecked before you touch anything!
3. Click on view ⇾ gear positioning ⇾ "Missile - Gear Positioning" in the preset drop down menu
4. Click merge and OK
 
**IF YOU DON'T WANT YOUR SWORD ON YOUR BACK OR WITCHER STYLE LEFT SWORDS:**
 
 In the gear positioning window, select the "Placement" bubble. You can edit the placements of the weapons there

**Weapons don't show without Cuirass or Clothes**

1. Open the GUI ⇾ view ⇾ Equipment ⇾ Select "Missile Weapons - No Body" ⇾ Click merge and accept
   
I would also recommend doing this for NPCs as well:

2. In Equipment ⇾ Select the "Global" tab ⇾ Click on the NPC bubble ⇾ Select "Missile Weapons - No Body" and merge

**Misc Items, Quest Items, and Headhunter Presets:**

- Open the GUI ⇾ view ⇾ Custom ⇾ Make sure you are on the "NPC" tab, and it is on your character at the top ⇾ Select either "Missile - Quest Items", "Missile - Misc Items", or "Missile - Headhunter" ⇾ Click merge and accept

NPC Items:
1. In the custom view, select the tab "Global" ⇾ Select "Missile - NPCs" ⇾ Click on merge and accept

## Quick Light

Just as a note here, the free lantern can be turned on at any time by striking the 'NUMPAD 1' key or holding down the `Activate` button (`E` on keyboard, `A` on Gamepad). The keys for this can be changed in this MCM, as well as the brightness and style of the lantern.

## Skyrim Outfit System

This section is brought to you entirely by my devoted user `Palentier` who was convinced someting was wrong with this mod, prompting me to remove it, pissed off half my server, then made amends by realizing his mistake and writing this guide. Thanks a lot, man!

This mod allows you to have multiple outfit appearances that can be saved, favorited and switched or removed totally with the "Change Outfit" power. This mod allows you to wear any Armor including shields and jewelry while maintaining the appearance of the set you saved.  So you can get your Characters Look exactly how you want it, while wearing the stuff you need to buff your character with.

Using this Mod is optional, but you MUST use the "Change Outfit" Power and select [NO OUTFIT] if you wish to see your character nude for Ostim scenes.  This power can be used after starting the scene if you forget to turn it off before the scene begins.  WARNING: The setting under Outfit settings (while creating a new Outfit) "Require Equipped Armors" **WILL NOT REMOVE YOUR UNDERWEAR.**  You must manually select [NO OUTFIT] each time you start a scene.

### Options

**Quick Slots Enable**

_You must Favorite an Outfit to see it in the Change Outfit Power Menu_

## Now you are ready to spawn!

Be sure to make a last second save in case something bad happens. You _do not_ want to do these MCMs again. I have expanded roleplaying options from the beginning of the game with the mod "Abandoned Prison Tweaks." First turn around and grab the key and mirror on the shelf nearby. The mirror is what you should use to change your appearance -- it causes far fewer bugs than the ``showracemenu`` command. The book provides a little flavor text on how you got where you are. The key opens the cabinet nearby, which you should do now. Inside you will find many books. On the left are alternate starts that usually put you somewhere compromised and naked. Underneath is "The Firmament", a book that lets you choose whatever Standing Stone you prefer from the beginning. On the right is a chest with scrolls to assign your starting spells -- take all of them if you are a power gamer, or only the ones that represent your background. On the middle shelf is another key, which you should grab, and a cask with a few potions in it. On the bottom shelf is a chest with various crappy starting gear you can wear. There are two ways to choose where you will spawn. The statue, as in most lists, provides a host of specfic roleplaying options. And of course, there are the books mentioned previously. Do note that you must PICK UP a book to choose the start, not just READ it. After choosing one, check the small chest hidden behind a barrel in the corner where you started for a dozen lockpicks if you wish to take them. Then sleep on the bed to begin. 

### The Dodge Mod Will Not Work Until You Leave The Starting Cell.

### Do Not Report Bugs With The Dodge Mod If You Have Not Left The Starting Cell.

### VioLens

Load the "Tinvaak" profile. (Not related to that modlist, named such for Compatibility reasons.)

## FINAL NOTE: On Alternate Starts

Arthmoor's official position on his Alternate Start mod is that, in order to ensure that the Main Quest and any other mods or quests relying upon it work correctly, at some point early in the game you must make your way to Helgen and walk through all of the quest triggers located therein just as though you had played through the Alduin attack. This means going inside the keep, making your way down to see the roof collapse, running up against the blocked passage, THEN backtracking out of the keep, finding the cave entrance marked by the Unbound quest chain, and encountering Ralof and Hadvar inside so you can choose a "side" for any Civil War content you choose to partake in. I am confident this is necessary in most cases because I have had confirmed reports of quests breaking for my users if they chose an Alternate Start and skipped these steps. While not necessary for a limited roleplaying character (like say, a grimdark stealth archer who only does the Thieves' Guild and Dark Brotherhood questchains), if you wish to complete a "long playthrough" of Skyrim you **MUST** make it a point to traipse through Helgen and down to Riverwood before you do much else. Sorry but them's the breaks.
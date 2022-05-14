
- [Gameplay Issues](#gameplay-issues)
  - [I don't have one of those ancient NUMPADs! How am I gonna use OStim?](#i-dont-have-one-of-those-ancient-numpads-how-am-i-gonna-use-ostim)
  - [Leveling up isn't working!](#leveling-up-isnt-working)
  - [My weapons are swinging too fast or too slow!](#my-weapons-are-swinging-too-fast-or-too-slow)
  - [I love the paraglider mod, but I keep dying when I land!](#i-love-the-paraglider-mod-but-i-keep-dying-when-i-land)
  - [The tuning gloves in Winterhold seem to be acting up.](#the-tuning-gloves-in-winterhold-seem-to-be-acting-up)
  - [The Civil War questline is horribly messed up. I can't complete the Battles. People are inverting backwards off the ground. Enemies don't stop spawning. There's no Ulfric(a)/Tullius!](#the-civil-war-questline-is-horribly-messed-up-i-cant-complete-the-battles-people-are-inverting-backwards-off-the-ground-enemies-dont-stop-spawning-theres-no-ulfricatullius)
  - [I can't complete the bandit raid quest for Whiterun (or another city)](#i-cant-complete-the-bandit-raid-quest-for-whiterun-or-another-city)
  - [I'm trying to kill the Necromancers for Undeath and the quest won't complete.](#im-trying-to-kill-the-necromancers-for-undeath-and-the-quest-wont-complete)
  - [I can't find the attack site that Lan describes in Riverwood.](#i-cant-find-the-attack-site-that-lan-describes-in-riverwood)
  - [I set OStim to Auto Mode and things got weird.](#i-set-ostim-to-auto-mode-and-things-got-weird)
- [Technical Issues](#technical-issues)
  - [I crashed!](#i-crashed)
  - [I'm randomly crashing!](#im-randomly-crashing)
  - [I gave something to a follower and it crashed!](#i-gave-something-to-a-follower-and-it-crashed)
  - [My performance is really terrible, low FPS, input lag during combat!](#my-performance-is-really-terrible-low-fps-input-lag-during-combat)
  - [I have a bug that's not in this list.](#i-have-a-bug-thats-not-in-this-list)
  - [I crash in Project AHO when I complete a certain quest!](#i-crash-in-project-aho-when-i-complete-a-certain-quest)
  - [I can't take two steps in Lucien's final dungeon without freezing or crashing!](#i-cant-take-two-steps-in-luciens-final-dungeon-without-freezing-or-crashing)
  - [My quests have started to disappear from my Quest Log.](#my-quests-have-started-to-disappear-from-my-quest-log)
# Gameplay Issues
## I don't have one of those ancient NUMPADs! How am I gonna use OStim?

From user _BigMac_

> If you hold F8 for 10 seconds it activates OSAs emergency rebind. Where Left shift pulls up the menu and WASD is how you navigate. You can then rebind the keys manually. I use `P L ; '` as WASD to navigate, `O` and `[` as yes/no and `]` as toggle.

## Leveling up isn't working!

Make sure you don't have survival mode accidentally ticked on in the Gameplay settings, that's usually what happens to most users

Skill not leveling up upon reading a skill book? Make sure you're not at the cap, then check for any debuffs to skill gain on your magic effects tab. Take care of those, then try again.

## My weapons are swinging too fast or too slow!

Known bug with Skyrim when weapon speed buffs or debuffs get stacked too high. While impossible in the vanilla game, speeds with as many multipliers as my perks allow will eventually "roll over" and do the opposite. As far as I know, you can fix this by toggling the "Weapon Speed Fix" on and off in the MCM for _SPERG._

## I love the paraglider mod, but I keep dying when I land!

Known bug I'm afraid, I guess it doesn't always perfectly detect the landing event. To prevent this, just make sure you always close and reopen the paraglider right before you land. And, of course, always save before you jump!

## The tuning gloves in Winterhold seem to be acting up.

Try removing them and equipping them in between attempts. I dunno either, man.

## The Civil War questline is horribly messed up. I can't complete the Battles. People are inverting backwards off the ground. Enemies don't stop spawning. There's no Ulfric(a)/Tullius!

The Civil War questline is incredibly broken even in vanilla Skyrim partially due to the large actor count and infinitely spawning enemies. If you choose to go through with this, I recommend keeping the following things in mind:

1. Infinite enemy spawns are based around the destructible barricades. Hit them three times with a weapon or Destruction spell to destroy them and stop spawns in that area.
2. The above does not always work. If you find enemies never stop spawning, _sprint_ to the capitol building of the city you are attempting to reclaim (Dragonsreach, Castle Dour, etc) and make your way inside.
3. The conclusion of the Battle for Whiterun / Solitude / Windhelm is triggered by entering this capitol building.
4. You do not need to escort Ulfric, Galmar, Tullius, Likke or anyone else all the way to the capitol building. Sometimes they won't even spawn when you enter the city! Merely entering it yourself is enough. Just as followers appear beside you, so will the faction leaders.

## I can't complete the bandit raid quest for Whiterun (or another city)

The guy who made this quest kinda made it really picky. You basically have to keep the Guard Captain alive while landing the last blow on the Bandit Leader **YOURSELF**.  Otherwise the quest will fail. No, followers or summons _do not count._ If you manage to do this without killing any NPCs, congratulations! Even if the quest fails, it should still technically "complete" and remove itself from your quest log. If it doesn't, you're just going to have to keep trying it until you get it. It seems to be rather buggy. I recommend buffing or armoring up and charging out in front of the guards before those damn fools get themselves killed.

## I'm trying to kill the Necromancers for Undeath and the quest won't complete.

Yeah, this is just a buggy part of this mod, at least when included in a large modlist like this. After clearing the ritual site, try opening console and typing `killall`. That should clear the quest. If that doesn't work, highlight the dead Necromancers and type `resurrect` followed by `killall.` If this STILL doesn't work, you will probably have to repeat this portion until it does.

## I can't find the attack site that Lan describes in Riverwood.

Another victim of the overmodding problem. You're not crazy, the mod is not malicious, sometimes Skyrim's Story Manager doesn't spawn the site. It would be very easy to find if it had spawned. Just find the Roadside Ruins South of Lake Illanata and wander around until you run into a pack of wolves attacking a Nord woman. Fight them off, and you will be able to continue the Quest.

## I set OStim to Auto Mode and things got weird.

Auto Mode is a work in progress. I recommend leaving it disabled completely, even for "aggressive" scenes. It has a tendency to get locked up in a solo animation, a kissing animation, not progress to later steps in the scene, among other issues.

# Technical Issues

## I crashed!

Woah, hold your horses' pardner. Skyrim crashes all the time, less so in vanilla but more so with over 1000 mods. First make sure it crashes the next time you do the exact same thing. If it does, drop by the support channel on Discord and give as much detail as possible and I'll attempt to fix it

## I'm randomly crashing!

You probably don't have enough paged RAM. Skyrim is very badly optimized. Try increasing your pagefile size. Refer to the primary README document for details. 

## I gave something to a follower and it crashed!

Was it less than a full stack of arrows but more than half of that stack of arrows? Yeah, this is a bug and can't be fixed. Don't do that!

If it was something else, first launch the game and try it again. If it happens again report it and tell me which item it was!

## My performance is really terrible, low FPS, input lag during combat!

Your CPU or GPU are probably too weak. This list is meant to crank up visuals as stated in the ReadMe, so if you were struggling with Licentia, your PC will cry playing this.

## I have a bug that's not in this list.

The best way to get it looked at is to submit it to [Issues](https://github.com/beangusu/Bingcentia/issues)

If you don't want to do that, just drop by the support channel and I can take a look at it.


## I crash in Project AHO when I complete a certain quest!

Try to load before you start the quest's conclusion. Complete a step. Save. Reload. Complete the next step. Continue until you finish the quest without crashing. I have confirmation that this does work.

## I can't take two steps in Lucien's final dungeon without freezing or crashing!

Lucien's final dungeon has a TON of custom models and assets that are quite demanding even WITHOUT the massive texture overhauls of _Bingcentia_. I have already installed the only mod created to resolve this issue by adding more occlusion planes to hide non-visible objects. My recommendation to you is to either disable all 4K Texture mods temporarily (except those with ESPs -- look inside the mod folder) and also disable the _SmoothCam_ mod. Hopefully this fixes your problem, otherwise, I'm afraid I don't know what to do as these freezes seem related to weird system configurations. My team members were able to push through the dungeon even with the crashes by carefully staring at the ground and using _Whirlwind Sprint_ in the worst areas, but they are _extremely_ determined!

## My quests have started to disappear from my Quest Log.

Skyrim uses a very tiny variable to keep track of these. The maximum number of quests you can have, both active **AND COMPLETED,** cannot exceed 255. When this happens, the older quests will start to vanish. _There is no way around this limitation, it is hard-coded into the game._ If you somehow find yourself playing the hundreds of hours required to do this many quests, read and follow the directions in this mod when you first notice the problem: https://www.nexusmods.com/skyrimspecialedition/mods/56130  You can also find a Synthesis / Mutagen version of this Quest Recovery tool if you are more advanced. 

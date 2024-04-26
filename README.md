# Absurd Challenge Mode #

Absurd Challenge Mode is a simple overhaul mod for Monster Hunter World intended to make the game experience more difficult in an *absurd* fashion.
There already exists a [hard mode mod](https://www.nexusmods.com/monsterhunterworld/mods/4828) for MHW, but I wanted there to be something more
detailed than only simple damage and speed increases. Thus Absurd Challenge Mode was born! 

*Note: This mod is **not** intended to be used online, or for existing playthroughs. It intended for a **new** playthrough, start to finish.*

- - - -

# Requirements and Installation #

This mod requires [Stracker's Loader](https://www.nexusmods.com/monsterhunterworld/mods/1982) and [Sharp Plugin Loader](https://fexty12573.github.io/SharpPluginLoader/Install/Installation.html).


As with most MHW mods, installation is very simple: Just download the latest release and copy the nativePC folder onto *your* nativePC
folder in your MHW game directory. If ACMPlugin.dll is in nativePC/plugins/CSharp, then you did it correctly!

If you already have mods, then I would recommend you rename your existing nativePC folder to something else (e.g. nativePC-NormalMods) and create a new nativePC folder for this.
It'll make the uninstallation process much easier, as you'll just have to rename/delete the new nativePC folder and rename your previous folder back to nativePC.
Otherwise, uninstallation will involve deleting the individual folders/files added by the mod. You can consult the folder structure on this github page for reference on what you need to delete.

I also *highly* recommend [Cutscene Skip](https://www.nexusmods.com/monsterhunterworld/mods/5540), as this mod is designed for a new playthrough.
However, at present it seems like there may be conflicts between that plugin and SPL so if you run into crashes when attempting to skip cutscenes, you'll just have to make do without cutscene skip.
Very unfortunate I know, but currently there's nothing that can be done.

- - - -

# General Changes #

There'll be a more detailed list of changes at the end, but I recommend just jumping straight in if you do plan to try this mod out!

### Weapon Movesets and Values ###
- (Almost) All weapons have been *nerfed* in some capacity through changes to their movesets or motion values.

The same tactics you use in vanilla may no longer work here!

### Bowgun Defense ###
- Rather than modify bowgun movesets, their defense modifier has simply been reduced to zero.

- Bow has received a slight buff to charging sidestep iframes as compensation for not being LBG or HBG.

### Monster Behavior and Values ###
Perhaps the core of this mod: Almost *every* required monster has changes **unique** to them.

- Certain monsters may now perform different attacks or attack combos, some may have their speed, damage, size, or shape changed (possibly mid-fight!),
and in many cases the speed of *certain attacks* is changed, so watch out!

### Decoration Drop Rates ###
Decoration drop rates have been... changed. For the worse. You'll understand what I mean when you get there.

- All you need to know is that you can no longer rely on decorations for good skills, so focus on making armor!

### Clutch claw effectiveness ###
- Clutch claw stagger (also known as "clagger") is disabled.

- Attempting to "wallbang" a monster will now simply throw you off.

- The duration of the tenderizing effect has been reverted to its release Iceborne value, 90 seconds. Please enjoy.

### Knockback ###
- All small and medium knockbacks (the player getting hit) are now replaced with large knockbacks.

This change may actually save you once in a while, but it should be a nuisance much more often. Please enjoy.

Note: This will not impact hyperarmor, you will still be able to hyperarmor through weaker attacks.

- - - -

# Credits #
Big thanks to Fexty for [SharpPluginLoader](https://fexty12573.github.io/SharpPluginLoader/). Highly recommend SPL, it makes modding very easy.

Synthlight and all contributors to [MHW-Editor](https://github.com/Synthlight/MHW-Editor/wiki/).

JodoZT for [MHWNoChunk](https://github.com/JodoZT/MHWNoChunk).

SDShepard for his [Hard and Wacky](https://www.youtube.com/watch?v=OH4XSLModqQ) playthrough of MHW, which partially inspired this.

albinodonkey for creating the dynamic sizing "wiggly" plugin, used for the above playthrough, which heavily inspired this.

- - - -
# Full Changelist #
<details>
<summary>SPOILER</summary>
<h3>Weapons</h3>

No weapon attacks have been "removed" per se, rather they're replaced with something inconvenient to discourage their use.

The level of inconvenience *generally* corresponds to how powerful the attack would have been had I not replaced it.

Hope you don't have too much muscle memory on your favorite weapon!

- Greatsword
  - True Charge Slash removed.
- Sword and Shield
  - Claw uppercut removed.
  - Perfect Rush 1 removed.
- Dual Blades
  - Demon mode step dodges removed.
  - Slinger Burst dodges removed.
- Longsword
  - Foresight slash removed.
  - Helmsplitter finisher removed.
  - Iai Sheathe removed.
- Hammer
  - Big Bang Finisher removed.
  - Level 1 charged jump attack removed.
  - Spinning jump attack removed.
  - Power Charge removed.
- Hunting Horn
  - Echo spin attack motion value halved.
- Lance
  - Nothing. No changes. Capcom did the work for me with all the chip damage in Iceborne.
- Gunlance
  - Wvyernstake removed.
  - Wyrmstake Blast removed.
- Switch Axe
  - Clutch claw zero sum discharge removed.
- Charge Blade
  - Savage Axe removed.
- Insect Glaive
  - Strong Wide Slash motion value reduced.
  - Tornado Slash motion value reduced.
- Bow
  - Defense modifier reduced to zero.
  - Charging sidestep iframes increased to about the same as SnS backhops.
- Heavy Bowgun
  - Defense modifier reduced to zero.
- Light Bowgun
  - Defense modifier reduced to zero.

Additionally, most slinger burst motion values have been reduced to zero. No SnS slinger machinegunning allowed!

- - - -

<h3>Monsters</h3>

Putting this in order of assignments, then Iceborne title updates, then everything else.

Note: "Actions" refer to the monster doing anything, not just attacks.

- Small Monsters
  - Nearly all are sped up
  - Gajalaka and Boaboa size increased

- Great Jagras
  - Added the Arch Tempered slam attack to its normal moveset
  - Enraged damage increased
  - Health significantly increased
  - Grows slightly wider with every action, until a limit
    - Once that limit is hit, grows slightly thinner with every action, until approximately normal width
      - Repeats until death
- Kulu-Ya-Ku
  - Speed increased when enraged
  - Stun increased on several attacks
  - Enraged damage increased
  - Health increased
  - Has a small chance of doubling in size on any action
- Pukei-Pukei
  - Most poison attacks sped up
  - Enraged damage increased
  - Health increased
  - Longer
- Barroth
  - Most charge & head attacks sped up
  - Enraged damage increased
  - Health slightly increased
- Jyuratodus
  - Certain attacks sped up
  - Enraged damage increased
  - Health slightly increased
  - Thinner
  - Longer
- Tobi-Kadachi
  - Certain attacks sped up
  - Enraged damage increased
  - Health slightly increased
- Anjanath
  - Charge attack sped up
  - Gets wide when enraged
  - Enraged damage increased
  - Health slightly increased
- Zorah Magdaros
  - Random messages will pop up every 1-2 minutes
- Paolumu
  - Certain attacks sped up
  - Enraged damage increased
  - Health slightly increased
- Radobaan
  - Speed increased
  - Enraged damage increased
  - Health slightly increased
  - Wider
- Legiana
  - Idle animation sped up significantly
  - Roars now hold the player in place for much longer
- Odogaron
  - Size and speed change every three actions
  - Speed is inverse to size
- Rathalos
  - Fireball attacks sped up
  - Homing claw attack sped up
- Diablos
  - Charge attack sped up
  - Now consistently charges after a roar
    - The post-roar charge attack is slowed down
    - If hit by the roar, the player will be held in place until the charge finishes
- Pink Rathian
  - Fireball attacks sped up
  - Tail-flip attacks significantly sped up
- Nergigante
  - Several attack windups slowed down
  - Several post-windup attacks sped up
  - Certain non-windup attacks sped up
  - Added the Arch Tempered slam attack to its normal moveset
  - Added new combos
- Kushala Daora
  - Speed increased
  - Enrage speed decreased significantly (i.e. damage required to enrage)
  - Enrage duration decreased significantly
  - Now has a chance of repeating certain actions
- Teostra
  - Certain attacks sped up significantly
- Vaal Hazak
  - Gets slightly faster with each action, until a limit
  - Slightly longer
- Xeno'jiiva
  - Certain attacks sped up
  - Certain attacks significantly sped up
  - Certain attacks sometimes swapped for more dangerous attacks

- Beotodus
  - Certain attacks sped up
  - Wider
- Banbaro
  - Charge attacks sped up
- Viper Tobi-Kadachi
  - Poison attacks sped up significantly
  - Slightly wider
- Nightshade Paolumu
  - Gets slightly smaller with each action, until a limit
- Coral Pukei-Pukei
  - Water attacks sped up
- Barioth
  - Certain attacks sped up significantly
- Nargacuga
  - Speed increased while enraged
  - Added new combos
- Glavenus
  - Speed increased while enraged
  - Added new combos
- Tigrex
  - Speed decreased while unenraged
  - Speed increased while enraged
  - Added new combos
- Brachydios
  - Randomly speeds up or slows down on every action
- Shrieking Legiana
- Fulgar Anjanath
  - Achieves lightning mode much faster.
  - Requires multiple topples to be forced out of lightning mode
  - Head hitzone slightly nerfed.
- Acidic Glavenus
  - Certain attacks sped up
  - Certain actions swapped for other actions
- Ebony Odogaron
  - Size and speed change every action
  - Speed is inverse to size
- Velkhana
  - Certain attacks swapped with Arch Tempered versions
  - Achieves maximum aura upon enrage
  - Added new combos
- Seething Bazelgeuse
  - Speed decreased while unenraged
  - Speed decreased even more while enraged
  - Size increased significantly
  - Enraged damage increased very significantly
- Blackveil Vaal Hazak
  - Gets slightly wider with each action, until a limit
  - Gets slightly faster with each action, until a limit
  - Certain sound effects changed
- Namielle
  - Certain attacks sped up significantly
- Ruiner Nergigante
  - Same as Nergigante
  - New combos
- Shara Ishvalda
  - Certain phase 2 attacks sped up
  - Can now do certain phase 2 attacks in phase 1

- - - -

- Rajang
  - Size increased
  - Added several new combos
- Stygian Zinogre
  - Turns inside out every other action
- Safi'jiiva
  - Flattened sideways
- Raging Brachydios
  - Same as Brachydios
- Furious Rajang
  - Size increased
  - Speed increased
- Frostfang Barioth
  - Certain attacks sped up significantly
  - Slightly longer
- Alatreon
  - Added teammates
- Fatalis
  - Certain phase 3 attacks added to phase 1 and 2
  - Certain attacks sped up significantly
  - Certain attacks sometimes swapped for more dangerous attacks
  - Turns inside out when doing a certain attack

- - - -

Note: Since none of these monsters are required, less effort was put into them.
- TziTzi-Ya-Ku
  - Walking speed increased significantly
  - Flash attack sped up very significantly
  - Certain MR attacks swapped out with other attacks
- Great Girros
  - Flattened vertically
- Black Diablos
  - Size increased
- Dodogama
  - Gets slightly bigger with each action, until a limit
- Uragaan
  - Size increased
- Lavasioth
  - Same as Jyuratodus
- Bazelgeuse
  - Size increased significantly
- Kirin
  - Gets randomly squashed with each action
- Deviljho
  - Size increased
- Savage Deviljho
  - Size increased
- Lunastra
  - Size increased
  - Speed increased
- Zinogre
  - Turned inside out
- Yian Garuga
  - Charge speed increased
  - Size increased
- Scarred Yian Garuga
  - Same as Yian Garuga
- Silver Rathalos
  - Longer
- Golden Rathian
  - Wider
- Brute Tigrex
  - Speed decreased slightly
  - Size increased
</details>

















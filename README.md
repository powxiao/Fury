# Fury
Fury Addon originally by Bhaerau, modifications for end game raiding in vanilla by cubenicke. Purpose for the addon is to make a Fury warriors life easier while raiding in vanilla wow.
Fury makes one button for the warrior rotation, but still makes it possible to adapt the rotation with manual settings to make it adapt for each fight. Also gives some aid with mid-fight buffs
like Jujus.

## Usage
In key bindings, bind these actions to some keys available to you mid fight (Same commands can also be created as macros - to create a button on action bar). Easiest way to get going
is to bind keys to Attack and Charge. Those two will work in most situations and just use charge to initiate fights (2-3 presses) then spam use Attack. When You want to have more control over
the logic you can go into the other keybinds or even macros to finetune your playstyle and handle certain mechanics.   

### KeyBinds
Attack - One button Fury Warrior rotation. Spam it!  
Charge - Will charge or intercept, sometimes builds rage and or switch stance to be able to charge/intercept.  
Toggle HS or Cleave - Dump excessing rage with Heroic Strike or Cleave. Useful in threat situations and for a AoE with single mob prio.  
Toggle WW - Stops using Whirlwind during normal rotation, toggle it in CC situations. or Kel'Thuzad to don't do damage on Mind Controlled people.   
Toggle DW - Enable it a bit into fights when you want your first Death Wish to fire off (Also controls Orc racial Blood Fury).  

### Usage as Macros
Some commands exists as key bindings, but for most commands one has to write a macro to make them usable during combat.
To get a button to press on the action bar, create a macro
    
    /fury juju power

To get the correct Icon for the macro, edit the macro file in a text editor **WTF/<account>/<character>/macros-cache.txt**, change the icon name to the correct one. See below for some icon names.

    MACRO 16777224 "Power" INV_Misc_MonsterScales_11
        /fury juju power
    END

## Reference
### Logic
Dismount (Mounted only)  
Berserker Rage (Feared only)  
Execute  
Overpower  
Pummel / Shield Bash  
Hamstring  
Piercing Howl  
Rend (PvP only)  
Sweeping Strikes  
Berserker Rage (PvE only)  
Bloodrage  
Berserking (Troll racial)  
Disarm (PvP only)  
Demoralizing Shout (PvE only)  
Battle Shout  
Mortal Strike / Bloodthirst  
Whirlwind  
Juju Flurry  
Juju Chill  
Juju Ember  
Juju Might  
Juju Power  
Oil of Immolation  
Blood Fury (Orc racial)  
Death Wish (on every cooldown)  
Hamstring  
Heroic Strike / Cleave  

### Abilities
**Name, Icon**  
![](https://classicdb.ch/images/icons/small/ability_warrior_battleshout.jpg) [Battle Shout](https://classicdb.ch/?spell=25959)  
![](https://classicdb.ch/images/icons/small/spell_nature_ancestralguardian.jpg) [Berserker Rage](https://classicdb.ch/?spell=18449)  
![](https://classicdb.ch/images/icons/small/racial_orc_berserkerstrength.jpg) [Blood Fury](https://classicdb.ch/?spell=20572)  
![](https://classicdb.ch/images/icons/small/ability_racial_bloodrage.jpg) [Bloodrage](https://classicdb.ch/?spell=2687)  
![](https://classicdb.ch/images/icons/small/spell_nature_bloodlust.jpg) [Bloodthirst](https://classicdb.ch/?spell=23900)  
![](https://classicdb.ch/images/icons/small/ability_warrior_charge.jpg) [Charge](https://classicdb.ch/?spell=11578)  
![](https://classicdb.ch/images/icons/small/ability_warrior_cleave.jpg) [Cleave](https://classicdb.ch/?spell=20569)  
![](https://classicdb.ch/images/icons/small/spell_shadow_deathpact.jpg) [Death Wish](https://classicdb.ch/?spell=12328)  
![](https://classicdb.ch/images/icons/small/ability_warrior_warcry.jpg) [Demoralizing Shout](https://classicdb.ch/?spell=11556)  
![](https://classicdb.ch/images/icons/small/ability_warrior_disarm.jpg) [Disarm](https://classicdb.ch/?spell=676)  
![](https://classicdb.ch/images/icons/small/inv_sword_48.jpg) [Execute](https://classicdb.ch/?spell=20662)  
![](https://classicdb.ch/images/icons/small/ability_shockwave.jpg) [Hamstring](https://classicdb.ch/?spell=7373)  
![](https://classicdb.ch/images/icons/small/ability_rogue_ambush.jpg) [Heroic Strike](https://classicdb.ch/?spell=25286)  
![](https://classicdb.ch/images/icons/small/ability_rogue_sprint.jpg) [Intercept](https://classicdb.ch/?spell=20252)  
![](https://classicdb.ch/images/icons/small/ability_warrior_savageblow.jpg) [Mortal Strike](https://classicdb.ch/?spell=21553)  
![](https://classicdb.ch/images/icons/small/ability_meleedamage.jpg) [Overpower](https://classicdb.ch/?spell=11585)  
![](https://classicdb.ch/images/icons/small/inv_gauntlets_04.jpg) [Pummel](https://classicdb.ch/?spell=6552)  
![](https://classicdb.ch/images/icons/small/spell_shadow_deathscream.jpg) [Piercing Howl](https://classicdb.ch/?spell=12323)  
![](https://classicdb.ch/images/icons/small/ability_gouge.jpg) [Rend](https://classicdb.ch/?spell=11574)  
![](https://classicdb.ch/images/icons/small/ability_warrior_revenge.jpg) [Revenge](https://classicdb.ch/?spell=25288)  
![](https://classicdb.ch/images/icons/small/ability_warrior_shieldbash.jpg) [Shield Bash](https://classicdb.ch/?spell=72)  
![](https://classicdb.ch/images/icons/small/inv_shield_05.jpg) [Shield Slam](https://classicdb.ch/?spell=23925)  
![](https://classicdb.ch/images/icons/small/ability_marksmanship.jpg) [Shoot Bow,Crossbow,Gun](https://classicdb.ch/?spell=3018)  
![](https://classicdb.ch/images/icons/small/ability_warrior_sunder.jpg) [Sunder Armor](https://classicdb.ch/?spell=11597)  
![](https://classicdb.ch/images/icons/small/ability_rogue_slicedice.jpg) [Sweeping Strikes](https://classicdb.ch/?spell=26654)  
![](https://classicdb.ch/images/icons/small/spell_nature_thunderclap.jpg) [Thunder Clap](https://classicdb.ch/?spell=11581)  
![](https://classicdb.ch/images/icons/small/ability_throw.jpg) [Throw](https://classicdb.ch/?spell=2764)  
![](https://classicdb.ch/images/icons/small/ability_whirlwind.jpg) [Whirlwind](https://classicdb.ch/?spell=1680)  

### Items in rotation
#### For rage calculations
![](https://classicdb.ch/images/icons/small/inv_gauntlets_23.jpg) [Knight-Lieutenant's Plate Gauntlets](https://classicdb.ch/?item=16406)  
![](https://classicdb.ch/images/icons/small/inv_gauntlets_29.jpg) [Marshal's Plate Gauntlets](https://classicdb.ch/?item=16484)  
![](https://classicdb.ch/images/icons/small/inv_gauntlets_26.jpg) [Blood Guard's Plate Gloves](https://classicdb.ch/?item=16510)  
![](https://classicdb.ch/images/icons/small/inv_gauntlets_10.jpg) [General's Plate Gauntlets](https://classicdb.ch/?item=16548)  

#### Situational
![](https://classicdb.ch/images/icons/small/inv_jewelry_trinketpvp_01.jpg) [Insignia of the Alliance](https://classicdb.ch/?item=18854)  
![](https://classicdb.ch/images/icons/small/inv_jewelry_trinketpvp_02.jpg) [Insignia of the Horde](https://classicdb.ch/?item=18834)  
![](https://classicdb.ch/images/icons/small/inv_belt_25.jpg) [Spider Belt](https://classicdb.ch/?item=3863)  
![](https://classicdb.ch/images/icons/small/inv_boots_01.jpg) [Ornate Mithril Boots](https://classicdb.ch/?item=7936)  
![](https://classicdb.ch/images/icons/small/inv_misc_rune_01.jpg) [Tidal Charm](https://classicdb.ch/?item=1404)  
![](https://classicdb.ch/images/icons/small/inv_weapon_shortblade_10.jpg) [Linken's Boomerang](https://classicdb.ch/?item=11905)  

### Consumables
  * ![](https://classicdb.ch/images/icons/small/inv_misc_monsterscales_09.jpg) [Juju Chill](https://classicdb.ch/?item=12457) (Only on Kel'Thuzad and Sapphiron)
  * ![](https://classicdb.ch/images/icons/small/inv_misc_monsterscales_15.jpg) [Juju Ember](https://classicdb.ch/?item=12455)
  * ![](https://classicdb.ch/images/icons/small/inv_misc_monsterscales_17.jpg) [Juju Flurry](https://classicdb.ch/?item=12450)
  * ![](https://classicdb.ch/images/icons/small/inv_misc_monsterscales_07.jpg) [Juju Might](https://classicdb.ch/?item=12460) (Doesn't overrride ![](https://classicdb.ch/images/icons/small/inv_potion_92.jpg) [Winterfall Firewater](https://classicdb.ch/?item=12820))
  * ![](https://classicdb.ch/images/icons/small/inv_misc_monsterscales_11.jpg) [Juju Power](https://classicdb.ch/?item=12451) (Doesn't overrride ![](https://classicdb.ch/images/icons/small/inv_potion_61.jpg) [Elixir of Giants](https://classicdb.ch/?item=9206))
  * ![](https://classicdb.ch/images/icons/small/inv_potion_11.jpg) [Oil of Immolation](https://classicdb.ch/?item=8956)


### operational Control
```
/fury - uses Fury
/fury charge - uses Intercept or Charge sequence
/fury shoot - fires ranged weapon
/fury aoe - enables cleave and whirlwind, disables overpower, bloodhtirst, Heroic Strike (Swithced off when fewer than 2 enemies)
/fury toggle - toggles Fury on/off
/fury threat - enables Cleave or Heroic Strike based on current settings, use on threat critical fights to decrease threat build up
/fury juju flurry|power|might|ember|chill - enables buff on every cooldown, chill only on Kel'Thuzad and Sapphiron
/fury ooi - enables Oil of Immolation whenever OoI buff is not up
/fury ability <name> - toggles the use of abilities. Must use correct names with capitalization, ie. Heroic Strike, Rend etc.
```
### Setup commands
```
/fury dance <number> - sets rage allowed to be wasted when switching stance ("dancing")
/fury attackrage <number> - sets minimum rage required when using Heroic Strike or Cleave
/fury rage <number> - sets maximum rage allowed when using abilities to gain rage
/fury bloodrage <number> - sets minimum percent of health required when using Bloodrage
/fury hamstring <number> - sets maximum percent of health allowed when using Hamstring on NPCs
/fury berserk <number> - sets minimum percent of health required when using Berserk
/fury deathwish <number> - sets minimum percent of health required when using Death Wish
/fury demodiff <number> - If Target is x levels below Demoralizing Shout is not used
/fury stance <name> - sets stance to return to after switching stance. If default is selected it will return to your last used stance. If no stance is selected it will disable stance switching. Must use correct names with capitalization.
/fury talents - Rescan range spells and talent tree (needed after action bar buttons have moved)
```
### Debugging
```
/fury help [command] - prints help text
/fury attack - toggles the use of autoattack. Experimental.
/fury debug - toggles debug mode
/fury distance - show distance to target  
/fury log [on|off] - Start a new channel for logging commands will be saved to Logs folder
/fury unit [player|target] - shows buffs and debuffs for player or target
/fury where - info about whereabouts
```
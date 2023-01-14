minetest modpack 3d Armor
===========================

ARMOR pack for your gameplay

## Information
--------------

This mod provides ARMORS to your gameplays, such like shields, gloves, wielded, 
helmet, chestplate, leggings and boots.

![screenshot.png](screenshot.png)

## Technical info
-----------------

This modpack must be named `3d_armor` and enables armor manage for the gameplay

It can be download from 

* https://git.minetest.io/minenux/minetest-mod-3d_armor
* https://codeberg.org/minenux/minetest-mod-3d_armor

This modpack provides `3d_armor`, `3d_armor_gloves`, `3d_armor_stand`, `shields` and `wieldview`

Aditional this particular modpack integrates back `3d_armor_technic`

For the inventory it provides integration for `sfinv`, `inventory_plus` and `unified_inventory`

- [[mod] Visible Player Armor [3d_armor and 3d_armor_technic]](#mod-visible-player-armor-3d_armor)
- [[mod] Visible Wielded Items [wieldview]](#mod-visible-wielded-items-wieldview)
- [[mod] Shields [shields]](#mod-shields-shields)
- [[mod] 3d Armor Stand [3d_armor_stand]](#mod-3d-armor-stand-3d_armor_stand)

### [mod] Visible Player Armor [3d_armor]

Minetest Version: 0.4.16 +

Game: minetest_game and many derivatives

Depends: default

Adds craftable armor that is visible to other players. Each armor item worn contributes to
a player's armor group level making them less vulnerable to attack.

Armor takes damage when a player is hurt, however, many armor items offer a 'stackable'
percentage chance of restoring the lost health points. Overall armor level is boosted by 10%
when wearing a full matching set (helmet, chestplate, leggings and boots of the same material)

Fire protection has been added by TenPlus1 and in use when ethereal mod is found and crystal
armor has been enabled.  each piece of armor offers 1 fire protection, level 1 protects
against torches, level 2 against crystal spikes, 3 for fire and 5 protects when in lava.

Compatible with sfinv, inventory plus or unified inventory by enabling the appropriate
inventory module, [3d_armor_sfinv], [3d_armor_ip] and [3d_armor_ui] respectively.
Also compatible with [smart_inventory] without the need for additional modules.

built in support player skins [skins] by Zeg9 and Player Textures [player_textures] by PilzAdam
and [simple_skins] by TenPlus1.

Armor can be configured by adding a file called armor.conf in 3d_armor mod or world directory.
see armor.conf.example for all available options.

For mod installation instructions, please visit: http://wiki.minetest.com/wiki/Installing_Mods

### [mod] Visible Wielded Items [wieldview]

Depends: 3d_armor

Makes hand wielded items visible to other players.

### [mod] Shields [shields]

Depends: 3d_armor

Originally a part of 3d_armor, shields have been re-included as an optional extra.
If you do not want shields then simply remove the shields folder from the modpack.

### [mod] 3d Armor Stand [3d_armor_stand]

Depends: 3d_armor

Adds a chest-like armor stand for armor storage and display.

## LICENSE

License Source Code: Copyright (C) 2013-2018 Stuart Jones - LGPL v2.1

Armor Textures: Copyright (C) 2017-2018 davidthecreator - CC-BY-SA 3.0

Special credit to Jordach and MirceaKitsune for providing the default 3d character model.

Changes the color of the admin armor from stupid rose 3d_armor mod to black.

License: Creative Commons Attribution-NonCommercial-ShareAlike


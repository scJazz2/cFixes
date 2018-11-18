# Community Fixes
Community fixes to the Harebrained Schemes game BATTLETECH.
http://harebrained-schemes.com/
https://www.paradoxplaza.com/games/

This MOD is intended to be version neutral. It contains no game play changes beyond fixing simple JSON typos.

The following link is the source of this mod. Do not comment on this thread unless it is a new simple JSON Typo!
https://forum.paradoxplaza.com/forum/index.php?threads/simple-json-typo-fixes-for-1-3.1126334/

## Credits
These files are the result of the combined work of several community members, namely:
(all names are paradoxplaza.com nicknames)
- Amechwarrior: bug tracing and code review
- Dr. Banzai: bug fixes and configuration management
- scJazz: bug fixes and code review

Special thanks
- Justin Kase: writing the original thread that listed many of the fixes contained. This wouldn't be complete without his work.
- Ark Evensong: writing the original thread regarding Pilots and the fixes

The files are intended for free use and re-use.
The authors do not claim any intellectual or legal property on the content of these files. 

## List of Fixes (by directory)

### /data/chassis/
chassisdef_commando_COM-1B.json - fixed typo: "IB" changed to "1B".
chassisdef_thunderbolt_TDR-5S.json - fixed typo: "well armored and" changed to "well armed and".
chassisdef_trebuchet_TBT-5N.json - fixed value: CT Armor 120 changed to 160.
chassisdef_zeus_ZEU-6S.json - fixed value: Jump Jets 3 changed to 4.

### /data/events/
event_mw_arcadeMercenaries.json - fixed typo: "his" changed to "{TGT_MW.Gender?Male:his|Female:her|NonBinary:their}"

### /data/factions/
faction_MagistracyOfCanopus.json - fixed typo: "conservation" changed to "compensation"

### /data/mech/
mechdef_cataphract_CTF-1X.json - removed tag: "unit_jumpOK", 
mechdef_catapult_CPLT-C1.json - added tag: "unit_jumpOK", - added tag: "unit_indirectFire",
mechdef_centurion_CN9-AL.json - added tag: "unit_indirectFire",
mechdef_commando_COM-1B.json - fixed typo: "IB" changed to "1B"
mechdef_highlander_HGN-733P.json - added tag: "unit_indirectFire",
mechdef_jagermech_JM6-A.json - added tag: "unit_indirectFire",
mechdef_orion_ON1-K.json - added tag: "unit_indirectFire",
mechdef_quickdraw_QKD-5A.json - removed tag: "unit_indirectFire",
mechdef_zeus_ZEU-6S.json - added tag: "unit_indirectFire",

### /data/pilot/
The exact list of changes is to long to detail see original thread...
https://forum.paradoxplaza.com/forum/index.php?threads/battletech-pregenerated-ronin-kickstarter-pilots-missing-passive-skills.1125874/
along with the additions noted by Amechwarrior for PvP pilots...
https://forum.paradoxplaza.com/forum/index.php?threads/simple-json-typo-fixes-for-1-3.1126334/

### /data/starsystem/
starsystemdef_NewGanymede.json - fixed typo: "Concordant" changed to "Concordat"

### /data/vehicle/
vehicledef_APC_Wheeled.json - fixed value: Turret Armor 210 changed to 30 - fixed value: Turret Structure 30 changed to 5
vehicledef_STRIKER.json - fixed value: Turret Armor 120 changed to 110

### /data/weapon/
Weapon_LRM_LRM5_2-Delta.json - fixed value: "Instability" : 5, changed to "Instability" : 4,
Weapon_LRM_LRM10_2-Delta.json - fixed value: "Instability" : 5, changed to "Instability" : 4,
Weapon_LRM_LRM15_2-Delta.json - fixed value: "Instability" : 5, changed to "Instability" : 4,
Weapon_PPC_PPCER_0-STOCK.json - added ability: PPC status debuff "sensors impaired"
Weapon_SRM_SRM6_1-Holly.json - fixed value: "Cost" : 140000, changed to "Cost" : 120000,
Weapon_SRM_SRM6_2-Holly.json - fixed value: "AccuracyModifier" : -5, changed to "AccuracyModifier" : 0, - fixed value: "Cost" : 330000, changed to "Cost" : 125000,


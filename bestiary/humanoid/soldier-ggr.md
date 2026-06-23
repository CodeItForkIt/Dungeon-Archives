---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Soldier"
---
# [Soldier](/bestiary/humanoid/soldier-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 226*  

Soldiers are found in many of Ravnica's guilds. The soldier stat block represents a typical member of the rank and file, though weaponry and armor can vary.

```statblock
"name": "Soldier (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "[chain mail](/items/chain-mail-xphb.md), [shield](/items/shield-xphb.md)"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"modifier": !!int "1"
"stats":
  - !!int "13"
  - !!int "12"
  - !!int "12"
  - !!int "10"
  - !!int "11"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Perception](/rules/skills.md#Perception)"
    "desc": "+2"
  - "name": "[Athletics](/rules/skills.md#Athletics)"
    "desc": "+3"
"gear":
  - "[longsword](/items/longsword-xphb.md)"
"senses": "passive Perception 12"
"languages": "any one language (usually Common)"
"cr": "1/2"
"traits":
  - "desc": "The soldier has advantage on saving throws against being [charmed](/rules/conditions.md#Charmed),\
      \ [frightened](/rules/conditions.md#Frightened), [grappled](/rules/conditions.md#Grappled),\
      \ or [restrained](/rules/conditions.md#Restrained) while it is within 5 feet\
      \ of at least one ally."
    "name": "Formation Tactics"
"actions":
  - "desc": "The soldier makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d8 + 2) slashing damage, or 7 (1d10 + 2) slashing damage if used with\
      \ two hands."
    "name": "Longsword"
"source":
  - "GGR"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Soldier.webp"
```
^statblock
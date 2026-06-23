---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/rhw
- monster/cr/1
- monster/environment/any
- monster/size/medium
- monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Boneless"
---
# [Boneless](/bestiary/undead/boneless-rhw.md)
*Source: RHW p. 238*  

*Flayed Flesh with Murderous Intent*

Boneless are the animate skins of crushed or flensed humanoids. They rise from the corpses of those who suffered brutal ends such as flaying, crushing, or cannibalism. These hateful skins might seek vengeance, constricting and smothering victims using their elastic bodies. Alternatively, necromancers might create boneless to serve as stealthy assassins.

Vile magic-users might order a boneless to hang like a grotesque banner or adorn a skeleton or zombie. When foes approach, the boneless peels away from its surroundings or undead ally to face them.

```statblock
"name": "Boneless (RHW)"
"size": "Medium"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"hp": !!int "22"
"hit_dice": "4d8 + 4"
"modifier": !!int "2"
"stats":
  - !!int "15"
  - !!int "14"
  - !!int "12"
  - !!int "1"
  - !!int "10"
  - !!int "1"
"speed": "30 ft."
"skillsaves":
  - "name": "[Stealth](/rules/skills.md#Stealth)"
    "desc": "+4"
"damage_resistances": "bludgeoning"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/rules/conditions.md#Exhaustion), [poisoned](/rules/conditions.md#Poisoned)"
"senses": "[Darkvision](/rules/senses.md#Darkvision) 60 ft., passive Perception 10"
"languages": "understands Common but can't speak"
"cr": "1"
"traits":
  - "desc": "The boneless needn't spend extra movement to move a creature it is grappling."
    "name": "Abduct"
  - "desc": "The boneless can move through a space as narrow as 1 inch without expending\
      \ extra movement to do so."
    "name": "Compression"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 7 (2d4 + 2) Bludgeoning\
      \ damage. If the target is a Medium or smaller creature, it has the [Grappled](/rules/conditions.md#Grappled)\
      \ condition (escape DC 12). Until the grapple ends, the target has the [Blinded](/rules/conditions.md#Blinded)\
      \ and [Restrained](/rules/conditions.md#Restrained) conditions, is suffocating,\
      \ and takes 7 (2d4 + 2) Bludgeoning damage at the start of each of the boneless's\
      \ turns. The boneless can smother only one creature at a time. While grappling\
      \ a target, the boneless can't take this action again."
    "name": "Smother"
"bonus_actions":
  - "desc": "*Wisdom Saving Throw:* DC 11, each creature within 30 feet that can see\
      \ the boneless. *Failure:* The target has the [Frightened](/rules/conditions.md#Frightened)\
      \ condition. *Failure or Success:* The boneless moves up to its [Speed](/rules/variant-rules/speed-xphb.md)\
      \ without provoking Opportunity Attacks."
    "name": "Unraveling Flesh (1/Day)"
"source":
  - "RHW"
```
^statblock

## Environment

any
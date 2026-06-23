---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/fraif
- monster/cr/5
- monster/environment/underdark
- monster/environment/urban
- monster/size/medium
- monster/type/humanoid/drow-elf
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Drow Elite Warrior of Lolth"
---
# [Drow Elite Warrior of Lolth](/bestiary/humanoid/drow-elite-warrior-of-lolth-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 260*  

Elite warriors of Lolth lead raids and command garrisons in the Underdark.

## Drow of Lolth

*Elves Who Serve the Spider Queen*

Throughout the vast Underdark, in cities such as Menzoberranzan, many drow worship Lolth, the Spider Queen. Exiled from the surface world millennia ago, these drow now consider the Underdark to be their true home. Their insidious schemes include raiding the surface, plotting against each other, and preparing for ultimate war.

```statblock
"name": "Drow Elite Warrior of Lolth (FRAiF)"
"size": "Medium"
"type": "humanoid"
"subtype": "Drow elf"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"hp": !!int "71"
"hit_dice": "11d8 + 22"
"modifier": !!int "4"
"stats":
  - !!int "13"
  - !!int "18"
  - !!int "14"
  - !!int "11"
  - !!int "13"
  - !!int "12"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "7"
  - "constitution": !!int "5"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Perception](/rules/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](/rules/skills.md#Stealth)"
    "desc": "+10"
"gear":
  - "[shield](/items/shield-xphb.md)"
  - "[shortsword](/items/shortsword-xphb.md)"
  - "[studded leather armor](/items/studded-leather-armor-xphb.md)"
"senses": "[Darkvision](/rules/senses.md#Darkvision) 120 ft., passive Perception 14"
"languages": "Common, Elvish, Undercommon"
"cr": "5"
"traits":
  - "desc": "The drow has [Advantage](/rules/variant-rules/advantage-xphb.md) on saving\
      \ throws it makes to avoid or end the [Charmed](/rules/conditions.md#Charmed)\
      \ condition, and magic can't put the drow to sleep."
    "name": "Fey Ancestry"
  - "desc": "While in sunlight, the drow has [Disadvantage](/rules/variant-rules/disadvantage-xphb.md)\
      \ on attack rolls."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "The drow makes two attacks using Shortsword or Drow Hand Crossbow in\
      \ any combination"
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +7, reach 5 ft. *Hit:* 11 (2d6 + 4) Piercing\
      \ damage plus 10 (3d6) Poison damage."
    "name": "Shortsword"
  - "desc": "*Ranged Attack Roll:* +7, range 30/120 ft. *Hit:* 7 (1d6 + 4) Piercing\
      \ damage, and the target makes a saving throw. *Constitution Saving Throw:*\
      \ DC 15. *Failure:* The target has the [Poisoned](/rules/conditions.md#Poisoned)\
      \ condition for 1 hour. While [Poisoned](/rules/conditions.md#Poisoned) in this\
      \ way, the target also has the [Unconscious](/rules/conditions.md#Unconscious)\
      \ condition. The target wakes up if it takes damage or if a creature within\
      \ 5 feet of it takes an action to wake it."
    "name": "Drow Hand Crossbow"
"bonus_actions":
  - "desc": "The drow casts [Darkness](/spells/darkness-xphb.md), [Faerie Fire](/spells/faerie-fire-xphb.md),\
      \ or [Levitate](/spells/levitate-xphb.md) (self only), requiring no Material\
      \ components and using Charisma as the spellcasting ability (spell save DC 12).\n"
    "name": "Underdark Magic (3/Day)"
"source":
  - "FRAiF"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/FRAiF/Drow%20Elite%20Warrior%20of%20Lolth.webp"
```
^statblock

## Environment

underdark, urban
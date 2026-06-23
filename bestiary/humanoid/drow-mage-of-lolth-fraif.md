---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/fraif
- monster/cr/7
- monster/environment/underdark
- monster/environment/urban
- monster/size/medium
- monster/type/humanoid/drow-elf
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Drow Mage of Lolth"
---
# [Drow Mage of Lolth](/bestiary/humanoid/drow-mage-of-lolth-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 261*  

Some drow pursue arcane study, summoning Fiends from the Abyss in Lolth's name.

## Drow of Lolth

*Elves Who Serve the Spider Queen*

Throughout the vast Underdark, in cities such as Menzoberranzan, many drow worship Lolth, the Spider Queen. Exiled from the surface world millennia ago, these drow now consider the Underdark to be their true home. Their insidious schemes include raiding the surface, plotting against each other, and preparing for ultimate war.

```statblock
"name": "Drow Mage of Lolth (FRAiF)"
"size": "Medium"
"type": "humanoid"
"subtype": "Drow elf"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"hp": !!int "81"
"hit_dice": "18d8"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "10"
  - !!int "17"
  - !!int "13"
  - !!int "12"
"speed": "30 ft., fly 15 ft. (hover)"
"saves":
  - "dexterity": !!int "5"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Arcana](/rules/skills.md#Arcana)"
    "desc": "+6"
  - "name": "[Perception](/rules/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](/rules/skills.md#Stealth)"
    "desc": "+5"
"senses": "[Darkvision](/rules/senses.md#Darkvision) 120 ft., passive Perception 14"
"languages": "Abyssal, Common, Elvish, Undercommon"
"cr": "7"
"traits":
  - "desc": "The drow has [Advantage](/rules/variant-rules/advantage-xphb.md) on saving\
      \ throws it makes to avoid or end the [Charmed](/rules/conditions.md#Charmed)\
      \ condition, and magic can't put the drow to sleep."
    "name": "Fey Ancestry"
  - "desc": "While in sunlight, the drow has [Disadvantage](/rules/variant-rules/disadvantage-xphb.md)\
      \ on attack rolls."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "The drow makes three Abyssal Burst attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +6, reach 5 ft. or range 120 ft. *Hit:*\
      \ 21 (4d8 + 3) Poison damage."
    "name": "Abyssal Burst"
  - "desc": "The drow casts one of the following spells, requiring no Material components\
      \ and using Intelligence as the spellcasting ability (spell save DC 14, +6\
      \ to hit with spell attacks):\n\n**At will:** [Dancing Lights](/spells/dancing-lights-xphb.md),\
      \ [Mage Armor](/spells/mage-armor-xphb.md) (included in AC), [Mage Hand](/spells/mage-hand-xphb.md),\
      \ [Minor Illusion](/spells/minor-illusion-xphb.md)\n\n**1/day:** [Summon Fiend](/spells/summon-fiend-xphb.md)\
      \ (demon only)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The drow casts [Faerie Fire](/spells/faerie-fire-xphb.md) or [Misty Step](/spells/misty-step-xphb.md),\
      \ requiring no Material components and using the same spellcasting ability as\
      \ Spellcasting.\n"
    "name": "Underdark Magic (3/Day)"
"source":
  - "FRAiF"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/FRAiF/Drow%20Mage%20of%20Lolth.webp"
```
^statblock

## Environment

underdark, urban
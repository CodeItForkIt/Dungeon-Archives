---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/4
- monster/environment/arctic
- monster/environment/forest
- monster/environment/mountain
- monster/environment/swamp
- monster/environment/urban
- monster/size/medium
- monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Warlock of the Archfey"
---
# [Warlock of the Archfey](/bestiary/humanoid/warlock-of-the-archfey-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 255, Volo's Guide to Monsters p. 219*  

Warlocks of the Archfey gain their powers through magical pacts forged with lords of the Feywild. These warlocks commonly associate with lesser Fey creatures such as [boggles](/bestiary/fey/boggle-mpmm.md), [quicklings](/bestiary/fey/quickling-mpmm.md), and [redcaps](/bestiary/fey/redcap-mpmm.md) (all appear in "this book") or even [satyrs](/bestiary/fey/satyr-xmm.md) and [sprites](/bestiary/fey/sprite-xmm.md).

## Warlocks

Warlocks gain arcane might through magical pacts with mysterious entities. While some use their abilities to serve the sources of their power, others use them to undermine or even destroy these entities.

```statblock
"name": "Warlock of the Archfey (MPMM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "16 with [mage armor](/spells/mage-armor-xphb.md)"
"hp": !!int "67"
"hit_dice": "15d8"
"modifier": !!int "3"
"stats":
  - !!int "9"
  - !!int "16"
  - !!int "11"
  - !!int "11"
  - !!int "12"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "3"
  - "charisma": !!int "6"
"skillsaves":
  - "name": "[Arcana](/rules/skills.md#Arcana)"
    "desc": "+2"
  - "name": "[Deception](/rules/skills.md#Deception)"
    "desc": "+6"
  - "name": "[Nature](/rules/skills.md#Nature)"
    "desc": "+2"
  - "name": "[Persuasion](/rules/skills.md#Persuasion)"
    "desc": "+6"
"condition_immunities": "[charmed](/rules/conditions.md#Charmed)"
"gear":
  - "[rapier](/items/rapier-xphb.md)"
"senses": "passive Perception 11"
"languages": "any two languages (usually Sylvan)"
"cr": "4"
"actions":
  - "desc": "The warlock makes two Rapier attacks, or it uses Bewildering Word twice."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d8 + 3) piercing damage plus 7 (2d6) force damage."
    "name": "Rapier"
  - "desc": "The warlock utters a magical bewilderment, targeting one creature it\
      \ can see within 60 feet of it. The target must succeed on a DC 14 Wisdom saving\
      \ throw or take 9 (2d8) psychic damage and have disadvantage on attack rolls\
      \ until the end of the warlock's next turn."
    "name": "Bewildering Word"
  - "desc": "The warlock casts one of the following spells, using Charisma as the\
      \ spellcasting ability (spell save DC 14): \n\n**At will:** [dancing lights](/spells/dancing-lights-xphb.md),\
      \ [disguise self](/spells/disguise-self-xphb.md), [mage armor](/spells/mage-armor-xphb.md)\
      \ (self only), [mage hand](/spells/mage-hand-xphb.md), [minor illusion](/spells/minor-illusion-xphb.md),\
      \ [prestidigitation](/spells/prestidigitation-xphb.md), [speak with animals](/spells/speak-with-animals-xphb.md)\n\
      \n**1/day each:** [charm person](/spells/charm-person-xphb.md), [dimension door](/spells/dimension-door-xphb.md),\
      \ [hold monster](/spells/hold-monster-xphb.md)"
    "name": "Spellcasting"
"reactions":
  - "desc": "In response to taking damage, the warlock turns [invisible](/rules/conditions.md#Invisible)\
      \ and teleports, along with any equipment it is wearing or carrying, up to 60\
      \ feet to an unoccupied space it can see. It remains [invisible](/rules/conditions.md#Invisible)\
      \ until the start of its next turn or until it attacks, makes a damage roll,\
      \ or casts a spell."
    "name": "Misty Escape (Recharges after a Short or Long Rest)"
"source":
  - "MPMM"
  - "VGM"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Warlock%20of%20the%20Archfey.webp"
```
^statblock

## Environment

arctic, forest, mountain, swamp, urban
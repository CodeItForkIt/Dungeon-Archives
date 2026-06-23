---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/nf
- monster/cr/8
- monster/environment/any
- monster/size/medium
- monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Terran Magen"
---
# [Terran Magen](/bestiary/construct/terran-magen-nf.md)
*Source: Netheril's Fall*  

Terran magen are equipped with magic to help them perform laborious physical tasks. These magen commonly perform household handiwork and build infrastructure.

```statblock
"name": "Terran Magen (NF)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "21"
"hp": !!int "121"
"hit_dice": "22d8 + 22"
"modifier": !!int "3"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "12"
  - !!int "10"
  - !!int "18"
  - !!int "10"
"speed": "30 ft., fly 20 ft. (hover)"
"saves":
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "[Perception](/rules/skills.md#Perception)"
    "desc": "+7"
"damage_immunities": "poison, thunder"
"condition_immunities": "[blinded](/rules/conditions.md#Blinded), [charmed](/rules/conditions.md#Charmed),\
  \ [deafened](/rules/conditions.md#Deafened), [exhaustion](/rules/conditions.md#Exhaustion),\
  \ [frightened](/rules/conditions.md#Frightened), [paralyzed](/rules/conditions.md#Paralyzed),\
  \ [petrified](/rules/conditions.md#Petrified), [poisoned](/rules/conditions.md#Poisoned)"
"senses": "passive Perception 17"
"languages": "understands Common plus two other languages but can't speak"
"cr": "8"
"traits":
  - "desc": "If the magen dies, it disintegrates into dust, leaving behind anything\
      \ it was wearing or carrying."
    "name": "Disintegration"
  - "desc": "The magen has [Advantage](/rules/variant-rules/advantage-xphb.md) on\
      \ saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The magen makes two attacks, using Hammer Fist or Thunderous Boom in\
      \ any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +6, reach 5 ft. *Hit:* 16 (3d8 + 3) Bludgeoning\
      \ damage plus 13 (3d8) Force damage."
    "name": "Hammer Fist"
  - "desc": "*Ranged Attack Roll:* +7, range 60 ft. *Hit:* 28 (8d6) Thunder damage."
    "name": "Thunderous Boom"
  - "desc": "The magen casts one of the following spells, requiring no Material components\
      \ and using Wisdom as the spellcasting ability (spell save DC 15):\n\n**At will:**\
      \ [Mage Hand](/spells/mage-hand-xphb.md), [Mending](/spells/mending-xphb.md),\
      \ [Prestidigitation](/spells/prestidigitation-xphb.md)\n\n**1/day each:** [Disintegrate](/spells/disintegrate-xphb.md),\
      \ [Move Earth](/spells/move-earth-xphb.md), [Stone Shape](/spells/stone-shape-xphb.md)"
    "name": "Spellcasting"
"source":
  - "NF"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/NF/Terran%20Magen.webp"
```
^statblock

## Environment

any
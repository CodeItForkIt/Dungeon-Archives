---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/xmm
- monster/cr/1-4
- monster/environment/feywild
- monster/environment/forest
- monster/environment/planar
- monster/size/tiny
- monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Pixie"
---
# [Pixie](/bestiary/fey/pixie-xmm.md)
*Source: Monster Manual (2024) p. 244*  

Pixies spend their days frolicking and exploring and avoid direct conflict when they can.

## Pixies

*Friends of the Forest*

- **Habitat.** Forest, Planar (Feywild)  
- **Treasure.** [Arcana](Random%20-%20Magic%20Items%20Arcana.md)  

Barely a foot tall, pixies resemble diminutive elves with gossamer wings. They invisibly observe those who enter their wooded homes, revealing themselves to those with friendly intentions. Those who are unfriendly become the targets of pixies' pranks.

```statblock
"name": "Pixie (XMM)"
"size": "Tiny"
"type": "fey"
"alignment": "Neutral Good"
"ac": !!int "15"
"hp": !!int "9"
"hit_dice": "6d4 - 6"
"modifier": !!int "5"
"stats":
  - !!int "2"
  - !!int "20"
  - !!int "8"
  - !!int "10"
  - !!int "14"
  - !!int "15"
"speed": "10 ft., fly 30 ft."
"skillsaves":
  - "name": "[Perception](/rules/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](/rules/skills.md#Stealth)"
    "desc": "+7"
"senses": "passive Perception 14"
"languages": "Sylvan"
"cr": "1/4"
"traits":
  - "desc": "The pixie has [Advantage](/rules/variant-rules/advantage-xphb.md) on\
      \ saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "*Melee  or Ranged Attack Roll:* +4, reach 5 ft. or range 60 ft. *Hit:*\
      \ 1 Radiant damage, and the target has the [Charmed](/rules/conditions.md#Charmed)\
      \ or [Poisoned](/rules/conditions.md#Poisoned) condition (pixie's choice) until\
      \ the start of the pixie's next turn."
    "name": "Faerie Dust"
  - "desc": "The pixie casts one of the following spells, requiring no Material components\
      \ and using Charisma as the spellcasting ability (spell save DC 12):\n\n**At\
      \ will:** [Dancing Lights](/spells/dancing-lights-xphb.md), [Druidcraft](/spells/druidcraft-xphb.md),\
      \ [Invisibility](/spells/invisibility-xphb.md) (self only)\n\n**1/day each:**\
      \ [Detect Thoughts](/spells/detect-thoughts-xphb.md), [Fly](/spells/fly-xphb.md),\
      \ [Sleep](/spells/sleep-xphb.md)"
    "name": "Spellcasting"
"source":
  - "XMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Pixie.webp"
```
^statblock

## Environment

forest, planar, feywild
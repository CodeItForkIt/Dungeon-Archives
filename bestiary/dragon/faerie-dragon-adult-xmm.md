---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/xmm
- monster/cr/2
- monster/environment/forest
- monster/size/tiny
- monster/type/dragon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Faerie Dragon Adult"
---
# [Faerie Dragon Adult](/bestiary/dragon/faerie-dragon-adult-xmm.md)
*Source: Monster Manual (2024) p. 117*  

The pranks of faerie dragon adults tend to lead others to people in need or wrongs to be righted.

## Faerie Dragons

*Whimsical Draconic Tricksters*

- **Habitat.** Forest  
- **Treasure.** [Implements](Random%20-%20Magic%20Items%20Implements.md)  

Faerie dragons are cat-size pranksters with draconic features, butterfly-like wings, and scales of warm hues as youths and cool hues as adults.

```statblock
"name": "Faerie Dragon Adult (XMM)"
"size": "Tiny"
"type": "dragon"
"alignment": "Chaotic Good"
"ac": !!int "15"
"hp": !!int "35"
"hit_dice": "10d4 + 10"
"modifier": !!int "5"
"stats":
  - !!int "3"
  - !!int "20"
  - !!int "13"
  - !!int "14"
  - !!int "12"
  - !!int "16"
"speed": "10 ft., fly 60 ft."
"skillsaves":
  - "name": "[Arcana](/rules/skills.md#Arcana)"
    "desc": "+4"
  - "name": "[Perception](/rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](/rules/skills.md#Stealth)"
    "desc": "+7"
"senses": "[Darkvision](/rules/senses.md#Darkvision) 60 ft., passive Perception 13"
"languages": "Draconic, Sylvan; telepathy 60 ft. (faerie dragons only)"
"cr": "2"
"traits":
  - "desc": "The dragon has [Advantage](/rules/variant-rules/advantage-xphb.md) on\
      \ saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "*Melee Attack Roll:* +7, reach 5 ft. *Hit:* 7 (1d4 + 5) Piercing\
      \ damage plus 3 (1d6) Psychic damage."
    "name": "Bite"
  - "desc": "*Wisdom Saving Throw:* DC 13, each creature in a 15-foot [Cone](/rules/variant-rules/cone-area-of-effect-xphb.md).\
      \ *Failure:* The target has the [Incapacitated](/rules/conditions.md#Incapacitated)\
      \ condition and repeats the save at the end of each of its turns, ending the\
      \ effect on itself on a success. After 1 minute, it succeeds automatically.\
      \ While [Incapacitated](/rules/conditions.md#Incapacitated), the target uses\
      \ all its movement on each of its turns to move in a random direction."
    "name": "Euphoria Breath (Recharge 5-6)"
  - "desc": "The dragon casts one of the following spells, requiring no Material components\
      \ and using Charisma as the spellcasting ability (spell save DC 13):\n\n**At\
      \ will:** [Dancing Lights](/spells/dancing-lights-xphb.md), [Mage Hand](/spells/mage-hand-xphb.md),\
      \ [Minor Illusion](/spells/minor-illusion-xphb.md)\n\n**1/day each:** [Hallucinatory\
      \ Terrain](/spells/hallucinatory-terrain-xphb.md), [Polymorph](/spells/polymorph-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The dragon casts [Greater Invisibility](/spells/greater-invisibility-xphb.md)\
      \ on itself, requiring no spell components and using the same spellcasting ability\
      \ as Spellcasting.\n"
    "name": "Superior Invisibility"
"source":
  - "XMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Faerie%20Dragon%20Adult.webp"
```
^statblock

## Environment

forest
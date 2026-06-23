---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/xmm
- monster/cr/1
- monster/environment/forest
- monster/size/tiny
- monster/type/dragon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Faerie Dragon Youth"
---
# [Faerie Dragon Youth](/bestiary/dragon/faerie-dragon-youth-xmm.md)
*Source: Monster Manual (2024) p. 117*  

Faerie dragon youths are quick to use their euphoria-inducing breath on rude or uptight folk.

## Faerie Dragons

*Whimsical Draconic Tricksters*

- **Habitat.** Forest  
- **Treasure.** [Implements](/tables/random-magic-items-implements.md)  

Faerie dragons are cat-size pranksters with draconic features, butterfly-like wings, and scales of warm hues as youths and cool hues as adults.

```statblock
"name": "Faerie Dragon Youth (XMM)"
"size": "Tiny"
"type": "dragon"
"alignment": "Chaotic Good"
"ac": !!int "13"
"hp": !!int "21"
"hit_dice": "6d4 + 6"
"modifier": !!int "3"
"stats":
  - !!int "3"
  - !!int "16"
  - !!int "12"
  - !!int "12"
  - !!int "12"
  - !!int "14"
"speed": "10 ft., fly 60 ft."
"skillsaves":
  - "name": "[Arcana](/rules/skills.md#Arcana)"
    "desc": "+3"
  - "name": "[Perception](/rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](/rules/skills.md#Stealth)"
    "desc": "+5"
"senses": "[Darkvision](/rules/senses.md#Darkvision) 60 ft., passive Perception 13"
"languages": "Draconic, Sylvan; telepathy 60 ft. (faerie dragons only)"
"cr": "1"
"traits":
  - "desc": "The dragon has [Advantage](/rules/variant-rules/advantage-xphb.md) on\
      \ saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 5 (1d4 + 3) Piercing\
      \ damage plus 2 (1d4) Psychic damage."
    "name": "Bite"
  - "desc": "*Wisdom Saving Throw:* DC 12, each creature in a 15-foot [Cone](/rules/variant-rules/cone-area-of-effect-xphb.md).\
      \ *Failure:* The target has the [Incapacitated](/rules/conditions.md#Incapacitated)\
      \ condition until the end of its next turn and uses all its movement on its\
      \ turn to move in a random direction."
    "name": "Euphoria Breath (Recharge 5-6)"
  - "desc": "The dragon casts one of the following spells, requiring no Material components\
      \ and using Charisma as the spellcasting ability (spell save DC 12):\n\n**At\
      \ will:** [Dancing Lights](/spells/dancing-lights-xphb.md), [Mage Hand](/spells/mage-hand-xphb.md),\
      \ [Minor Illusion](/spells/minor-illusion-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The dragon casts [Greater Invisibility](/spells/greater-invisibility-xphb.md)\
      \ on itself, requiring no spell components and using the same spellcasting ability\
      \ as Spellcasting.\n"
    "name": "Superior Invisibility"
"source":
  - "XMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Faerie%20Dragon%20Youth.webp"
```
^statblock

## Environment

forest
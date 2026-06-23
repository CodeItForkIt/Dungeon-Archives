---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/xmm
- monster/cr/12
- monster/environment/any
- monster/size/small-or-medium
- monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Questing Knight"
---
# [Questing Knight](/bestiary/humanoid/questing-knight-xmm.md)
*Source: Monster Manual (2024) p. 184*  

Questing knights travel in pursuit of a cause, such as slaying a villain, defeating a monster, recovering an Artifact, or restoring their lost honor.

## Knights

*Battle Masters and Heroic Wanderers*

- **Habitat.** Any  
- **Treasure.** [Armaments](/tables/random-magic-items-armaments.md), Individual  

Knights are skilled warriors trained for war and tested in battle. Many serve the rulers of a realm, a religion, or an order devoted to a cause.

```statblock
"name": "Questing Knight (XMM)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Neutral"
"ac": !!int "18"
"hp": !!int "202"
"hit_dice": "27d8 + 81"
"modifier": !!int "7"
"stats":
  - !!int "20"
  - !!int "16"
  - !!int "16"
  - !!int "11"
  - !!int "12"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "strength": !!int "9"
  - "constitution": !!int "7"
  - "wisdom": !!int "5"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[Athletics](/rules/skills.md#Athletics)"
    "desc": "+9"
  - "name": "[Perception](/rules/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Persuasion](/rules/skills.md#Persuasion)"
    "desc": "+8"
"condition_immunities": "[charmed](/rules/conditions.md#Charmed), [frightened](/rules/conditions.md#Frightened)"
"gear":
  - "[greatsword](/items/greatsword-xphb.md)"
  - "[longbow](/items/longbow-xphb.md)"
  - "[plate armor](/items/plate-armor-xphb.md)"
"senses": "passive Perception 15"
"languages": "Common plus one other language"
"cr": "12"
"traits":
  - "desc": "Creatures of the knight's choice in a 30-foot [Emanation](/rules/variant-rules/emanation-area-of-effect-xphb.md)\
      \ originating from it have [Immunity](/rules/variant-rules/immunity-xphb.md)\
      \ to the [Charmed](/rules/conditions.md#Charmed) and [Frightened](/rules/conditions.md#Frightened)\
      \ conditions while there."
    "name": "Aura of Bravery"
"actions":
  - "desc": "The knight makes three attacks, using Greatsword or Longbow in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +9, reach 5 ft. *Hit:* 12 (2d6 + 5) Slashing\
      \ damage plus 22 (5d8) Radiant damage."
    "name": "Greatsword"
  - "desc": "*Ranged Attack Roll:* +7, range 150/600 ft. *Hit:* 12 (2d8 + 3) Piercing\
      \ damage plus 22 (5d8) Radiant damage."
    "name": "Longbow"
  - "desc": "The knight casts one of the following spells, using Charisma as the spellcasting\
      \ ability (spell save DC 16):\n\n**1/day each:** [Daylight](/spells/daylight-xphb.md),\
      \ [Dispel Evil and Good](/spells/dispel-evil-and-good-xphb.md), [Greater Restoration](/spells/greater-restoration-xphb.md),\
      \ [Phantom Steed](/spells/phantom-steed-xphb.md)"
    "name": "Spellcasting"
"source":
  - "XMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Questing%20Knight.webp"
```
^statblock

## Environment

any
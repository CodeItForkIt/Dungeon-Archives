---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/3
- monster/size/small-or-medium
- monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Society of Sensation Muse"
---
# [Society of Sensation Muse](/bestiary/humanoid/society-of-sensation-muse-mpp.md)
*Source: Morte's Planar Parade p. 61*  

The muses of the Society of Sensation are performers who enthrall crowds with spectacle and minor sensory experiences. When threatened, they beguile their foes, placating their enemies with magical displays.

```statblock
"name": "Society of Sensation Muse (MPP)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "[leather armor](/items/leather-armor-xphb.md)"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"modifier": !!int "3"
"stats":
  - !!int "8"
  - !!int "16"
  - !!int "12"
  - !!int "15"
  - !!int "14"
  - !!int "17"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "5"
  - "charisma": !!int "5"
"skillsaves":
  - "name": "[Insight](/rules/skills.md#Insight)"
    "desc": "+4"
  - "name": "[Perception](/rules/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Performance](/rules/skills.md#Performance)"
    "desc": "+7"
  - "name": "[Stealth](/rules/skills.md#Stealth)"
    "desc": "+5"
"senses": "passive Perception 14"
"languages": "Common plus two more languages"
"cr": "3"
"actions":
  - "desc": "The muse makes two Beguiling Resonance attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +5 to hit, reach 5 ft. or range 90\
      \ ft., one target. *Hit:* 9 (2d8) psychic damage. If the target is a creature,\
      \ it must succeed on a DC 13 Charisma saving throw or have disadvantage on the\
      \ next attack roll it makes until the end of its next turn."
    "name": "Beguiling Resonance"
  - "desc": "The muse casts one of the following spells, using Charisma as the spellcasting\
      \ ability (spell save DC 13):\n\n**At will:** [dancing lights](/spells/dancing-lights-xphb.md)\n\
      \n**1/day each:** [comprehend languages](/spells/comprehend-languages-xphb.md),\
      \ [hypnotic pattern](/spells/hypnotic-pattern-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Each creature within 30 feet of the muse must make a DC 13 Wisdom saving\
      \ throw. On a failed save, the creature has the [charmed](/rules/conditions.md#Charmed)\
      \ condition for 1 minute. On a successful save, the creature becomes immune\
      \ to any muse's Enchanting Presence for 24 hours.\n\nWhenever the muse deals\
      \ damage to the [charmed](/rules/conditions.md#Charmed) creature, the [charmed](/rules/conditions.md#Charmed)\
      \ creature can repeat the saving throw, ending the effect on itself on a success."
    "name": "Enchanting Presence"
"source":
  - "MPP"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Society%20of%20Sensation%20Muse.webp"
```
^statblock
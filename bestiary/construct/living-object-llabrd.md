---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/llabrd
- monster/cr/
- monster/size/medium
- monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Living Object"
---
# [Living Object](/bestiary/construct/living-object-llabrd.md)
*Source: Alternate Bard p. 3*  

```statblock
"name": "Living Object (LLABrd)"
"size": "Medium"
"type": "construct"
"alignment": "Any Good alignment"
"ac_class": "10 + CHA + PB"
"modifier": !!int "3"
"stats":
  - !!int "12"
  - !!int "16"
  - !!int "16"
  - !!int "2"
  - !!int "4"
  - !!int "8"
"speed": "30 ft., fly 30 ft."
"damage_immunities": "poison, psychic"
"condition_immunities": "[charmed](/rules/conditions.md#Charmed), exhausted, [poisoned](/rules/conditions.md#Poisoned)"
"senses": "passive Perception 12"
"languages": "understands the languages of its creator"
"traits":
  - "desc": "You add your PB to any ability check or saving throw that the Living\
      \ Object makes."
    "name": "Creator's Bond"
  - "desc": "Once per turn when the Living Object hits a creature with its Slam, the\
      \ target must succeed on a Wisdom saving throw or its speed is halved until\
      \ the start of your next turn as it dances."
    "name": "Enchanting Touch"
  - "desc": "If the Living Object makes a Dexterity ability check or saving throw,\
      \ it gains a bonus to its roll equal to one roll of your Bardic Inspiration\
      \ Die."
    "name": "Lively Dance"
"actions":
  - "desc": "*Melee Weapon Attack:* + CHA + PB to hit, reach 5 ft., one target. On\
      \ hit: magical bludgeoning damage equal to a roll of your Bardic Inspiration\
      \ Die + CHA."
    "name": "Slam"
"source":
  - "LLABrd"
```
^statblock
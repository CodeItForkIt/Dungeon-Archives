---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/xphb
- monster/cr/
- monster/size/medium
- monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Construct Spirit (Clay)"
---
# [Construct Spirit (Clay)](/bestiary/construct/construct-spirit-clay-xphb.md)
*Source: Player's Handbook (2024) p. 324*  

```statblock
"name": "Construct Spirit (Clay) (XPHB)"
"size": "Medium"
"type": "construct"
"alignment": "Neutral"
"ac_class": "13 + the spell's level"
"modifier": !!int "0"
"stats":
  - !!int "18"
  - !!int "10"
  - !!int "18"
  - !!int "14"
  - !!int "11"
  - !!int "5"
"speed": "30 ft."
"damage_resistances": "poison"
"condition_immunities": "[charmed](/rules/conditions.md#Charmed), [exhaustion](/rules/conditions.md#Exhaustion),\
  \ [frightened](/rules/conditions.md#Frightened), [paralyzed](/rules/conditions.md#Paralyzed),\
  \ [poisoned](/rules/conditions.md#Poisoned)"
"senses": "[Darkvision](/rules/senses.md#Darkvision) 60 ft., passive Perception 10"
"languages": "Understands the languages you know"
"actions":
  - "desc": "The spirit makes a number of Slam attacks equal to half this spell's\
      \ level (round down)."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* Bonus equals your spell attack modifier, reach 5\
      \ ft. *Hit:* 1d8 + 4 + the spell's level Bludgeoning damage."
    "name": "Slam"
"reactions":
  - "desc": "Trigger: The spirit takes damage from a creature. _Response:_ The spirit\
      \ makes a Slam attack against that creature if possible, or the spirit moves\
      \ up to half its Speed toward that creature without provoking [Opportunity Attacks](/rules/actions.md#Opportunity%20Attack)."
    "name": "Berserk Lashing"
"source":
  - "XPHB"
```
^statblock
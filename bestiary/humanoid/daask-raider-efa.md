---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/efa
- monster/cr/1
- monster/size/medium
- monster/type/humanoid/gnoll
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Daask Raider"
---
# [Daask Raider](/bestiary/humanoid/daask-raider-efa.md)
*Source: Eberron: Forge of the Artificer p. 58*  

Raiders use guerrilla tactics to ambush warehouses and beat down opponents. These skilled fistfighters work in tandem to claim goods and territory for Daask.

```statblock
"name": "Daask Raider (EFA)"
"size": "Medium"
"type": "humanoid"
"subtype": "gnoll"
"alignment": "Neutral Evil"
"ac": !!int "15"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"modifier": !!int "1"
"stats":
  - !!int "16"
  - !!int "12"
  - !!int "13"
  - !!int "10"
  - !!int "11"
  - !!int "8"
"speed": "30 ft."
"saves":
  - "strength": !!int "5"
"skillsaves":
  - "name": "[Athletics](/rules/skills.md#Athletics)"
    "desc": "+5"
  - "name": "[Perception](/rules/skills.md#Perception)"
    "desc": "+2"
"senses": "[Darkvision](/rules/senses.md#Darkvision) 60 ft., passive Perception 12"
"languages": "Common, Gnoll"
"cr": "1"
"traits":
  - "desc": "The raider has [Advantage](/rules/variant-rules/advantage-xphb.md) on\
      \ an attack roll against a creature if at least one of the raider's allies is\
      \ within 5 feet of the creature and the ally doesn't have the [Incapacitated](/rules/conditions.md#Incapacitated)\
      \ condition."
    "name": "Pack Tactics"
"actions":
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 5 (1d4 + 3) Bludgeoning\
      \ damage."
    "name": "Pummel"
"reactions":
  - "desc": "Trigger: The raider takes damage from a creature within 5 feet. _Response:_\
      \ The raider makes one Pummel attack, targeting the triggering creature."
    "name": "Smackback"
"source":
  - "EFA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/EFA/Daask%20Raider.webp"
```
^statblock
---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/llar
- monster/cr/
- monster/size/medium
- monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Beast of the Land"
---
# [Beast of the Land](/bestiary/beast/beast-of-the-land-llar.md)
*Source: Alternate Ranger*  

```statblock
"name": "Beast of the Land (LLAR)"
"size": "Medium"
"type": "beast"
"alignment": "Neutral"
"ac_class": "13 + PB (natural armor)"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "14"
  - !!int "13"
  - !!int "8"
  - !!int "12"
  - !!int "11"
"speed": "40 ft., climb 40 ft."
"saves":
  - "strength": !!int "5"
  - "dexterity": !!int "4"
"skillsaves":
  - "name": "[Stealth](/rules/skills.md#Stealth)"
    "desc": "+4"
  - "name": "[Perception](/rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Survival](/rules/skills.md#Survival)"
    "desc": "+3"
"senses": "[darkvision](/rules/senses.md#Darkvision) 60 ft., passive Perception 12"
"languages": "understands the languages you speak"
"traits":
  - "desc": "The Beast has a total number of d8 Hit Dice equal to your Ranger level.\
      \ It also gains all the normal benefits of rests."
    "name": "Hit Dice"
  - "desc": "If the Beast moves at least 20 ft. in a line, then hits with its Maul,\
      \ it deals bonus damage equal to your Quarry Die, and if the target is equal\
      \ to the Beast's size or smaller, the target is also knocked Prone."
    "name": "Charge"
  - "desc": "When your PB increases, the Beast's bonus to skill and saving throw proficiencies\
      \ increases as well."
    "name": "Primal Bond"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 +PB to hit, reach 5 ft., one target. *Hit:*\
      \ : (Quarry Die + PB) slashing damage"
    "name": "Maul"
"source":
  - "LLAR"
```
^statblock
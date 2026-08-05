---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/llwrc
- monster/cr/
- monster/size/tiny
- monster/type/dragon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Draconic Familiar"
---
# [Draconic Familiar](/bestiary/dragon/draconic-familiar-llwrc.md)
*Source: Alternate Warlock p. 8*  

```statblock
"name": "Draconic Familiar (LLWrc)"
"size": "Tiny"
"type": "dragon"
"alignment": "Any Evil alignment"
"ac_class": "13 + PB (natural armor)"
"modifier": !!int "3"
"stats":
  - !!int "3"
  - !!int "16"
  - !!int "12"
  - !!int "10"
  - !!int "8"
  - !!int "13"
"speed": "20 ft., fly 60 ft."
"damage_resistances": "Draconic Essence damage type"
"senses": "[blindsight](/rules/senses.md#Blindsight) 10ft, darkvision 60 ft., passive\
  \ Perception 13"
"languages": "Draconic, understands the languages spoken by its master."
"traits":
  - "desc": "The Familiar has a total number of d4 Hit Dice equal to your Warlock\
      \ level. It also gains all the normal benefits of both short and long rests."
    "name": "Hit Dice"
  - "desc": "When conjured, the Familiar's master chooses acid, cold, fire, poison,\
      \ or lightning to be the Familiar's Draconic Essence type. This affects its\
      \ Damage Resistances and Bite attack."
    "name": "Draconic Essence"
  - "desc": "When the Familiar is forced to make an ability check or saving throw,\
      \ it adds your PB to its roll."
    "name": "Eldritch Bond"
  - "desc": "The Familiar has advantage on Wisdom (Perception) checks that rely on\
      \ its sight or smell."
    "name": "Keen Senses"
  - "desc": "The Familiar has advantage on saving throws against spells and magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "*Melee Weapon Attack:* +Spell Attack modifier to hit, reach 5 ft., one\
      \ target. *Hit:* 1d4 + 3 + PB piercing damage, + 1d4 Draconic Essence damage.\
      \ On hit, the target must succeed on a Strength saving throw (DC equals 10 +\
      \ PB) or be [grappled](/rules/conditions.md#Grappled)."
    "name": "Bite"
"source":
  - "LLWrc"
```
^statblock
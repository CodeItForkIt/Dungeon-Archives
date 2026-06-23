---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/erlw
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid/shifter
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Shifter"
---
# [Shifter](/bestiary/humanoid/shifter-erlw.md)
*Source: Eberron: Rising from the Last War p. 319*  

Shifters are tied to primal spirits, which most of them refer to as the beast within. They are lithe of form and have bestial features: large eyes, flat noses, pointed ears, and light fur over much of their bodies. When a shifter fully embraces the beast within by "shifting," these features become even more pronounced.

```statblock
"name": "Shifter (ERLW)"
"size": "Medium"
"type": "humanoid"
"subtype": "shifter"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "[leather armor](/items/leather-armor-xphb.md)"
"hp": !!int "19"
"hit_dice": "3d8 + 6"
"modifier": !!int "3"
"stats":
  - !!int "12"
  - !!int "16"
  - !!int "14"
  - !!int "11"
  - !!int "15"
  - !!int "10"
"speed": "30 ft."
"skillsaves":
  - "name": "[Acrobatics](/rules/skills.md#Acrobatics)"
    "desc": "+5"
  - "name": "[Insight](/rules/skills.md#Insight)"
    "desc": "+4"
  - "name": "[Nature](/rules/skills.md#Nature)"
    "desc": "+2"
  - "name": "[Perception](/rules/skills.md#Perception)"
    "desc": "+4"
"gear":
  - "[shortsword](/items/shortsword-xphb.md)"
"senses": "[darkvision](/rules/senses.md#Darkvision) 60 ft., passive Perception 14"
"languages": "Common"
"cr": "1/2"
"traits":
  - "desc": "As a bonus action, the shifter takes on a more bestial form for 1 minute\
      \ or until it dies. The shifter gains 5 temporary hit points. It can make a\
      \ bite attack when it activates this trait and also as a bonus action on each\
      \ of its turns while in its bestial form."
    "name": "Shifting (Recharges after a Short or Long Rest)"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d6 + 3) piercing damage."
    "name": "Shortsword"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one creature. *Hit:*\
      \ 5 (1d4 + 3) piercing damage."
    "name": "Bite"
"source":
  - "ERLW"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ERLW/Shifter.webp"
```
^statblock
---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/tftyp
- monster/cr/2
- monster/size/large
- monster/type/ooze
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Reduced-Threat Ochre Jelly"
---
# [Reduced-Threat Ochre Jelly](/bestiary/ooze/reduced-threat-ochre-jelly-tftyp.md)
*Source: Tales from the Yawning Portal p. 113*  

```statblock
"name": "Reduced-Threat Ochre Jelly (TftYP)"
"size": "Large"
"type": "ooze"
"alignment": "Unaligned"
"ac": !!int "8"
"hp": !!int "22"
"hit_dice": "6d10 + 12"
"modifier": !!int "-2"
"stats":
  - !!int "15"
  - !!int "6"
  - !!int "14"
  - !!int "2"
  - !!int "6"
  - !!int "1"
"speed": "10 ft., climb 10 ft."
"damage_resistances": "acid"
"damage_immunities": "lightning, slashing"
"condition_immunities": "[blinded](/rules/conditions.md#Blinded), [charmed](/rules/conditions.md#Charmed),\
  \ [deafened](/rules/conditions.md#Deafened), [exhaustion](/rules/conditions.md#Exhaustion),\
  \ [frightened](/rules/conditions.md#Frightened), [prone](/rules/conditions.md#Prone)"
"senses": "[blindsight](/rules/senses.md#Blindsight) 60 ft. (blind beyond this radius),\
  \ passive Perception 8"
"languages": ""
"cr": "2"
"traits":
  - "desc": "A reduced-threat monster takes a −2 penalty on attack rolls (included\
      \ in the stat block), ability checks (included in the stat block for skill proficiencies),\
      \ saving throws (included in the stat block for saving throw proficiencies),\
      \ and saving throw DCs (included in the stat block)."
    "name": "Reduced Threat"
  - "desc": "The jelly can move through a space as narrow as 1 inch wide without squeezing."
    "name": "Amorphous"
  - "desc": "The jelly can climb difficult surfaces, including upside down on ceilings,\
      \ without needing to make an ability check."
    "name": "Spider Climb"
"actions":
  - "desc": "*Melee Weapon Attack:* +2 to hit, reach 5 ft., one target. *Hit:* 9\
      \ (2d6 + 2) bludgeoning damage plus 3 (1d6) acid damage."
    "name": "Pseudopod"
"reactions":
  - "desc": "When a jelly that is Medium or larger is subjected to lightning or slashing\
      \ damage, it splits into two new jellies if it has at least 10 hit points. Each\
      \ new jelly has hit points equal to half the original jelly's, rounded down.\
      \ New jellies are one size smaller than the original jelly."
    "name": "Split"
"source":
  - "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TftYP/Reduced-Threat%20Ochre%20Jelly.webp"
```
^statblock
---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/tftyp
- monster/cr/3
- monster/size/medium
- monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Torlin Silvershield"
---
# [Torlin Silvershield](/bestiary/npc/torlin-silvershield-tftyp.md)
*Source: Tales from the Yawning Portal p. 159*  

```statblock
"name": "Torlin Silvershield (TftYP)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "[studded leather](/items/studded-leather-armor-xphb.md)"
"hp": !!int "45"
"hit_dice": "6d8 + 18"
"modifier": !!int "2"
"stats":
  - !!int "15"
  - !!int "14"
  - !!int "16"
  - !!int "10"
  - !!int "13"
  - !!int "15"
"speed": "30 ft."
"skillsaves":
  - "name": "[Perception](/rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](/rules/skills.md#Stealth)"
    "desc": "+4"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/rules/conditions.md#Exhaustion), [poisoned](/rules/conditions.md#Poisoned)"
"gear":
  - "[longbow](/items/longbow-xphb.md)"
  - "[longsword](/items/longsword-xphb.md)"
"senses": "[darkvision](/rules/senses.md#Darkvision) 60 ft., passive Perception 13"
"languages": "the languages it knew in life"
"cr": "3"
"traits":
  - "desc": "While in sunlight, Torlin has disadvantage on attack rolls, as well as\
      \ on Wisdom ([Perception](/rules/skills.md#Perception)) checks that rely on\
      \ sight."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "Torlin makes two longsword attacks or two longbow attacks. It can use\
      \ its Life Drain in place of one longsword attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one creature. *Hit:*\
      \ 5 (1d6 + 2) necrotic damage. The target must succeed on a DC 13 Constitution\
      \ saving throw or its hit point maximum is reduced by an amount equal to the\
      \ damage taken. This reduction lasts until the target finishes a long rest.\
      \ The target dies if this effect reduces its hit point maximum to 0.\n\nA humanoid\
      \ slain by this attack rises 24 hours later as a [zombie](/bestiary/undead/zombie-xmm.md)\
      \ under Torlin's control, unless the humanoid is restored to life or its body\
      \ is destroyed. Torlin can have no more than twelve zombies under its control\
      \ at one time."
    "name": "Life Drain"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d8 + 2) slashing damage, or 7 (1d10 + 2) slashing damage if used with\
      \ two hands."
    "name": "Longsword"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, range 150/600 ft., one target. *Hit:*\
      \ 6 (1d8 + 2) piercing damage."
    "name": "Longbow"
"source":
  - "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TftYP/Torlin%20Silvershield.webp"
```
^statblock
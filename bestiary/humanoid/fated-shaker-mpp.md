---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/5
- monster/size/small-or-medium
- monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Fated Shaker"
---
# [Fated Shaker](/bestiary/humanoid/fated-shaker-mpp.md)
*Source: Morte's Planar Parade p. 56*  

Fated shakers are bullies who shake down those indebted to the faction's tax collectors and evictors. These enforcers use their magic to intimidate and subjugate those who try to stand up to them.

```statblock
"name": "Fated Shaker (MPP)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "16 with [mage armor](/spells/mage-armor-xphb.md)"
"hp": !!int "76"
"hit_dice": "17d8"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "16"
  - !!int "10"
  - !!int "15"
  - !!int "16"
  - !!int "15"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "5"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Insight](/rules/skills.md#Insight)"
    "desc": "+6"
  - "name": "[Investigation](/rules/skills.md#Investigation)"
    "desc": "+5"
  - "name": "[Perception](/rules/skills.md#Perception)"
    "desc": "+6"
"senses": "passive Perception 16"
"languages": "Common plus two more languages"
"cr": "5"
"actions":
  - "desc": "The shaker makes two Golden Rod or Radiant Bolt attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d6 + 3) bludgeoning damage plus 9 (2d8) radiant damage."
    "name": "Golden Rod"
  - "desc": "*Ranged Spell Attack:* +6 to hit, range 120 ft., one target. *Hit:*\
      \ 14 (2d10 + 3) radiant damage."
    "name": "Radiant Bolt"
  - "desc": "The shaker casts one of the following spells, requiring no material components\
      \ and using Wisdom as the spellcasting ability (spell save DC 14):\n\n**At will:**\
      \ [mage armor](/spells/mage-armor-xphb.md), [mage hand](/spells/mage-hand-xphb.md)\n\
      \n**1/day each:** [enlarge/reduce](/spells/enlarge-reduce-xphb.md), [fly](/spells/fly-xphb.md),\
      \ [suggestion](/spells/suggestion-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The shaker speaks magical words to order a creature it can see within\
      \ 30 feet of itself. The target must succeed on a DC 14 Wisdom saving throw\
      \ or be affected by one of the following effects (choose one or roll a d4):\n\
      \n- **1-2 Grovel.** The target takes 14 (4d6) psychic damage, drops whatever\
      \ it is holding, and has the [prone](/rules/conditions.md#Prone) condition.\
      \  \n- **3-4 Cower.** The target takes 10 (3d6) psychic damage and has the\
      \ [frightened](/rules/conditions.md#Frightened) condition until the end of its\
      \ next turn.  "
    "name": "Commanding Words"
"source":
  - "MPP"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Fated%20Shaker.webp"
```
^statblock
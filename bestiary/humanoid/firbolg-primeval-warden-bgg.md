---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/bgg
- monster/cr/4
- monster/size/medium
- monster/type/humanoid/druid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Firbolg Primeval Warden"
---
# [Firbolg Primeval Warden](/bestiary/humanoid/firbolg-primeval-warden-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 136*  

Like giant priests of Hiatea, firbolgs who serve her fall into two distinct roles that parallel Hiatea's dual nature. At home, primeval wardens tend the hearths and tutor the young. Primeval wardens who patrol the borders of firbolg communities are fierce hunters who guard against external threats and incursions.

## Firbolgs

Distant cousins of giants, the first firbolgs wandered the primeval forests of the multiverse, and the magic of those forests entwined itself with the firbolgs' souls. Ages later, that magic still thrums inside firbolgs.

Firbolgs are often drawn to the service or emulation of the gods Diancastra and Hiatea. Firbolgs' innate magic of obscurement and trickery resonates with Diancastra's wily resourcefulness. A traditional emphasis on community and harmony leads many firbolgs to pledge themselves to Hiatea's service.

```statblock
"name": "Firbolg Primeval Warden (BGG)"
"size": "Medium"
"type": "humanoid"
"subtype": "druid"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "[hide armor](/items/hide-armor-xphb.md), [shield](/items/shield-xphb.md)"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "14"
  - !!int "14"
  - !!int "12"
  - !!int "16"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "3"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "[Medicine](/rules/skills.md#Medicine)"
    "desc": "+5"
  - "name": "[Nature](/rules/skills.md#Nature)"
    "desc": "+3"
  - "name": "[Perception](/rules/skills.md#Perception)"
    "desc": "+7"
"gear":
  - "[spear](/items/spear-xphb.md)"
"senses": "passive Perception 17"
"languages": "Common, Druidic, Giant"
"cr": "4"
"actions":
  - "desc": "The firbolg makes two Spear or Fire Lance attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 6 (1d6 + 3) piercing damage plus 9 (2d8) fire\
      \ damage."
    "name": "Spear"
  - "desc": "*Ranged Spell Attack:* +5 to hit, range 120 ft., one target. *Hit:*\
      \ 14 (2d10 + 3) fire damage."
    "name": "Fire Lance"
  - "desc": "The firbolg casts one of the following spells, using Wisdom as the spellcasting\
      \ ability (spell save DC 13):\n\n**At will:** [entangle](/spells/entangle-xphb.md),\
      \ [speak with animals](/spells/speak-with-animals-xphb.md), [speak with plants](/spells/speak-with-plants-xphb.md)\n\
      \n**1/day each:** [commune with nature](/spells/commune-with-nature-xphb.md)\
      \ (as an action), [detect magic](/spells/detect-magic-xphb.md), [disguise self](/spells/disguise-self-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The firbolg magically turns [invisible](/rules/conditions.md#Invisible)\
      \ until the start of its next turn, until it makes an attack roll, or until\
      \ it forces someone to make a saving throw."
    "name": "Hidden Step (2/Day)"
"source":
  - "BGG"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BGG/Firbolg%20Primeval%20Warden.webp"
```
^statblock
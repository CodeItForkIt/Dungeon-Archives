---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/scc
- monster/cr/7
- monster/size/small-or-medium
- monster/type/humanoid/bard
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Silverquill Professor of Radiance"
---
# [Silverquill Professor of Radiance](/bestiary/humanoid/silverquill-professor-of-radiance-scc.md)
*Source: Strixhaven: A Curriculum of Chaos p. 215*  

Professors of radiance call up magic through spoken words and glyphs formed of magically shaped ink and light. The professors channel radiance to illuminate their allies, bolstering them with encouragement and inspiring any who witness their orations. Professors of radiance can turn their words into potent assets in battle or strike at their foes with searing radiance.

These Silverquill teachers seek to inspire greatness in all that they do, pushing their students to look for the good in all things and bring that into the light.

## Silverquill Scholars

The scholars of Silverquill College study the power of magic shaped through spoken and written words. They use that power either to illuminate and guide or to obscure and demoralize.

```statblock
"name": "Silverquill Professor of Radiance (SCC)"
"size": "Small or Medium"
"type": "humanoid"
"subtype": "bard"
"alignment": "Any alignment"
"ac": !!int "12"
"hp": !!int "97"
"hit_dice": "15d8 + 30"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "14"
  - !!int "14"
  - !!int "16"
  - !!int "13"
  - !!int "19"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "5"
  - "intelligence": !!int "6"
  - "wisdom": !!int "4"
  - "charisma": !!int "7"
"skillsaves":
  - "name": "[Arcana](/rules/skills.md#Arcana)"
    "desc": "+6"
  - "name": "[Deception](/rules/skills.md#Deception)"
    "desc": "+7"
  - "name": "[Performance](/rules/skills.md#Performance)"
    "desc": "+10"
  - "name": "[Persuasion](/rules/skills.md#Persuasion)"
    "desc": "+10"
"damage_resistances": "radiant"
"senses": "passive Perception 11"
"languages": "Common plus any four languages"
"cr": "7"
"actions":
  - "desc": "The professor makes two Radiant Strike attacks. The professor can replace\
      \ one of the attacks with a use of Spellcasting."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +7 to hit, reach 5 ft. or range 120\
      \ ft., one target. *Hit:* 17 (3d8 + 4) radiant damage. If the target is a\
      \ creature, it must succeed on a DC 15 Constitution saving throw be [blinded](/rules/conditions.md#Blinded)\
      \ until the end of its next turn."
    "name": "Radiant Strike"
  - "desc": "The professor casts one of the following spells, requiring no material\
      \ components and using Charisma as the spellcasting ability (spell save DC 15):\n\
      \n**At will:** [dancing lights](/spells/dancing-lights-xphb.md), [friends](/spells/friends-xphb.md)\n\
      \n**2/day each:** [bless](/spells/bless-xphb.md), [command](/spells/command-xphb.md),\
      \ [cure wounds](/spells/cure-wounds-xphb.md), [daylight](/spells/daylight-xphb.md),\
      \ [mage armor](/spells/mage-armor-xphb.md)\n\n**1/day each:** [hypnotic pattern](/spells/hypnotic-pattern-xphb.md),\
      \ [tongues](/spells/tongues-xphb.md)"
    "name": "Spellcasting"
"source":
  - "SCC"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/SCC/Silverquill%20Professor%20of%20Radiance.webp"
```
^statblock
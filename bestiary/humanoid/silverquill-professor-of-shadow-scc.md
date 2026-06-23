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
- "Silverquill Professor of Shadow"
---
# [Silverquill Professor of Shadow](/bestiary/humanoid/silverquill-professor-of-shadow-scc.md)
*Source: Strixhaven: A Curriculum of Chaos p. 215*  

Professors of shadow wield the linguistic magic of Silverquill College through slicing wit and debilitating inky shadow. Whether weaving their magic through spoken incantations and scathing insults or through shadows, these teachers break down the resolve of their foes.

The professors strive to carry themselves as immaculately as possible, seeking to overawe and wrong-foot anyone who would stand against them in debate or in battle. In teaching their students, professors of shadow focus on words that find the tiniest, most invisible cracks in an opponent's defenses and break them.

## Silverquill Scholars

The scholars of Silverquill College study the power of magic shaped through spoken and written words. They use that power either to illuminate and guide or to obscure and demoralize.

```statblock
"name": "Silverquill Professor of Shadow (SCC)"
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
    "desc": "+10"
  - "name": "[Persuasion](/rules/skills.md#Persuasion)"
    "desc": "+7"
  - "name": "[Stealth](/rules/skills.md#Stealth)"
    "desc": "+5"
"damage_resistances": "necrotic"
"senses": "[darkvision](/rules/senses.md#Darkvision) 300 ft., passive Perception 11"
"languages": "Common plus any four languages"
"cr": "7"
"traits":
  - "desc": "Magical darkness doesn't impede the professor's darkvision."
    "name": "Devil's Sight"
"actions":
  - "desc": "The professor makes two Ink Lance attacks. The professor can replace\
      \ one of the attacks with a use of Spellcasting."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +7 to hit, reach 5 ft. or range 120\
      \ ft., one target. *Hit:* 17 (3d8 + 4) necrotic damage. If the target is a\
      \ creature, it must succeed on a DC 15 Constitution saving throw be [blinded](/rules/conditions.md#Blinded)\
      \ until the end of its next turn."
    "name": "Ink Lance"
  - "desc": "The professor casts one of the following spells, requiring no material\
      \ components and using Charisma as the spellcasting ability (spell save DC 15):\n\
      \n**At will:** [dancing lights](/spells/dancing-lights-xphb.md), [friends](/spells/friends-xphb.md)\n\
      \n**2/day each:** [bane](/spells/bane-xphb.md), [command](/spells/command-xphb.md),\
      \ [darkness](/spells/darkness-xphb.md), [mage armor](/spells/mage-armor-xphb.md)\n\
      \n**1/day each:** [tongues](/spells/tongues-xphb.md)"
    "name": "Spellcasting"
"source":
  - "SCC"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/SCC/Silverquill%20Professor%20of%20Shadow.webp"
```
^statblock
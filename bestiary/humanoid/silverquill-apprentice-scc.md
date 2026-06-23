---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/scc
- monster/cr/2
- monster/size/small-or-medium
- monster/type/humanoid/bard
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Silverquill Apprentice"
---
# [Silverquill Apprentice](/bestiary/humanoid/silverquill-apprentice-scc.md)
*Source: Strixhaven: A Curriculum of Chaos p. 214*  

Stylish and driven, the students of Silverquill College—first as apprentices and then as pledgemages—cut imposing figures on campus. Dressed in smartly trimmed black-and-white uniforms, these budding mages practice bolstering speeches and wield inky blades.

Some Silverquill students prefer the benevolent side of language, using their words to uplift their friends and illuminate harsh truths about those in power. Others, though, choose to wield words more ruthlessly and master the art of insults and discouragement (and in some cases, petty trash talk). Regardless, nearly all members of Silverquill College carry themselves with a fearsome, never-second-place attitude—because in the art of wielding words, confidence is key.

## Silverquill Scholars

The scholars of Silverquill College study the power of magic shaped through spoken and written words. They use that power either to illuminate and guide or to obscure and demoralize.

```statblock
"name": "Silverquill Apprentice (SCC)"
"size": "Small or Medium"
"type": "humanoid"
"subtype": "bard"
"alignment": "Any alignment"
"ac": !!int "12"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "13"
  - !!int "12"
  - !!int "11"
  - !!int "15"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "4"
  - "charisma": !!int "4"
"skillsaves":
  - "name": "[Deception](/rules/skills.md#Deception)"
    "desc": "+4"
  - "name": "[Performance](/rules/skills.md#Performance)"
    "desc": "+6"
  - "name": "[Persuasion](/rules/skills.md#Persuasion)"
    "desc": "+6"
"senses": "passive Perception 10"
"languages": "Common plus any two languages"
"cr": "2"
"actions":
  - "desc": "*Melee  or Ranged Spell Attack:* +4 to hit, reach 5 ft. or range 60\
      \ ft., one target. *Hit:* 5 (1d6 + 2) piercing damage plus 9 (2d8) psychic\
      \ damage."
    "name": "Ink Blade"
  - "desc": "The apprentice casts one of the following spells, requiring no material\
      \ components and using Charisma as the spellcasting ability (spell save DC 12):\n\
      \n**At will:** [dancing lights](/spells/dancing-lights-xphb.md), [friends](/spells/friends-xphb.md)\n\
      \n**1/day each:** [command](/spells/command-xphb.md), [mage armor](/spells/mage-armor-xphb.md)"
    "name": "Spellcasting"
"reactions":
  - "desc": "When a creature the apprentice can see within 30 feet of it fails a saving\
      \ throw, the apprentice magically weaves together stirring prose, allowing the\
      \ creature to reroll the saving throw and use the higher result."
    "name": "Rousing Verse"
"source":
  - "SCC"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/SCC/Silverquill%20Apprentice.webp"
```
^statblock
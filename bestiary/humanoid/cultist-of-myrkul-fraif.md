---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/fraif
- monster/cr/11
- monster/environment/urban
- monster/size/small-or-medium
- monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Cultist of Myrkul"
---
# [Cultist of Myrkul](/bestiary/humanoid/cultist-of-myrkul-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 255*  

Cultists of Myrkul dominate the dead, whether to raise Undead servants, terrorize the living, or extract secrets known only to the deceased. Most are more interested in amassing knowledge than power or wealth. Many cultists of Myrkul are sinister manipulators who hoard necromantic lore and gather in cults to share their gruesome secrets. Such secrets often require unsavory experimentation, which these heartless cultists relish.

## Cultists

*Wicked Zealots of the Dead Three*

The adventurers Bane, Bhaal, and Myrkul seized divinity but were slain for their hubris. All three have been reborn and are now known as the Dead Three. Each of the Dead Three has inspired wicked cults that follow their paths of tyranny, murder, and necromancy.

More than any other gods, the Dead Three directly influence Faerûn—and particularly the city of Baldur's Gate—in malign ways. Cultists who receive orders from their patron god directly are often the most ambitious and most dangerous.

```statblock
"name": "Cultist of Myrkul (FRAiF)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Neutral Evil"
"ac": !!int "16"
"hp": !!int "204"
"hit_dice": "24d8 + 96"
"modifier": !!int "6"
"stats":
  - !!int "13"
  - !!int "14"
  - !!int "18"
  - !!int "20"
  - !!int "18"
  - !!int "15"
"speed": "30 ft."
"saves":
  - "constitution": !!int "8"
  - "intelligence": !!int "9"
  - "wisdom": !!int "8"
  - "charisma": !!int "6"
"skillsaves":
  - "name": "[Arcana](/rules/skills.md#Arcana)"
    "desc": "+9"
  - "name": "[Insight](/rules/skills.md#Insight)"
    "desc": "+8"
  - "name": "[Religion](/rules/skills.md#Religion)"
    "desc": "+9"
"damage_resistances": "necrotic"
"gear":
  - "[breastplate](/items/breastplate-xphb.md)"
  - "[holy symbol](/items/holy-symbol-xphb.md)"
"senses": "[Darkvision](/rules/senses.md#Darkvision) 60 ft., passive Perception 14"
"languages": "Common"
"cr": "11"
"traits":
  - "desc": "While Bloodied, the cultist has [Immunity](/rules/variant-rules/immunity-xphb.md)\
      \ to the [Frightened](/rules/conditions.md#Frightened) and [Poisoned](/rules/conditions.md#Poisoned)\
      \ conditions."
    "name": "Nearer to the Dead"
"actions":
  - "desc": "The cultist makes three Necrotic Burst attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +9, reach 5 ft. or range 120 ft. *Hit:*\
      \ 27 (5d10) Necrotic damage and the target can't regain [Hit Points](/rules/variant-rules/hit-points-xphb.md)\
      \ until the end of the cultist's next turn."
    "name": "Necrotic Burst"
  - "desc": "The cultist casts one of the following spells, using Intelligence as\
      \ the spellcasting ability (spell save DC 17):\n\n**At will:** [Speak with Dead](/spells/speak-with-dead-xphb.md),\
      \ [Thaumaturgy](/spells/thaumaturgy-xphb.md)\n\n**1/day each:** [Animate Dead](/spells/animate-dead-xphb.md),\
      \ [Circle of Death](/spells/circle-of-death-xphb.md)"
    "name": "Spellcasting"
"source":
  - "FRAiF"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/FRAiF/Cultist%20of%20Myrkul.webp"
```
^statblock

## Environment

urban
---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/bam
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/gith
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Githyanki Buccaneer"
---
# [Githyanki Buccaneer](/bestiary/humanoid/githyanki-buccaneer-bam.md)
*Source: Boo's Astral Menagerie p. 27*  

Githyanki buccaneers ply the Astral Plane for riches, which they haul back to their hidden fortresses in the Deep Astral. Many of them are warriors who lost the will to serve the Lich-Queen Vlaakith; they prefer to live by their own code or revel in their unbridled freedom.

```statblock
"name": "Githyanki Buccaneer (BAM)"
"size": "Medium"
"type": "humanoid"
"subtype": "gith"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "[breastplate](/items/breastplate-xphb.md)"
"hp": !!int "58"
"hit_dice": "9d8 + 18"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "14"
  - !!int "14"
  - !!int "16"
  - !!int "13"
  - !!int "13"
"speed": "30 ft."
"saves":
  - "constitution": !!int "4"
  - "intelligence": !!int "5"
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "[Athletics](/rules/skills.md#Athletics)"
    "desc": "+5"
  - "name": "[Deception](/rules/skills.md#Deception)"
    "desc": "+3"
  - "name": "[Perception](/rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Survival](/rules/skills.md#Survival)"
    "desc": "+3"
"gear":
  - "[greatsword](/items/greatsword-xphb.md)"
"senses": "passive Perception 13"
"languages": "Common, Gith"
"cr": "3"
"actions":
  - "desc": "The githyanki makes two Greatsword or Telekinetic Bolt attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (2d6 + 3) slashing damage plus 3 (1d6) psychic damage."
    "name": "Greatsword"
  - "desc": "*Ranged Spell Attack:* +5 to hit, range 60 ft., one target. *Hit:*\
      \ 13 (3d6 + 3) force damage."
    "name": "Telekinetic Bolt"
  - "desc": "The githyanki casts one of the following spells, requiring no spell components\
      \ and using Intelligence as the spellcasting ability (spell save DC 13):\n\n\
      **At will:** [light](/spells/light-xphb.md), [mage hand](/spells/mage-hand-xphb.md)\
      \ (the hand is invisible)\n\n**1/day each:** [plane shift](/spells/plane-shift-xphb.md),\
      \ [telekinesis](/spells/telekinesis-xphb.md)"
    "name": "Spellcasting (Psionics)"
"bonus_actions":
  - "desc": "The githyanki teleports, along with any equipment it is wearing or carrying,\
      \ up to 30 feet to an unoccupied space it can see."
    "name": "Astral Step (Recharge 4-6)"
"source":
  - "BAM"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BAM/Githyanki%20Buccaneer.webp"
```
^statblock
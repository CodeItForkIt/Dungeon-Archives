---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/efa
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/elf
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Vulkoori Venom Priest"
---
# [Vulkoori Venom Priest](/bestiary/humanoid/vulkoori-venom-priest-efa.md)
*Source: Eberron: Forge of the Artificer p. 98*  

Vulkoori venom priests delight in inflicting suffering through poison. Their weaponry and magic are carefully crafted to evoke the presence of the scorpion-god and strike terror into their enemies' hearts.

```statblock
"name": "Vulkoori Venom Priest (EFA)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Neutral Evil"
"ac": !!int "15"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"modifier": !!int "3"
"stats":
  - !!int "15"
  - !!int "16"
  - !!int "12"
  - !!int "10"
  - !!int "16"
  - !!int "13"
"speed": "30 ft."
"saves":
  - "constitution": !!int "3"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "[Perception](/rules/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Religion](/rules/skills.md#Religion)"
    "desc": "+2"
  - "name": "[Stealth](/rules/skills.md#Stealth)"
    "desc": "+5"
"damage_resistances": "poison"
"gear":
  - "[holy symbol](/items/holy-symbol-xphb.md)"
  - "[quarterstaff](/items/quarterstaff-xphb.md)"
  - "[studded leather armor](/items/studded-leather-armor-xphb.md)"
"senses": "[Darkvision](/rules/senses.md#Darkvision) 120 ft., passive Perception 15"
"languages": "Common, Elvish, Giant"
"cr": "2"
"traits":
  - "desc": "Magic can't put the priest to sleep."
    "name": "Fey Ancestry"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 9 (2d6 + 2) Bludgeoning\
      \ damage, and the target has the [Poisoned](/rules/conditions.md#Poisoned) condition\
      \ until the end of the priest's next turn."
    "name": "Venom Staff"
  - "desc": "The priest casts one of the following spells, using Wisdom as the spellcasting\
      \ ability (spell save DC 13, +5 to hit with spell attacks):\n\n**At will:**\
      \ [Dancing Lights](/spells/dancing-lights-xphb.md), [Ray of Sickness](/spells/ray-of-sickness-xphb.md),\
      \ [Thaumaturgy](/spells/thaumaturgy-xphb.md)\n\n**1/day each:** [Cure Wounds](/spells/cure-wounds-xphb.md),\
      \ [Hold Person](/spells/hold-person-xphb.md), [Protection from Poison](/spells/protection-from-poison-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Each creature with the [Poisoned](/rules/conditions.md#Poisoned) condition\
      \ within a 30-foot [Emanation](/rules/variant-rules/emanation-area-of-effect-xphb.md)\
      \ originating from the priest takes 3 (1d6) Poison damage."
    "name": "Intensify Poison"
"source":
  - "EFA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/EFA/Vulkoori%20Venom%20Priest.webp"
```
^statblock
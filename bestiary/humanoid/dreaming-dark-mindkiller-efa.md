---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/efa
- monster/cr/11
- monster/size/small-or-medium
- monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Dreaming Dark Mindkiller"
---
# [Dreaming Dark Mindkiller](/bestiary/humanoid/dreaming-dark-mindkiller-efa.md)
*Source: Eberron: Forge of the Artificer p. 60*  

Mindkillers are the assassins of the Dreaming Dark, sent to terrify their foes before striking to kill. Mindkillers force foes to attack their own allies, causing physical and emotional devastation to grow the power of the Dreaming Dark.

```statblock
"name": "Dreaming Dark Mindkiller (EFA)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Lawful Evil"
"ac": !!int "19"
"hp": !!int "180"
"hit_dice": "24d8 + 72"
"modifier": !!int "4"
"stats":
  - !!int "15"
  - !!int "19"
  - !!int "16"
  - !!int "21"
  - !!int "18"
  - !!int "17"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "8"
  - "intelligence": !!int "9"
  - "wisdom": !!int "8"
  - "charisma": !!int "7"
"skillsaves":
  - "name": "[Deception](/rules/skills.md#Deception)"
    "desc": "+7"
  - "name": "[Insight](/rules/skills.md#Insight)"
    "desc": "+8"
  - "name": "[Perception](/rules/skills.md#Perception)"
    "desc": "+8"
  - "name": "[Stealth](/rules/skills.md#Stealth)"
    "desc": "+8"
"damage_resistances": "psychic"
"condition_immunities": "[charmed](/rules/conditions.md#Charmed), [frightened](/rules/conditions.md#Frightened)"
"senses": "[Truesight](/rules/senses.md#Truesight) 30 ft., passive Perception 18"
"languages": "Common, Quori; telepathy 120 ft."
"cr": "11"
"actions":
  - "desc": "The mindkiller makes two Nightmare Whisper attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +9, reach 5 ft. or range 30 ft. *Hit:*\
      \ 27 (5d8 + 5) Psychic damage, and the target has the [Frightened](/rules/conditions.md#Frightened)\
      \ condition until the start of the mindkiller's next turn. If the target is\
      \ already [Frightened](/rules/conditions.md#Frightened), it instead takes an\
      \ extra 10 (3d6) Psychic damage."
    "name": "Nightmare Whisper"
  - "desc": "*Wisdom Saving Throw:* DC 17, each creature in a 30-foot-radius [Sphere](/rules/variant-rules/sphere-area-of-effect-xphb.md)\
      \ centered on a point the mindkiller can see within 120 feet. *Failure:* 35\
      \ (10d6) Psychic damage, and the target has the [Frightened](/rules/conditions.md#Frightened)\
      \ condition until the start of the mindkiller's next turn. While [Frightened](/rules/conditions.md#Frightened)\
      \ in this way, the target can do only one of the following on each of its turns:\
      \ move, take an action, or take a [Bonus Action](/rules/variant-rules/bonus-action-xphb.md).\
      \ *Success:* Half damage only."
    "name": "Primal Fear (1/Day)"
"bonus_actions":
  - "desc": "The mindkiller casts [Dominate Person](/spells/dominate-person-xphb.md),\
      \ requiring no spell components and using Intelligence as the spellcasting ability\
      \ (spell save DC 17).\n"
    "name": "Slayer's Puppet (1/Day)"
"source":
  - "EFA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/EFA/Dreaming%20Dark%20Mindkiller.webp"
```
^statblock
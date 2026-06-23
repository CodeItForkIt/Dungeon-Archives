---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/5
- monster/size/medium
- monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Cranium Rat Squeaker Swarm"
---
# [Cranium Rat Squeaker Swarm](/bestiary/aberration/cranium-rat-squeaker-swarm-mpp.md)
*Source: Morte's Planar Parade p. 22*  

The cranium rats squeakers of Sigil have no connection to the mind flayers that created their progenitors. Rather, these magical rodents cooperate with the residents of the City of Doors, whether by simply living together or by pursuing greater ambitions. When squeakers collect in large numbers, their swarms merge into a single intelligence with enhanced psionic abilities and the accumulated memories of its constituents.

```statblock
"name": "Cranium Rat Squeaker Swarm (MPP)"
"size": "Medium"
"type": "aberration"
"alignment": "typically  Neutral"
"ac": !!int "12"
"hp": !!int "76"
"hit_dice": "17d8"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "10"
  - !!int "15"
  - !!int "11"
  - !!int "14"
"speed": "30 ft."
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](/rules/conditions.md#Charmed), [frightened](/rules/conditions.md#Frightened),\
  \ [grappled](/rules/conditions.md#Grappled), [paralyzed](/rules/conditions.md#Paralyzed),\
  \ [petrified](/rules/conditions.md#Petrified), [prone](/rules/conditions.md#Prone),\
  \ [restrained](/rules/conditions.md#Restrained), [stunned](/rules/conditions.md#Stunned)"
"senses": "[darkvision](/rules/senses.md#Darkvision) 30 ft., passive Perception 10"
"languages": "telepathy 30 ft."
"cr": "5"
"traits":
  - "desc": "The swarm can use its [sending](/spells/sending-xphb.md) spell to target\
      \ someone familiar to a creature in telepathic contact with the swarm."
    "name": "Psychic Messenger"
  - "desc": "The swarm can occupy another creature's space and vice versa, and the\
      \ swarm can move through any opening large enough for a Tiny rat. The swarm\
      \ can't regain hit points or gain temporary hit points."
    "name": "Swarm"
  - "desc": "The swarm is immune to any effect that would sense its emotions or read\
      \ its thoughts, as well as to divination spells."
    "name": "Telepathic Shroud"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 0 ft., one target in the swarm's\
      \ space. *Hit:* 14 (4d6) piercing damage, or 7 (2d6) piercing damage if\
      \ the swarm has half of its hit points or fewer, plus 22 (5d8) psychic damage."
    "name": "Bites"
  - "desc": "The swarm casts one of the following spells, requiring no spell components\
      \ and using Intelligence as the spellcasting ability (spell save DC 13):\n\n\
      **At will:** [command](/spells/command-xphb.md) *, [detect thoughts](/spells/detect-thoughts-xphb.md)\
      \ *, [sending](/spells/sending-xphb.md) *\n\n**1/day each:** [confusion](/spells/confusion-xphb.md)\
      \ *, [dominate monster](/spells/dominate-monster-xphb.md) *\n\n*To cast this\
      \ spell, the swarm must have more than half its hit points remaining."
    "name": "Spellcasting (Psionics)"
"bonus_actions":
  - "desc": "The swarm sheds dim light from its brains in a 5-foot radius, increases\
      \ the illumination to bright light in a 5- to 20-foot radius and dim light for\
      \ an additional number of feet equal to the chosen radius, or extinguishes the\
      \ light."
    "name": "Illumination"
"source":
  - "MPP"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Cranium%20Rat%20Squeaker%20Swarm.webp"
```
^statblock
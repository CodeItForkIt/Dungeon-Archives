---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/rhw
- monster/cr/10
- monster/environment/grassland
- monster/environment/hill
- monster/environment/urban
- monster/size/medium
- monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Dullahan"
---
# [Dullahan](/bestiary/undead/dullahan-rhw.md)
*Source: RHW p. 244*  

*Vengeful Headless Hunter*

Headless, undying warriors, dullahans arise from decapitated villains and murderously seek to recover their missing heads. In their endless hunts, they terrorize sites relevant to their crimes or near where they died, beheading anyone they believe responsible (or connected to those responsible) for their deaths. Aside from their lethal blades, dullahans terrorize foes with their terrifying wails and by throwing the flame-wreathed skulls of past victims. Many pursue their victims astride undead or fiendish steeds.

```statblock
"name": "Dullahan (RHW)"
"size": "Medium"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"hp": !!int "127"
"hit_dice": "17d8 + 51"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "16"
  - !!int "11"
  - !!int "15"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "constitution": !!int "7"
"skillsaves":
  - "name": "[Perception](/rules/skills.md#Perception)"
    "desc": "+6"
"damage_resistances": "cold, necrotic, poison"
"condition_immunities": "[blinded](/rules/conditions.md#Blinded), [charmed](/rules/conditions.md#Charmed),\
  \ [deafened](/rules/conditions.md#Deafened), [frightened](/rules/conditions.md#Frightened),\
  \ [poisoned](/rules/conditions.md#Poisoned)"
"senses": "[Truesight](/rules/senses.md#Truesight) 120 ft., passive Perception 16"
"languages": "understands Common plus one other language but can't speak"
"cr": "10"
"traits":
  - "desc": "While mounted and without the [Incapacitated](/rules/conditions.md#Incapacitated)\
      \ condition, the dullahan and its mount have [Advantage](/rules/variant-rules/advantage-xphb.md)\
      \ on Dexterity saving throws, and the dullahan can force an attack targeted\
      \ at its mount to target the dullahan instead."
    "name": "Mounted Adept"
  - "desc": "The dullahan has [Advantage](/rules/variant-rules/advantage-xphb.md)\
      \ on attack rolls against targets that have the [Frightened](/rules/conditions.md#Frightened)\
      \ condition."
    "name": "Terrorizer"
"actions":
  - "desc": "The dullahan makes two attacks, using Beheading Blade or Fiery Skull\
      \ in any combination, and uses Headless Wail."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +8, reach 5 ft. *Hit:* 9 (1d10 + 4) Slashing\
      \ damage plus 11 (2d10) Necrotic damage. If the target is reduced to 0 [Hit\
      \ Points](/rules/variant-rules/hit-points-xphb.md) by this attack, it dies and\
      \ its head is lopped off. The head rises as a Death's Head in the space of the\
      \ target's corpse or in the nearest unoccupied space. The head is under the\
      \ dullahan's control. The dullahan can control no more than seven heads at a\
      \ time."
    "name": "Beheading Blade"
  - "desc": "*Ranged Attack Roll:* +7, range 120 ft. *Hit:* 18 (4d8) Fire damage."
    "name": "Fiery Skull"
  - "desc": "*Constitution Saving Throw:* DC 15, up to three creatures within 120\
      \ feet of the dullahan that aren't Constructs or Undead. *Failure:* 13 (2d12)\
      \ Psychic damage, and the target has the [Frightened](/rules/conditions.md#Frightened)\
      \ condition until the start of the dullahan's next turn. *Success:* Half damage\
      \ only."
    "name": "Headless Wail"
"source":
  - "RHW"
```
^statblock

## Environment

grassland, hill, urban
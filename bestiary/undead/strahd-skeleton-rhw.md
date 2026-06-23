---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/rhw
- monster/cr/4
- monster/environment/planar
- monster/environment/shadowfell
- monster/environment/underdark
- monster/environment/urban
- monster/size/medium
- monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Strahd Skeleton"
---
# [Strahd Skeleton](/bestiary/undead/strahd-skeleton-rhw.md)
*Source: RHW p. 269*  

*Skeletal Soldier of the First Vampire*

Vampires sometimes turn mortal servants unworthy of the gift of vampirism into skeletal soldiers. Known as Strahd skeletons—in recognition of the lord of Barovia who first created them—these silent, capable undead soldiers wield vampiric blades. Strahd skeletons that whet their blades in blood often carry their weapons back to their vampire lords. Tales disagree on whether vampires can feed from these bloody blades or merely revel in the sacrifice.

```statblock
"name": "Strahd Skeleton (RHW)"
"size": "Medium"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "16"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"modifier": !!int "1"
"stats":
  - !!int "17"
  - !!int "13"
  - !!int "15"
  - !!int "12"
  - !!int "15"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "strength": !!int "5"
"damage_vulnerabilities": "bludgeoning"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/rules/conditions.md#Exhaustion), [frightened](/rules/conditions.md#Frightened),\
  \ [poisoned](/rules/conditions.md#Poisoned)"
"gear":
  - "[longsword](/items/longsword-xphb.md)"
  - "[shield](/items/shield-xphb.md)"
"senses": "[Darkvision](/rules/senses.md#Darkvision) 60 ft., passive Perception 12"
"languages": "understands Common but can't speak"
"cr": "4"
"traits":
  - "desc": "If damage reduces the skeleton to 0 [Hit Points](/rules/variant-rules/hit-points-xphb.md),\
      \ it makes a Constitution saving throw (DC 5 plus the damage taken) unless the\
      \ damage is Radiant or from a [Critical Hit](/rules/variant-rules/critical-hit-xphb.md).\
      \ On a successful save, the skeleton drops to 1 [Hit Point](/rules/variant-rules/hit-points-xphb.md)\
      \ instead."
    "name": "Undead Fortitude"
"actions":
  - "desc": "The skeleton makes two Vampiric Longsword attacks. It can replace one\
      \ attack with a use of Shield Bash."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 7 (1d8 + 3) Slashing\
      \ damage plus 7 (2d6) Necrotic damage. The target's [Hit Point](/rules/variant-rules/hit-points-xphb.md)\
      \ maximum decreases by an amount equal to the Necrotic damage taken."
    "name": "Vampiric Longsword"
  - "desc": "*Strength Saving Throw:* DC 13, one creature within 5 feet that the skeleton\
      \ can see. *Failure:* 10 (2d6 + 3) Bludgeoning damage. If the target is a\
      \ Medium or smaller creature, it has the [Prone](/rules/conditions.md#Prone)\
      \ condition"
    "name": "Shield Bash"
"source":
  - "RHW"
```
^statblock

## Environment

planar, shadowfell, underdark, urban
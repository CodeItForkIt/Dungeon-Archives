---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/bmt
- monster/cr/4
- monster/size/medium
- monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Helmed Horror Detention Drone"
---
# [Helmed Horror Detention Drone](/bestiary/construct/helmed-horror-detention-drone-bmt.md)
*Source: The Book of Many Things p. 135*  

Detention drones vary in size, strength, and shape, though most are shaped like some kind of mechanical animal or plant.

```statblock
"name": "Helmed Horror Detention Drone (BMT)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "20"
"ac_class": "[plate armor](/items/plate-armor-xphb.md), [shield](/items/shield-xphb.md)"
"hp": !!int "60"
"hit_dice": "8d8 + 24"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "13"
  - !!int "16"
  - !!int "10"
  - !!int "10"
  - !!int "10"
"speed": "30 ft., fly 30 ft. (hover)"
"skillsaves":
  - "name": "[Perception](/rules/skills.md#Perception)"
    "desc": "+4"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks that\
  \ aren't adamantine"
"damage_immunities": "force, necrotic, poison"
"condition_immunities": "[blinded](/rules/conditions.md#Blinded), [charmed](/rules/conditions.md#Charmed),\
  \ [deafened](/rules/conditions.md#Deafened), [frightened](/rules/conditions.md#Frightened),\
  \ [paralyzed](/rules/conditions.md#Paralyzed), [petrified](/rules/conditions.md#Petrified),\
  \ [poisoned](/rules/conditions.md#Poisoned), [stunned](/rules/conditions.md#Stunned)"
"gear":
  - "[longsword](/items/longsword-xphb.md)"
"senses": "[blindsight](/rules/senses.md#Blindsight) 60 ft. (blind beyond this radius),\
  \ passive Perception 14"
"languages": "understands the languages of its creator but can't speak"
"cr": "4"
"traits":
  - "desc": "The drone has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "The drone is immune to three spells chosen by its creator. Typical immunities\
      \ include [fireball](/spells/fireball-xphb.md), [heat metal](/spells/heat-metal-xphb.md),\
      \ and [lightning bolt](/spells/lightning-bolt-xphb.md)."
    "name": "Spell Immunity"
"actions":
  - "desc": "The drone makes two longsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 8\
      \ (1d8 + 4) slashing damage, or 9 (1d10 + 4) slashing damage if used with\
      \ two hands."
    "name": "Longsword"
  - "desc": "The drone launches a tiny orb of magical force at a creature it can see\
      \ within 30 feet of itself. The creature must succeed on a DC 15 Constitution\
      \ saving throw or be encased in the orb, which expands to a size just large\
      \ enough to contain the creature. While encased, the creature doesn't need to\
      \ breathe, eat, or drink, and it doesn't age. Nothing can pass through the orb,\
      \ nor can any creature teleport or use planar travel to enter or exit the orb.\
      \ As a bonus action, the drone can move the orb and its contents up to 30 feet\
      \ in any direction. A successful casting of the [Dispel Magic](/spells/dispel-magic-xphb.md)\
      \ spell on the orb (DC 15) destroys it. The orb otherwise remains intact until\
      \ the drone spends an action to end the effect or the drone is destroyed. A\
      \ drone can have only one detention orb active at a time; if the drone creates\
      \ a detention orb when it already has one active, the first orb disappears,\
      \ freeing the creature inside."
    "name": "Detention Orb"
"source":
  - "BMT"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BMT/Helmed%20Horror%20Detention%20Drone.webp"
```
^statblock
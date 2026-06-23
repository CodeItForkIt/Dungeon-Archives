---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/mismv1
- monster/cr/8
- monster/size/large
- monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Scrapper"
---
# [Scrapper](/bestiary/construct/scrapper-mismv1.md)
*Source: Misplaced Monsters: Volume 1 p. 10*  

> [!note]
> Created by Jake F.

Scrappers are tall, broad-shouldered automatons usually found in scrap yards. Sparks erupt from the loose wires that protrude from their hulking frames. Their quasi-mechanical minds are shielded with lead, protecting them from psychic damage.

A scrapper feeds on scrap metal and uses its electrified wires to grapple and reel in foes. It zaps enemies it can't reach with an energy beam fired from an extended eye.

```statblock
"name": "Scrapper (MisMV1)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "126"
"hit_dice": "12d10 + 60"
"modifier": !!int "0"
"stats":
  - !!int "20"
  - !!int "10"
  - !!int "20"
  - !!int "3"
  - !!int "10"
  - !!int "1"
"speed": "30 ft."
"skillsaves":
  - "name": "[Perception](/rules/skills.md#Perception)"
    "desc": "+6"
"damage_resistances": "lightning"
"damage_immunities": "poison, psychic"
"condition_immunities": "[charmed](/rules/conditions.md#Charmed), [exhaustion](/rules/conditions.md#Exhaustion),\
  \ [frightened](/rules/conditions.md#Frightened), [paralyzed](/rules/conditions.md#Paralyzed),\
  \ [petrified](/rules/conditions.md#Petrified), [poisoned](/rules/conditions.md#Poisoned)"
"senses": "[darkvision](/rules/senses.md#Darkvision) 120 ft., passive Perception 16"
"languages": "understands the languages of its creator but can't speak"
"cr": "8"
"traits":
  - "desc": "A creature that hits the scrapper with a melee attack while within 5\
      \ feet of it takes 19 (3d12) lightning damage."
    "name": "Electrified Chassis"
"actions":
  - "desc": "The scrapper makes two Spike Punch attacks. It can replace one of those\
      \ with a Wires attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 14\
      \ (2d8 + 5) bludgeoning damage plus 5 (1d10) piercing damage."
    "name": "Spike Punch"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 20 ft., one Large or smaller\
      \ creature. *Hit:* The target has the [grappled](/rules/conditions.md#Grappled)\
      \ condition (escape DC 16) and must succeed on a DC 16 Strength saving throw\
      \ or be pulled into an unoccupied space within 5 feet of the scrapper and take\
      \ 19 (3d12) lightning damage. The scrapper can have only one creature [grappled](/rules/conditions.md#Grappled)\
      \ in this way at a time."
    "name": "Wires"
  - "desc": "The scrapper shoots a magical beam from its extended eye at one creature\
      \ it can see within 120 feet of itself. The target must make a DC 16 Dexterity\
      \ saving throw, taking 44 (8d10) force damage on a failed save, or half as\
      \ much damage on a successful one."
    "name": "Eye Beam (Recharge 5-6)"
"source":
  - "MisMV1"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MisMV1/Scrapper.webp"
```
^statblock
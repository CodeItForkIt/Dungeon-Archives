---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/rhw
- monster/cr/12
- monster/environment/urban
- monster/size/medium
- monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Mordenheim's Monster"
---
# [Mordenheim's Monster](/bestiary/construct/mordenheims-monster-rhw.md)
*Source: RHW p. 257*  

*Masterwork of Stolen Flesh*

The creations of Dr. Viktra Mordenheim, Darklord of Lamordia, defy reason and classification as mere flesh golems. As she seeks to re-create her masterpiece, the Unbreakable Heart, Mordenheim has refined the creation of beings that are much more than the sum of their rotting parts. Known as Mordenheim's monsters, these collections of body parts are reanimated into striking, mighty, thinking beings with wills of their own. While some might be convinced to serve their creator, others seek to recover some semblance of the lives they remember in fractured memories. Still others believe that they are something new and greater than what they were before and seek to create a new life—whether on their own or at the expense of communities that shun and fear them.

```statblock
"name": "Mordenheim's Monster (RHW)"
"size": "Medium"
"type": "construct"
"alignment": "Neutral"
"ac": !!int "18"
"hp": !!int "161"
"hit_dice": "19d8 + 76"
"modifier": !!int "7"
"stats":
  - !!int "22"
  - !!int "16"
  - !!int "19"
  - !!int "14"
  - !!int "10"
  - !!int "5"
"speed": "40 ft."
"saves":
  - "strength": !!int "10"
  - "dexterity": !!int "7"
"skillsaves":
  - "name": "[Acrobatics](/rules/skills.md#Acrobatics)"
    "desc": "+7"
  - "name": "[Athletics](/rules/skills.md#Athletics)"
    "desc": "+14"
"damage_resistances": "bludgeoning, piercing, slashing"
"damage_immunities": "lightning, poison"
"condition_immunities": "[charmed](/rules/conditions.md#Charmed), [exhaustion](/rules/conditions.md#Exhaustion),\
  \ [frightened](/rules/conditions.md#Frightened), [paralyzed](/rules/conditions.md#Paralyzed),\
  \ [petrified](/rules/conditions.md#Petrified), [poisoned](/rules/conditions.md#Poisoned)"
"senses": "[Darkvision](/rules/senses.md#Darkvision) 60 ft., passive Perception 10"
"languages": "Common plus one other language"
"cr": "12"
"traits":
  - "desc": "Whenever the monster is subjected to Lightning damage, it regains a number\
      \ of [Hit Points](/rules/variant-rules/hit-points-xphb.md) equal to the Lightning\
      \ damage dealt, and its [Speed](/rules/variant-rules/speed-xphb.md) increases\
      \ by 40 feet until the end of its next turn."
    "name": "Greater Lightning Absorption"
  - "desc": "The monster can't shape-shift."
    "name": "Immutable Form"
  - "desc": "The monster has [Advantage](/rules/variant-rules/advantage-xphb.md) on\
      \ saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The monster makes two Slam attacks and uses Crush or Throw."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +10, reach 5 ft. *Hit:* 13 (2d6 + 6) Bludgeoning\
      \ damage plus 7 (2d6) Lightning damage. If the target is a Medium or smaller\
      \ creature, it has the [Grappled](/rules/conditions.md#Grappled) condition (escape\
      \ DC 18) from one of two hands."
    "name": "Slam"
  - "desc": "*Strength Saving Throw:* DC 18, one creature [Grappled](/rules/conditions.md#Grappled)\
      \ by the monster. *Failure:* 13 (2d6 + 6) Bludgeoning damage plus 7 (2d6)\
      \ Lightning damage, and the target has the [Restrained](/rules/conditions.md#Restrained)\
      \ condition. While [Restrained](/rules/conditions.md#Restrained), the target\
      \ is suffocating."
    "name": "Crush"
  - "desc": "The monster throws a creature [Grappled](/rules/conditions.md#Grappled)\
      \ by it to a space it can see within 30 feet of itself that isn't in the air.\
      \ *Dexterity Saving Throw:* DC 18, the creature thrown and each creature in\
      \ the destination space. *Failure:* 13 (2d6 + 6) Bludgeoning damage, and the\
      \ target has the [Prone](/rules/conditions.md#Prone) condition. *Success:* Half\
      \ damage only."
    "name": "Throw"
"bonus_actions":
  - "desc": "The monster spends 10 feet of movement to jump to a space within 40 feet\
      \ that contains one or more Medium or smaller creatures. *Dexterity Saving Throw:*\
      \ DC 18, each creature in the monster's destination space. *Failure:* 14 (4d6)\
      \ Bludgeoning damage, and the target has the [Prone](/rules/conditions.md#Prone)\
      \ condition. *Failure or Success:* The target moves to the nearest unoccupied\
      \ space."
    "name": "Violent Leap"
"source":
  - "RHW"
```
^statblock

## Environment

urban
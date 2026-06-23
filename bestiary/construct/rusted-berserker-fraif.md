---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/fraif
- monster/cr/4
- monster/environment/coastal
- monster/environment/forest
- monster/size/medium
- monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Rusted Berserker"
---
# [Rusted Berserker](/bestiary/construct/rusted-berserker-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 273*  

A Rusted berserker is a human Norlander transformed by the Rusting. These berserkers have forsaken the traditional Norlander lifestyle to rage against nature and its protectors.

## Rusted

*Construct Victims of a Supernatural Curse*

The supernatural Rusting curse that pervades the Moonshae Isles manifests as a thin scrim of iron over a living creature's skin. This coarse iron rusts easily, turning the creature a sickly orange gray. Unchecked, this curse transforms the victim into a Rusted, an animated iron caricature of itself that sheds flakes of toxic rust.

As the Rusting curse hardens the skin, it also hollows out the mind. Rusted creatures despise unspoiled nature and are compelled to destroy it when they can.

> [!note] Other Rusted
> 
> You can turn any Beast, Fey, Giant, Humanoid, or Monstrosity into a Rusted version of itself by doing the following: change the creature's type to Construct, and give it Immunity to Poison damage and the [Exhaustion](/rules/conditions.md#Exhaustion), [Petrified](/rules/conditions.md#Petrified), and [Poisoned](/rules/conditions.md#Poisoned) conditions.
^other-rusted

```statblock
"name": "Rusted Berserker (FRAiF)"
"size": "Medium"
"type": "construct"
"alignment": "Neutral"
"ac": !!int "16"
"hp": !!int "82"
"hit_dice": "11d8 + 33"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "17"
  - !!int "6"
  - !!int "10"
  - !!int "6"
"speed": "30 ft."
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/rules/conditions.md#Exhaustion), [petrified](/rules/conditions.md#Petrified),\
  \ [poisoned](/rules/conditions.md#Poisoned)"
"gear":
  - "[greatsword](/items/greatsword-xphb.md)"
  - "six [javelins](/items/javelin-xphb.md)"
"senses": "passive Perception 10"
"languages": "Common"
"cr": "4"
"actions":
  - "desc": "The Rusted makes two attacks, using Greatsword or Javelin in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +6, reach 5 ft. *Hit:* 11 (2d6 + 4) Slashing\
      \ damage, and the target has the [Poisoned](/rules/conditions.md#Poisoned) condition\
      \ until the end of its next turn."
    "name": "Greatsword"
  - "desc": "*Melee  or Ranged Attack Roll:* +6, reach 5 ft. or range 30/120 ft.\
      \ *Hit:* 11 (2d6 + 4) Piercing damage, and the target has the [Poisoned](/rules/conditions.md#Poisoned)\
      \ condition until the end of its next turn."
    "name": "Javelin"
"source":
  - "FRAiF"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/FRAiF/Rusted%20Berserker.webp"
```
^statblock

## Environment

coastal, forest
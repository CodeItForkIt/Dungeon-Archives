---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/lfl
- monster/cr/7
- monster/environment/feywild
- monster/environment/planar
- monster/size/huge
- monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Incarnation of Transience"
---
# [Incarnation of Transience](/bestiary/fey/incarnation-of-transience-lfl.md)
*Source: Lorwyn: First Light*  

The incarnations of transience represent all that is fleeting or ephemeral. Despite their apparent bulk, these incarnations are actually ephemeral beings with only a spectral existence in material reality. Each incarnation resembles a saurian behemoth with an axolotl face, a many-frilled tail, and a hulking back covered in bright-orange pustules. In Lorwyn, transience incarnations embody the changing of seasons and the flowing of rivers. In Shadowmoor, these incarnations embody disease passing through its hosts, or the susurration of fallen leaves blowing through an empty village.

## Incarnations of Nature

Incarnations of nature embody abstract ideas such as curiosity, relief, or terror. Incarnations of nature are beyond the ken of most mortal beings—untamable, primal, and awe inspiring.

In the realm of Lorwyn-Shadowmoor, these beings take the forms of chimeric behemoths that combine the features of three or more creatures. In Lorwyn, incarnations of nature often embody positive, exhilarating emotions. In Shadowmoor, they often manifest dour, violent impulses.

An incarnation of nature that wanders from Lorwyn to Shadowmoor or vice versa retains its core identity but might transform physically. An incarnation of hope in Lorwyn, for example, might resemble a giant dove with a lizard's tail and leonine legs; in Shadowmoor, this same being might instead resemble a giant crow with a rattlesnake's tail, its leonine legs stained with blood.

```statblock
"name": "Incarnation of Transience (LFL)"
"size": "Huge"
"type": "fey"
"alignment": "Neutral"
"ac": !!int "16"
"hp": !!int "142"
"hit_dice": "15d12 + 45"
"modifier": !!int "8"
"stats":
  - !!int "21"
  - !!int "20"
  - !!int "17"
  - !!int "10"
  - !!int "14"
  - !!int "16"
"speed": "40 ft., swim 40 ft."
"saves":
  - "dexterity": !!int "8"
  - "constitution": !!int "6"
"condition_immunities": "[grappled](/rules/conditions.md#Grappled), [paralyzed](/rules/conditions.md#Paralyzed),\
  \ [petrified](/rules/conditions.md#Petrified), [prone](/rules/conditions.md#Prone),\
  \ [restrained](/rules/conditions.md#Restrained)"
"senses": "[Darkvision](/rules/senses.md#Darkvision) 60 ft., passive Perception 12"
"languages": "Sylvan; telepathy 120 ft."
"cr": "7"
"traits":
  - "desc": "The incarnation can move through other creatures and objects as if they\
      \ were [Difficult Terrain](/rules/variant-rules/difficult-terrain-xphb.md),\
      \ and its movement doesn't provoke Opportunity Attacks. It takes 5 (1d10)\
      \ Force damage if it ends its turn inside an object."
    "name": "Ephemeral Movement"
  - "desc": "The incarnation has [Advantage](/rules/variant-rules/advantage-xphb.md)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The incarnation makes three attacks, using Bite or Miasmic Globule in\
      \ any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +8, reach 5 ft. *Hit:* 14 (2d8 + 5) Piercing\
      \ damage."
    "name": "Bite"
  - "desc": "*Ranged Attack Roll:* +8, range 60/120 ft. *Hit:* 15 (6d4) Acid damage,\
      \ and the target's [Speed](/rules/variant-rules/speed-xphb.md) is reduced by\
      \ 10 feet until the end of the incarnation's next turn."
    "name": "Miasmic Globule"
  - "desc": "The incarnation moves up to 80 feet in a straight line. Each creature\
      \ whose space the incarnation enters is targeted once by the following effect.\
      \ *Dexterity Saving Throw:* DC 16. *Failure:* 18 (4d8) Force damage. If the\
      \ target is the incarnation's size or smaller, it has the [Prone](/rules/conditions.md#Prone)\
      \ condition. *Success:* Half damage only."
    "name": "Spectral Stampede"
"bonus_actions":
  - "desc": "The incarnation changes its size to Medium, Large, or Huge."
    "name": "Shape-Shift"
"source":
  - "LFL"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/LFL/Incarnation%20of%20Transience.webp"
```
^statblock

## Environment

planar, feywild
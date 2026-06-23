---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/bgdia
- monster/cr/5
- monster/size/small
- monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Hollyphant"
---
# [Hollyphant](/bestiary/celestial/hollyphant-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 237*  

Hollyphants are gentle, stalwart creatures native to the Upper Planes. Good-aligned deities and angels use them as messengers and helpers. Hollyphants treasure friendship and honesty.

A hollyphant looks like a miniature elephant with luminous gold fur and small, rapidly fluttering wings that not only hold it aloft but also propel it at great speed. Although kind, a hollyphant won't bear witness to an evil act without punishing the malefactor. Its pearlescent tusks are far from formidable, but it can unleash trumpet blasts from its trunk that can deafen creatures or engulf evildoers in radiant sparkles of positive energy. A hollyphant is also blessed with powerful innate magic to help it combat evil and protect its friends.

```statblock
"name": "Hollyphant (BGDIA)"
"size": "Small"
"type": "celestial"
"alignment": "Lawful Good"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "36"
"hit_dice": "8d6 + 8"
"modifier": !!int "0"
"stats":
  - !!int "10"
  - !!int "11"
  - !!int "12"
  - !!int "16"
  - !!int "19"
  - !!int "16"
"speed": "20 ft., fly 120 ft."
"saves":
  - "dexterity": !!int "3"
  - "constitution": !!int "4"
  - "charisma": !!int "6"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/rules/conditions.md#Poisoned)"
"senses": "passive Perception 14"
"languages": "Celestial, telepathy 120 ft."
"cr": "5"
"traits":
  - "desc": "The hollyphant's innate spellcasting ability is Wisdom (spell save DC\
      \ 15). It can innately cast the following spells, requiring no material components:\n\
      \n**At will:** [light](/spells/light-xphb.md)\n\n**2/day each:** [bless](/spells/bless-xphb.md),\
      \ [cure wounds](/spells/cure-wounds-xphb.md), [protection from evil and good](/spells/protection-from-evil-and-good-xphb.md)\n\
      \n**1/day each:** [banishment](/spells/banishment-xphb.md), [heal](/spells/heal-xphb.md),\
      \ [raise dead](/spells/raise-dead-xphb.md), [shapechange](/spells/shapechange-xphb.md)\
      \ (into a golden-furred [mammoth](/bestiary/beast/mammoth-xmm.md) with feathered\
      \ wings and a flying speed of 120 ft.), [teleport](/spells/teleport-xphb.md)\
      \ (with no chance of error)"
    "name": "Innate Spellcasting"
  - "desc": "An [invisible](/rules/conditions.md#Invisible) aura forms a 10-foot-radius\
      \ sphere around the hollyphant for as long as it lives. Any spell of 5th level\
      \ or lower cast from outside the barrier can't affect creatures or objects within\
      \ it, even if the spell is cast using a higher level spell slot. Such a spell\
      \ can target creatures and objects within the barrier, but the spell has no\
      \ effect on them. Similarly, the area within the barrier is excluded from the\
      \ areas affected by such spells. The hollyphant can use an action to suppress\
      \ this trait until its [concentration](/rules/conditions.md#Concentration) ends\
      \ (as if [concentrating](/rules/conditions.md#Concentration) on a spell)."
    "name": "Aura of Invulnerability"
  - "desc": "The hollyphant's weapon attacks are magical."
    "name": "Magic Weapons"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 3\
      \ (1d6) piercing damage."
    "name": "Tusks"
  - "desc": "The hollyphant blows air through its trunk, creating a trumpet sound\
      \ that can be heard out to a range of 600 feet. The trumpet also creates a 30-foot\
      \ cone of energy that has one of the following effects, chosen by the hollyphant:"
    "name": "Trumpet (3/Day)"
  - "desc": "Each creature in the cone must make a DC 14 Constitution saving throw.\
      \ On a failed save, a creature takes 17 (5d6) thunder damage and is [deafened](/rules/conditions.md#Deafened)\
      \ for 1 minute. On a successful save, a creature takes half as much damage and\
      \ isn't [deafened](/rules/conditions.md#Deafened). Nonmagical objects in the\
      \ cone that aren't being held or worn take 35 (10d6) thunder damage."
    "name": "Trumpet of Blasting"
  - "desc": "Creatures in the cone must make a DC 14 Constitution saving throw, taking\
      \ 22 (4d8 + 4) radiant damage on a failed save, or half as much damage on\
      \ a successful one. Evil creatures have disadvantage on the saving throw. Good\
      \ creatures in the cone take no damage."
    "name": "Trumpet of Sparkles"
"source":
  - "BGDIA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BGDIA/Hollyphant.webp"
```
^statblock
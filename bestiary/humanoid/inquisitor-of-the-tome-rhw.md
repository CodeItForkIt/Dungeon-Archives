---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/rhw
- monster/cr/8
- monster/environment/any
- monster/size/small-or-medium
- monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Inquisitor of the Tome"
---
# [Inquisitor of the Tome](/bestiary/humanoid/inquisitor-of-the-tome-rhw.md)
*Source: RHW p. 273*  

The Order of Tristian harnesses the powers that come from careful study and observation rather than innate magic or honed muscle. They use telekinetic force to alter the environment, entrap their enemies, and destroy evildoers. As the inquisition's scholars, they represent themselves with a tome.

## Ulmist Inquisitors

*Zealous Vanquishers of Evil Intent*

"Evil lurks everywhere. With our minds, we will unearth it, we will plumb its depths, and we will annihilate it." With those words, the psychically gifted priest Ulmed founded the Ulmist Inquisition, an order of psionic inquisitors that seeks to uncover and extinguish the wickedness lurking deep in people's hearts. From the depraved city of Malitain on the Material Plane, the inquisition sends its members throughout the multiverse seeking to thwart the work of malevolent cults, reality-defying horrors, and the evil inherent to mortals. Sects of the inquisition exist within the Domains of Dread, working either in hidden cabals or infiltrating other faiths, such as the Church of Ezra.

The Ulmist Inquisition is organized into three orders named for Ulmed's companions: the Order of Cosima, the Order of Ansel, and the Order of Tristian. Each order specializes in a different psionic power, and each bears a different symbol on its coat of arms. Some inquisitors entertain friendly rivalries with their fellows from other orders, but most put aside their grudges—at least temporarily—to work together against evil.

```statblock
"name": "Inquisitor of the Tome (RHW)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Lawful Neutral"
"ac": !!int "14"
"hp": !!int "88"
"hit_dice": "16d8 + 16"
"modifier": !!int "1"
"stats":
  - !!int "10"
  - !!int "12"
  - !!int "12"
  - !!int "19"
  - !!int "16"
  - !!int "15"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "7"
  - "wisdom": !!int "6"
  - "charisma": !!int "5"
"skillsaves":
  - "name": "[Arcana](/rules/skills.md#Arcana)"
    "desc": "+10"
  - "name": "[History](/rules/skills.md#History)"
    "desc": "+7"
  - "name": "[Nature](/rules/skills.md#Nature)"
    "desc": "+7"
  - "name": "[Religion](/rules/skills.md#Religion)"
    "desc": "+10"
"condition_immunities": "[charmed](/rules/conditions.md#Charmed), [frightened](/rules/conditions.md#Frightened)"
"gear":
  - "[longsword](/items/longsword-xphb.md)"
"senses": "[Truesight](/rules/senses.md#Truesight) 30 ft., passive Perception 13"
"languages": "Common plus two other languages"
"cr": "8"
"actions":
  - "desc": "The inquisitor makes three Force Blade attacks. It can replace one attack\
      \ with a use of Spellcasting to cast [Otiluke's Resilient Sphere](/spells/otilukes-resilient-sphere-xphb.md)\
      \ or [Telekinesis](/spells/telekinesis-xphb.md) if available."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +7, reach 5 ft. or range 120 ft. *Hit:*\
      \ 22 (4d8 + 4) Force damage. If the target is a Large or smaller creature,\
      \ it is pushed up to 10 feet straight away from the inquisitor."
    "name": "Force Blade"
  - "desc": "The inquisitor casts one of the following spells, requiring no spell\
      \ components and using Intelligence as the spellcasting ability (spell save\
      \ DC 15):\n\n**At will:** [Detect Magic](/spells/detect-magic-xphb.md), [Dispel\
      \ Magic](/spells/dispel-magic-xphb.md), [Mage Armor](/spells/mage-armor-xphb.md)\
      \ (included in AC), [Mage Hand](/spells/mage-hand-xphb.md) (the hand is Invisible),\
      \ [Sending](/spells/sending-xphb.md)\n\n**1/day each:** [Otiluke's Resilient\
      \ Sphere](/spells/otilukes-resilient-sphere-xphb.md), [Telekinesis](/spells/telekinesis-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "*Dexterity Saving Throw:* DC 15, each creature in a 20-foot-radius [Sphere](/rules/variant-rules/sphere-area-of-effect-xphb.md)\
      \ centered on a point the inquisitor can see within 120 feet. *Failure:* 27\
      \ (6d8) Force damage, and the target has the [Prone](/rules/conditions.md#Prone)\
      \ condition and is pulled up to 20 feet straight toward the [Sphere](/rules/variant-rules/sphere-area-of-effect-xphb.md)'s\
      \ center. *Success:* Half damage only."
    "name": "Implode (Recharge 4-6)"
"source":
  - "RHW"
```
^statblock

## Environment

any
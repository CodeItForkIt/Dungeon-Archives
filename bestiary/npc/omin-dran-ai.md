---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/ai
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/half-elf
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Omin Dran"
---
# [Omin Dran](/bestiary/npc/omin-dran-ai.md)
*Source: Acquisitions Incorporated p. 196*  

> [!quote]  
> 
> My duty, first and foremost, is to my shareholders. And I am the only shareholder.

Ominifis Hereward Dran spent his formative years in the small way-stop of Red Larch, where his mother, Prophetess, ran a popular inn and restaurant. In the brief periods of respite afforded by working the family business, Omin and his sisters, Auspicia and Portentia, were wont to wander the hills and trails around town, dreaming of adventure. But adventure of the wrong kind came calling for the trio one day, when an underground ruin they had often explored-actually a creature called the Wandering Crypt-took Auspicia from the world.

Omin Dran built the organization called Acquisitions Incorporated to facilitate and expand his quest to find his true sister, at least in part. For despite his unprecedented success in establishing the market for franchised adventuring across the Sword Coast and beyond, Omin's full measure eludes most people. He is known to be a worshiper of Tymora, ruthless in matters of business, feckless in matters of love, and hopeless in games of chance. Omin is also often accused of being one of the Masked Lords of Waterdeep, though this bit of fancy earns little more than a chuckle in response. And even if the rumor were true, Omin would never leverage such a position for greater financial gain and power. Because that would be wrong...

```statblock
"name": "Omin Dran (AI)"
"size": "Medium"
"type": "humanoid"
"subtype": "half-elf"
"alignment": "Lawful Neutral"
"ac": !!int "18"
"ac_class": "[plate armor](/items/plate-armor-xphb.md)"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"modifier": !!int "-1"
"stats":
  - !!int "16"
  - !!int "8"
  - !!int "14"
  - !!int "11"
  - !!int "18"
  - !!int "12"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "7"
  - "charisma": !!int "4"
"skillsaves":
  - "name": "[Deception](/rules/skills.md#Deception)"
    "desc": "+4"
  - "name": "[Insight](/rules/skills.md#Insight)"
    "desc": "+7"
  - "name": "[Intimidation](/rules/skills.md#Intimidation)"
    "desc": "+4"
  - "name": "[Medicine](/rules/skills.md#Medicine)"
    "desc": "+7"
  - "name": "[Perception](/rules/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Persuasion](/rules/skills.md#Persuasion)"
    "desc": "+4"
"gear":
  - "[maul](/items/maul-xphb.md)"
"senses": "[darkvision](/rules/senses.md#Darkvision) 60 ft., passive Perception 17"
"languages": "Common, Dwarvish, Elvish, Goblin"
"cr": "5"
"traits":
  - "desc": "Omin is a 9th-level spellcaster. His spellcasting ability is Wisdom (spell\
      \ save DC 15, +7 to hit with spell attacks). He has the following cleric spells\
      \ prepared:\n\n**Cantrips (at will):** [guidance](/spells/guidance-xphb.md),\
      \ [sacred flame](/spells/sacred-flame-xphb.md), [spare the dying](/spells/spare-the-dying-xphb.md),\
      \ [thaumaturgy](/spells/thaumaturgy-xphb.md)\n\n**1st level (4 slots):** [bless](/spells/bless-xphb.md),\
      \ [command](/spells/command-xphb.md), [divine favor](/spells/divine-favor-xphb.md),\
      \ [shield of faith](/spells/shield-of-faith-xphb.md)\n\n**2nd level (3 slots):**\
      \ [enhance ability](/spells/enhance-ability-xphb.md), [hold person](/spells/hold-person-xphb.md),\
      \ [magic weapon](/spells/magic-weapon-xphb.md), [silence](/spells/silence-xphb.md),\
      \ [spiritual weapon](/spells/spiritual-weapon-xphb.md)\n\n**3rd level (3 slots):**\
      \ [beacon of hope](/spells/beacon-of-hope-xphb.md), [crusader's mantle](/spells/crusaders-mantle-xphb.md),\
      \ [dispel magic](/spells/dispel-magic-xphb.md), [mass healing word](/spells/mass-healing-word-xphb.md),\
      \ [spirit guardians](/spells/spirit-guardians-xphb.md)\n\n**4th level (3 slots):**\
      \ [death ward](/spells/death-ward-xphb.md), [freedom of movement](/spells/freedom-of-movement-xphb.md),\
      \ [locate creature](/spells/locate-creature-xphb.md), [stoneskin](/spells/stoneskin-xphb.md)\n\
      \n**5th level (1 slots):** [dispel evil and good](/spells/dispel-evil-and-good-xphb.md),\
      \ [flame strike](/spells/flame-strike-xphb.md), [hold monster](/spells/hold-monster-xphb.md),\
      \ [greater restoration](/spells/greater-restoration-xphb.md), [legend lore](/spells/legend-lore-xphb.md)"
    "name": "Spellcasting"
  - "desc": "Once on each of his turns when he hits a creature with a weapon attack,\
      \ Omin can cause the attack to deal an extra 4 (1d8) damage of the same type\
      \ dealt by the weapon."
    "name": "Divine Strike"
  - "desc": "Omin has advantage on saving throws against being [charmed](/rules/conditions.md#Charmed),\
      \ and magic can't put him to sleep."
    "name": "Fey Ancestry"
"actions":
  - "desc": "Omin makes two attacks with his maul."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (2d6 + 3) bludgeoning damage."
    "name": "Maul"
"reactions":
  - "desc": "When a creature within 30 feet of Omin makes an attack roll, but before\
      \ learning whether it hits or misses, Omin can grant the creature a +10 bonus\
      \ to that roll."
    "name": "War God's Blessing (Recharges after a Short or Long Rest)"
"source":
  - "AI"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/AI/Omin%20Dran.webp"
```
^statblock
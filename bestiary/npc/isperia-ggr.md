---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/21
- monster/size/gargantuan
- monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Isperia"
---
# [Isperia](/bestiary/npc/isperia-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 227*  

Isperia is the current guildmaster of the Azorius Senate. As a sphinx, she is aloof and values solitude above all. However, she has been forced to give up her privacy to deal with the increased crime and chaos on Ravnica.

Isperia is devoted to her guild's belief that law is the ultimate bulwark against chaos, and it is her steady hand that guides the Azorius through these uncertain times. As guildmaster, Isperia serves as the supreme judge, a role that takes advantage of her encyclopedic knowledge of Ravnica's labyrinthine legal system.

If an encounter turns violent, Isperia refrains from using lethal force if possible, preferring to subdue a wrongdoing so that the legal system can mete out justice.

```statblock
"name": "Isperia (GGR)"
"size": "Gargantuan"
"type": "monstrosity"
"alignment": "Lawful Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "261"
"hit_dice": "18d20 + 72"
"modifier": !!int "2"
"stats":
  - !!int "20"
  - !!int "14"
  - !!int "18"
  - !!int "23"
  - !!int "26"
  - !!int "20"
"speed": "40 ft., fly 60 ft."
"saves":
  - "dexterity": !!int "9"
  - "constitution": !!int "11"
  - "intelligence": !!int "13"
  - "wisdom": !!int "15"
"skillsaves":
  - "name": "[Arcana](/rules/skills.md#Arcana)"
    "desc": "+13"
  - "name": "[History](/rules/skills.md#History)"
    "desc": "+13"
  - "name": "[Insight](/rules/skills.md#Insight)"
    "desc": "+15"
  - "name": "[Perception](/rules/skills.md#Perception)"
    "desc": "+15"
"damage_immunities": "psychic; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[charmed](/rules/conditions.md#Charmed), [frightened](/rules/conditions.md#Frightened)"
"senses": "[truesight](/rules/senses.md#Truesight) 120 ft., passive Perception 25"
"languages": "Common, Sphinx"
"cr": "21"
"traits":
  - "desc": "Isperia is a 15th-level Azorius spellcaster. Her spellcasting ability\
      \ is Wisdom (spell save DC 23, +14 to hit with spell attacks). Isperia has\
      \ the following cleric spells prepared:\n\n**Cantrips (at will):** [guidance](/spells/guidance-xphb.md),\
      \ [light](/spells/light-xphb.md), [resistance](/spells/resistance-xphb.md),\
      \ [sacred flame](/spells/sacred-flame-xphb.md), [thaumaturgy](/spells/thaumaturgy-xphb.md)\n\
      \n**1st level (4 slots):** [command](/spells/command-xphb.md), [detect evil\
      \ and good](/spells/detect-evil-and-good-xphb.md), [ensnaring strike](/spells/ensnaring-strike-xphb.md),\
      \ [sanctuary](/spells/sanctuary-xphb.md), [shield of faith](/spells/shield-of-faith-xphb.md)\n\
      \n**2nd level (3 slots):** [arcane lock](/spells/arcane-lock-xphb.md), [augury](/spells/augury-xphb.md),\
      \ [calm emotions](/spells/calm-emotions-xphb.md), [hold person](/spells/hold-person-xphb.md),\
      \ [silence](/spells/silence-xphb.md), [zone of truth](/spells/zone-of-truth-xphb.md)\n\
      \n**3rd level (3 slots):** [bestow curse](/spells/bestow-curse-xphb.md), [clairvoyance](/spells/clairvoyance-xphb.md),\
      \ [counterspell](/spells/counterspell-xphb.md), [dispel magic](/spells/dispel-magic-xphb.md),\
      \ [tongues](/spells/tongues-xphb.md)\n\n**4th level (3 slots):** [divination](/spells/divination-xphb.md),\
      \ [locate creature](/spells/locate-creature-xphb.md)\n\n**5th level (2 slots):**\
      \ [dispel evil and good](/spells/dispel-evil-and-good-xphb.md), [scrying](/spells/scrying-xphb.md)\n\
      \n**6th level (1 slots):** [word of recall](/spells/word-of-recall-xphb.md)\n\
      \n**7th level (1 slots):** [divine word](/spells/divine-word-xphb.md)\n\n**8th\
      \ level (1 slots):** [antimagic field](/spells/antimagic-field-xphb.md)"
    "name": "Spellcasting"
  - "desc": "Isperia's innate spellcasting ability is Wisdom (spell save DC 23). Isperia\
      \ can innately cast [imprisonment](/spells/imprisonment-xphb.md) twice per day,\
      \ requiring no material components.\n"
    "name": "Innate Spellcasting"
  - "desc": "Isperia is immune to any effect that would sense her emotions or read\
      \ her thoughts, as well as any divination spell that she refuses. Wisdom ([Insight](/rules/skills.md#Insight))\
      \ checks made to ascertain her intentions or sincerity have disadvantage."
    "name": "Inscrutable"
  - "desc": "If Isperia fails a saving throw, she can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Isperia has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Isperia makes two claw attacks. She can cast a spell with a casting time\
      \ of 1 action in place of one claw attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 5 ft., one target. *Hit:*\
      \ 21 (3d10 + 5) slashing damage. If the target is a creature, it must succeed\
      \ on a DC 23 Wisdom saving throw or take 14 (4d6) psychic damage after each\
      \ attack it makes against Isperia before the start of her next turn."
    "name": "Claw"
  - "desc": "Isperia chooses up to three creatures she can see within 90 feet of her.\
      \ Each target must succeed on a DC 23 Intelligence saving throw or Isperia chooses\
      \ an action for that target: [Attack](/rules/actions.md#Attack), [Cast a Spell](/rules/actions.md#Magic),\
      \ [Dash](/rules/actions.md#Dash), [Disengage](/rules/actions.md#Disengage),\
      \ [Dodge](/rules/actions.md#Dodge), [Help](/rules/actions.md#Help), [Hide](/rules/actions.md#Hide),\
      \ [Ready](/rules/actions.md#Ready), [Search](/rules/actions.md#Search), or [Use\
      \ an Object](/rules/actions.md#Utilize). The affected target can't take that\
      \ action for 1 minute. At the end of each of the target's turns, it can end\
      \ the effect on itself with a successful DC 23 Intelligence saving throw. A\
      \ target that succeeds on the saving throw becomes immune to Isperia's Supreme\
      \ Legal Authority for 24 hours."
    "name": "Supreme Legal Authority"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Isperia can expend a use to take one of the following actions. Isperia regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Isperia makes one claw attack."
    "name": "Claw Attack"
  - "desc": "Isperia casts a spell of 3rd level or lower from her list of prepared\
      \ spells, using a spell slot as normal."
    "name": "Cast a Spell (Costs 2 Actions)"
  - "desc": "Isperia uses Supreme Legal Authority."
    "name": "Supreme Legal Authority (Costs 3 Actions)"
"source":
  - "GGR"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Isperia.webp"
```
^statblock
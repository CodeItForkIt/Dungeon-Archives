---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/rhw
- monster/cr/17
- monster/size/medium
- monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ankhtepot"
---
# [Ankhtepot](/bestiary/npc/ankhtepot-rhw.md)
*Source: RHW p. 88*  

Ankhtepot has known treachery and conquest. He has known divinity and rule. But now he knows simply boredom and despair. He desires only to recover his lost ka, which he knows lies hidden in Har'Akir. With it, he hopes to become mortal again, die, and face his gods' judgment. Whether this means peace or oblivion matters not to him. Ankhtepot seeks only an end, and he and his followers will be a plague on Har'Akir until he finds it.

## Ankhtepot's Domain

Har'Akir is altered by Ankhtepot's presence, creating the following effects:

- **Blistering Sun.** Any outdoor area of Bright Light in Har'Akir is an area of extreme heat (see the Dungeon Master's Guide).  
- **Closing the Borders.** While in his domain, Ankhtepot can close or open the borders to Har'Akir at will. While the borders are closed, whirling sands fill the Mists surrounding Har'Akir. A creature that enters the Mists for the first time on a turn or starts its turn there takes `2d6` Slashing damage.  
- **Control Undead.** Undead of CR 5 or lower in Har'Akir have the Charmed condition and obey Ankhtepot's orders.  

If Ankhtepot dies, these effects end immediately.

```statblock
"name": "Ankhtepot (RHW)"
"size": "Medium"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "17"
"hp": !!int "202"
"hit_dice": "27d8 + 81"
"modifier": !!int "6"
"stats":
  - !!int "18"
  - !!int "10"
  - !!int "17"
  - !!int "15"
  - !!int "20"
  - !!int "16"
"speed": "30 ft., fly 30 ft. (hover)"
"saves":
  - "intelligence": !!int "8"
  - "wisdom": !!int "11"
"skillsaves":
  - "name": "[History](/rules/skills.md#History)"
    "desc": "+8"
  - "name": "[Perception](/rules/skills.md#Perception)"
    "desc": "+11"
  - "name": "[Religion](/rules/skills.md#Religion)"
    "desc": "+8"
"damage_vulnerabilities": "fire"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](/rules/conditions.md#Charmed), [exhaustion](/rules/conditions.md#Exhaustion),\
  \ [frightened](/rules/conditions.md#Frightened), [paralyzed](/rules/conditions.md#Paralyzed),\
  \ [poisoned](/rules/conditions.md#Poisoned)"
"senses": "[Truesight](/rules/senses.md#Truesight) 60 ft., passive Perception 21"
"languages": "Celestial, Common, Draconic"
"cr": "17"
"traits":
  - "desc": "If Ankhtepot dies, he revives with all his [Hit Points](/rules/variant-rules/hit-points-xphb.md)\
      \ in 1d10 weeks somewhere in Har'Akir."
    "name": "Darklord Restoration"
  - "desc": "If Ankhtepot fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day, or 4/Day in Domain)"
  - "desc": "Ankhtepot has [Advantage](/rules/variant-rules/advantage-xphb.md) on\
      \ saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Ankhtepot makes four Negative Energy Burst attacks. He can replace one\
      \ attack with a use of Spellcasting to cast [Power Word Stun](/spells/power-word-stun-xphb.md)."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +11, reach 5 ft. or range 60 ft. *Hit:*\
      \ 26 (6d6 + 5) Necrotic damage."
    "name": "Negative Energy Burst"
  - "desc": "Ankhtepot touches one creature within 5 feet. If the creature has 80\
      \ [Hit Points](/rules/variant-rules/hit-points-xphb.md) or fewer, it dies. Otherwise,\
      \ it takes 52 (8d12) Necrotic damage."
    "name": "Touch of Death (Recharge 6)"
  - "desc": "Ankhtepot casts one of the following spells, requiring no spell components\
      \ and using Wisdom as the spellcasting ability (spell save DC 19):\n\n**At will:**\
      \ [Dispel Magic](/spells/dispel-magic-xphb.md), [Divination](/spells/divination-xphb.md),\
      \ [Mage Hand](/spells/mage-hand-xphb.md) (hand is Invisible), [Power Word Stun](/spells/power-word-stun-xphb.md)\n\
      \n**1/day each:** [Animate Dead](/spells/animate-dead-xphb.md), [Sunburst](/spells/sunburst-xphb.md)"
    "name": "Spellcasting"
"regional_effects":
  - "desc": "Har'Akir is altered by Ankhtepot's presence, creating the following effects:\n\
      \n- **Blistering Sun.** Any outdoor area of [Bright Light](/rules/variant-rules/bright-light-xphb.md)\
      \ in Har'Akir is an area of [extreme heat](/traps-hazards/extreme-heat-xdmg.md)\
      \ (see the \"Dungeon Master's Guide\").  \n- **Closing the Borders.** While\
      \ in his domain, Ankhtepot can close or open the borders to Har'Akir at will.\
      \ While the borders are closed, whirling sands fill the Mists surrounding Har'Akir.\
      \ A creature that enters the Mists for the first time on a turn or starts its\
      \ turn there takes 2d6 Slashing damage.  \n- **Control Undead.** Undead of\
      \ CR 5 or lower in Har'Akir have the [Charmed](/rules/conditions.md#Charmed)\
      \ condition and obey Ankhtepot's orders.  \n\nIf Ankhtepot dies, these effects\
      \ end immediately."
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Ankhtepot can expend a use to take one of the following actions. Ankhtepot\
  \ regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Ankhtepot makes one Negative Energy Burst attack."
    "name": "Death Strike"
  - "desc": "*Strength Saving Throw:* DC 19, one Large or smaller creature Ankhtepot\
      \ can see within 60 feet. *Failure:* 14 (2d8 + 5) Force damage, and the target\
      \ is pushed or pulled up to 20 feet straight away or toward Ankhtepot. *Success:*\
      \ Half damage only. *Failure or Success:* Ankhtepot can't take this action again\
      \ until the start of his next turn."
    "name": "Hand of Fate"
  - "desc": "Ankhtepot teleports up to 60 feet to an unoccupied space he can see.\
      \ *Charisma Saving Throw:* DC 19, each creature in a 10-foot [Emanation](/rules/variant-rules/emanation-area-of-effect-xphb.md)\
      \ originating from Ankhtepot at his destination space. *Failure:* 11 (2d10)\
      \ Necrotic damage, and the target magically ages 10 years. *Success:* Half damage\
      \ only. *Failure or Success:* Ankhtepot can't take this action again until the\
      \ start of his next turn."
    "name": "Sands of Time"
"source":
  - "RHW"
```
^statblock
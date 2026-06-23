---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/tftyp
- monster/cr/13
- monster/size/medium
- monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Tarul Var"
---
# [Tarul Var](/bestiary/npc/tarul-var-tftyp.md)
*Source: Tales from the Yawning Portal p. 244*  

After failing in an earlier task for the Red Wizards, the lich Tarul Var is sequestered within the Doomvault (Dead in Thay), where he tries to avoid the attention of Szass Tam. Interlopers who discover his quarters are set upon by the lich and his dread warrior guards, but if Var is brought to the brink of death, he might bargain for a chance to escape the dungeon.

## Undead Nature

A lich doesn't require air, food, drink, or sleep.

```statblock
"name": "Tarul Var (TftYP)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "105"
"hit_dice": "14d8 + 42"
"modifier": !!int "3"
"stats":
  - !!int "11"
  - !!int "16"
  - !!int "16"
  - !!int "19"
  - !!int "14"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "constitution": !!int "8"
  - "intelligence": !!int "9"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "[Arcana](/rules/skills.md#Arcana)"
    "desc": "+9"
  - "name": "[History](/rules/skills.md#History)"
    "desc": "+9"
  - "name": "[Insight](/rules/skills.md#Insight)"
    "desc": "+7"
  - "name": "[Perception](/rules/skills.md#Perception)"
    "desc": "+7"
"damage_resistances": "cold; lightning; necrotic; bludgeoning, piercing, slashing\
  \ from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/rules/conditions.md#Charmed), [exhaustion](/rules/conditions.md#Exhaustion),\
  \ [frightened](/rules/conditions.md#Frightened), [paralyzed](/rules/conditions.md#Paralyzed),\
  \ [poisoned](/rules/conditions.md#Poisoned)"
"senses": "[darkvision](/rules/senses.md#Darkvision) 60 ft., passive Perception 17"
"languages": "Abyssal, Common, Infernal, Primordial, Thayan"
"cr": "13"
"traits":
  - "desc": "Var is a 12th-level spellcaster. His spellcasting ability is Intelligence\
      \ (spell save DC 17, +9 to hit with spell attacks). He has the following wizard\
      \ spells prepared:\n\n*Conjuration spell of 1st level or higher\n\n**Cantrips\
      \ (at will):** [fire bolt](/spells/fire-bolt-xphb.md), [mage hand](/spells/mage-hand-xphb.md),\
      \ [minor illusion](/spells/minor-illusion-xphb.md), [prestidigitation](/spells/prestidigitation-xphb.md),\
      \ [ray of frost](/spells/ray-of-frost-xphb.md)\n\n**1st level (4 slots):** [detect\
      \ magic](/spells/detect-magic-xphb.md), [magic missile](/spells/magic-missile-xphb.md),\
      \ [shield](/spells/shield-xphb.md), [unseen servant](/spells/unseen-servant-xphb.md)*\n\
      \n**2nd level (3 slots):** [detect thoughts](/spells/detect-thoughts-xphb.md),\
      \ [flaming sphere](/spells/flaming-sphere-xphb.md)*, [mirror image](/spells/mirror-image-xphb.md),\
      \ [scorching ray](/spells/scorching-ray-xphb.md)\n\n**3rd level (3 slots):**\
      \ [counterspell](/spells/counterspell-xphb.md), [dispel magic](/spells/dispel-magic-xphb.md),\
      \ [fireball](/spells/fireball-xphb.md)\n\n**4th level (3 slots):** [dimension\
      \ door](/spells/dimension-door-xphb.md)*, [Evard's black tentacles](/spells/evards-black-tentacles-xphb.md)*\n\
      \n**5th level (3 slots):** [cloudkill](/spells/cloudkill-xphb.md)*, [scrying](/spells/scrying-xphb.md)\n\
      \n**6th level (1 slots):** [circle of death](/spells/circle-of-death-xphb.md)"
    "name": "Spellcasting"
  - "desc": "While Var is [concentrating](/rules/conditions.md#Concentration) on a\
      \ conjuration spell, his [concentration](/rules/conditions.md#Concentration)\
      \ can't be broken as a result of taking damage."
    "name": "Focused Conjuration"
  - "desc": "If Var fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "If Var is destroyed but his phylactery remains intact, Var gains a new\
      \ body in 1d10 days, regaining all his hit points and becoming active again.\
      \ The new body appears within 5 feet of the phylactery."
    "name": "Rejuvenation"
  - "desc": "Var has advantage on saving throws against any effect that turns undead."
    "name": "Turn Resistance"
"actions":
  - "desc": "*Melee Spell Attack:* +9 to hit, reach 5 ft., one creature. *Hit:*\
      \ 10 (3d6) cold damage. The target must succeed on a DC 17 Constitution saving\
      \ throw or be [paralyzed](/rules/conditions.md#Paralyzed) for 1 minute. The\
      \ target can repeat the saving throw at the end of each of its turns, ending\
      \ the effect on itself on a success."
    "name": "Paralyzing Touch"
  - "desc": "Var teleports up to 30 feet to an unoccupied space he can see. Alternatively,\
      \ he can choose a space within range that is occupied by a Small or Medium creature.\
      \ If that creature is willing, both creatures teleport, swapping places. Var\
      \ can use this feature again only after he finishes a long rest or casts a conjuration\
      \ spell of 1st level or higher."
    "name": "Benign Transposition"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Tarul can expend a use to take one of the following actions. Tarul regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Var casts a cantrip."
    "name": "Cantrip"
  - "desc": "Var uses Paralyzing Touch."
    "name": "Paralyzing Touch (Costs 2 Actions)"
  - "desc": "Var fixes his gaze on one creature he can see within 10 feet of him.\
      \ The target must succeed on a DC 17 Wisdom saving throw against this magic\
      \ or become [frightened](/rules/conditions.md#Frightened) for 1 minute. The\
      \ [frightened](/rules/conditions.md#Frightened) target can repeat the saving\
      \ throw at the end of each of its turns, ending the effect on itself on a success.\
      \ If a target's saving throw is successful or the effect ends for it, the target\
      \ is immune to Var's gaze for the next 24 hours."
    "name": "Frightening Gaze (Costs 2 Actions)"
"source":
  - "TftYP"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TftYP/Tarul%20Var.webp"
```
^statblock
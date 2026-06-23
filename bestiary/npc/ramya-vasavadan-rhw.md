---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/rhw
- monster/cr/15
- monster/size/medium
- monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ramya Vasavadan"
---
# [Ramya Vasavadan](/bestiary/npc/ramya-vasavadan-rhw.md)
*Source: RHW p. 116*  

Ramya Vasavadan desperately fights to claim and hold power over Kalakeri in a brutal cycle of victory and loss with her equally uncompromising siblings. Unlike most Darklords, Ramya struggles to control her domain, leading her to seek allies in opposing her siblings and their treacherous allies.

In her true form, Ramya is an undead horror, but illusions mask her monstrous appearance. Her true nature is revealed by her chilled skin and her reflection, which always appears withered and terrifying.

Although Ramya's siblings, Arijani and Reeva, aren't Darklords of Kalakeri, they motivate the rebellions in Kalakeri and Ramya's torments. This monstrous pair is detailed in " Arijani and Reeva."

## Ramya's Domain

While Ramya is in control of the Sapphire Throne, Kalakeri is altered by Ramya's presence, creating the following effects:

- **Closing the Borders.** While in her domain, Ramya can close or open the borders to Kalakeri at will. While the borders are closed, the Mists surrounding Kalakeri sap the life of those within them. A creature that enters the Mists for the first time on a turn or starts its turn there and isn't a Construct or an Undead must succeed on a DC 20 Constitution saving throw or gain 1 Exhaustion level. A creature makes this save only once per turn.  
- **Everlasting Army.** A Medium or Small Humanoid slain in combat rises 24 hours later as a Wight under Ramya's control, unless the Humanoid is restored to life or its body is destroyed.  

If Ramya dies or her siblings control the Sapphire Throne, these effects end immediately.

```statblock
"name": "Ramya Vasavadan (RHW)"
"size": "Medium"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"hp": !!int "190"
"hit_dice": "20d8 + 100"
"modifier": !!int "15"
"stats":
  - !!int "14"
  - !!int "20"
  - !!int "20"
  - !!int "12"
  - !!int "16"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "strength": !!int "7"
  - "wisdom": !!int "8"
"skillsaves":
  - "name": "[Perception](/rules/skills.md#Perception)"
    "desc": "+8"
  - "name": "[Persuasion](/rules/skills.md#Persuasion)"
    "desc": "+9"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[exhaustion](/rules/conditions.md#Exhaustion), [frightened](/rules/conditions.md#Frightened),\
  \ [poisoned](/rules/conditions.md#Poisoned)"
"senses": "[Darkvision](/rules/senses.md#Darkvision) 120 ft., passive Perception 18"
"languages": "Abyssal, Common"
"cr": "15"
"traits":
  - "desc": "If Ramya dies, her body dissolves into mist, and she gains a new body\
      \ in 1d10 weeks, reviving with all her [Hit Points](/rules/variant-rules/hit-points-xphb.md)\
      \ somewhere in Kalakeri."
    "name": "Darklord Restoration"
  - "desc": "If Ramya fails a saving throw, she can choose to succeed instead."
    "name": "Legendary Resistance (3/Day, or 4/Day in Domain)"
  - "desc": "Ramya has [Advantage](/rules/variant-rules/advantage-xphb.md) on saving\
      \ throws against spells and other magical effects."
    "name": "Magic Resistance"
  - "desc": "Undead creatures of Ramya's choice (excluding herself) in a 60-foot [Emanation](/rules/variant-rules/emanation-area-of-effect-xphb.md)\
      \ originating from her have [Advantage](/rules/variant-rules/advantage-xphb.md)\
      \ on attack rolls and saving throws. She can't use this trait if she has the\
      \ [Incapacitated](/rules/conditions.md#Incapacitated) condition."
    "name": "Marshal Undead"
"actions":
  - "desc": "Ramya makes three Dread Blade attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +10, reach 5 ft. *Hit:* 12 (2d6 + 5) Slashing\
      \ damage plus 9 (2d8) Necrotic damage."
    "name": "Dread Blade"
  - "desc": "*Dexterity Saving Throw:* DC 17, each creature in a 20-foot-radius [Sphere](/rules/variant-rules/sphere-area-of-effect-xphb.md)\
      \ centered on a point Ramya can see within 120 feet. *Failure:* 28 (8d6) Fire\
      \ damage plus 28 (8d6) Necrotic damage. *Success:* Half damage."
    "name": "Vengeful Fire (Recharge 5-6)"
  - "desc": "Ramya casts one of the following spells, requiring no Material components\
      \ and using Charisma as the spellcasting ability (spell save DC 17):\n\n**At\
      \ will:** [Phantom Steed](/spells/phantom-steed-xphb.md)\n\n**1/day:** [Create\
      \ Undead](/spells/create-undead-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Ramya casts [Disguise Self](/spells/disguise-self-xphb.md) using the\
      \ same spellcasting ability as Spellcasting. The spell lasts until Ramya drops\
      \ to 80 [Hit Points](/rules/variant-rules/hit-points-xphb.md) or fewer or uses\
      \ her Vengeful Fire action. Intelligence ([Investigation](/rules/skills.md#Investigation))\
      \ checks to discern her true appearance are made with [Disadvantage](/rules/variant-rules/disadvantage-xphb.md).\n\
      \nWhen the disguise ends, each creature in a 30-foot [Emanation](/rules/variant-rules/emanation-area-of-effect-xphb.md)\
      \ originating from Ramya is subjected to the following effect. Wisdom [Saving\
      \ Throw](/rules/variant-rules/saving-throw-xphb.md): DC 17 (the target succeeds\
      \ automatically if it is a Construct or an Undead). Failure: The target has\
      \ the Frightened condition for 1 minute. While Frightened, the target has [Disadvantage](/rules/variant-rules/disadvantage-xphb.md)\
      \ on saving throws.\n"
    "name": "Illusory Disguise"
"reactions":
  - "desc": "Trigger: Ramya is hit by a melee attack roll while holding a weapon.\
      \ _Response:_ Ramya adds 5 to her AC against that attack, possibly causing it\
      \ to miss."
    "name": "Parry"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Ramya can expend a use to take one of the following actions. Ramya regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Ramya moves up to half her [Speed](/rules/variant-rules/speed-xphb.md)\
      \ and makes one Dread Blade attack."
    "name": "Lunge"
  - "desc": "*Constitution Saving Throw:* DC 17, one creature Ramya can see within\
      \ 120 feet. *Failure:* 21 (6d6) Psychic damage, and the target is cursed until\
      \ the end of its next turn. Until the curse ends, the target can't speak or\
      \ cast spells with a Verbal component. *Success:* Half damage only."
    "name": "Words of Silence"
  - "desc": "Ramya casts [Command](/spells/command-xphb.md), using the same spellcasting\
      \ ability as Spellcasting. Ramya can't take this action again until the start\
      \ of her next turn.\n"
    "name": "Dread Authority"
"source":
  - "RHW"
```
^statblock
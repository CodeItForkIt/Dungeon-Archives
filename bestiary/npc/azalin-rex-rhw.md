---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/rhw
- monster/cr/23
- monster/size/medium
- monster/type/undead/wizard
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Azalin Rex"
---
# [Azalin Rex](/bestiary/npc/azalin-rex-rhw.md)
*Source: RHW p. 62*  

In Darkon, Azalin was a tyrannical wizard-king obeyed by the living and the dead. When he first appeared before his people, he adopted an illusion of the form he possessed in life: that of a middle-aged human man with dark hair and a superior demeanor. However, his true form was that of a moldering lich, eyes ablaze with blasphemous energy.

Since arriving in the Domains of Dread, Azalin has been unable to learn new magic. For a wizard who forsook his mortality to pursue arcane studies, this was the ultimate frustration. Despite the limits on his studies, Azalin numbered among the few Darklords who understood the mysterious nature of the Domains of Dread. For generations, Azalin struggled to escape Darkon. His magical atrocities reshaped Darkon and the Domains of Dread time and again. However, these struggles gave Azalin only a glimpse of freedom, and his metaphysical violations inevitably reverted to the Dark Powers' original designs. Nevertheless, Azalin refused to stay a prisoner. His most recent plot culminated in the Hour of Ascension and the destruction of Castle Avernus. Since then, no one in Darkon has seen the Darklord, and his realm has begun deteriorating.

This stat block presents the Darklord as he was prior to his disappearance and how he would be should he return. Azalin's current spirit jar is a golden amulet he carries. If this amulet is destroyed, Azalin's original spirit jar—an immovable dragon skull in the ruins of Castle Avernus—reactivates, and the lich's spirit returns to Darkon if his body is destroyed.

## Azalin's Domain

Darkon is altered by Azalin's presence, creating the following effects:

- **Closing the Borders.** While in his domain, Azalin can close or open the borders to Darkon at will. While the borders are closed, undead terrors fill the Mists surrounding Darkon. Whenever a creature enters the Mists, one Hostile Zombie Clot (see chapter 5) appears in a random unoccupied space within 30 feet of that creature.  
- **Lord of the Dead.** While in his domain, Azalin can cast Clairvoyance, requiring no spell components and using the same spellcasting ability as his Spellcasting action. When Azalin casts this spell in this way, he can place the sensor in any Undead in Darkon with an Intelligence of 6 or less, even if it is beyond 1 mile of Azalin. In addition, Azalin can speak through the Undead he placed the sensor in.  
- **No Secrets.** Whenever a creature in Darkon casts a spell using a level 5+ spell slot, Azalin becomes aware of that creature's name and location. A Nondetection spell blocks this effect.  

If Azalin dies, these effects end immediately.

```statblock
"name": "Azalin Rex (RHW)"
"size": "Medium"
"type": "undead"
"subtype": "wizard"
"alignment": "Neutral Evil"
"ac": !!int "20"
"hp": !!int "390"
"hit_dice": "52d8 + 156"
"modifier": !!int "17"
"stats":
  - !!int "11"
  - !!int "16"
  - !!int "16"
  - !!int "21"
  - !!int "17"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "10"
  - "constitution": !!int "10"
  - "intelligence": !!int "12"
  - "wisdom": !!int "10"
"skillsaves":
  - "name": "[Arcana](/rules/skills.md#Arcana)"
    "desc": "+19"
  - "name": "[History](/rules/skills.md#History)"
    "desc": "+12"
  - "name": "[Insight](/rules/skills.md#Insight)"
    "desc": "+10"
  - "name": "[Perception](/rules/skills.md#Perception)"
    "desc": "+10"
"damage_resistances": "cold, lightning"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](/rules/conditions.md#Charmed), [exhaustion](/rules/conditions.md#Exhaustion),\
  \ [frightened](/rules/conditions.md#Frightened), [paralyzed](/rules/conditions.md#Paralyzed),\
  \ [poisoned](/rules/conditions.md#Poisoned)"
"senses": "[Truesight](/rules/senses.md#Truesight) 120 ft., passive Perception 20"
"languages": "all"
"cr": "23"
"traits":
  - "desc": "If Azalin dies and his spirit jar remains intact, he revives with all\
      \ his [Hit Points](/rules/variant-rules/hit-points-xphb.md) in 2d10 days in\
      \ the unoccupied space nearest his spirit jar. If Azalin's spirit jar is destroyed,\
      \ he instead revives in 4d10 days in Castle Avernus in Darkon."
    "name": "Darklord Restoration"
  - "desc": "If Azalin fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (4/Day, or 5/Day in Domain)"
"actions":
  - "desc": "Azalin makes three attacks, using Eldritch Burst or Paralyzing Touch\
      \ in any combination."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +12, reach 5 ft. or range 120 ft. *Hit:*\
      \ 31 (4d12 + 5) Force damage."
    "name": "Eldritch Burst"
  - "desc": "*Melee Attack Roll:* +12, reach 5 ft. *Hit:* 15 (3d6 + 5) Cold damage,\
      \ and the target has the [Paralyzed](/rules/conditions.md#Paralyzed) condition\
      \ until the start of Azalin's next turn."
    "name": "Paralyzing Touch"
  - "desc": "Azalin casts one of the following spells, requiring no spell components\
      \ and using Intelligence as the spellcasting ability (spell save DC 20):\n\n\
      **At will:** [Detect Magic](/spells/detect-magic-xphb.md), [Detect Thoughts](/spells/detect-thoughts-xphb.md),\
      \ [Dispel Magic](/spells/dispel-magic-xphb.md), [Invisibility](/spells/invisibility-xphb.md),\
      \ [Lightning Bolt](/spells/lightning-bolt-xphb.md) (level 5 version), [Mage\
      \ Hand](/spells/mage-hand-xphb.md), [Prestidigitation](/spells/prestidigitation-xphb.md)\n\
      \n**2/day each:** [Animate Dead](/spells/animate-dead-xphb.md), [Dimension Door](/spells/dimension-door-xphb.md),\
      \ [Modify Memory](/spells/modify-memory-xphb.md), [Plane Shift](/spells/plane-shift-xphb.md),\
      \ [Scrying](/spells/scrying-xphb.md)\n\n**1/day each:** [Chain Lightning](/spells/chain-lightning-xphb.md),\
      \ [Finger of Death](/spells/finger-of-death-xphb.md), [Power Word Kill](/spells/power-word-kill-xphb.md)"
    "name": "Spellcasting"
"reactions":
  - "desc": "Azalin casts [Counterspell](/spells/counterspell-xphb.md) in response\
      \ to the spell's trigger, using the same spellcasting ability as Spellcasting.\
      \ If the target creature fails its saving throw against this [Counterspell](/spells/counterspell-xphb.md),\
      \ Azalin steals knowledge of the triggering spell. For 1 hour or until Azalin\
      \ takes this [Reaction](/rules/variant-rules/reaction-xphb.md) again, Azalin\
      \ can cast that spell once, using the same spellcasting ability as Spellcasting.\n"
    "name": "Siphon Spell"
"regional_effects":
  - "desc": "Darkon is altered by Azalin's presence, creating the following effects:\n\
      \n- **Closing the Borders.** While in his domain, Azalin can close or open the\
      \ borders to Darkon at will. While the borders are closed, undead terrors fill\
      \ the Mists surrounding Darkon. Whenever a creature enters the Mists, one [Hostile](/rules/variant-rules/hostile-attitude-xphb.md)\
      \ [Zombie Clot](/bestiary/undead/zombie-clot-rhw.md) appears in a random unoccupied\
      \ space within 30 feet of that creature.  \n- **Lord of the Dead.** While in\
      \ his domain, Azalin can cast [Clairvoyance](/spells/clairvoyance-xphb.md),\
      \ requiring no spell components and using the same spellcasting ability as his\
      \ Spellcasting action. When Azalin casts this spell in this way, he can place\
      \ the sensor in any Undead in Darkon with an Intelligence of 6 or less, even\
      \ if it is beyond 1 mile of Azalin. In addition, Azalin can speak through the\
      \ Undead he placed the sensor in.  \n- **No Secrets.** Whenever a creature in\
      \ Darkon casts a spell using a level 5+ spell slot, Azalin becomes aware of\
      \ that creature's name and location. A [Nondetection](/spells/nondetection-xphb.md)\
      \ spell blocks this effect.  \n\nIf Azalin dies, these effects end immediately."
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Azalin can expend a use to take one of the following actions. Azalin regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Azalin teleports up to 60 feet to an unoccupied space he can see and\
      \ makes one Eldritch Burst or Paralyzing Touch attack."
    "name": "Eldritch Teleport"
  - "desc": "*Intelligence Saving Throw:* DC 20, up to three creatures Azalin can\
      \ see within 60 feet. *Failure:* 28 (8d6) Psychic damage, and the target has\
      \ the [Stunned](/rules/conditions.md#Stunned) condition until the end of Azalin's\
      \ next turn. *Success:* Half damage only. *Failure or Success:* Azalin can't\
      \ take this action again until the start of his next turn."
    "name": "Forbidden Knowledge"
"source":
  - "RHW"
```
^statblock
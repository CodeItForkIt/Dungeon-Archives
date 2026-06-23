---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/lfl
- monster/cr/4
- monster/environment/feywild
- monster/environment/planar
- monster/size/medium
- monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Merrow Doublespeaker"
---
# [Merrow Doublespeaker](/bestiary/monstrosity/merrow-doublespeaker-lfl.md)
*Source: Lorwyn: First Light*  

Most Shadowmoor merrow are Merrow Doublespeakers, seeking to trick those not wise to their nature. These merrows' tail spines are dangerous; doublespeakers can use them to stab or throw at foes.

## Merrow

Merrow are primarily water-dwelling people who exploit the realm of Lorwyn-Shadowmoor's land-dwelling species. They resemble large fish with humanoid torsos and arms, though their forms vary widely. Merrow are often capable warriors, but most prefer to duel with cutting words before resorting to physical violence.

```statblock
"name": "Merrow Doublespeaker (LFL)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Lawful Evil"
"ac": !!int "14"
"hp": !!int "67"
"hit_dice": "9d8 + 27"
"modifier": !!int "3"
"stats":
  - !!int "18"
  - !!int "17"
  - !!int "16"
  - !!int "12"
  - !!int "13"
  - !!int "16"
"speed": "20 ft., swim 40 ft."
"saves":
  - "dexterity": !!int "5"
  - "charisma": !!int "5"
"skillsaves":
  - "name": "[Deception](/rules/skills.md#Deception)"
    "desc": "+5"
  - "name": "[Stealth](/rules/skills.md#Stealth)"
    "desc": "+5"
"senses": "[Darkvision](/rules/senses.md#Darkvision) 120 ft., passive Perception 11"
"languages": "Common, Primordial (Aquan)"
"cr": "4"
"traits":
  - "desc": "The merrow can breathe air and water."
    "name": "Amphibious"
  - "desc": "The merrow can mimic voices and animal sounds. A creature that hears\
      \ the mimicries can tell they are imitations with a successful DC 15 Wisdom\
      \ ([Insight](/rules/skills.md#Insight)) check."
    "name": "Mimicry"
"actions":
  - "desc": "The merrow makes three Spined Tail attacks. It can replace one of these\
      \ attacks with a use of Spellcasting to cast [Command](/spells/command-xphb.md)."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +6, reach 5 ft. or range 20/60 ft.\
      \ *Hit:* 14 (3d6 + 4) Piercing damage."
    "name": "Spined Tail"
  - "desc": "The merrow casts one of the following spells, requiring no Material components\
      \ and using Charisma as the spellcasting ability (spell save DC 13):\n\n**At\
      \ will:** [Command](/spells/command-xphb.md), [Mage Hand](/spells/mage-hand-xphb.md),\
      \ [Minor Illusion](/spells/minor-illusion-xphb.md)"
    "name": "Spellcasting"
"source":
  - "LFL"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/LFL/Merrow%20Doublespeaker.webp"
```
^statblock

## Environment

planar, feywild
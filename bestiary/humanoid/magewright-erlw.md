---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/erlw
- monster/cr/0
- monster/size/medium
- monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Magewright"
---
# [Magewright](/bestiary/humanoid/magewright-erlw.md)
*Source: Eberron: Rising from the Last War p. 318*  

In Khorvaire, magic is part of everyday life. A chef might use [prestidigitation](/spells/prestidigitation-xphb.md) to heat and season food, while a blacksmith uses [mending](/spells/mending-xphb.md) to perform minor repairs and [guidance](/spells/guidance-xphb.md) to help inspire their work. Those who work minor magic into their labors are called magewrights.

Far more limited in magical power than a typical spellcaster, a magewright is dedicated to learning a handful of spells, and magewrights cast their non-cantrip spells as rituals—even spells that can't normally be cast in this way. Most magewright rituals take 10 minutes to perform, but certain complex rituals can take up to 1 hour. However long the ritual takes, it requires extra material components, usually in the form of dragonshards.

## Creating a Magewright

The magewright stat block provides the baseline statistics for a magewright. You then add to that baseline by choosing a specialty from the Magewright Specialties table, or roll for one. The specialty determines additional spells the magewright knows, including ones that can be cast only as rituals. The specialty also gives the magewright more proficiencies.

**Magewright Specialties**

| dice: d8 | Specialty | Spells | Proficiencies |
|----------|-----------|--------|---------------|
| 1 | Artisan | [Guidance](/spells/guidance-xphb.md), [mending](/spells/mending-xphb.md) | One type of artisan's tools |
| 2 | Entertainer | [Minor illusion](/spells/minor-illusion-xphb.md), [thaumaturgy](/spells/thaumaturgy-xphb.md). Ritual only: [disguise self](/spells/disguise-self-xphb.md). | [Performance](/rules/skills.md#Performance) (+3) |
| 3 | Healer | [Resistance](/spells/resistance-xphb.md), [spare the dying](/spells/spare-the-dying-xphb.md). Ritual only: [detect poison and disease](/spells/detect-poison-and-disease-xphb.md), [lesser restoration](/spells/lesser-restoration-xphb.md) (1 hour). | [Medicine](/rules/skills.md#Medicine) (+4), [herbalism kit](/items/herbalism-kit-xphb.md) |
| 4 | Lamplighter | [Light](/spells/light-xphb.md). Ritual only: [continual flame](/spells/continual-flame-xphb.md) (1 hour). | [Tinker's tools](/items/tinkers-tools-xphb.md) |
| 5 | Locksmith | [Mending](/spells/mending-xphb.md). Ritual only: [arcane lock](/spells/arcane-lock-xphb.md) (1 hour), [knock](/spells/knock-xphb.md). | [Thieves' tools](/items/thieves-tools-xphb.md), [tinker's tools](/items/tinkers-tools-xphb.md) |
| 6 | Mediator | [Guidance](/spells/guidance-xphb.md). Ritual only: [comprehend languages](/spells/comprehend-languages-xphb.md), [zone of truth](/spells/zone-of-truth-xphb.md). | [Insight](/rules/skills.md#Insight) (+4), [Persuasion](/rules/skills.md#Persuasion) (+3) |
| 7 | Medium | [Minor illusion](/spells/minor-illusion-xphb.md). Ritual only: [speak with dead](/spells/speak-with-dead-xphb.md). | [Deception](/rules/skills.md#Deception) (+3), [Religion](/rules/skills.md#Religion) (+4) |
| 8 | Oracle | [Guidance](/spells/guidance-xphb.md). Ritual only: [augury](/spells/augury-xphb.md), [divination](/spells/divination-xphb.md) (1 hour). | [History](/rules/skills.md#History) (+4), [Religion](/rules/skills.md#Religion) (+4) |
^magewright-specialties

```statblock
"name": "Magewright (ERLW)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "11"
"hp": !!int "9"
"hit_dice": "2d8"
"modifier": !!int "1"
"stats":
  - !!int "11"
  - !!int "13"
  - !!int "10"
  - !!int "14"
  - !!int "14"
  - !!int "12"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](/rules/skills.md#Arcana)"
    "desc": "+4"
"gear":
  - "[dagger](/items/dagger-xphb.md)"
"senses": "passive Perception 12"
"languages": "Common plus any two languages"
"cr": "0"
"traits":
  - "desc": "The magewright's spellcasting ability is Intelligence (spell save DC\
      \ 12). To cast one of its rituals, the magewright must provide additional material\
      \ components whose value in gold pieces is 20 times the spell's level. These\
      \ components are consumed when the ritual is finished. The magewright knows\
      \ the following spells:\n\n**At will:** [mage hand](/spells/mage-hand-xphb.md),\
      \ [prestidigitation](/spells/prestidigitation-xphb.md)\n\n**Rituals:** [knock](/spells/knock-xphb.md)"
    "name": "Spellcasting"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +3 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 3 (1d4 + 1) piercing damage."
    "name": "Dagger"
"source":
  - "ERLW"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ERLW/Magewright.webp"
```
^statblock
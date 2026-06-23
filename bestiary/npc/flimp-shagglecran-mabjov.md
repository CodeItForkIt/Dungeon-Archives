---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/9
- monster/size/small
- monster/type/humanoid/gnome
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Flimp Shagglecran"
---
# [Flimp Shagglecran](/bestiary/npc/flimp-shagglecran-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 32*  

Flimpius Theodore Shagglecran (known to his friends as Flimp) is a gnome artificer who hails from the island nation of Lantan. Flimp has an appearance unlike any other gnome on Faerûn. Dressed in plate armor with hooks and pouches for keeping his many inventions, Flimp is always accompanied by his ornery, but entirely mechanical, dog named Metallison.

Flimp spent his youth as many gnomes in Lantan do—studying with hopes to one day join the Gnomish Academy of Engineering. While he easily qualified to study at the Academy, Flimp quickly found that such a life was too boring for his tastes. To the consternation of his family and teachers, Flimp set off on a merchant ship headed north to the fabled city of Waterdeep. Halfway into the voyage, his ship was struck by misfortune and swamped during a powerful storm. Flimp found himself shipwrecked on a strange land with only a few other survivors with him. This turned out to be a blessing in disguise, for it was how he met his great friend and ally, the Waterdhavian scholar Doc Watson.

Together the two of them were able to rebuild and modify the wrecked ship which they named the Kraken's Folly. The name was inspired by the ship's most unique addition, a magical steering wheel (stolen from the lair of a kraken) that allows the ship to sail between worlds. After convincing Doc Watson to give up academic life, the two new friends used the ship to launch an adventuring career. This career turned out to be so lucrative, that eventually they founded a joint venture they named "The Adventurer's Guild".

## Flimp as a Contact

Flimp is the primary contact for members of the Adventurer's Guild at low levels. Flimp can use his planar ship, the Kraken's Folly, to take adventurers to many exotic locations.

**Flimp's Planar Ship Transportation Costs**

| Location | Required Level | Cost |
|----------|----------------|------|
| Waterdeep | 1 | 10 gp per passenger |
| Baldur's Gate | 1 | 10 gp per passenger |
| Neverwinter | 1 | 10 gp per passenger |
| Athkatla | 1 | 10 gp per passenger |
| Lantan | 5 | 25 gp per passenger |
| Ust Natha | 5 | 50 gp per passenger |
| Icewind Dale | 5 | 50 gp per passenger |
| Port Nyanzaru | 5 | 25 gp per passenger |
| Abyss | 10 | 500 gp per passenger |
| Avernus | 10 | 500 gp per passenger |
| Githyanki City | 10 | 400 gp per passenger |
| City Of Greyhawk | 10 | 250 gp per passenger |
^flimps-planar-ship-transportation-costs

```statblock
"name": "Flimp Shagglecran (MaBJoV)"
"size": "Small"
"type": "humanoid"
"subtype": "gnome"
"alignment": "Lawful Neutral"
"ac": !!int "21"
"ac_class": "[+2 plate](/items/2-armor-xdmg.md), [cloak of protection](/items/cloak-of-protection-xdmg.md)"
"hp": !!int "137"
"hit_dice": "25d6 + 50"
"modifier": !!int "0"
"stats":
  - !!int "14"
  - !!int "10"
  - !!int "14"
  - !!int "18"
  - !!int "12"
  - !!int "11"
"speed": "25 ft., fly 25 ft., swim 60 ft."
"saves":
  - "constitution": !!int "6"
  - "intelligence": !!int "8"
"skillsaves":
  - "name": "[Arcana](/rules/skills.md#Arcana)"
    "desc": "+8"
  - "name": "[History](/rules/skills.md#History)"
    "desc": "+8"
  - "name": "[Medicine](/rules/skills.md#Medicine)"
    "desc": "+5"
"senses": "[darkvision](/rules/senses.md#Darkvision) 60 ft., passive Perception 11"
"languages": "Common, Dwarvish, Giant, Gnomish"
"cr": "9"
"traits":
  - "desc": "Flimp uses his Intelligence modifier for attack and damage rolls with\
      \ his weapons."
    "name": "Battle Smith"
  - "desc": "Flimp has advantage on all Intelligence, Wisdom, and Charisma Saving\
      \ Throws against magic."
    "name": "Gnome Cunning"
  - "desc": "Flimp wears a [cloak of the manta ray](/items/cloak-of-the-manta-ray-xdmg.md),\
      \ a [cloak of protection](/items/cloak-of-protection-xdmg.md), [+2 plate armor](/items/2-armor-xdmg.md),\
      \ and [winged boots](/items/winged-boots-xdmg.md). Flimp wields a [+2 warhammer](/items/2-weapon-xdmg.md).\
      \ These items vanish 4 days after Flimp dies."
    "name": "Special Equipment"
"actions":
  - "desc": "Flimp makes two Magic Warhammer attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one target. *Hit:*\
      \ 10 (1d8 + 6) bludgeoning damage plus 3 (1d6) force damage."
    "name": "Magic Warhammer"
  - "desc": "Flimp hurls a vial of acid at a location within 60 feet. Every creature\
      \ within 10 feet of the target location must succeed on a DC 16 Dexterity saving\
      \ throw or take 21 (6d6) acid damage."
    "name": "Hurl Acid (Recharge 6)"
  - "desc": "Flimp summons a [metallic panther](/bestiary/construct/steel-defender-efa.md)\
      \ to aid him in combat. The panther has 24 hit points and is immune to poison\
      \ damage and the poison and [charmed](/rules/conditions.md#Charmed) conditions."
    "name": "Summon Steel Defender (1/Day)"
  - "desc": "Flimp casts one of the following spells using Intelligence as his spellcasting\
      \ ability (spell save DC 16):\n\n**At will:** [guidance](/spells/guidance-xphb.md),\
      \ [light](/spells/light-xphb.md)\n\n**2/day each:** [aid](/spells/aid-xphb.md),\
      \ [blur](/spells/blur-xphb.md), [cure wounds](/spells/cure-wounds-xphb.md),\
      \ [shield](/spells/shield-xphb.md)\n\n**1/day each:** [blink](/spells/blink-xphb.md),\
      \ [elemental weapon](/spells/elemental-weapon-xphb.md), [fire shield](/spells/fire-shield-xphb.md)"
    "name": "Spellcasting"
"reactions":
  - "desc": "When Flimp or another creature he can see within 30 feet of him makes\
      \ an ability check or a saving throw, Flimp can use his reaction to add +4 to\
      \ the roll."
    "name": "Flash of Genius"
"source":
  - "MaBJoV"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Flimp%20Shagglecran.webp"
```
^statblock
---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/9
- monster/size/large
- monster/type/giant/ogre
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Darien"
---
# [Darien](/bestiary/npc/darien-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 112*  

Typically appearing as a beautiful, young elven woman clad in golden jewelry, Darien is usually accompanied by several scantily clad and equally beautiful "bodyguards", all of whom seem to be comfortable in any climate, no matter how cold. However, in reality Darien is a powerful half-ogre illusionist and the golden jewelry aren't simply valuable trinkets, but the soul circlets of skeleton warriors—the magically disguised bodyguards that accompany her. Worst of all, Darien is driven by a disturbing obsession for those who call themselves adventurers.

Born to a human mother who died at birth, Darien was rescued by an elven adventurer from Evereska named Vail. Vail tried to keep Darien's nature a secret from the elves of Evereska, knowing that they would never accept a half-ogre. When Darien was in her teens, Vail taught her illusion magic which she could use to change her appearance and create an entirely different identity. Darien modeled her looks and behavior off an elven girl named Shirri—a young elven princess that Darien idolized to the point of obsession. But Darien lacked the grace and refinement of a true elf and despite looking the part, she was never accepted by the elven youth of Evereska.

One spring, when Vail was away on a campaign, Darien kidnapped Shirri. She kept her a prisoner for weeks, obsessively studying her in order to learn how to mimic her poise and speech. She both loved and hated Shirri, and her moods would constantly shift between fawning adoration and bitter resentment. She would often shower her prisoner with gifts, like rich cakes and beautiful clothes, but even the smallest, seemingly insignificant thing could trigger a sudden bout of rage, causing Darien to lock Shirri for days in the cellar, naked, cold, and starving.

When Vail returned, he was horrified to discover what Darien had done and cast her out of Evereska. Banished, Darien wandered the Greycloak Hills that protect Evereska, hoping to die in the snows of an early winter. Instead, she was found by a force of Elemental Evil: Cryonax, Prince of Ice. A pact was made, and Darien survived the winter to make her way down into the civilized lands of the Sword Coast.

Darien's natural talent with illusion magic, coupled with the power that Cryonax provided, allowed her to thrive. In her travels, she became obsessed with the men and women that called themselves adventurers. These bands of treasure hunting thrill seekers seemed to exist outside of the normal order of the world. They did what they liked and became rich and powerful doing so. They also reminded her of the one man who had ever showed her love—Vail.

Darien is parasitic in nature. The smallest word or act—or even seeing them across a crowded room—will cause her to become obsessed with an individual. From that point on she will use all her powers to insert herself into their life, typically by hiring her victim for a high-paying adventuring job. If her machinations fail, however, she is not averse to resorting to brute force such as enchantment magic or taking loved ones as hostages to compel compliance.

Ultimately, she wants the targets of her obsessive infatuation to come to love and respect her. If she is not shown the love that she craves, then she will lash out. Often this means that she will wait for an opportune time to "rescue" them from a battle not going their way. These adventurers might wake to find themselves hostages of Darien, where they must endure her erratic emotional outbursts and cruel mind games until they either escape, are rescued, or are driven into total madness.

```statblock
"name": "Darien (MaBJoV)"
"size": "Large"
"type": "giant"
"subtype": "ogre"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/spells/mage-armor-xphb.md)"
"hp": !!int "161"
"hit_dice": "19d10 + 57"
"modifier": !!int "2"
"stats":
  - !!int "20"
  - !!int "14"
  - !!int "16"
  - !!int "10"
  - !!int "11"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "4"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[Arcana](/rules/skills.md#Arcana)"
    "desc": "+8"
  - "name": "[Deception](/rules/skills.md#Deception)"
    "desc": "+8"
  - "name": "[Persuasion](/rules/skills.md#Persuasion)"
    "desc": "+8"
"damage_resistances": "psychic"
"damage_immunities": "cold"
"gear":
  - "[war pick](/items/war-pick-xphb.md)"
"senses": "[darkvision](/rules/senses.md#Darkvision) 120 ft., passive Perception 10"
"languages": "Aquan, Auran, Common, Elvish, Giant, telepathy 30 ft."
"cr": "9"
"traits":
  - "desc": "Darien can see normally in darkness, both magical and nonmagical, to\
      \ a distance of 120 feet"
    "name": "Devil's Sight"
  - "desc": "Darien has advantage on Constitution saving throws that she makes to\
      \ maintain [concentration](/rules/conditions.md#Concentration) on a spell."
    "name": "Eldritch Mind"
"actions":
  - "desc": "Darien makes two War Pick attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 5 ft, one target. *Hit:* 10\
      \ (1d8 + 6) piercing damage plus 4 necrotic damage."
    "name": "War Pick"
  - "desc": "*Ranged Spell Attack:* +8 to hit, range 300 ft., three targets. *Hit:*\
      \ 9 (1d10 + 4) force damage."
    "name": "Eldritch Blast"
  - "desc": "Darien touches an [incapacitated](/rules/conditions.md#Incapacitated)\
      \ Humanoid. That creature is then [charmed](/rules/conditions.md#Charmed) by\
      \ her until a [remove curse](/spells/remove-curse-xphb.md) spell is cast on\
      \ it, the [charmed](/rules/conditions.md#Charmed) condition is removed from\
      \ it, or she uses this feature again. Darien can communicate telepathically\
      \ with the [charmed](/rules/conditions.md#Charmed) creature as long as the two\
      \ of them are on the same plane of existence."
    "name": "Create Thrall"
  - "desc": "Darien creates a magical war pick in her empty hand. The war pick counts\
      \ as magical for the purpose of overcoming resistance and immunity to nonmagical\
      \ attacks and damage. The war pick has a +1 bonus to attack and damage (already\
      \ factored into Darien's attacks)."
    "name": "Summon War Pick"
  - "desc": "Darien casts one of the following spells, requiring no material component\
      \ and using Charisma as the spellcasting ability (spell save DC 16, +8 to\
      \ hit with spell attacks):\n\n**At will:** [alter self](/spells/alter-self-xphb.md),\
      \ [blade ward](/spells/blade-ward-xphb.md), [chill touch](/spells/chill-touch-xphb.md),\
      \ [disguise self](/spells/disguise-self-xphb.md), [false life](/spells/false-life-xphb.md),\
      \ [invisibility](/spells/invisibility-xphb.md), [mage armor](/spells/mage-armor-xphb.md)\
      \ (self only), [silent image](/spells/silent-image-xphb.md)\n\n**2/day each:**\
      \ [armor of Agathys](/spells/armor-of-agathys-xphb.md), [cone of cold](/spells/cone-of-cold-xphb.md),\
      \ [darkness](/spells/darkness-xphb.md), [fear](/spells/fear-xphb.md), [hallucinatory\
      \ terrain](/spells/hallucinatory-terrain-xphb.md), [hold person](/spells/hold-person-xphb.md),\
      \ [hypnotic pattern](/spells/hypnotic-pattern-xphb.md), [major image](/spells/major-image-xphb.md),\
      \ [mirror image](/spells/mirror-image-xphb.md), [mislead](/spells/mislead-xphb.md),\
      \ [sleet storm](/spells/sleet-storm-xphb.md)\n\n**1/day each:** [dream](/spells/dream-xphb.md),\
      \ [feeblemind](/spells/befuddlement-xphb.md), [mass suggestion](/spells/mass-suggestion-xphb.md),\
      \ [project image](/spells/project-image-xphb.md)"
    "name": "Innate Spellcasting"
"reactions":
  - "desc": "When Darien takes damage, she can entomb herself in ice, which melts\
      \ away at the end of her next turn. She gains 150 temporary hit points, which\
      \ take as much of the triggering damage as possible. Immediately after she takes\
      \ the damage, she gains vulnerability to fire damage, her speed is reduced to\
      \ 0, and she is [incapacitated](/rules/conditions.md#Incapacitated). These effects,\
      \ including any remaining temporary hit points, all end when the ice melts."
    "name": "Shield of Cryonax (1/Day)"
"source":
  - "MaBJoV"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Darien.webp"
```
^statblock
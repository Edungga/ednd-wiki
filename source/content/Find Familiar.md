---
School: Conjuration
Spell Circle: 1st
Casting Time: 1 hour or Ritual
Range: 10 ft
Components: V, S, M (burning incense worth 10+ GP, which the spell consumes)
Duration: Instantaneous
Spell List: Arcane
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
FROM "Spells"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name -->

| School | Spell Circle | Casting Time | Range | Components | Duration | Spell List |
| ------ | ------------ | ------------ | ----- | ---------- | -------- | ---------- |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->

You gain the service of an otherworldly spirit, which manifests in an unoccupied space of your choice within range. This creature uses the Otherworldly Familiar stat block below. 

**One Familiar Only**. If you already have a Familiar from this Spell, that Familiar transforms into the new one but retains its memories; you don’t get a second Familiar. 

**Otherworldly Form**. Whenever you cast the Spell, choose the familiar’s creature type: Celestial, Fey, or Fiend. Also choose an environment: Air, Land, or Water. The Familiar resembles a Tiny animal of your choice—such as an owl, a cat, or a frog—that is native to the chosen environment. Both choices—creature type and environment— determine certain traits in the stat block. 

**Telepathic Connection**. While your familiar is within 100 feet of you, you can communicate with it telepathically. Additionally, as a Bonus Action, you can see through the familiar's eyes and hear what it hears until the start of your next turn, gaining the benefits of any special senses it has.

**Remote Delivery**. When you cast a spell with a range of touch, your familiar can deliver the touch. Your familiar must be within 100 feet of you.

**Combat**. The Familiar is an Ally to you and your companions, and shares your Initiative in combat.

**Disappearance of the Familiar**. The Familiar disappears if it drops to 0 HP, if you dismiss it as a Bonus Action, or if you die. When it disappears, it leaves behind anything it was wearing or carrying. If you cast this Spell again, you decide whether you summon the familiar that disappeared or a different one.

| Otherworldly Familiar                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| *Tiny Aberration Celestial, Fey, or Fiend (Choose when casting the Spell)*                                                                                                                                                                                                                                                                                                                                                                                                   |
| **Armour Class**: 10 + 2 (Land only) + 1 per Spell Level                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **Hit Points**: 2 + 2 per Spell Level (the Familiar has a number of Hit Dice (d4s) equal to the Spell’s Level)                                                                                                                                                                                                                                                                                                                                                               |
| **Speed**: 30ft Walk, 30ft Climb (Land only), 30ft Fly (Air only), 30ft Swim (Water only)                                                                                                                                                                                                                                                                                                                                                                                    |
| STR 3 (-4) \| DEX 14 (+2) \| CON 12 (+1) \| INT 11 (+0) \| WIS 14 (+2) \| CHA 8 (-1)                                                                                                                                                                                                                                                                                                                                                                                         |
| Proficiency Bonus equals your bonus<br>                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| Senses Darkvision 120 ft., passive Perception 12                                                                                                                                                                                                                                                                                                                                                                                                                             |
| Languages Telepathy 120 ft. (only between you and the familiar)                                                                                                                                                                                                                                                                                                                                                                                                              |
| **ACTIONS**<br>**Eldritch Strike**. Melee Spell Attack: your Spell Attack Modifier to hit, reach 5 ft., one target. Hit: 2 + half your Warlock level (round up) Damage of a type determined by the Familiar’s creature type: Aberration or Ooze (Acid), Celestial (Radiant), Dragon (Fire), Fey (Psychic), Fiend (Poison), or Undead (Necrotic).<br>**Invisibility**. The Familiar becomes [[Conditions#Invisible (Buff)\|Invisible (Buff)]] until the end of its next turn. |
| **REACTIONS**<br>**Deliver Spell**. When you cast a Spell with a Range of touch, the Familiar can deliver the Spell with its touch. To do so, the Familiar must be within 120ft of you.                                                                                                                                                                                                                                                                                      |
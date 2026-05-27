---
School: Conjuration
Spell Circle: 1st
Casting Time: Action
Range: 90 ft
Components: V, S, M (a bell and silver wire)
Duration: Concentration, up to 1 hour
Spell List: Arcane
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School      | Spell Circle | Casting Time | Range | Components                       | Duration                    | Spell List |
| ----------- | ------------ | ------------ | ----- | -------------------------------- | --------------------------- | ---------- |
| Conjuration | 1st          | Action       | 90 ft | V, S, M (a bell and silver wire) | Concentration, up to 1 hour | Arcane     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
You create an acidic bubble at a point within range, where it explodes in a 5-foot-radius Sphere. Each creature in that Sphere must succeed on a Dexterity saving throw or take 1d6 Acid damage.

**At Higher Levels**. You Summon one additional Oozeling for each spell slot level above 1.

| Oozeling                                                                                                                                                                |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Small Ooze                                                                                                                                                              |
| **Armour Class**: 10                                                                                                                                                    |
| **Hit Points**: 10                                                                                                                                                      |
| **Speed**: 15ft Walk, 15ft Spider Climb                                                                                                                                 |
| STR 8 (-1) \| DEX 15 (+2) \| CON 14 (+2) \| INT 1 (-5) \| WIS 10 (0) \| CHA 3 (-4)                                                                                      |
| **Senses** Blindsight 60 ft. (blind beyond this radius), Passive Perception 10                                                                                          |
| **Languages** understands the languages you speak                                                                                                                       |
| **Amorphous**. The ooze can move through a space as narrow as 1 inch wide without squeezing.                                                                            |
| **ACTIONS**<br>**Pseudopod**. Melee Spell Attack: your Spell Attack Modifier to hit, reach 5 ft., one target. Hit: 1d4 + Your Spellcasting Ability modifier Acid Damage |

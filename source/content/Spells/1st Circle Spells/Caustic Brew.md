---
School: Evocation
Spell Circle: 1st
Casting Time: Action
Range: Self (30ft line)
Components: V, S, M (a bit of rotten food)
Duration: Concentration up to 1 minute
Spell List: Arcane
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School    | Spell Circle | Casting Time | Range            | Components                     | Duration                     | Spell List |
| --------- | ------------ | ------------ | ---------------- | ------------------------------ | ---------------------------- | ---------- |
| Evocation | 1st          | Action       | Self (30ft line) | V, S, M (a bit of rotten food) | Concentration up to 1 minute | Arcane     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
A stream of acid emanates from you in a line 30 feet long and 5 feet wide in a direction you choose. Each creature in the line must succeed on a DEX Save or be covered in acid for the spell’s duration or until a creature uses its action to scrape or wash the acid off itself or another creature. A creature covered in the acid takes 2d4 Acid damage at start of each of its turns.

**At Higher Levels**. The damage increases by 2d4 for each spell slot level above 1.
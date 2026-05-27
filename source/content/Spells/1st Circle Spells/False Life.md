---
School: Necromancy
Spell Circle: 1st
Casting Time: Action
Range: Self
Components: V, S, M (a drop of alcohol)
Duration: Instantaneous
Spell List: Arcane
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School     | Spell Circle | Casting Time | Range | Components                  | Duration      | Spell List |
| ---------- | ------------ | ------------ | ----- | --------------------------- | ------------- | ---------- |
| Necromancy | 1st          | Action       | Self  | V, S, M (a drop of alcohol) | Instantaneous | Arcane     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
You gain 2d4 + 5 Temporary Hit Points.

**At Higher Levels**. You gain 5 additional Temporary Hit Points for each spell slot level above 1.
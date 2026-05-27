---
School: Abjuration
Spell Circle: 1st
Casting Time: Action
Range: Self
Components: V, S, M (a cup of water)
Duration: Until Long Rest
Spell List: Arcane, Primal
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School     | Spell Circle | Casting Time | Range | Components               | Duration        | Spell List     |
| ---------- | ------------ | ------------ | ----- | ------------------------ | --------------- | -------------- |
| Abjuration | 1st          | Action       | Self  | V, S, M (a cup of water) | Until Long Rest | Arcane, Primal |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
Protective magical frost surrounds you. You gain 5 Temporary Hit Points. If a creature hits you with a melee attack roll before the spell ends, the creature takes 5 Cold damage. The spell ends early if you have no Temporary Hit Points.

**At Higher Levels**. The Temporary Hit Points and the Cold damage both increase by 5 for each spell slot level above 1.
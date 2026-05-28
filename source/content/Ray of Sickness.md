---
School: Necromancy
Spell Circle: 1st
Casting Time: Action
Range: 60 ft
Components: V,S
Duration: Instantaneous
Spell List: Arcane, Primal
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School     | Spell Circle | Casting Time | Range | Components | Duration      | Spell List     |
| ---------- | ------------ | ------------ | ----- | ---------- | ------------- | -------------- |
| Necromancy | 1st          | Action       | 60 ft | V,S        | Instantaneous | Arcane, Primal |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
You shoot a greenish ray at a creature within range. Make a ranged spell attack against the target. On a hit, the target takes 2d8 Poison damage and is [[Conditions#Poisoned (Debuff)|Poisoned (Debuff)]] until the end of your next turn.

**At Higher Levels**. The damage increases by 1d8 for each spell slot level above 1.
You can affect one additional creature for each spell slot level above 1.

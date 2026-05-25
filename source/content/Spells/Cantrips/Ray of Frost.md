---
School: Evocation
Spell Circle: Cantrip
Casting Time: Action
Range: 60 ft
Components: V,S
Duration: Instantaneous
Spell List: Arcane, Primal
tags:
  - Spell
---

<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
FROM "Spells"
WHERE file.name = this.file.name
FLATTEN spell-list
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

| School    | Spell Circle | Casting Time | Range | Components | Duration      | Spell List     |
| --------- | ------------ | ------------ | ----- | ---------- | ------------- | -------------- |
| Evocation | Cantrip      | Action       | 60 ft | V,S        | Instantaneous | Arcane, Primal |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

A frigid beam of blue-white light streaks toward a creature within range. Make a Ranged Spell Attack against the target. On a hit, it takes 1d8 Cold damage, and its Speed is reduced by 10 feet until the start of your next turn.

**Cantrip Upgrade**. This spell’s damage increases by 1d8 when you reach levels 5 (2d8), 11 (3d8), and 17 (4d8).
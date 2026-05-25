---
School: Evocation
Spell Circle: Cantrip
Casting Time: Action
Range: 60 ft
Components: V,S
Duration: Instantaneous
Spell List: "[[Arcane Spell List|Arcane]], [[Primal Spell List|Primal]]"
tags:
  - Spell
---

<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
FROM "Spells"
WHERE file.name = this.file.name
FLATTEN spell-list
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

| School    | Spell Circle | Casting Time | Range | Components | Duration      | Spell List                                                   |
| --------- | ------------ | ------------ | ----- | ---------- | ------------- | ------------------------------------------------------------ |
| Evocation | Cantrip      | Action       | 60 ft | V,S        | Instantaneous | [[Arcane Spell List\|Arcane]], [[Primal Spell List\|Primal]] |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

You cause numbing frost to form on one creature that you can see within range. The target must make a CON Save or take 1d6 Cold damage, and has Disadvantage on the next Attack Roll it makes before the end of its next turn.

Cantrip Upgrade. This spell’s damage increases by 1d6 when you reach levels 5 (2d6), 11 (3d6), and 17 (4d6).
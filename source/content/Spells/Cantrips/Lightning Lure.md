---
School: Evocation
Spell Circle: Cantrip
Casting Time: Action
Range: 15 ft
Components: S
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
| Evocation | Cantrip      | Action       | 15 ft | S          | Instantaneous | [[Arcane Spell List\|Arcane]], [[Primal Spell List\|Primal]] |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

You create a lash of lightning energy that strikes at one creature of your choice that you can see within range. The target must succeed on a STR Save or be pulled up to 10 feet in a straight line toward you and then take 1d8 Lightning damage.

**Cantrip Upgrade**. This spell’s damage increases by 1d8 when you reach levels 5 (2d8), 11 (3d8), and 17 (4d8).
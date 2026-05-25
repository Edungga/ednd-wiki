---
School: Necromancy
Spell Circle: Cantrip
Casting Time: Action
Range: 30 ft
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

| School     | Spell Circle | Casting Time | Range | Components | Duration      | Spell List                                                   |
| ---------- | ------------ | ------------ | ----- | ---------- | ------------- | ------------------------------------------------------------ |
| Necromancy | Cantrip      | Action       | 30 ft | V,S        | Instantaneous | [[Arcane Spell List\|Arcane]], [[Primal Spell List\|Primal]] |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

You launch a mist of toxic energy at a creature within range. Creatures make a CON Save or take 1d12 Poison damage.

Cantrip Upgrade. This spell’s damage increases by 1d12 when you reach levels 5 (2d12), 11 (3d12), and 17 (4d12).
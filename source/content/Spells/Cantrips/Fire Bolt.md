---
School: Evocation
Spell Circle: Cantrip
Casting Time: Action
Range: 120 ft
Components: V,S
Duration: Instantaneous
Spell List: "[[Arcane Spell List|Arcane]]"
tags:
  - Spell
---

<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
FROM "Spells"
WHERE file.name = this.file.name
FLATTEN spell-list
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

| School    | Spell Circle | Casting Time | Range  | Components | Duration      | Spell List                              |
| --------- | ------------ | ------------ | ------ | ---------- | ------------- | --------------------------------------- |
| Evocation | Cantrip      | Action       | 120 ft | V,S        | Instantaneous | [[Arcane Spell List\|Arcane]] |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

You hurl a mote of fire at a creature or object within range. Make a Ranged Spell Attack against the target. On a hit, the target takes 1d10 Fire damage. A flammable object hit by this spell ignites if it isn't being worn or carried.

**Cantrip Upgrade**. This spell’s damage increases by 1d10 when you reach levels 5 (2d10), 11 (3d10), and 17 (4d10).
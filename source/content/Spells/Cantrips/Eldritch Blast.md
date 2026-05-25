---
School: Evocation
Spell Circle: Cantrip
Casting Time: Action
Range: 120 ft
Components: V,S
Duration: Instantaneous
Spell List:
tags:
  - Spell
---

<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
FROM "Spells"
WHERE file.name = this.file.name
FLATTEN spell-list
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

| School    | Spell Circle | Casting Time | Range  | Components | Duration      | Spell List |
| --------- | ------------ | ------------ | ------ | ---------- | ------------- | ---------- |
| Evocation | Cantrip      | Action       | 120 ft | V,S        | Instantaneous | -          |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

A beam of crackling energy streaks toward a creature within range. Make a Ranged Spell Attack against the target. On a hit, the target takes 1d10 Force Damage.

**Cantrip Upgrade**. This spell creates another beam when you reach levels 5 (2 beams), 11 (3 beams), and 17 (4 beams). You can direct the beams at the same target or at different ones. Make a separate attack roll for each beam.
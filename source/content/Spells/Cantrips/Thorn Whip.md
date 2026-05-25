---
School: Conjuration
Spell Circle: Cantrip
Casting Time: Action
Range: 30 ft
Components: V, S, M (the stem of a plant with thorns)
Duration: Instantaneous
Spell List: Primal
tags:
  - Spell
---

<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
FROM "Spells"
WHERE file.name = this.file.name
FLATTEN spell-list
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

| School      | Spell Circle | Casting Time | Range | Components                                | Duration      | Spell List |
| ----------- | ------------ | ------------ | ----- | ----------------------------------------- | ------------- | ---------- |
| Conjuration | Cantrip      | Action       | 30 ft | V, S, M (the stem of a plant with thorns) | Instantaneous | Primal     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

You create a long, vine-like whip covered in thorns that lashes out at your command toward a creature in range. Make a Melee Spell Attack against the target. If the attack hits, the creature takes 1d6 Piercing damage, and if the creature is no more than one size larger than you, you pull the creature up to 10 feet closer to you.

**Cantrip Upgrade**. This spell’s damage increases by 1d6 when you reach levels 5 (2d6), 11 (3d6), and 17 (4d6).
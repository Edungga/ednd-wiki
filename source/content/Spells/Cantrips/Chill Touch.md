---
School: Necromancy
Spell Circle: Cantrip
Casting Time: Action
Range: 60 ft
Components: S
Duration: Instantaneous
Spell List: Arcane
tags:
  - Spell
---

<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
FROM "Spells"
WHERE file.name = this.file.name
FLATTEN spell-list
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

| School     | Spell Circle | Casting Time | Range | Components | Duration      | Spell List |
| ---------- | ------------ | ------------ | ----- | ---------- | ------------- | ---------- |
| Necromancy | Cantrip      | Action       | 60 ft | S          | Instantaneous | Arcane     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->

You create a ghostly, skeletal hand striking a creature within range. Make a Ranged Spell Attack against the creature. On a hit, the target takes 1d8 necrotic damage, and it can’t heal until the start of your next turn.

Cantrip Upgrade. This spell’s damage increases by 1d8 when you reach levels 5 (2d8), 11 (3d8), and 17 (4d8).
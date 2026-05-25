---
School: Divination
Spell Circle: Cantrip
Casting Time: Bonus Action
Range: 30 ft
Components: S
Duration: 1 round
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

| School     | Spell Circle | Casting Time | Range | Components | Duration | Spell List |
| ---------- | ------------ | ------------ | ----- | ---------- | -------- | ---------- |
| Divination | Cantrip      | Bonus Action | 30 ft | S          | 1 round  | Arcane     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

You extend your hand and point a finger at a target in Range. Your magic grants you a brief insight into the target's defences. The next Attack against the target has Advantage.

**Cantrip Upgrade**. This Attack also deals additional Weapon Damage when you reach levels 5 (1d6), 11 (2d6), and 17 (3d6).
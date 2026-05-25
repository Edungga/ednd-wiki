---
School: Evocation
Spell Circle: Cantrip
Casting Time: Action
Range: Touch
Components: V,S
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

| School    | Spell Circle | Casting Time | Range | Components | Duration      | Spell List |
| --------- | ------------ | ------------ | ----- | ---------- | ------------- | ---------- |
| Evocation | Cantrip      | Action       | Touch | V,S        | Instantaneous | Arcane     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

Lightning springs from your hand to deliver a shock to a creature you try to touch. Make a Melee Spell Attack against the target. On a hit, the target takes 1d8 Lightning damage, and it can't take Reactions until the start of its next turn.

**Cantrip Upgrade**. This spell’s damage increases by 1d8 when you reach levels 5 (2d8), 11 (3d8), and 17 (4d8).
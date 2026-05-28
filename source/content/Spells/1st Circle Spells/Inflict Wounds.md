---
School: Necromancy
Spell Circle: 1st
Casting Time: Action
Range: Touch
Components: V,S
Duration: Instantaneous
Spell List: Divine
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School     | Spell Circle | Casting Time | Range | Components | Duration      | Spell List |
| ---------- | ------------ | ------------ | ----- | ---------- | ------------- | ---------- |
| Necromancy | 1st          | Action       | Touch | V,S        | Instantaneous | Divine     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
A creature you touch makes a Constitution saving throw, taking 3d10 Necrotic damage on a failed save or half as much damage on a successful one.

**At Higher Levels**. The damage increases by 1d10 for each spell slot level above 1.

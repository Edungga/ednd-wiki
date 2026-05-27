---
School: Divination
Spell Circle: 1st
Casting Time: 1 minute
Range: Touch
Components: V,S
Duration: Until Long Rest
Spell List: Arcane
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School     | Spell Circle | Casting Time | Range | Components | Duration        | Spell List |
| ---------- | ------------ | ------------ | ----- | ---------- | --------------- | ---------- |
| Divination | 1st          | 1 minute     | Touch | V,S        | Until Long Rest | Arcane     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
You touch a willing creature. For the duration, the target can add 1d8 to its initiative rolls.

**At Higher Levels**. You can affect one additional creature for each spell slot level above 1.
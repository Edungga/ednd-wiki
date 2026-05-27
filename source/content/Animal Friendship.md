---
School: Enchantment
Spell Circle: 1st
Casting Time: Action
Range: 30 ft
Components: V, S, M (a morsel of food)
Duration: 24 hours
Spell List: Primal
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
FROM "Spells"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name -->

| School | Spell Circle | Casting Time | Range | Components | Duration | Spell List |
| ------ | ------------ | ------------ | ----- | ---------- | -------- | ---------- |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
Target a Beast that you can see within range. The target must succeed on a Wisdom saving throw or have the Charmed condition for the duration. If you or one of your allies deals damage to the target, the spells ends.

**At Higher Levels**. You can target one additional Beast for each spell slot level above 1.
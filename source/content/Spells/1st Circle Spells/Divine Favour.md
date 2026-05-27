---
School: Evocation
Spell Circle: 1st
Casting Time: Bonus Action
Range: Touch
Components: V,S
Duration: 1 minute
Spell List: Divine
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School    | Spell Circle | Casting Time | Range | Components | Duration | Spell List |
| --------- | ------------ | ------------ | ----- | ---------- | -------- | ---------- |
| Evocation | 1st          | Bonus Action | Touch | V,S        | 1 minute | Divine     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
Your prayer empowers a weapon you touch with divine radiance. Until the spell ends, that weapons Attacks deal an extra 1d4 Radiant Damage on a hit.

**At Higher Levels**. The damage increases by 1d4 for each spell slot level above 1.
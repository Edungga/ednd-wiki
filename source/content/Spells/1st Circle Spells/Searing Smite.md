---
School: Evocation
Spell Circle: 1st
Casting Time: Bonus Action, which you take immediately after hitting a creature with a Weapon Attack
Range: Self
Components: V
Duration: 1 minute
Spell List: Divine
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School    | Spell Circle | Casting Time                                                                           | Range | Components | Duration | Spell List |
| --------- | ------------ | -------------------------------------------------------------------------------------- | ----- | ---------- | -------- | ---------- |
| Evocation | 1st          | Bonus Action, which you take immediately after hitting a creature with a Weapon Attack | Self  | V          | 1 minute | Divine     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
As you hit the target, it takes an extra 1d6 Fire damage from the attack. At the start of each of its turns until the spell ends, the target takes 1d6 Fire damage and then makes a Constitution saving throw. On a failed save, the spell continues. On a successful save, the spell ends.

**At Higher Levels**. The damage increases by 1d6 for each spell slot level above 1.

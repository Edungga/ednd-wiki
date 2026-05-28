---
School: Abjuration
Spell Circle: 1st
Casting Time: Bonus Action
Range: 30 ft
Components: V, S, M (a shard of glass from a mirror)
Duration: 1 minute
Spell List: Divine
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School     | Spell Circle | Casting Time | Range | Components                               | Duration | Spell List |
| ---------- | ------------ | ------------ | ----- | ---------------------------------------- | -------- | ---------- |
| Abjuration | 1st          | Bonus Action | 30 ft | V, S, M (a shard of glass from a mirror) | 1 minute | Divine     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
You ward a creature within range. Until the spell ends, any creature who targets the warded creature with an attack roll or a damaging spell must succeed on a Wisdom saving throw or either choose a new target or lose the attack or spell. This spell doesn't protect the warded creature from areas of effect.

The spell ends if the warded creature makes an attack roll, casts a spell, or deals damage.

**At Higher Levels**. You can affect one additional creature for each spell slot level above 1.

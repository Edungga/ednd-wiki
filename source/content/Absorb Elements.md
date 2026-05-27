---
School: Abjuration
Spell Circle: 1st
Casting Time: Reaction, when you take Acid, Cold, Fire, Lightning, or Thunder Damage
Range: Self
Components: S
Duration: End of your next Turn
Spell List: Arcane, Primal
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
The spell captures some of the incoming energy, lessening its effect on you and storing it for your next Melee Attack. You have Resistance to the triggering Damage Type for the Duration. Also, the next Melee Attack you hit with deals an extra 1d6 Damage of the triggering type, and the Spell ends.

**At Higher Levels**. When you cast this spell using a spell slot of 2nd level or higher, the extra damage increases by 1d6 for each slot level above 1st.
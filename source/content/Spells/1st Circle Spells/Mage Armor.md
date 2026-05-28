---
School: Abjuration
Spell Circle: 1st
Casting Time: Action
Range: Touch
Components: V, S, M (a piece of cured leather)
Duration: Until Long Rest
Spell List:
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School     | Spell Circle | Casting Time | Range | Components                         | Duration        | Spell List |
| ---------- | ------------ | ------------ | ----- | ---------------------------------- | --------------- | ---------- |
| Abjuration | 1st          | Action       | Touch | V, S, M (a piece of cured leather) | Until Long Rest | \-         |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
You touch a willing creature who isn't wearing armor. Until the spell ends, the target's base AC becomes 13 plus its Dexterity modifier. The spell ends early if the target dons armor.

**At Higher Levels**. When you cast this spell using a Spell Slot of 3rd or 4th level, the target’s base AC becomes 14 + its DEX modifier. When you use a Spell Slot of 5th level or higher, the target’s base AC becomes 16 + its DEX modifier. 

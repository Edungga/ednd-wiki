---
School: Enchantment
Spell Circle: 1st
Casting Time: Action
Range: 30 ft
Components: V, S, M (a tart and a feather)
Duration: Concentration up to 1 minute
Spell List: Arcane
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School      | Spell Circle | Casting Time | Range | Components                     | Duration                     | Spell List |
| ----------- | ------------ | ------------ | ----- | ------------------------------ | ---------------------------- | ---------- |
| Enchantment | 1st          | Action       | 30 ft | V, S, M (a tart and a feather) | Concentration up to 1 minute | Arcane     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
One creature of your choice that you can see within range makes a Wisdom saving throw. On a failed save, it has the Prone and Incapacitated conditions for the duration. During that time, it laughs uncontrollably if it's capable of laughter, and it can't end the Prone condition on itself.

At the end of each of its turns and each time it takes damage, it makes another Wisdom saving throw. The target has Advantage on the save if the save is triggered by damage. On a successful save, the spell ends.

**At Higher Levels**. You can affect one additional creature for each spell slot level above 1.

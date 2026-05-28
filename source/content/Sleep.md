---
School: Enchantment
Spell Circle: 1st
Casting Time: Action
Range: 60 ft
Components: V, S, M (a pinch of sand or rose petals)
Duration: Concentration up to 1 minute
Spell List: Arcane
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School      | Spell Circle | Casting Time | Range | Components                               | Duration                     | Spell List |
| ----------- | ------------ | ------------ | ----- | ---------------------------------------- | ---------------------------- | ---------- |
| Enchantment | 1st          | Action       | 60 ft | V, S, M (a pinch of sand or rose petals) | Concentration up to 1 minute | Arcane     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
You create an acidic bubble at a point within range, where it explodes in a 5-foot-radius Sphere. Each creature in that Sphere must succeed on a Dexterity saving throw or take 1d6 Acid damage.

**At Higher Levels**. The damage increases by 1d6 for each spell slot level above 1.
You can affect one additional creature for each spell slot level above 1.

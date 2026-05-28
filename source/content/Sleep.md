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
Each creature of your choice in a 5-foot-radius Sphere centered on a point within range must succeed on a Wisdom saving throw or be [[Conditions#Incapacitated (Condition)|Incapacitated (Condition)]] until the end of its next turn, at which point it must repeat the save. If the target fails the second save, the target has the [[Conditions#Unconscious (Condition)|Unconscious (Condition)]] for the duration. The spell ends on a target if it takes damage or someone within 5 feet of it takes an action to shake it out of the spell's effect.

Creatures that don't sleep, such as elves, or that have Immunity to being [[Conditions#Exhaustion (Condition)|Ex]] automatically succeed on saves against this spell.

**At Higher Levels**. The damage increases by 1d6 for each spell slot level above 1.
You can affect one additional creature for each spell slot level above 1.

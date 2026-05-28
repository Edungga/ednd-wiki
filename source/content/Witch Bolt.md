---
School: Evocation
Spell Circle: 1st
Casting Time: Action
Range: 60 ft
Components: V, S, M (a twig struck by lightning)
Duration: Concentration up to 1 minute
Spell List: Arcane
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School    | Spell Circle | Casting Time | Range | Components                           | Duration                     | Spell List |
| --------- | ------------ | ------------ | ----- | ------------------------------------ | ---------------------------- | ---------- |
| Evocation | 1st          | Action       | 60 ft | V, S, M (a twig struck by lightning) | Concentration up to 1 minute | Arcane     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
A beam of crackling energy lances toward a creature within range, forming a sustained arc of lightning between you and the target. Make a ranged spell attack against it. On a hit, the target takes 2d12 Lightning damage.

On each of your subsequent turns, you can take a Bonus Action to deal 1d12 Lightning damage to the target automatically, even if the first attack missed.

The spell ends if the target is ever outside the spell's range or if it has Total Cover from you.

**At Higher Levels**. The damage increases by 1d12 for each spell slot level above 1.

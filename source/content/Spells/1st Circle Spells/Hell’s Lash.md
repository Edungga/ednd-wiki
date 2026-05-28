---
School: Evocation
Spell Circle: 1st
Casting Time: Action
Range: 30 ft
Components: V, S, M (the forked tongue of a serpent)
Duration: Concentration up to 1 minute
Spell List: Arcane
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School    | Spell Circle | Casting Time | Range | Components                               | Duration                     | Spell List |
| --------- | ------------ | ------------ | ----- | ---------------------------------------- | ---------------------------- | ---------- |
| Evocation | 1st          | Action       | 30 ft | V, S, M (the forked tongue of a serpent) | Concentration up to 1 minute | Arcane     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
You lash a whip of crimson energy at a creature you can see within range, creating a conduit between you and the target.  The target must succeed on a CON Save or take 4d4 Fire Damage and be tethered. A tethered creature takes 2d4 Fire Damage at the beginning of each of their turns and can repeat the Save at the end of each of their turns, ending the effect on a success. 

For the duration, if the target is an Interdicted creature, you can use your Reaction to burn one of your seals on the creature. When you do, the creature makes their next Save to end this spell with Disadvantage

**At Higher Levels**. The damage increases by 2d4 for each spell slot level above 1.

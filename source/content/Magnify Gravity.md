---
School: Transmutation
Spell Circle: 1st
Casting Time: Action
Range: 60 ft
Components: V,S
Duration: End of your next Turn
Spell List: Arcane
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School        | Spell Circle | Casting Time | Range | Components | Duration              | Spell List |
| ------------- | ------------ | ------------ | ----- | ---------- | --------------------- | ---------- |
| Transmutation | 1st          | Action       | 60 ft | V,S        | End of your next Turn | Arcane     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
The gravity in a 10-foot-radius sphere centered on a point you can see within range increases for a moment. Each creature in the sphere on the turn when you cast the spell must make a Constitution saving throw. On a failed save, a creature takes 2d8 force damage, and its speed is halved until the end of its next turn. On a successful save, a creature takes half as much damage and suffers no reduction to its speed.

Until the start of your next turn, any object that isn't being worn or carried in the sphere requires a successful Strength check against your spell save DC to pick up or move.

**At Higher Levels**. The damage increases by 1d6 for each spell slot level above 1.
You can affect one additional creature for each spell slot level above 1.

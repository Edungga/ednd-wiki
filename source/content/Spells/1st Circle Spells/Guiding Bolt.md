---
School: Evocation
Spell Circle: 1st
Casting Time: Action
Range: 120 ft
Components: V,S
Duration: End of your next Turn
Spell List: Divine
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School    | Spell Circle | Casting Time | Range  | Components | Duration              | Spell List |
| --------- | ------------ | ------------ | ------ | ---------- | --------------------- | ---------- |
| Evocation | 1st          | Action       | 120 ft | V,S        | End of your next Turn | Divine     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
You hurl a bolt of light toward a creature within range. Make a ranged spell attack against the target. On a hit, it takes 4d6 Radiant damage, and the next attack roll made against it before the end of your next turn has Advantage.

**At Higher Levels**. The damage increases by 1d6 for each spell slot level above 1.

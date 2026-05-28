---
School: Evocation
Spell Circle: 1st
Casting Time: Action
Range: Self (15ft cube)
Components: V,S
Duration: Instantaneous
Spell List: Arcane, Primal
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School    | Spell Circle | Casting Time | Range            | Components | Duration      | Spell List     |
| --------- | ------------ | ------------ | ---------------- | ---------- | ------------- | -------------- |
| Evocation | 1st          | Action       | Self (15ft cube) | V,S        | Instantaneous | Arcane, Primal |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
You unleash a wave of thunderous energy. Each creature in a 15-foot Cube originating from you makes a Constitution saving throw. On a failed save, a creature takes 2d8 Thunder damage and is pushed 10 feet away from you. On a successful save, a creature takes half as much damage only.

In addition, unsecured objects that are entirely within the Cube are pushed 10 feet away from you, and a thunderous boom is audible within 300 feet.

**At Higher Levels**. The damage increases by 1d8 for each spell slot level above 1.

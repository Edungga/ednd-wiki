---
School: Conjuration
Spell Circle: 1st
Casting Time: Bonus Action, which you take immediately after hitting a creature with a Weapon Attack
Range: Self
Components: V
Duration: Instantaneous
Spell List: Primal
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School      | Spell Circle | Casting Time                                                                           | Range | Components | Duration      | Spell List |
| ----------- | ------------ | -------------------------------------------------------------------------------------- | ----- | ---------- | ------------- | ---------- |
| Conjuration | 1st          | Bonus Action, which you take immediately after hitting a creature with a Weapon Attack | Self  | V          | Instantaneous | Primal     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
As you hit the target, grasping vines appear on it, and it makes a Strength saving throw. A Large or larger creature has Advantage on this save. On a failed save, the target is [[Conditions#Restrained (Condition)|Restrained (Condition)]] until the spell ends. On a successful save, the vines shrivel away, and the spell ends.

While Restrained, the target takes 1d6 Piercing damage at the start of each of its turns. The target or a creature within reach of it can take an action to make a Strength (Athletics) check against your spell save DC. On a success, the spell ends.

**At Higher Levels**. The damage increases by 1d6 for each spell slot level above 1.
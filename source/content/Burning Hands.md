---
School: Evocation
Spell Circle: 1st
Casting Time: Action
Range: Self
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

| School    | Spell Circle | Casting Time | Range | Components | Duration      | Spell List     |
| --------- | ------------ | ------------ | ----- | ---------- | ------------- | -------------- |
| Evocation | 1st          | Action       | Self  | V,S        | Instantaneous | Arcane, Primal |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
A thin sheet of flames shoots forth from you. Each creature in a 15-foot Cone makes a Dexterity saving throw, taking 3d6 Fire damage on a failed save or half as much damage on a successful one.

Flammable objects in the Cone that aren't being worn or carried start [[Burning]].

**At Higher Levels**. The damage increases by 1d6 for each spell slot level above 1.
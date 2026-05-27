---
School: Conjuration
Spell Circle: 1st
Casting Time: Action
Range: 90 ft
Components: V,S
Duration: Concentration up to 1 minute
Spell List: Primal
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School      | Spell Circle | Casting Time | Range | Components | Duration                     | Spell List |
| ----------- | ------------ | ------------ | ----- | ---------- | ---------------------------- | ---------- |
| Conjuration | 1st          | Action       | 90 ft | V,S        | Concentration up to 1 minute | Primal     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
Grasping plants sprout from the ground in a 20-foot square within range. For the duration, these plants turn the ground in the area into Difficult Terrain. They disappear when the spell ends.

Each creature (other than you) in the area when you cast the spell must succeed on a Strength saving throw or have the Restrained condition until the spell ends. A Restrained creature can take an action to make a Strength (Athletics) check against your spell save DC. On a success, it frees itself from the grasping plants and is no longer Restrained by them.

**At Higher Levels**. The damage increases by 1d6 for each spell slot level above 1.
You can affect one additional creature for each spell slot level above 1.
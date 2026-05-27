---
School: Conjuration
Spell Circle: 1st
Casting Time: Action
Range: 120 ft
Components: V,S
Duration: Concentration, up to 1 hour
Spell List: Arcane, Primal
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School      | Spell Circle | Casting Time | Range  | Components | Duration                    | Spell List     |
| ----------- | ------------ | ------------ | ------ | ---------- | --------------------------- | -------------- |
| Conjuration | 1st          | Action       | 120 ft | V,S        | Concentration, up to 1 hour | Arcane, Primal |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
You create a 20-foot-radius Sphere of fog centered on a point within range. The Sphere is Heavily Obscured. It lasts for the duration or until a strong wind (such as one created by [[Gust of Wind]]) disperses it.

**At Higher Levels**. The fog's radius increases by 20 feet for each spell slot level above 1.


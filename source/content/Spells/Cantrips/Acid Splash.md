---
School: Evocation
Spell Circle: Cantrip
Casting Time: Action
Range: 60 ft
Components: V,S
Duration: Instantaneous
Spell List: Arcane
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
FROM "Spells"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name -->

| School    | Spell Circle | Casting Time | Range | Components | Duration      | Spell List |
| --------- | ------------ | ------------ | ----- | ---------- | ------------- | ---------- |
| Evocation | Cantrip      | Action       | 60 ft | V,S        | Instantaneous | Arcane     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->

You create an acidic bubble at a point within range, where it explodes in a 5-foot-radius Sphere. Each creature in that Sphere must succeed on a Dexterity saving throw or take 1d6 Acid damage.

**Cantrip Upgrade**. The damage increases by 1d6 when you reach levels 5 (2d6), 11 (3d6), and 17 (4d6).
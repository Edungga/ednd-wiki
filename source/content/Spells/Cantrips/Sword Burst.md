---
School: Conjuration
Spell Circle: Cantrip
Casting Time: Action
Range: Self (5 ft emination)
Components: V,S
Duration: Instantaneous
Spell List: Arcane
tags:
  - Spell
---

<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
FROM "Spells"
WHERE file.name = this.file.name
FLATTEN spell-list
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

| School      | Spell Circle | Casting Time | Range                 | Components | Duration      | Spell List |
| ----------- | ------------ | ------------ | --------------------- | ---------- | ------------- | ---------- |
| Conjuration | Cantrip      | Action       | Self (5 ft emination) | V,S        | Instantaneous | Arcane     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

You create a momentary circle of spectral blades that sweep around you. All other creatures within 5 feet of you must succeed on a DEX Save or take 1d6 force damage.

**Cantrip Upgrade**. This spell's damage increases by 1d6 when you reach 5th level (2d6), 11th level (3d6), and 17th level (4d6).
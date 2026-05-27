---
School: Necromancy
Spell Circle: 1st
Casting Time: Action
Range: Touch
Components: V,S
Duration: Instantaneous
Spell List: Divine, Primal
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School     | Spell Circle | Casting Time | Range | Components | Duration      | Spell List     |
| ---------- | ------------ | ------------ | ----- | ---------- | ------------- | -------------- |
| Necromancy | 1st          | Action       | Touch | V,S        | Instantaneous | Divine, Primal |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
A creature you touch regains a number of Hit Points equal to 2d8 plus your spellcasting ability modifier.

**At Higher Levels**. The healing increases by 2d8 for each spell slot level above 1.
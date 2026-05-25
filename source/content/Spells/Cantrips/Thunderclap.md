---
School: Evocation
Spell Circle: Cantrip
Casting Time: Action
Range: Self (5 ft emination)
Components: S
Duration: Instantaneous
Spell List: Arcane, Primal
tags:
  - Spell
---

<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
FROM "Spells"
WHERE file.name = this.file.name
FLATTEN spell-list
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

| School    | Spell Circle | Casting Time | Range                 | Components | Duration      | Spell List     |
| --------- | ------------ | ------------ | --------------------- | ---------- | ------------- | -------------- |
| Evocation | Cantrip      | Action       | Self (5 ft emination) | S          | Instantaneous | Arcane, Primal |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

You create a burst of thunderous sound that can be heard up to 100ft away. Each creature within 5ft of you, must make a CON Save or take 1d6 Thunder Damage.

Cantrip Upgrade. This spell’s damage increases by 1d6 when you reach levels 5 (2d6), 11 (3d6), and 17 (4d6).
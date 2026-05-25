---
School: Evocation
Spell Circle: Cantrip
Casting Time: Action
Range: Self (5 ft emination)
Components: V, M (a sunburst token)
Duration: Instantaneous
Spell List: Divine
tags:
  - Spell
---

<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
FROM "Spells"
WHERE file.name = this.file.name
FLATTEN spell-list
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

| School    | Spell Circle | Casting Time | Range                 | Components              | Duration      | Spell List |
| --------- | ------------ | ------------ | --------------------- | ----------------------- | ------------- | ---------- |
| Evocation | Cantrip      | Action       | Self (5 ft emination) | V, M (a sunburst token) | Instantaneous | Divine     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

You utter a divine word, and burning radiance erupts from you. Each creature of your choice within Range must succeed on a CON Save or take 1d6 Radiant Damage.

**Cantrip Upgrade**. This spell’s Damage increases when you reach levels 5 (2d6), 11 (3d6), and 17 (4d6).
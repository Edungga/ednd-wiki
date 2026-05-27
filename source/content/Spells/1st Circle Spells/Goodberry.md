---
School: Conjuration
Spell Circle: 1st
Casting Time: Action
Range: Touch
Components: V, S, M (a sprig of mistletoe)
Duration: 24 hours
Spell List: Primal
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School      | Spell Circle | Casting Time | Range | Components                     | Duration | Spell List |
| ----------- | ------------ | ------------ | ----- | ------------------------------ | -------- | ---------- |
| Conjuration | 1st          | Action       | Touch | V, S, M (a sprig of mistletoe) | 1 day    | Primal     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
Ten berries appear in your hand and are infused with magic for the duration. A creature can take a Bonus Action to eat one berry. Eating a berry restores 1 Hit Point, and the berry provides enough nourishment to sustain a creature for one day.

Uneaten berries disappear when the spell ends.

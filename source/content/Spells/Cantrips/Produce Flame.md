---
School: Conjuration
Spell Circle: Cantrip
Casting Time: Action
Range: Self
Components: S
Duration: Instantaneous
Spell List: "[[Primal Spell List|Primal]]"
tags:
  - Spell
---

<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
FROM "Spells"
WHERE file.name = this.file.name
FLATTEN spell-list
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

| School      | Spell Circle | Casting Time | Range | Components | Duration      | Spell List                              |
| ----------- | ------------ | ------------ | ----- | ---------- | ------------- | --------------------------------------- |
| Conjuration | Cantrip      | Action       | Self  | S          | Instantaneous | [[Primal Spell List\|Primal]] |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

A flickering flame appears in your hand and remains there for the duration. While in your hand the flame emits no heat but sheds Bright Light in a 20-ft radius and Dim Light for an additional 20ft. The Spell ends if you dismiss it as a Bonus Action or if you cast it again.

When you cast this Spell, or as an Action on a later turn, you can hurl the flame at a creature within 60ft of you. Make a Ranged Spell Attack. On a hit, the target takes 1d8 Fire damage.

**Cantrip Upgrade**. This spell’s damage increases by 1d8 when you reach levels 5 (2d8), 11 (3d8), and 17 (4d8).
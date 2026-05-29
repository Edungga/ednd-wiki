---
School: Abjuration
Spell Circle: Cantrip
Casting Time: Bonus Action
Range: Self
Components: V,S
Duration: Concentration, up to 1 minute
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

| School     | Spell Circle | Casting Time | Range | Components | Duration                      | Spell List |
| ---------- | ------------ | ------------ | ----- | ---------- | ----------------------------- | ---------- |
| Abjuration | Cantrip      | Bonus Action | Self  | V,S        | Concentration, up to 1 minute | Arcane     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->

You extend your hand and trace a sigil of warding in the air, granting yourself [[Conditions#Warded (Buff)|Warded (Buff)]] for the duration.
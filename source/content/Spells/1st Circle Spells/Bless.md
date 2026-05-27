---
School: Enchantment
Spell Circle: 1st
Casting Time: Action
Range: 30 ft
Components: V, S, M (a sprinkling of holy water)
Duration: Concentration up to 1 minute
Spell List: Divine
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School      | Spell Circle | Casting Time | Range | Components                           | Duration                     | Spell List |
| ----------- | ------------ | ------------ | ----- | ------------------------------------ | ---------------------------- | ---------- |
| Enchantment | 1st          | Action       | 30 ft | V, S, M (a sprinkling of holy water) | Concentration up to 1 minute | Divine     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
Up to three creatures of your choice within Range gain [[Conditions#Bless (Buff)|Bless (Buff)]]

**At Higher Levels**. You can target one additional creature for each spell slot level above 1.
---
School: Enchantment
Spell Circle: 1st
Casting Time: Action
Range: Touch
Components: V,S
Duration: Concentration up to 1 minute
Spell List: Divine
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School      | Spell Circle | Casting Time | Range | Components | Duration                     | Spell List |
| ----------- | ------------ | ------------ | ----- | ---------- | ---------------------------- | ---------- |
| Enchantment | 1st          | Action       | Touch | V,S        | Concentration up to 1 minute | Divine     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
A willing creature you touch is imbued with bravery. Until the spell ends, the creature is immune to being [[Conditions#Frightened (Debuff)|Frightened (Debuff)]] and gains Temporary Hit Points equal to your spellcasting ability modifier at the start of each of its turns.

**At Higher Levels**. You can affect one additional creature for each spell slot level above 1.

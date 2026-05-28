---
School: Enchantment
Spell Circle: 1st
Casting Time: Bonus Action, which you take immediately after hitting a creature with a Weapon Attack
Range: Self
Components: V
Duration: 1 minute
Spell List: Divine
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School      | Spell Circle | Casting Time                                                                           | Range | Components | Duration | Spell List |
| ----------- | ------------ | -------------------------------------------------------------------------------------- | ----- | ---------- | -------- | ---------- |
| Enchantment | 1st          | Bonus Action, which you take immediately after hitting a creature with a Weapon Attack | Self  | V          | 1 minute | Divine     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
The target takes an extra 1d6 Necrotic damage from the attack, and it must succeed on a Wisdom saving throw or be [[Conditions#Frightened (Debuff)|Frightened (Debuff)]] until the spell ends. At the end of each of its turns, the Frightened target repeats the save, ending the spell on itself on a success.

**At Higher Levels**. The damage increases by 1d6 for each spell slot level above 1.

---
School: Enchantment
Spell Circle: 1st
Casting Time: Action
Range: 30 ft
Components: V,S
Duration: 1 hour
Spell List: Arcane
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School      | Spell Circle | Casting Time | Range | Components | Duration | Spell List |
| ----------- | ------------ | ------------ | ----- | ---------- | -------- | ---------- |
| Enchantment | 1st          | Action       | 30 ft | V,S        | 1 hour   | Arcane     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
One Humanoid you can see within range makes a Wisdom saving throw. It does so with Advantage if you or your allies are fighting it. 
On a failed save, the target is [[Conditions#Charmed (Debuff)|Charmed (Debuff)]] until the spell ends or until you or your allies damage it. The Charmed creature is Friendly to you. When the spell ends, the target knows it was Charmed by you.

**At Higher Levels**. You can target one additional creature for each spell slot level above 1.
---
School: Transmutation
Spell Circle: Cantrip
Casting Time: Action
Range: Self
Components: V, S, M (shamrock leaf and a bludgeoning Melee Weapon)
Duration: Instantaneous
Spell List: Primal
tags:
  - Spell
---

<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
FROM "Spells"
WHERE file.name = this.file.name
FLATTEN spell-list
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

| School        | Spell Circle | Casting Time | Range | Components                                             | Duration      | Spell List |
| ------------- | ------------ | ------------ | ----- | ------------------------------------------------------ | ------------- | ---------- |
| Transmutation | Cantrip      | Action       | Self  | V, S, M (shamrock leaf and a bludgeoning Melee Weapon) | Instantaneous | Primal     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

You make a Melee Weapons Attack with the the weapons you are holding, imbuing it with nature's power. 
For the attack, you can use your Spellcasting Ability instead of Strength for the attack and damage rolls, and the weapon's damage deals an additional 1d8. If the attack deals damage, it can be Force damage or the weapon’s normal damage type (your choice).

**Cantrip Upgrade**. This additional damage die changes when you reach levels 5 (d12), 11 (2d8), and 17 (2d12).
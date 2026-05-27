---
School: Evocation
Spell Circle: 1st
Casting Time: Action
Range: 120 ft
Components: V,S
Duration: Instantaneous
Spell List: Arcane
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School    | Spell Circle | Casting Time | Range  | Components | Duration      | Spell List |
| --------- | ------------ | ------------ | ------ | ---------- | ------------- | ---------- |
| Evocation | 1st          | Action       | 120 ft | V,S        | Instantaneous | Arcane     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
You hurl an undulating, warbling mass of chaotic energy at one creature in range. Make a Ranged Spell Attack against the target. On a hit, the target takes 2d8 + 1d6 damage. Choose one of the d8s. The number rolled on that die determines the attack's damage type, as shown on the table.

If you roll the same number on both d8s, the chaotic energy leaps from the target to a different creature of your choice within 30 feet of it. Make a new Attack against a new target, and make a new damage roll, which could cause the chaotic energy to leap again.

| d8  | Damage Type | d8  | Damage Type |
| --- | ----------- | --- | ----------- |
| 1   | Acid        | 5   | Lightning   |
| 2   | Cold        | 6   | Poison      |
| 3   | Fire        | 7   | Psychic     |
| 4   | Force       | 8   | Thunder     |

**At Higher Levels**. The damage increases by 1d6 for each spell slot level above 1.
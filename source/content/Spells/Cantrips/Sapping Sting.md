---
School: Necromancy
Spell Circle: Cantrip
Casting Time: Action
Range: 30 ft
Components: V,S
Duration: Instantaneous
Spell List: "[[Arcane Spell List|Arcane]], [[Primal Spell List|Primal]]"
tags:
  - Spell
---

<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
FROM "Spells"
WHERE file.name = this.file.name
FLATTEN spell-list
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

| School     | Spell Circle | Casting Time | Range | Components | Duration      | Spell List                                                   |
| ---------- | ------------ | ------------ | ----- | ---------- | ------------- | ------------------------------------------------------------ |
| Necromancy | Cantrip      | Action       | 30 ft | V,S        | Instantaneous | [[Arcane Spell List\|Arcane]], [[Primal Spell List\|Primal]] |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

You sap the vitality of one creature you can see in range. The target must succeed on a CON Save or take 1d4 Necrotic damage and be [[Conditions#Feeble (Debuff)|Feeble (Debuff)]] until the end of your next turn.

Cantrip Upgrade. This spell’s damage increases by 1d4 when you reach levels 5 (2d4), 11 (3d4), and 17 (4d4).
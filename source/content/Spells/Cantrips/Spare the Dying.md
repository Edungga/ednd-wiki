---
School: Necromancy
Spell Circle: Cantrip
Casting Time: Action
Range: 15 ft
Components: V,S
Duration: Instantaneous
Spell List: "[[Divine Spell List|Divine]], [[Primal Spell List|Primal]]"
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
| Necromancy | Cantrip      | Action       | 15 ft | V,S        | Instantaneous | [[Divine Spell List\|Divine]], [[Primal Spell List\|Primal]] |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

Choose a [[Conditions#Dying (Condition)|Dying (Condition)]] creature within Range. The creature becomes Stable. 
This Spell has no effect on Undead or Constructs.
**Cantrip Upgrade**. This Spell’s Range increases when you reach levels 5 (30ft), 11 (60ft), and 17 (90ft).
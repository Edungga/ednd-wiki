---
School: Transmutation
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

| School        | Spell Circle | Casting Time | Range | Components | Duration      | Spell List                              |
| ------------- | ------------ | ------------ | ----- | ---------- | ------------- | --------------------------------------- |
| Transmutation | Cantrip      | Action       | Self  | S          | Instantaneous | [[Primal Spell List\|Primal]] |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

You channel primal magic to cause your teeth or fingernails to sharpen, ready to deliver a corrosive attack. Make a Melee Spell Attack against one creature within 5 feet of you. On a hit, the target takes 1d10 Acid damage. After you make the attack, your teeth or fingernails return to normal.

**Cantrip Upgrade**. This spell’s damage increases by 1d10 when you reach levels 5 (2d10), 11 (3d10), and 17 (4d10).
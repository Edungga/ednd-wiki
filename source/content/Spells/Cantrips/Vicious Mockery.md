---
School: Enchantment
Spell Circle: Cantrip
Casting Time: Action
Range: 60 ft
Components: V
Duration: Instantaneous
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

| School      | Spell Circle | Casting Time | Range | Components | Duration      | Spell List |
| ----------- | ------------ | ------------ | ----- | ---------- | ------------- | ---------- |
| Enchantment | Cantrip      | Action       | 60 ft | V          | Instantaneous | Arcane     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

You unleash a string of insults laced with subtle enchantments at one creature you can see or hear within range. The target must succeed on a WIS Save or take 1d6 Psychic damage and have Disadvantage on the next attack roll it makes before the end of its next turn.

**Cantrip Upgrade**. The damage increases by 1d6 when you reach levels 5 (2d6), 11 (3d6), and 17 (4d6).
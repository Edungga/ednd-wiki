---
School: Enchantment
Spell Circle: Cantrip
Casting Time: Action
Range: 10 ft
Components: S, M (a small amount of makeup applied to the face as this spell is cast)
Duration: Concentration up to 1 minute
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

| School      | Spell Circle | Casting Time | Range | Components                                                                | Duration                     | Spell List |
| ----------- | ------------ | ------------ | ----- | ------------------------------------------------------------------------- | ---------------------------- | ---------- |
| Enchantment | Cantrip      | Action       | 10 ft | S, M (a small amount of makeup applied to the face as this spell is cast) | Concentration up to 1 minute | Arcane     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

You magically emanate a sense of friendship toward one visible creature within range. The target must succeed on a WIS Save or be Charmed by you for the duration.

The target succeeds automatically if it isn’t a Humanoid, if you’re fighting it, or if you have cast this spell on it within the past 24 hours.

The spell ends early if the target takes damage or if you make an Attack Roll, deal damage, or force anyone to make a Save.
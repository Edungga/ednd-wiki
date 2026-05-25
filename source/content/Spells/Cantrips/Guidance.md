---
School: Divination
Spell Circle: Cantrip
Casting Time: Reaction, to an Ally within Range making a Check
Range: Touch
Components: V,S
Duration: Instantaneous
Spell List: "[[Divine Spell List|Divine]]"
tags:
  - Spell
---

<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
FROM "Spells"
WHERE file.name = this.file.name
FLATTEN spell-list
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

| School     | Spell Circle | Casting Time                                     | Range | Components | Duration      | Spell List                              |
| ---------- | ------------ | ------------------------------------------------ | ----- | ---------- | ------------- | --------------------------------------- |
| Divination | Cantrip      | Reaction, to an Ally within Range making a Check | Touch | V,S        | Instantaneous | [[Divine Spell List\|Divine]] |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

You channel magical insight to the creature making the Check, they add a d4 to the Check.
Once a creature benefits from this Spell, they can’t do so again until they finish a Long Rest.
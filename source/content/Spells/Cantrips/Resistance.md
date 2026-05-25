---
School: Abjuration
Spell Circle: Cantrip
Casting Time: Reaction, to an Ally within Range making a Save
Range: 30 ft
Components: V,S
Duration: Instantaneous
Spell List: Divine, Primal
tags:
  - Spell
---

<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
FROM "Spells"
WHERE file.name = this.file.name
FLATTEN spell-list
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

| School     | Spell Circle | Casting Time                                    | Range | Components | Duration      | Spell List     |
| ---------- | ------------ | ----------------------------------------------- | ----- | ---------- | ------------- | -------------- |
| Abjuration | Cantrip      | Reaction, to an Ally within Range making a Save | 30 ft | V,S        | Instantaneous | Divine, Primal |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

You channel magical protection to the creature making the Save That creature adds a d4 to their Save. 

Once a creature benefits from this spell, they can’t do so again until they finish a Long Rest.
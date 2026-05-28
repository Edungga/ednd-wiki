---
School: Illusion
Spell Circle: 1st
Casting Time: 1 minute or Ritual
Range: Touch
Components: S, M (ink worth 10+ GP, which the spell consumes)
Duration: 10 days
Spell List: Arcane
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
FLATTEN Duration
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name FLATTEN Duration -->

| School   | Spell Circle | Casting Time       | Range | Components                                        | Duration       | Spell List |
| -------- | ------------ | ------------------ | ----- | ------------------------------------------------- | -------------- | ---------- |
| Illusion | 1st          | 1 minute or Ritual | Touch | S, M (ink worth 10+ GP, which the spell consumes) | 1 week, 3 days | Arcane     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
You write on parchment, paper, or another suitable material and imbue it with an illusion that lasts for the duration. To you and any creatures you designate when you cast the spell, the writing appears normal, seems to be written in your hand, and conveys whatever meaning you intended when you wrote the text. To all others, the writing appears as if it were written in an unknown or magical script that is unintelligible. Alternatively, the illusion can alter the meaning, handwriting, and language of the text, though the language must be one you know.

If the spell is dispelled, the original script and the illusion both disappear.

A creature that has Truesight can read the hidden message.

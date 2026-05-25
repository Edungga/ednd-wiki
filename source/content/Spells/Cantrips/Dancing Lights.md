---
School: Evocation
Spell Circle: Cantrip
Casting Time: Action
Range: 120 ft
Components: V, S, M (a bit of phosphorus or wychwood, or a bioluminescent creature such as a glowworm)
Duration: Concentration up to 10 minutes
Spell List: Arcane, Primal
tags:
  - Spell
---

<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
FROM "Spells"
WHERE file.name = this.file.name
FLATTEN spell-list
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

| School    | Spell Circle | Casting Time | Range  | Components                                                                                 | Duration                       | Spell List     |
| --------- | ------------ | ------------ | ------ | ------------------------------------------------------------------------------------------ | ------------------------------ | -------------- |
| Evocation | Cantrip      | Action       | 120 ft | V, S, M (a bit of phosphorus or wychwood, or a bioluminescent creature such as a glowworm) | Concentration up to 10 minutes | Arcane, Primal |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

You create up to four torch-sized lights within range, making them appear as torches, lanterns, or glowing orbs that hover in the air for the duration. You can also combine the four lights into one glowing vaguely humanoid form of Medium Size. Whichever form you choose, each light sheds dim light in a 10ft radius.

As a Bonus Action you can move the lights up to 60ft to a new spot within range. A light must be within 20ft of another light created by this spell, and a light winks out if it exceeds the spell's range.
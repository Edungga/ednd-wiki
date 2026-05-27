---
School: Conjuration
Spell Circle: 1st
Casting Time: Action
Range: 60 ft
Components: V, S, M (a bit of pork rind or butter)
Duration: 1 minute
Spell List: Arcane
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School      | Spell Circle | Casting Time | Range | Components                             | Duration | Spell List |
| ----------- | ------------ | ------------ | ----- | -------------------------------------- | -------- | ---------- |
| Conjuration | 1st          | Action       | 60 ft | V, S, M (a bit of pork rind or butter) | 1 minute | Arcane     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
Flammable grease covers the ground in a 10-foot square centered on a point within range and turns it into Difficult Terrain for the duration.

When the grease appears, each creature standing in its area must succeed on a Dexterity saving throw or be [[Conditions#Prone (Condition)|Prone (Condition)]]. A creature that enters the area or ends its turn there must also succeed on that save or fall Prone.

Any creatures in the grease also count as having Fire Vulnerability.

**At Higher Levels**. The radius increases by 10ft for each spell slot level above 1.

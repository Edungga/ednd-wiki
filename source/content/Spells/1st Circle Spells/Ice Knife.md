---
School: Conjuration
Spell Circle: 1st
Casting Time: Action
Range: 60 ft
Components: S, M (a drop of water or a piece of ice)
Duration: Instantaneous
Spell List: Arcane, Primal
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School      | Spell Circle | Casting Time | Range | Components                               | Duration      | Spell List     |
| ----------- | ------------ | ------------ | ----- | ---------------------------------------- | ------------- | -------------- |
| Conjuration | 1st          | Action       | 60 ft | S, M (a drop of water or a piece of ice) | Instantaneous | Arcane, Primal |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
You create a shard of ice and fling it at one creature within range. Make a ranged spell attack against the target. On a hit, the target takes 1d10 Piercing damage. Hit or miss, the shard then explodes. The target and each creature within 5 feet of it must succeed on a Dexterity saving throw or take 2d6 Cold damage.

**At Higher Levels**. The damage increases by 1d6 for each spell slot level above 1.

---
School: Enchantment
Spell Circle: 1st
Casting Time: Action
Range: 60 ft
Components: V
Duration: Instantaneous
Spell List: Divine
tags:
  - Spell
---
<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
WHERE file.name = this.file.name
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" WHERE file.name = this.file.name -->

| School      | Spell Circle | Casting Time | Range | Components | Duration      | Spell List |
| ----------- | ------------ | ------------ | ----- | ---------- | ------------- | ---------- |
| Enchantment | 1st          | Action       | 60 ft | V          | Instantaneous | Divine     |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->
You speak a one-word command to a creature you can see within range. The target must succeed on a Wisdom saving throw or follow the command on its next turn. Choose the command from these options:
- **Approach**. The target moves toward you by the shortest and most direct route, ending its turn if it moves within 5 feet of you.
- **Drop**. The target drops whatever it is holding and then ends its turn.
- **Flee**. The target spends its turn moving away from you by the fastest available means.
- **Grovel**. The target is [[Conditions#Prone (Condition)|Prone (Condition)]] and then ends its turn.
- **Halt**. On its turn, the target doesn't move and takes no action or Bonus Action

**At Higher Levels**. You can affect one additional creature for each spell slot level above 1.
---
School: Evocation
Spell Circle: Cantrip
Casting Time: Action
Range: Touch
Components: V,S
Duration: 1 hour
Spell List: "[[Arcane Spell List|Arcane]], [[Divine Spell List|Divine]], [[Primal Spell List|Primal]]"
tags:
  - Spell
---

<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
FROM "Spells"
WHERE file.name = this.file.name
FLATTEN spell-list
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

| School    | Spell Circle | Casting Time | Range | Components | Duration | Spell List                                                                                  |
| --------- | ------------ | ------------ | ----- | ---------- | -------- | ------------------------------------------------------------------------------------------- |
| Evocation | Cantrip      | Action       | Touch | V,S        | 1 hour   | [[Arcane Spell List\|Arcane]], [[Divine Spell List\|Divine]], [[Primal Spell List\|Primal]] |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

You touch one object that is no larger than 10 feet in any dimension. Until the spell ends, the object sheds bright light in a 20-foot radius and dim light for an additional 20 feet. The light can be coloured as you like. Completely covering the object with something opaque blocks the light. The spell ends if you cast it again or dismiss it as an action.

If you target an object held or worn by a hostile creature, that creature must succeed on a DEX Save to avoid the spell.
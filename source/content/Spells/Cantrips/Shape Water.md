---
School: Transmutation
Spell Circle: Cantrip
Casting Time: Action
Range: 60 ft
Components: V,S
Duration: Instantaneous or 1 hour (see below)
Spell List: "[[Arcane Spell List|Arcane]], [[Primal Spell List|Primal]]"
tags:
  - Spell
---

<!-- QueryToSerialize: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List"
FROM "Spells"
WHERE file.name = this.file.name
FLATTEN spell-list
-->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

| School        | Spell Circle | Casting Time | Range | Components | Duration                            | Spell List                                                   |
| ------------- | ------------ | ------------ | ----- | ---------- | ----------------------------------- | ------------------------------------------------------------ |
| Transmutation | Cantrip      | Action       | 60 ft | V,S        | Instantaneous or 1 hour (see below) | [[Arcane Spell List\|Arcane]], [[Primal Spell List\|Primal]] |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

You choose an area of water that you can see within range and that fits within a 5ft cube. You manipulate it in one of the following ways:
- You instantaneously move or otherwise change the flow of the water as you direct, up to 5ft in any direction. This movement doesn't have enough force to cause Damage.
- You cause the water to form into simple shapes and animate at your direction. This change lasts for 1 hour.
- You change the water's colour or opacity. The water must be changed in the same way throughout. This change lasts for 1 hour.
- You freeze the water, provided that there are no creatures in it. The water unfreezes in 1 hour.

If you cast this spell multiple times, you can have no more than two of its non-instantaneous effects active at a time, and you can dismiss such an effect as an Action.
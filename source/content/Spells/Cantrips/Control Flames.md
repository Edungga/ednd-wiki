---
School: Transmutation
Spell Circle: Cantrip
Casting Time: Action
Range: 60 ft
Components: S
Duration: Instantaneous or 1 hour (see below)
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

| School        | Spell Circle | Casting Time | Range | Components | Duration                            | Spell List     |
| ------------- | ------------ | ------------ | ----- | ---------- | ----------------------------------- | -------------- |
| Transmutation | Cantrip      | Action       | 60 ft | S          | Instantaneous or 1 hour (see below) | Arcane, Primal |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE spell-circle = "Cantrip" -->

You manipulate a Mundane flame that you can see within Range and that fits within a 5ft cube in one of the following ways:
- You instantaneously expand the flame 5ft in one direction, provided that fuel is present in the new location
- You instantaneously extinguish the flames within the cube
- You double or halve the area of Light cast by the flame, change its colour, or both. The change lasts for 1 hour.
- You cause simple shapes—such as the vague form of a creature, an inanimate object, or a location—to appear within the flames and animate as you like. The shapes last for 1 hour.

If you cast this Spell multiple times, you can have up to three non-instantaneous effects created by it active at a time, and you can dismiss such an effect as an Action.
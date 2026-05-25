---
School: Necromancy
Spell Circle: Cantrip
Casting Time: Action
Range: 60 ft
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

| School     | Spell Circle | Casting Time | Range | Components | Duration      | Spell List                              |
| ---------- | ------------ | ------------ | ----- | ---------- | ------------- | --------------------------------------- |
| Necromancy | Cantrip      | Action       | 60 ft | V,S        | Instantaneous | [[Divine Spell List\|Divine]] |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

You point at one creature you can see within range, and the sound of a dolorous bell fills the air around it for a moment. The target must succeed on a WIS Save or take 1d8 Necrotic damage. If the target is missing any of its hit points, it instead takes 1d12 Necrotic damage.

**Cantrip Upgrade**. This spell’s damage increases when you reach levels 5 (2d8 or 2d12), 11 (3d8 or 3d12), and 17 (4d8 or 4d12).
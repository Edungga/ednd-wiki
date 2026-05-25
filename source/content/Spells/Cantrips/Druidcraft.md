---
School: Transmutation
Spell Circle: Cantrip
Casting Time: Action
Range: 30 ft
Components: V,S
Duration: Instantaneous
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

| School        | Spell Circle | Casting Time | Range | Components | Duration      | Spell List     |
| ------------- | ------------ | ------------ | ----- | ---------- | ------------- | -------------- |
| Transmutation | Cantrip      | Action       | 30 ft | V,S        | Instantaneous | Arcane, Primal |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table WITHOUT ID School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE file.name = this.file.name FLATTEN spell-list -->

Whispering to the spirits of nature, you create one of the following effects within range.

**Weather Sensor**. You create a Tiny, harmless sensory effect that predicts what the weather will be at your location for the next 24 hours. The effect might manifest as a golden orb for clear skies, a cloud for rain, falling snowflakes for snow, and so on. This effect persists for 1 round.

**Bloom**. You instantly make a flower blossom, a seed pod open, or a leaf bud bloom.

**Sensory Effect**. You create a harmless sensory effect, such as falling leaves, spectral dancing fairies, a gentle breeze, the sound of an animal, or the faint odor of skunk. The effect must fit in a 5-foot Cube.

**Fire Play**. You light or snuff out a candle, a torch, or a campfire.
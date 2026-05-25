
<!-- QueryToSerialize: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration
FROM "Spells"
WHERE contains(spell-list,"Divine")
-->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration FROM "Spells" WHERE contains(spell-list,"Divine") -->

| File                                                      | School        | Spell Circle | Casting Time                                     | Range                 | Components              | Duration      |
| --------------------------------------------------------- | ------------- | ------------ | ------------------------------------------------ | --------------------- | ----------------------- | ------------- |
| [[Guidance]]                 | Divination    | Cantrip      | Reaction, to an Ally within Range making a Check | Touch                 | V,S                     | Instantaneous |
| [[Light]]                       | Evocation     | Cantrip      | Action                                           | Touch                 | V,S                     | 1 hour        |
| [[Mending]]                   | Transmutation | Cantrip      | 1 minute                                         | Touch                 | V,S                     | Instantaneous |
| [[Sacred Flame]]         | Evocation     | Cantrip      | Action                                           | 60 ft                 | V,S                     | Instantaneous |
| [[Spare the Dying]]   | Necromancy    | Cantrip      | Action                                           | 15 ft                 | V,S                     | Instantaneous |
| [[Resistance]]             | Abjuration    | Cantrip      | Reaction, to an Ally within Range making a Save  | 30 ft                 | V,S                     | Instantaneous |
| [[Thaumaturgy]]           | Transmutation | Cantrip      | Action                                           | 30 ft                 | V                       | 1 minute      |
| [[Toll the Dead]]       | Necromancy    | Cantrip      | Action                                           | 60 ft                 | V,S                     | Instantaneous |
| [[Word of Radiance]] | Evocation     | Cantrip      | Action                                           | Self (5 ft emination) | V, M (a sunburst token) | Instantaneous |

<!-- SerializedQuery END -->
<!-- SerializedQuery: table School, spell-circle as "Spell Circle", casting-time as "Casting Time", Range, Components, Duration, spell-list as "Spell List" FROM "Spells" WHERE contains(spell-list,"Arcane") -->

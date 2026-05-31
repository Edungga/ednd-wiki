# Light Armour

<!-- QueryToSerialize: table ac-bonus AS "AC Bonus", armour-stealth AS "Armour Stealth", Cost
WHERE contains(tags, "Light-Armour")
SORT ac-bonus
-->
<!-- SerializedQuery: table ac-bonus AS "AC Bonus", armour-stealth AS "Armour Stealth", Cost WHERE contains(tags, "Light-Armour") SORT ac-bonus -->

| File                                                                             | AC Bonus    | Armour Stealth | Cost  |
| -------------------------------------------------------------------------------- | ----------- | -------------- | ----- |
| [[Leather Armour]]                 | AC 11 + Dex | -              | 10 GP |
| [[Padded Armour]]                   | AC 11 + Dex | Disadvantage   | 5 GP  |
| [[Studded Leather Armour]] | AC 12 + Dex | \-             | 45 GP |

<!-- SerializedQuery END -->

# Medium Armour
<!-- QueryToSerialize: table ac-bonus AS "AC Bonus", armour-stealth AS "Armour Stealth", Cost
WHERE contains(tags, "Medium-Armour")
SORT ac-bonus
-->
<!-- SerializedQuery: table ac-bonus AS "AC Bonus", armour-stealth AS "Armour Stealth", Cost WHERE contains(tags, "Medium-Armour") SORT ac-bonus -->

| File                                                                   | AC Bonus            | Armour Stealth | Cost   |
| ---------------------------------------------------------------------- | ------------------- | -------------- | ------ |
| [[Hide Armour]]             | AC 12 + Dex (max 2) | -              | 10 GP  |
| [[Chain Shirt]]             | AC 13 + Dex (max 2) | -              | 50 GP  |
| [[Breastplate]]             | AC 14 + Dex (max 2) | -              | 400 GP |
| [[Scale Mail]]               | AC 14 + Dex (max 2) | Disadvantage   | 50 GP  |
| [[Half Plate Armour]] | AC 15 + Dex (max 2) | Disadvantage   | 750 GP |

<!-- SerializedQuery END -->

# Heavy Armour
<!-- QueryToSerialize: table ac-bonus AS "AC Bonus", str-requirement AS "STR requirement", armour-stealth AS "Armour Stealth", Cost
WHERE contains(tags, "Heavy-Armour")
SORT ac-bonus
-->
<!-- SerializedQuery: table ac-bonus AS "AC Bonus", str-requirement AS "STR requirement", armour-stealth AS "Armour Stealth", Cost WHERE contains(tags, "Heavy-Armour") SORT ac-bonus -->

| File                                                           | AC Bonus | STR requirement                                                                      | Armour Stealth | Cost    |
| -------------------------------------------------------------- | -------- | ------------------------------------------------------------------------------------ | -------------- | ------- |
| [[Ring Mail]]         | AC 14    | \-                                                                                   | Disadvantage   | 30 GP   |
| [[Chain Mail]]       | AC 16    | If the wearer has a Strength score lower than 13, their speed is reduced by 10 feet. | Disadvantage   | 75 GP   |
| [[Splint Armour]] | AC 17    | If the wearer has a Strength score lower than 15, their speed is reduced by 10 feet. | Disadvantage   | 200 GP  |
| [[Plate Armour]]   | AC 18    | If the wearer has a Strength score lower than 15, their speed is reduced by 10 feet. | Disadvantage   | 1500 GP |

<!-- SerializedQuery END -->


# Shields

<!-- QueryToSerialize: table ac-bonus AS "AC Bonus", str-requirement AS "STR requirement", Cost
WHERE contains(tags, "Shield")
SORT ac-bonus
-->
<!-- SerializedQuery: table ac-bonus AS "AC Bonus", str-requirement AS "STR requirement", Cost WHERE contains(tags, "Shield") SORT ac-bonus -->

| File                                                               | AC Bonus | STR requirement | Cost  |
| ------------------------------------------------------------------ | -------- | --------------- | ----- |
| [[Standard Shield]] | +2       | \-              | 10 GP |

<!-- SerializedQuery END -->


# Simple Melee Weapons
<!-- QueryToSerialize: table ac-bonus AS "AC Bonus", armour-stealth AS "Armour Stealth", Cost
WHERE contains(tags, "Simple-Weapon")
SORT Cost
-->
<!-- SerializedQuery: table ac-bonus AS "AC Bonus", armour-stealth AS "Armour Stealth", Cost WHERE contains(tags, "Simple-Weapon") SORT Cost -->

| File | AC Bonus | Armour Stealth | Cost |
| ---- | -------- | -------------- | ---- |

<!-- SerializedQuery END -->
# Simple Ranged Weapons

# Martial Melee Weapons
<!-- QueryToSerialize: table Damage, weapon-mastery, weapon-property, Cost
WHERE contains(tags, "Martial-Weapon")
SORT Cost
-->
<!-- SerializedQuery: table Damage, weapon-mastery, weapon-property, Cost WHERE contains(tags, "Martial-Weapon") SORT Cost -->

| File                                  | Damage       | weapon-mastery                                            | weapon-property                          | Cost  |
| ------------------------------------- | ------------ | --------------------------------------------------------- | ---------------------------------------- | ----- |
| [[Battleaxe]] | 1d8 Slashing | [[Weapon Mastery Properties.md#Topple\|Topple]] | [[Weapons#Versatile\|Versatile]] (d10)]] | 10 GP |

<!-- SerializedQuery END -->
# Martial Ranged Weapons


---
# Weapons Properties


## Versatile
A Versatile weapon can be used with one or two hands. A damage value in parentheses appears with the property. The weapon deals that damage when used with two hands to make a melee attack.
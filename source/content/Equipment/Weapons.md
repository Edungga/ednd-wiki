# Simple Melee Weapons
<!-- QueryToSerialize: table Damage, weapon-mastery AS "Weapon Mastery", weapon-property AS "Weapon Property", Cost
WHERE contains(tags, "Simple-Melee-Weapon")
SORT Cost
-->
<!-- SerializedQuery: table Damage, weapon-mastery AS "Weapon Mastery", weapon-property AS "Weapon Property", Cost WHERE contains(tags, "Simple-Melee-Weapon") SORT Cost -->

| File | Damage | Weapon Mastery | Weapon Property | Cost |
| ---- | ------ | -------------- | --------------- | ---- |

<!-- SerializedQuery END -->
# Simple Ranged Weapons
<!-- QueryToSerialize: table Damage, weapon-mastery AS "Weapon Mastery", weapon-property AS "Weapon Property", Cost
WHERE contains(tags, "Simple-Ranged-Weapon")
SORT Cost
-->
<!-- SerializedQuery: table Damage, weapon-mastery AS "Weapon Mastery", weapon-property AS "Weapon Property", Cost WHERE contains(tags, "Simple-Ranged-Weapon") SORT Cost -->

| File | Damage | Weapon Mastery | Weapon Property | Cost |
| ---- | ------ | -------------- | --------------- | ---- |

<!-- SerializedQuery END -->
# Martial Melee Weapons
<!-- QueryToSerialize: table Damage, weapon-mastery AS "Weapon Mastery", weapon-property AS "Weapon Property", Cost
WHERE contains(tags, "Martial-Melee-Weapon")
SORT Cost
-->
<!-- SerializedQuery: table Damage, weapon-mastery AS "Weapon Mastery", weapon-property AS "Weapon Property", Cost WHERE contains(tags, "Martial-Melee-Weapon") SORT Cost -->

| File                                  | Damage       | Weapon Mastery                                            | Weapon Property                                     | Cost  |
| ------------------------------------- | ------------ | --------------------------------------------------------- | --------------------------------------------------- | ----- |
| [[Battleaxe]] | 1d8 Slashing | [[Weapon Mastery Properties.md#Topple\|Topple]] | [[Weapons.md#Versatile\|Versatile (d10)]] | 10 GP |

<!-- SerializedQuery END -->
# Martial Ranged Weapons
<!-- QueryToSerialize: table Damage, weapon-mastery AS "Weapon Mastery", weapon-property AS "Weapon Property", Cost
WHERE contains(tags, "Martial-Ranged-Weapon")
SORT Cost
-->
<!-- SerializedQuery: table Damage, weapon-mastery AS "Weapon Mastery", weapon-property AS "Weapon Property", Cost WHERE contains(tags, "Martial-Ranged-Weapon") SORT Cost -->

| File                              | Damage     | Weapon Mastery                                      | Weapon Property                                                                                     | Cost  |
| --------------------------------- | ---------- | --------------------------------------------------- | --------------------------------------------------------------------------------------------------- | ----- |
| [[Blowgun]] | 1 Piercing | [[Weapon Mastery Properties.md#Vex\|Vex]] | [[Weapons#Range\|Range (25/100)]], [[Weapons#Ammunition\|Ammunition]], [[Weapons#Loading\|Loading]] | 10 GP |

<!-- SerializedQuery END -->

---
# Weapons Properties

## Ammunition
You can use a weapon that has the Ammunition property to make a ranged attack only if you have ammunition to fire from it. The type of ammunition required is specified with the weapon's range. Each attack expends one piece of ammunition. Drawing the ammunition is part of the attack (you need a free hand to load a one-handed weapon). After a fight, you can spend 1 minute to recover half the ammunition (round down) you used in the fight; the rest is lost.

## Loading
You can fire only one piece of ammunition from a Loading weapon when you use an action, a Bonus Action, or a Reaction to fire it, regardless of the number of attacks you can normally make.
 
## Range
A Range weapon has a range in parentheses after the Ammunition or Thrown property. The range lists two numbers. The first is the weapon's normal range in feet, and the second is the weapon's long range. When attacking a target beyond normal range, you have Disadvantage on the attack roll. You can't attack a target beyond the long range.
## Versatile
A Versatile weapon can be used with one or two hands. A damage value in parentheses appears with the property. The weapon deals that damage when used with two hands to make a melee attack.
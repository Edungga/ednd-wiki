# Simple Melee Weapons
<!-- QueryToSerialize: table Damage, weapon-property AS "Weapon Property", weapon-mastery AS "Weapon Mastery", Cost
WHERE contains(tags, "Simple-Melee-Weapon")
SORT Cost
-->
<!-- SerializedQuery: table Damage, weapon-property AS "Weapon Property", weapon-mastery AS "Weapon Mastery", Cost WHERE contains(tags, "Simple-Melee-Weapon") SORT Cost -->

| File                            | Damage          | Weapon Property                                                                                  | Weapon Mastery                                        | Cost |
| ------------------------------- | --------------- | ------------------------------------------------------------------------------------------------ | ----------------------------------------------------- | ---- |
| [[Club]]     | 1d4 Bludgeoning | [[Weapons.md#Light\|Light]]                                                            | [[Weapon Mastery Properties.md#Slow\|Slow]] | 1 SP |
| [[Dagger]] | 1d4 Piercing    | [[Weapons#Finesse\|Finesse]], [[Weapons#Light\|Light]], [[Weapons#Thrown\|Thrown (Range 20/60)]] | [[Weapon Mastery Properties.md#Nick\|Nick]] | 2 GP |

<!-- SerializedQuery END -->
# Simple Ranged Weapons
<!-- QueryToSerialize: table Damage, weapon-property AS "Weapon Property", weapon-mastery AS "Weapon Mastery", Cost
WHERE contains(tags, "Simple-Ranged-Weapon")
SORT Cost
-->
<!-- SerializedQuery: table Damage, weapon-property AS "Weapon Property", weapon-mastery AS "Weapon Mastery", Cost WHERE contains(tags, "Simple-Ranged-Weapon") SORT Cost -->

| File | Damage | Weapon Property | Weapon Mastery | Cost |
| ---- | ------ | --------------- | -------------- | ---- |

<!-- SerializedQuery END -->
# Martial Melee Weapons
<!-- QueryToSerialize: table Damage, weapon-property AS "Weapon Property", weapon-mastery AS "Weapon Mastery", Cost
WHERE contains(tags, "Martial-Melee-Weapon")
SORT Cost
-->
<!-- SerializedQuery: table Damage, weapon-property AS "Weapon Property", weapon-mastery AS "Weapon Mastery", Cost WHERE contains(tags, "Martial-Melee-Weapon") SORT Cost -->

| File                                  | Damage       | Weapon Property                                     | Weapon Mastery                                            | Cost  |
| ------------------------------------- | ------------ | --------------------------------------------------- | --------------------------------------------------------- | ----- |
| [[Battleaxe]] | 1d8 Slashing | [[Weapons.md#Versatile\|Versatile (d10)]] | [[Weapon Mastery Properties.md#Topple\|Topple]] | 10 GP |

<!-- SerializedQuery END -->
# Martial Ranged Weapons
<!-- QueryToSerialize: table Damage, weapon-property AS "Weapon Property", weapon-mastery AS "Weapon Mastery", Cost
WHERE contains(tags, "Martial-Ranged-Weapon")
SORT Cost
-->
<!-- SerializedQuery: table Damage, weapon-property AS "Weapon Property", weapon-mastery AS "Weapon Mastery", Cost WHERE contains(tags, "Martial-Ranged-Weapon") SORT Cost -->

| File                              | Damage     | Weapon Property                                                                                     | Weapon Mastery                                      | Cost  |
| --------------------------------- | ---------- | --------------------------------------------------------------------------------------------------- | --------------------------------------------------- | ----- |
| [[Blowgun]] | 1 Piercing | [[Weapons#Range\|Range (25/100)]], [[Weapons#Ammunition\|Ammunition]], [[Weapons#Loading\|Loading]] | [[Weapon Mastery Properties.md#Vex\|Vex]] | 10 GP |

<!-- SerializedQuery END -->

---
# Weapons Properties

## Ammunition
You can use a weapon that has the Ammunition property to make a ranged attack only if you have ammunition to fire from it. The type of ammunition required is specified with the weapon's range. Each attack expends one piece of ammunition. Drawing the ammunition is part of the attack (you need a free hand to load a one-handed weapon). After a fight, you can spend 1 minute to recover half the ammunition (round down) you used in the fight; the rest is lost.

## Finesse
When making an attack with a Finesse weapon, use your choice of your Strength or Dexterity modifier for the attack and damage rolls. You must use the same modifier for both rolls.
## Heavy
You have Disadvantage on attack rolls with a Heavy weapon if it's a Melee weapon and your Strength score isn't at least 13 or if it's a Ranged weapon and your Dexterity score isn't at least 13.
## Light 
When you take the Attack action on your turn and attack with a Light weapon, you can make one extra attack as a [[Bonus Actions#Two-Weapon Fighting|Two-Weapon Fighting Bonus Action]] on the same turn. That extra attack must be made with a different Light weapon, and you don't add your ability modifier to the extra attack's damage unless that modifier is negative.
## Loading
You can fire only one piece of ammunition from a Loading weapon when you use an action, a Bonus Action, or a Reaction to fire it, regardless of the number of attacks you can normally make.
## Range
A Range weapon has a range in parentheses after the Ammunition or Thrown property. The range lists two numbers. The first is the weapon's normal range in feet, and the second is the weapon's long range. When attacking a target beyond normal range, you have Disadvantage on the attack roll. You can't attack a target beyond the long range.
## Reach
A Reach weapon adds 5 feet to your reach when you attack with it, as well as when determining your reach for Opportunity Attacks with it.
## Thrown
If a weapon has the Thrown property, you can throw the weapon to make a ranged attack, and you can draw that weapon as part of the attack. If the weapon is a Melee weapon, use the same ability modifier for the attack and damage rolls that you use for a melee attack with that weapon.
## Two-Handed
A Two-Handed weapon requires two hands when you attack with it.
## Versatile
A Versatile weapon can be used with one or two hands. A damage value in parentheses appears with the property. The weapon deals that damage when used with two hands to make a melee attack.
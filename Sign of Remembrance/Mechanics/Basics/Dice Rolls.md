A lot of times during play, it isn't always obvious whether an action attempted by a character is bound to succeed. Though basic actions, like walking down the stairs or paying for a room in an inn, are almost guaranteed to work, more difficult or complicated actions - such as hitting an enemy, bartering with a shopkeeper or avoiding a deadly trap, have a chance to fail. Dice rolls are a way to introduce the element of randomness into the game, while keeping everyone in the table on their toes to see whether their actions fail or succeed.
- - -
## The Dice
 
In order to play Sign of Remembrance, the game master and each player need (at least) one set of dice, denoted by the letter 'd' and a number after the letter. The number indicates the number of sides the die has, and the set is as follows:

- d4 - a pyramid-shaped die
- d6 - a cube-shaped die
- d8
- d10
- d12
- d20

>[!note]
>Sometimes the system requires to roll a d3, in which case the recommendation is to roll a d6 and divide the result by 2 (rounded up).
 
When multiple dice are needed, they are denoted by a number before the letter 'd', which is the number of dice required. The results of all the dice are then added, and the sum is used as the roll's result. For example:

- Rolling (3d4 + 2) means rolling 3 dice with 4 sides, and adding 2 to the sum of the result.
- Rolling 2d6 + d8 means rolling 2 dice with 6 sides and 1 die with 8 sides.

And so on.

- - -
## Types of Dice Rolls
 
All dice rolls can be categorized into five main categories, being: the attack roll, the damage roll, the saving throw, the attribute check and the flat check.  
The common property almost all rolls have is their need to meet a certain minimum in order to succeed. Such minimum is often called a Difficulty Class, or DC for short. A "basic DC" is the standard formula for calculating the DC for an action against another creature. The basic DC is usually defined with a skill in mind, and is equal to 10 + the creature's bonus for that skill.  

>[!example] 
>A basic Athletics (Strength) DC will be equal to 10 + the target's Strength modifier + the Target's proficiency bonus with the Athletics skill.
 
### Attack Rolls
 
Attack rolls are used by creatures to attempt to attack another creature. For the most part, they don't determine how strong an attack hits, since that is determined by damage rolls. Instead, attack rolls determine whether the attack hits in the first place. The roll is made up like so:  
_Attack Roll = d20 + attribute modifier + proficiency bonus_

- Attribute modifier - each attack roll uses one of the seven [attributes](Attribute%20Scores.md), and the corresponding attribute's modifier is added to the attack roll. Weapons use Strength, though weapons with the Finesse trait can use Dexterity instead, and spell attacks use their corresponding attribute (more information in the magic section).
- Proficiency bonus - if the creature is proficient with the weapon (in the case of weapon attacks) or with the [[Reading a Spell Entry|magic type]] (in the case of spell attacks), the creature's [proficiency bonus](Proficiency and Downtime) is added to the attack roll.

The DC of an attack roll is the [[Armor Rules|Armor Class (AC)]] of the defending creature. On a success, the attack hits, and the attacking creature proceeds to roll a damage roll.  
Attacks can also critically hit or critically miss. The default range of a critical hit is a natural 20 on the attack roll, meaning the result on the d20 is a 20. Similarly, the default range for a critical miss is a natural 1. Traits which augment that range increase the amount of numbers which result in their respective critical, such as the Lethal and Fragile traits.  
Critical hits result in doubling all damage, while critical misses result in either breakage (in the case of weapons) or exhaustion (in the case of spells).
 
### Damage Rolls
 
Damage rolls, as the name implies, determine how much damage is dealt to the defending creature or hit object. For weapon attacks, the formula to calculate damage is as follows:  
_Damage Roll = weapon's damage die + attribute modifier_

- Weapon damage dice - can be found in the [weapons](Weaponsmith.md) page. Note that different upgrades, magic items and class features might modify the weapon's damage dice.
- Attribute modifier - as with the attack roll.

For spells and other special cases, the damage dice are noted in the relevant feature's description, though it is important to remember that the spellcasting attribute modifier (for example, Intelligence for Arcana) is added to the damage roll of spell attacks, just as Strength would be added to weapon damage rolls. Any item bonuses to a creature's spellcasting modifier are also added to spell damage rolls.  
Damage is dealt according to the rules listed in the [Damage and Death](Damage%20and%20Death.md) page.
 
### Saving Throws
 
Saving throws are used as defensive rolls against different effects, from dodging traps to resisting mental spell effects, and everything in between. Calculating a saving throw is as follows:  
_Saving Throw = d20 + attribute modifier + proficiency bonus_

- Attribute modifier - according to the type of saving throw required, you add one of the following attribute bonuses:
    - Resilience - highest among Strength or Constitution
    - Initiative - highest among Dexterity or Wisdom
    - Wits - highest among Intelligence or Charisma
    - Willpower - Willpower
    - Flat saving throws - no attribute modifier
- Proficiency bonus - all creatures add their proficiency bonus to saving throws. However, if they are proficient in a particular save (such as from downtime training or class features), they add twice their proficiency bonus instead. 

>[!example]
> The [leshy](Leshy.md) race gets a racial feature which grants them proficiency with Resilience saving throws.
 
### Ability Checks
 
Ability checks are used both in combat and out of combat to determine the success of actions not covered by any of the previous rolls. They usually involve the use of skill and tool proficiencies, such as climbing a tree using an Athletics (Strength) check, discerning a creature's motive using an Insight (Wisdom) check, etc. Calculating ability checks is done using the following formula:  
_Ability Checks = d20 + attribute modifier + proficiency bonus_

- Attribute modifier - ability checks correspond to a certain attribute modifier, according to the roll.
- Proficiency bonus - if the check is not a normal ability check (for example, a Dexterity check), a skill or tool is noted in the requirement for the check, with the corresponding attribute modifier in parentheses. 

>[!example]
>An Insight (Wisdom) check would use the Insight skill with the Wisdom attribute. In this case, the creature's proficiency bonus is added according to their [proficiency level](Proficiency and Downtime) in that specific skill.

The DC for an ability check is either noted in whatever required the check (for example, an opposing saving throw), or determined by the game master. In the case of a tie in opposing checks, the "attacker" wins.

>[!example] Examples
>Deception is usually thought of as more offensive than Insight, and Perception more offensive than Stealth.
 
### Flat Checks
 
Flat checks are rarely used, and mostly correspond to pure luck, since they use no modifiers to be calculated:  
_Flat Check = d20_
   
- - -
## Reading the Situation
 
A lot of times, calling out a DC for a roll is not as simple as first thought of: the scene might contain a lot of variables the system did not specify, from [cover](Cover.md) to creatures being [prone](Conditions.md). While raising or lowering the DC for a task might be a solution for some uses, sometimes a different approach is used, in the form of advantage and disadvantage.
 
Both terms are used to determine whether a side has a significant lead on the other - for example, an attacker standing tall above a prone creature should surely have advantage on their attack roll, while the prone creature has disadvantage on the saving throw attempting to dodge an incoming [Blood Boil](Blood%20Boil.md) spell.
 
Advantage and disadvantage can be applied to attack rolls, saving throws and ability checks. For each advantage you have, roll another d20, and take only the highest d20 result. For each disadvantage, roll another d20, and take only the lowest d20 result. Advantages and disadvantages cancel each other out, so if you have 2 advantages and 1 disadvantage, you roll only 1 additional d20 and use the highest result.
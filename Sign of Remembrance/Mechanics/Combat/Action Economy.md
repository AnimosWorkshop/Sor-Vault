In combat-related gameplay, time is usually measured in 'rounds', a unit of time equal to 6 seconds. When combat starts, each creature relevant to the combat rolls an Initiative save. During each round, each creature takes their turn according to the initiative order, from the highest to the lowest, until all creatures took their turn. Then, the creature with the highest initiative takes their turn again, and the cycle continues until combat ends.
 
During a turn, creatures may take the following moves:

- Movement
- Action
- Quick Action

And they may also make another type of move at any time before the start of their turn:

- Reactions
 
We will now go over what each of those moves means.
 
## Movement
 
The creature may move up to its movement speed. The total number of feet the creature may move is according to its highest movement speed type, and whenever it moves using its movement, movement speed of the matching type is expended. When a creature moves in what is called "difficult terrain", twice the movement speed is expended for each foot it moves. 

>[!note] 
>All races and creatures have a base movement speed specified in their page. This value is used as a baseline, and is mentioned in different actions and features.

>[!example] 
>A creature with the following movement speeds: 20' walking, 50' flying, 20' burrowing, can move in the following example combinations:
>- walk 20', burrow 20', fly 10'
>- walk 20', fly 30'
>- fly 30', burrow 20'
>- walk 10', fly 10', burrow 15', fly 15'

The movement speeds can be expended in any order, and not all the movement speed must be expended in the same turn.  

It is important to mention that movement can be used before and after other actions, and not all of it has to be expended at the same time - meaning that a creature with a 30' walking speed can walk 15', then use its action, then walk 15' more.
### Movement Speed Types

- Walking - the creature can move on solid ground without issue, and on top of semi-solid ground as if it were difficult terrain.
- Flying - the creature can move freely mid-air without issue.
    - Default - The creature uses minimal effort to fly, and only [[Damage and Death#Fall Damage|falls]] to the ground when it wishes to or when it becomes unconscious or its movement speed drops to 0.
    - (Levitating) - The creature can't be made to fall without it willing to.
    - (Active) - The creature falls to the ground in the end of its turn. It may attempt an Acrobatics (Dexterity) check to not fall prone.
- Burrowing - the creature may move through solid ground without issue, and through semi-solid ground as if it were difficult terrain.
- Climbing - the creature may move on vertical spaces without issue, unless they are slippery or have no gripping points.
- Swimming - the creature may move through liquids without issue, and through viscous liquids as if they were difficult terrain.
 
Also, a creature might have the 'phasing' property, meaning that it can go through objects as it wills to as if they were difficult terrain. The creature may use any solid object as floor in that case if it goes through the ground, but no force is exerted on whatever the creature steps. If it ends its turn inside an object or creature, it loses 1d6 hit points.
 
### Jumping

Long jump takes a running-start of at least 10' to perform, and takes movement equal to the distance you are planning to jump. In addition, when you jump you must succeed on an Athletics (Strength) check with a DC equal to the number of feet you are attempting to jump. On a fail, you fail your jump, only advancing a number of feet equal to the result of your skill check.

### Opportunity Attacks

In order to introduce this concept, consider the following drawing. The black lines represent the grid, and red "C" a creature's position, and the blue and green "E"s possible positions for that creature's enemies, who stand on opposite sides from him. A creature in this position is considered _flanked_.
 ![[Pasted image 20250904140501.png]]
When a creature moves a flanked position, they may choose one enemy to be protected from. All other creatures may use a [[#Reactions|reaction]] to try to make a weapon attack them while they are moving.
A creature may only attack each other creature once during a round.
 - - -
## Action
 
Actions are things a creature can do, which take the majority of its turn. These are most often what creatures rely on in order to make their time well-spent, both in combat (as most moves require 1 action) and outside of combat. Moves which take more than 1 round require the creature to invest 1 action during each of those rounds, until the move is finished.

Actions will usually be most things a creature improvises, from picking up items to hurling them, be focused and convincing in a conversation and casting the majority of spells. Therefore, a difficulty arises in specifying all the actions a creature may take. The following list contains many of the combat-effective actions.

>[!note]
>You may use an action to perform a [[#Quick Action|quick action]], although for the most part it is not turn-efficient.
 
- **Attack** - the creature makes 1 weapon attack against another creature or object. The creature makes an attack roll. If the result is equal to or higher than the defending creature's AC, the attack hits, allowing the attacking creature to make a damage roll.
	Readied light weapons (such as a sheathed shortsword) can be drawn and used to attack using 1 Attack action.
	In addition, a weapon attack can be performed nonlethaly. This subject is elaborated on in the [[Weaponsmith|weaponsmith]] page. ^43d1b5
- **Brawl** - while using the attack action, you may replace the attack with performing one of the following actions, all of which are considered brawl actions: ^b70e3f
    - **Grapple** - By using one hand, you attempt to get a hold of a creature up to 1 size larger than you. The target must make a Resilience save against your basic Athletics (Strength) DC. On a failed save:
	    - The target is [[Brawling Conditions#Grappled|grappled]] until they break free.
	    - Grappling requires you to use a hand to maintain your hold. You may still use it to hold items, but cannot use these items other than a [[Armorer#Shields|shield]] with the [[Weapon Rules#Glove|glove trait]], which still provides its AC bonus for creatures other than the grappled. 
		
		The escape DC is the same of your grapple DC. Attempting to grapple a prone creature turns it into the Topple action instead.
    - **Shove** - A creature within 5' of you must make a Resilience saving throw against your basic Athletics (Strength) DC, with a -2 penalty if they are mounted. On a failed save, they are either shoved up to 10' in a direction of your choice or fall prone. Shoving a creature into a wall deals 1d4 kinetic damage for each 5' the target was moved. This is considered unarmed strike damage, and is enhanced by sources such as [[Sentinel|sentinel features]] and the [[Weaponsmith#Special Weapons|enchanted wrappings]]. ^5d5dd0
    - **Topple** - An unmounted creature within 5' of you must make a Resilience saving throw against your basic Athletics (Strength) DC. The DC is increased by 2 if you are of their size category or larger than them. On a failed save, they become [[Brawling Conditions#Toppled|toppled]]. The escape DC is the same of your topple DC.
    - **Restrain** - A creature physically grappled or toppled by you must make a Resilience saving throw against your basic Athletics (Strength) DC. On a failed save, they are also [[Brawling Conditions#Restrained|restrained]] in addition to the other condition. When the other condition ends, the restraining does too.
- **Bluff** - you confuse an enemy trying to attack you in order to soften a blow. The next time a creature within 30' attacks you, they must make a Wits saving throw against your basic Deception (Charisma) DC. On a failure, the damage they deal with their attack is reduced by your Deception (Charisma) modifier. The Bluff action must be the last thing you do on your turn to work.
- **Dash** - the creature can move additional distance equal to its base movement speeds. ^f8a635
- **Disorient** - you attempt to throw a creature off-balance using your immediate surroundings, such as kicking dirt into your opponent's eyes, knocking a nearby branch towards their face, etc. The target creature within 5' must make an Initiative saving throw against your basic Sleight of Hand (Dexterity) DC or against your basic Deception (Charisma) DC. On a fail, they are [[Conditions#Pacified|pacified]] 1 until the end of their next turn, or pacified 2 if you have a free hand. ^1e684d
- **Hide** - the creature makes a Stealth (Dexterity) roll. They are hidden from all creatures whose basic Perception (Wisdom) DC is lower than the roll. ^284a7e
- **Major interaction** - the creature interacts with different objects in the world within its reach. For example: ^30b3a9
    - Pick up a large object (GM's decision for what counts as a large or difficult to pick up item) or many small objects
    - Draw or stow two objects if neither are heavy
    - Switch between different items it holds if neither are heavy
    - Draw or stow a heavy item
    - Search a large inventory for an item and draw it
    - Apply a [[Alchemist#Substances|substance]] to a weapon a willing creature holds
- **Prepare** - the creature defines a specific action it will take if a specific condition is met until the start of its next turn. When the condition is met, the creature may use their reaction (will be expanded upon later) to perform the action, using the previous reaction DC used, meaning that if no reactions were yet used the DC is 0, if one reaction was used the DC is 10, and so on, and the reaction DC does not rise by performing the action. If the action was performed, the creature may not use it again, as the prepared action counts as used.
- **Search** - the creature makes a Perception (Wisdom), Investigation (Intelligence), Nature (Intelligence) or Sorcery (Wisdom) roll, and gets information according to it: ^3d44e8
    - Perception (Wisdom) - see objects and creatures, etc. Each [[Conditions#Hidden|hidden]] creature with basic Stealth (Dexterity) DC lower than your roll is not hidden from you.
    - Investigation (Intelligence) - understand the form of an item or its purpose, find clues, etc.
    - Sorcery (Wisdom) - sense the quality of magic affecting the area around you. Taking base [[Class Summary#Caster Classes|caster classes]] grants features which extend what is possible to sense using this action.
- **Medicate** - the creature attempts to aid a [[Damage and Death#Death|fallen creature]] in order to pull them away from death's door. Roll either a Medicine (Intelligence) or a Medicine (Wisdom) check, according to the GM's decision. On DC 15, the fallen creature gets 1 successful death save. On DC 25, the creature gets 2 successful death saves. ^79c113
- **Wake up** - any unconscious creatures above 0 hit points within 15' wake up, unless what put them under that condition specifies otherwise. ^c3c100
 - - -
## Quick Action
 
Quick actions are things a creature can do which take up little time. Their versatility is lower than that of regular actions, as time is a constraint in this case. Examples for quick actions are:
 
- **Attack** - if the creature used its action to use a [[#^30b3a9|major Interaction]] or the [[Action Economy#^941070|attack]] action using a light or medium weapon, it may use this quick action to make an attack using a different light weapon held in a different hand. The attribute modifier for the weapon isn't added to the damage roll. ^941070
- **Assess** - Make a Nature (Intelligence), a Nature (Wisdom) or an Insight (Wisdom) check. Depending on your roll, understand some facts about a creature. You understand one fact if you pass DC 10, two facts for DC 15, or three for DC 20, and so on. You can learn the following facts:^047348
    - 1 fact:
		- Creature type and race
		- Damage weakness
		- Damage resistances and immunities
    - 2 facts:
		- Current health points percentage, in increments of 25%.
		- Armor class
		- Highest or lowest saving throw
	- 3 facts:
		- Items held on person for quick draw
- **Demoralize** - you taunt and scare a creature to the point of doubt. A creature within 30' that can hear you and understands a language you speak makes a Wits saving throw against your basic Intimidation (Charisma) DC or Intimidation (Strength). On a failed save, the first attack or Wits saving throw they make in their next turn is made with a penalty equal to third of your Intimidation modifier. A creature can't be demoralized twice at the same time. ^362ce9
- **Disengage** - you attempt to flee any opponent which might be waiting for an opportunity to strike you. Make an Acrobatics (Dexterity) roll. Until the end of your turn, any [[#Opportunity Attacks|opportunity attack]] roll made to hit you automatically misses if it is lower than your roll. ^665abd
- **Inspire** - you inspire courage and unity within an ally. A creature within 30' that can hear you and understands a language you talk in gets a bonus to their first attack during their next turn equal to third of your Persuasion (Charisma) or Performance (Charisma) modifier. A creature can't be inspired twice at the same time. ^9bb451
- **Minor interaction** - the creature interacts with different objects within its reach. Examples: ^359f07
    - Pick up a small object (GM's decision for what counts as a small or easy to pick up item)
    - Draw or stow an item without the Heavy property
    - Apply a [[Alchemist#Substances|substance]] to a weapon they hold
 - - -
## Reactions
 
Reactions are taken as responses to moves committed by other creatures. Each reaction has a condition which has to be met in order to take that reaction, and it occurs before the triggering move resolves. In order to take a reaction, the creature must make a Willpower save, with the DC increasing by 5 for each other reaction they use, starting at 10. If a feature requires you to use up multiple reactions, you roll against the higher DC only. The DC resets at the start of the creature's turn, and goes up after each used reaction, whether the check was successful or not. If multiple reactions can be triggered from the same condition, only one of them may be used. An example for a reaction, available for all creatures, is the [[#Opportunity Attacks|opportunity attack]].
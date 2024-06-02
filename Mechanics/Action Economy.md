In combat-related gameplay, time is usually measured in 'rounds', a unit of time equal to 6 seconds. When combat starts, each creature relevant to the combat rolls an Initiative save. During each round, each creature takes their turn according to the initiative order, from the highest to the lowest, until all creatures took their turn. Then, the creature with the highest initiative takes their turn again, and the cycle continues until combat ends.
 
During a turn, creatures may take the following moves:

- Movement
- Action
- Quick Action

And they may also make another type of move any time before the start of their turn:

- Reactions
 
We will now go over what each of those moves means:
 
## Movement
 
The creature may move up to its movement speed. The total number of feet the creature may move is according to its highest movement speed type, and whenever it moves using its movement, movement speed of the matching type is expended. When a creature moves in what is called "difficult terrain", twice the movement speed is expended for each foot it moves.  
For example, a creature with the following movement speeds: 20' walking, 50' flying, 20' burrowing, can move in the following example combinations:

- walk 20', burrow 20', fly 10'
- walk 20', fly 30'
- fly 30', burrow 20'
- walk 10', fly 10', burrow 15', fly 15'

The movement speeds can be expended in any order, and not all the movement speed must be expended in the same turn.  
It is important to mention that movement can be used before and after other actions, and not all of it has to be expended at the same time - meaning that a creature with a 30' walking speed can walk 15', then use its action, then walk 15' more.
### Movement Speed Types

- Walking - the creature can move on solid ground without issue, and on top of semi-solid ground as if it were difficult terrain.
- Flying - the creature can move freely mid-air without issue.
    
    - Default - The creature uses minimal effort to fly, and only falls to the ground when it wishes to or when it becomes unconscious or its movement speed drops to 0.
    - (Levitating) - The creature can't be made to fall without it willing to.
    - (Active) - The creature falls to the ground in the end of its turn. It may attempt an Acrobatics (Dexterity) check to not fall prone.
- Burrowing - the creature may move through solid ground without issue, and through semi-solid ground as if it were difficult terrain.
- Climbing - the creature may move on vertical spaces without issue, unless they are slippery or have no gripping points.
- Swimming - the creature may move through liquids without issue, and through viscous liquids as if they were difficult terrain.
 
Also, a creature might have the 'phasing' property, meaning that it can go through objects as it wills to as if they were difficult terrain. The creature may use any solid object as floor in that case if it goes through the ground, but no force is exerted on whatever the creature steps. If it ends its turn inside an object or creature, it loses 1d6 hit points.
 
### Jumping

Long jump takes a running-start of at least 10' to perform, and takes movement equal to the distance you are planning to jump. In addition, when you jump you must succeed on an Athletics (Strength) check with a DC equal to the number of feet you are attempting to jump. On a fail, you fail your jump, only advancing a number of feet equal to the result of your skill check.
 - - -
## Action
 
Actions are things a creature can do, which take the majority of its turn. These are most often what creatures rely on in order to make their time well-spent, both in combat (as most moves require 1 action) and outside of combat. Moves which take more than 1 round require the creature to invest 1 action during each of those rounds, until the move is finished.  
Actions will usually be most things a creature improvises, from picking up items to hurling them, be focused and convincing in a conversation and casting the majority of spells. Therefore, a difficulty arises in specifying all the actions a creature may take. The following list contains many of the combat-effective actions:
 
- Attack - the creature makes 1 weapon attack against another creature or object. The creature makes an attack roll. If the result is equal to or higher than the defending creature's AC, the attack hits, allowing the attacking creature to make a damage roll.
	Readied light weapons (such as a sheathed shortsword) can be drawn and used to attack using 1 Attack action.
	In addition, a weapon attack can be performed nonlethaly. This subject is elaborated on in the [weapons](Weapons.md) page.
- Brawl - you may perform one of the following actions, all of which are considered brawl actions:
    - Grapple - You use one hand, and a creature of your size or 1 higher must make a Strength saving throw against your basic Athletics (Strength) DC. On a failed save, they are [grappled](Conditions.md) until they break free. Grappling requires you to use an arm to maintain it. That arm can still hold items, but usually cannot use them (such as weapons), except for shields with the Glove trait, which still provide their AC bonus against creatures you do not grapple. The escape DC is the same of your grapple DC.
		Attempting to grappling a prone creature turns into the Topple action instead.
    - Shove - A creature within 5' of you must make a Strength saving throw against your basic Athletics (Strength) DC, with a -2 penalty if they are mounted. On a failed save, they are either shoved 5' to a direction of your choice or fall prone.
    - Topple - An unmounted creature within 5' of you must make a Resilience saving throw against your basic Athletics (Strength) DC. The DC is increased by 2 if you are of their size category or larger than them. On a failed save, they become [toppled](Conditions.md). The escape DC is the same of your topple DC.
    - Restrain - A creature grappled or toppled by you must make a Resilience saving throw against your basic Athletics (Strength) DC. On a failed save, they are also [restrained](Conditions.md). The conditions to ending the restraining are the same as to ending the grappling or toppling.
- Bluff - you confuse an enemy trying to attack you in order to soften a blow. The next time a creature within 30' attacks you, they must make a Wits saving throw against your basic Deception (Charisma) DC. On a failure, the damage they deal with their attack is reduced by your Deception (Charisma) modifier. The Bluff action must be the last thing you do on your turn to work.
- Dash - the creature can move additional distance equal to its base movement speeds.
- Disengage - the creature may escape another creature's reach without provoking attacks of opportunity for the rest of the turn.
- Disorient - you attempt to throw a creature off-balance using your immediate surroundings, such as kicking dirt into your opponent's eyes, knocking a nearby branch towards their face, etc. The target creature within 5' must make an Initiative saving throw against your basic Sleight of Hand (Dexterity) DC or against your basic Deception (Charisma) DC. On a fail, they are [pacified](Conditions.md) 1 until the end of their next turn, or pacified 2 if you have a free hand.
- Hide - the creature makes a Stealth (Dexterity) roll. They are hidden from all creatures whose basic Perception (Wisdom) DC is lower than the roll.
- Major Interaction - the creature interacts with different objects in the world within its reach. For example:
    - Pick up a large object (GM's decision for what counts as a large or difficult to pick up item) or many small objects
    - Draw or stow two objects if neither are heavy
    - Switch between different items it holds if neither are heavy
    - Draw or stow a heavy item
    - Search a large inventory for an item and draw it
- Prepare - the creature defines a specific action it will take if a specific condition is met until the start of its next turn. When the condition is met, the creature may use their reaction (will be expanded upon later) to perform the action, using the previous reaction DC used, meaning that if no reactions were yet used the DC is 0, if one reaction was used the DC is 10, and so on, and the reaction DC does not rise by performing the action. If the action was performed, the creature may not use it again, as the prepared action counts as used.
- Search - the creature makes a Perception (Wisdom), Investigation (Intelligence), Nature (Intelligence) or Sorcery (Wisdom) roll, and gets information according to it:
    - Perception (Wisdom) - see objects and creatures, etc. Each hidden creature with basic Stealth (Dexterity) DC lower than your roll is not hidden from you.
    - Investigation (Intelligence) - understand the form of an item or its purpose, find clues, etc.
    - Sorcery (Wisdom) - sense the quality of magic affecting the area around you. Taking base caster classes ([cleric](Cleric.md), [druid](Druid.md), [mentalist](Mentalist.md), [wizard](Wizard.md)) grants features which extend what is possible to sense using this action.
- Medicate - the creature attempts to aid a fallen creature in order to pull them away from death's door. Roll either a Medicine (Intelligence) or a Medicine (Wisdom) check, according to the GM's decision. On DC 10, the fallen creature makes their next Death check with advantage. On DC 20, the fallen creature gets a death success instead.
- Wake Up - any unconscious creatures above 0 hit points within 15' wake up, unless what put them under that condition specifies otherwise.
 - - -
## Quick Action
 
Quick actions are things a creature can do which take up little time. Their versatility is lower than that of regular actions, as time is a constraint in this case. Quick actions may also be used if you take your action to use them. Examples for quick actions are:
 
- Attack - if the creature used its action to use the Major Interaction action or the Attack action using a weapon without the Heavy property, it may use this quick action to make an attack using a different light weapon held in a different hand. The ability modifier for the weapon isn't added to the damage roll.
- Assess - Make a Nature (Intelligence), a Nature (Wisdom) or an Insight (Wisdom) check. Depending on your roll, understand some facts about a creature. You understand one fact if you pass DC 10, two facts for DC 15, or three for DC 20, and so on. You can learn the following facts:
    - Creature type and race
    - Current health points percentage (out of its maximum)
    - Damage weaknesses
    - Damage resistances and immunities
    - Highest attribute
    - Lowest attribute
- Demoralize - you taunt and scare a creature to the point of doubt. A creature within 30' that can hear you and understands a language you speak makes a Wits saving throw against your basic Intimidation (Charisma) DC or Intimidation (Strength). On a failed save, the first attack or Wits saving throw they make in their next turn is made with a penalty equal to third of your Intimidation modifier. A creature can't be demoralized twice at the same time.
- Inspire - you inspire courage and unity within an ally. A creature within 30' that can hear you and understands a language you talk in gets a bonus to their first attack during their next turn equal to third of your Performance (Charisma) modifier. A creature can't be inspired twice at the same time.
- Minor interaction - the creature interacts with different objects within its reach. Examples:
    - Pick up a small object (GM's decision for what counts as a small or easy to pick up item)
    - Draw or stow an item without the Heavy property
 - - -
## Reactions
 
Reactions are taken as responses to moves committed by other creatures. Each reaction has a condition which has to be met in order to take that reaction, and it occurs before the triggering move resolves. In order to take a reaction, the creature must make a Willpower save, with the DC increasing by 5 for each other reaction they use, starting at 10. If a feature requires you to use up multiple reactions, you roll against the higher DC only. The DC resets at the start of the creature's turn, and goes up after each used reaction, whether the check was successful or not. If multiple reactions can be triggered from the same condition, only one of them may be used. An example for a reaction available for all creatures is:
 
- Attack of Opportunity - when a creature willingly moves away from you out of reach (but doesn't teleport away), you may attempt a single weapon attack against them right before they move out. Each creature may use only one attack of opportunity against each other creature during a turn, meaning that a creature leaving and entering another creature's range multiple times during the same turn is safe from multiple attacks of opportunity.
	On a critical hit, the creature stops, and may not use their normal movement to move during that turn anymore.
>Note: This applies to a single turn, not a single round.
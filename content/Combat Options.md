---
title: Combat Options
---

In this chapter, you will find the new actions and options a character can take
during combat.

![[./assets/cover3.png|400]]

> *(credits: Vermis*)

Quick Reference
- [[Combat Options#Actions]]
	- [[Combat Options#Attacking]]
	- [[Combat Options#Combat insight]]
	- [[Combat Options#Prayer]]
	- [[Combat Options#Prayer]]
	- [[Combat Options#Strike fear]]
- [[Combat Options#Bonus Actions]]
	- [[Combat Options#Feint]]
- [[Combat Options#Reactions]]
	- [[Combat Options#Parry]]
	- [[Combat Options#Dodge]]
# Actions

## Attacking

Within this expansion, an entirely new system for attacks is included. It
replaces the attack roll versus AC system in D&D 5th edition.

**After** reading the rules detailed below, check out the [Hit Visualizer](https://kingless-hit-visualizer.vercel.app/).

### Weak Spots

All creatures have a weak spot, be it a gap within the plate armor, a spot of
soft tissue or a blind spot which they cannot defend. In order to damage a
creature, an attacker must tactically aim for the weak spot and, if they hit
close enough, they succeed in hurting said creature. 

The weak spot is simply a number between 1 and, including, 20.  Creatures do
**not** automatically know each other's weak spots. 

#### Determining the weak spots

##### For monsters

For any monster, the DM can choose any weak spot value. Multiple monsters of the
same type can have different weak spots. 

Additionally, the DM can give a monster multiple weak spots. This can confuse
the players but also makes the monster easier to hit.

##### For players

Players can determine their weak spot by rolling a `d20`.  Players can choose to
reroll this value whenever they level up.

### Armor Window

The armor window of a creature determines how close an attack must be to the
weak spot in order to damage the creature.

**Armor Window = 20 - AC** 

The armor window is then "placed" in the middle of the creature's weak spot. For
example, a creature with a weak spot at 9 and an armor window of 6 will take
damage from rolls that fall into the range 6 and 12 (3 to the left of 9 and 3 to
the right). 

![[./assets/graph1.png]]

Any hit that falls between 8 and 12 (inclusive) is considered a hit.

### Hits and Aiming

To determine the hit score, roll a d20. Do not add the usual modifiers to the
roll. Instead, add or subtract up to half of the modifier value. This means that
for a `d20+5`, you can add or subtract the values 0, 1, and 2. For example, if
you roll a 12, you can choose from 10, 11, 12, 13, and 14. Attacks that fall
within the armor window around the weak spot are considered a hit. This
introduces the concept of aiming, choosing the right value to get as close as
possible to the creature's weak spot. The players will have to narrow down the
attack window and keep mental notes of each creature's weak spot. Adding or
subtracting to the roll can be analogous to  "aiming high" or "aiming low",
respectively. Additionally, players are encouraged to cooperate and strike in
different places as to cover as much ground. Thus, the fight becomes a game of
investigation, trying to find the adversary's weak spot.

**Tip** Since the DM knows the players' weak spots ahead of time, it's
recommended that they roll for the hit modifier when rolling attacks. Of course,
there isn't a dice for every modifier. They can also cycle through possible hit
values. If a monster hits, the DM can choose whether the monster remembers the
attack window based on the monster's wisdom or intelligence and the difficulty
of the encounter.

### Advantage and Disadvantage changes

Since within the aiming system higher isn't always better and advantage and disadvantage aren't flat modifiers, they act different in this context.

**Disadvantage**: On an attack roll made with disadvantage, the attacker rolls
one dice and can only add or subtract the maximum value of their attack modifier
(e.g. for a `d20+5` they can only take the `d20+5` or `d20-5`).

**Advantage**: On an attack roll made with advantage, the attacker rolls two die
and can choose whichever one they like.

**These changes only apply within the context of hit rolls**

### Critical hits

Whenever an attack roll, without adding any modifier, equals the score of the
attacked creature's weak spot, a critical hit happens. In this case, the player
is not given the option of adding or subtracting anything from the roll and the
attack automatically succeeds.  

For more information, see [[New Effects#Critical Hits]].

## Stance Actions

Some weapons allow for special actions. These actions consume **stance slots**
(similar to spell slots). You have a number stance slots equal to your level.
Stance slots replenish after long rests. At 0 stance slots, using stance actions
puts you on the backfoot: for 2 turns, any hit made against you is a critical
hit.

Stance actions **do not** work with the 'Extra Attack' feature, or any feature that
requires an attack to be made.

## Combat insight

A combatant can perform an insight check to determine the armor window of a
creature. The DC is the creature's armor class. On a failed check, the attacker
gains no insight. On a successful check, they realize whether the weak spot is
lower or higher compared to the most recent attack made against the creature. If
the creature hasn't been attacked yet, the combatant gains other useful
Information about the target.

## Prayer

A combatant can pray to the divinity to receive aid in battle. They make a
religion check and choose one of the following effects:
- an ally is blessed and can use the score of the religion check instead of rolling a saving throw. does not stack.
- an ally is cured of a minor debuff inflicted by a failed saving throw. The DC of the check is equal to the DC of the failed save.
- an ally is cured of Frightened. DC is equal to that of the original save.
- an ally can ignore 2 levels of [[New Effects#Fatigue]] for 1 minute. does not stack.
	- DC: **15**

## Occult insight

A combatant can recall information about the arcane and occult during a battle. They make an arcana check and choose one of the following effects:
- them or an ally become immune to poison for one round
	- DC: **14**
- they gain useful information about another creature's spellcasting ability
	- DC: 10 + that creature's arcana score
- a creature of their choice uninitiated in magic gains a level of [[New Effects#Insanity]] (once per creature)
	- DC: the creature's passive wisdom score
- a creature of their choice receives disadvantage on a spell saving throw
	-  DC: the creature's passive wisdom score
- them or an ally recover a spell slot (once per short rest)
	- DC: **15**
- sacrifice a willing ally. they die, and their current health is transferred to someone else. On a failed check, the ally dies and the transfer fails.
	- DC: **5**

## Strike fear

A combatant can attempt to frighten an enemy. They roll an intimidation check against a DC equal to 10 + the level difference (at least one) + the creature's charisma modifier. 

For example, level 12 fighter can attempt to intimidate a lich (CR 21). The DC
is 10 + (21 - 12) + 3 (the lich's charisma) = 22

## Parry

*requirement: holding a weapon or shield you are proficient with*

A combatant can attempt to parry an incoming attack (including spells) or
anything that requires a saving throw as long as it's some sort of external
effect (eg. inflict wounds or mind spike cannot be parried). After taking the
parry action on their turn, the next time they are attacked they make an attack
roll (modifier is +5 if using a shield).  They must match the number of the
opponent's roll exactly. 

- **On a hit**, the parry succeeds and they can attack the creature immediately
(weapon range still applies) with advantage as part of the same reaction and any
hit counts as a critical hit. 
- **On a miss**, all nearby opponents can make attacks of opportunity against
them.

Another combatant can only know a parry is being
prepared by using [[#Combat insight]]. The parry cannot be canceled after it is initiated.

## Dodge

A combatant can prepare to dodge an incoming attack, shifting their weak spot to
the left or right by an amount equal to their proficiency bonus **the next time
they are attacked**. This means the direction is determined on the turn the
dodge is initiated and the weak spot remains changed until the beginning of the
combatant's next turn. The creature cannot use any movement on the turn the
*dodge* action is used. 

Additionally, while the effect of the dodge is active, the first DEX save a
creature must roll succeeds automatically.

Another combatant can only know a dodge is being
prepared by using [[#Combat insight]]. The dodge cannot be canceled or altered
in any way after it is initiated.

This mechanic is similar to turn based RPGs 'guard' mechanic.

<details>
<summary> DM TIP </summary>
Always determine what an NPC combatant does on their turn the turn prior and
lock that in to a high degree (eg. if a monster was going to use an attack that
demands a DEX save, do not change your mind after a player prepares a dodge, but
if for eg. a trap is detonated that might harm the monster, they would react).
In short, don't do metagaming.
</details>

# Bonus Actions

## Feint

A combatant can expend a bonus action to feint an attack. As a result of the
feint, the attack is canceled, and any parry or dodge made against the attack
fails. 

**Tip** Use this to waste enemy parries or dodges.


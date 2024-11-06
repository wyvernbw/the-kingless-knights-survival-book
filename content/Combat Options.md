---
title: Combat Options
---

In this chapter, you will find the new actions and options a character can take
during combat.

# Actions

## Attacking

Within this expansion, an entirely new system for attacks is included. It
replaces the attack roll versus AC system in D&D 5th edition.

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

Critical hits are more devastating than the base game, doubling the damage die
and taking the max value (`2d6 -> 4d6 -> 4 * 6 = 24)` and adding damage
modifiers once.

For additional effects of critical hits, see [[Combat Changes]].

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
- an ally is blessed and can use the score of the religion check instead of rolling a saving throw.
- an ally is cured of a minor debuff inflicted by a failed saving throw. The DC of the check is equal to the DC of the failed save.
- an ally is cured of Frightened or Madness.

## Occult insight

A combatant can recall information about the arcane and occult during a battle. They make an arcana check and choose one of the following effects:
- them or an ally become immune to poison for one round
- they gain useful information about another creature's spellcasting ability
- a creature of their choice uninitiated in magic gains a level of Madness (once per creature)
- a creature of their choice receives disadvantage on a spell saving throw (once per creature)
- them or an ally recover a spell slot (once per long rest)

## Strike fear

A combatant can attempt to frighten an enemy. They roll an intimidation check against a DC equal to 10 + the level difference (at least one) + the creature's charisma modifier. 

For example, level 12 fighter can attempt to intimidate a lich (CR 21). The DC
is 10 + (21 - 12) + 3 (the lich's charisma) = 22

# Bonus Actions

## Feint

A combatant can expend a bonus action to feint an attack. This must be done
**before** any reactions are triggered. As a result of the feint, the attack is
canceled, and any parry made against the attack fails. 

**Tip** It's recommended for players to declare they want to feint as they
attack, to avoid early reactions canceling their feint. 

**Tip** Use this to bait enemy parries or dodges.

# Reactions

## Parry

A combatant can attempt to parry an incoming attack. They must decide whether to
parry or not before the attack roll is made. If they have a weapon they are
proficient with in hand, they can add their proficiency bonus to their AC,
shrinking their attack window. Note that the attacker is unaware of the
intention to parry their attack until the hit is made. If the attack would have
normally hit, but misses because of the parry, the combatant can attack
immediately with advantage and any hit counts as a critical hit. If the parry
fails, the next attack against the combatant has advantage.

**Tip** For Monsters, it's recommended to keep the parry ability use to a
minimum. DMs can use it as a gimmick to take the players by surprise but should
balance the monsters accordingly. 

## Dodge

A combatant can dodge an incoming attack, shifting their weak spot to the left
or right by half their proficiency bonus. The dodge must be initiated **before**
the attack roll is made. The dodge also leaves the creature on unstable footing,
gaining disadvantage on the next dexterity saving throw. 
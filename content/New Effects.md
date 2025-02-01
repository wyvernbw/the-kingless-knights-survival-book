---
title: New Effects
---

This ruleset comes with a few new effects and conditions, as well as changes to
the r.a.w. ones.

- [[New Effects#Critical Hits]]
- [[New Effects#Fatigue]]
- [[New Effects#Insanity]]
	- [[New Effects#Common effects of insanity]]
- 

## Critical Hits

Critical hits now happen when a an unmodified roll lands on the enemy's [[Combat Options#Weak Spots|weak spot]], instead of the usual 20. 

On a critical hit, you double the dice and take the max value (e.g. `2d8`
becomes `4d8` so you take `4*8 = 32`). Additionally, critical hits inflict
permanent wounds based on where the weak spot is and grant one level of
insanity and one level of fatigue.

## Fatigue 

Fatigue is the replacement for 5e's exhaustion condition. It represents the
physical toll adventurers must pay as their bodies are pushed to their limits
over the course of long periods. If a rule in the base game consists of giving a
player one level of exhaustion, replace that with two levels of fatigue.

At each short or long rest, your fatigue level decreases by one if you spend at
least two hit die (long rests always decrease it by one level).

**Fatigue effect table**

| Fatigue | effect                                                                                                                    | description                                                               |
| ------- | ------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- |
| 1       | -1 STR                                                                                                                    | muscle aches.                                                             |
| 2       | -5 ft. move speed                                                                                                         | sore legs.                                                                |
| 3       | -2 STR                                                                                                                    | ...                                                                       |
| 4       | -1 DEX and -5 ft. move speed                                                                                              | feelings of heaviness.                                                    |
| 5       | -2 CON                                                                                                                    | weakened immune system.                                                   |
| 6       | -1 DEX and -5 ft. move speed                                                                                              | ...                                                                       |
| 7       | Spells cast always use the max level spell slot available and -2 Perception                                               | You lose your precision in channeling magic.                              |
| 8       | Unable to wear heavy armor. When wearing light armor, the DEX bonus to AC is at most 2.                                   | can barely keep your body moving.                                         |
| 9       | Disadvantage on ability checks you're not proficient in                                                                   | You can barely handle tasks that aren't already muscle memory for you.    |
| **10**  | **can hold up to 2 failed death saves instead of 3**. [[#Infection]] kills you in 2 days instead of 3.                    | Your body is nearing it's limit. Any serious wound is likely to kill you. |
| 11      | -1d4 on attack rolls                                                                                                      | Can no longer muster the strength to strike your foes.                    |
| 12      | Disadvantage on saving throws                                                                                             | Your reflexes and survival capabilities suffer greatly.                   |
| 13      | Effect of all healing halved                                                                                              | Your body can no longer be a vessel for otherworldly aid.                 |
| 14      | Whenever you use a spell that requires concentration, you must roll a DC 15 CON save or lose concentration. -2 Perception | the pain numbs your mind.                                                 |
| 15      | -2 to all stats                                                                                                           | ...                                                                       |
| 16      | -5 ft. move speed and -2 Perception                                                                                       | ...                                                                       |
| 17      | Disadvantage on all ability checks and attack rolls                                                                       | ...                                                                       |
| 18      | Damage dealt is halved                                                                                                    | You lose power in your strikes.                                           |
| 19      | -8 on all charisma ability checks except intimidation, +2 intimidation                                                    | You are a walking corpse.                                                 |
| **20**  | **Max HP halved and can hold up to 1 failed death save instead of 3**. [[#Infection]] kills you in 1 day instead of 3.    | You are at death's door.                                                  |

## Insanity

Upon witnessing incredible horrors, adventurers begin to lose their
mental capacity. This makes them battle-worn veterans but also increasingly
unhinged. They might start losing their grip on reality, be paralyzed with fear
upon seeing an old foe, or lose all cognitive function.

**Insanity levels can only be healed through [[#Bond]].**

The first time you gain a level of insanity, roll on the Insanity table to
determine the effect. Subsequent levels add stacks to this insanity.

**Tip** Feel free to extends the insanity table however you see fit.

**Insanity table**

| `d10`  | effect              |
| ------ | ------------------- |
| 1      | apathy              |
| 2      | paranoia            |
| 3      | shadowed intentions |
| 4      | obsessive tic       |
| 5      | unfamiliar faces    |
| 6      | paranoia            |
| 7      | apathy              |
| 8      | shadowed intentions |
| 9      | unfamiliar faces    |
| 10<br> | obsessive tic       |

###### Common effects of insanity:

**apathy** 

You become increasingly detached from reality and you begin to not understand
the emotions of those around you. (NOTE: all debuffs to charisma do **not**
apply to intimidation).

- 1 stack and above:
	- -1 per apathy stack on all charisma ability checks except intimidation, +1
	per apathy stack on intimidation
- 2 stacks and above:
	- disadvantage on performance checks.
	- -2 * apathy stack on all bonuses you grant to allies.
- 3 stacks and above:
	- disadvantage on persuasion checks
	- can no longer use [[#Bond]].
- 4 stacks and above:
	- receive NIHILISM:
		- temporary debuff.
		- +3 intimidation.
		- every time you take a short rest or roll a charisma ability check or save, you lose a hit dice.
		- any charisma ability check below 10 fails (regardless of modifier). If you have 0 hit die, all charisma ability checks fail.
		- can be cured if an ally spends meaningful time with you during 3 consecutive short rests or equivalent time (including one long rest).

**paranoia** 

You begin to question those around you and are convinced they are plotting
something against you. **the effects stacks beyond 4 start over from 1**.

- 1 stack and above:
	- -1 on insight and perception checks when your allies are around you, unless made against an ally.
- 2 stacks and above:
	- -2 per paranoia stacks on all bonuses you receive from allies.
- 3 stacks and above: 
	- sleeping within 60 ft. of your allies grants you a level of fatigue.
- 4 stacks and above:
	- disadvantage on all wisdom saving throws.
	- advantage on all checks against deception or persuasion.

**unfamiliar faces**

The faces in your memory become an unintelligible blur. 

- At random intervals, you roll a wisdom saving throw. On a
	failed save, you fail to tell foe and friend apart. The effect
	persists until you succeed the check. 
- **DC** is equal to 10 + the number of *unfamiliar faces* stacks twice.
- **In Combat:** If you don't interact (using combat options) with the unfamiliar
faces for 3 consecutive rows, you gain the frightened condition. Additionally,
any attack made against you succeeds automatically until the effects of
unfamiliar faces end. 
- 3 stacks and above: 
	- The effect of unfamiliar faces is guaranteed to trigger for the first attack you make or the first spell you cast. The effect lasts for one turn, and no saving throw is required. 
- 4 stacks and above:
	- Your mind goes completely blank. You can only take the attack action on your turn, or you can pass out for 8h.

**obsessive tic**

You develop a compulsion to perform a specific action (counting, arranging
items, reciting a prayer, etc.) to stave off perceived danger or misfortune.

- stack 1 and above:
	- At random intervals, you must act on your tic. You have disadvantage on all
	checks (including attacks) until you manage to do it. 
	- Your tic requires a number of actions or bonus actions equal to the number of stacks of *obsessive tic* in order to complete. You can use both an action and a bonus action in your turn to advance your tic.
	- Your weak spot becomes visible to every creature around you, until you finish your tic.
	- Completing your tic permanently changes your weak spot.
- stack 3 and above:
	- Your tic triggers whenever you fail a saving throw
- stack 4 and above:
	- A creature can remind you of your tic, forcing you to act on it. 
	- This only works twice per combat encounter.

 **Shadowed Intentions**
 
You occasionally become convinced you are a pawn of a malevolent force, with no control over your actions.

- At random intervals, you must make a Wisdom save. On a failure, you become incapacitated for 1 round, “fighting off” the influence you believe is controlling you.
- **DC** is equal to 10 + the number of *shadowed intentions* stacks twice
- 3 stacks and higher:
	- You unknowingly sabotage your party. On every short rest you either:
		- Sabotage an ally's weapon: The weapon breaks after the first attack.
		- Discard an ally's rations. 
		- Sabotage an ally's armor: -2 AC (they only realize after being attacked)
		- You alert enemies to your position. 
- 4 stacks and higher:
	- Whenever an ally becomes staggered around you, roll a DC 15 wisdom save. On a failure, attack them. If it is possible for the attack to hit based on the roll (regardless of the modifier you choose), the attack hits and counts as a critical hit.


## Bleeding

Any piercing or slashing damage inflicts bleeding. While bleeding, you take
damage based on the dice of the attack you were hit with (eg. 1d8 for 2d8, 1d6
for 3d6). Additionally, you cannot gain bleeding again unless the damage is
higher, in which case it replaces the old one. Any magical healing stops the
bleeding. Alternatively, a creature can perform a medicine check with a DC equal
to half the damage taken to staunch the bleeding (requires cloth).

## Concussion

Taking bludgeoning damage decreases your move speed by 5 feet for one round.

## Infection

You can easily get infections through unsanitary practices. If three days pass
without curing the infection, you die. Infections can only be cured by using
certain herbs (requires a medicine modifier of at least 4).

Common sources of infections include:
- staunching bleeding with a dirty cloth
- eating raw meat
- getting attacked with a weapon coated in faeces 
- stepping on a rusty nail
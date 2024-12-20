---
title: New Effects
---

This ruleset comes with a few new effects and conditions, as well as changes to
the r.a.w. ones.

- [[New Effects#Critical Hits]]
- [[New Effects#Fatigue]]
- [[New Effects#Insanity]]
	- [[New Effects#Common effects of insanity]]

##### Critical Hits

Critical hits now happen when a an unmodified roll lands on the enemy's [[Combat Options#Weak Spots|weak spot]], instead of the usual 20. 

On a critical hit, you double the dice and take the max value (e.g. `2d8`
becomes `4d8` so you take `4*8 = 32`). Additionally, critical hits inflict
permanent wounds based on where the weak spot is and grant one level of
insanity and one level of fatigue.

##### Fatigue 

Fatigue is the replacement for 5e's exhaustion condition. It represents the
physical toll adventurers must pay as their bodies are pushed to their limits
over the course of long periods. If a rule in the base game consists of giving a
player one level of exhaustion, replace that with two levels of fatigue.

At each short or long rest, your fatigue level decreases by one if you spend at
least two hit die (long rests always decrease it by one level).

**Fatigue effect table**

| Fatigue | effect                                                                                | description                                                               |
| ------- | ------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- |
| 1       | -1 STR                                                                                | muscle aches.                                                             |
| 2       | -5 ft. move speed                                                                     | sore legs.                                                                |
| 3       | -2 STR                                                                                | ...                                                                       |
| 4       | -1 DEX and -5 ft. move speed                                                          | feelings of heaviness.                                                    |
| 5       | -2 CON                                                                                | weakened immune system.                                                   |
| 6       | -1 DEX and -5 ft. move speed                                                          | ...                                                                       |
| 7       | Unable to concentrate (can't use spells that require concentration) and -2 Perception | the pain numbs your mind.                                                 |
| 8       | Unable to use the dodge reaction                                                      | can barely keep your body moving.                                         |
| 9       | Disadvantage on ability checks you're not proficient in                               | ...                                                                       |
| **10**  | **Max HP halved and can hold up to 2 failed death saves instead of 3**                | Your body is nearing it's limit. Any serious wound is likely to kill you. |
| 11      | -1d4 on attack rolls                                                                  | Can no longer muster the strength to strike your foes.                    |
| 12      | Disadvantage on saving throws                                                         | Your reflexes and survival capabilities suffer greatly.                   |
| 13      | Effect of all healing halved                                                          | Your body can no longer be a vessel for otherworldly aid.                 |
| 14      | Spells cast always use the max level spell slot available and -2 Perception           | You lose your precision in channeling magic.                              |
| 15      | -2 to all stats                                                                       | ...                                                                       |
| 16      | -5 ft. move speed and -2 Perception                                                   | ...                                                                       |
| 17      | Disadvantage on all ability checks and attack rolls                                   | ...                                                                       |
| 18      | Damage dealt is halved                                                                | ...                                                                       |
| 19      | -8 on all charisma ability checks except intimidation, +2 intimidation                | You are a walking corpse.                                                 |
| **20**  | **Max HP halved and can hold up to 1 failed death save instead of 3**                 | You are at death's door.                                                  |

##### Insanity
Upon witnessing incredible horrors, adventurers begin to lose their
mental capacity. This makes them battle-worn veterans but also increasingly
unhinged. They might start losing their grip on reality, be paralysed with fear
upon seeing an old foe, or lose all cognitive function.

**Insanity levels DO NOT regenerate, unlike Madness levels**

When you gain a level of insanity, roll a `d10` on the insanity table. Additionally, at certain levels of insanity, you gain a level of [[New Effects#Madness|Madness]].

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
	- receive NIHILISM:
		- temporary debuff.
		- +3 intimidation.
		- every time you take a short rest or roll a charisma ability check or save,
		your **max hit die count is drained by 1.** 
		- any charisma ability check below 10 fails. If you have 0 hit die, all
		charisma ability checks fail.
		- can be cured by spending time with an ally during 3 consecutive short rests or equivalent time (including one long rest).

**paranoia** 

You begin to question those around you and are convinced they are plotting
something against you.

- 1 stack and above:
	- -1 per paranoia stack on insight and perception checks when your allies are
	around you, unless made against an ally.
- 2 stacks and above:
	- -2 per paranoia stacks on all bonuses you grant to allies.
- 3 stacks and above: 
	- sleeping within 60 ft. of your allies grants you a level of fatigue.

**unfamiliar faces**

The faces in your memory become an unintelligible blur. 

- At random intervals, the creature must roll a charisma saving throw. On a
	failed save, the creature fails to tell foe and friend apart. The effect
	persists until you succeed the check. 
- **DC** is equal to 10 + the number of *unfamiliar faces* stacks twice.
- **In Combat:** If you don't interact (using combat options) with the unfamiliar
faces for 3 consecutive rows, you gain the frightened condition. Additionally,
any attack made against you succeeds automatically until the effects of
unfamiliar faces end. 

**obsessive tic**

You develop a compulsion to perform a specific action (counting, arranging
items, reciting a prayer, etc.) to stave off perceived danger or misfortune.

- At random intervals, you must act on your tic. You have disadvantage on all
checks (including attacks) until you manage to do it.
- Your tic takes turns equal to the stacks of *obsessive tic*, time in which your
weak spot becomes visible to all creatures around you.
- Completing your tic permanently changes your weak spot.

 **Shadowed Intentions**
 
You occasionally become convinced you are a pawn of a malevolent force, with no control over your actions.

- At random intervals, such as after taking damage, you must make a Wisdom save.
On a failure, you become incapacitated for 1 round, “fighting off” the influence
you believe is controlling you.
- **DC** is equal to 10 + the number of *shadowed intentions* stacks twice
- 3 stacks and higher:
	- You unknowingly sabotage your party. On every short rest you either:
		- Sabotage an ally's weapon: The weapon breaks after the first attack.
		- Discard an ally's rations. 
		- Sabotage an ally's armor: -2 AC (they only realize after being attacked)
		- You alert enemies to your position. 

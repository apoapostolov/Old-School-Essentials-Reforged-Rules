# Wrestling

Wrestling is the oldest combat art. It is older than the sword, older than
the spear, older than the walled town. When blades are barred, when the law
forbids blood, when you need a prisoner breathing, or when a monster closes
past your spear, men reach for each other. This subsystem turns the single
grapple roll of the Weapon Mastery Wrestling track into a complete
close-combat game: positions, exhaustion, pins, and the ugly tricks that end
fights quietly.

It does not replace the Wrestling track under Weapon Mastery (see Weapon
Mastery). It builds the procedures around it: what a hold is, how it deepens,
how fighters tire, and how the fight ends.

## How a Hold Works

A hold begins with a Wrestling attack. Roll to hit as normal against the
target's AC. Armour counts, because you are grabbing flesh, cloth, and
hardware, and armour gives you less to grab. On a hit, the target is _held_:

- Cannot move from its space.
- -2 AC against creatures other than the grappler.
- -4 to hit anything.

The grappler cannot use a weapon while maintaining the hold, but may use
Wrestling techniques (see Techniques below). This is the base state. Every
rule in this subsystem hangs off it.

### Escaping a Hold

Escape is an opposed roll-under Strength check. Both fighters roll d20 equal
or under their STR. Compare margins of success:

- Both fail: stalemate, the hold holds.
- One succeeds: that side wins.
- Both succeed: the wider margin wins (lower roll relative to the stat).
- Natural 1 is a critical success and auto-wins for that side.

Escaping takes the escaping fighter's action for the round. A held fighter
may attempt to escape once per round, or may fight back with a weapon
subject to the weapon rules below.

> Design note: opposed roll-under Strength keeps every level honest. Hit
> points grow with level; Strength does not. A 9th-level fighter can hold a
> 1st-level thief as easily as a 1st-level fighter can. Wrestling is the one
> combat art where the rookie can be dangerous, and that is correct.

## Positions

A hold is not a single grip. It moves through three positions. Position is
not rolled separately; it is the outcome of the techniques the fighters
choose.

| Position | Who stands | Who has the edge | Effect |
| --- | --- | --- | --- |
| Clinch | Both | Neither | Neutral grips. Both fighters use techniques at no penalty. |
| Dominant | Attacker | Attacker | Attacker controls the target (behind them, arm trapped, weight over the hips). The target is at -2 to its escape checks and cannot use two-handed weapons. The attacker may use Pin, Throw, Joint Lock, Submission, and Choke Hold. |
| Ground | Neither | Fighter on top | Both fighters are down. The fighter on top is dominant for ground techniques (Pin, Joint Lock, Submission, Choke Hold, strikes). The fighter underneath is at -2 to hit and escapes through the pin initiative. |

The Clinch is where every hold starts. Dominant and Ground are advantages you
earn. A grapple that stays in the Clinch is a fight nobody is winning.

> Design note: three positions, not a ladder of nine. Old-school combat is
> decided by the fighter's choice and the die, not by a flowchart. Clinch,
> Dominant, Ground covers every grip a real fight reaches; anything finer is
> flavour text on top of the same modifiers.

## The Exhaustion Pool

Wrestling is exhausting, and exhaustion is how wrestles end. Subdual damage
from holds does not accumulate against hit points. It accumulates in a
separate pool.

- Pool capacity equals the fighter's _current_ Constitution score. If CON
  drops, capacity drops with it.
- When the pool fills, the fighter gains one exhaustion level and the pool
  resets to 0.
- Subdual damage never causes Constitution loss. The pool and the Dropping
  to 0 HP rule interact only through capacity, never through the death
  spiral.

| Exhaustion | Initiative | Escape hold checks | Movement | Attack | AC | Other |
| --- | --- | --- | --- | --- | --- | --- |
| Level 1 | -1 | -2 | Cannot run | - | - | - |
| Level 2 | -2 | -4 | Speed halved | -2 | - | - |
| Level 3 | -3 | -6 | Falls prone | - | -2 | Unconscious 1d4 turns |

The order of penalties is deliberate. Resistance breaks first: the escape
penalty is the first symptom. Then mobility: the initiative penalty is combat
mobility. Then offense and defense. Then the fight ends.

Recovery: one turn of complete rest clears one exhaustion level and empties
the pool. A fighter at Level 3 wakes in 1d4 turns and is at Level 2, not
Level 0. Exhaustion is a ladder you climb down, one rung at a time.

> Design note: the pool keys to Constitution because CON 15 is CON 15 at
> every level, while hit points inflate with level. A CON-keyed pool keeps
> wrestling decisive at 1st level and at 14th. The shrinking capacity also
> synergizes with the Dropping to 0 HP rule: a damaged fighter tires faster,
> and a tired fighter fights worse, without ever doubling up on CON loss.

## The Pin Initiative

A hold is its own initiative event. It does not ride on the normal turn
order. Each round that a hold persists, run this sub-event:

1. The pinner rolls d6. The resister rolls d6, minus their exhaustion
   penalty.
2. The higher roll acts first within the pin.
3. Ties go to the resister. Exhaustion converts ties into pinner wins.
4. The pin resolves as one exchange at its initiative value, then the rest
   of the round continues in normal order.
5. The held creature takes no separate turn that round.

Other combatants cannot interrupt a pin mid-exchange. Help arrives next
round. This is what makes a pin useful: it buys the pinners time and locks
the fight into one exchange.

> Design note: the classic grapple freeze is solved here. One exchange per
> round, then initiative continues. Cap it at one exchange or the table
> waits on a duel. The tie rule favours the resister because exhaustion
> already stacks the dice against them; giving the resister the tie keeps
> the defender honest without a second penalty layer.

## Techniques

Techniques are the Wrestling track's specials, plus the moves below. Rank
gates what a fighter can attempt, exactly as in the Weapon Mastery table.
A fighter at Basic can Grapple and Trip. A fighter at Grand Master can do
everything, including the Choke Hold that ends fights.

| Rank | Technique | Effect |
| --- | --- | --- |
| BS | Grapple | On hit, target is held. Escape as above. |
| BS | Trip | On hit, target falls prone. You stay standing. A target that fails a save vs Breath may be _dazed_ (see below). |
| SK | Pin | From Dominant: on hit, target is pinned: cannot act, you cannot move. Escape needs a margin 3+ better than yours. |
| SK | Headlock | From Dominant: on hit, target cannot speak or cast verbal spells and is at -2 to hit. Escape checks at -2. |
| EX | Throw | From Dominant or a hold: release the target and hurl them 1d4 x 5 feet. They take 1d6 damage and land prone. You stay standing. |
| EX | Takedown | From Clinch: on hit, both fighters fall to the Ground, you on top. You are dominant for ground techniques. |
| MS | Joint Lock | Held target takes 1d2 subdual damage per round automatically until they escape. No action required from you. |
| MS | Submission | When a held target is below half hit points, force a Morale check at -2. On failure, the target surrenders. |
| GM | Choke Hold | Pinned target begins suffocating: CON rounds until unconscious. Opposed STR check each round to maintain. If the target wins, the choke breaks but the pin holds. Natural 1 on their escape slips them free entirely. |
| GM | Master of the Hold | Maintain a hold on one target and attack another at -4 in the same round. |

### Dazed

Dazed is a light stun. A dazed fighter acts at -2 on everything except
saves for 1 round. It stacks with nothing and refreshes nothing. It is the
baseline "your head is ringing" state.

## Dirty Tactics

A formal wrestle is a contest. A bar fight, a dungeon scuffle, or a monster
that has decided you are dinner is not. Dirty tactics are the moves a
wrestler uses when nobody is keeping score. They all work inside a hold or
at arm's reach outside one, unless noted.

| Tactic | Hit / Save | Effect | Immune |
| --- | --- | --- | --- |
| Bite | Normal attack, no save | 1d3 damage. Target fails save vs Paralysis: -1 to hit for 1 round. | - |
| Headbutt | Normal attack, save vs Paralysis | 1d4 damage. On failed save: dazed 1 round. Natural 20: 2d4, target stunned. | - |
| Nose-Butt | Normal attack, save vs Paralysis | 1 damage, bleeding nose: -1 to hit from blood in the eyes, cosmetic. | - |
| Sand or Dirt in the Eyes | Save vs Breath | Blinded 1d3 rounds: -4 to hit, half movement. One round to clear the eyes. | Undead, constructs |
| Spit in the Eyes | Save vs Breath | -1 to hit for 1 round, blinking. | Undead, constructs |
| Beard or Hair Grip | Opposed STR | +1 to all your grapple checks, target at -1 to escape, while held. Requires hair or beard long enough to grip. | Bald, short-haired, full helm |
| Thumb Gouge | Save vs Paralysis | Target must break free at -4 next round or surrender the round after. | Undead, constructs |
| Ear Clap | Save vs Paralysis | Dazed 1 round; on failed save, stunned. | Undead, constructs |

Dirty tactics are one-for-one: using one costs your attack for the round.
They are not a bonus attack. They are a choice between a clean technique and
a dirty one, and the dirty one is usually better against an unarmoured face.

> Design note: undead and constructs are immune to everything that needs
> eyes, ears, blood, or pain. A skeleton does not care about your thumb in
> its eye socket because it has no eye socket. This is not a balance patch;
> it is the cheapest possible way to make the undead feel undead in the one
> place a wrestler would expect to win.

## Weapons in the Hold

Weapon length decides what you can do once somebody has hold of you.

| Situation | Rule |
| --- | --- |
| Initiating a grapple with a two-handed weapon in hand | Impossible. Drop or stow it first. |
| Initiating with a one-handed weapon or shield | Possible, but you must free the hand to grip. |
| Maintaining a hold | No weapons. Wrestling techniques only. |
| Held fighter with a dagger or short sword | Attack at the held penalty (-4). |
| Held fighter with a spear, polearm, or greatsword | Cannot attack at all. Escape first. |
| Held fighter with a bow or crossbow | Impossible. |
| Ranged fire into a grapple | The held fighter is -2 to be hit (they are pinned, not dodging). Use the Shooting Past Creatures rule for the grappler. |

A grappler holding a target with a dagger can reasonably angle the dagger
away with their free hand. The target keeps the dagger but cannot use it
well. This is what the -4 represents.

## Creatures That Wrestle

Monsters do not follow human technique. They follow appetite. These hooks
replace the human rules where they apply.

| Creature | Hook |
| --- | --- |
| Undead | Immune to Choke Hold, suffocation, and Submission (no breath, no pain). They never tire: they gain no exhaustion from holding or being held. |
| Bear, big cat | On a successful grapple, automatically bites the same round at -2. |
| Giant, ogre, troll | On a successful grapple, constricts: 1d6 crush damage per round. Escape is opposed STR at -2. |
| Wolf, dire wolf | Bite-and-hold: on a hit, the target is held. Packmates gain +2 to hit the held target. |
| Ooze, slime | Cannot be grappled, pinned, or held. It flows through grips. Melee against it while it engulfs you is at -4. |
| Construct | As undead for eyes, ears, breath, and pain. It also cannot be Joint Locked or submitted; it has no joints worth locking. |

> Design note: every hook exists to make one scene play differently at the
> table. The undead hook makes the party's wrestler the wrong answer to a
> wight. The wolf hook makes packs terrifying because they share the hold.
> Write your own hooks the same way: one sentence, one scene, one decision.

## Wrestling Styles of the Old World

The generic Wrestling table is a template. Cultures wrestle the way they
fight. Each style below swaps one or two specials for something
culturally-appropriate. The DM may require a teacher, membership in a
wrestling society, or a quest to learn a foreign style.

- _Vlastari Mountain Wrestling_: STR-based, throws and immobilisation.
  Replaces Trip's daze with +1 to Throw distance rolls.
- _Thyatian Pankration_: STR + CON, brutal clinch work. Joint Lock at
  Expert instead of Master, but no Headlock.
- _Dwarven Tunnel-Fighting_: low stances and powerful holds. +2 to hit
  creatures larger than you, no Headlock.
- _Skanian Glima_: the three classic Norse grips, each a style of its own.
  - _Brotartok_ (belt and trouser grip): +1 to Trip and Throw checks.
    The style of the belt, the hip, and the ground.
  - _Lausatok_ (loose grip, open stance): +1 to escape checks and to
    Takedown. The style of the collar and the dance.
  - _Hryggspenna_ (back grip, spine lock): Takedown places you in
    Dominant instead of Clinch. The style of the ambush and the bear.

Every style uses the same 5-rank table and the same escape rules. The swap
is the flavour; the mechanics underneath are the same honest dice.

> Design note: the style list is deliberately short. One line per style,
> one mechanical swap, no ten-page martial arts trees. The DM who wants a
> wrestling scene has everything they need in this list, and the space to
> invent their own with the same shape.

## Example of Play

Kara, a 5th-level fighter with Wrestling at Master (STR 15), faces a goblin
scout (AC 14, STR 9) in a cellar passage.

Round 1. Kara declares she grabs the goblin. She rolls to hit: 12, plus her
Master Wrestling bonus of +4, versus AC 14: a hit. The goblin is held. The
goblin tries to escape: it rolls d20 against STR 9 and rolls 11: a failure.
Kara rolls against STR 15 and rolls 6: a success. The hold holds. The goblin
takes 1d3 subdual damage into its exhaustion pool (CON 11): it takes 2.

Round 2. Kara attempts a Trip. She rolls 9 + 4: a hit. The goblin falls
prone and rolls a save vs Breath: 13, a success, so it is not dazed. Kara
stays standing. The goblin, prone and held, tries to draw its knife, but a
held fighter with a short sword attacks at -4, and a prone fighter is
worse. It tries to escape instead: rolls 7 against STR 9: a success. Kara
rolls 13 against STR 15: a failure. The goblin squirms free.

Round 3. The goblin, prone, scrambles for its dagger. Kara dives into a
Takedown: she rolls 7 + 4, a hit. Both fighters go to the Ground, Kara on
top. She is dominant. The pin initiative runs: Kara rolls d6: 4. The goblin
rolls d6: 6, minus 0 exhaustion: 6. Ties go to the resister, but this is
not a tie. The goblin acts first within the pin and stabs: 11 minus 4
(held) is 7, versus Kara's AC: a miss. Kara then drives a Joint Lock
attempt: she rolls 10 + 4, a hit. The lock holds.

Round 4. The Joint Lock deals 1d2 subdual: 1. The goblin's pool (CON 11)
now holds 2 + 1: still below capacity. It tries to escape at -2 (exhaustion
level 0, so just the Dominant penalty): rolls 8 against STR 9: a success.
Kara rolls 14 against STR 15: a success. Margins: the goblin made it by 1,
Kara by 1. A tie in margin: the goblin, as the resister, wins on the tie
rule and slips free.

Round 5. The goblin, free, backs to the wall and hisses, knife out. Kara
stands up, bleeding from a shallow cut. The wrestle is over; the knife
fight begins.

The exchange took five rounds, generated two reversals, and ended without a
kill. That is the point of the subsystem: a fight that could have been one
dull grapple roll became a remembered scene.

# Proposal: Counter-Attack Against Slow Weapons

- **Status**: Draft proposal, not part of the ruleset.
- **Proposed**: 2026-08-21 by Apostol Apostolov.
- **Target**: Combat chapter (rules/04-combat.md), next to the Slow Weapons rule.
- **Intent**: Let a wielder of a small Quick weapon act during the enemy
  initiative phase when his side lost the roll, instead of standing still
  waiting to be killed before his turn ever comes. The 2026-08-22 clean-up
  adds the second half of the design: everyone else gets a positional
  answer to reach instead of a counter.

## Proposed rules text

> Weapons with a damage die of d4 are considered Quick.
>
> If a creature wielding a Slow weapon that is not capable of Brace misses
> against a target wielding a Quick weapon, and the target's action for the
> round was not already spent, the target may use that action to make a
> counter-attack against the attacker.

## Provenance note: Brace

The original text gates the exclusion on Brace. In the OSE core rules,
Brace is a basic property of polearms and needs no Weapon Mastery: a set
polearm deals double damage to a charging foe as a core rule. The current
Weapon Mastery chapter presents Brace as a rank feature (Polearm Skilled,
Lance Grand Master). That presentation is an artifact of how the mastery
import folded the core basic rule into the rank ladder, and the import
needs a redo to separate the two (see Follow-up). This proposal does not
depend on the mastery presentation either way.

The intent behind the Brace clause is reach: a set polearm strikes from
10 feet and should not be answerable by a dagger at that distance. The
recommended wording below replaces the Brace lookup with a positional
rule: the counter only answers a miss delivered from within melee
contact, and any creature can instead walk inside the point, where the
reach weapon's damage die collapses to d4 until the wielder wins a DEX
check and steps back out.

## How it lands on the existing rules

The rule plugs into four pieces of Reforged, and the fit is better than it
first looks:

- **Slow weapons** are already defined here by damage die (base die d8 or
  larger, see Combat), and monster attacks of d8 or larger may be ruled
  Slow by the monster entry or the DM. Quick as base die d4 is the natural
  mirror: one property statement, no new equipment tags.
- **Side-based initiative** does most of the design work for free. Under
  B/X group initiative the rule can only ever fire in the window where the
  enemy side won the roll and is acting, because after your own side has
  acted your action is spent. The trigger window and the death-spiral the
  rule targets are the same window. That is elegant, and it is why this
  rule suits B/X better than it would suit a system with individual
  initiative.
- **The counter is priced.** It consumes the defender's attack for the
  round. When his side's phase arrives he has already swung, so the real
  choice is: strike now at the one who missed, from where you stand, or
  hold your attack for your own phase with full movement and target
  selection. That is a genuine tactical decision, and the cost also
  self-limits the rule: a second enemy miss in the same round offers
  nothing, because the action is already gone. No once-per-round clause
  is needed.
- **Weapon Mastery is not undercut.** The Short Sword Grand Master
  capstone (riposte on enemy miss, 1/round) stays strictly better because
  it is free: it costs no action and carries only a -2 penalty. The
  proposal is the everyman version of that capstone, paid for with your
  whole attack. Class-feature protection holds.

## Analysis: useful or bogging in a B/X environment?

**Verdict: useful.** This is a low-frequency, low-bookkeeping rule pair
that softens the harshest edge of side initiative without touching
lethality math. It earns its place at an old-school table. The three spec
gaps found in review are folded into the recommended wording below.

### What it does well

- **It answers a real B/X failure mode.** When the enemy side wins
  initiative, a low-hit-die character can be reduced to 0 hp before taking
  a single turn, and low-level play is exactly where Slow d8+ weapons are
  everywhere: nearly every orc, hobgoblin, and ogre swings a d8 or better.
  The counter gives the dagger-wielder agency inside the enemy phase
  instead of a purely passive death spiral.
- **It is old-school in spirit.** The rule rewards reading the fight and
  accepting risk, and it hands the biggest relative boost to the weakest
  combatants: the Magic-User with a dagger, the Halfling, the untrained
  conscript. A 1d4 counter does not save anyone from the next enemy's
  hit, so lethality stays intact. What changes is that the small
  character participates.
- **It weaponises the small die.** In Reforged, d4 weapons are mostly the
  low-rank state of a weapon (Basic dagger, Basic sling, Basic Martial
  Arts, Improvised weapons). The rule gives that starting tier an
  identity: inferior damage, superior tempo. That is a meaningful trade
  axis that B/X otherwise never prices.
- **It matches the design line already in the ruleset.** Reforged taxes
  commitment: Slow weapons already carry the death-delay rule and lost
  their initiative modifier on purpose. A whiff with a great weapon now
  has a consequence beyond an empty round. Quick and Slow become two ends
  of one philosophy: small weapons reward presence, big weapons reward
  landing the blow.

### The two answers to reach

The 2026-08-22 clean-up splits the reach problem into two clean parts,
one for each kind of defender:

1. **The Quick wielder answers a miss with steel.** Only a creature
   wielding a Quick weapon may make the counter-attack, and only against
   a miss delivered from within melee contact. A polearm thrust from 10
   feet is safe at that distance, and a giant's blow swung from beyond
   arm's length is safe the same way.
2. **Everyone else answers reach with position.** Any creature, armed
   with anything, may move into melee contact with an attacker whose
   attack comes from beyond contact (a reach weapon, an oversized
   monster). While the intruder remains in contact, that attacker's
   damage die is d4. Before each of his attacks, the attacker may attempt
   a DEX check: on a success he attacks with his normal damage die and
   steps back to restore his range (10 feet for a polearm); on a failure
   he makes this attack at d4 and stays where he is.

The two halves reinforce each other. Inside the point, the polearm swings
at d4 from within contact, so a Quick intruder who makes it miss can also
counter: the within-contact gate is satisfied by the intruder's own
positioning. Getting inside the point is the work, and the dagger then
collects the reward.

The position rule is self-balancing through movement economy. When the
wielder wins his DEX check he steps back out of contact, and the intruder
must spend his own movement to close again. Nobody tracks a condition:
the downgrade exists exactly while a creature stands inside contact, and
it ends the moment range is restored. This is the reach pressure of
weapon-length systems (Mythras, Forbidden Lands 2e) reduced to one
positional fact and one occasional die, which is about as much of it as
B/X can carry.

Expected odds: OSE ability checks roll a d20 under the score, so a
typical DEX of 9 to 10 recovers the die on 45-50% of attempts, roughly
once per two attacks. A fighter with DEX 13+ shakes the intruder off
faster, which is a reasonable reflection of skill.

### The three gaps and their fixes

1. **The Brace gate needed a reach mechanic.** Brace, core or mastery, is
   invisible on a monster statblock, and monsters are exactly where d8+
   attacks concentrate. The fix is positional: contact answers contact.
   Whether a monster's attack strikes from beyond contact is decided by
   the DM, mirroring the existing rule that d8+ monster attacks are Slow
   only if the entry or the DM says so. The same DM call now drives both
   the counter's within-contact gate and the walk-in downgrade, so a
   giant that cannot be countered from afar is also a giant that can be
   body-checked into a d4 paw. No new lookup is introduced.
2. **Quick is pinned to the base damage die.** Reforged damage dice grow
   with rank (Dagger: 1d4 at Basic, 1d6+ at Skilled and beyond). If Quick
   tracks the _current_ rank die, the rule quietly evaporates for anyone
   with training. Pinned to the _base_ die, a dagger stays Quick for
   life. The position rule uses the same principle in reverse: the
   wielder's downgrade is to d4 regardless of his rank die.
3. **The trigger is melee-only.** Longbow and Crossbow damage dice are
   d8+, so by the raw text an archer's miss at 140 feet would invite a
   counter-attack. The trigger must be a missed melee attack.

### Scope note: reach weapons, or all Slow weapons

The walk-in downgrade should apply only to attacks delivered from beyond
melee contact (reach weapons, oversized monsters). Applying it to every
d8+ weapon would drop greatswords and mauls to d4 whenever any creature
stands next to them, which is their normal fighting condition and would
gut the weapon class. B/X has no range tracking for ordinary melee
weapons, and the rule should not invent any.

### Frequency check

The counter chain (enemy side won initiative, attacker has a d8+ melee
weapon, he misses from within contact, defender holds a base-d4 weapon,
defender has not attacked) fires perhaps once or twice a session at low
levels and close to never at high levels. The position rule fires only
when someone chooses to close inside a reach weapon, which a table sees
when a spear wall or a giant matters. Resolution is a single attack roll,
or a single DEX check plus a normal attack. This does not bog a B/X
table.

### Foundry note

The earlier deferred variant needed a persistent damage-override effect
plus a recurring recovery-check hook, which was its disqualifier. The
cleaned position rule is lighter: the downgrade is a function of
distance, with no timed effect to maintain, and the recovery is one
inline DEX roll. It still needs custom automation (a distance check on
attack), but of a much simpler kind than the variant it replaced.

## Recommended wording if adopted

> ### Quick Weapons and Counter-Attacks
>
> Weapons with a base damage die of d4 are Quick.
>
> When a creature misses with a melee attack using a Slow weapon, and the
> target wields a Quick weapon and has not yet attacked this round, the
> target may spend its attack for the round to immediately make a
> counter-attack against the attacker. The counter-attack follows all
> normal attack rules. It can only be made against an attacker who
> missed from within melee contact: an attack delivered from beyond
> contact, such as a polearm set or thrust from 10 feet, or a giant's
> blow swung from beyond arm's length, cannot be answered. Whether a
> monster's attack strikes from beyond contact is decided by the DM, as
> with Slow monster attacks.
>
> ### Inside the Point
>
> A creature that moves into melee contact with an attacker whose attack
> comes from beyond contact (a reach weapon, an oversized monster)
> collapses that attacker's damage die to d4 while it remains in contact.
>
> Before each of his attacks, such an attacker may attempt a DEX check.
> On a success, he makes the attack with his normal damage die and steps
> back to restore his range (10 feet for a polearm). On a failure, he
> makes this attack at d4 and remains in contact. Whether a monster's
> attack comes from beyond contact is decided by the DM, as with Slow
> monster attacks.

## Options

| Option | Change | Effect |
| --- | --- | --- |
| A. As originally proposed | Trigger on any miss by a non-Brace Slow weapon | Brace is invisible on monster statblocks; Quick evaporates with training; missile misses invite counters. |
| B. Recommended wording | Quick counter (melee miss, within contact, base die d4, spends the attack) plus the inside-the-point position rule | Closes all three gaps; two clean answers to reach (steel for Quick, position for everyone); monster reach rides the same DM call as monster Slow. |
| C. Counter only, no position rule | Adopt the Quick counter without inside the point | The counter stays useful, but non-Quick characters have no answer to a spear wall beyond waiting. |
| D. Mastery-only variant | Give the counter as a Weapon Mastery special (e.g. Dagger Skilled) | Zero new combat-chapter rules, but denies the rule to the squishy characters who need it most. |
| E. Reject | Do not adopt | The lost-initiative death spiral stays as-is; Parry already offers a defensive answer, but only to characters willing to forfeit their attack before knowing the enemy rolls. |

## Follow-up

- Redo the Weapon Mastery import so the core basic Brace for polearms and
  the rank-gated mastery enhancement are separate entries. This proposal
  flags the issue; the redo is its own task.

## Changelog

- 2026-08-22 (clean-up): Counter confirmed Quick-only. Added the
  inside-the-point rule: any creature may move into contact with a
  beyond-contact attacker, collapsing its damage die to d4; DEX check
  before each attack to recover the die and step back to range. Supersedes
  the deferred punish-the-brace variant, whose check loop and persistent
  override are replaced by one positional fact and one inline roll.
- 2026-08-22: Recorded the punish-the-brace variant (brace weapon
  answerable, d4 downgrade until a DEX recovery check) with analysis;
  deferred as a weapon-length dynamic whose bookkeeping and Foundry
  automation cost outweigh its payoff in B/X.
- 2026-08-21: Corrected Brace provenance (OSE core: basic polearm brace,
  no mastery required), replaced the Brace gate with a reach exclusion,
  pinned Quick to the base damage die, restricted the trigger to melee
  misses, flagged the Weapon Mastery import redo.
- 2026-08-21: Initial proposal recorded, with analysis and recommended
  wording.

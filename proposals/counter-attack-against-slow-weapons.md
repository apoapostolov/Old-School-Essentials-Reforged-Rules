# Proposal: Counter-Attack Against Slow Weapons

- **Status**: Draft proposal, not part of the ruleset.
- **Proposed**: 2026-08-21 by Apostol Apostolov.
- **Target**: Combat chapter (rules/04-combat.md), next to the Slow Weapons rule.
- **Intent**: Let a wielder of a small Quick weapon act during the enemy
  initiative phase when his side lost the roll, instead of standing still
  waiting to be killed before his turn ever comes.

## Proposed rules text

> Weapons with a damage die of d4 are considered Quick.
>
> If a creature wielding a Slow weapon that is not capable of Brace misses
> against a target wielding a Quick weapon, and the target's action for the
> round was not already spent, the target may use that action to make a
> counter-attack against the attacker.

## How it lands on the existing rules

The rule plugs into four pieces of Reforged, and the fit is better than it
first looks:

- **Slow weapons** are already defined here by damage die (base die d8 or
  larger, see Combat). Quick as base die d4 is the natural mirror: one
  property statement, no new equipment tags.
- **Side-based initiative** does most of the design work for free. Under B/X
  group initiative the rule can only ever fire in the window where the enemy
  side won the roll and is acting, because after your own side has acted your
  action is spent. The trigger window and the death-spiral the rule targets
  are the same window. That is elegant, and it is why this rule suits B/X
  better than it would suit a system with individual initiative.
- **The counter is priced.** It consumes the defender's attack for the round.
  When his side's phase arrives he has already swung, so the real choice is:
  strike now at the one who missed, from where you stand, or hold your attack
  for your own phase with full movement and target selection. That is a
  genuine tactical decision, and the cost also self-limits the rule: a second
  enemy miss in the same round offers nothing, because the action is already
  gone. No once-per-round clause is needed.
- **Weapon Mastery is not undercut.** The Short Sword Grand Master capstone
  (riposte on enemy miss, 1/round) stays strictly better because it is free:
  it costs no action and carries only a -2 penalty. The proposal is the
  everyman version of that capstone, paid for with your whole attack.
  Class-feature protection holds.

## Analysis: useful or bogging in a B/X environment?

**Verdict: useful.** This is a low-frequency, low-bookkeeping rule that
softens the harshest edge of side initiative without touching lethality
math. It earns its place at an old-school table, provided three spec gaps
are pinned down first (next section).

### What it does well

- **It answers a real B/X failure mode.** When the enemy side wins
  initiative, a low-hit-die character can be reduced to 0 hp before taking a
  single turn, and low-level play is exactly where Slow d8+ weapons are
  everywhere: nearly every orc, hobgoblin, and ogre swings a d8 or better.
  The counter gives the dagger-wielder agency inside the enemy phase instead
  of a purely passive death spiral.
- **It is old-school in spirit.** The rule rewards reading the fight and
  accepting risk, and it hands the biggest relative boost to the weakest
  combatants: the Magic-User with a dagger, the Halfling, the untrained
  conscript. A 1d4 counter does not save anyone from the next enemy's hit,
  so lethality stays intact. What changes is that the small character
  participates.
- **It weaponises the small die.** In Reforged, d4 weapons are mostly the
  low-rank state of a weapon (Basic dagger, Basic sling, Basic Martial
  Arts, Improvised weapons). The rule gives that starting tier a identity:
  inferior damage, superior tempo. That is a meaningful trade axis that B/X
  otherwise never prices.
- **It matches the design line already in the ruleset.** Reforged taxes
  commitment: Slow weapons already carry the death-delay rule and lost their
  initiative modifier on purpose. A whiff with a great weapon now has a
  consequence beyond an empty round. Quick and Slow become two ends of one
  philosophy: small weapons reward presence, big weapons reward landing the
  blow.

### Where it could bog

- **The Brace gate does not survive contact with monsters.** Brace vs
  Charge exists in this ruleset only as a Weapon Mastery feature (Polearm
  Skilled, Lance Grand Master). Monster statblocks carry no mastery ranks,
  so "not capable of Brace" forces the DM to adjudicate a hidden property
  mid-round. The intent behind the clause is reach: a set polearm strikes
  from 10 feet and should not be punishable by a dagger. The cleaner B/X
  gate is adjacency, and it is printed on the weapon already.
- **Quick must be pinned to the base damage die.** Reforged damage dice grow
  with rank (Dagger: 1d4 at Basic, 1d6+ at Skilled and beyond). If Quick
  tracks the *current* rank die, the rule quietly evaporates for anyone with
  training. If it tracks the *base* die, a dagger stays Quick for life.
  The rule needs one sentence to say which.
- **Missile Slow weapons need excluding.** Longbow and Crossbow damage dice
  are d8+, so by the raw text an archer's miss at 140 feet would invite a
  counter-attack. The trigger must be a missed *melee* attack.
- **Frequency check passes.** The full trigger chain (enemy side won
  initiative, attacker has a d8+ melee weapon, he misses, defender holds a
  d4 weapon, defender has not attacked) fires perhaps once or twice a
  session at low levels and close to never at high levels. Resolution is a
  single attack roll with the normal to-hit and damage. This does not bog a
  B/X table.

## Recommended wording if adopted

> Weapons with a base damage die of d4 are Quick.
>
> When a creature misses with a melee attack using a Slow weapon, and the
> target wields a Quick weapon and has not yet attacked this round, the
> target may spend its attack for the round to immediately make a
> counter-attack against the attacker. The counter-attack follows all
> normal attack rules. It may only be made against an adjacent attacker.

Three changes from the original: base die pinned, melee-only trigger, and
the Brace clause replaced by adjacency, which excludes set polearms and
lances by their printed reach instead of a mastery lookup.

## Options

| Option | Change | Effect |
| --- | --- | --- |
| A. As originally proposed | Trigger on any miss by a non-Brace Slow weapon | Needs monster adjudication for Brace; missile weapons leak in. |
| B. Recommended wording | Melee miss, adjacent attacker, base die d4, spends the attack | Closes all three gaps with no added bookkeeping. |
| C. Mastery-only variant | Give the counter as a Weapon Mastery special (e.g. Dagger Skilled) | Zero new combat-chapter rules, but denies the rule to the squishy characters who need it most. |
| D. Reject | Do not adopt | The lost-initiative death spiral stays as-is; Parry already offers a defensive answer, but only to characters willing to forfeit their attack before knowing the enemy rolls. |

## Changelog

- 2026-08-21: Initial proposal recorded, with analysis and recommended
  wording.

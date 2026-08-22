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
10 feet and should not be answerable by a dagger. The recommended wording
below expresses that intent as a reach exclusion, which also covers
monsters whose bulk gives them de facto reach (giant size, huge paws
swinging from beyond contact) without looking up any hidden property.

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

**Verdict: useful.** This is a low-frequency, low-bookkeeping rule that
softens the harshest edge of side initiative without touching lethality
math. It earns its place at an old-school table. The three spec gaps found
in review are folded into the recommended wording below.

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
  landing the blow. The reach exclusion joins the core Brace rule in
  telling the same story: polearm power lives at 10 feet, and closing
  inside the point is the historic counter.

### The three gaps and their fixes

1. **The Brace gate needs a reach mechanic.** The clause intends to keep
   set polearms and lances safe, and in the OSE core rules Brace is a
   basic polearm property with no mastery attached (see Provenance note).
   But Brace, core or mastery, is invisible on a monster statblock, and
   monsters are exactly where d8+ attacks concentrate. A giant never
   braces anything, yet its paws swing from well beyond a halfling's
   dagger reach, and at that distance it should be no more answerable
   than a set spear. The fix is distance: the counter may only answer a
   miss from within melee contact. Printed reach (Polearm "attack from
   10'", Lance "reach keeps them at bay") and monster bulk then resolve
   through the same question, and the DM call for monsters mirrors the
   existing rule that d8+ monster attacks are Slow only if the entry or
   the DM says so. No new lookup is introduced.
2. **Quick is pinned to the base damage die.** Reforged damage dice grow
   with rank (Dagger: 1d4 at Basic, 1d6+ at Skilled and beyond). If Quick
   tracks the *current* rank die, the rule quietly evaporates for anyone
   with training. Pinned to the *base* die, a dagger stays Quick for
   life.
3. **The trigger is melee-only.** Longbow and Crossbow damage dice are
   d8+, so by the raw text an archer's miss at 140 feet would invite a
   counter-attack. The trigger must be a missed melee attack.

### Frequency check

The full trigger chain (enemy side won initiative, attacker has a d8+
melee weapon, he misses from within contact, defender holds a base-d4
weapon, defender has not attacked) fires perhaps once or twice a session
at low levels and close to never at high levels. Resolution is a single
attack roll with the normal to-hit and damage. This does not bog a B/X
table.

## Recommended wording if adopted

> Weapons with a base damage die of d4 are Quick.
>
> When a creature misses with a melee attack using a Slow weapon, and the
> target wields a Quick weapon and has not yet attacked this round, the
> target may spend its attack for the round to immediately make a
> counter-attack against the attacker. The counter-attack follows all
> normal attack rules. It can only be made against an attacker who missed
> from within melee contact: an attack delivered from beyond contact,
> such as a polearm set or thrust from 10 feet, or a giant's blow swung
> from beyond arm's length, cannot be answered. Whether a monster's
> attack strikes from beyond contact is decided by the DM, as with Slow
> monster attacks.

Stricter alternative, if polearms should be excluded as a class rather
than by use: any weapon or monster attack with reach is never answerable,
even in melee contact. This is simpler to police at the table but removes
the "get inside the point" maneuver, which is the classic answer to a
spear wall. Taken further, that same maneuver grows into a full
weapon-length system; see the variant below.

## Variant: punish the brace (deferred)

Recorded 2026-08-21 (revised 2026-08-22). An extension proposed in case
the "get inside the point" dynamics are ever wanted in full:

> If the wielder of a weapon with Brace misses an attack, the opponent
> may make a counter-attack (as above). If that counter-attack hits, the
> brace weapon's damage die is reduced to d4. As part of his next attack,
> the wielder may attempt a DEX check to recover: on a success the
> weapon's normal damage returns; on a failure the weapon deals d4 for
> that attack, and the check may be attempted again on a later attack.

Analysis:

- **This is a weapon-length system in miniature.** Degrading the polearm
  until distance is regained is the core dynamic of reach systems such as
  Mythras and Forbidden Lands 2e. Grafting it onto OSE converts the game
  toward those systems, and B/X buys none of their supporting structure.
  The base proposal deliberately stops short of that line.
- **Bookkeeping triples.** The variant adds persistent per-weapon state
  (downgraded die), a recurring DEX check rider on each attack while
  degraded, and a damage override at the table. The base proposal's
  selling point is a single attack roll with no state to carry between
  rounds.
- **Foundry automation cost is high.** No native support exists for a
  conditional damage-die override with a per-attack recovery check; it
  needs a custom active effect plus a check hook on every attack while
  the condition lasts. The cost is out of proportion to the payoff.
- **Verdict: record and defer.** If it is ever wanted, consider replacing
  the DEX check loop with a simpler recovery, for instance normal damage
  returning at the start of the wielder's next turn unless the opponent
  is still inside contact. That keeps the pressure while removing the
  recurring roll and most of the automation burden.

## Options

| Option | Change | Effect |
| --- | --- | --- |
| A. As originally proposed | Trigger on any miss by a non-Brace Slow weapon | Brace is invisible on monster statblocks; Quick evaporates with training; missile misses invite counters. |
| B. Recommended wording | Melee miss, within-contact gate, base die d4, spends the attack | Closes all three gaps; monster reach rides the same DM call as monster Slow. |
| C. Mastery-only variant | Give the counter as a Weapon Mastery special (e.g. Dagger Skilled) | Zero new combat-chapter rules, but denies the rule to the squishy characters who need it most. |
| D. Reject | Do not adopt | The lost-initiative death spiral stays as-is; Parry already offers a defensive answer, but only to characters willing to forfeit their attack before knowing the enemy rolls. |
| E. Punish the brace | Brace weapons are answerable; a hit counter reduces the brace weapon to d4 until a DEX check recovers it | True reach pressure (Mythras / FL 2e flavor) at triple the bookkeeping and a real Foundry automation cost. Deferred. |

## Follow-up

- Redo the Weapon Mastery import so the core basic Brace for polearms and
  the rank-gated mastery enhancement are separate entries. This proposal
  flags the issue; the redo is its own task.

## Changelog

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

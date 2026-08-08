# Old-School Essentials Reforged Rules

_Old-School Essentials Reforged_ is a house-rule framework by Apostol Apostolov
for _Old-School Essentials_ (OSE) and classic B/X D&D. It is built for tables
that love the simplicity and danger of old-school play but want sharper
mechanical structure, deeper character options, and subsystems that hold up
under long campaigns.

The goal of Reforged is not to turn B/X into a modern game. It is to keep what
makes old-school play worth running: lethal combat, meaningful exploration,
resource pressure, and rulings over rules. Where Reforged departs from the
published rules, it does so to fill gaps that B/X leaves to the DM's
improvisation: unified attack progressions, a complete skill system, weapon
mastery with training and quest hooks, downtime activities that matter, and
class reworks that give every archetype a reason to be played.

This repository is the canonical Markdown edition of the ruleset. It is built
for readability, easy reference at the table, and clean version tracking.

## What is in this ruleset

Reforged layers on top of the _Old-School Essentials Advanced Fantasy_ rule
set. You need the published OSE books to use it. The house rules modify,
expand, and add to the published material; they do not replace it wholesale.

The framework is designed for a 14-level game with accelerated XP (x10
standard D&D progression) to support meaningful advancement within a modern
play schedule.

### Highlights

- **Class Rework**: Every basic, demihuman, and advanced class gets
  targeted improvements. Demihuman classes are rebalanced with boosted
  ability requirements (11+) and stronger racial features. Advanced
  classes get meaningful new abilities. Unified THAC0 progression replaces
  per-class tables with three clean groups (Warrior, Adventurer, Mage).
- **Weapon Mastery**: A full rank system (Basic through Grand Master) with
  slot progression by class group, a training system (teachers, costs,
  quest gates), weapon-specific specials at each rank, and three unarmed
  combat tracks (Brawling, Wrestling, Martial Arts).
- **Skills**: A complete skill system adapted from the Rules Cyclopedia
  with 40+ skills organised by attribute, tiered checks (Simple, Expert,
  Heroic), and class-feature protection so no general skill eclipses a
  dedicated class feature.
- **Combat**: Slow weapon death-delay, subduing damage, parry and riposte,
  cover an ally, shooting past creatures, fire and bleeding damage, and
  masterwork weapon rules.
- **Downtime**: Philanthropy with social consequences, carousing with
  venue tiers and outcome tables, life XP, and spell learning rewards.
- **Environment**: Darkness and vision rules (infravision, low-light,
  moonlit vision), torch mechanics with type and duration variety.
- **Hirelings**: Separate XP pools, hireling limits, and Level 0 rules.

### Power-User Analysis

The [Class Power Level Analysis](analysis/class-power-analysis.md) evaluates
every class across five axes (Combat, Utility, Scaling, Autonomy, Entry Cost)
with S-tier ratings, design observations, and a full balance assessment. This
is a tool for DMs and optimizers who want to understand the tier structure,
spot pressure points, and tune the system for their table.

## Contents

### Rules

- [Character Creation](rules/01-character-creation.md)
- [General Rules](rules/02-general-rules.md)
- [Class Rework](rules/03-class-rework.md)
- [Combat](rules/04-combat.md)
- [Skills](rules/05-skills.md)
- [Weapon Mastery](rules/06-weapon-mastery.md)
- [Hirelings](rules/07-hirelings.md)
- [Environment](rules/08-environment.md)
- [XP and Downtime](rules/09-xp-and-downtime.md)

### Additional Content

- [New Classes](additional-content/new-classes.md)

### Subsystems

- [Wrestling](subsystems/wrestling.md)

### Appendix

- [Ability Score Descriptors](appendix/ability-score-descriptors.md)
- [Torch Realism: Feudal Slavic Lighting](appendix/torch-realism.md)

### Analysis

- [Class Power Level Analysis](analysis/class-power-analysis.md)

## How to use this ruleset

1. Read the rules chapters in order. Each chapter is self-contained but
   builds on the previous one.
2. Use the OSE Advanced Fantasy books as the base. Apply the Reforged
   changes on top.
3. The DM decides which optional systems to use. Weapon Mastery and the
   expanded skill system are the largest additions; both can be used
   independently.
4. The Class Power Level Analysis is a reference tool, not rules text.
   Use it to understand balance and inform ruling decisions.

## Format and version

The rules use standard Markdown with underscore italics and bold emphasis.
All chapters follow the same notation conventions and style.

The ruleset follows [Semantic Versioning](https://semver.org/):

- **MAJOR**: breaking mechanical changes to rules or class features
- **MINOR**: backward-compatible additions or new options
- **PATCH**: wording or formatting only; no mechanical values changed

See the [changelog](CHANGELOG.md) for the full version history.

## The OSE family

The OSE support projects by Apostol Apostolov work together. Pick the one
that matches the task: read the rules, run them in Foundry VTT, or
generate a character.

| Repository | What it is |
| --- | --- |
| [Old-School-Essentials-Reforged-Rules](https://github.com/apoapostolov/Old-School-Essentials-Reforged-Rules) | The ruleset: the full Reforged house rules as Markdown, for reading and table reference |
| [OSE-Reforged-Rules-for-Foundry-VTT](https://github.com/apoapostolov/OSE-Reforged-Rules-for-Foundry-VTT) | Foundry module: every Reforged class ability in a compendium with dice automation |
| [OSE-Combat-Improvements-for-Foundry-VTT](https://github.com/apoapostolov/OSE-Combat-Improvements-for-Foundry-VTT) | Foundry module: combat tracker, injury tracking, and secret death saves |
| [OSE-Statblock-Importer-for-Foundry-VTT](https://github.com/apoapostolov/OSE-Statblock-Importer-for-Foundry-VTT) | Foundry module: paste OSE statblocks and import complete actors |
| [Old-School-Essentials-Character-Creator](https://github.com/apoapostolov/Old-School-Essentials-Character-Creator) | Web app: roll a character, pick class and gear, export a print-ready PDF |

## License

This house-rule framework is released under the
[MIT License](LICENSE). The rules text is original work by Apostol Apostolov.

_Old-School Essentials_ is a trademark of Necrotic Gnome. This project is not
affiliated with or endorsed by Necrotic Gnome. You need the published OSE
rules to use these house rules.

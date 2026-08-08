# AGENTS.md - Old-School Essentials Reforged Rules

**Project-specific operating contract.** This repository holds the canonical
public edition of the Old-School Essentials Reforged house rules.

## Project Identity

- **Purpose**: Maintain a clear, versioned, public ruleset for OSE Reforged
  house rules.
- **Canonical source**: Treat `README.md` and the `rules/` chapters as the
  authoritative source for current rules text.
- **Scope**: Mechanical changes, class reworks, subsystems, analysis, and
  changelog entries that support the house rules document set.

## Working Rules

- Keep rules text direct, readable, and mechanically precise.
- Prefer one rule per bullet when documenting behavior.
- Use underscore italics, never asterisk italics (markdownlint MD049).
- Use hyphens or colons, never em dashes.
- Preserve old versions by archiving instead of deleting.
- Use absolute dates (`YYYY-MM-DD`) in changelog entries.
- Keep public content free of secrets, private campaign data, internal
  tooling references, and unpublished personal information.

## Structure

| Path | Role |
| --- | --- |
| `rules/NN-slug.md` | Main rules chapters (01 through 09) |
| `subsystems/` | Optional systems (new classes) |
| `appendix/` | Reference material (ability descriptors, torch rules) |
| `analysis/` | Power-user analysis (class tier evaluation) |
| `README.md` | Index with links to every chapter |
| `CHANGELOG.md` | Dated entries, newest first |
| `AGENTS.md` | This operating contract |

## Source Hierarchy

1. Explicit user instruction in the current session.
2. This `AGENTS.md`.
3. The repository `README.md` and rules files.
4. Surrounding documentation and established repo patterns.
5. External rules references only when local context is insufficient.

## Change Protocol

- Edit files in place rather than creating duplicate variants.
- Run `markdownlint-cli2 --fix` on changed Markdown files before finishing.
- New main chapter: next free `rules/NN-slug.md` plus README link plus
  CHANGELOG entry.
- Version bump follows SemVer: MAJOR for breaking changes, MINOR for
  additions, PATCH for wording only.

## Last reviewed

`2026-08-08`.

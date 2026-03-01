# Fabled Realm: Friendly Fire

A 2+ player fantasy card game where history's most iconic monsters are reimagined as D&D archetypes and thrown together in a battle for survival.

## Concept

Players use cards to attack, defend, and outmaneuver rivals using each legend's unique **Fabled Gifts**. Last player standing wins.

## Repo Structure

| Folder | Purpose |
|--------|---------|
| `rules/` | Game rules, turn structure, card types, glossary |
| `characters/` | One file per legend — stats, archetype, Fabled Gifts |
| `art/` | Visual style guide and card layout specs |
| `playtest/sessions/` | Notes from playtesting sessions |
| `simulations/` | Game simulations (in progress) |

## Conventions

- Each character lives in its own file under `characters/` using the format in `characters/_template.md`
- Rules are split by topic — don't consolidate into one file
- Art direction lives in `art/` only — no embedded art specs in character files

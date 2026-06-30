# Google Store Order Case: GS.0190-9911-6648

A living case study documenting a Pixel 10 Pro XL order to Northern Ireland that stalled for 21+ days across six operational systems. The goal is not complaint documentation; it is role-hat analysis: wearing each role's seat, finding systemic loose ends, designing fixes that would prevent recurrence.

## What this is

A methodology applied to real friction. Customer → carrier → order management → specialist team → billing automation → Klarna, each layer examined from the inside. The pattern it exposes (systems operating correctly in isolation, failing collectively) is the finding.

## Files

- `index.html`: shareable single-page site (self-contained, no build step)
- `log.md`: update log for this project

## Vault source

All primary analysis lives in the Obsidian vault:
`Void/Observations/Google Store Order Case/`

- `Google Store Order Case.md`: framework and goals
- `Google Store Order Case: Log.md`: running case log (update this first)
- `Case Debrief: End to End Analysis.md`: six-layer investigative debrief
- `Systemic Solution Design.md`: seven failure points with staged fixes
- `Lever Identification: Ranked.md`: five levers by impact
- `Solution Design: Fixing Each Lever.md`: per-lever design options
- `Role Architecture: Who Owns These Levers.md`: org mapping
- `Research: External Intelligence: 2026-06.md`: UK law, DHL DG, Klarna regulatory

## Update protocol

When new information arrives (Google responds, Klarna dispute updates, replacement ships, case closes):

1. Add entry to vault `Google Store Order Case: Log.md` (date + what happened + what it confirms or changes)
2. Update `index.html`:
   - Hero badge (Day X: Unresolved / Resolved)
   - Stat bar day count
   - Add timeline entry with correct dot colour
   - Revise conclusion block if the resolution outcome is meaningful
3. Add entry to `log.md` in this folder

## The broader method

This format works for any customer friction that crosses org boundaries. The shape is:
- Identify all systems that touched the problem
- Wear each role's hat (what could they see, what couldn't they see, what were they actually optimising for)
- Separate confirmed from inferred from researched
- Find the structural gap, not the surface failure
- Design the cheap-now fix and the structural fix separately

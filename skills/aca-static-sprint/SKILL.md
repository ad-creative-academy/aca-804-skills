---
name: aca-static-sprint
description: The AI creative sprint for statics, hypothesis first. Takes rows from the concept matrix, chooses ad types per row, pulls structure references from the swipe file, writes copy from customer voice, stops for a copy check, generates the batch, runs the QA checklist, builds a gut check board, makes variations of the keepers and hands off to the launch sheet. Use when someone says "run a static sprint", "make a batch of statics for <brand>", "Black Friday statics", or runs /aca-static-sprint.
---

# The static sprint (Course 804, lessons 5.1 to 5.3)

Every ad is a hypothesis. This sprint starts from the concept matrix, not from a reference ad.

```
matrix rows → ad types → references → copy → COPY CHECK → generate → QA → GUT CHECK → variations → launch sheet
```

## Files in this skill
| File | What it holds |
|---|---|
| `corrections-log.md` | Every past correction, plus the change log. **Read it first, every run. It overrides the other files** |
| `copy-rules.md` | Where a headline comes from, and the headlines we'd cut next to the ones we'd keep |
| `qa-checklist.md` | What gets checked on every image |
| `gut-check-board.md` | How to build the board |
| `variations.md` | The variation plays |
| `swipe-file/` | References by ad type, awareness level and point of view |

## Step 0: Set the sprint
Read the mission control file and `02-language/how-we-read-the-ad-account.md`. Then ask, don't assume:
- which rows from `04-concepts/concept-matrix.md`
- batch size (default 20)
- the share of iterations vs new angles. Use the spend guidance from the launching ad campaigns module (601): at $50K to $100K a month, about 40 to 50% of new ads are iterations of proven winners. At $100K to $500K, about 60 to 70% iterations and 30 to 40% new. Below that, a few concepts a month with 3 to 5 variations each. Ask for the monthly spend and confirm the split.

Check `06-pipeline/creative-pipeline.md` and the change log. Ads that are too new to judge are **"too early"**, not winners or losers. Leave them out of the weighting and say so. Mark each row `iteration` or `new`.

## Step 1: Choose ad types per row
Use `02-language/ad-types.md` and its awareness level to ad types mapping. If the doc is missing, copy the starter from `aca-creative-os/templates/ad-types.md` first. Spread across points of view (brand, customer, expert). Make the ads different enough to avoid the similarity penalty: small tweaks read as the same ad.

## Step 2: Pull references
From `swipe-file/references.json`, match on `ad_type`, `awareness_levels` and `point_of_view`. Structure only. Research to inspire, not to copy.

## Step 3: Write copy
Follow `copy-rules.md`: start from copy mining sorted by emotion, take the angle from the matrix row, one idea per ad, grade 5 reading level, structure from the ad type reference and never its words. Show a table the strategist can edit:

`# | row | iteration/new | ad type | point of view | headline | support | source ID`

## Copy check (stop)
**Stop. Wait for the strategist to approve, edit or cut. Generate nothing until they say "approved".** Add any headline they cut or rewrote to the cut and keep table in `copy-rules.md`, with one line on why.

## Step 4: Generate
One image per approved line, with the reference as a layout guide and the right product image from `01-brand/brand-assets/`. Default 4:5. Save to `05-production/statics/<YYYY-MM>/<batch>/`. If a generation fails twice, skip it and note it.

## Step 5: QA checklist pass
Check every image against `qa-checklist.md`. Tag **pass / fix / fail** with one line of reason. Never hide fails.

## Step 6: Gut check board
Build the board per `gut-check-board.md`. The strategist marks keep or cut and leaves notes per ad. A note with the **"always"** box ticked is written to `corrections-log.md` with today's date.

## Step 7: Variations
For keepers, follow `variations.md`. If the platform would see two ads as the same ad, it is not a variation. Same QA, same board.

## Step 8: Hand off
Run `aca-launch-sheet` on the keepers. Add a dated line to the change log in `corrections-log.md` with the date results should be checked.

## Rules
- **Agents prepare. People approve.** Never generate before the copy check. Never upload to an ad account.
- Every testimonial-style line traces to a real source ID.
- If one reference keeps producing fails, suggest removing it from the swipe file.

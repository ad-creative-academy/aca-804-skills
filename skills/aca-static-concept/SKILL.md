---
name: aca-static-concept
description: Takes one concept matrix row and turns it into a small set of static ads, hypothesis first. States the hypothesis, picks three static ad types that fit the awareness level, finds structure references in the swipe file, mines copy from customer voice, stops for a copy check, then generates, runs the QA checklist and shows a gut check grid. Use when someone says "make statics for this concept", "statics for row 2", "test this concept as a static", or runs /aca-static-concept.
---

# One concept, as statics (Course 804, lesson 5.1)

This is the AI creative sprint at its smallest: one row of the concept matrix, tested as statics before anyone spends on video.

## Inputs
- One row from `04-concepts/concept-matrix.md`. If there's no matrix yet, run `aca-concept-matrix` first, or ask the strategist for the row.
- `02-language/ad-types.md`: the team's static ad types, the three points of view and the awareness level to ad types mapping. If it's missing, copy the starter from `aca-creative-os/templates/ad-types.md` and say so.
- `03-research/audience/customer-voice.md`, `01-brand/dos-and-donts.md`, `01-brand/offers.md`.
- Product images in `01-brand/brand-assets/`.
- The swipe file in the `aca-static-sprint` skill folder (`swipe-file/references.json`).

## Step 1: Read the row and state the hypothesis
Write down the persona, angle, awareness level and offer. Then answer the three questions:
1. What am I testing?
2. What do I expect to learn?
3. How will this inform the next iteration?

If the row already has a hypothesis, use it unchanged.

## Step 2: Pick three static ad types
Choose from the static ad types in `02-language/ad-types.md`.

- Fit the **awareness level**. Use the mapping in that doc. The starter mapping is a starting point, so if the account's learnings or the strategist say otherwise, follow them and offer to update the doc.
- Cover more than one **point of view** where possible: brand voice, customer voice, expert voice.
- Say why each ad type fits, in one line.

## Step 3: Find references
For each ad type, find one or two references in the swipe file with a matching `ad_type`. Keep the **structure** only: layout, hierarchy, the job each element does. Research to inspire, not to copy. Their words, product, people, claims and brand assets stay out. If the swipe file has nothing for an ad type, say so and ask.

## Step 4: Write the copy
Start from copy mining: the quotes sorted by emotion in customer voice, for the angle on this row. One idea per ad. Draft the copy per ad: headline, supporting line, CTA if the layout has one, and the **source ID** for any customer line. Follow `copy-rules.md` in `aca-static-sprint`. Apply the do's and don'ts.

## Copy check: stop and wait for approval
Show a table: `# | ad type | point of view | headline | support | source ID`.

**Stop. Generate nothing until the strategist approves, edits or cuts each line.**

## Step 5: Generate
- One image per approved line, with the reference as a layout guide and **the right product image** from `01-brand/brand-assets/` (right variant, right color, in stock).
- 4:5 unless told otherwise.
- Put headline text in quotes. Don't ask the model to add copy.
- Save to `05-production/statics/<YYYY-MM>/<concept>/`.

## Step 6: QA checklist
Check every image against `02-language/qa-checklist.md` (or `qa-checklist.md` in `aca-static-sprint`). Tag each pass, fix or fail with a one-line reason. Show the fails.

## Step 7: Gut check grid
Show a small grid: each ad next to its reference, with the copy source and QA tag under it. The strategist marks each **keep / fix / cut**. This is the human instinct gut check.

## After the gut check
Suggest `aca-launch-sheet` for the keepers. For a full batch across several rows, use `aca-static-sprint`.

## Never
- Copy a reference's words, logo, product, people or artwork.
- Generate before the copy check is approved.
- Invent testimonials. Every quote traces to a real source ID.

**Agents prepare. People approve.** Nothing is uploaded to an ad account or published from this skill.

## Corrections log
- (empty)

---
name: aca-launch-sheet
description: Takes a finished batch of ads and produces the launch sheet for the media buyer, with each ad's file, its name built from the team's naming convention, its concept matrix row and its hypothesis. Adds one row per concept to the creative pipeline. Never uploads to an ad account. Use when someone says "make the launch sheet", "name these ads", "hand this batch to the media buyer", "add this to the creative pipeline", or runs /aca-launch-sheet.
---

# The launch sheet and the creative pipeline (Course 804, lesson 6.1)

This follows the launching ad campaigns module (601).

## Inputs
- The finished batch: keepers from the gut check board in `05-production/statics/<YYYY-MM>/<batch>/`, or approved videos in `05-production/video/`.
- `04-concepts/concept-matrix.md` for each ad's row and hypothesis.
- `02-language/naming-conventions.md`.
- `06-pipeline/creative-pipeline.md`.

Only ads a person has approved go on the sheet. If an ad has no approval or failed QA, leave it off and say why.

## Step 1: The naming convention
Read `02-language/naming-conventions.md`. **If it doesn't exist, ask first.** Naming conventions are built with the media buyer, so ask the user what the media buyer already uses. Don't make one up.

These are the fields the module suggests. The team picks which ones, in which order, with which separator:

| Field | Example values |
|---|---|
| Producer | Who made it |
| Date | Launch or production date |
| Concept stage | new vs iteration |
| Format | video, static, carousel |
| Ad type | notes app, us vs them, customer review |
| Concept ID | From the matrix row |
| Hook ID | Which hook variation |
| Hook category | From `02-language/hook-categories.md` |
| Talent | Creator or talent name or code |
| VO type | For video |

Save the agreed convention to `02-language/naming-conventions.md` with one worked example, then show the user the example and wait for a yes.

## Step 2: Build the launch sheet
One line per ad:

`file | ad name | matrix row | persona | angle | awareness | ad type | hook ID | hypothesis`

The hypothesis answers the three questions:
1. What am I testing?
2. What do I expect to learn?
3. How will this inform the next iteration?

Take it from the matrix row. For a variation, add what this variation changes. If a field can't be filled from the Creative OS, leave it blank and list it as waiting on the user.

Add a short header: batch name, date, number of ads, the landing page each ad points to, and any notes for the media buyer (offers that end, products that must not run).

Save to `06-pipeline/launch-sheets/<batch>.md`. Offer a CSV. Offer to rename the files to match.

## Step 3: Add to the creative pipeline
One row per **concept**, not per ad, in `06-pipeline/creative-pipeline.md`:

| Column | Filled now? |
|---|---|
| Test (concept name and ID) | Yes |
| Hypothesis and goal | Yes |
| Launch date | Yes, if known. If not, blank |
| Spend and key metrics | **Left blank** |
| Links (launch sheet, files, storyboard or brief) | Yes |
| Learnings and next steps | **Left blank** |

`aca-performance-readout` and `aca-os-update` fill the blanks once there is data. Never fill results in here.

## Step 4: Hand off
Show the sheet and the new pipeline rows. Say what's waiting on the user: the launch date, any blank field, the media buyer's confirmation of the names.

## Rules
- **Agents prepare. People approve.** This skill never uploads to an ad account, never creates campaigns and never changes budgets. The media buyer launches.
- Never invent a hypothesis after the fact. If a batch has none, ask the strategist for it.
- Never change the naming convention without asking. Old names must stay readable.

## Corrections log
- (empty)

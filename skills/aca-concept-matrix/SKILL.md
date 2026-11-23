---
name: aca-concept-matrix
description: Builds the concept matrix with the strategist. Starts from their own concept idea, builds concepts with the concept map (persona, motivator, benefits, offer), lays out persona by angle by awareness level by ad type, marks each square tested, untested or fatigued, prioritizes with six criteria and writes the hypothesis for every prioritized row. Use when someone says "build the concept matrix", "what should we test next", "plan concepts for <brand>", or runs /aca-concept-matrix.
---

# The concept matrix (Course 804, lesson 4.1)

This is the method from the ideation module (401). A concept is the who (persona), the why (motivator) and the what (offer). A concept is not a format.

## Step 0: Think first, then ask
Before you show anything, ask the strategist: **"What's your own concept idea, in one line?"** Wait for it. Their idea goes into the matrix as row 1 and is marked as theirs.

## Step 1: Read
- `04-concepts/personas.md` and `03-research/audience/customer-voice.md`
- the latest `03-research/account/audit-<YYYY-MM>.md`
- `03-research/competitors/` and `03-research/trends/` for white space
- `06-pipeline/creative-pipeline.md` for what has been tested
- `01-brand/offers.md` and `01-brand/dos-and-donts.md`
- `02-language/ad-types.md` for the team's ad types, the three points of view and the awareness level to ad types mapping. If it's missing, copy the starter from `aca-creative-os/templates/ad-types.md` and say so

If a doc is missing, say so. Don't fill the gap.

## Step 2: Concept map
For each concept, fill the four parts:

| Part | Question |
|---|---|
| Persona | Who is this for? (a micro persona with evidence) |
| Motivator | Why do they care? (the emotion behind it) |
| Benefits | What do they get? |
| Offer | What are we asking them to take? |

Personas need evidence in customer voice. One with thin evidence is labeled **candidate**.

## Step 3: Lay out the matrix
Four dimensions: persona × angle × awareness level × format or ad type. Use only angles that trace to research. Use awareness levels in order: unaware, problem aware, solution aware, product aware, most aware. For each square, suggest ad types from the mapping in `02-language/ad-types.md`. The starter mapping is a starting point. Where the audit shows something different for this account, the audit wins. Check `01-brand/dos-and-donts.md` and drop any square that breaks a rule (an out-of-stock product, a banned claim, a discount the brand doesn't allow).

## Step 4: Mark each square
From the creative pipeline and the audit:

| Status | Meaning |
|---|---|
| tested | Has a result. Say which ad and the verdict |
| untested | No ad has run on it |
| fatigued | A winner whose numbers are slipping under the team's fatigue signal |

Ads that are too new are "too early to call", not tested.

## Step 5: Prioritize, and say why
Rank the rows with the six criteria from module 401. Give the reason in one line per row.

1. **High-confidence angles:** strong evidence in research or the account.
2. **Business priorities:** the North Star, stock, launches, offers.
3. **Awareness and the customer journey:** cover the levels the account is missing.
4. **Trends and timing:** moments that will pass.
5. **Resource efficiency:** what can be made from footage, talent or assets we already have.
6. **Structured testing:** rows that isolate one question, so the result teaches something.

Ask how many rows the next sprint can carry. Don't assume.

## Step 6: Write the hypothesis
Every ad is a hypothesis. For each prioritized row, answer:
1. What am I testing?
2. What do I expect to learn?
3. How will this inform the next iteration?

## Output
Save to `04-concepts/concept-matrix.md` with date and sources:

`# | persona | angle | awareness | ad type/format | offer | status | priority reason | hypothesis`

Rows not chosen go to `04-concepts/backlog.md`. In chat, show the top rows and one line on what the matrix still doesn't cover.

Next: `aca-hook-factory` and `aca-script-draft` for video rows, `aca-static-sprint` for static rows.

## Rules
- Never invent personas, numbers or results. Label assumptions.
- Rows must be different enough from each other. Small tweaks read as the same ad to the platform.
- The strategist decides the final order. You recommend.

## Corrections log
- (empty)

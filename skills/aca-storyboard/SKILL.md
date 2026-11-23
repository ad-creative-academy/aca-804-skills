---
name: aca-storyboard
description: Turns an approved script into ACA's storyboard template as a markdown file, with the overview block, optional mood board references, the storyboard table (section, building block, shot type and visual direction, script, supers, done, asset link), a hook variations table and static extensions. Offers a CSV for Sheets. Use when someone says "storyboard this script", "build the storyboard", "turn the script into a shot plan", or runs /aca-storyboard.
---

# Storyboard (Course 804, lesson 4.3)

The scriptwriting and storyboarding module (403) gives two routes: a full storyboard for in-house or studio production with approvals, or a creative production brief for creators. This skill is the first route. For creators, use `aca-creator-brief`.

## Inputs
- An **approved** script in `05-production/scripts/<concept>-approved.md`. If the script isn't approved, stop and say so.
- The row in `04-concepts/concept-matrix.md`.
- `02-language/shot-list.md` (the team's shot list database), if it exists. Use its shot names. If it doesn't exist, describe shots in plain words and offer to start one from this storyboard.
- `01-brand/dos-and-donts.md` and `01-brand/brand-assets/`.

## Part 1: Overview block
This is the storyboard's own mission control. Fill what you know. Ask for the rest. Leave unknowns blank, never made up.

| Field | |
|---|---|
| Concept name | |
| Talent | A role or creator type, or a named person the user gives you |
| Product | |
| Ad type | |
| Disclaimers | |
| Branded vs native | |
| Props | |
| Status | draft |
| Strategist | |
| Editor | |
| Links | script, brief, footage folder |

## Part 2: Mood board references (optional)
List reference links or files the strategist provides, with one line on what to take from each (framing, light, pace). Structure only. Research to inspire, not to copy.

## Part 3: The storyboard table
One row per beat.

`section | building block | shot type and visual direction | script | supers | done | asset link`

- **Section:** hook, body or CTA.
- **Building block:** from `02-language/building-blocks.md`.
- **Shot type and visual direction:** the shot, the setting, the action, where the product is.
- **Script:** the approved words, unchanged. If a line needs to change to fit a shot, flag it. Don't rewrite it.
- **Supers:** the on-screen text, short, inside safe zones.
- **Done** and **asset link:** left empty for the production team to track.

Avoid empty frames. Something should happen in every row.

## Part 4: Hook variations table
`hook # | message | visual | sound (ear stopper) | thumbnail | supers`

Three for a new concept. Each must be visually different, not the same shot with a new line.

## Part 5: Static extensions
A short brief for statics that carry the same concept: the ad type, the headline source, the product image to use. Point to `aca-static-concept` to make them.

## Checks before you show it
- Every script line appears once, in order.
- Supers are spelled right and match the script's meaning.
- Disclaimers from the script draft are carried into the overview.
- The CTA matches the offer and the landing page promise (congruency).
- Nothing in the visual direction breaks a do or don't.

## Output
Save to `05-production/storyboards/<concept>.md`. Offer a CSV of the storyboard table for Google Sheets, saved next to it.

**Agents prepare. People approve.** Show the storyboard to the strategist. Don't send it to an editor, a studio or talent. A person does that after approving it.

End with one line: what's waiting on the strategist (blank fields, talent, props, approvals).

## Corrections log
- (empty)

---
name: aca-creative-qa
description: Checks raw creator footage or finished ads (video or static, one ad or a batch) against the brief, the team's QA checklist and the brand's do's and don'ts. For raw footage it lists which shots and lines are missing. For finished ads it runs the QA checklist and drafts timestamped feedback for the editor or creator. Use when someone says "QA these ads", "check this edit against the brief", "delivery check", "did the creator send everything", "spell check the edits", or runs /aca-creative-qa.
---

# Creative QA (Course 804, lesson 5.5)

**Agents prepare. People approve.** A person approves every comment that goes to an editor or creator, and every final creative decision.

## Inputs
- The ads: video or image files, a review folder through a connector, or links.
- The brief or storyboard for each ad (`05-production/briefs/`, `05-production/storyboards/`).
- `02-language/qa-checklist.md`, the mission control file and `01-brand/dos-and-donts.md`.

## Pick the mode
Ask which one, if it isn't clear.

| Mode | When | Output |
|---|---|---|
| **Footage check** | A creator uploaded raw clips, before editing | What's there, what's missing against the brief, what's unusable. One draft message asking only for what's missing |
| **Delivery check** | After editing | The full checklist below |
| **Quick pass** | Every new edit in the review folder, good for a scheduled run | Only the checks with a right answer |

## Two kinds of checks
- **Checks with a right answer:** spelling, names, prices and offers, banned words and claims, missing shots, disclaimers, safe zones, aspect ratios, length, file names. Be strict.
- **Checks that need taste:** these start from the QA checklist too. Does the hook have the five elements? Are the hook variations different enough? Is there an ear stopper? Is the pacing free of empty frames? Is the hierarchy clear? Where's the feeling? To judge them the team's way, read `02-language/edits-we-loved.md`: three edits your team loved, with a note on why. If that doc doesn't exist, ask the strategist for the three edits and the note on each, and save it. Until it exists, keep taste comments few and label them suggestions.

## How to look at video
Work from what you can get, and say which you had:
1. A transcript of the ad.
2. Frames: one every 1 to 2 seconds, plus the first three seconds frame by frame.
3. The editor's notes.

Don't claim to have seen or heard what you didn't.

## The checklist (per ad)
Use the team's `02-language/qa-checklist.md`. If it doesn't exist, use this one from the growth creative operating system module (704) and offer to save it.

| Check | What to look for |
|---|---|
| Length | Matches the brief |
| Aspect ratios | Every size asked for, rebuilt for the placement |
| Safe zones | Supers and key visuals clear of the platform's top and bottom UI |
| Brand guidelines or native fonts | As the brief says: branded or native |
| Spelling and grammar | Supers, captions, product names, prices |
| Sound quality | Voice clear, music not fighting the voice |
| Hook | Has the five elements (persona, message, visual, sound, thumbnail), and hook variations are different enough |
| CTA | Matches the campaign objective |
| Ear stopper | The first second has a sound that stops the scroll |
| Pacing | No empty frames |
| Hierarchy and congruency | Clear focal point. The promise and offer match the landing page |

Then, against the brief and the do's and don'ts: claims allowed, disclaimers present, no out-of-stock products, building blocks in the storyboard's order. Where's the feeling?

## Output
1. A table per batch: `ad | verdict (approve / fix / reject) | top issue | notes`.
2. For every "fix", **timestamped feedback** in the editor's language, for example `00:02 to 00:04, super says "alumnium", should be "aluminum"`.
3. Save to `05-production/qa/<batch>-qa.md`.

**Stop. Show the feedback for approval. Don't post comments to a review tool, Slack or email, and don't message creators, until the user says so.**

## Corrections log
When the user overrides a verdict ("that's fine, we allow that"), add the rule here with the date.
- (empty)

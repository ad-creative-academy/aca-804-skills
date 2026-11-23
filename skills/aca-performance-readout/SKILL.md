---
name: aca-performance-readout
description: The weekly performance readout, built for a scheduled run before the performance review meeting. Starts with the North Star, then what launched, top creatives and movers, the symptom and creative lever for each ad that matters, creative problem vs market problem, win criteria, patterns across four tags, three new customer quotes, and what to make next as More, Fix, Adapt and New candidates. Use when someone says "weekly readout", "performance readout", "what should we make next", "prep the performance review", or runs /aca-performance-readout.
---

# The performance readout (Course 804, lesson 6.3)

One page the team reads before the performance review meeting. It doesn't replace the strategist's judgment in the meeting.

## Before you start
- Read the mission control file and **`02-language/how-we-read-the-ad-account.md`**. Those are the team's rules. **Benchmarks are account-specific. Never invent one.** If the rules doc is missing, report raw numbers, say so, and suggest `aca-account-audit`.
- Read `06-pipeline/creative-pipeline.md` and the latest launch sheets.
- Data: a read-only ad data connector or an export in `00-inbox/`. Window: the last 7 days against the 7 before, unless told otherwise.

## What goes in the readout
1. **North Star first:** where it stands against the target, and spend for the window.
2. **What launched:** new concepts since the last readout, each with its hypothesis.
3. **Top creatives and movers:** what is carrying spend, what moved up, what moved down.
4. **Symptom and creative lever**, for each ad that matters:

| Symptom | Creative lever |
|---|---|
| Low first-frame retention | Thumbnail or the first second |
| Low hook rate | The first three seconds |
| Low hold rate | Reorder clips, new shots, make it shorter |
| Low CTR | Scarcity, social proof, credibility, a new CTA |
| Low conversion rate | Check congruency with the landing page |

"Low" means low against this account's own benchmarks.

5. **Creative problem or market problem:** put CPM next to ROAS for the window. Say whether the move shows up across the account or on specific ads, and label your read as a read. Ask the team if their rules doc doesn't cover it.
6. **Win criteria**, from Chloe Rhys's sprint planning module (703). An ad is called a winner when it beats the CPA goal, at scale (about 20 times the CPA in spend), across several variants, and holds for 5 to 7 days or more. Anything short of that is **"too early to call"**. If the team's rules differ, theirs win.
7. **Patterns:** tag each ad on four dimensions (visual, persona, messaging, hook) and report what the top ads share and what the weakest share. Study the top to raise the ceiling, the weakest to raise the floor.
8. **Three new customer quotes:** verbatim, with source IDs.
9. **What to make next**, as candidates for the next sprint. Use the four request types from Chloe Rhys's sprint planning module (703):

| Request type | What it is |
|---|---|
| More | Iterate on a winner |
| Fix | A near-miss. Change one or two things |
| Adapt | Take a proven structure, angle or format (your own or another brand's) to a new product or persona |
| New | A net-new, untested concept |

A Fix names the symptom and the creative lever. An Adapt names the proven structure, angle or format it borrows and where it's going. A New points to an untested row in the concept matrix. Each candidate carries its evidence. The team decides.

## Format
Plain text that reads well in Slack or email. Around 400 words. Every number has its time window and spend. Leave out sections with no data, and say what wasn't connected.

## After writing
- Save to `06-pipeline/readouts/<YYYY-MM-DD>.md`.
- Fill spend, key metrics and a one-line learning in the matching rows of the creative pipeline.
- Suggest `aca-iteration` for More, Fix and Adapt, `aca-concept-matrix` for New, and `aca-sprint-plan` for the week.

## Delivery
**Agents prepare. People approve.** Draft the message. A person sends it, unless the scheduled run was explicitly set up to post to one channel. Then it posts there and nowhere else. It never messages clients or creators and never changes an ad account.

## Rules
- Follow the team's rules on what counts as proof. Say "early signal" when it is one.
- Never invent numbers, quotes or benchmarks. A missing metric stays missing.

## Corrections log
- (empty)

---
name: aca-account-audit
description: Runs the ad account audit from ACA's research module, read the team's way. Mode 1 is a quick performance analysis (unicorn ad, 30-day snapshot, 7-day vs 30-day stability, hook rate and hold rate, six-month trend). Mode 2 is an in-depth creative audit that ends in creative principles, a creative mix, a testing plan and benchmarks for this account. Use when someone says "audit the ad account", "what's working in the account", "find the unicorn ad", "quick performance analysis", or runs /aca-account-audit.
---

# Ad account audit (Course 804, lesson 3.1)

The ad account is the first of the four research pillars in the research module. Say three cautions at the start, as cautions and not as facts about this account:
- Retargeting is not proof for new customers.
- Small spend is an early signal, not a winner.
- "Just because an ad is running doesn't mean it's working."

## Before you start
1. Read the mission control file for the North Star and targets.
2. Read `02-language/how-we-read-the-ad-account.md`. These are the team's reading rules. If the doc doesn't exist, run Mode 1 and then build it with the strategist (see "The team's reading rules" below).
3. Get the data: an ad data connector (read-only) or an export in `00-inbox/`. Say the time window and what you had.

Benchmarks are account-specific. Never supply your own.

Ask which mode. Default to Mode 1.

## Mode 1: Quick performance analysis
1. **Find the unicorn ad:** disproportionate spend and staying power. Reverse engineer it with the building blocks (hook, body, CTA, persona, angle, awareness level, ad type).
2. **30-day snapshot:** formats, top ads by conversion rate and ROAS, angles, styles.
3. **7-day vs 30-day stability check:** where the last 7 days are worse than the 30-day picture, flag fatigue.
4. **Hook rate and hold rate** for video:
   - hook rate = 3-second views / impressions
   - hold rate = ThruPlays / impressions
5. **Six-month trend**, if the data exists: evergreen vs seasonal.

Conclude with five short sections: iteration opportunities, creative gaps, red flags, low-hanging fruit, and how each ad that matters compares to the unicorn.

## Mode 2: In-depth creative audit
Start from the goals and the North Star. Then compare, where the data allows:

| Compare | |
|---|---|
| Format | Video length |
| Branded vs native | Text, voiceover, music |
| Opening shot (person, product, problem) | Problem-first vs solution-first |
| Features vs benefits | Emotional vs rational |
| Demographics | Cold vs warm audiences |
| Production cost vs return | Creative lifespan |

Say which comparisons you could not run and why. Output:
- 3 to 5 creative principles for this account, each with its evidence
- the creative mix (what share of spend sits in which formats and ad types)
- a testing plan where every test has a hypothesis: what are we testing, what do we expect to learn, how will this inform the next iteration
- benchmarks for this account, from this account's own numbers

## The team's reading rules
The rules for reading this account live in `02-language/how-we-read-the-ad-account.md`. They come from the quick performance analysis, not from the agent. After Mode 1, draft the doc with these sections and **ask the strategist to confirm or correct each one before you save it**:

| Section | What the team writes down |
|---|---|
| What we're trying to achieve | The North Star and the targets |
| The unicorn ad | Which ad it is, and why. The ad every other ad is compared with |
| The 30-day snapshot | Which campaigns we look at when we judge new concepts, and which we leave out |
| 7 days vs 30 days | What a drop between the two means here, and when we call it fatigue |
| Hook rate and hold rate | How we calculate them, and what each one tells us to change |
| Our benchmarks | From this account's own numbers. Account-specific, with the date they were set |
| The house line | "Just because an ad is running doesn't mean it's working." What that means here: retargeting, small spend, discounts |

A cell the strategist can't answer yet stays blank. `demo-brand/example-docs/how-we-read-the-ad-account.md` in the course library shows a filled example.

## Verdict labels
Give every ad one label, with spend and time window next to it.

| Label | Meaning |
|---|---|
| unicorn | Disproportionate spend and staying power |
| winner | Meets the team's win criteria |
| fatiguing | A winner whose recent numbers or fatigue signal are slipping |
| early signal | Promising, under the minimum spend |
| left out | Not used to judge new concepts under the team's rules (for example retargeting) |
| failed | Had real spend and missed the target |
| paused | Off for a reason other than results (for example out of stock) |

## Output
Save to `03-research/account/audit-<YYYY-MM>.md` with a summary line, source and date. In chat, show the unicorn, the verdict table and the three most useful next moves.

## Rules
- Never invent numbers or benchmarks. A blank cell stays blank.
- Read-only access. Never change anything in an ad account.

## Corrections log
- (empty)

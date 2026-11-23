---
name: aca-os-update
description: The weekly Creative OS update, built for a scheduled run before the performance review meeting. Finds what changed since the last run (new reviews and comments, new account data, competitors, meeting notes, the inbox), updates the right docs with a dated line, adds results to the creative pipeline, and flags stale docs and contradictions. Use when someone says "update the OS", "what changed this week", "weekly OS update", or runs /aca-os-update.
---

# OS update (Course 804, lesson 2.3)

A Creative OS is only useful while it's true. This skill is the weekly habit that keeps it true. It works best as a scheduled run in the cloud (the app feature is called Routines), so it runs with the laptop closed. It does not write the weekly message for the team. That is `aca-performance-readout`.

## Before you start
- Read the mission control file (`CLAUDE.md` / `AGENTS.md`) for the do's and don'ts, the North Star and where things go.
- Read `06-pipeline/os-update-log.md` to find the date of the last run. If it doesn't exist, use the last 7 days.

## What changed since the last run
Use whatever is connected. Skip what isn't, and say so.

| Source | What to do | Where it goes |
|---|---|---|
| New reviews, ad comments, support tickets | Run the `aca-copy-mining` steps on the new items only | `03-research/audience/customer-voice.md` |
| New account data (connector or an export in `00-inbox/`) | Run the rules in `02-language/how-we-read-the-ad-account.md`, the same ones `aca-account-audit` uses | `03-research/account/` and `06-pipeline/creative-pipeline.md` |
| Competitors listed in `03-research/competitors/competitor-list.md` | Note ads launched or still running. Structure and insight only | `03-research/competitors/<brand>.md` |
| New meeting notes and decisions | File the decisions, rules and open questions | `02-language/how-we-work.md` or `01-brand/` |
| Anything in `00-inbox/` | File it with the `aca-knowledge-doc` steps | The right folder |

## Read the account our way
Don't copy numbers across. For each ad that matters, write what happened (number, spend and time window), what we think it means, and how sure we are. Apply the team's rules. Benchmarks are account-specific, so never bring your own. If `how-we-read-the-ad-account.md` doesn't exist, report the raw numbers, say the rules are missing, and suggest running `aca-account-audit`.

Remember that an ad still running is not proof that it's working.

## Update the docs
- Update each doc in place with a dated line at the top: `Updated <date>: <what changed>`.
- In `06-pipeline/creative-pipeline.md`, fill in spend, key metrics and a one-line learning for each concept that has new data. Ads that are too new stay "too early to call".
- Add new ideas to `04-concepts/backlog.md` with the evidence that sparked them.

## Flag, don't fix silently
List these for a person to decide:
- docs that should be live but haven't changed in 60 days or more (personas, competitors, offers)
- contradictions between docs (two different CPA targets, for example). Show both sources
- do's and don'ts in mission control that the newest material contradicts
- anything in the inbox you couldn't place

## Output
1. A short update note in chat (or saved by the scheduled run): what changed, which docs were updated, what was flagged, what's waiting on a person.
2. One line in `06-pipeline/os-update-log.md` with the run date and a summary.

## Access for the scheduled run
Read-only connectors, plus write access to the OS folder. Nothing else.

**Agents prepare. People approve.** This skill reads sources and writes to the Creative OS only. It never messages clients or creators, never posts to a channel, and never changes an ad account.

## Corrections log
- (empty)

---
name: aca-creative-os
description: Builds a brand's Creative OS, the shared strategy layer every agent and team member works from (common language, shared knowledge and how we work, in one folder). Scaffolds the folder and the mission control file, walks through the brief essentials, sets up the common language (including a starter ad types doc), runs a kickoff interview, then files the user's material one input at a time. Use when someone says "build a Creative OS for <brand>", "set up the OS", "onboard the agent on this account", or runs /aca-creative-os.
---

# Creative OS builder (Course 804, Module 2)

A Creative OS is the shared strategy layer: common language, shared knowledge, and how we work, in one folder. It comes from the growth creative operating system module (704). Build it with the strategist, one piece at a time.

## Rules
- **Never invent.** No made-up numbers, personas, quotes or competitors. If something is missing, ask.
- When two sources disagree, show both and ask. Never pick one silently.
- If you have to assume something to keep going, label it **Assumption:** so a person can confirm it.
- No empty folders and no placeholder files.

## Step 1: Name and location
Ask for the brand name and where `<brand>-os` should live (ideally synced to GitHub or a shared drive). Wait for the answer.

## Step 2: Scaffold
```
<brand>-os/
  CLAUDE.md / AGENTS.md  # mission control file
  00-inbox/        # raw drops
  01-brand/        # the brief essentials, brand-assets/
  02-language/     # common language and how we work
  03-research/     # account/ audience/ competitors/ trends/
  04-concepts/     # personas, concept matrix, backlog
  05-production/   # storyboards, briefs, statics, video, landing pages, qa
  06-pipeline/     # creative pipeline, launch sheets, learnings, sprint plans
  .claude/skills/  .agents/skills/
```
Create a folder only when its first real doc exists.

Write the mission control file from `templates/CLAUDE.md` and copy it to `AGENTS.md`. Think of it as the brief you'd give a new team member on day one:
1. Who the brand is and what we're trying to achieve (the North Star).
2. The rules we never break.
3. Who approves what.
4. Where things live.

Keep it under a page. It points to docs and never copies them. Fill it in as the steps below give you the answers.

## Step 3: The brief essentials first
Walk through the eleven items one at a time. File each answer and say where it went.

| # | Brief essential | File |
|---|---|---|
| 1 | Target audience | `04-concepts/personas.md` (candidates labeled) |
| 2 | Competitors | `03-research/competitors/competitor-list.md` |
| 3 | Branded vs native, or both | `01-brand/brand-guidelines.md` |
| 4 | Product info | `01-brand/products.md` |
| 5 | Breaking-resistance messaging | `01-brand/messaging.md` |
| 6 | Benefits, features, USPs | `01-brand/messaging.md` |
| 7 | Promotions and offers | `01-brand/offers.md` |
| 8 | Platforms | `01-brand/brief-essentials.md` |
| 9 | Campaign objective and North Star | `01-brand/brief-essentials.md` |
| 10 | Previous learnings | `06-pipeline/learnings.md` |
| 11 | Brand guidelines, do's and don'ts | `01-brand/dos-and-donts.md`, summarized in mission control |

## Step 4: Common language
**Ask which of these the team already has before writing anything:** building blocks, ad types, hook categories, glossary, QA checklist, naming conventions. Copy in what exists, in the team's own words. Build the missing ones with the strategist. Save each to `02-language/`.

**Ad types.** If the team has no ad types doc, copy `templates/ad-types.md` to `02-language/ad-types.md`. It lists the video and static ad types, the three points of view (brand voice, customer voice, expert voice) and a starter awareness level to ad types mapping. Tell the strategist the mapping is a starting point and should be replaced with their own account's learnings. `aca-concept-matrix` and `aca-static-concept` read this doc.

**How we read the ad account.** Don't write `02-language/how-we-read-the-ad-account.md` here. `aca-account-audit` builds it from the account's own numbers.

## Step 5: The kickoff interview
Run a kickoff interview, the way you'd run a kickoff call with a new strategist. Ask one question at a time and wait for each answer:
1. What is the North Star, and where does it stand today?
2. What is the budget, and what would make you scale it?
3. What is working right now, and why do you think it works?
4. What have you tried that didn't work?
5. What would you never say or show?
6. Which tools does the team use, and where does the work live?
7. Who sits in which seat, and who approves what?

File the answers under `02-language/how-we-work.md`, update the mission control file, and list the open questions.

## Step 6: Feed inputs, one at a time
For each voice note, meeting transcript or export: read it next to what's already filed, save the useful parts with source, date and a one-line summary, say where each part went and why, then ask **one** follow-up question.

## Step 7: Brand assets
Ask for product images (every color and variant, packaging, logo) and save them to `01-brand/brand-assets/`. The static skills point here.

## Step 8: Keep it true
Offer to schedule `aca-os-update` weekly, before the performance review meeting.

## Step 9: Health check (on request)
Report stale docs, duplicates, contradictions and empty folders. **Ask before moving or deleting anything.**

End every session with one line: what's waiting on the user.

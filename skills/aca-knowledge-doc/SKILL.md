---
name: aca-knowledge-doc
description: Turns any raw input (a meeting transcript, a voice note, a video transcript, a Slack thread, a data export, a link or pasted notes) into one clean, sourced knowledge doc and files it in the right folder of the Creative OS. Decides which layer it belongs to (common language, shared knowledge, or how we work). Use when someone pastes material and says "file this", "add this to the OS", "make a knowledge doc", "remember this for the brand", or runs /aca-knowledge-doc.
---

# Knowledge doc maker (Course 804, Module 2)

Onboarding an agent works like onboarding a new team member. They need the common language, the shared knowledge and how we work. Your job is to take messy input and turn it into one doc an agent or a team member can use later. Keep what matters, drop the noise, and never invent anything.

## Step 1: Decide the layer
Say which layer it belongs to, in one line.

| Layer | What it is | Examples | Home |
|---|---|---|---|
| **Common language** | The words and frameworks the team shares | Building blocks, ad types, hook categories, glossary, diversification guide | `02-language/` |
| **Shared knowledge** | What we know about the brand, the customer and the market | Product info, offers, reviews, audits, competitor notes, trends, learnings | `01-brand/`, `03-research/`, `06-pipeline/` |
| **How we work** | The team's own documentation | Brief essentials, do's and don'ts, naming conventions, QA checklist, who owns what, meeting decisions, how we read the ad account | `02-language/` or `01-brand/` |

If the folder's mission control file (`CLAUDE.md` / `AGENTS.md`) says something different, follow it.

## Step 2: Pull out what matters
- **Common language:** terms and their meaning, steps, examples, do and don't rules, in the source's own words.
- **Shared knowledge:** facts with their source, verbatim customer or founder quotes, numbers with the time window. Keep raw numbers apart from what we think they mean. If a number could mislead (a retargeting ad with a high ROAS), say why in one line.
- **How we work:** decisions (who decided, when), rules and limits ("never say detox"), goals, people and seats, tools and where things live, open questions.

## Step 3: Write the doc

```markdown
---
title: <clear title>
layer: common language | shared knowledge | how we work
source: <link, file name or "voice note from X">
date_added: <YYYY-MM-DD>
summary: <one line that says what this doc covers and when to use it>
---

# <title>

## Key points
- ...

## Rules and decisions (if any)
- ...

## Open questions and contradictions
- ...
```

Rules:
- Keep customer and founder quotes verbatim. They're gold for copy.
- Mark anything uncertain as **Assumption:**.
- If the input contradicts an existing doc, don't overwrite. Show both under "Open questions and contradictions" and tell the user.
- One topic per doc. If the input covers three topics, update three docs.

## Step 4: File it
1. Look at the existing folders first. Update a doc if one fits. Create a new one only if nothing fits.
2. Name files in lowercase with hyphens, for example `founder-priorities-q4.md`.
3. Customer language goes to `03-research/audience/customer-voice.md`. Account numbers go to `03-research/account/`. Results of tests go to `06-pipeline/creative-pipeline.md`.
4. Tell the user in two or three lines: what you saved, where, and why there.
5. Ask **one** follow-up question that would make the doc more useful (for example "What made the calendar ad work, in your view?").

## Never
- Invent facts, numbers, names or quotes.
- Paste a whole transcript as the doc. Summarize, then keep the best verbatim lines.
- Store passwords, API keys, card numbers or customers' personal data.
- Move or delete an existing doc without asking.

## Corrections log
- (empty)

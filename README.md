# ACA Course 804: The Agentic Creative Strategist, skill library

Skills and demo materials for Ad Creative Academy Course 804. A skill is a training doc your agent can run: the same thing you'd write to onboard a junior strategist. The library follows the creative strategy workflow you know from the ACA program: research, ideation and briefing, production, launch, analysis and iteration. Every lesson ends with a skill you can run.

## What's inside

```
skills/                     # the ACA skills, one folder each (SKILL.md + supporting files)
demo-brand/
  brisa-brand-brief.md      # the fictional demo brand + prompts for Lovable and Claude Design
  brisa-raw-materials/      # fictional reviews, comments, ad export and transcripts
  example-docs/             # reference docs used in demos (how we read the ad account)
  example-skills/           # reference Brisa skills: a one-path skill and a playbook skill
```

| Module | Skill | What it does |
|---|---|---|
| M1. Foundations: your first AI agent | `aca-setup-check` | Checks your agent workspace (Claude Code or Codex) and creates your practice folder |
| M1 | `aca-skill-builder` | Turns a task you already do into a one-path skill or a playbook skill |
| M2. The Creative OS | `aca-creative-os` | Builds a brand's Creative OS: mission control file, brief essentials, common language, shared knowledge |
| M2 | `aca-knowledge-doc` | Turns any transcript, link, export or notes into one filed knowledge doc |
| M2 | `aca-os-update` | Weekly update of the OS, built for a scheduled run |
| M3. Research agents | `aca-account-audit` | The ad account audit: unicorn ad, stability check, creative principles, and the team's reading rules |
| M3 | `aca-copy-mining` | Collects verbatim customer quotes, sorts them by emotion into angles, fills micro persona sheets |
| M3 | `aca-competitor-research` | Competitor framework and trends. Research to inspire, not to copy |
| M3 | `aca-site-watch` | Checks a page on a schedule and reports when the offer, the price or the promise changes |
| M4. Ideation and briefing agents | `aca-concept-matrix` | Builds and prioritizes the concept matrix, with a hypothesis per row |
| M4 | `aca-hook-factory` | Playbook skill: three hooks for a new concept, ten for a winner |
| M4 | `aca-script-draft` | Drafts a script in building blocks, reviews it, stops for your edit |
| M4 | `aca-storyboard` | Turns an approved script into the storyboard template |
| M4 | `aca-creator-brief` | Writes the creative production brief for a creator |
| M5. Production agents | `aca-static-concept` | One concept matrix row in, statics out, with a copy check and a gut check |
| M5 | `aca-static-sprint` | The AI creative sprint for statics: matrix rows → copy check → generate → QA → gut check board → variations |
| M5 | `aca-casting` | Casts creators to persona, scores them, drafts outreach a person sends |
| M5 | `aca-creative-qa` | Checks raw footage and finished ads against the brief and the QA checklist |
| M6. Launch, analysis and iteration | `aca-launch-sheet` | Names the ads, writes the launch sheet, adds concepts to the creative pipeline |
| M6 | `aca-ad-to-landing-page` | Turns a winning ad into a landing page that keeps the promise |
| M6 | `aca-performance-readout` | Weekly readout: North Star, creative levers by symptom, what to make next |
| M6 | `aca-iteration` | Playbook skill: six iteration plays for winners and near-misses |
| M6 | `aca-sprint-plan` | Plans the next sprint: volume, the More / Fix / Adapt / New mix (Chloe Rhys, module 703), jobs, meeting agendas |
| M7. Your agentic team | `aca-org-chart` | Builds the agentic team org chart: which seat an agent takes, and who it reports to |
| M7 | `aca-capstone-check` | Reviews your capstone against the rubric |

25 skills in total.

## Your starter ad types doc

`skills/aca-creative-os/templates/ad-types.md` is a starter "common language" doc. It lists ACA's video ad types and static ad types, the three points of view (brand voice, customer voice, expert voice) and a starter mapping of awareness level to ad types for the five stages. `aca-creative-os` copies it to `02-language/ad-types.md` in your Creative OS, and `aca-concept-matrix` and `aca-static-concept` read it. The mapping is a starting point. Replace it with your own account's learnings.

## The Creative OS folder layout

Every skill reads from and writes to the same folder structure, built in Module 2 with `aca-creative-os`:

```
<brand>-os/
  CLAUDE.md / AGENTS.md   # mission control file
  00-inbox/               # raw drops
  01-brand/               # the brief essentials: products, offers, voice, do's and don'ts, brand-assets/
  02-language/            # common language and how we work
  03-research/            # four pillars: account/ audience/ competitors/ trends/
  04-concepts/            # personas, concept matrix, backlog
  05-production/          # storyboards, briefs, statics, video, landing pages, qa
  06-pipeline/            # creative pipeline, launch sheets, learnings, sprint plans
  .claude/skills/  .agents/skills/
```

## Install (the easy way)

Open your Creative OS folder in Claude Code or Codex and paste:

> Clone https://github.com/ad-creative-academy/aca-804-skills into a temporary folder. Copy every folder inside `skills/` into `.claude/skills/` in this folder (for Claude Code) and into `.agents/skills/` (for Codex). Don't overwrite any skill I already have with the same name; ask me first. Then list what you installed.

Then fully quit and reopen the app.
- **Claude Code:** type `/` to see the skills, for example `/aca-creative-os`.
- **Codex:** type `$` to see the skills, for example `$aca-creative-os`.

You can also describe the task in your own words. The agent reads each skill's description and picks the right one.

## Using the skills on your own brand
The skills point to docs in the Creative OS. They don't carry brand rules themselves. If your folders are named differently, tell the agent once, or update your mission control file (`CLAUDE.md` / `AGENTS.md`).

## Adapt them
These are our starting points. Open each `SKILL.md`, read it, and change it to match how you work. A skill is only as good as the strategist who wrote it, so put your own expertise in: your plays, the headlines you'd cut next to the ones you'd keep, your rules for reading the ad account, your own awareness level to ad types mapping. Most skills have a corrections log, so they get better every time you correct them.

## Safety
- **Agents prepare. People approve.** Skills never send messages, publish, upload to ad accounts or spend money without a person approving it first. Keep it that way when you edit them.
- Give agents read-only access first. Add more only where the job needs it.
- Never put passwords, API keys or customer personal data in your Creative OS or your skills.

---
Brisa is a fictional brand created for teaching. All data in `demo-brand/` is invented.

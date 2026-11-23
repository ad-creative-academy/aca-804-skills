---
name: aca-skill-builder
description: Interviews a creative strategist and turns a task they already do into a skill, a training doc an agent can run in Claude Code or Codex. Decides whether it should be a one-path skill or a playbook skill (several plays plus a when-to-use guide). Use when someone says "turn this into a skill", "let's build a skill", "make this repeatable", or runs /aca-skill-builder.
---

# ACA skill builder (Course 804, lessons 1.5 and 1.6)

A skill is a training doc your agent can run. The strategist is the expert. You write it down properly. **Never invent their process, their taste, their plays or their definition of "good".** Draw it out, organize it, test it.

## Two ways in
- **From a job you already did together.** The strategist did the task with an agent and liked the result. Give the agent the transcript and ask it to write the training doc. Every edit the strategist made along the way goes in as a rule.
- **From a blank page.** Interview them, one question at a time, the way you'd ask a senior strategist to explain a task to a junior.

## Step 1: One job
Confirm the job in one sentence: "This skill takes ___ and produces ___ for ___."

## Step 2: One-path or playbook?
Ask: "Do you do this the same way every time, or does the right approach change with the situation?"

| Type | When | Example |
|---|---|---|
| **One-path skill** | Same steps every time. Only the input changes | A weekly performance summary |
| **Playbook skill** | Several valid plays, and choosing between them takes judgment | Creative levers by symptom, or the three-part winner playbook (talent refresh, format variation, modular remixing) |

Say which you think it is and why. Let them overrule you.

## Step 3: The interview
For every skill, capture in this order:
1. **Trigger:** what would someone type?
2. **Inputs:** files, folders, connectors, links.
3. **Steps:** in the order they really do them.
4. **Knowledge:** which docs in the Creative OS should be read first?
5. **Output:** ask for a real example of a good one.
6. **Checks:** how they'd know it's good, and what would make them reject it.
7. **Approvals:** where the agent must stop and wait for a person.

For a playbook skill, also capture:
1. **Plays:** every distinct way the job can be done, each with a short name.
2. **For each play:** what it does, when to choose it, when not to, its steps, its output, its checks.
3. **When to use:** short rules for choosing between plays.

If you see a gap, describe the situation and ask. Don't fill it yourself.

**Before writing any files, show the full map (the job, the plays, when each is chosen, the gaps) and wait for a yes.** Silence is not a yes.

## Step 4: Write the files
- **One-path skill:** one folder, one `SKILL.md`, from `templates/one-path-SKILL.md`.
- **Playbook skill:** from `templates/playbook-SKILL.md`, `templates/when-to-use.md` and `templates/play.md`:

```
<skill-name>/
  SKILL.md         # shared steps, inputs, output, checks
  when-to-use.md   # how to choose the play
  plays/<play>.md  # one file per play
```

Rules for every skill:
- Frontmatter has only `name` (lowercase, hyphens, same as the folder) and `description`. The description says what it does and when to use it.
- Point to docs in the Creative OS. Don't copy brand rules in.
- Put approval points in bold. If the skill makes anything for the outside world, add: **Agents prepare. People approve.**
- End with a `## Corrections log` section for dated rules.

## Step 5: Save and test
Save to `.claude/skills/<skill-name>/` (Claude Code) and `.agents/skills/<skill-name>/` (Codex) inside the Creative OS folder. Run with `/skill-name` or `$skill-name` after restarting the app.

Run it once on a real input. Ask: "What would you change?" Add every answer to the corrections log as a rule.

## A skill someone else wrote
A skill is only as good as the strategist who wrote it. Look at their ads before you install their skill. Then read it first, the way you'd read a training doc from another agency. Keep what fits how your team works and rewrite the rest. Never run a skill you haven't read.

## Step 6: Put it on the calendar
Ask whether it should be a scheduled run (the app feature is called Routines). If yes, agree the day and time, where the output goes, and read-only access.

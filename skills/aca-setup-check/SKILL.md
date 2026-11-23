---
name: aca-setup-check
description: Checks that a new student's agent workspace (Claude Code or Codex) is ready for ACA Course 804 (desktop app, paid plan, Git, a working folder, connectors, privacy setting), fixes gaps one step at a time, and creates their first practice folder. Use when someone says "check my setup", "am I ready for 804", or runs /aca-setup-check.
---

# ACA setup check (Course 804, lesson 1.2)

You are helping a creative strategist who may have never opened a terminal. Be warm, plain and patient. One step at a time. Never show more than one instruction before they confirm it worked.

## What "ready" means

1. They are in an **agent workspace**: Claude Code (desktop app, Code tab) or Codex (desktop app), not the regular chat. A chatbot answers. An agent does the job.
2. They are on a **paid plan** (Claude Pro/Max or ChatGPT Plus/Pro). The free tier won't run this course.
3. **Git is installed** (Claude Code needs it to read and edit files).
4. They have a **working folder** open.
5. At least **two connectors** are live (for example Google Drive and Notion, or Gmail and Slack).
6. Model training on their data is **switched off** if they will use client material.

## How to run

1. Say what you're about to check, in one sentence.
2. Run the checks you can do yourself, without asking:
   - `git --version` (if it fails, go to "Install Git" below)
   - list the current working folder
   - list the connectors and tools you can see
3. Report back as a short checklist: done or missing, one line each.
4. Fix the first missing item only. Wait for "done" before moving to the next.

### Install Git (only if missing)
Ask: "Are you on a Mac or a PC?" Then:
- **Mac:** open Terminal (Cmd + Space, type "terminal"). Paste `git --version`. If a popup offers "Command Line Developer Tools", click Install and Agree. It can take up to 20 minutes. If asked to install Homebrew, that's normal.
- **PC:** download Git for Windows from git-scm.com, accept the defaults, then restart the app.

Then ask them to fully quit and reopen the desktop app and run this skill again.

### Connectors
Point them to where connectors live in their app (in Claude: Customize → Connectors). Suggest starting with the tools they already use every day: email, calendar, Google Drive, Notion or Airtable, Slack. Start with read-only access where the tool offers it. If a tool isn't listed, tell them to search "<tool name> MCP".

## Create the practice folder

When everything passes, offer to create a folder called `aca-804-practice` with one file, `about-me.md`. Ask three questions, one at a time:
1. What's your role and where do you work?
2. Which brands or clients do you work on?
3. What's one task you do every week that you'd love to hand to an agent?

Save the answers to `about-me.md` in plain markdown. Then explain in two sentences: "This is your first knowledge doc. From now on, anything in this folder is something I can read before I answer you."

## Tone rules
- No jargon without a one-line explanation (for example "Git is the tool that lets me read and change files on your computer.").
- Never make them feel slow.
- If something looks different from these instructions, ask for a screenshot and the full error text.

## Ground rules to say once
- **Agents prepare. People approve.** Nothing is sent, published, uploaded or paid for without a person's approval.
- No passwords, API keys or customer personal data in any folder the agent reads.

## Output
End with a short "You're ready" checklist, one line on what's waiting on them (if anything), and one suggested next step: "Open lesson 1.3."

---
name: aca-org-chart
description: Builds the agentic team org chart for a creative team. Lists the seats on the team, asks what each seat does in a normal sprint, decides task by task whether an agent does it, an agent prepares and a person approves, or a person does it, then defines each agent's job, skills, access and reporting line. Recommends the next three agents to set up. Use when someone says "build our agentic team", "which seat can an agent take", "where can agents help", "org chart for agents", or runs /aca-org-chart.
---

# The agentic team org chart (Course 804, lesson 7.1)

An AI agent is one team member. An agentic team is a whole pod. This skill answers one question for every task: which seat can an agent take, and who does it report to?

The seats come from the growth creative operating system module (704).

## Step 1: The seats
List the seats and ask which ones exist on this team, and who sits in each. One person can hold several.

| Seat |
|---|
| Creative strategist |
| Media buyer |
| Talent manager |
| Production manager |
| Video editors and graphic designers |
| QA and compliance coordinator |
| AI and automation specialist |

## Step 2: What each seat does in a normal sprint
For each seat, ask: "Walk me through what this seat does in a normal sprint." Also read `02-language/how-we-work.md` and the latest sprint plan, if they exist. Write tasks down in their words. Don't add tasks they didn't mention.

## Step 3: Decide, task by task
For every task, pick one, with a one-line reason:

| Decision | Use it when |
|---|---|
| **An agent does it** | Same steps each time, inputs an agent can reach, nothing leaves the team |
| **An agent prepares, a person approves** | Anything that goes to the outside world, costs money, or needs taste |
| **A person does it** | It needs their judgment, their relationships, or it keeps them close to the customer |

The strategist can overrule any decision.

## Step 4: Define each agent
An agent has one job. For every agent on the chart, write:

| Field | |
|---|---|
| Job | One sentence |
| Seat it supports | |
| Skills it runs | For example `aca-os-update`, `aca-performance-readout`, `aca-creative-qa` |
| Access | **Read-only first.** List each connector and folder. Add write access only where the job needs it |
| When it runs | On request, or a scheduled run (day and time) |
| Reports to | A named person |
| Where a person approves | The exact point |
| Where its output lands | One folder or one channel |

## Step 5: Recommend
- **The next three agents to set up**, in order, each with the reason. Start where the pain is weekly and the access is simple.
- **One or two tasks to keep by hand on purpose**, even if an agent could do them, because they keep the team close to the customer or the account. For example, reading reviews yourself once a month.

## Output
Save to `02-language/agentic-team.md`, with date and a summary line:
1. A simple text org chart, for example:

```
Creative strategist (name)
├── Agent: OS update (weekly) → reports to the strategist
├── Agent: performance readout (weekly) → reports to the strategist
Media buyer (name)
└── Agent: launch sheet (on request) → approved by the media buyer
```

2. The task table: `seat | task | decision | reason`.
3. One block per agent with the fields above.
4. The next three agents, and the tasks kept by hand.

Offer to build the first agent's skill with `aca-skill-builder`.

## Rules
- **Agents prepare. People approve.** No agent on the chart sends, publishes, uploads or pays without a person's approval.
- Never invent tasks, time estimates or savings.
- No agent gets passwords, API keys in files, or customer personal data.

## Corrections log
- (empty)

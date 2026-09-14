---
type: plan
status: not-started
tags:
  - type/plan
---
# Interview rubric

← [[00-Home|Home]] · [[Schedule]] · [[Glossary]]

Use this sheet after every timed design. Score each row from **1** to **5**.

A passing mock is **28 / 40** or higher, with no row at 1.

## Score guide
- **1** — Missing or wrong. Interviewer must drag you.
- **2** — Partial. Large gaps. Weak numbers or no trade-off.
- **3** — Solid hire bar. You lead. Some depth missing.
- **4** — Strong. Clear numbers, a real deep dive, and a failure story.
- **5** — Staff-like. You set scope, defend trade-offs, and evolve the design.

## Scorecard

Copy this block into the design note after a mock.

```
Date:
Prompt:
Time used:

Clarify & scope            / 5
NFRs & constraints         / 5
Estimates                  / 5
High-level design          / 5
APIs & data model          / 5
Deep dive                  / 5
Trade-offs & failure       / 5
Communication              / 5

Total                      / 40
```

## What each row means

### Clarify and scope
You ask who the users are. You cut features. You restate the prompt.

### NFRs and constraints
You pick 2–3 NFRs that matter. You drop the rest on purpose.

### Estimates
You show QPS, storage, and machine count with round math. You check if one box is enough.

### High-level design
You draw a path for reads and writes. Boxes have jobs. The diagram matches the NFRs.

### APIs and data model
You name core calls and keys. You pick a shard key. You do not hand-wave the data.

### Deep dive
You pick 1–2 hard parts. You go below the first diagram.

### Trade-offs and failure
You compare two options. You say what dies first and how you detect it.

### Communication
You time-box. You say where you are. You invite the interviewer to choose a dive.

## Time box (45 minutes)
| Minutes | Job |
| --- | --- |
| 0–5 | Clarify, cut scope, pick NFRs |
| 5–12 | Estimates |
| 12–22 | High-level design + APIs |
| 22–38 | One or two deep dives |
| 38–45 | Failures, metrics, v2, recap |

If the interviewer pulls you to a dive, follow them. Drop a later section on purpose.

## After the mock
- [ ] Write 3 things that worked.
- [ ] Write 3 things to drill next.
- [ ] Add missing terms to [[Glossary]].
- [ ] Link the score to the design note you used.

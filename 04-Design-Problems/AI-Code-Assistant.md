---
type: design-problem
section: C
status: not-started
est_minutes: 85
week: 7
prev: LLM-Support-Bot
next: Lessons-from-System-Failures
course_url: "https://www.educative.io/courses/grokking-the-system-design-interview"
tags:
  - status/not-started
  - type/design-problem
  - section/C
---
# AI Code Assistant

← [[LLM-Support-Bot|LLM Support Bot]] · [[00-Home|Home]] · [[Lessons-from-System-Failures|Lessons from System Failures]] →

## Learning goals
- Scope inline code help that reads local context.
- Hit a tight latency budget for completions.
- Plan privacy: repo code may not leave the trust boundary.

## Study todos
- [ ] Open the matching Educative chapter. Keep this note in your own words.
- [ ] Time a first pass (45–60 min) before you read the course solution.
- [ ] Fill the RESHADED-style checkboxes in this note.
- [ ] Split complete-as-you-type vs chat-about-the-repo.
- [ ] Estimate QPS from thousands of IDEs.
- [ ] List the building blocks you reused. Wikilink them.
- [ ] Write 3 trade-offs in the Notes section.
- [ ] Do a 5-minute failure story (one component dies). Update Failure modes.
- [ ] Score the attempt with [[Interview-Rubric]]. Set `status` when done.

## RESHADED-style prompts
Use this as a timed interview script. Write your own answers. Do not paste course text.

### R — Requirements
- [ ] State the product in one sentence.
- [ ] List must-have functions for this interview.
- [ ] List functions you will cut from scope.
- [ ] Ask who the users are and what success looks like.

### E — Estimates
- [ ] Pick DAU, peak QPS, and read/write split.
- [ ] Estimate payload size and storage for 1 year.
- [ ] Estimate bandwidth at the edge and at origin.
- [ ] Say if one machine is enough. If not, say why.

### S — Storage and data
- [ ] List the main objects you must store.
- [ ] Choose online store vs object store vs cache vs queue.
- [ ] State retention and deletion rules.
- [ ] Note what must be durable vs what can be rebuilt.

### H — High-level design
- [ ] Draw clients, gateway, core services, and data stores.
- [ ] Write the read path in 5 steps.
- [ ] Write the write path in 5 steps.
- [ ] Mark async work (queues, workers, CDN).

### A — APIs
- [ ] List 3–6 core API calls.
- [ ] For each call, note input, output, and error cases.
- [ ] Say which calls are sync and which are async.
- [ ] Note auth, idempotency, and pagination where needed.

### D — Data model
- [ ] Sketch tables or documents and primary keys.
- [ ] Choose a shard key. Say why it avoids hotspots.
- [ ] Note indexes for the main queries.
- [ ] State replication and consistency for each store.

### E — Evaluate
- [ ] Name the first bottleneck at 10x load.
- [ ] Check the NFRs you promised.
- [ ] Point to a single point of failure. Fix it.
- [ ] Say what you would measure (SLIs) in production.

### D — Deep dives
- [ ] Pick 1–2 components to design in more detail.
- [ ] State two options and the trade-off you choose.
- [ ] Walk through one failure (node, zone, or dependency).
- [ ] Say how you would evolve the design in v2.

## Problem-specific prompts
- What context do you send (open file, repo index, diffs)?
- How do you keep p95 latency low enough for typing?
- Where do you run inference (local, VPC, vendor API)?
- How do you log quality without logging secret code?

## Notes
_Write your own notes here. Do not paste paid course text._

### Requirements

### Constraints

### High-level design

### Deep dives

### Trade-offs

### Failure modes

## Time
Estimated: **85 minutes**.

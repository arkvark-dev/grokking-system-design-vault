---
type: design-problem
section: C
status: not-started
est_minutes: 90
week: 6
prev: Web-Crawler
next: Typeahead
course_url: "https://www.educative.io/courses/grokking-the-system-design-interview"
tags:
  - status/not-started
  - type/design-problem
  - section/C
---
# WhatsApp

← [[Web-Crawler|Web Crawler]] · [[00-Home|Home]] · [[Typeahead|Typeahead]] →

## Learning goals
- Scope 1:1 chat, group chat, online status, and media.
- Design delivery: store-and-forward when the receiver is offline.
- Keep message payloads out of the hot metadata path when large.

## Study todos
- [ ] Open the matching Educative chapter. Keep this note in your own words.
- [ ] Time a first pass (45–60 min) before you read the course solution.
- [ ] Fill the RESHADED-style checkboxes in this note.
- [ ] Write the path for online delivery vs offline delivery.
- [ ] Estimate message QPS and storage retention.
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
- Where do you keep unread messages, and for how long?
- How do group fan-out and 'read' receipts scale?
- What consistency do ticks / delivery receipts need?
- How do you push media through blob storage + CDN?

## Notes
_Write your own notes here. Do not paste paid course text._

### Requirements

### Constraints

### High-level design

### Deep dives

### Trade-offs

### Failure modes

## Time
Estimated: **90 minutes**.

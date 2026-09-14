---
type: building-block
section: B
status: not-started
est_minutes: 50
week: 3
prev: Sharded-Counters
next: YouTube
course_url: "https://www.educative.io/courses/grokking-the-system-design-interview"
tags:
  - status/not-started
  - type/building-block
  - section/B
---
# Concluding Building Blocks / RESHADED

← [[Sharded-Counters|Sharded Counters]] · [[00-Home|Home]] · [[YouTube|YouTube]] →

## Learning goals
- Write a short interview script you can reuse on any prompt.
- Map each building block to at least one later design problem.
- Do a short timed dry run before you start full designs.

## Study todos
- [ ] Copy the RESHADED-style prompts below into your own one-page cheat sheet.
- [ ] For each block in this folder, write one line: job + one design that uses it.
- [ ] Do a 15-minute timed outline for TinyURL using only your cheat sheet.
- [ ] List 5 phrases you will say in interviews ('the bottleneck is…', 'the trade-off is…').
- [ ] Update [[Glossary]] with any term you still mix up.
- [ ] Mark week 3 complete in [[PROGRESS]].

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

## Block → later design (fill this)
| Block | One design that uses it |
| --- | --- |
| DNS | |
| Load balancer | |
| Database | |
| KV store | |
| CDN | |
| Sequencer | |
| Monitoring | |
| Cache | |
| Queue | |
| Pub-sub | |
| Rate limiter | |
| Blob store | |
| Search | |
| Logging | |
| Scheduler | |
| Sharded counters | |

## Notes
_Write your own notes here. Do not paste paid course text._

### Requirements

### Constraints

### High-level design

### Deep dives

### Trade-offs

### Failure modes

## Time
Estimated: **50 minutes**.

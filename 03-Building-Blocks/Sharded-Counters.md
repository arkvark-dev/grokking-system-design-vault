---
type: building-block
section: B
status: not-started
est_minutes: 40
week: 3
prev: Distributed-Task-Scheduler
next: Concluding-Building-Blocks
course_url: "https://www.educative.io/courses/grokking-the-system-design-interview"
tags:
  - status/not-started
  - type/building-block
  - section/B
---
# Sharded Counters

← [[Distributed-Task-Scheduler|Distributed Task Scheduler]] · [[00-Home|Home]] · [[Concluding-Building-Blocks|Concluding Building Blocks / RESHADED]] →

## Learning goals
- Explain why one row that increments on every write does not scale.
- Sketch shard-and-sum.
- Trade exact counts vs fast, almost-exact counts.

## Study todos
- [ ] Write the job of sharded counters in one sentence.
- [ ] Give a hotspot example (like counts on a popular post).
- [ ] Sketch N shards plus a periodic aggregator.
- [ ] Say when approximate counts are fine (views) vs not (money).
- [ ] Note read path: sum shards vs read a cached total.
- [ ] Write a failure mode: lost shard. Do you under-count or rebuild?

## Notes
_Write your own notes here. Do not paste paid course text._

### Requirements

### Constraints

### High-level design

### Deep dives

### Trade-offs

### Failure modes

## Time
Estimated: **40 minutes**.

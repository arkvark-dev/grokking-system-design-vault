---
type: building-block
section: B
status: not-started
est_minutes: 50
week: 3
prev: Distributed-Logging
next: Sharded-Counters
course_url: "https://www.educative.io/courses/grokking-the-system-design-interview"
tags:
  - status/not-started
  - type/building-block
  - section/B
---
# Distributed Task Scheduler

← [[Distributed-Logging|Distributed Logging]] · [[00-Home|Home]] · [[Sharded-Counters|Sharded Counters]] →

## Learning goals
- Contrast one-box cron with a fleet of workers.
- Handle missed runs, duplicates, and partitions.
- State at-least-once vs exactly-once for jobs.

## Study todos
- [ ] Write the job of a task scheduler in one sentence.
- [ ] List job types: one-shot, cron, delayed, dependent.
- [ ] Sketch: API to create jobs, store, dispatcher, workers, leases.
- [ ] Explain a lease/lock so two workers do not run the same job.
- [ ] Design retry with backoff and a poison-job path.
- [ ] Write a failure mode: dispatcher down during a DST or clock jump.

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

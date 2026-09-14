---
type: building-block
section: B
status: not-started
est_minutes: 45
week: 3
prev: Distributed-Search
next: Distributed-Task-Scheduler
course_url: "https://www.educative.io/courses/grokking-the-system-design-interview"
tags:
  - status/not-started
  - type/building-block
  - section/B
---
# Distributed Logging

← [[Distributed-Search|Distributed Search]] · [[00-Home|Home]] · [[Distributed-Task-Scheduler|Distributed Task Scheduler]] →

## Learning goals
- Sketch ship, store, and query for logs from many hosts.
- Set retention and PII rules.
- Contrast logs with metrics.

## Study todos
- [ ] Write the job of distributed logging in one sentence.
- [ ] Sketch app → agent → buffer/queue → store → search UI.
- [ ] Estimate volume: 1 KB/request at 10k QPS. What is that per day?
- [ ] Write a PII rule: fields you strip before storage.
- [ ] Choose retention (hot 7 days, warm 30, delete after 90) and say why.
- [ ] Note how logs help an incident vs how metrics page you first.

## Notes
_Write your own notes here. Do not paste paid course text._

### Requirements

### Constraints

### High-level design

### Deep dives

### Trade-offs

### Failure modes

## Time
Estimated: **45 minutes**.

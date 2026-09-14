---
type: building-block
section: B
status: not-started
est_minutes: 50
week: 3
prev: Distributed-Messaging-Queue
next: Rate-Limiter
course_url: "https://www.educative.io/courses/grokking-the-system-design-interview"
tags:
  - status/not-started
  - type/building-block
  - section/B
---
# Pub-Sub

← [[Distributed-Messaging-Queue|Distributed Messaging Queue]] · [[00-Home|Home]] · [[Rate-Limiter|Rate Limiter]] →

## Learning goals
- Contrast a queue (competing consumers) with pub-sub (fan-out).
- Sketch topics, subscriptions, and replay.
- Discuss ordering and duplicate events.

## Study todos
- [ ] Write the job of pub-sub in one sentence.
- [ ] Give one use case that needs a queue and one that needs pub-sub.
- [ ] Sketch publisher → topic → N independent subscribers.
- [ ] Note ordering: per-key vs global. Say which you can afford.
- [ ] Discuss replay and retention for new subscribers.
- [ ] Write a failure mode: slow subscriber. How do you isolate it?

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

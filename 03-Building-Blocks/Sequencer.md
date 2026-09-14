---
type: building-block
section: B
status: not-started
est_minutes: 45
week: 2
prev: CDN
next: Distributed-Monitoring
course_url: "https://www.educative.io/courses/grokking-the-system-design-interview"
tags:
  - status/not-started
  - type/building-block
  - section/B
---
# Sequencer

← [[CDN|CDN]] · [[00-Home|Home]] · [[Distributed-Monitoring|Distributed Monitoring]] →

## Learning goals
- Explain why unique IDs in a fleet are harder than on one box.
- Compare time-based IDs, central ticket servers, and random IDs.
- Name clock skew and hotspot risks.

## Study todos
- [ ] Write the job of a sequencer / ID generator in one sentence.
- [ ] List requirements: unique, roughly ordered (if needed), high QPS, low latency.
- [ ] Compare UUID, DB auto-increment, ticket server, and time+worker IDs.
- [ ] Say when sort-by-time IDs help and when they create hot partitions.
- [ ] Note clock skew: what breaks if a clock jumps.
- [ ] Pick one scheme for tweets and one for uploads. Justify each.

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

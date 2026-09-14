---
type: building-block
section: B
status: not-started
est_minutes: 55
week: 3
prev: Blob-Store
next: Distributed-Logging
course_url: "https://www.educative.io/courses/grokking-the-system-design-interview"
tags:
  - status/not-started
  - type/building-block
  - section/B
---
# Distributed Search

← [[Blob-Store|Blob Store]] · [[00-Home|Home]] · [[Distributed-Logging|Distributed Logging]] →

## Learning goals
- Sketch how documents become searchable (index) and how queries use that index.
- Explain why search is not a simple DB `LIKE`.
- Name freshness vs query-cost trade-offs.

## Study todos
- [ ] Write the job of distributed search in one sentence.
- [ ] Sketch invert-index at a high level (term → document ids).
- [ ] Split ingest path vs query path.
- [ ] Note sharding by term or by document. Give one cost of each.
- [ ] Discuss ranking as a separate step after recall.
- [ ] Write a failure mode: index lag after a write. What does the user see?

## Notes
_Write your own notes here. Do not paste paid course text._

### Requirements

### Constraints

### High-level design

### Deep dives

### Trade-offs

### Failure modes

## Time
Estimated: **55 minutes**.

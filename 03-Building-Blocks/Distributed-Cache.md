---
type: building-block
section: B
status: not-started
est_minutes: 55
week: 3
prev: Monitor-Client-Side-Errors
next: Distributed-Messaging-Queue
course_url: "https://www.educative.io/courses/grokking-the-system-design-interview"
tags:
  - status/not-started
  - type/building-block
  - section/B
---
# Distributed Cache

← [[Monitor-Client-Side-Errors|Monitor Client-Side Errors]] · [[00-Home|Home]] · [[Distributed-Messaging-Queue|Distributed Messaging Queue]] →

## Learning goals
- Place a cache in the read path and name who fills it.
- Compare cache-aside vs write-through vs write-back.
- Handle expiry, eviction, and a cache stampede.

## Study todos
- [ ] Write the job of a distributed cache in one sentence.
- [ ] Draw cache-aside for a user profile read.
- [ ] Compare write-through and write-back for durability vs latency.
- [ ] Explain TTL, LRU, and memory cap.
- [ ] Design stampede control (lock, singleflight, or early refresh).
- [ ] Write 2 failure modes: cache down (fall through), cache inconsistent with DB.

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

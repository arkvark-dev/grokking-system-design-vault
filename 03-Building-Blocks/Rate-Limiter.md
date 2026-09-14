---
type: building-block
section: B
status: not-started
est_minutes: 50
week: 3
prev: Pub-Sub
next: Blob-Store
course_url: "https://www.educative.io/courses/grokking-the-system-design-interview"
tags:
  - status/not-started
  - type/building-block
  - section/B
---
# Rate Limiter

← [[Pub-Sub|Pub-Sub]] · [[00-Home|Home]] · [[Blob-Store|Blob Store]] →

## Learning goals
- Explain who you protect (your APIs, a dependency, a user quota).
- Compare token bucket, leaky bucket, and window counters.
- Place the limiter at the edge vs in each service.

## Study todos
- [ ] Write the job of a rate limiter in one sentence.
- [ ] List dimensions: per IP, per user, per API key, per endpoint.
- [ ] Compare algorithms in a small table (burst, smoothness, memory).
- [ ] Sketch a distributed limiter (shared counter vs local + sync).
- [ ] Define the client-visible error (HTTP 429, retry-after).
- [ ] Write a failure mode: limiter store down. Fail open or fail closed? Why?

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

# Conventions

- Decisions: a decision is recorded in an issue comment as a line `Decision: NAME = value`. When an issue
  has several `Decision:` comments, the latest one supersedes the earlier ones. A `Proposal:` line is not a
  decision.
- Duplicates: of two issues about the same thing, the duplicate is closed with the `duplicate` label. The
  issue that stays open is the canonical one, and its `Requested:` line is the request.
- Config changes go through pull requests. A pull request that was closed without merging is abandoned. The
  files on the default branch hold the current values, not proposed ones.
- Tracking issues name the issue that holds the measurements by its exact title, on a line
  `Measurements: <title>`. Benchmark comments give one line per environment (`staging:`, `production:`).
- Labels: among competing proposals, the issue labelled `release-blocker` is binding for the next release.

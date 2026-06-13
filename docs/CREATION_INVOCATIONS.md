# Creation Invocations

This repo was built using the `ai-engineering-skills` workflow as the control layer for content and verification.

| Step | Invocation | Purpose | Output |
| --- | --- | --- | --- |
| 1 | `$mini-spec` | Define repo goal, audience, constraints, and v0.1 scope | [`SPEC.md`](process/SPEC.md) |
| 2 | `$thin-plan` | Break the build into small vertical slices | [`PLAN.md`](process/PLAN.md), [`TODO.md`](process/TODO.md) |
| 3 | `$scope-freeze` | Freeze write scope before each slice | Scope sections in [`TODO.md`](process/TODO.md) and [`docs/BUILD_LOG.md`](./BUILD_LOG.md) |
| 4 | `$build-one` | Implement one slice at a time | Repo files created slice by slice |
| 5 | `$test-mini` | Run lightweight validation after each slice | Validation entries in [`docs/VERIFY.md`](./VERIFY.md) |
| 6 | `$verify-contract` | Record evidence that the repo matches the brief | [`docs/VERIFY.md`](./VERIFY.md) |
| 7 | `$handoff` | Leave a durable end-state for the next session | [`docs/HANDOFF.md`](./HANDOFF.md) |

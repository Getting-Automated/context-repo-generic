# Operating Rules

These rules help keep the context repo useful as it grows.

## Keep Context Scoped

Do not make every agent read every file. Use onboarding paths and context packs to define what matters for each job.

## Keep Truth Reviewable

Durable context should be reviewed like code:

- small changes
- clear ownership
- pull requests when possible
- decision records for important calls

## Prefer Pointers Over Dumps

If a fact changes often, link to the source system instead of copying the data here.

## Use Confidence Labels

Use:

- `confirmed`
- `conflicting`
- `proposed`
- `unknown`

## Do Not Hide Gaps

Missing context is useful signal. Agents should surface gaps and propose updates instead of guessing.

## Keep Entry Files Small

`AGENTS.md` and `CLAUDE.md` should route agents to context. They should not duplicate the whole repo.

## Review Before Sharing

Before publishing this repo or using it as a template, run through [publishing-checklist.md](publishing-checklist.md).

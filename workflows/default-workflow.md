# Default Workflow

Owner: `[name or team]`
Last reviewed: `[YYYY-MM-DD]`
Sensitivity: `internal`
Status: `draft`

## Purpose

Use this file when a task does not have a more specific workflow.

## Trigger

- `[what starts the work]`

## Inputs

- `[required input]`
- `[required input]`

## Process

1. Confirm the task objective.
2. Read the relevant onboarding path.
3. Gather only the context needed.
4. Produce a draft or recommendation.
5. Cite context used.
6. Flag assumptions and missing context.
7. Propose updates if the repo is stale or incomplete.

## Outputs

- `[expected output]`
- `[expected output]`

## Review Requirements

Human review is required before:

- external sends
- production changes
- source-of-truth updates
- sensitive claims

## Failure Paths

| Failure | Expected Behavior |
|---|---|
| missing context | mark `unknown` and propose update |
| conflicting sources | cite conflict and ask for review |
| restricted data | stop and request permission |

# Start Here

This repo contains stable context for agents.

Use it to onboard an agent before it writes, researches, codes, plans, drafts, analyzes, or updates work on your behalf.

## Replace These Placeholders

Fill this section in before sharing the repo with an agent.

- Organization or project name: `[replace me]`
- Owner: `[replace me]`
- Primary use case: `[replace me]`
- Last reviewed: `[YYYY-MM-DD]`

## How To Use This Repo

1. Start with this file.
2. Read the relevant onboarding path in [agent-onboarding/](agent-onboarding/).
3. Read only the context files named by that onboarding path.
4. Cite the files used when producing output.
5. Propose updates when context is missing, stale, or conflicting.

## Core Context Map

- Company context: [company/](company/)
- People and ownership: [people/](people/)
- Client or stakeholder context: [clients/](clients/)
- Systems and sources of truth: [systems/](systems/)
- Workflow rules: [workflows/](workflows/)
- Decision records: [decisions/](decisions/)
- Project briefs: [projects/](projects/)
- Reusable templates: [templates/](templates/)

## Stable Context Versus Live Facts

Use this repo for stable context:

- positioning
- roles
- workflows
- source-of-truth maps
- decision records
- style and quality rules
- agent onboarding paths

Do not use this repo as a live data store:

- current pipeline status
- live revenue
- open tickets
- customer records
- private exports
- credentials

When a task needs live facts, use the source system named in the context files.

## Fact Confidence Labels

Use these labels when facts matter:

- `confirmed`: directly supported by this repo or a cited source
- `conflicting`: supported by one source but contradicted by another
- `proposed`: a reasonable suggestion that is not yet approved context
- `unknown`: cannot be resolved from available context

## Safety Rules

- Do not invent durable facts.
- Do not treat examples as real business data.
- Do not expose secrets or credentials.
- Do not make irreversible changes without explicit approval.
- Do not silently overwrite context; propose changes for review.

## First Setup Checklist

- [ ] Replace placeholders in this file.
- [ ] Fill in [company/positioning.md](company/positioning.md).
- [ ] Fill in [people/roles-and-ownership.md](people/roles-and-ownership.md).
- [ ] Fill in [systems/source-of-truth.md](systems/source-of-truth.md).
- [ ] Fill in [workflows/default-workflow.md](workflows/default-workflow.md).
- [ ] Decide who reviews changes to this repo.

# Context Repo Starter

A lightweight starter repo for giving AI agents reusable business context without stuffing everything into one giant prompt.

Use this as a template for a company, client, project, or personal operating context repo. The goal is not to document everything. The goal is to give agents a reliable front door, scoped reading paths, and a repeatable way to cite what shaped their work.

## What This Is

This repo is a place to store stable context:

- who you are
- what the business or project does
- who owns what
- what systems are sources of truth
- how common workflows run
- what decisions have already been made
- what agents should read before doing work

It is not a replacement for your CRM, data warehouse, task tracker, codebase, or private notes app.

Use this repo for durable context. Use live systems for live facts.

## Start Here

1. Edit [00-start-here.md](00-start-here.md).
2. Update [AGENTS.md](AGENTS.md) and [CLAUDE.md](CLAUDE.md) only if your tools need different routing.
3. Fill in [agent-onboarding/default.md](agent-onboarding/default.md).
4. Copy files from [templates/](templates/) when you need new context files.
5. Keep secrets, credentials, private exports, and raw customer data out of this repo.

## Repo Structure

This template includes the core folders most teams eventually need. You do not need to fill them all out on day one, but keeping the structure in place makes the repo easier to share, fork, and reuse.

```text
context-repo/
|- README.md
|- 00-start-here.md
|- AGENTS.md
|- CLAUDE.md
|- context-manifest.json
|- agent-onboarding/
|  |- default.md
|  |- researcher.md
|  |- content-writer.md
|  `- codebase-maintainer.md
|- company/
|  |- README.md
|  |- positioning.md
|  |- offers.md
|  `- voice-and-style.md
|- people/
|  |- README.md
|  |- roles-and-ownership.md
|  `- stakeholders.md
|- clients/
|  |- README.md
|  |- index.md
|  `- client-profile.template.md
|- systems/
|  |- README.md
|  |- source-of-truth.md
|  `- access-and-sensitivity.md
|- workflows/
|  |- README.md
|  `- default-workflow.md
|- decisions/
|  |- README.md
|  `- decision-record.template.md
|- projects/
|  |- README.md
|  `- project-context.template.md
|- templates/
|  |- context-file.template.md
|  |- context-pack.template.md
|  |- source-backed-brief.template.md
|  `- scoped-task.template.md
|- examples/
   `- commented-out-example.md
`- docs/
   |- operating-rules.md
   `- publishing-checklist.md
```

## How Agents Should Use This Repo

Agents should not read everything by default.

They should:

1. Read [00-start-here.md](00-start-here.md).
2. Read the relevant file in [agent-onboarding/](agent-onboarding/).
3. Read only the files listed for the task.
4. Cite the files that shaped the answer.
5. Mark missing context as `unknown` or `proposed`.
6. Suggest repo updates when context is missing or stale.

## What Not To Store Here

Do not store:

- API keys
- passwords
- session tokens
- raw customer exports
- private financial exports
- legal documents that should not be shared with agents
- sensitive personal data
- anything that should be fetched fresh from a source system

When in doubt, store a pointer to the source of truth instead of copying the source data.

## Good First Files To Add

If you are setting this up for a real business, fill in these first:

- `company/positioning.md`
- `people/roles-and-ownership.md`
- `systems/source-of-truth.md`
- `workflows/default-workflow.md`
- `agent-onboarding/default.md`

Keep each file short, owned, and reviewable.

## Operating Rule

The prompt should not be the storage layer.

Use prompts to ask for work. Use this repo to tell the agent what context to read before doing the work.

## Before Sharing

Run through [docs/publishing-checklist.md](docs/publishing-checklist.md) before making a copy public or distributing it as a template.

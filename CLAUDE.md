# Claude Code Entry Point

Use this file when working in Claude Code.

This repo is a context router, not a giant prompt. Start with the shared context files and then follow the scoped reading path for the job.

## Read Order

1. [00-start-here.md](00-start-here.md)
2. [agent-onboarding/default.md](agent-onboarding/default.md)
3. Any task-specific files named by the user

## Rules

- Do not load the whole repo by default.
- Cite the files you used.
- Treat examples as examples, not real business facts.
- Mark missing context as `unknown` or `proposed`.
- Suggest a repo update when a recurring gap appears.
- Do not store secrets, credentials, or raw private data in this repo.

## Suggested Response Shape

For context-heavy work, end with:

```text
Context used:
- path/to/file.md
- path/to/other-file.md

Open context gaps:
- [unknown/proposed] description of what is missing
```

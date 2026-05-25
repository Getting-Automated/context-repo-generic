# Codebase Maintainer Onboarding

Use this path when an agent is working in or around a codebase.

## Required Reading

- [../00-start-here.md](../00-start-here.md)
- Relevant project brief in [../projects/](../projects/) if one exists
- Repo-local agent instructions in the target codebase, if present

## Optional Reading

- [../systems/source-of-truth.md](../systems/source-of-truth.md)
- [../systems/access-and-sensitivity.md](../systems/access-and-sensitivity.md)
- [../workflows/default-workflow.md](../workflows/default-workflow.md)

## Rules

- Prefer the target codebase instructions over generic assumptions.
- Read before editing.
- Keep changes scoped.
- Do not modify secrets, credentials, or generated files unless asked.
- Run the relevant tests or explain why they were not run.
- Cite files changed and validation performed.

## Expected Output

```text
Changed:
- ...

Validation:
- ...

Context used:
- ...

Notes:
- ...
```

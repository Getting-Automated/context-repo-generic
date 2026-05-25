# Agent Entry Point

Use this file when working as Codex or any agent that reads `AGENTS.md`.

This file is a router. It should stay short. Do not turn it into the whole company handbook.

## Read Order

1. [00-start-here.md](00-start-here.md)
2. [agent-onboarding/default.md](agent-onboarding/default.md)
3. Any task-specific files named by the user or the onboarding path

## Operating Rules

- Read only the context needed for the task.
- Cite the files that shaped your answer.
- Separate confirmed context from proposed context.
- If context is missing, say so and propose the smallest useful update.
- If files conflict, call out the conflict instead of choosing silently.
- Treat templates and examples as examples, not facts.
- Never search private folders, exports, or credentials unless the user explicitly asks and the repo permits it.
- Do not make durable repo changes without explaining what changed.

## Output Expectations

For non-trivial work, include a short section named `Context used` with the file paths that mattered.

If you propose a repo update, include:

- file to update
- proposed change
- reason
- confidence label

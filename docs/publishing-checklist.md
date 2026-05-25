# Publishing Checklist

Use this before sharing the repo publicly or using it as a template.

## Remove Or Replace Placeholders

- [ ] Replace `[replace me]` in [../00-start-here.md](../00-start-here.md).
- [ ] Fill in [../company/positioning.md](../company/positioning.md).
- [ ] Fill in [../people/roles-and-ownership.md](../people/roles-and-ownership.md).
- [ ] Fill in [../systems/source-of-truth.md](../systems/source-of-truth.md).
- [ ] Fill in [../workflows/default-workflow.md](../workflows/default-workflow.md).

## Check Safety

- [ ] No secrets or credentials.
- [ ] No raw customer exports.
- [ ] No private financial exports.
- [ ] No sensitive personal data.
- [ ] No fake examples that could be mistaken for real clients.

## Check Distribution Settings

- [ ] Decide whether the repo is public, private, or template-only.
- [ ] Add a license if you want others to reuse it as open source.
- [ ] Add CODEOWNERS or branch protection if multiple people will update context.
- [ ] Keep [../AGENTS.md](../AGENTS.md) and [../CLAUDE.md](../CLAUDE.md) as routing files, not full context dumps.

## First Test

Ask an agent to do a small task using the repo:

```text
Read 00-start-here.md and agent-onboarding/default.md.
Tell me what context is missing before you could help with [task].
Do not invent missing facts.
```

If the agent guesses, tighten the context files.

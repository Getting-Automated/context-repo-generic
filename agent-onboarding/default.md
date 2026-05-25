# Default Agent Onboarding

Use this path when there is not a more specific onboarding file.

## Required Reading

- [../00-start-here.md](../00-start-here.md)
- [../company/positioning.md](../company/positioning.md)
- [../people/roles-and-ownership.md](../people/roles-and-ownership.md)
- [../systems/source-of-truth.md](../systems/source-of-truth.md)
- [../workflows/default-workflow.md](../workflows/default-workflow.md)

## Optional Reading

- [../company/offers.md](../company/offers.md)
- [../company/voice-and-style.md](../company/voice-and-style.md)
- [../systems/access-and-sensitivity.md](../systems/access-and-sensitivity.md)
- Relevant project brief in [../projects/](../projects/)
- Relevant client profile in [../clients/](../clients/)

## Allowed Work

By default, agents may:

- summarize context
- draft content
- propose plans
- identify missing context
- suggest repo updates
- create draft files when asked

By default, agents should not:

- invent durable facts
- expose secrets
- copy private data into outputs
- make irreversible external changes
- treat examples as real company data

## Expected Output

For any work that depends on repo context, include:

```text
Context used:
- path/to/file.md

Assumptions:
- ...

Open context gaps:
- ...
```

## Missing Context Rule

If the context is missing, do not pretend it exists.

Use one of these labels:

- `unknown`: cannot be resolved from available files
- `proposed`: a reasonable draft that needs review
- `conflicting`: available files disagree

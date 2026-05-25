# Source Of Truth Map

Owner: `[name or team]`
Last reviewed: `[YYYY-MM-DD]`
Sensitivity: `internal`
Status: `draft`

## Purpose

Use this file when an agent needs to know where a fact should come from.

## Source Map

| Domain | Source System | Use For | Do Not Use For | Owner |
|---|---|---|---|---|
| `[customers]` | `[CRM]` | `[account status]` | `[billing truth]` | `[owner]` |
| `[tasks]` | `[issue tracker]` | `[work status]` | `[business decisions]` | `[owner]` |

## Precedence Rules

If sources disagree:

1. Cite the conflict.
2. Prefer the system named in this file for that domain.
3. Ask for review if no precedence rule exists.

## Missing Source Rule

If no source of truth is listed, mark the fact as `unknown` or `proposed`.

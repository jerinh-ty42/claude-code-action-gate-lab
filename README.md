# claude-code-action-gate-lab

Testbed repo for studying `anthropics/claude-code-action` behavior, especially:
- `issue_comment` triggers
- branch checkout logic
- whether repo instructions (e.g., `CLAUDE.md`) can be supplied from PR branches

## Setup
Add GitHub Actions secret:
- `ANTHROPIC_API_KEY`

## Trigger
Comment `@claude ...` on an issue or PR.

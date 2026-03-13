# Agent Stack (BYOM + Claude)

This repository uses a layered agent configuration:

1. Global portfolio policy: `/Users/jack.reis/Documents/=notes/CLAUDE.md`
2. Repo policy: `/Users/jack.reis/Documents/neurodivergent-visual-org/CLAUDE.md`
3. Shared capabilities:
   - Skills: `.claude/shared-skills` -> `/Users/jack.reis/Documents/superpowers/skills`
   - Agents: `.claude/shared-agents` -> `/Users/jack.reis/Documents/superpowers/agents`
4. Repo-local capabilities (optional): `.claude/skills/`, `.claude/agents/`

## Notes
- Keep settings in `.claude/settings.json` generic and non-secret.
- Avoid hardcoding provider keys; use environment variables.
- Prefer model aliases and fallback chains in app/runtime configs.

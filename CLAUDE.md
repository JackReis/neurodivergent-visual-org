## Inheritance Model (Folder-First)

This repository inherits operational policy from:
- Global baseline: `/Users/jack.reis/Documents/=notes/CLAUDE.md`
- Domain contract: `/Users/jack.reis/Documents/=notes/claude/contracts/DOMAIN-PLUGINS-AGENTS.md`

### Default complex-task behavior
- Plan first using `superpowers:writing-plans`
- Use `openclaw-sync` when orchestration/state is involved
- Execute with `superpowers:executing-plans`

### Local overrides
Keep only repo-specific build/test/deploy details below.

---

# Neurodivergent Visual Organization (NVO)

- Obsidian plugin v3.1.1 for ADHD-friendly visual organization using Mermaid diagrams
- Adaptive cognitive modes for different executive function states
- TypeScript + Obsidian API

## Portfolio Context

This repo is part of an 18-repo portfolio coordinated from the `=notes` vault.

- **Role**: Obsidian community plugin for neurodivergent-friendly visual workflows
- **Coordination**: See `=notes/REPOSITORY-MAP.md` for full dependency graph
- **Relationships**:
  - Developed alongside → `=notes` vault (`/Users/jack.reis/Documents/=notes/`)
  - Published to → Obsidian community plugin directory
  - Showcased in → `jackdotdigital` portfolio (`/Users/jack.reis/Documents/jackdotdigital/`)
  - Automated by → `tonkotsu-automation` (`/Users/jack.reis/Documents/tonkotsu-automation/`)

## Repository Remote Policy
- Repo policy: GitHub is primary `origin` and CI/CD source; GitLab is backup remote (`gitlab`) with GitLab CI disabled.

## Local Overrides
- Any capability change must include usage docs/examples.
- Keep plugin/skill APIs stable where possible; note breaking changes explicitly.
- Preserve provider-agnostic interfaces and adapter boundaries.

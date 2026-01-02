# Contributing to n-skills

This is a curated marketplace. All submissions are reviewed for quality.

## Submission Requirements

1. **SKILL.md** with proper frontmatter (name, description)
2. Description includes trigger phrases and use cases
3. Clear documentation with examples
4. Apache 2.0 or MIT license

## SKILL.md Format

```yaml
---
name: your-skill-name
description: |
  Brief description including:
  - What the skill does
  - When to use it (trigger phrases)
  - Any requirements (API keys, etc.)
---

# Skill Name

[Instructions here]
```

## How to Submit

1. Fork this repository
2. Add your skill to the appropriate category under `skills/`
3. Update `.claude-plugin/marketplace.json` with your plugin entry
4. Update `AGENTS.md` with your skill
5. Open a PR with description of the skill

## Categories

| Category | Description |
|----------|-------------|
| **tools** | CLI tools and utilities |
| **development** | Language/framework assistance |
| **productivity** | Workflow automation |
| **automation** | Browser, CI/CD, system |
| **data** | Databases, data processing |
| **documentation** | Docs, diagrams, specs |

## Quality Standards

- Clear, actionable instructions
- Working examples
- Proper error handling guidance
- No hardcoded secrets
- Documentation for any dependencies

## Review Process

1. Automated validation of SKILL.md format
2. Manual review for quality and usefulness
3. Security review for any scripts
4. Merge upon approval

PRs are typically reviewed within 1-2 days.

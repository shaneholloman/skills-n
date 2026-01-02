# n-skills

Curated plugin marketplace for AI agents. Works with Claude Code, Codex, and any agent via openskills.

## Philosophy

**Complexity is a drag.** Every coding agent has its own instruction format. Instead of fighting fragmentation, we embrace simplicity:

- **SKILL.md** - The [agentskills.io](https://agentskills.io) standard (works everywhere)
- **AGENTS.md** - Universal discovery ([20,000+ repos](https://www.infoq.com/news/2025/08/agents-md/), supported by GitHub Copilot, Gemini, Codex, Cursor, and more)
- **openskills** - One tool for installation and distribution

## Installation

### Claude Code (Native)

```bash
/plugin marketplace add numman-ali/n-skills
/plugin install zai-cli@n-skills
```

### OpenSkills (Universal)

```bash
openskills install numman-ali/n-skills
```

Works with: Cursor, Windsurf, Aider, Cline, and any AGENTS.md-compatible agent.

### Codex

```bash
$skill-installer https://github.com/numman-ali/n-skills/tree/main/skills/tools/zai-cli
```

## Available Skills

| Skill | Category | Description |
|-------|----------|-------------|
| [zai-cli](./skills/tools/zai-cli/) | Tools | Z.AI vision, search, reader, and GitHub exploration |

## Categories

- **tools** - CLI tools and utilities
- **development** - Language-specific dev assistance
- **productivity** - Workflow automation
- **automation** - Browser, CI/CD, system automation
- **data** - Databases, data processing
- **documentation** - Docs, diagrams, specs

## Compatibility

| Agent | Installation | Status |
|-------|--------------|--------|
| Claude Code | `/plugin install` | Native |
| GitHub Copilot | AGENTS.md | Native |
| Codex | `$skill-installer` | Native |
| Cursor | openskills → AGENTS.md | Universal |
| Windsurf | openskills → AGENTS.md | Universal |
| Cline | openskills → AGENTS.md | Universal |
| Factory/Droid | AGENTS.md | Native |
| Aider | openskills → AGENTS.md | Universal |

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md) for submission guidelines.

## License

Apache 2.0

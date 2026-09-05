# Skills

A curated collection of AI coding agent skills, gathered as Git submodules with a unified `skills/` directory that symlinks the most useful skill definitions for quick access.

## What Are Agent Skills?

Agent skills are reusable instruction sets that give AI coding assistants (Claude Code, Gemini, Cursor, etc.) domain-specific expertise. Instead of stuffing everything into a system prompt, skills are loaded on demand — keeping context lean and answers sharp.

## Included Projects

| Directory | Description | Source |
|-----------|-------------|--------|
| [`Jeffallan-claude-skills`](Jeffallan-claude-skills/) | 67+ skills and 9 workflows for full-stack development with Claude Code | [jeffallan/claude-skills](https://github.com/jeffallan/claude-skills) |
| [`agents-cli`](agents-cli/) | CLI and skills for building agents on Google's Gemini Enterprise Agent Platform | [google/agents-cli](https://github.com/google/agents-cli) |
| [`astral-claude-code-plugins`](astral-claude-code-plugins/) | Astral plugins for Claude Code — skills for `ruff`, `uv`, and `ty` | [astral-sh/claude-code-plugins](https://github.com/astral-sh/claude-code-plugins) |
| [`cc-skills-golang`](cc-skills-golang/) | Production-ready Go skills covering testing, security, observability, and more | [samber/cc-skills-golang](https://github.com/samber/cc-skills-golang) |
| [`fastapi`](fastapi/) | FastAPI framework skills for building APIs with Python | [fastapi/fastapi](https://github.com/fastapi/fastapi) |
| [`go-modern-guidelines`](go-modern-guidelines/) | Modern Go guidelines — teaches agents idiomatic Go 1.0–1.26 patterns | [JetBrains/go-modern-guidelines](https://github.com/JetBrains/go-modern-guidelines) |
| [`pydantic`](pydantic/) | Pydantic data validation skills for Python | [pydantic/pydantic](https://github.com/pydantic/pydantic) |

## Quick-Access Skills

The `skills/` directory provides symlinks to individual skill definitions extracted from the submodules above:

| Skill | Points To |
|-------|-----------|
| `skills/fastapi` | FastAPI skill from the `fastapi` submodule |
| `skills/pydantic` | Pydantic skill from the `pydantic` submodule |
| `skills/ruff` | Ruff linter skill from `astral-claude-code-plugins` |
| `skills/ty` | ty type checker skill from `astral-claude-code-plugins` |
| `skills/uv` | uv package manager skill from `astral-claude-code-plugins` |

## Getting Started

Clone with submodules:

```bash
git clone --recurse-submodules <repo-url>
```

If you already cloned without submodules:

```bash
git submodule update --init --recursive
```

## License

Each submodule retains its own license. See the individual project directories for details.

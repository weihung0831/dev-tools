# weihung-tools

Wei-Hung's developer toolkit for Claude Code — productivity skills for daily reports, README generation, and spec analysis. Supports both English and Traditional Chinese triggers.

## Skills

| Skill | Trigger | Description |
|-------|---------|-------------|
| `daily-report` | "daily report", "work summary", "today's progress" | Generate daily work progress reports from git history |
| `readme-updater` | "update readme", "generate readme", "sync readme" | Auto-generate or update README.md from codebase analysis |
| `spec-analyzer` | "analyze spec", "extract requirements", "spec breakdown" | Analyze spec documents, extract DO/DON'T lists and test cases |

## Installation

In Claude Code, run:

```
/install weihung0831/weihung-tools
```

## Usage

Once installed, skills activate automatically when you use their trigger phrases:

```
> daily report           # Generates daily progress report from git
> update readme          # Updates README.md from codebase
> analyze spec ./spec.md # Analyzes spec document
```

## Structure

```
weihung-tools/
├── .claude-plugin/
│   └── plugin.json
└── skills/
    ├── daily-report/
    │   └── SKILL.md
    ├── readme-updater/
    │   ├── SKILL.md
    │   └── references/
    │       └── section-templates.md
    └── spec-analyzer/
        ├── SKILL.md
        └── references/
            └── output-template.md
```

## License

MIT

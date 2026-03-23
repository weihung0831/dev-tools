# weihung-tools

Wei-Hung's developer toolkit for Claude Code — a collection of productivity skills for project management and documentation workflows, optimized for Traditional Chinese output.

## Skills

| Skill | Trigger | Description |
|-------|---------|-------------|
| `daily-report` | 「今日進度」「每日回報」「daily report」 | Generate daily work progress reports from git history |
| `readme-updater` | 「更新 readme」「產生 readme」 | Auto-generate or update README.md from codebase analysis |
| `spec-analyzer` | 「分析 spec」「萃取需求」 | Analyze spec documents, extract DO/DON'T lists and test cases |

## Installation

```bash
claude --plugin-dir /path/to/weihung-tools
```

Or install from marketplace:

```bash
claude /install weihung-tools
```

## Usage

Once installed, skills activate automatically when you use their trigger phrases:

```
> 今日進度          # Generates daily progress report
> 更新 readme       # Updates README.md from codebase
> 分析 spec ./spec.md  # Analyzes spec document
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

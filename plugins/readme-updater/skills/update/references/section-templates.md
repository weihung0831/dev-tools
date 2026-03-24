# README Section Templates

## Project Title & Description

```markdown
# {Project Name}

{Taken from package manifest description or existing README first paragraph, 1-2 sentences}
```

## Features

```markdown
## Features

- {Feature list derived from components/routes/commands}
- {One line per feature, brief description}
```

## Tech Stack Table

```markdown
## Tech Stack

| Category | Technology |
|----------|-----------|
| Language | TypeScript, Rust |
| Framework | React 19, Tauri 2 |
| Styling | Tailwind CSS v4 |
| State | Zustand |
| Router | TanStack Router |
| Testing | Vitest, Cargo test |
| Build | Vite |
```

## Getting Started

```markdown
## Getting Started

### Prerequisites

- Node.js >= {version}
- Rust >= {version} (if applicable)
- {Other required tools}

### Installation

\`\`\`bash
{Install commands from manifest scripts}
\`\`\`

### Development

\`\`\`bash
{Dev server command}
\`\`\`
```

## Project Structure

```markdown
## Project Structure

\`\`\`
src/
├── components/    # {Brief description}
├── hooks/         # {Brief description}
├── stores/        # {Brief description}
├── routes/        # {Brief description}
└── ...
\`\`\`
```

Keep structure tree to 2 levels deep with brief annotations.

## Scripts Table

```markdown
## Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm run test` | Run tests |
| `npm run lint` | Lint code |
```

Sourced from `package.json` scripts, `Makefile`, `Cargo.toml`, etc.

## Architecture Overview

```markdown
## Architecture

{Only generate when architecture info exists in CLAUDE.md or docs/}
{High-level description, 2-3 sentences}
```

## Optional Sections (Preserve Existing)

- **License** — Preserve as-is
- **Contributing** — Preserve as-is
- **Badges/Shields** — Preserve as-is
- **Screenshots** — Preserve as-is
- **Acknowledgments** — Preserve as-is

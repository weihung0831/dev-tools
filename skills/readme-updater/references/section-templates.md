# README 區塊模板

## 專案標題與描述

```markdown
# {專案名稱}

{從 package manifest 的 description 或現有 README 第一段取得，1-2 句}
```

## 功能特色

```markdown
## Features

- {從 components/routes/commands 推導的功能列表}
- {每項功能一行，簡短描述}
```

## 技術棧表格

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

## 快速開始

```markdown
## Getting Started

### Prerequisites

- Node.js >= {版本}
- Rust >= {版本}（若適用）
- {其他必要工具}

### Installation

\`\`\`bash
{從 manifest scripts 取得安裝指令}
\`\`\`

### Development

\`\`\`bash
{開發伺服器指令}
\`\`\`
```

## 專案結構

```markdown
## Project Structure

\`\`\`
src/
├── components/    # {簡短說明}
├── hooks/         # {簡短說明}
├── stores/        # {簡短說明}
├── routes/        # {簡短說明}
└── ...
\`\`\`
```

保持結構樹深度 2 層，附簡短註解。

## 指令表格

```markdown
## Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | 啟動開發伺服器 |
| `npm run build` | 建置正式版本 |
| `npm run test` | 執行測試 |
| `npm run lint` | 程式碼檢查 |
```

從 `package.json` scripts、`Makefile`、`Cargo.toml` 等取得。

## 架構概覽

```markdown
## Architecture

{僅在 CLAUDE.md 或 docs/ 中有架構資訊時才產生}
{高層級描述，2-3 句}
```

## 選用區塊（保留現有的即可）

- **License** — 保留原文
- **Contributing** — 保留原文
- **Badges/Shields** — 保留原文
- **Screenshots** — 保留原文
- **Acknowledgments** — 保留原文

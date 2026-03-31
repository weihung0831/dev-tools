[English](./README.md) | [繁體中文](./README.zh-TW.md)

# 🛠️ dev-tools

> A Claude Code plugin marketplace by [weihung0831](https://github.com/weihung0831) — curated developer productivity skills for project documentation and workflow automation.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Plugins](https://img.shields.io/badge/Plugins-2-green.svg)](#available-plugins)
[![Claude Code](https://img.shields.io/badge/Claude_Code-Plugin-blueviolet.svg)](https://claude.ai/code)

## 📦 Available Plugins

### 📋 reporting

Generate structured daily progress reports from git commit history. Automatically categorizes changes by conventional commit types and summarizes work completed, in-progress items, and notable changes.

- **`reporting:daily-report`** — Generate daily work progress report

> **Triggers:** `"daily report"` · `"work summary"` · `"today's progress"`

### 📝 docs

Analyze your codebase and auto-generate or update `README.md` with accurate tech stack, project structure, scripts, and architecture overview. Preserves existing badges, screenshots, and custom sections.

- **`docs:update-readme`** — Auto-generate or update README.md

> **Triggers:** `"update readme"` · `"generate readme"` · `"sync readme"`


## 🚀 Installation

Add the marketplace:

```
/plugin marketplace add weihung0831/dev-tools
```

Install plugins individually:

```
/plugin install dev-tools@daily-report
/plugin install dev-tools@readme-updater
```

## 🌐 Language Support

All plugins support both **English** and **Traditional Chinese** triggers and output.

## 📄 License

MIT

[English](./README.md) | [繁體中文](./README.zh-TW.md)

# 🛠️ dev-tools

> A Claude Code plugin marketplace by [weihung0831](https://github.com/weihung0831) — curated developer productivity skills for project documentation and workflow automation.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Plugins](https://img.shields.io/badge/Plugins-4-green.svg)](#available-plugins)
[![Claude Code](https://img.shields.io/badge/Claude_Code-Plugin-blueviolet.svg)](https://claude.ai/code)

## 📦 Available Plugins

### 📋 daily-report

Generate structured daily progress reports from git commit history. Automatically categorizes changes by conventional commit types and summarizes work completed, in-progress items, and notable changes.

> **Triggers:** `"daily report"` · `"work summary"` · `"today's progress"`

### 📝 readme-updater

Analyze your codebase and auto-generate or update `README.md` with accurate tech stack, project structure, scripts, and architecture overview. Preserves existing badges, screenshots, and custom sections.

> **Triggers:** `"update readme"` · `"generate readme"` · `"sync readme"`

### 📐 plan-analyzer

Validate and standardize plan files (`plan.md` + `phase-XX.md`) after plan creation. Checks required sections, correct ordering, status values, and E2E test scenario format. Outputs a correction summary with auto-fixes.

> **Triggers:** `"analyze plan"` · `"validate plan"` · `"standardize plan"` · `"check plan format"`

### 🔍 spec-analyzer

Parse spec and design documents to extract actionable **DO/DON'T checklists** and **test-case-driven verification metrics**, grouped by functional area with priority levels (P0/P1/P2).

> **Triggers:** `"analyze spec"` · `"extract requirements"` · `"spec breakdown"`

## 🚀 Installation

Add the marketplace:

```
/plugin marketplace add weihung0831/dev-tools
```

Install plugins individually:

```
/plugin install dev-tools@daily-report
/plugin install dev-tools@readme-updater
/plugin install dev-tools@plan-analyzer
/plugin install dev-tools@spec-analyzer
```

## 🌐 Language Support

All plugins support both **English** and **Traditional Chinese** triggers and output.

## 📄 License

MIT

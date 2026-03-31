[English](./README.md) | [繁體中文](./README.zh-TW.md)

# 🛠️ dev-tools

> 由 [weihung0831](https://github.com/weihung0831) 維護的 Claude Code 插件市集 — 精選開發者生產力工具，涵蓋專案文件與工作流程自動化。

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Plugins](https://img.shields.io/badge/Plugins-2-green.svg)](#可用插件)
[![Claude Code](https://img.shields.io/badge/Claude_Code-Plugin-blueviolet.svg)](https://claude.ai/code)

## 📦 可用插件

### 📋 reporting

從 git commit 歷史產生結構化的每日進度回報。自動依 conventional commit 類型分類變更，摘要已完成、進行中項目與注意事項。

- **`reporting:daily-report`** — 產生每日工作進度報告

> **觸發詞：** `「今日進度」` · `「每日回報」` · `「daily report」` · `「工作摘要」`

### 📝 docs

分析程式碼庫，自動產生或更新 `README.md`，包含準確的技術棧、專案結構、指令與架構概覽。保留現有的徽章、截圖與自訂區塊。

- **`docs:update-readme`** — 自動產生或更新 README.md

> **觸發詞：** `「更新 readme」` · `「產生 readme」` · `「sync readme」`


## 🚀 安裝方式

新增市集：

```
/plugin marketplace add weihung0831/dev-tools
```

個別安裝插件：

```
/plugin install dev-tools@daily-report
/plugin install dev-tools@readme-updater
```

## 🌐 語言支援

所有插件皆支援**英文**與**繁體中文**的觸發詞與輸出。

## 📄 授權

MIT

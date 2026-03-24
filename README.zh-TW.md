[English](./README.md) | [繁體中文](./README.zh-TW.md)

# 🛠️ dev-tools

> 由 [weihung0831](https://github.com/weihung0831) 維護的 Claude Code 插件市集 — 精選開發者生產力工具，涵蓋專案文件與工作流程自動化。

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Plugins](https://img.shields.io/badge/Plugins-3-green.svg)](#可用插件)
[![Claude Code](https://img.shields.io/badge/Claude_Code-Plugin-blueviolet.svg)](https://claude.ai/code)

## 📦 可用插件

### 📋 daily-report

從 git commit 歷史產生結構化的每日進度回報。自動依 conventional commit 類型分類變更，摘要已完成、進行中項目與注意事項。

> **觸發詞：** `「今日進度」` · `「每日回報」` · `「daily report」` · `「工作摘要」`

### 📝 readme-updater

分析程式碼庫，自動產生或更新 `README.md`，包含準確的技術棧、專案結構、指令與架構概覽。保留現有的徽章、截圖與自訂區塊。

> **觸發詞：** `「更新 readme」` · `「產生 readme」` · `「sync readme」`

### 🔍 analyzer

單一插件包含兩個技能：

- **`analyzer:spec`** — 解析 spec 與設計文件，萃取可執行的 **DO/DON'T 清單**與**測試案例導向的驗證指標**，依功能區域分組並標注優先級（P0/P1/P2）。
- **`analyzer:plan`** — 驗證並標準化計畫檔案（`plan.md` + `phase-XX.md`）。檢查必要區段、正確排序、狀態值與 E2E 測試情境格式。

> **觸發詞：** `「分析 spec」` · `「萃取需求」` · `「分析 plan」` · `「驗證計畫」`

## 🚀 安裝方式

新增市集：

```
/plugin marketplace add weihung0831/dev-tools
```

個別安裝插件：

```
/plugin install dev-tools@daily-report
/plugin install dev-tools@readme-updater
/plugin install dev-tools@analyzer
```

## 🌐 語言支援

所有插件皆支援**英文**與**繁體中文**的觸發詞與輸出。

## 📄 授權

MIT

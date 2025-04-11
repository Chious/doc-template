# 🧙‍♂️ 文件詠唱指南

## 背景

> 作為開發時需要的技術文件，作為專案開始的起手式。

## 模型選擇

|      | 非推理模型        | 推論模型                                            |
| :--- | :---------------- | :-------------------------------------------------- |
| 舉例 | Claude 3.5 Sonnet | Claude 3.7 Sonnet(Thinking)                         |
| 用途 | 1. 單一的 Debug   | 1. Multiple Task \n 2. 寫技術文件 \n 3. 總結 Commit |

## 範圍

### 開發前準備

- `rules/prd.md`: 設定 PRD 的格式
- `rules/code_style.md`: 設定程式碼風格的格式
- `rules/PlantUML.md`: 使用 PlantUML 繪製流程圖 (Alternative: [Mermaid](https://mermaid.js.org/))

### 技術研究

> 這塊仍然要交給 RD 去負責，包含根據不同的需求情境、可維護性，選擇不同的框架或工具，或是制定技術規範。

- 為什麼要選擇這個框架或工具？做了哪些比較？
- 需求對齊：做這個專案的效益是？

### 開發中

- `rules/pr_generaton.md`: 設定 PR 生成的格式
- `rules/commit.md`: 設定提交訊息的格式 [Reference](https://www.conventionalcommits.org/en/v1.0.0/)

**其他**

- 記憶 Debugs 時的資訊

```plaintext
based on the process of debugging, update `fy.md`
```

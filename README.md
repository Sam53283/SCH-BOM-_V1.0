# SCH-BOM-_V1.0
# SCH & BOM 自動比對工具 (V1.0)

這是一個基於 Python 的自動化工具，用於對比電路圖 (PDF) 與零件清單 (BOM)，並產出具有視覺化標記的 Excel 報告。

## 🚀 如何使用
點擊下方按鈕直接進入 Google Colab 執行環境：

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sam53283/SCH-BOM-_V1.0/blob/main/V1_0.ipynb)

## 📋 準備工作
在使用工具前，請確保您有以下兩個檔案：
1. **BOM.xlsx**: 包含 `Designator` 欄位的零件清單。
2. **SCH.pdf**: 電路圖檔案。

## ✨ 工具特色
* **自動排序**：依照零件類別 (PCB -> R -> C -> U...) 自動排序。
* **莫蘭迪配色**：產出美觀且易於閱讀的 Excel 報表。
* **視覺化對照**：在 Excel 第二分頁提供高亮標記的電路圖，方便目視檢驗。
* **釘選功能**：報表前三列自動釘選，方便大數據滾動查看。

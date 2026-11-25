# SimClass

國小數學微型教學多代理人 AI 學生模擬系統專案程式碼儲存庫。

## 🌐 互動網站（GitHub Pages）

👉 **[點此開啟 SimClass 學生 Agent 動態狀態卡片（互動網頁版）](https://ho-yu-chiao.github.io/simclass/)**

- 支援每次重啟／重新整理自動隨機產生初始掌握度與信心度
- 可點擊「🎲 重新隨機抽值」即時互動更新數值
- 支援「🖨️ 列印 / 存為 PDF」A4 排版輸出

## 📁 目錄結構

```text
simclass/
├── docs/
│   ├── index.html   # GitHub Pages 入口頁（自動導向 card.html）
│   └── card.html    # 5 大學生 Agent 動態狀態卡片互動網頁
├── .gitignore
└── README.md
```

## 👤 學生 Agent 狀態卡片 (`docs/card.html`)

包含 5 位異質性學生 Agent 的動態初始狀態與課堂行為設定：

- `AGENT_A` (`solid_understanding`)：A. 穩固理解型
- `AGENT_B` (`partial_understanding`)：B. 部分理解型
- `AGENT_C` (`misconception_holder`)：C. 迷思概念型
- `AGENT_D` (`anxious_low_achiever`)：D. 低成就焦慮型
- `AGENT_E` (`distracted_disruptive`)：E. 分心干擾型

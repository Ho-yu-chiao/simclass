# SimClass

國小數學微型教學多代理人 AI 學生模擬系統專案程式碼儲存庫。

## 目錄結構

```text
simclass/
├── docs/
│   └── card.html    # 5 大學生 Agent 動態狀態卡片（支援隨機初始化與 A4 列印）
├── .gitignore
└── README.md
```

## 學生 Agent 狀態卡片 (`docs/card.html`)

包含 5 位異質性學生 Agent 的動態初始狀態與課堂行為設定：

- `AGENT_A` (`solid_understanding`)：A. 穩固理解型
- `AGENT_B` (`partial_understanding`)：B. 部分理解型
- `AGENT_C` (`misconception_holder`)：C. 迷思概念型
- `AGENT_D` (`anxious_low_achiever`)：D. 低成就焦慮型
- `AGENT_E` (`distracted_disruptive`)：E. 分心干擾型

直接以瀏覽器開啟 `docs/card.html` 即可檢視、重新隨機抽值或列印為 A4 實體卡片。

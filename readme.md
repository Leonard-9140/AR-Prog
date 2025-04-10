# 阿拉伯語 AI 學習計畫(BETA)

歡迎來到 **阿拉伯語 AI 學習計畫**，這是一個結合人工智慧的創新學習方法，專為提升阿拉伯語學習樂趣與效率而設計的專案。本專案皆為AI可以直接使用的提示詞(Prompt)，以下內容皆基於Chat GPT-4o模型進行開發與調試。

## 專案目標
本專案旨在透過 AI 驅動的互動式內容，提升學習者對阿拉伯語的理解與記憶效率。包含但不限於(更多功能仍在開發中)使用經典且文化底蘊豐厚的伊斯蘭聖訓 (Ḥadīth) 和阿拉伯語詞根（الجذر）系統作為學習核心，使語言學習更貼近生活。**注意:**目前內容仍針對中文母語者學習阿拉伯語的狀態進行開發，因其內建輸出範例皆為基於繁體中文與阿拉伯語雙語並行的內容，而**無法保證**其他語言環境下的正常運作。

## 問題回饋與新功能許願池
- https://forms.gle/KG98HEdJpBd6vcsU7

### Prerequisites
- 阿拉伯語基礎(對語言有基礎認識並認得字母即足夠)
- Chat GPT或Claude，推薦使用**Chat GPT Plus**以獲得最佳品質回覆。
- 使用Chat GPT免費方案或Claude免費方案亦可運行。
- 可運行模型與版本：Chat GPT-4o、GPT4.5、Claude 3.7 Sonnet
- 一顆想學阿語的心

## 專案內容

### 📚 **聖訓為基礎的學習單元**
精心挑選正統且語法簡潔的伊斯蘭聖訓，涵蓋日常生活、品德行為等主題，打造結構清晰的學習單元。

每個單元包含：
- 阿拉伯語原文（含完整母音符號）
- 羅馬拼音逐字對應
- 精確且易懂的中文翻譯
- 詞彙表（附詳細解釋）
- 語法講解
- 實用的練習活動（造句、翻譯、朗讀指引）

使用者透過簡單的指令 `/start` 即可觸發內容，進行自主學習。更多細部調整指令仍在新增中，預計會在未來版本中發布。

### 🌳 **十式動詞詞根衍生器**
透過阿拉伯語詞根系統，尤其是動詞十式對詞根進行派生，學習者能輕鬆記住並理解詞彙間的關聯與變化。本系統根據線上阿拉伯語詞典進行嚴格驗證，確保資料準確。

系統將展示：
- 十式動詞變化與衍生詞
- 每個動詞形式的意義與用法
- 動名詞、名詞單複數形式
- 中文解釋與用法情境

學習者透過 `/start` 指令即可啟動此模組，透過系統化的表格快速掌握豐富詞彙。

## 使用方法
**方法一(推薦)**
使用以本專案內容製作之GPT機器人，輸入 `/start`以開始對話
- 聖訓基礎學習機器人
https://chatgpt.com/g/g-67ead1deae948191b043cbf8c7f3763a-yong-sheng-xun-xue-a-la-bo-yu

- 十式動詞衍生器
https://chatgpt.com/g/g-67ead3bafc448191ad2eee494e37b74d-a-la-bo-yu-xue-xi-ji-yu-dong-ci-shi-shi

**方法二(免費方案使用者推薦)**
- 選定你要使用的提示詞與AI模型，打開專案內`.txt`結尾之文件並複製檔案中所有文字(建議使用Chat GPT-4o，付費方案佳，其他AI推薦使用Claude)
- 於對話欄或專案功能所提供的指令欄位輸入前項複製之提示詞(prompt)
- 啟動聖訓學習模式：輸入指令 `/start`。
- 啟動詞根衍生學習模式：輸入指令 `/start`。
- 測驗自我學習成果(僅詞根模式)：輸入指令 `/test`，快速檢驗詞根變化掌握程度。

## 專案目標
- 🎯 精準詞彙與語法解釋，快速提高語言能力
- 🧠 根據阿拉伯語特有的詞根系統加深記憶，降低學習負擔
- 📖 透過文化底蘊濃厚的內容，增進語言與文化的雙重理解

## 版本紀錄
**v0.1.0(BETA)**
- Minimum Viable Product
- 可使用 `/start`啟用機器人的基本功能
- 開放GPT bot直接使用
- 推薦使用Chat GPT-4o模型

**v0.2.0(Apr.7, 2025)**
- 加入動詞十式動詞衍生器bot的啟動提示詞
- 版本紀錄加入日期戳記

**v0.2.1(Apr.11, 2025)**
- 新增錯誤回報及許願池表單
- 修改readme.md內容細節
# 🌌 CT宇宙 (CT Universe)

> **跨領域創新應用與數位工具整合平台**  
> 一站式匯聚個人品牌履歷、AI 英語學習、本地離線資安、策略遊戲、發票對獎與健康管理的多功能數位門戶。

---

## 📖 專案簡介 (About Project)

**CT宇宙 (CT Universe)** 是針對 `CTcool` 專案所建置的高質感整合入口首頁。本專案將 6 款各具特色的獨立網頁應用整合於統一的視覺門戶中，具備宇宙深空美學、全響應式設計（RWD）、即時搜尋與分類過濾、快速預覽彈窗以及深色/淺色主題切換功能。

所有應用皆採用 **純前端技術（Pure HTML5 / CSS3 / Vanilla JS）** 打造，**100% 支援本機離線即開即用**，無需複雜的後端安裝或建置流程。

---

## 🚀 收錄應用矩陣 (Applications Matrix)

| 圖示 | 程式檔案 | 專案名稱 | 類別領域 | 核心特色亮點 |
| :---: | :--- | :--- | :---: | :--- |
| 🧑‍💼 | [`aboutMe.html`](aboutMe.html) | **陳柏瑋 Po-Wei Chen** | 專業履歷 | 跨產業經營管理、數據分析實績、全方位專業成果與職涯歷程展示 |
| 🎙️ | [`dailyEnglish.html`](dailyEnglish.html) | **每日一句學英語** | 語言學習 | AI 語音多國口音擬真朗讀、每日精選實用金句、文法解析與對話練習 |
| 🛡️ | [`delTool.html`](delTool.html) | **本地個資假名化工具** | 資安工具 | 100% 瀏覽器本地離線運算、Excel/CSV 批次去識別化、自訂遮蔽假名規則 |
| ⚔️ | [`gameWar.html`](gameWar.html) | **政商大戰** | 休閒遊戲 | 政客 vs 富豪策略卡牌對決、特色技能連攜機制、復古霓虹街機打擊感 |
| 🐱 | [`moneygogo.html`](moneygogo.html) | **喵喵發財 對獎機** | 生活理財 | 115 年最新統一發票獎號、相機 QR Code 極速辨識對獎、獎金自動試算 |
| 💧 | [`water.html`](water.html) | **AquaFlow 喝水紀錄** | 健康生活 | 擬真動態水位波浪視覺、體重活動量目標試算、Chart.js 趨勢統計圖表 |
| 🌌 | [`index.html`](index.html) | **CT宇宙 門戶首頁** | 總覽入口 | 宇宙深空 Canvas 動態星空、毛玻璃卡片、即時搜尋過濾、快速預覽彈窗 |

---

## ✨ 核心特色與技術亮點 (Features)

1. **宇宙深空視覺與動態星空 (Cosmic Aesthetic)**：
   - 使用 HTML5 Canvas 繪製即時隨機星宿粒子，並具備游標微互動效果。
   - 融合毛玻璃擬態（Glassmorphism）、微發光光暈邊框（Neon Glow）與精緻漸層排版。
   - 內建一鍵切換**深色宇宙模式 (Dark Mode)** 與 **明亮極簡模式 (Light Mode)**。

2. **智慧即時搜尋與多標籤過濾 (Instant Search & Filter)**：
   - 支援依程式名稱、中英文關鍵字、技術標籤與功能描述即時秒速篩選。
   - 提供 6 大分類標籤按鈕（專業履歷、語言學習、資安工具、休閒遊戲、生活理財、健康生活），一鍵精準定位。

3. **作品卡片與快速預覽彈窗 (Work Cards & Quick Preview)**：
   - 每張卡片均具備獨立色彩識別、狀態標籤、檔案副標與 3 大核心條目。
   - 具備直覺的「開啟程式」主按鈕與「快速預覽」彈窗，可於首頁直接檢視詳細特色後一鍵啟動。

4. **全方位 RWD 響應式佈局 (Responsive Web Design)**：
   - 手機螢幕（單欄）、平板（雙欄）、電腦寬螢幕（三欄）自動最佳化流暢排版。

---

## 🛠️ 技術棧 (Tech Stack)

- **核心架構**：HTML5, CSS3, Modern Vanilla JavaScript (ES6+)
- **樣式與佈局**：[Tailwind CSS CDN](https://tailwindcss.com/), 自訂 CSS 關鍵幀動畫與毛玻璃濾鏡
- **圖示庫**：[FontAwesome 6.4](https://fontawesome.com/)
- **字型資源**：[Google Fonts](https://fonts.google.com/) (Outfit, Plus Jakarta Sans, Noto Sans TC, Inter, Zen Maru Gothic, Teko)
- **外部輔助套件**：
  - [Chart.js](https://www.chartjs.org/)（健康飲水數據視覺化圖表）
  - [SheetJS / xlsx](https://sheetjs.com/)（本地 Excel / CSV 資料解析與處理）
  - [HTML5-QRCode](https://github.com/mebjas/html5-qrcode)（相機發票 QR Code 即時掃描辨識）

---

## 💻 快速開始 (Quick Start)

本專案無需任何建置指令或伺服器環境，直接以瀏覽器開啟即可：

### 方法一：直接點擊開啟
1. 在檔案總管中雙擊 [`index.html`](index.html)。
2. 預設瀏覽器（Chrome, Edge, Safari, Firefox 等）將立即載入 CT宇宙 首頁。

### 方法二：使用本機 Live Server (選用)
若使用 VS Code 等編輯器，可透過 Live Server 擴充套件啟動：
```bash
# 或使用 Python 快速架設本地 HTTP 伺服器
python -m http.server 8000
```
開啟瀏覽器訪問 `http://localhost:8000/index.html` 即可。

---

## 📁 專案檔案結構 (Project Structure)

```text
CTcool/
├── README.md            # 專案說明文件 (本文件)
├── index.html           # CT宇宙 整合門戶首頁
├── aboutMe.html         # 陳柏瑋 Po-Wei Chen 個人品牌與專業履歷
├── dailyEnglish.html    # 每日一句學英語 AI 學習平台
├── delTool.html         # 本地端個資假名化與規則自訂工具
├── gameWar.html         # 政商大戰 策略卡牌遊戲
├── moneygogo.html       # 喵喵發財 統一發票對獎機
└── water.html           # AquaFlow 每日喝水紀錄與健康統計
```

---

## 📄 版權宣告 (License & Copyright)

© 2026 **CT Universe**. All rights reserved.  
專案作品由 CT 團隊設計與開發，支援個人學習、作品展示與本地實用工具用途。

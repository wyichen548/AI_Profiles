# 我的網頁作品集 (Web & AI Multimedia Portfolio)

> 專為**手機優先（Mobile-First）**互動體驗打造的前端作品集導覽中心，收錄實用商務系統、桌面小工具、資訊儀表板與生成式 AI 原創音樂。

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Design-Mobile--First-6366f1?style=flat-square)
![GitHub](https://img.shields.io/badge/Author-wyichen548-purple?style=flat-square&logo=github)

---

## 📱 專案亮點

- **手機優先體驗（Mobile-First Architecture）**：全站針對移動端觸控體驗與螢幕比例（375px~430px+）優化，具備常駐頂部與底部 App 風格導航欄、分類過濾與大觸控熱區反饋。
- **多元整合領域**：跨足商業電商 POS、桌面實用工具、即時 API 氣象儀表板與多媒體生成式音樂。
- **免繁瑣依賴**：純粹前端架構，可直接於瀏覽器預覽，並能無縫部署至 **GitHub Pages**。

---

## 📂 專案結構

```text
AI_Profiles/
├── assets/
│   └── Wendy_AI.png                   # 創作者形象照片
├── audio/
│   └── AI_music_Wendy.mp3             # Wendy 原創 AI 生成多媒體音樂 (3.57MB)
├── Web/
│   ├── drink_order/                   # 楊老大手搖飲料線上點餐系統
│   │   └── Order.html
│   ├── clock_widget/                  # 明星簡潔時鐘桌布小工具
│   │   └── Snoopy_desktop.html
│   └── weather_station/               # 台灣即時天氣氣象站儀表板
│       └── weather.html
├── index.html                         # 作品集首頁（手機優先、作品目錄、關於我）
└── README.md                          # 專案介紹說明文件
```

---

## 🎨 作品詳細介紹

### 1. 楊老大飲料店點餐系統
- **入口檔案**：[`Web/drink_order/Order.html`](Web/drink_order/Order.html)
- **類型**：商業系統 / POS / 購物車
- **簡介**：專為手搖茶飲店打造的完整響應式線上點餐平台。顧客可自由客製冰塊、甜度與加料選項，即時計算消費金額並支援購物車管理。送出後自動整合遠端試算表進行訂單歸檔，大幅提升小型店家接單與結帳效率。
- **使用 API**：
  - `Google Apps Script (GAS) Web App API`（接收訂單並寫入 Google 試算表）
  - `Fetch API`（無阻跨域非同步資料傳送）
  - `DOM Manipulation & Custom Modal API`
- **應用場景**：手搖飲門市顧客免安裝掃碼點餐、辦公室下午茶外帶團購快速彙整、市集快閃無紙化訂單。

---

### 2. 明星簡潔時鐘桌布
- **入口檔案**：[`Web/clock_widget/Snoopy_desktop.html`](Web/clock_widget/Snoopy_desktop.html)
- **類型**：桌面小工具 / 沉浸式時間 / 動態桌布
- **簡介**：打造極簡沉浸式數位時鐘與動態桌面展示小工具。支援12/24小時制切換、即時秒數與完整日期星期資訊。內建高畫質桌布自動輪播、模糊度及透明遮罩自訂調節功能，兼具實用時鐘與優雅螢幕保護桌布。
- **使用 API**：
  - `JavaScript Date & Timing API`（毫秒級校時動態計時器）
  - `Fetch API`（讀取自訂 CSV 圖庫清單）
  - `CSS Backdrop-Filter & Keyboard Event API`（毛玻璃濾鏡與鍵盤快捷鍵切換）
- **應用場景**：辦公室次螢幕或平板常駐翻頁時鐘、會議中場休息投影畫面、沉浸式工作專注番茄鐘。

---

### 3. 台灣即時天氣氣象站
- **入口檔案**：[`Web/weather_station/weather.html`](Web/weather_station/weather.html)
- **類型**：資訊儀表板 / 玻璃擬態 / 氣象預報
- **簡介**：採用現代玻璃擬態風格的全台即時天氣儀表板。使用者可快速切換22個縣市，即時掌握最新溫度、體感、濕度、紫外線與降雨機率，並呈現未來多日氣溫走勢圖，讓每日出門穿著與戶外行程規劃變得一目了然。
- **使用 API**：
  - `Open-Meteo Weather Forecast API`（全球開放氣象與多日預報）
  - `Fetch API`（非同步抓取與 JSON 解析）
  - `Geolocation Coordinates Mapping`（台灣全縣市經緯度映射演算法）
- **應用場景**：每日早晨出門穿搭與雨具評估、跨縣市出遊露營行程天候掌握、外勤物流即時氣候避險。

---

### 4. AI 音樂創作 (AI_music_Wendy)
- **檔案路徑**：[`audio/AI_music_Wendy.mp3`](audio/AI_music_Wendy.mp3)
- **類型**：多媒體創作 / 生成式 AI 音樂
- **簡介**：融合生成式 AI 與創意編曲的多媒體音樂創作。曲風兼具節奏律動與療癒氛圍，透過精確提示詞調校樂器層次與旋律起伏。網頁內建無障礙 HTML5 音訊控制元件，支援隨選即聽、進度調整與一鍵無損音質下載。
- **使用 API**：
  - `HTML5 Media Audio API`（音訊播放、進度緩衝與音量控制）
  - `Binary Streaming / Blob Download Interface`
- **應用場景**：YouTube / Podcast 節目免版稅片頭 BGM、編程閱讀時專注背景音、產品展示短片配樂素材。

---

## 🚀 快速開始與本地預覽

1. **直接開啟**：
   在電腦或手機的瀏覽器中直接雙擊打開專案根目錄下的 [`index.html`](index.html) 即可開始體驗。

2. **使用輕量本地伺服器**：
   ```bash
   # 使用 Python 內建伺服器
   python -m http.server 8080

   # 或使用 Node.js http-server
   npx http-server . -p 8080
   ```
   接著開啟瀏覽器前往 `http://localhost:8080`。

3. **啟用 GitHub Pages 線上公開部署**：
   - 進入本倉庫的 **Settings** > **Pages**
   - 在 **Build and deployment** 下方的 **Branch** 選擇 `main` 分支並設定目錄為 `/ (root)`
   - 點擊 **Save**，即可透過 `https://wyichen548.github.io/<repo-name>/` 獲得專屬線上公開作品集網址！

---

## 👩‍💻 關於作者 (About Me)

- **作者**：Wendy (溫蒂)
- **GitHub**：[@wyichen548](https://github.com/wyichen548)
- **理念**：「用 AI 賦予想法形體，用代碼打造貼心體驗。專注於手機端的每一處細節，創造有價值的小巧思。」

---

## 📄 授權條款 (License)

本專案採用 [MIT License](LICENSE) 授權，歡迎學習交流與改進！

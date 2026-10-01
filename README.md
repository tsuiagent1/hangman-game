# Hangman Challenge 猜單字挑戰賽 (崔董特仕版)

專為崔董客製打造之現代化響應式 Hangman 猜單字 Web 應用，內建電競硬體、投資財務與 AI 科技三大專業領域題庫，具備 SVG 動態向量絞刑台、粒子彩帶特效、Web Audio 擬真音效與實體/虛擬雙模操作。

---

## 🎮 專案亮點與特色

1. **零相依與純原生架構 (Zero-Dependency)**：
   - 採用原生 HTML5、現代 CSS3 (Flexbox/Grid) 與 ES6+ JavaScript 單檔架構。
   - 零第三方外掛依賴，加載速度低於 100ms，100% 完美相容 GitHub Pages 靜態託管。

2. **三大專屬客製題庫**：
   - **電競硬體 (Esports & Hardware)**：收錄 ZOWIE、DYAC、SENSOR、OPTICAL、REFRESH、WIRELESS、ERGONOMIC、POLLING 等電競專業術語。
   - **投資與財務 (Investment & Finance)**：收錄 PORTFOLIO、DIVIDEND、REBALANCE、LIQUIDITY、VOLATILITY、BENCHMARK、STOPLOSS 等投資風控核心詞彙。
   - **AI 與軟體科技 (AI & Tech)**：收錄 FASTAPI、GITHUB、SANDBOX、PIPELINE、CONTAINER、AUTOMATION、BACKEND 等現代技術工程術語。

3. **動態視覺與多媒體回饋**：
   - **向量動態絞刑台**：以原生 SVG 向量繪製，隨失誤次數逐步解鎖軀幹部位（頭、身、左手、右手、左腳、右腳）。
   - **Web Audio 輕量音效**：無需加載音訊檔，直接調用 Web Audio API 合成命中、失誤、通關號角與失敗音效。
   - **勝利彩帶 (Confetti)**：通關時觸發全螢幕物理粒子噴射彩帶。

4. **全端自適應與雙模操作**：
   - 筆電/桌機：支援實體鍵盤直接盲打（敲擊 A-Z 鍵輸入、Space 鍵取得提示、Enter 鍵快速開局）。
   - 行動裝置：內建人體工學 QWERTY 觸控虛擬鍵盤，自適應 iPhone 與 Android 各種螢幕尺寸。
   - 戰績紀錄：自動將勝率、連勝紀錄、得分累計保存於瀏覽器 `localStorage`。

---

## 🚀 部署至 GitHub Pages

本專案已完全相容 GitHub Pages 自動託管服務：

1. 於 GitHub 儲存庫進入 **Settings** ➔ **Pages**。
2. 在 **Build and deployment** 下的 **Source** 選擇 `Deploy from a branch`。
3. **Branch** 選擇 `main`，目錄選擇 `/ (root)`，點擊 **Save**。
4. GitHub Pages 將在數十秒內完成靜態網頁發布，並產出公開 HTTPS 存取網址：
   `https://<用戶名>.github.io/hangman-game/`。

---

## 🕹️ 本地即刻暢玩

無需架設後端伺服器，直接下載本專案原始碼，雙擊 `index.html` 即可於 Chrome、Safari、Edge 等任何瀏覽器離線暢玩。

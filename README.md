# Mei Guild Piano Profile Links Page

Elegant multi-link landing page for piano teacher 林美杏，展示社群平台、教學理念、QR Code 與聯絡資訊。專案使用純 HTML、CSS，並透過 CDN 載入 QR Code Styling 套件，適合部署在 GitHub Pages 或任何靜態網站服務。

## 專案結構

- `index.html`：主要頁面內容與動態初始化腳本。
- `styles.css`：頁面風格與響應式樣式。
- `static/Headshot.JPG`：老師個人頭像。

## 本機預覽

1. 將專案下載到本機：
   ```bash
   git clone <your-repo-url>
   cd <your-repo-folder>
   ```
2. 直接開啟 `index.html` 即可在瀏覽器中預覽。

## 部署到 GitHub Pages

1. 將程式碼推送到 GitHub 倉庫的 `main`（或 `master`）分支。
2. 在 GitHub 倉庫頁面，進入 **Settings → Pages**。
3. 於 **Branch** 選擇 `main`，資料夾選擇 `/ (root)`，點擊 **Save**。
4. 等待 GitHub Pages 建置完成後，使用提供的網址存取頁面。

## 客製化建議

- 更新 `index.html` 中的社群連結與文案以符合最新資訊。
- 以 `static` 資料夾替換頭像或加入其他資產。
- 調整 `styles.css` 內的色彩與排版以符合品牌需求。
- 需要變更 QR Code 連結時，修改 `.qr` 區塊的 `data-url` 屬性或於腳本中自訂邏輯。

## 授權

此專案內容由作者與林美杏老師所有，未經許可請勿轉載。

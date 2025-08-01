# n8n on Render (Clean Setup)

這是一個乾淨的 n8n 專案模板，支援 Google OAuth、Google Sheets、Gmail 等。

## 使用方法

1. Fork 此 Repo 到自己的 GitHub。
2. 修改 `.env.template`：
   - `N8N_HOST` 和其他相關變數換成 Render 網域資訊與加密金鑰。
3. 建立 Web Service：
   - 選 GitHub Repo
   - Build Command：`npm install`
   - Start Command：`n8n`
   - 貼 `.env.template` 內容進 Render 的「Add from .env」
4. Deploy 成功後開啟：
https://YOUR_RENDER_DOMAIN.onrender.com

markdown
複製
編輯
5. 測試 Google OAuth：
- 建 Google Sheets / Gmail Credential
- 點「Connect」並完成授權

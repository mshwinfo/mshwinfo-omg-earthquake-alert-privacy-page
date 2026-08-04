# OMG 台灣地震速報 — 隱私權政策與服務條款頁

本 repo 透過 GitHub Pages 提供「OMG 台灣地震速報」法務文件的**正本**：

| 文件 | 網址 |
|---|---|
| 隱私權政策 | **https://mshwinfo.github.io/mshwinfo-omg-earthquake-alert-privacy-page/** |
| 服務條款 | **https://mshwinfo.github.io/mshwinfo-omg-earthquake-alert-privacy-page/terms.html** |

這個網址被以下地方引用，改內容只要改這裡：

- App 內「設定 → 關於 → 隱私權政策」與首次啟動的隱私同意視窗
- 主專案 Cloudflare Worker 的 `https://omgalert.mshw.info/privacy`（301 轉址到本頁）
- AppGallery Connect 上架表單的「隱私政策網址」欄位

修改流程：編輯 `index.html` → 合併進 `main` → GitHub Pages 自動重新部署（約 1 分鐘）。

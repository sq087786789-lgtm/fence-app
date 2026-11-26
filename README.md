# 圍籬尺寸與工程圖工具（fence-app）

這是上慶企業社的**圍籬尺寸試算與參考工程圖小工具**（支援網頁版、PWA 與 Android Capacitor 打包）。

## 這個專案是幹嘛用的？
- 輸入場地四邊長度、立柱間距與大門位置。
- 自動幫忙計算圍籬總周長與所需立柱數量。
- 產生對應的參考工程圖（`drawing.html`），方便現場溝通與核對尺寸。

## 主要檔案說明
- `index.html`：主操作畫面（輸入尺寸與參數）。
- `drawing.html`：工程圖顯示／輸出畫面。
- `manifest.json` / `sw.js`：手機桌面安裝（PWA）設定。
- `capacitor.config.json` / `android/`：Android App 打包設定。

## 備註
- 本倉庫為公開工具程式，不含任何客戶個資或正式報價單資料。

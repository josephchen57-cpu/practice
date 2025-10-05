# 📇 名片辨識產生器（BusinessCardOCR）

本專案提供 **網頁版**與**桌面版**的名片辨識工具，使用 OCR 技術自動擷取名片上的聯絡資訊，並整理成結構化資料格式，方便儲存與管理。

---

## 🚀 功能特色

- 上傳名片圖片，自動辨識姓名、電話、公司名稱、職稱等資訊
- 支援網頁瀏覽器與 Python 桌面環境
- 使用 Tesseract OCR 技術進行文字辨識
- 輸出 JSON 格式，方便整合聯絡人資料
- 可擴充匯出 CSV、vCard 或雲端儲存功能

---

## 🌐 網頁版使用方式

### 📁 路徑：`web_version/index.html`

### ✅ 使用步驟：
1. 開啟 `index.html`（使用 Chrome、Edge 等瀏覽器）
2. 上傳名片圖片（JPG、PNG）
3. 系統會自動辨識並顯示聯絡人資訊（JSON 格式）

### 🔧 技術說明：
- 使用 Tesseract.js 進行瀏覽器端 OCR
- JavaScript 處理文字解析與資料整理

---

## 🖥️ 桌面版使用方式

### 📁 路徑：`desktop_version/card_reader.py`

### ✅ 安裝步驟：
1. 安裝 Python（建議使用 3.9 以上版本）
2. 安裝必要套件：
   ```bash
   pip install -r requirements.txt

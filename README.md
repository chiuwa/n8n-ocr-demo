# n8n OCR Demo - 圖片文字識別工具

一個簡單易用的n8n OCR（光學字符識別）工具，支援圖片上傳並自動提取其中的文字內容。
![image](https://github.com/user-attachments/assets/b7fba2e1-a328-41ae-bbf1-8ea3b3c7c2de)
![image](https://github.com/user-attachments/assets/df1dfa7f-8d9b-43e2-a193-abf297754fd7)
![image](https://github.com/user-attachments/assets/ecc9d14d-e84e-4449-be8f-a92a637885d7)
![image](https://github.com/user-attachments/assets/9959939b-91d6-4806-bb7b-aa1b47d3dae3)

## ✨ 功能特點

- 🖼️ **多格式支援**: 支援 JPG、PNG、GIF 圖片格式
- 🎯 **拖拽上傳**: 支援拖拽檔案到上傳區域
- 🔍 **智能識別**: 使用AI技術進行文字識別
- 📊 **結構化資料**: 自動提取並格式化結構化資訊（如名片、文件等）
- 📋 **一鍵複製**: 支援複製識別文字、結構化資料或完整JSON回應
- 📱 **行動裝置友善**: 基本響應式設計，支援手機和平板瀏覽
- 🎨 **波波球UI**: 漸層設計和動畫效果

## 🚀 使用方法

1. **上傳圖片**: 點擊上傳區域選擇圖片，或直接拖拽圖片到指定區域
2. **預覽確認**: 檢查上傳的圖片預覽
3. **開始處理**: 點擊「🚀 開始 OCR 處理」按鈕
4. **查看結果**: 
   - 查看識別出的文字內容
   - 檢視結構化資料（如果適用）
   - 複製需要的內容

## 🛠️ 技術特點

- **純前端實現**: 使用原生 HTML、CSS、JavaScript
- **模組化設計**: 遵循單一職責原則
- **事件驅動架構**: 清晰的事件處理邏輯
- **錯誤處理**: 完善的錯誤提示和處理機制
- **效能優化**: 
  - 檔案大小限制（10MB）
  - 格式驗證
  - Base64 編碼優化

## 📋 系統需求

- 現代網頁瀏覽器（Chrome、Firefox、Safari、Edge）
- 網路連接（用於 OCR API 呼叫）
- JavaScript 啟用

## ⚙️ 設定說明

1. **下載檔案**: 下載 `index.html` 檔案
2. **開啟檔案**: 使用瀏覽器直接開啟 HTML 檔案
3. **配置 API**: 如需使用自己的 OCR 服務，請修改 JavaScript 中的 `webhookUrl`

```javascript
// 在 index.html 中修改此行
this.webhookUrl = 'YOUR_OCR_WEBHOOK_URL';
```


## 🎯 支援的資料類型

- 一般文字內容
- 名片資訊（姓名、職稱、聯絡方式、地址等）
- 文件內容
- 手寫文字（依 OCR 服務能力而定）

## 📸 使用示例

1. 上傳包含文字的圖片
2. 系統自動識別並提取文字
3. 如為名片或結構化文件，會自動分類資訊
4. 可複製文字內容或下載 JSON 格式資料


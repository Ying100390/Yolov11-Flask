# Flask YOLOv11 Web

## 簡介

這是一個基於 Flask 與 YOLOv11 實現的物件檢測網頁應用程式，用戶可以上傳圖片進行目標檢測，並實時查看檢測結果。

---

## 功能特色

- **物件檢測**：上傳圖片，透過 YOLOv11 模型進行目標檢測。
- **結果視覺化**：將檢測結果以圖片形式回傳，包含標註框與分類標籤。
- **簡易部署**：基於 Flask 框架，方便進行本地或伺服器部署。

---

## 項目結構

專案檔案包含以下內容：

- `app.py`：主應用程式檔案，負責後端邏輯與路由。
- `templates/`：存放 HTML 檔案的資料夾，用於前端顯示。
- `static/`：包含靜態資源，如 CSS 和 JavaScript。
- `uploads/`：用戶上傳的圖片存放目錄。
- `output/`：存放檢測後圖片的目錄。
- `best.pt`：YOLOv8 訓練好的模型權重檔案。

---

## 如何使用

### 1. 安裝 Conda 環境

1. 創建 Conda 環境：
   ```bash
   conda create -n flask-yolov8 python=3.8 anaconda
   ```
2. 啟用環境：
   ```bash
   conda activate flask-yolov8
   ```

### 2. 下載專案

   ```bash
   git clone https://github.com/Ying100390/Yolov11-Flask.git
   cd Yolov11-Flask
   ```

### 3. 安裝依賴

   ```bash
   pip install -r requirements.txt
   ```

### 4. 啟動應用

   ```bash
   python app.py
   ```

### 5. 開啟瀏覽器

- 在瀏覽器中打開 `http://127.0.0.1:5000`。
- 上傳圖片並查看檢測結果。

---

## 技術架構

- **後端框架**：Flask
- **深度學習模型**：YOLO11
- **前端技術**：HTML、CSS、JavaScript

---

## 截圖展示

### 主畫面
![Home](https://github.com/user-attachments/assets/ce44a86b-dcec-44f7-830f-052eb5719a3b)


### 檢測結果
![image](https://github.com/user-attachments/assets/38b3f763-13de-4380-8fad-74945807cee3)

![image](https://github.com/user-attachments/assets/0bfbf655-7c9b-44e8-8c9d-5a36a087ea83)



---

## 貢獻

歡迎提出 Issue 或提交 Pull Request，協助改善此專案！
---



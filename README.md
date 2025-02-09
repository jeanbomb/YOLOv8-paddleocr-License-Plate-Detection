# 車牌辨識系統 (YOLOv8-paddleocr-License-Plate-Detection)

本專案在 Kaggle 上開發，利用 YOLOv8 進行車牌偵測，並結合 PaddleOCR 進行文字辨識，透過 OpenCV 進行影像處理，最後使用 Matplotlib 視覺化呈現結果。

## 📌 專案特色
- **YOLOv8 車牌偵測**：使用深度學習模型 YOLOv8 來準確偵測車牌位置。
- **OCR 文字辨識**：
  - **PaddleOCR**：支援中英文的高精度辨識工具。
- **OpenCV 影像處理**：
  - 色彩空間轉換
  - 影像前處理優化
- **Matplotlib 視覺化**：即時顯示偵測與辨識結果。

## 📊 目前進度
✅ YOLOv8 模型載入  
✅ PaddleOCR 整合  
✅ 批次處理功能  
❌ 效能優化待改進  

## ⚙️ 主要技術
- **YOLOv8** (Ultralytics)
- **PaddleOCR**
- **OpenCV**
- **PIL (Pillow)**
- **Matplotlib**
- **NumPy**
- **Kaggle**

## 📌 未來改進方向
- **效能優化**
  - 影像預處理流程優化
  - 批次處理效能提升
  - 記憶體使用優化
- **功能擴充**
  - 增加更多圖片格式支援
  - 新增結果儲存功能
  - 加入更多辨識參數設定

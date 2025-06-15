# 🧠 Vision AI Assistant — TSMC IT CareerHack 2025 專案

> AI 視覺任務規劃與輔助系統
> A6 組｜蔡哲偉、蔡旻桓、楊淨雯、賴柏叡

## 📌 專案簡介

本專案為參加 **TSMC 2025 IT CareerHack** 黑客松比賽的參賽作品，旨在開發一個能夠理解自然語言指令、自動規劃視覺任務、並執行影像處理與分析工作的 AI 視覺任務助理系統。透過整合多種強大模型與提示工程技術，提供視覺工程師更加高效、直觀的操作方式。

## 🧩 系統架構概覽

本系統由以下幾個核心模組構成：

* **Prompt 設計與規劃**

  * Prompt Planning：整合知識檢索與案例比對
  * Few-shot Prompting：參考範例以提高模型理解力
  * Chain-of-Note Prompting：類似 Chain-of-Thought 的邏輯提示策略

* **模型組件**

  * `DINO`：支援自然語言物件偵測
  * `SAM2`：Segment Anything Model，用於任意影像分割
  * `Diffusion`：圖像生成與修補
  * `cv2`：處理影像旋轉的自定義函式
  * `Vertex AI`：進行圖像生成與提示分析

* **前端介面**

  * 使用 Next.js 打造直覺式 UI
  * 內建雷達圖等視覺化元件

## 🎥 Demo

▶️ [Demo 影片連結](https://youtu.be/XsJ37pzegiA?si=WrSmjv6QgaHMD8nM)

## 📁 專案內容

```
Vision-AI-Assistant/
├── AAID_A6.pptx              # 專案簡報
├── backend/                  # 推論與影像處理模組
├── prompts/                  # Prompt 規劃與設計
├── tools/                    # 支援工具（e.g., OpenCV, SAM）
└── README.md                 # 本檔案
```

## 🚀 技術亮點

* 利用多模態提示語言驅動 AI 任務流程
* 自動化影像處理任務（物件檢測、分割、修補）
* 高度模組化、可擴充的設計架構

## 🙌 聯絡我們

本專案由 A6 組開發：蔡哲偉、蔡旻桓、楊淨雯、賴柏叡
如需更多技術細節，歡迎參考簡報或聯繫作者。


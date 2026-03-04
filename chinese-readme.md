# 嗨，我是 Yu-Chi Ko（datafox）

> **LLM Systems Research Engineer —— 專注於打造具結構性、可優化、且具財金基礎的推理系統。**

我的研究與工程工作橫跨大型語言模型、最佳化理論與量化金融。
我關注的核心問題，是如何將 LLM 從「黑箱生成模型」轉化為**結構化、可重現、可審計的系統**，特別是在對可靠性與風險意識要求極高的應用場景中。

結合財務金融與資料科學背景，我將 LLM 視為**可嵌入於確定性、可評估流程中的系統元件**，而非單純的文本生成工具。

相較於打造零散的 demo，我更專注於：

* 設計 **基於搜尋的推理框架**
* 提升 **LLM 的可靠性與評估機制**
* 連結 **金融建模與符號計算**
* 建構模組化、可重現、可部署的系統架構
* 
<div align="left">
  <a href="https://www.linkedin.com/in/koyuchi/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://datafox.tw/">
    <img src="https://img.shields.io/badge/Website-datafox.tw-0A66C2?style=for-the-badge&logo=google-chrome&logoColor=white" />
  </a>
</div>


---

## 研究導向工程專案

### 1️⃣ [Automatic_Generic_Optimizer](https://github.com/datafox-tw/Automatic_Generic_Optimizer)

*一個以基因演算法為核心的結構化 LLM 推理最佳化框架。*

本專案以「演化搜尋」取代傳統的對抗式辯論優化方式，核心設計包括：

* 將結構化推理輸出定義為可演化的「基因」
* 在推理過程上實作 crossover 與 mutation 機制
* 透過 fitness scoring 選擇並精煉候選解答
* 以搜尋式最佳化取代單次 prompt 推理

核心關注方向：

* LLM 推理搜尋空間設計
* Prompt 與推理步驟層級的變異運算子
* Fitness 評分與解答整合機制
* 可重現的評估流程

此專案體現了我的核心研究方向：

**將 LLM 推理視為一個搜尋與最佳化問題。**

---

### 2️⃣ [Chinese_RAG_Expert_Finetuning_System](https://github.com/datafox-tw/Chinese_RAG_Expert_Finetuning_System)

*一套可重現訓練流程的領域適應型 RAG 系統。*

本專案最初源自以 Recall@10 與 MRR@10 為核心的檢索研究任務，後續被重新設計為一個模組化系統，具備：

* 開源 LLM（如 Qwen、LLaMA）的微調流程
* Retriever 與 Reranker 的最佳化整合
* 結構化資料格式與可重複訓練設計
* 實驗管理的前端介面整合

設計重點在於：

* 強調可重現性，而非一次性實驗
* 模組化的 retriever / reranker 架構
* 以評估指標為導向的系統最佳化

此專案展現了我將研究目標轉化為**系統級實作能力**的能力。

---

### 3️⃣ [GLoVE (GARCH-informed Loss for Volatility Estimation)](https://github.com/datafox-tw/GLoVE)

*融合經濟計量模型與深度學習的多資產波動率預測系統。*

此專案整合：

* 傳統金融模型（GARCH 系列）
* 神經網路架構（如 TSMixer）
* 端到端訓練與評估流程
* 清楚的重訓與實驗重現說明

核心關注方向：

* 多資產風險建模
* 經濟計量與神經模型融合
* 結構化實驗設計
* 可重現的金融機器學習流程

這項工作反映了我長期對於：

**LLM × 金融 × 結構化建模** 的興趣與探索。

---

### 4️⃣ [CloudNative_Stadium_System](https://github.com/datafox-tw/CloudNative_Stadium_System)

*以生產級架構為導向的雲原生全端系統。*

本專案作為雲原生應用實作，包含：

* 後端 API 與資料庫整合
* 多角色使用者前端介面
* 容器化部署流程
* 可擴展的服務導向設計

目的在於：

* 展示系統架構設計能力
* 呈現模型開發之外的端到端工程能力
* 保持對生產級 Web 系統開發的熟悉度

---

## 核心技術主軸

與其羅列工具，我更關注在以下技術面向的深度探索：

**LLM 系統與代理架構**

* 推理搜尋與最佳化
* RAG 設計與評估
* 多步驟工作流程編排
* 模型微調與基準測試

**最佳化與演算法**

* 基因演算法
* 貝葉斯最佳化
* 結構化搜尋設計
* 符號與確定性計算

**AI × 金融**

* 波動率建模
* 因果推論
* 風險導向系統設計

**工程基礎能力**

* Python（主要語言）
* 模組化與可重現設計
* Docker 化工作流程
* 嚴謹的實驗設計與評估紀律

---

## 研究方向

我特別關注：

* 設計以搜尋為核心，而非僅依賴 prompt 的 LLM 系統
* 讓推理過程具備可審計與結構化驗證能力
* 融合符號計算、最佳化理論與金融建模
* 在風險約束與評估紀律下運作的 AI 系統設計

長期願景是：

LLM 不應僅生成看似合理的文本，
而應成為**嵌入於可負責任系統中的結構化推理引擎**。

### GitHub Stats

<div align="center">
  <img src="https://github-readme-stats-theta-ochre-67.vercel.app/api?username=datafox-tw&show_icons=true&theme=dracula&hide_border=true&bg_color=0d1117" />
  <img src="https://github-readme-stats-theta-ochre-67.vercel.app/api/top-langs/?username=datafox-tw&layout=compact&theme=dracula&hide_border=true&bg_color=0d1117" />
</div>


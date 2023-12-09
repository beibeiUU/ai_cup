# 文字辨識模型訓練項目
 
## 專案介紹
本專案是先使用已經整理好的醫療檔案(訓練集)來訓練模型，並把訓練好的模型使用在需要整理的醫療檔案(驗證集)上。
本專案使用的模型是EleutherAI/pythia-160m-deduped
若要使用更大資料量的模型請參考:https://huggingface.co/EleutherAI/pythia-160m-deduped

## 專案連結
https://colab.research.google.com/drive/1CFAUzvW-qLOkmQwiKbUeZ9jkTfs1OdRU?usp=sharing#scrollTo=qMO95olzhlts

## 上手指南

“[/your_github_name/your_repository](https://github.com/beibeiUU/ai_cup/blob/main/%E4%B8%8A%E6%89%8B%E6%8C%87%E5%8D%97)”

## 使用資料
1.訓練集:"[opendid_set1.tsv](https://github.com/beibeiUU/ai_cup/blob/main/opendid_set1.tsv)"
2.驗證集:"[opendid_valid.tsv](https://github.com/beibeiUU/ai_cup/blob/main/opendid_valid.tsv)"

## 為何要在google colab上開發

1. 免費的計算資源：Google Colab 提供免費的處理器（CPU）、圖形處理器（GPU）和張量處理器（TPU）資源。對於初學者或沒有強大硬件的研究人員來說，這是一個很大的優勢。
2. 無需配置環境：在 Colab 上，您無需擔心安裝和配置機器學習庫和依賴項。大部分常用的庫（如 TensorFlow、PyTorch、Keras 等）已預先安裝且可立即使用。
3. 易於共享和協作：與 Google Docs 類似，Colab 筆記本可以輕鬆地與其他用戶共享和協作。這對於教育、團隊項目和協同工作非常有用。
4. 基於網頁的界面：由於 Colab 是一個基於瀏覽器的平台，您可以在任何有網絡連接的設備上使用它，無需特定的硬件或操作系統。
5. 與 Google Drive 集成：Colab 與 Google Drive 緊密集成，方便您存取和儲存數據集、模型、腳本等文件。
6. 交互式數據分析和視覺化：Colab 支持各種數據視覺化工具，如 Matplotlib、Seaborn 等，並提供交互式數據分析的能力。
7. 教育和學習資源：Colab 廣泛用於教育和自學，許多開放的教育資源和專案都使用 Colab，方便學生和學習者訪問。
8. 快速原型開發：對於快速測試概念或進行原型開發，Colab 提供了一個方便且快速的解決方案。

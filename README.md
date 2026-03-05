# AI-Cup-2024-Power-Prediction
深度學習｜⚡ AI Cup 2024：基於區域微氣候資料之發電量預測模型 (Power generation prediction based on regional microclimate data) 

## 📂 Repository Structure
AI-Cup-2024-Power-Prediction/
├── competition-guidelines/       # 競賽官方說明文件與資料格式規範
├── sample-data/
│   └── microclimate_sample.csv   # 僅放置部分微氣候數據供格式參考 (不含原始大檔)
├── scripts/
│   ├── 01_eda_and_cleaning.ipynb # 資料降噪與前處理管線
│   └── 02_model_training.ipynb   # TimesNet 訓練與 Optuna 超參數搜索
├── reports/                      
│   └── stat_dl_final_report.pdf  # 🏆 專案期末報告與成效對比圖 (Start Here!)
├── checkpoints/                  # 存放訓練完成之 TimesNet 模型權重 (Model weights)
├── submission-prediction-csvs/   # 最終上傳至 AI CUP 系統之預測結果檔
└── README.md

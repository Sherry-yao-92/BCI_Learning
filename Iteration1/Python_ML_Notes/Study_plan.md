📅 第一階段（第 1 個月）：行動清單與學習分配 🚀

🌟 第 1 週：Python/Pandas 數據科學基礎

週一 Pandas 基礎： 學習 pd.read_csv() 載入數據，df.head(), .info() 檢查數據類型。[Git] 提交 Pandas_Intro.md
週二 Pandas 數據探索： 學習 df.describe() 統計摘要，處理字串 (.str)。[Git] 提交 Pandas_EDA.md
週三數據篩選與分組： 學習布林索引 (df[df['col'] > 0]) 和 df.groupby()。[Git] 提交 Pandas_Grouping.md
週四 Git/GitHub 實戰 (A4)： 練習 git clone, git add, git commit。 開始閱讀 A3： 什麼是 EEG？[Git] 提交 Git_Practice.md
週五 NumPy 基礎： 學習陣列創建、索引、基本數學運算。[Git] 提交 NumPy_Basic.md
週六實作 P1 專案 (1/3)： 載入糖尿病數據集，進行數據探索，並使用 Matplotlib/Seaborn 繪製 原始數據分佈圖。[專案] 提交 Diabetes_Project_EDA.ipynb
週日 A3 BCI 概念： 學習 EEG 波段 (Delta, Alpha, Beta) 及其對應的認知狀態。[A3] 提交 A3_EEG_Waves.md

🌟 第 2 週：數據清理與 ML 基礎
週一 Pandas 數據清理： 處理缺失值 (.fillna())，使用 df.replace() 處理異常值 (0 值)。[Git] 提交 Pandas_Cleaning.md
週二 Scikit-learn 基礎： 學習 train_test_split 切分數據，和 StandardScaler 特徵縮放。[Git] 提交 Sklearn_Prep.md
週三 Logistic Regression (A2)： 學習原理，如何在 Scikit-learn 中引入並訓練模型。[Git] 提交 Logistic_Reg_Principle.md
週四 Decision Tree (A2)： 學習原理，如何在 Scikit-learn 中引入並訓練模型。[Git] 提交 Decision_Tree_Principle.md
週五 ML 流程： 學習交叉驗證 (KFold) 和 Pipeline 的基本概念。[Git] 提交 ML_Process.md
週六實作 P3 專案核心 (2/3)： 整合清理與 ML。 在 Diabetes_Project/ 中建立 data_processor.py 模組，完成數據清理和特徵縮放，並訓練 Logistic Regression 模型。[專案] 提交 data_processor.py 和 Diabetes_Project_ML_Core.ipynb
週日 A3 BCI 概念： 學習 BCI 範式：運動想像 (MI) 和 P300 的基本原理和用途。[A3] 提交 A3_BCI_Paradigms.md

🌟 第 3 週：模型比較與評估指標
週一性能指標： 學習 Accuracy, Precision, Recall, F1-Score 的定義和計算。[Git] 提交 ML_Metrics.md
週二混淆矩陣： 學習 confusion_matrix，並理解 假陽性/假陰性 的意義。[Git] 提交 Confusion_Matrix.md
週三 A3 神經生理學： 學習神經元放電和訊號類型（Spikes vs. LFP/EEG）。[A3] 提交 A3_Neural_Signals.md
週四 A3 BCI 概念： 學習 BCI 系統架構（從電極到輸出）。[A3] 提交 A3_BCI_Architecture.md
週五工程習慣： 學習 Git Branch 的基本使用，將筆記從 feature branch 合併到 main。[Git] 提交 Git_Branch_Practice.md
週六實作 P3 進階 (3/3)： 模型比較與臨床分析。 訓練 Decision Tree，比較兩種模型的性能。計算並分析兩種模型的 Recall。[專案] 更新 Diabetes_Project_ML_Core.ipynb
週日專案總結： 撰寫 Notebook 的 結論和分析（強調 Recall 對臨床的重要性）。[專案] 最終提交高質量的 Notebook

🌟 第 4 週：準備進入下一階段
週一 A1/A2 總結： 回顧您在糖尿病專案中用到的所有 Pandas 和 Scikit-learn 函式
週二 A3 總結： 總結所有 BCI 概念，準備進入第二階段
週三 Git 整理： 整理 GitHub 儲存庫，確保所有筆記和專案代碼結構清晰
週四預習 B1： 搜索並安裝 MNE-Python。瀏覽官方文檔的入門教程
週五預習 B2： 搜索訊號處理概念：什麼是 FFT？什麼是濾波？
週六/日 Check Point 檢驗： 確保您已完成所有 Check Point (P1-P4)。享受成果，準備迎接第二階段的 BCI 訊號挑戰！

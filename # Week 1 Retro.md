# Week 1 Retro

**完成時間：** 2025-08-13

1. **收穫**  
   - 掌握了 JupyterLab 環境架設與快速起手。  
   - 熟練了 pandas 基本 EDA（`info()`, `describe()`, `.head()`, `.fillna()`）。  
   - 能用 seaborn 畫出直方圖、箱型圖、長條圖、Violin plot。  
   - 成功把 1 MB 資料集做完整探索並產出可分享的 HTML 報告。

2. **挑戰與痛點**  
   - 遇到字型設定與中文顯示問題，花了些時間調整 `rcParams`。  
   - chained-assignment 警告與欄位刪除順序導致 KeyError，學到一定要注意 DataFrame 變更順序。  
   - Notebook 輸出截斷、parquet engine 缺少等環境陷阱。

3. **下一步優化 Sprint**  
   1. **大檔案處理**：導入 `dask`/`polars`，跑 1 GB+ 資料。  
   2. **模組化**：把重複的清洗與視覺化程式抽成 `utils/`。  
   3. **自動化報告**：CI + nbconvert，自動生成最新版 HTML。  
   4. **特徵工程深化**：處理 `Cabin`、分箱策略優化、加入外部變數。

> _這週我完成了從環境架設到完整報告的全流程，收穫滿滿，也發現了不少環境與程式細節要注意。

   下一步會把流程固化與優化，為後續本地 AI 助手的資料管線打基礎。_
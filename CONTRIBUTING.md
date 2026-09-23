# 協作方式

## 任務與分支

- 每個任務開一個 Issue，註明負責人、目標與完成條件。
- 從最新的 `main` 建立分支，例如 `feat/data-cleaning`、`docs/proposal` 或 `fix/data-split`。
- Commit 清楚描述變更，例如 `docs: add dataset description`。
- 開 Pull Request，說明變更與驗證結果，請至少一位隊友 review 後再合併。
- 上述 review 是團隊約定；是否有平台強制保護，需以 GitHub 設定為準。

## 實驗紀錄

- 記錄資料版本、切分方法、random seed、套件版本與評估指標。
- 先切分訓練與測試資料；前處理僅以訓練資料 fit，避免資料洩漏。
- 測試集留給最終評估，模型選擇使用驗證集或交叉驗證。
- Notebook 提交前清除敏感輸出與過大的結果。
- 大型資料與模型檔放在團隊約定的外部位置，在文件中寫明取得方式。

# チームゾーン銀行口座解約分類タスク

## 📁 ディレクトリ構造

あなたのリポジトリ名/
├── data/                  # データ管理（※GitHub管理外）
│   ├── raw/               # 生のデータ
│   └── processed/         # 前処理済みのデータ
├── notebooks/             # Jupyter Notebook
│   ├── 1_eda/             # 1. データ分析
│   ├── 2_preprocessing/   # 2. 前処理
│   ├── 3_modeling/        # 3. モデル作成
│   └── 4_evaluation/      # 4. 評価
├── model/                 # 学習済みモデル（.pkl）の保存先
├── src/                   # 共通スクリプト・関数
└── submission/            # 提出用CSVの出力先
これまでのPractice Test（#1〜#4）に登場した重要な英単語を、意味や役割の類似性に基づいたグループごとにまとめました。英語での試験対策としてご活用ください。

### 1. AI・データサイエンスの基本 (AI/ML Fundamentals)
技術的な手法やモデルの構築に関する用語です。

*   **Supervised learning**: 教師あり学習（入力と正解ラベルのペアで学習）。
*   **Unsupervised learning**: 教師なし学習（正解なしでデータのパターンを特定）。
*   **Semi-supervised learning**: 半教師あり学習（少量のラベル付きデータと大量のラベルなしデータを併用）。
*   **Self-supervised learning**: 自己教師あり学習（ラベルなしデータから自律的にラベルを作成。基盤モデルの学習に使用される）。
*   **Reinforcement learning (RL)**: 強化学習（エージェントが環境と対話し、報酬を最大化するように学習）。
*   **Deep learning (DL)**: 深層学習（多層のニューラルネットワークを使用）。
*   **Transfer learning**: 転移学習（あるタスクで学習した知識を別の関連タスクに適用）。
*   **Fine-tuning**: 微調整（事前学習済みモデルを特定のデータで追加訓練し、重みを書き換える）。

### 2. データの準備と特徴量 (Data & Feature Engineering)
モデルに入力するデータの加工や管理に関する用語です。

*   **Feature Engineering**: 特徴量エンジニアリング（生のデータからモデルに役立つ変数を選択・作成する）。
*   **Feature Extraction**: 特徴量抽出（データを新しい空間に変換し、次元を削減する）。
*   **Feature Selection**: 特徴量選択（既存のデータから重要な変数を選び出す）。
*   **Preprocessing**: 前処理（学習の前にデータをクリーニング・加工する）。
*   **Tokenization**: トークン化（テキストを最小単位のトークンに分割する）。
*   **Vectorization / Embedding**: ベクトル化 / 埋め込み（データや単語を数値のリストに変換する）。
*   **Data Lineage**: データリネージ（データの起源や加工の履歴。コンプライアンスに重要）。
*   **Synthetic data**: 疑似データ / 合成データ（実データの統計的性質を模倣して人工的に作られたデータ）。

### 3. モデルの性能と評価指標 (Performance & Metrics)
AIがどれだけ正確かを測るための「物差し」です。

*   **Inference**: 推論（学習済みモデルに新しいデータを入れて予測を出す本番プロセス）。
*   **Accuracy**: 正解率（全体の予測のうち正解した割合）。
*   **Precision**: 適合率（「正」と予測したもののうち、実際に正解だった割合）。
*   **Recall**: 再現率（正解データのうち、どれだけ漏らさず見つけられたかの割合）。
*   **F1-Score**: F1スコア（適合率と再現率のバランスを示す指標）。
*   **Confusion Matrix**: 混同行列（分類モデルの正誤の内訳を表す表）。
*   **Bias**: バイアス（予測の偏り。高いと **Underfitting** / 学習不足を招く）。
*   **Variance**: バリアンス / 分散（ノイズへの過敏さ。高いと **Overfitting** / 過学習を招く）。

### 4. 生成AI特有の概念 (Generative AI Concepts)
LLMなどの最新技術に関連する専門用語です。

*   **Foundation Model (FM)**: 基盤モデル（広範なデータで事前学習された汎用的なモデル）。
*   **Large Language Model (LLM)**: 大規模言語モデル（言語処理に特化した巨大な基盤モデル）。
*   **Hallucination**: ハルシネーション / 幻覚（もっともらしい嘘を生成する現象）。
*   **Retrieval-Augmented Generation (RAG)**: 検索拡張生成（外部知識ベースを参照して回答を補強する手法。モデルの重みは変えない）。
*   **Context window**: コンテキストウィンドウ（モデルが一度に処理できる情報の最大量。トークンで測定される）。
*   **Temperature**: 温度（回答の「創造性」や「ランダムさ」を制御するパラメータ）。
*   **Zero-shot / Few-shot**: ゼロショット（例題なし） / フューショット（数個の例題あり）のプロンプト手法。

### 5. セキュリティと責任あるAI (Security & Responsible AI)
安全な運用のためのリスク管理用語です。

*   **Personally Identifiable Information (PII)**: 個人情報（名前、住所など特定可能な情報）。
*   **Toxicity**: 有害性（攻撃的、不適切なコンテンツの生成）。
*   **Prompt Injection**: プロンプトインジェクション（入力に悪意のある命令を混ぜてAIを操る攻撃）。
*   **Jailbreaking**: ジェイルブレイキング / 脱獄（AIの安全制限を回避して禁止された情報を言わせる行為）。
*   **Poisoning**: ポイズニング / 汚染（学習データに悪意あるデータを混ぜてモデルを壊す攻撃）。
*   **Interpretability / Explainability**: 解釈性（内部構造のわかりやすさ） / 説明可能性（予測理由の提示能力）。
*   **Mitigation**: 緩和 / 軽減（リスクやバイアスを減らすこと）。

### 6. ビジネス・プロセス (Business & Process Terms)
AWSの利点や管理に関連する用語です。

*   **Agility**: 俊敏性（迅速な開発・展開能力）。
*   **Elasticity**: 弾力性（リソースを需要に合わせて即座に増減できる性質）。
*   **Economies of scale**: 規模の経済（多くの利用者がいることでコストが下がること）。
*   **Governance**: ガバナンス / 統治（組織がAIを正しく管理・運用するための枠組み）。
*   **Audit / Auditing**: 監査（規定遵守状況のチェック）。
*   **Compliance**: コンプライアンス / 遵守（法律や基準に従うこと）。
*   **Trade capital expense for variable expense**: 設備投資（固定費）を変動費に変える。
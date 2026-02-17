### **重要キーワードの英語対比**
試験問題でよく狙われる対比構造です。

*   **Training (学習)** ＝ **Trainium** / **Inference (推論)** ＝ **Inferentia** <br>
*   **Deterministic (決定的)**: Always same output for same input / **Probabilistic (確率的)**: Range of possible outcomes <br>
*   **Overfitting (過学習)**: High performance on training, poor on unseen data (**High Variance**) <br>
*   **Underfitting (学習不足)**: Poor performance on both training and test data (**High Bias**) <br>
*   **Precision**: Accuracy of positive predictions / **Recall**: Ability to identify all positive instances <br>
*   **Accuracy**: Overall percentage of correct predictions <br>

試験勉強の追い込みにお役立てください！
### **1. 生成AI・大規模言語モデル（LLM）関連**
生成AIを「作る」「使う」「守る」ための中心的なサービスです。

*   **Amazon Bedrock** <br> 複数の基盤モデル（Claude, Llama, Titanなど）をAPIで利用できるプラットフォーム。
    *   **Knowledge Bases for Bedrock**: 社内データを読み込ませてRAG（検索拡張生成）を実現する機能。
    *   **Guardrails for Bedrock**: 有害なコンテンツをブロックしたり、個人情報（PII）を隠したりする安全柵。
    *   **Model Evaluation on Bedrock**: 複数のモデルを比較・評価して、最適なものを選ぶ機能。
    *   **Agents for Bedrock**: AIが自分で考えて、社内システムの実行などのタスクを完了させる仕組み。
*   **Amazon Q シリーズ** <br> ビジネスや開発を助けるAIアシスタント。
    *   **Amazon Q Business**: 社内資料に基づいて回答や要約を行う「AI社員」。
    *   **Amazon Q Developer**: コード生成やデバッグ、AWS構成の質問に答える「エンジニアの相棒」。
    *   **Amazon Q in QuickSight**: 言葉で指示するだけでグラフやダッシュボードを作成する。
    *   **Amazon Q in Connect**: コールセンターでオペレーターにリアルタイムで回答案を出す。

---

### **2. Amazon SageMaker エコシステム**
機械学習（ML）の全工程を管理する巨大な道具箱です。

*   **SageMaker Canvas**: コードを書かずに（ノーコード）クリック操作だけでMLモデルを作れる。
*   **SageMaker Data Wrangler**: データの掃除、加工、分割（学習/テスト用）をGUIで行う。300以上の変換機能がある。
*   **SageMaker Ground Truth / Plus**: 人間がデータに正解ラベルを貼る作業を支援する。
*   **SageMaker Clarify**: AIの「なぜ？」を説明（説明可能性）し、データの偏り（バイアス）を検出する。
*   **SageMaker Feature Store**: 作成した「特徴量（入力データ）」を保存・共有・再利用するための倉庫。
*   **SageMaker Model Cards**: モデルの用途、リスク、仕様を記録した「公式説明書」。
*   **SageMaker Model Dashboard**: 全てのモデルの稼働状況や監視結果をまとめた「管理パネル」。
*   **SageMaker Model Monitor**: 本番稼働中のモデルの精度低下や異常を監視する。
*   **SageMaker JumpStart**: 学習済みモデルや解決策が並んでいる「モデルのデパート」。
*   **SageMaker Studio**: 全てのリソースにアクセスできる統合開発環境（IDE）。

---

### **3. すぐに使えるAIサービス（機能別）**
特定の目的のためにAWSが用意した、学習済みのAIサービスです。

*   **文章・言語関連**
    *   **Amazon Comprehend / Medical**: 文章の感情分析やキーワード抽出、個人情報（PII）の特定を行う。
    *   **Amazon Textract**: 書類やレシートから「文字」や「表」を抜き出す。
    *   **Amazon Translate**: 高精度な多言語翻訳。
    *   **Amazon Kendra**: AIを使った企業内ドキュメント検索エンジン。
*   **音声・動画関連**
    *   **Amazon Rekognition**: 画像・動画内の物体、顔、ナンバープレート、不適切コンテンツを検出する。
    *   **Amazon Transcribe / Medical**: 音声をテキストに書き起こす。
    *   **Amazon Polly**: テキストを自然な声で読み上げる（文章から音声へ）。
*   **予測・最適化関連**
    *   **Amazon Personalize**: 「あなたへのおすすめ」を作成する（レコメンデーション）。
    *   **Amazon Forecast**: 過去のデータから未来の売上や需要を予測する。
    *   **Amazon Lex**: チャットボット（対話型AI）を作る。
*   **学習用デバイス**
    *   **AWS DeepRacer**: 強化学習（RL）を学ぶための自動運転レーシングカー。

---

### **4. インフラ・セキュリティ・ガバナンス**
AI/MLを安全・効率的に動かすための土台です。

*   **ハードウェア（チップ）**
    *   **AWS Trainium**: モデルの「学習（Training）」に特化した省エネ・高速チップ。
    *   **AWS Inferentia**: モデルの「推論（Inference）」に特化した低コスト・低遅延チップ。
*   **セキュリティ・監査**
    *   **AWS IAM / IAM Identity Center**: ユーザーのアクセス権限管理（誰が触れるか）。
    *   **AWS Artifact**: AWSやISV（他社）の監査報告書（ISOなど）を入手する場所。
    *   **AWS Config**: リソースの設定変更を記録・監視する。
    *   **AWS Audit Manager**: コンプライアンスの証拠収集を自動化する。
    *   **Amazon Inspector**: アプリの脆弱性を自動で診断する。
    *   **AWS Trusted Advisor**: コストやセキュリティのベストプラクティスを助言してくれる。
*   **人間によるレビュー**
    *   **Amazon A2I (Augmented AI)**: AIが自信がない時に、人間に判定をバトンタッチする仕組み。
*   **通信・その他**
    *   **VPC Endpoint**: インターネットを通らずにS3などのサービスと安全に通信する「私道」。
    *   **Amazon Connect**: クラウド型のコールセンターを構築するサービス。

---

### **暗記のコツ**
1.  **「データの掃除」** ＝ Data Wrangler <br>
2.  **「説明・公平性」** ＝ Clarify <br>
3.  **「情報の倉庫」** ＝ Feature Store <br>
4.  **「APIで最新AI」** ＝ Bedrock <br>
5.  **「社内資料の先生」** ＝ Q Business / Kendra <br>
6.  **「学習用チップ」** ＝ Trainium / **「推論用チップ」** ＝ Inferentia <br>

試験直前にこのリストを見返して、「このサービスは何をするものか」を一行で言えるようにしておけば安心です！
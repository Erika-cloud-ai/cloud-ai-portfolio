# AWS Certified AI Practitioner (AIF-C01) Service & Concept List

### 1. Generative AI & Foundation Models (生成AIと基盤モデル)
| Service / Concept | Description (English) | 説明（日本語） |
| :--- | :--- | :--- |
| **Amazon Bedrock** | A fully managed service that makes foundation models (FMs) from Amazon and leading AI startups available through an API. | Amazonや主要AI企業の基盤モデルをAPI経由で利用できるフルマネージドサービス。 |
| **Knowledge Bases for Amazon Bedrock** | A solution that supports an end-to-end Retrieval Augmented Generation (RAG) workflow to deliver relevant and customized responses. | RAG（検索拡張生成）ワークフローをエンドツーエンドでサポートし、特定のデータに基づいた回答を生成する機能。 |
| **Guardrails for Amazon Bedrock** | Helps implement safeguards by filtering undesirable and harmful content and redacting PII. | 不適切なコンテンツのフィルタリングや個人情報（PII）の隠蔽など、安全対策を実装する機能。 |
| **Amazon SageMaker JumpStart** | A machine learning hub with foundation models, built-in algorithms, and prebuilt ML solutions. | 基盤モデル、組み込みアルゴリズム、構築済みソリューションが揃ったMLハブ。 |

### 2. Machine Learning Tools (機械学習ツール)
| Service / Concept | Description (English) | 説明（日本語） |
| :--- | :--- | :--- |
| **Amazon SageMaker Canvas** | A no-code service with an intuitive, point-and-click interface to generate predictions without writing code. | コードを書かずにクリック操作だけで機械学習の予測モデルを作成できるノーコードサービス。 |
| **Amazon SageMaker Data Wrangler** | Offers 300+ pre-configured data transformations to prepare data for ML. | 機械学習用のデータ準備のために、300以上の前処理・変換機能を提供するツール。 |
| **Amazon SageMaker Ground Truth** | Harnesses human feedback to improve the accuracy and relevancy of models through data labeling. | 人間の力（ラベリング）を借りて、モデルの精度と関連性を向上させるサービス。 |

### 3. Specialized AI Services & Hardware (特化型サービスとハードウェア)
| Service / Concept | Description (English) | 説明（日本語） |
| :--- | :--- | :--- |
| **Amazon Q (Business)** | A generative AI-powered assistant for accelerating software development and leveraging internal data via LLM and RAG. | ソフトウェア開発や社内データの活用を加速させる、LLMとRAGを用いた生成AIアシスタント。 |
| **AWS Trainium** | An ML chip purpose-built for high-performance deep learning training of 100B+ parameter models. | 1,000億以上のパラメータを持つ大規模モデルの学習用に設計された専用チップ。 |
| **AWS Inferentia** | An ML chip purpose-built to deliver high-performance inference at a low cost. | 低コストで高性能な推論（モデルの実行）を行うために設計された専用チップ。 |

### 4. Responsible AI & Governance (責任あるAIとガバナンス)
| Service / Concept | Description (English) | 説明（日本語） |
| :--- | :--- | :--- |
| **Amazon SageMaker Clarify** | Helps detect biases and explain predictions to enhance transparency and fairness. | バイアスの検出や予測の理由を説明し、AIの透明性と公平性を高めるツール。 |
| **Amazon SageMaker Model Monitor** | Continuously monitors ML models in production to detect data quality issues and concept drift. | 本番環境のモデルを監視し、データの品質低下や精度の劣化を自動検出するサービス。 |
| **Shared Responsibility Model** | AWS is responsible for security **"of"** the cloud, while the customer is responsible for security **"in"** the cloud. | AWSは「クラウド自体の安全」に責任を持ち、ユーザーは「クラウド内の安全」に責任を持つという枠組み。 |

### 5. Key ML Concepts (重要な機械学習コンセプト)
| Term (English) | Definition | 定義（日本語訳） |
| :--- | :--- | :--- |
| **Inference** | The process where a trained model uses learned patterns to provide a prediction based on new data. | 学習済みモデルが新しいデータに対して予測や回答を行うプロセス（推論）。 |
| **Overfitting** | When a model performs well on training data but poorly on new, unseen data. | 訓練データに過剰に適応し、新しいデータで正しく予測できない状態（過学習）。 |
| **Self-supervised learning** | A technique where models generate labels from unlabeled data themselves, used by Foundation Models. | ラベルのないデータからAIが自ら学習する手法。基盤モデルの学習に用いられる。 |
| **Temperature** | An inference parameter that regulates the creativity or randomness of the model's responses. | AIの回答の「創造性」や「ランダムさ」を調整するパラメータ。 |

---

### GitHubポートフォリオへのアドバイス
このリストをREADME.mdや学習ログ（Notes）としてGitHubにアップロードする際は、以下の工夫を加えることで「GitHubを使えること」をさらにアピールできます。

1.  **Table of Contents (目次) の作成:** ソースにも見られるように、READMEの冒頭にアンカーリンク付きの目次を設置してください。
2.  **Mermaid記法による図解:** 例えば「機械学習プロセス（Data Collection → Preprocessing → Training → Evaluation）」 を、Markdown内でMermaidのフローチャートを使って図解すると、ドキュメント作成能力が高く評価されます。
3.  **リンクの活用:** 各サービス名にAWS公式ドキュメントへのリンクを貼ることで、リサーチ能力をアピールできます。

模擬試験45%からのスコアアップに向けて、この用語集を復習に役立ててください。応援しています！


Memo
**FMs（Foundation Models / 基盤モデル）**は、現代の生成AIの基盤となる非常に強力なAIモデルのことです。模擬試験のソースに基づき、その特徴を分かりやすく説明します。

### 1. FMsの核心：大量のデータから自分で学ぶ
FMsの最大の特徴は、その**学習方法**にあります。

*   **自己教師あり学習 (Self-supervised learning):** 人間が一つ一つ「これは猫」「これは犬」とラベルを貼ったデータ（教師あり学習）ではなく、**ラベルのない膨大な生のデータ**を使って学習します。
*   **自ら答えを作る:** モデルは未加工のデータから自分自身でラベルを生成し、パターンや関係性を学習します。これにより、事前の教育がなくても「最初から非常に賢い」状態になります。

### 2. LLM（大規模言語モデル）との関係
よく耳にする**LLM**は、FMsという大きなカテゴリーの中の一つです。
*   **FMs:** 画像、音声、テキストなど様々なデータを扱える広義のモデル。
*   **LLM:** その中でも、特にテキストの要約、生成、分類などの**言語タスクに特化したFMs**を指します。

### 3. AWSでのFMsの活用方法
AWSでは、FMsを直接「育てる（学習させる）」のは大変なため、既存の強力なFMsを簡単に利用できるサービスが提供されています。

*   **Amazon Bedrock:** Amazonや主要なAIスタートアップのFMsを、インフラ管理なしにAPI経由ですぐに利用できるフルマネージドサービスです。
*   **Amazon SageMaker JumpStart:** FMsや組み込みアルゴリズムが集まったハブであり、数クリックでモデルのデプロイやカスタマイズが可能です。

### 4. 覚えておくべきキーワード（試験対策）
模擬試験で重要となるFMsのポイントは以下の通りです。

*   **汎用性:** 最小限のカスタマイズやファインチューニングで、多様なタスクに適用できます。
*   **マルチモーダル (Multimodal):** テキスト、画像、音声、ビデオといった複数の種類の入出力を同時に処理できる能力を指します。
*   **コストの法則:** 一般的に、**小さいモデルの方が大きいモデルよりも安価**で使用できます。

***

**覚え方のイメージ：**
FMsは、膨大な図書室の本をすべて読み終えて、**「何でも知っている状態で卒業した超天才の学生」**のようなものです。私たちはその天才に対して、特定の仕事（法律相談や広告作成など）の追加資料（RAGなど）を渡すだけで、すぐに高度な成果を出してもらうことができます。

はい、可能です。ソースに基づき、AWS Certified AI Practitioner (AIF-C01) 試験に登場する主要なサービスとコンセプトを、英語と日本語訳の対照表形式でまとめました。

これらの内容は、GitHubのポートフォリオにそのまま活用いただける構成にしています。

---
提供されたソースに基づき、AWS 認定 AI プラクティショナー（AIF-C01）模擬試験第1回の主要な問題と回答、および暗記のための解説を日本語と英語でまとめます。

---

# AWS Certified AI Practitioner - Practice Test #1 対策まとめ

## 1. 感情分析に最適なサービス (Sentiment Analysis)
**問題:** Eコマース企業が数千のカスタマーレビューを分析し、ポジティブ・ネガティブなどの感情を判別したい。

*   **英語 (English):** **Amazon Comprehend** and **Amazon Bedrock**
*   **日本語 (Japanese):** **Amazon Comprehend** および **Amazon Bedrock**
*   **暗記のポイント (Memorization):**
    *   **Amazon Comprehend:** テキストから洞察（感情、エンティティ、キーフレーズ）を見つける**自然言語処理 (NLP) 特化型**サービスです。
    *   **Amazon Bedrock:** 基盤モデル (FM) を使用して、高度にカスタマイズ可能な感情分析が可能です。
    *   **注意:** Amazon Rekognitionは「画像/ビデオ」、Amazon Textractは「文字起こし (OCR)」用であり、感情分析（NLP）用ではありません。
NLPの正式名称は Natural Language Processing です。日本語では一般的に「自然言語処理」と訳されます。
ソースに基づいたNLPに関する主な情報は以下の通りです：
• 定義と機能: NLPは、機械学習を使用してテキスト内の洞察や関係性を明らかにする技術です。これには、感情分析、エンティティ認識、キーフレーズ抽出、言語検出などのタスクが含まれます。
• 代表的なサービス: ソースでは、Amazon Comprehend が代表的なNLPサービスとして紹介されています。また、インテリジェント検索サービスである Amazon Kendra もNLPアルゴリズムを利用して回答を導き出します。
• 生成AI・大規模言語モデル（LLM）との関係: 基盤モデルやLLM（大規模言語モデル）は、NLPタスク（要約、テキスト生成、分類、対話など）を処理するために設計された高度な深層学習モデルの一種です。Amazon Bedrock を通じてこれらのモデルを利用し、NLPタスクを実行することが可能です。
• 具体的な用途:
    ◦ 顧客レビューの感情（ポジティブ、ネガティブなど）の判定。
    ◦ ドキュメントからの重要なフレーズや場所、人名、ブランドなどの抽出。
    ◦ テキスト生成や言語翻訳
---

## 2. データの不均衡とバイアスの緩和 (Data Imbalance & Bias)
**問題:** 画像生成モデルが特定の層に対して偏った出力をする場合、トレーニングデータの不均衡をどう修正すべきか？

*   **英語 (English):** **Augment the data** by generating new instances for underrepresented groups.
*   **日本語 (Japanese):** 過小評価されているグループの新しいデータを作成して**データを拡張（オーグメンテーション）する**。
*   **暗記のポイント (Memorization):**
    *   **データオーグメンテーション:** 不足しているグループの例を増やすことで、モデルが多様なパターンを学び、バイアスを減らすことができます。
    *   アルゴリズム（モデル）を変えるだけでは、元のデータの偏りは解決できません。

---

## 3. 基盤モデル (FM) の学習プロセス
**問題:** 基盤モデルの事前学習と微調整 (Fine-tuning) の学習形式は？

*   **英語 (English):** FMs use **self-supervised learning** for pre-training, but fine-tuning is a **supervised learning** process.
*   **日本語 (Japanese):** FMは事前学習に**自己教師あり学習**を使用するが、微調整は**教師あり学習**プロセスである。
*   **暗記のポイント (Memorization):**
    *   **自己教師あり (Self-supervised):** ラベルなしデータから自ら構造を学ぶ（事前学習）。
    *   **教師あり (Supervised):** ラベル付きデータ（正解）を与えて特定のタスク用に調整する（微調整）。

---

## 4. 責任あるAI：用語の定義 (Responsible AI)
**問題:** 生成AIに関連するリスクや現象の名称は？

*   **盗作 (Plagiarism):** AIツールを使って、自分が作成したものではないコンテンツを提出すること。
*   **ハルシネーション (Hallucination):** モデルが、もっともらしく見えるが事実に反する、または捏造された情報を生成すること。
*   **暗記のポイント (Memorization):**
    *   **ハルシネーション**は「もっともらしい嘘」と覚えましょう。AIは知識を確認しているのではなく、パターンの確率で次の言葉を選んでいるために起こります。

---

## 5. RAGとベクトルデータベース (RAG & Vector DB)
**問題:** 検索拡張生成 (RAG) において、高速な検索と類似性スコアリングに最適なデータベースは？

*   **英語 (English):** **Amazon OpenSearch Service**
*   **日本語 (Japanese):** **Amazon OpenSearch Service**
*   **暗記のポイント (Memorization):**
    *   **RAG:** 外部の知識源（PDFやドキュメント）を検索して、回答の精度を高める手法。
    *   **OpenSearch:** 全文検索、ベクトル検索、類似性スコアリングに特化しており、Amazon Bedrockのナレッジベースでもデフォルトで作成されます。

---

## 6. プロンプトエンジニアリングのテクニック
**問題:** 特定の要素を**含めない**ように指示する手法は？

*   **英語 (English):** **Negative prompting**
*   **日本語 (Japanese):** **ネガティブプロンプティング**
*   **暗記のポイント (Memorization):**
    *   **Negative prompting:** 「競合他社の名前を出さない」「特定のトピックを除外する」など、AIに避けてほしい内容を伝えます。
    *   **Few-shot:** いくつか「例」を与える。
    *   **Zero-shot:** 例を全く与えない。
    *   **Chain-of-thought:** 思考の過程をステップバイステップで説明させる。

---

## 7. 評価指標 (Metrics)
**問題:** 機械翻訳の精度を評価するのに最適な指標は？

*   **英語 (English):** **BLEU score** (Bilingual Evaluation Understudy)
*   **日本語 (Japanese):** **BLEU スコア**
*   **暗記のポイント (Memorization):**
    *   **BLEU:** **翻訳 (Translation)** の精度評価。人間が作成した参照翻訳との一致度を 0〜1 で測ります。
    *   **ROUGE:** **要約 (Summarization)** の評価に使われます。

---

## 8. AWS インフラの基本 (Global Infrastructure)
**問題:** リージョンとアベイラビリティゾーン (AZ) の関係は？

*   **英語 (English):** Each AWS Region consists of a minimum of **three** Availability Zones.
*   **日本語 (Japanese):** 各AWSリージョンは、最低**3つ**のアベイラビリティゾーンで構成される。
*   **暗記のポイント (Memorization):**
    *   1つのAZは、1つ以上の独立したデータセンターで構成されます。
    *   耐障害性を高めるため、最低3つの独立したAZが各リージョンに配置されています。

---

## 暗記用早見表 (Memorization Helper)

| サービス名 / 用語 | 主な役割・キーワード | 関連ソース |
| :--- | :--- | :--- |
| **Amazon Kendra** | エンタープライズ検索（社内資料やFAQから回答を探す） | |
| **Amazon Polly** | テキストを「音声」に変換 | |
| **Amazon Transcribe** | 「音声」をテキストに変換（文字起こし） | |
| **Amazon Lex** | 対話型インターフェース（チャットボット）の構築 | |
| **Amazon SageMaker Clarify** | 機械学習モデルのバイアス検出と説明可能性 | |
| **Amazon SageMaker JumpStart** | 事前トレーニング済みモデル（基盤モデル含む）のハブ | |
| **Temperature** | 生成される回答の「創造性・ランダム性」を制御（高いと創造的） | |
| **Top P / Top K** | 次に生成される単語の「候補の絞り込み」を制御 | |
| **Confusion Matrix** | 分類モデルの精度評価ツール（真陽性・偽陰性などを表示） | |

この内容はソース資料 から までの情報を基に構成されています。試験対策にお役立てください。
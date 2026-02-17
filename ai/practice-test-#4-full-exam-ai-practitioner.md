| １st Time    | 2nd time    |  3rd Time   | 4th Time |
|:---------------|:-----------|:----------|:----------|
| 40% | 69%    | 83% | %   |
<br>
---

### **AWS Certified AI Practitioner - Practice Test #4**

**問題1：データライネッジ（Data Lineage）の重要性** <br>
**English Question (Original)** <br>
Which of the following would you identify as the key reason to maintain data lineage? <br>
**日本語訳** <br>
データライネッジ（データの系譜）を維持する主な理由として、適切なものはどれですか？ <br>
**選択肢** <br>
• It reduces the storage costs... <br>
• It enhances the visualization capabilities... <br>
• ✅ **It ensures data privacy and compliance by tracking the flow and transformation of data** <br>データの流れと変換を追跡することで、データのプライバシーとコンプライアンスを確保します。 <br>
• It improves the performance of machine learning models... <br>
**🐒 猿でもわかる解説** <br>
データライネッジとは、データがどこから来て、どう加工されたかの「履歴（家系図）」のことです。これがあるおかげで、個人情報の扱いが正しいかチェックでき、法律（コンプライアンス）を守れます。 <br>
**🧠 暗記方法** <br>
👉 「データライネッジ ＝ データの履歴書 ＝ コンプライアンスのため」 <br>

---

**問題2：特徴量の寄与を特定するサービス** <br>
**English Question (Original)** <br>
Which Amazon SageMaker service will help the company understand how an input feature contributes to the predictions of a machine learning model? <br>
**日本語訳** <br>
入力されたデータ（年齢や血圧など）のどれが予測結果にどう影響したか（透明性）を理解するのに役立つサービスは？ <br>
**選択肢** <br>
• Amazon SageMaker Ground Truth <br>
• Amazon SageMaker JumpStart <br>
• ✅ **Amazon SageMaker Clarify** <br>
• Amazon SageMaker Canvas <br>
**🐒 猿でもわかる解説** <br>
SageMaker Clarifyは、AIが「なぜその答えを出したのか」をはっきり（Clarify）させてくれます。特定のデータが予測をどれくらい左右したか教えてくれます。 <br>
**🧠 暗記方法** <br>
👉 「理由をはっきり（Clarify）させる」 <br>

---

**問題3：AWS DeepRacer のアルゴリズム** <br>
**English Question (Original)** <br>
Which type of Machine Learning algorithm is used by the models that are trained, evaluated, and tuned on AWS DeepRacer? <br>
**日本語訳** <br>
AWS DeepRacerでトレーニングされるモデルには、どのタイプの機械学習アルゴリズムが使われていますか？ <br>
**選択肢** <br>
• Deep Learning <br>
• Unsupervised Learning <br>
• ✅ **Reinforcement Learning** <br>
• Semi-supervised Learning <br>
**🐒 猿でもわかる解説** <br>
DeepRacerは自動運転車です。コースをうまく走れたら「報酬（アメ）」をもらって学習する「強化学習（Reinforcement Learning）」を使っています。 <br>
**🧠 暗記方法** <br>
👉 「DeepRacer ＝ 強化学習（RL）」 <br>

---

**問題4：分類モデルの正解率指標（Accuracy）** <br>
**English Question (Original)** <br>
Which metric would be most appropriate for knowing the overall percentage of correct predictions, including both approved and denied applications? <br>
**日本語訳** <br>
承認・拒否の両方を含め、予測全体のうち正解した割合（正解率）を測るのに最も適切な指標は？ <br>
• R-squared <br>
• ✅ **The company should use Accuracy, which measures the proportion of correctly predicted instances (both true positives and true negatives) out of the total number of instances** <br>企業は、インスタンスの総数のうち、正しく予測されたインスタンス（真陽性と真陰性の両方）の割合を測定する精度を使用する必要があります。 <br>
• F1 Score <br>
• Root Mean Squared Error (RMSE) <br>
**🐒 猿でもわかる解説** <br>
「何問中、何問正解したか」という単純な正解率のことを「Accuracy」と言います。データが偏っていない時に最も分かりやすい指標です。 <br>
**🧠 暗記方法** <br>
👉 「全体の正解率 ＝ Accuracy」 <br>

---

**問題5：低遅延な個別予測エンドポイント** <br>
**English Question (Original)** <br>
The team needs a solution that offers persistent endpoints to handle individual prediction requests with low-latency. What do you recommend? <br>
**日本語訳** <br>
個別の予測リクエストを低遅延（即座）で処理できる、常時稼働の「エンドポイント」が必要な場合、何を推奨しますか？ <br>
**選択肢** <br>
• ✅ **Real-time hosting services** <br>
• Serverless Inference <br>
• Batch transform <br>
• Asynchronous Inference <br>
**🐒 猿でもわかる解説** <br>
病院の受付など、リクエストに対して「今すぐ」答えが必要な場合は、常時起動している「リアルタイムホスティング（エンドポイント）」を使います。 <br>
**🧠 暗記方法** <br>
👉 「今すぐ答えが欲しい ＝ リアルタイム」 <br>

---

**問題6：データの分割（Data Splits）** <br>
**English Question (Original)** <br>
Which of the following is the best fit to create train, test, and validation splits on your data for machine learning? <br>
**日本語訳** <br>
機械学習データを「学習用」「テスト用」「検証用」に分割するのに最適なサービスはどれですか？ <br>
**選択肢** <br>
• Amazon SageMaker Clarify <br>
• Amazon SageMaker Ground Truth <br>
• ✅ **Amazon SageMaker Data Wrangler** <br>
• Amazon SageMaker Feature Store <br>
**🐒 猿でもわかる解説** <br>
Data Wranglerはデータの掃除屋さんです。GUI操作でポチポチするだけで、データを学習用やテスト用に分ける（Split）作業も簡単にできます。 <br>
**🧠 暗記方法** <br>
👉 「データの加工・分割 ＝ Data Wrangler」 <br>

---

**問題7：画像生成のためのモデル** <br>
**English Question (Original)** <br>
Which Foundation Models would you recommend for generating images from text prompts in Amazon Bedrock? <br>
**日本語訳** <br>
Amazon Bedrockでテキスト指示から画像を生成するために推奨されるモデルはどれですか？ <br>
**選択肢** <br>
• ✅ **Stable Diffusion** <br>
• Claude <br>
• Jurassic <br>
• Llama <br>
**🐒 猿でもわかる解説** <br>
ClaudeやLlamaは「言葉（テキスト）」のプロです。画像を作るなら「Stable Diffusion」一択です。 <br>
**🧠 暗記方法** <br>
👉 「Bedrockで画像生成 ＝ Stable Diffusion」 <br>

---

**問題8：自然言語でBIダッシュボード作成** <br>
**English Question (Original)** <br>
Which solution allows business analysts to use natural language to build BI dashboards? <br>
**日本語訳** <br>
ビジネスアナリストが日常の言葉（自然言語）を使ってBIダッシュボードを作成できるソリューションは？ <br>
**選択肢** <br>
• Amazon Q Business <br>
• Amazon Q Developer <br>
• Amazon Q in Connect <br>
• ✅ **Amazon Q in QuickSight** <br>
**🐒 猿でもわかる解説** <br>
QuickSightはグラフを作るツールです。その中にAIが組み込まれた「Amazon Q in QuickSight」なら、言葉で指示するだけでグラフが作れます。 <br>
**🧠 暗記方法** <br>
👉 「グラフ作成（BI）のAI ＝ Q in QuickSight」 <br>

---

**問題9：AWSサービスの用途マッチング** <br>
**English Question (Original)** <br>
Match the services: <br>

A) Amazon Textract

B) Amazon Forecast

C) Amazon Kendra

1) Easy-to-use enterprise search service that’s powered by machine learning <br>
機械学習を活用した使いやすいエンタープライズ検索サービス <br>

2) Automatically extract printed text, handwriting, layout elements, and data from any document <br>あらゆるドキュメントから、印刷されたテキスト、手書き、レイアウト要素、データを自動的に抽出 <br>

3) Forecast business outcomes easily and accurately using machine learning <br>機械学習を活用して、ビジネス成果を簡単かつ正確に予測 <br>

**日本語訳** <br>
サービスの組み合わせを選んでください：A)Textract, B)Forecast, C)Kendra。 <br>
**選択肢** <br>
• ✅ **A-2 (Textract: 文字抽出), B-3 (Forecast: 需要予測), C-1 (Kendra: 企業内検索)** <br>
**🐒 猿でもわかる解説** <br>
Textractは書類から「文字を抜き出す」。Forecastは売上などを「予測する」。Kendraは社内の書類を「検索する」。 <br>
**🧠 暗記方法** <br>
👉 「Textract＝抽出」「Forecast＝予測」「Kendra＝検索」 <br>

---

**問題10：手書き文字の抽出** <br>
**English Question (Original)** <br>
A company needs to extract handwritten words and letters from scanned documents. Which AWS service? <br>
**日本語訳** <br>
スキャンした書類から「手書き文字」を読み取って抽出するサービスは？ <br>
**選択肢** <br>
• Amazon Rekognition <br>
• Amazon Transcribe <br>
• ✅ **Amazon Textract** <br>
• Amazon Kendra <br>
**🐒 猿でもわかる解説** <br>
手書きだろうが活字だろうが、書類（Document）から文字を抜き出すのはTextract（テキスト・エキストラクト）の仕事です。 <br>
**🧠 暗記方法** <br>
👉 「書類の文字抜き ＝ Textract」 <br>

---

**問題11：データ不均衡の解消（データ前処理）** <br>
**English Question (Original)** <br>
Which of the following is a key use case addressed by Amazon SageMaker Data Wrangler? <br>
**日本語訳** <br>
Amazon SageMaker Data Wranglerで解決できる主要なユースケースはどれですか？ <br>
**選択肢** <br>
• ✅ **Fix bias by balancing the dataset** <br>データセットのバランスをとることでバイアスを修正する <br>
• Store and share features... <br>
• Build ML models with no code <br>
• Monitor quality of a model <br>
**🐒 猿でもわかる解説** <br>
データの数がグループごとにバラバラ（不均衡）だとAIに偏り（バイアス）が出ます。Data Wranglerはデータを増やしたり減らしたりしてバランスを整えることができます。 <br>
**🧠 暗記方法** <br>
👉 「不均衡なデータの調整 ＝ Data Wrangler」 <br>

---

**問題12：ユーザー属性に応じた回答調整（プロンプト）** <br>
**English Question (Original)** <br>
The chatbot needs to dynamically tailor its responses based on the user's age group. What is the solution? <br>
**日本語訳** <br>
ユーザーの年齢に合わせて、チャットボットの話し方を動的に変えるための最適な解決策は？ <br>
**選択肢** <br>
• RAG... <br>
• Fine-tuning... <br>
• Re-training... <br>
• ✅ **Implement dynamic prompt engineering to customize responses based on user characteristics like age** <br>年齢などのユーザー特性に基づいて応答をカスタマイズする動的プロンプトエンジニアリングを実装します <br>
**🐒 猿でもわかる解説** <br>
「子供向けに優しく話して」「大人向けに簡潔に話して」という指示文（プロンプト）を、ユーザーの年齢に応じて切り替えるのが一番簡単で効果的です。 <br>
**🧠 暗記方法** <br>
👉 「属性で話し方を変える ＝ プロンプトを工夫する」 <br>

---

**問題13：プロンプトエンジニアリング攻撃の対策** <br>
**English Question (Original)** <br>
What is the best approach to mitigate prompt engineering attacks? <br>
**日本語訳** <br>
AIを騙して変な回答をさせる「プロンプト攻撃」を防ぐ最善のアプローチは？ <br>
**選択肢** <br>
• ✅ **Create a prompt template that teaches the LLM to detect attack patterns** <br>LLMに攻撃パターンを検出するように教えるプロンプトテンプレートを作成する <br>
• Disable user-generated inputs... <br>
• Monitor length of prompts... <br>
• Restrict LLM output... <br>
**🐒 猿でもわかる解説** <br>
あらかじめ「怪しい命令を無視してね」というルールを盛り込んだテンプレートを用意して、AIに攻撃を見破らせるのが有効です。 <br>
**🧠 暗記方法** <br>
👉 「攻撃対策 ＝ 攻撃パターンをAIに教えるプロンプト」 <br>

---

**問題14：物体検出（Object Detection）** <br>
**English Question (Original)** <br>
Which approach to effectively recognize and categorize the various animal species in their image dataset? <br>
**日本語訳** <br>
画像内のさまざまな動物の種類を認識し、分類（場所も特定）するための手法はどれですか？ <br>
**選択肢** <br>
• ✅ **The company should use object detection, which involves identifying and locating specific objects within an image** <br>企業は、画像内の特定の物体を識別して位置を特定する物体検出を使用する必要があります。 <br>
• Thermal imaging... <br>
• Face recognition... <br>
• Named entity recognition <br>
**🐒 猿でもわかる解説** <br>
「画像の中のどこに何があるか」を見つけるのは、その名の通り「物体検出（Object Detection）」です。 <br>
**🧠 暗記方法** <br>
👉 「画像の中のモノ探し ＝ 物体検出」 <br>

---

**問題15：人間参加型ワークフロー（Ground Truth）** <br>
**English Question (Original)** <br>
The team wants to incorporate human input at key stages... which AWS service allows human input and feedback to be integrated? <br>
**日本語訳** <br>
学習の各段階で「人間の判断（フィードバック）」を取り入れるのに役立つサービスは？ <br>
**選択肢** <br>
• ✅ **Amazon SageMaker Ground Truth** <br>
• Amazon SageMaker Role Manager <br>
• Amazon SageMaker Feature Store <br>
• Amazon SageMaker Clarify <br>
**🐒 猿でもわかる解説** <br>
AIの精度を上げるために、人間が「これは猫だよ」と教えたりチェックしたりする作業（Human-in-the-loop）を支援するのはGround Truthです。 <br>
**🧠 暗記方法** <br>
👉 「人間によるラベル貼り ＝ Ground Truth」 <br>

---

**問題16：法的文書からの洞察抽出（Comprehend）** <br>
**English Question (Original)** <br>
Which fully-managed service for automating the extraction of insights from legal briefs such as contracts? <br>
**日本語訳** <br>
契約書などの法的文書から、自動で重要な情報を抜き出す（感情やキーワードを分析する）ためのサービスは？ <br>
**選択肢** <br>
• Amazon Transcribe <br>
• Amazon Translate <br>
• Amazon Rekognition <br>
• ✅ **Amazon Comprehend** <br>
**🐒 猿でもわかる解説** <br>
契約書などの「文章の意味」を理解して分析するのはNLP（自然言語処理）の得意分野、つまりComprehend（理解する）の仕事です。 <br>
**🧠 暗記方法** <br>
👉 「テキストの意味分析 ＝ Comprehend」 <br>

---

**問題17：AWS DeepRacer の特徴** <br>
**English Question (Original)** <br>
Which of the following represents the CORRECT statement about AWS DeepRacer? <br>
**日本語訳** <br>
AWS DeepRacerに関する正しい記述はどれですか？ <br>
**選択肢** <br>
• DeepRacer is virtual only... <br>
• DeepRacer car uses supervised learning... <br>
• ✅ **The AWS DeepRacer vehicle is a Wi-Fi enabled, physical vehicle that can drive itself on a physical track** <br>AWS DeepRacer車両は、Wi-Fi対応の物理的な車両であり、物理的なトラック上で自動運転することができます。 <br>
• You need an AWS DeepRacer car to use the simulator... <br>
**🐒 猿でもわかる解説** <br>
DeepRacerはシミュレーターだけでなく、実際にWi-Fiで動く「本物の模型車」もあります。 <br>
**🧠 暗記方法** <br>
👉 「DeepRacer ＝ 実物の車もある」 <br>

---

**問題18：全モデルの統合監視画面（Model Dashboard）** <br>
**English Question (Original)** <br>
Which Amazon SageMaker service aggregates and displays data from Model Cards, Model Monitor and Endpoints? <br>
**日本語訳** <br>
モデルカード、監視、エンドポイントの情報を一箇所にまとめて表示してくれるサービスは？ <br>
**選択肢** <br>
• ✅ **Amazon SageMaker Model Dashboard** <br>
• Amazon SageMaker JumpStart <br>
• Amazon SageMaker Data Wrangler <br>
• Amazon SageMaker Feature Store <br>
**🐒 猿でもわかる解説** <br>
アカウント内の全てのモデルが「ちゃんと動いてるか」をパッと見れる「管理パネル」がモデルダッシュボードです。 <br>
**🧠 暗記方法** <br>
👉 「モデルの全部入り監視板 ＝ Dashboard」 <br>

---

**問題19：法的文書のレビュー効率化（3つ選択）** <br>
**English Question (Original)** <br>
Which of the following options would you suggest for automating extraction from legal documents? (Select three) <br>
**日本語訳** <br>
法的文書のレビューを自動化・効率化するための組み合わせは？（3つ選択） <br>
**選択肢** <br>
• ✅ **Amazon Textract** <br>
• ✅ **Generative AI powered summarization chatbot** <br>
• Convolutional Neural Network (CNN) <br>
• WaveNet <br>
• ✅ **Amazon Comprehend** <br>
• Amazon Personalize <br>
**🐒 猿でもわかる解説** <br>
まずTextractで「文字を読み出し」、次にComprehendで「意味を分析」し、生成AIボットで「要約」するのが最強の流れです。 <br>
**🧠 暗記方法** <br>
👉 「読み取り(Textract) ＋ 分析(Comprehend) ＋ 要約(GenAI)」 <br>

---

**問題20：例題なしのプロンプト（Zero shot）** <br>
**English Question (Original)** <br>
What type of prompting technique does the given use case represent when summarizing without specific examples? <br>
**日本語訳** <br>
例題（サンプル）を一つも与えずに、「要約して」とだけ頼むプロンプト手法を何と言いますか？ <br>
**選択肢** <br>
• Chain-of-thought prompting <br>
• Few shot Prompting <br>
• ✅ **Zero shot Prompting** <br>
• Negative prompting <br>
**🐒 猿でもわかる解説** <br>
例題がゼロ（Zero）なので、そのままゼロショットと言います。 <br>
**🧠 暗記方法** <br>
👉 「例題なし ＝ Zero shot」 <br>

---

**問題21：Bedrock のカスタマイズ方法（コピーの作成）** <br>
**English Question (Original)** <br>
The company wants to provide its own labeled training dataset to improve FM's performance. Solution? <br>
**日本語訳** <br>
Bedrockのモデルを自社データで強化する場合、技術的にどういう動きになりますか？ <br>
**選択肢** <br>
• ✅ **Leverage Amazon Bedrock to make a separate copy of the base FM model and train this private copy of the model using the labeled training dataset** <br>Amazon Bedrock を活用してベース FM モデルの別のコピーを作成し、ラベル付けされたトレーニング データセットを使用してこのモデルのプライベート コピーをトレーニングします。 <br>
• Train the base FM itself... <br>
• Create a new model from scratch... <br>
• Make a public copy... <br>
**🐒 猿でもわかる解説** <br>
元の「土台モデル」そのものを書き換えるのではなく、自分専用の「コピー（プライベートコピー）」を作って、それを鍛えます。 <br>
**🧠 暗記方法** <br>
👉 「カスタマイズ ＝ 自分専用のコピーを作る」 <br>

---

**問題22：Bedrock と JumpStart の使い分け** <br>
**English Question (Original)** <br>
Which of the following best addresses the requirements between Amazon Bedrock and Amazon SageMaker JumpStart? <br>
**日本語訳** <br>
Bedrock と SageMaker JumpStart の違いを正しく説明しているのはどれですか？ <br>
**選択肢** <br>
• ✅ **Amazon Bedrock provides foundational models for generative AI applications, whereas Amazon SageMaker JumpStart offers pre-built solutions and one-click deployment for various machine learning models** <br>Amazon Bedrock は生成 AI アプリケーションの基礎モデルを提供し、Amazon SageMaker JumpStart はさまざまな機械学習モデル向けに構築済みのソリューションとワンクリックのデプロイメントを提供します。 <br>
• Bedrock is for building, JumpStart is for analytics... <br>
**🐒 猿でもわかる解説** <br>
*   **Bedrock**：APIを叩くだけで最新の生成AIをすぐ使える「サービス」。 <br>
*   **JumpStart**：色々なモデルが並んでいる「ハブ（お店）」で、そこから選んでデプロイします。 <br>
**🧠 暗記方法** <br>
👉 「Bedrock ＝ サービス」「JumpStart ＝ モデルのデパート」 <br>

---

**問題23：クラウドコンタクトセンター（Connect）** <br>
**English Question (Original)** <br>
Which AWS service helps you set up a cloud contact center in just a few clicks? <br>
**日本語訳** <br>
数クリックでクラウド型のコールセンター（コンタクトセンター）を構築できるサービスは？ <br>
**選択肢** <br>
• Amazon Lex <br>
• ✅ **Amazon Connect** <br>
• Amazon SageMaker Clarify <br>
• Amazon Personalize <br>
**🐒 猿でもわかる解説** <br>
コールセンター機能と言えば「Amazon Connect」です。自動応答だけでなく、人間のオペレーターの管理もできます。 <br>
**🧠 暗記方法** <br>
👉 「コールセンター ＝ Connect」 <br>

---

**問題24：セキュリティ責任の最大化（ゼロからの構築）** <br>
**English Question (Original)** <br>
Which of the following scenarios would require the company to assume the maximum level of security ownership? <br>
**日本語訳** <br>
生成AIを使う際、ユーザーが「最も多くの」セキュリティ責任を負うことになるシナリオはどれですか？ <br>
**選択肢** <br>
• Consuming a public third-party service... <br>
• ✅ **Building and training a generative AI model from scratch** <br>生成AIモデルをゼロから構築してトレーニングする <br>
• Refining an existing foundation model... <br>
• Building its own application using an existing FM... <br>
**🐒 猿でもわかる解説** <br>
他人が作ったものを使うのではなく、自分で「ゼロから（Scratch）」モデルを作って学習させる場合、その全ての過程に責任を持つ必要があります。 <br>
**🧠 暗記方法** <br>
👉 「自作（Scratch） ＝ 責任MAX」 <br>

---

**問題25：不完全な文章の単語予測（BERT）** <br>
**English Question (Original)** <br>
Which type of model should be used to suggest missing words in incomplete sentences? <br>
**日本語訳** <br>
エラーログなどで「穴あき」になった文章の単語を、前後の文脈から予測して埋めるのに適したモデルは？ <br>
**選択肢** <br>
• Rule-based NLP Model <br>
• Clustering Model <br>
• Prescriptive AI Model <br>
• ✅ **Bidirectional Encoder Representations from Transformers (BERT) based Model** <br>双方向エンコーダ表現（BERT）ベースのモデル <br>
**🐒 猿でもわかる解説** <br>
BERTは「双方向（Bidirectional）」、つまり単語の前後の両方を見て意味を考えるのが得意なので、穴埋め問題に最適です。 <br>
**🧠 暗記方法** <br>
👉 「文章の穴埋め ＝ 双方向のBERT」 <br>

---

**問題26：遅延許容の大容量推論（バッチ推論）** <br>
**English Question (Original)** <br>
A company needs to process a large inference payload of several gigabytes (GBs). Which inference method would be the most suitable? <br>
**日本語訳** <br>
数ギガバイト（GB）という巨大なデータをまとめて処理したいが、即レス（リアルタイム）は不要な場合に最適な方法は？ <br>
**選択肢** <br>
• Real-time inference <br>
• ✅ **Batch inference:The company should use batch inference, which processes multiple data points at once in large batches, suitable for processing large datasets in a single operation when immediate real-time responses are not required** <br>企業は、即時のリアルタイム応答が要求されない場合に、大規模なデータセットを1回の操作で処理するのに適した、複数のデータポイントを一度に大きなバッチで処理するバッチ推論を使用する必要があります。 <br>
• Asynchronous inference <br>
• Serverless inference <br>
**🐒 猿でもわかる解説** <br>
「大量のデータをまとめて一気に」処理するのが「バッチ（Batch）」の本来の意味です。GB単位ならバッチ推論が最適です。 <br>
**🧠 暗記方法** <br>
👉 「巨大データ ＋ 急がない ＝ バッチ（Batch）」 <br>

---

**問題27：似たアイテムの推奨（Personalize）** <br>
**English Question (Original)** <br>
Which of the following use cases is addressed by Amazon Personalize? <br>
**日本語訳** <br>
Amazon Personalizeが解決できるユースケースはどれですか？ <br>
**選択肢** <br>
• Enterprise search... <br>
• Mobile subscriber activities... <br>
• ✅ **Generate recommendations for items that are similar to an item you specify** <br>指定したアイテムに類似したアイテムのおすすめを生成します <br>
• Extract layout elements... <br>
**🐒 猿でもわかる解説** <br>
「この商品を見た人にはこれもおすすめ」のように、特定のアイテムに似た（Similar）ものを提案するのは、レコメンド専用のPersonalizeの仕事です。 <br>
**🧠 暗記方法** <br>
👉 「おすすめ（レコメンド） ＝ Personalize」 <br>

---

**問題28：テキストから音声への変換（Polly）** <br>
**English Question (Original)** <br>
Which AWS service can convert text into human speech? <br>
**日本語訳** <br>
テキスト（文字）を人間の声（音声）に変換するサービスはどれですか？ <br>
**選択肢** <br>
• Amazon Comprehend <br>
• Amazon Translate <br>
• ✅ **Amazon Polly** <br>
• Amazon Lex <br>
**🐒 猿でもわかる解説** <br>
文字を「ポリー（Polly）」が喋ってくれる、と覚えましょう。高音質な読み上げサービスです。 <br>
**🧠 暗記方法** <br>
👉 「読み上げ ＝ Polly」 <br>

---

**問題29：AMT（自動チューニング）の設定** <br>
**English Question (Original)** <br>
Which of the following options is mandatory for SageMaker Automatic Model Tuning (AMT)? <br>
**日本語訳** <br>
SageMakerの自動モデルチューニング（AMT）を行う際、必ず（手動で）設定しなければならない項目は？ <br>
**選択肢** <br>
• Tuning strategy <br>
• Number of jobs <br>
• ✅ **None** <br>
• Hyperparameter ranges <br>
**🐒 猿でもわかる解説** <br>
最新のSageMaker AMTは非常に賢く、「何も指定しなくても（None）」、AIが勝手に範囲や回数を選んでチューニングを始めてくれます。 <br>
**🧠 暗記方法** <br>
👉 「自動チューニング ＝ 全部AIにお任せ(None)でもOK」 <br>

---

**問題30：Bedrock の核心的な特徴** <br>
**English Question (Original)** <br>
Which AWS service/feature offers a choice of high-performing Foundation Models (FMs) and the ability to privately customize the FMs? <br>
**日本語訳** <br>
数多くの高性能な基盤モデル（FM）の中から好きなものを選べて、さらに自社データでプライベートにカスタマイズできるサービスは？ <br>
**選択肢** <br>
• AWS Inferentia <br>
• Amazon Q Developer <br>
• Amazon Q in QuickSight <br>
• ✅ **Amazon Bedrock** <br>
**🐒 猿でもわかる解説** <br>
Bedrock（ベッドロック）は、色々なメーカーのAI（ClaudeやLlamaなど）を一つの窓口で使える「生成AIのプラットフォーム」です。 <br>
**🧠 暗記方法** <br>
👉 「モデルが選べる ＋ カスタマイズできる ＝ Bedrock」 <br>

---

**問題31：テキストからSQL文の生成（GPT）** <br>
**English Question (Original)** <br>
Which of the following solutions would be most suitable for converting plain English text commands into SQL queries? <br>
**日本語訳** <br>
「先月の売上を表示して」といった普通の言葉を、データベース用の「SQL命令」に変換するのに適したモデルは？ <br>
**選択肢** <br>
• ResNet... <br>
• ✅ **GPT (Generative Pre-trained Transformer):The company should use GPT (Generative Pre-trained Transformer), to interpret natural language inputs and generating coherent outputs, such as SQL queries, by leveraging its understanding of language patterns and structures** <br>企業はGPT（Generative Pre-trained Transformer）を使用して、自然言語入力を解釈し、言語パターンと構造の理解を活用してSQLクエリなどの一貫した出力を生成する必要があります。 <br>
• WaveNet... <br>
• Amazon Comprehend... <br>
**🐒 猿でもわかる解説** <br>
GPTのような強力な言語モデルは、言葉の構造を理解して別の言語（プログラミング言語やSQL）に書き換えるのが非常に得意です。 <br>
**🧠 暗記方法** <br>
👉 「言葉をコード（SQL）に変える ＝ GPT」 <br>

---

**問題32：動画・画像からのナンバープレート検知（Rekognition）** <br>
**English Question (Original)** <br>
A traffic monitoring application needs to detect license plate numbers. Which AWS service? <br>
**日本語訳** <br>
走行中の車の「ナンバープレート」を読み取るのに最適なサービスは？ <br>
**選択肢** <br>
• Amazon Textract <br>
• ✅ **Amazon Rekognition** <br>
• Amazon SageMaker JumpStart <br>
• Amazon SageMaker image classification algorithm <br>
**🐒 猿でもわかる解説** <br>
Textractは「平らな書類」が得意。Rekognitionは「写真や動画の中にある文字」を斜めからでも遠くからでも見つけるのが得意です。 <br>
**🧠 暗記方法** <br>
👉 「風景の中の文字探し ＝ Rekognition」 <br>

---

**問題33：省エネな学習用チップ（Trainium）** <br>
**English Question (Original)** <br>
Which of the following EC2 instance types would be the most energy efficient for training complex machine learning models? <br>
**日本語訳** <br>
複雑なモデルの「学習（トレーニング）」において、最も消費電力が少なく（省エネで）高性能なチップを搭載したインスタンスは？ <br>
**選択肢** <br>
• ✅ **AWS Trainium instances** <br>
• Accelerated Computing G type... <br>
• Compute Optimized C type... <br>
• Accelerated Computing P type... <br>
**🐒 猿でもわかる解説** <br>
Trainium（トレイニアム）は、AWSが学習専用に開発したチップです。既存のGPUより省エネで爆速です。 <br>
**🧠 暗記方法** <br>
👉 「学習(Train)用の省エネチップ ＝ Trainium」 <br>

---

**問題34：社内データに答えるAIアシスタント（Q Business）** <br>
**English Question (Original)** <br>
Which is a generative AI–powered assistant that can answer questions based on information in the enterprise systems? <br>
**日本語訳** <br>
社内のドキュメントやシステムに基づいて、質問に答えたり要約したりしてくれるAIアシスタントは？ <br>
**選択肢** <br>
• Amazon Q Developer <br>
• Amazon Q in Connect <br>
• Amazon Q in QuickSight <br>
• ✅ **Amazon Q Business** <br>
**🐒 猿でもわかる解説** <br>
ビジネス（Business）の現場で、社内ルールや過去の資料について教えてくれる「AI社員」のような存在が Q Business です。 <br>
**🧠 暗記方法** <br>
👉 「社内資料の専門家 ＝ Q Business」 <br>

---

**問題35：コードの自動提案（Q Developer）** <br>
**English Question (Original)** <br>
Which of the following accurately describes what Amazon Q Developer can do? <br>
**日本語訳** <br>
Amazon Q Developerができることは何ですか？ <br>
**選択肢** <br>
• Create SageMaker models... <br>
• Deploy applications... <br>
• Create LLM chatbots... <br>
• ✅ **Amazon Q Developer can suggest code snippets, providing developers with recommendations for code based on specific tasks or requirements** <br>Amazon Q Developer はコードスニペットを提案し、特定のタスクや要件に基づいて開発者にコードの推奨事項を提供します。 <br>
**🐒 猿でもわかる解説** <br>
開発者（Developer）向けなので、コードの続きを書いてくれたり（サジェスト）、バグを見つけたりするのが仕事です。 <br>
**🧠 暗記方法** <br>
👉 「コードを書くのを手伝う ＝ Q Developer」 <br>

---

**問題36：ラベル付きデータ vs ラベルなしデータ** <br>
**English Question (Original)** <br>
What is a key difference between labeled data and unlabeled data? <br>
**日本語訳** <br>
「ラベル付きデータ」と「ラベルなしデータ」の違いは何ですか？ <br>
**選択肢** <br>
• ✅ **Labeled data is annotated with output labels and is used for supervised learning, whereas, unlabeled data lacks such annotations and is used for unsupervised learning** <br>ラベル付きデータは、各データポイントに関する特定の情報を提供する出力ラベルで注釈が付けられ、教師あり学習に使用されます。一方、ラベルなしデータにはそのような注釈がなく、教師なし学習に使用されます。 
<br>
**🐒 猿でもわかる解説** <br>
*   **ラベルあり**：「これは猫」という正解が付いている（教師あり学習用）。 <br>
*   **ラベルなし**：ただの生データ（教師なし学習用）。 <br>
**🧠 暗記方法** <br>
👉 「ラベル ＝ 正解（タグ）」 <br>

---

**問題37：識別モデル vs 生成モデル** <br>
**English Question (Original)** <br>
What is the primary distinction between discriminative models and generative models? <br>
**日本語訳** <br>
「識別モデル」と「生成モデル」の根本的な違いは何ですか？ <br>
**選択肢** <br>
• ✅ **Generative models focus on generating new data from learned patterns, whereas discriminative models classify data by distinguishing between different classes** <br>生成モデルは学習したパターンから新しいデータを生成することに重点を置いているのに対し、識別モデルは異なるクラスを区別することでデータを分類する。 <br>
**🐒 猿でもわかる解説** <br>
*   **識別（Discriminative）**：「犬か猫か当てる（分類）」。 <br>
*   **生成（Generative）**：「新しい犬の絵を描く（作成）」。 <br>
**🧠 暗記方法** <br>
👉 「識別 ＝ 分ける」「生成 ＝ 作る」 <br>

---

**問題38：Guardrails vs Watermark の違い** <br>
**English Question (Original)** <br>
Which of the following summarizes the differences between Guardrails and watermark detection? <br>
**日本語訳** <br>
Bedrockの「ガードレール」と「透かし（ウォーターマーク）検出」の違いは何ですか？ <br>
**選択肢** <br>
• ✅ **Guardrails helps control the interaction between users and FMs by filtering undesirable and harmful content, whereas, watermark detection identifies if an image was created by the Amazon Titan Image Generator model on Bedrock** <br>ガードレールは、望ましくない有害なコンテンツをフィルタリングすることで、ユーザーとFM間のやりとりを制御するのに役立ちます。一方、透かし検出は、画像がBedrock上のAmazon Titan Image Generatorモデルによって作成されたかどうかを識別します。 <br>
**🐒 猿でもわかる解説** <br>
*   **ガードレール**：危ない発言や個人情報を「止める・隠す」ための壁。 <br>
*   **透かし検出**：その画像が「AI（Titan）で作られた本物か」を判定するマーク。 <br>
**🧠 暗記方法** <br>
👉 「ガードレール ＝ 防御」「透かし ＝ AI製かどうかの証明」 <br>

---

**問題39：需要予測サービス（Forecast）** <br>
**English Question (Original)** <br>
A retail company needs a solution for forecasting foot traffic and visitor counts. Which AWS service? <br>
**日本語訳** <br>
来客数や商品の需要を「予測」してコストを抑えたい場合に最適なサービスは？ <br>
**選択肢** <br>
• Amazon SageMaker Feature Store <br>
• Amazon Lex <br>
• Amazon Personalize <br>
• ✅ **Amazon Forecast** <br>
**🐒 猿でもわかる解説** <br>
過去のデータから未来を予測（Forecast）するのが、その名の通り「Amazon Forecast」です。 <br>
**🧠 暗記方法** <br>
👉 「未来の予測 ＝ Forecast」 <br>

---

**問題40：レシートや請求書の読み取り（Textract）** <br>
**English Question (Original)** <br>
A business needs an automated solution that can extract text from thousands of receipts and invoices. <br>
**日本語訳** <br>
数千枚ものレシートや請求書から文字を抽出するのに最適なサービスは？ <br>
**選択肢** <br>
• Amazon Transcribe <br>
• Amazon Comprehend <br>
• Amazon Rekognition <br>
• ✅ **Amazon Textract** <br>
**🐒 猿でもわかる解説** <br>
「書類のプロ」といえばTextract。表（テーブル）の構造も維持したまま抜き出してくれます。 <br>
**🧠 暗記方法** <br>
👉 「レシート・書類 ＝ Textract」 <br>

---

**問題41：モデルの使用指針とリスク評価（Model Cards）** <br>
**English Question (Original)** <br>
Which AWS tool offers clear guidance on how each model should be used along with an assessment of the potential risks? <br>
**日本語訳** <br>
モデルの正しい使い方（推奨用途）や、考えられるリスクを文書化して管理するツールは？ <br>
**選択肢** <br>
• Amazon SageMaker Ground Truth <br>
• Amazon SageMaker Canvas <br>
• Amazon SageMaker Model Monitor <br>
• ✅ **Amazon SageMaker Model Cards** <br>
**🐒 猿でもわかる解説** <br>
モデルの「説明書（カード）」のようなものです。何に使うべきか、何に注意すべきかを一箇所にまとめます。 <br>
**🧠 暗記方法** <br>
👉 「モデルの公式説明書 ＝ Model Cards」 <br>

---

**問題42：現実的な疑似データ生成（GAN）** <br>
**English Question (Original)** <br>
Which of the following methods would be most suitable for generating synthetic data? <br>
**日本語訳** <br>
本物のデータの統計的特徴を保ったまま、偽物の「疑似データ（合成データ）」を作るのに適した手法は？ <br>
**選択肢** <br>
• Support Vector Machines (SVMs)... <br>
• WaveNet... <br>
• Convolutional Neural Network (CNN)... <br>
• ✅ **The company should use a Generative Adversarial Network (GAN) for creating realistic synthetic data** <br>企業は、元のデータの統計的特性を維持しながら現実的な合成データを作成するために、生成的敵対的ネットワーク（GAN）を使用する必要があります。 <br>
**🐒 猿でもわかる解説** <br>
GAN（ギャン）は「作る係」と「見破る係」が競い合って、本物そっくりのデータ（画像など）を作り出す技術です。 <br>
**🧠 暗記方法** <br>
👉 「本物そっくりの偽物作り ＝ GAN」 <br>

---

**問題43：学習と推論のハードウェア最適化** <br>
**English Question (Original)** <br>
Which of the following hardware should be suggested for AI workflows? <br>
**日本語訳** <br>
ハードウェアの使い分けとして正しい提案はどれですか？ <br>
**選択肢** <br>
• ✅ **LLeverage AWS Trainium for high-performance, cost-effective Deep Learning training. Leverage AWS Inferentia for the deep learning (DL) and generative AI inference applications** <br>AWS Trainium を活用して、高性能でコスト効率の高いディープラーニングトレーニングを実現します。AWS Inferentia を活用して、ディープラーニング (DL) および生成型 AI 推論アプリケーションを実現します。 <br>
**🐒 猿でもわかる解説** <br>
学習（Training）は「トレイニアム（Trainium）」、推論（Inference）は「インフェレンシア（Inferentia）」です。名前の通りですね。 <br>
**🧠 暗記方法** <br>
👉 「学習 ＝ Trainium」「推論 ＝ Inferentia」 <br>

---

**問題44：Amazon Personalize 用の前処理（Data Wrangler）** <br>
**English Question (Original)** <br>
Which AWS service will help import, prepare, and transform data before it is fed into Amazon Personalize? <br>
**日本語訳** <br>
Amazon Personalize にデータを入れる前に、インポートや加工（前処理）をするのを助けるサービスは？ <br>
**選択肢** <br>
• Amazon SageMaker Ground Truth <br>
• Amazon SageMaker Clarify <br>
• Amazon SageMaker Feature Store <br>
• ✅ **Amazon SageMaker Data Wrangler** <br>
**🐒 猿でもわかる解説** <br>
データを綺麗にする（調理の下準備をする）のは、いつも「Data Wrangler（データのカウボーイ）」の仕事です。 <br>
**🧠 暗記方法** <br>
👉 「データ整理のプロ ＝ Data Wrangler」 <br>

---

**問題45：SageMaker Studio で使えるIDE** <br>
**English Question (Original)** <br>
Which Integrated Development Environments (IDEs) are supported within SageMaker Studio? <br>
**日本語訳** <br>
SageMaker Studio でサポートされている開発環境（IDE）はどれですか？ <br>
**選択肢** <br>
• JupyterLab <br>
• RStudio <br>
• Code Editor (VS Codeベース) <br>
• ✅ **All** <br>
**🐒 猿でもわかる解説** <br>
SageMaker Studioは「全部入り」の開発環境なので、JupyterもRStudioもVS Code風エディタも全部使えます。 <br>
**🧠 暗記方法** <br>
👉 「IDEは全部（All）入り」 <br>

---

**問題46：Amazon Q Developer の利用場所** <br>
**English Question (Original)** <br>
Where can Amazon Q Developer be used? <br>
**日本語訳** <br>
Amazon Q Developer はどこで利用できますか？ <br>
**選択肢** <br>
• Only in AWS Console... <br>
• ✅ **In integrated development environments (IDEs) as well as the AWS Management Console** <br>Amazon Q Developerは、AWSマネジメントコンソールだけでなく、統合開発環境（IDE）でも使用できます。 <br>
**🐒 猿でもわかる解説** <br>
AWSの管理画面だけでなく、プログラミングをする「IDE（VS Codeなど）」の中でも動いて助けてくれます。 <br>
**🧠 暗記方法** <br>
👉 「管理画面でも IDEの中でも Qが助ける」 <br>

---

**問題47： Bedrock カスタマイズ用のデータ置き場** <br>
**English Question (Original)** <br>
Which of the following storage options would be the most suitable for model validation datasets in Bedrock? <br>
**日本語訳** <br>
Amazon Bedrockでモデルをカスタマイズする際のデータ（学習・検証用）の置き場として最適なのは？ <br>
**選択肢** <br>
• ✅ **The company should use Amazon S3, which is a scalable object storage service fully integrated with Amazon Bedrock** <br>同社はAmazon Bedrockと完全に統合されたスケーラブルなオブジェクトストレージサービスであるAmazon S3を使用する必要がある。 <br>
• Amazon RDS... <br>
• Amazon EFS... <br>
• Amazon EBS... <br>
**🐒 猿でもわかる解説** <br>
機械学習の大量データは「とりあえずS3に置く」のがAWSの鉄則です。Bedrockとも最初から連携しています。 <br>
**🧠 暗記方法** <br>
👉 「データの置き場 ＝ いつものS3」 <br>

---

**問題48：責任あるAIのガバナンス戦略（2つ選択）** <br>
**English Question (Original)** <br>
Which two governance strategies should the team prioritize for ethical AI? (Select two) <br>
**日本語訳** <br>
倫理的なAI運用のために優先すべき2つのガバナンス戦略は？（2つ選択） <br>
**選択肢** <br>
• ✅ **Establish ethical AI guidelines for developers to follow** <br>
• ✅ **Implement robust auditing processes for AI outputs** <br>
**🐒 猿でもわかる解説** <br>
開発者が守るべき「ルール（ガイドライン）」を作り、AIが出した結果に問題がないか「検査（監査）」することが重要です。 <br>
**🧠 暗記方法** <br>
👉 「良いAI ＝ ルール作り ＋ 出力のチェック」 <br>

---

**問題49：創造性の設定：温度（Temperature）** <br>
**English Question (Original)** <br>
What do you recommend regarding the Temperature parameter in Amazon Bedrock? <br>
**日本語訳** <br>
Bedrockの推論パラメータ「Temperature（温度）」は何を調整するものですか？ <br>
**選択肢** <br>
• ✅ **Influences the likelihood of selecting lower-probability outputs, impacting the creativity** <br>
**🐒 猿でもわかる解説** <br>
「温度」を上げると、AIが少し珍しい言葉（低確率な単語）も選ぶようになり、回答が「クリエイティブ（独創的）」になります。 <br>
**🧠 暗記方法** <br>
👉 「温度を上げる ＝ AIがノリノリで独創的になる」 <br>

---

**問題50：医療情報の抽出（Comprehend Medical）** <br>
**English Question (Original)** <br>
Which ML-powered service is the right fit to extract health information from unstructured clinical data? <br>
**日本語訳** <br>
医師のメモなどの医療用データから、病名や薬名を自動で抜き出すのに最適なサービスは？ <br>
**選択肢** <br>
• Amazon Comprehend <br>
• Amazon Rekognition <br>
• ✅ **Amazon Comprehend Medical** <br>
• Amazon SageMaker <br>
**🐒 猿でもわかる解説** <br>
普通の文章分析（Comprehend）の「医療専門版」がある、と覚えましょう。HIPAA対応で専門用語に強いです。 <br>
**🧠 暗記方法** <br>
👉 「医療テキストの分析 ＝ Comprehend Medical」 <br>

---

**問題51：不適切な回答を防ぐプロンプト指示** <br>
**English Question (Original)** <br>
What would be the most effective approach to control risks of generating inappropriate content? <br>キーワード：inappropriate, sensitive, or malicious content<br>
**日本語訳** <br>
AIに不適切な内容を喋らせないための、最も（直接的で）効果的なアプローチは？ <br>
**選択肢** <br>
• ✅ **The company should instruct the model to stick to the prompt by adding explicit instructions to ignore any unrelated or malicious content** <br>企業は、モデルに、無関係なコンテンツや悪意のある可能性のあるコンテンツを無視するように明確な指示を追加して、プロンプトに従うように指示する必要があります。 <br>
**🐒 猿でもわかる解説** <br>
「関係ないことや、悪い指示は無視してね」とはっきり言葉で伝える（プロンプトで指示する）ことが、最初の一歩として非常に有効です。 <br>
**🧠 暗記方法** <br>
👉 「悪い指示は無視してね ＝ プロンプトで教え込む」 <br>

---

**問題52：特徴量の共有と管理（Feature Store）** <br>
**English Question (Original)** <br>
Which AWS tool would be the most suitable for sharing and managing the variables (features) used in models across teams? <br>
**日本語訳** <br>
作成した「特徴量」を他のチームと共有したり、再利用したりするために一箇所で管理するツールは？ <br>
**選択肢** <br>
• ✅ **SageMaker Feature Store** <br>
• SageMaker Model Monitor <br>
• SageMaker Clarify <br>
• SageMaker Data Wrangler <br>
**🐒 猿でもわかる解説** <br>
特徴量（Feature）を貯めておく専用の倉庫（Store）のことです。これがあれば、他のチームが作った便利なデータを再利用できます。 <br>
**🧠 暗記方法** <br>
👉 「特徴量の使い回し ＝ Feature Store」 <br>

---

**問題53：モデルの使用目的と前提条件の記録（Model Cards）** <br>
**English Question (Original)** <br>
Which Amazon SageMaker tool documents the model’s intended uses and any assumptions made during development? <br>
**日本語訳** <br>
モデルが「何のために作られたか」「どう使われるべきか」を記録して透明性を高めるツールは？ <br>
**選択肢** <br>
• ✅ **Amazon SageMaker Model Cards** <br>
• Amazon SageMaker Clarify <br>
• Amazon SageMaker Model Monitor <br>
• Amazon SageMaker Canvas <br>
**🐒 猿でもわかる解説** <br>
これも「モデルの説明書（カード）」の役割です。技術的なことだけでなく、「正しい使い道」を書くのがポイントです。 <br>
**🧠 暗記方法** <br>
👉 「モデルの履歴・用途の記録 ＝ Model Cards」 <br>

---

**問題54：LLM の性質（非決定的）** <br>
**English Question (Original)** <br>
Which of the following is correct regarding Large Language Models (LLMs)? <br>
**日本語訳** <br>
大規模言語モデル（LLM）の性質について正しい記述はどれですか？ <br>
**選択肢** <br>
• LLMs are discriminative... <br>
• ✅ **The Large Language Models (LLMs) are non-deterministic** <br>大規模言語モデル（LLM）は非決定論的である <br>
• LLMs are deterministic... <br>
• FMs are a class of LLMs... <br>
**🐒 猿でもわかる解説** <br>
LLMは「非決定的（Non-deterministic）」です。つまり、同じ質問をしても毎回少しずつ違う答えを出す可能性がある、ということです。 <br>
**🧠 暗記方法** <br>
👉 「AIの答えは毎回変わるかも ＝ 非決定的」 <br>

---

**問題55：検索対象からの個人情報削除（Comprehend）** <br>
**English Question (Original)** <br>
Which AWS service will help you redact the PII in support tickets before creating search indexes? <br>
**日本語訳** <br>
検索エンジンにデータを入れる前に、文書内の個人情報（PII：名前や住所など）を自動で見つけて伏せ字にするサービスは？ <br>
**選択肢** <br>
• ✅ **Amazon Comprehend** <br>
• Amazon Kendra <br>
• Amazon Textract <br>
• Amazon Lex <br>
**🐒 猿でもわかる解説** <br>
Comprehendは「文章を理解」するので、どこが名前で、どこが電話番号かを特定し、隠す（Redact）ことができます。 <br>
**🧠 暗記方法** <br>
👉 「個人情報の見つけ出し・削除 ＝ Comprehend」 <br>

---

**問題56：インフラ管理不要・断続的なワークロード（Serverless）** <br>
**English Question (Original)** <br>
Since the company has intermittent workloads and it does not want to manage the infrastructure... deployment model? <br>
**日本語訳** <br>
たまにしかリクエストが来ない（断続的）かつ、サーバーの管理をしたくない場合に最適な推論モデルは？ <br>
**選択肢** <br>
• Real-time... <br>
• Asynchronous... <br>
• Batch... <br>
• ✅ **Serverless Inference** <br>
**🐒 猿でもわかる解説** <br>
「サーバーレス（Serverless）」なら、使っていない時は料金がかからず、リクエストが来た時だけ自動で立ち上がって処理してくれます。 <br>
**🧠 暗記方法** <br>
👉 「たまにしか使わない ＋ 管理不要 ＝ サーバーレス」 <br>

---

**問題57：医療用音声の文字起こし（Transcribe Medical）** <br>
**English Question (Original)** <br>
Which AWS service is specifically designed for converting medical speech to text? <br>
**日本語訳** <br>
医師の診察音声などを、医療用語を正しく認識して文字起こしするサービスは？ <br>
**選択肢** <br>
• Amazon Polly <br>
• Amazon Rekognition <br>
• Amazon Transcribe <br>
• ✅ **Amazon Transcribe medical** <br>
**🐒 猿でもわかる解説** <br>
普通の文字起こし（Transcribe）の医療専門版です。難しい薬の名前なども正しく文字にできます。 <br>
**🧠 暗記方法** <br>
👉 「医療の聞き取り ＝ Transcribe Medical」 <br>

---

**問題58：基盤モデルの精度評価方法（ベンチマーク）** <br>
**English Question (Original)** <br>
What is the best way to assess the accuracy of the foundation model for image classification? <br>
**日本語訳** <br>
画像分類用モデルの精度を、客観的かつ信頼できる方法でテストするにはどうすればいいですか？ <br>
**選択肢** <br>
• ✅ **Use a benchmark dataset for evaluation** <br>
• Manually test with random images... <br>
• Gather user feedback in production... <br>
• Evaluate with small subset... <br>
**🐒 猿でもわかる解説** <br>
世界的に標準となっているテスト問題集（ベンチマークデータセット）を使って評価するのが、最も正確で公平です。 <br>
**🧠 暗記方法** <br>
👉 「精度テスト ＝ 共通テスト（ベンチマーク）」 <br>

---

**問題59：マルチクラス vs マルチラベルの違い** <br>
**English Question (Original)** <br>
What is the difference between multi-class and multi-label classification? <br>
**日本語訳** <br>
「マルチクラス分類」と「マルチラベル分類」の違いは何ですか？ <br>
**選択肢** <br>
• ✅ **Multi-class classification assigns each instance to one of several possible classes, while multi-label classification assigns each instance to one or more classes** <br>マルチクラス分類では各インスタンスを複数のクラスのいずれかに割り当てますが、マルチラベル分類では各インスタンスを1つ以上のクラスに割り当てます。 <br>
**🐒 猿でもわかる解説** <br>
*   **マルチクラス**：「犬・猫・鳥のどれか1つ」に分ける。 <br>
*   **マルチラベル**：「この本は『科学』かつ『歴史』」のように複数のタグを付ける。 <br>
**🧠 暗記方法** <br>
👉 「クラス ＝ どれか1つ」「ラベル ＝ 複数OK」 <br>

---

**問題60：モデルカードの内容（正しい記述）** <br>
**English Question (Original)** <br>
Which of the following represents the CORRECT statement regarding Amazon SageMaker Model Cards? <br>
**日本語訳** <br>
Amazon SageMaker モデルカードに関する正しい記述はどれですか？ <br>
**選択肢** <br>
• ✅ **Describes how a model should be used in a production environment** <br>モデルを本番環境でどのように使用すべきかを説明します <br>
• Customized to meet needs (No, fixed structure)... <br>
• Only technical requirements... <br>
• Cannot be created for non-SageMaker models... <br>
**🐒 猿でもわかる解説** <br>
モデルカードは、「このモデルは本番環境でこう使うべきですよ」というガイドラインを記すものです。 <br>
**🧠 暗記方法** <br>
👉 「モデルカード ＝ 本番での使い道を書く」 <br>

---

**問題61：画像からのテキスト抽出サービス（2つ選択）** <br>
**English Question (Original)** <br>
Which AWS ML services will automatically detect and extract text from scanned images? (Select two) <br>
**日本語訳** <br>
スキャンした画像から「文字」を見つけて抜き出せるサービスはどれですか？（2つ選択） <br>
**選択肢** <br>
• ✅ **Amazon Textract** <br>
• ✅ **Amazon Rekognition** <br>
• Amazon Comprehend <br>
• Amazon Lex <br>
**🐒 猿でもわかる解説** <br>
Textractは「書類」向き、Rekognitionは「写真の中の看板」など向きですが、どちらも画像から文字を抜くことができます。 <br>
**🧠 暗記方法** <br>
👉 「文字抜き（画像から） ＝ Textract ＆ Rekognition」 <br>

---

**問題62：予測の人間レビュー（Amazon A2I）** <br>
**English Question (Original)** <br>
Which AWS service helps in human reviews and audits for ML model predictions? <br>
**日本語訳** <br>
AIの予測が正しいか、人間がレビュー・監査する仕組みを簡単に作れるサービスは？ <br>
**選択肢** <br>
• ✅ **Amazon Augmented AI (A2I)** <br>
• Amazon Forecast <br>
• Amazon SageMaker Ground Truth <br>
• AWS DeepRacer <br>
**🐒 猿でもわかる解説** <br>
AIが「自信がないな…」となった時に、人間にパスして確認してもらう（Augmented：拡張されたAI）のが A2I です。 <br>
**🧠 暗記方法** <br>
👉 「人間が交代して確認 ＝ A2I」 <br>

---

**問題63：SageMaker のガバナンスツールセット** <br>
**English Question (Original)** <br>
Which of the following would you recommend as governance tools? <br>
**日本語訳** <br>
機械学習の責任ある運用（ガバナンス）のために推奨されるサービスセットは？ <br>
**選択肢** <br>
• ✅ **Amazon SageMaker Role Manager, Model Cards, Model Dashboard** <br>
**🐒 猿でもわかる解説** <br>
「誰が触るか（Role Manager）」「説明書（Model Cards）」「監視モニタ（Model Dashboard）」の3つが統治の基本セットです。 <br>
**🧠 暗記方法** <br>
👉 「ガバナンス ＝ 権限 ＋ 説明 ＋ 監視」 <br>

---

**問題64：コールセンターAI導入の成功指標** <br>
**English Question (Original)** <br>
Which of the following metrics should be monitored to evaluate the success of a chatbot for call center employees? <br>
**日本語訳** <br>
従業員の電話対応を助けるチャットボットを導入した際、最も「効率化」を測れる指標はどれですか？ <br>
**選択肢** <br>
• Average Chat Sessions... <br>
• Chat API Calls... <br>
• ✅ **Average Call Duration** <br>
• First-Call Resolution Rate <br>
**🐒 猿でもわかる解説** <br>
ボットが回答を素早く教えてくれれば、1回あたりの「通話時間（Duration）」が短くなるはずです。これが短くなれば成功です。 <br>
**🧠 暗記方法** <br>
👉 「コールセンターの効率化 ＝ 通話時間の短縮」 <br>

---

**問題65：高品質・低リスクなラベル付け（GroundTruth Plus）** <br>
**English Question (Original)** <br>
What is the best approach to achieve high accuracy and reduce the risk of errors in image annotations? <br>
**日本語訳** <br>
画像へのラベル貼り（アノテーション）において、ミスを減らし最高精度を出すための方法は？ <br>
**選択肢** <br>
• ✅ **Use GroundTruth Plus to label the data** <br>
• Internal employees... <br>
• Rule-based algorithm... <br>
• Pre-trained model... <br>
**🐒 猿でもわかる解説** <br>
GroundTruthの「Plus」版は、AWS側が専門のチームを組んで品質を保証してくれるフル管理型サービスです。自社でやるよりずっと正確です。 <br>
**🧠 暗記方法** <br>
👉 「最高のラベル貼り品質 ＝ GroundTruth Plus」 <br>
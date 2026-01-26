### **AWS Certified AI Practitioner - Practice Test #1**
# AWS AI Practitioner AIF-C01 Practice exam
| １st Time    | 2nd time    |  3rd Time   | 4th Time |
|:---------------|:-----------|:----------|:----------|
| 21% | 67%    | 75% | %   |

**問題1：顧客レビューの感情分析（2つ選択）** <br>
**English Question (Original)**
An e-commerce company wants to analyze thousands of customer reviews it receives daily to understand customer sentiment — whether positive, negative, neutral, or mixed. Which of the following would you recommend? <br> (Select two) <br>
**日本語訳** <br>
あるEC企業は、毎日数千件届く顧客レビューを分析し、それらがポジティブ・ネガティブ・中立・混合のどれなのかを理解したいと考えています。 <br>どのAWSサービスを推奨しますか？ <br>（2つ選択） <br>
**選択肢** <br>
*   Amazon Textract
*   Amazon Personalize
*   ✅ **Amazon Bedrock**
*   ✅ **Amazon Comprehend**
*   Amazon Rekognition <br>
<br>
**🐒 猿でもわかる解説** <br>
*   **Amazon Comprehend**：文章から感情やキーワードを見つけ出すNLP（Natural Language Processing:自然言語処理）の専門家です。 <br>
*   **Amazon Bedrock**：基盤モデルを使って感情分析などの高度なテキスト処理が可能です。 <br>
*   ❌ **Textract**：画像から文字を抽出するだけで、意味（感情）は分かりません。 <br>
*   ❌ **Rekognition**：画像や動画を分析するサービスです。 <br>
**🧠 暗記方法** <br>
👉 「感情＝Comprehend（理解する）」「テキスト生成・分析＝Bedrock」

---

**問題2：画像生成モデルのバイアス対策** <br>
**English Question (Original)** <br>
A media company has noticed that its AI-based image generation model consistently produces biased outputs due to imbalanced training data. What would be the most suitable strategy? <br>
**日本語訳** <br>
AI画像生成モデルが、学習データの不均衡（偏り）によってバイアスのある結果を出しています。 <br>最も適切な対策はどれですか？ <br>
**選択肢** <br>
*   Use another model
*   Apply regularization
*   Human intervention
*   ✅ **Augment the data for underrepresented groups** <br>代表性の低いグループのデータを増強する <br>
 <br>
**🐒 猿でもわかる解説** <br>
**データ拡張（Augmentation）**：足りないグループのデータを増やしてバランスを取るのが最も根本的な解決策です。 <br>
*   ❌ **モデル変更**：元のデータが偏っていたら、どのモデルを使ってもバイアスは消えません。 <br>
*   ❌ **人的介入**：大規模なデータでは現実的ではなく、ミスも起きます。 <br>
**🧠 暗記方法** <br>
👉 「バイアス対策＝データの増量（拡張）」

---

**問題3：生成AIの有効なユースケース** <br>
**English Question (Original)** <br>
Which of the following represents a valid use case for a generative AI-powered model? <br>
**日本語訳** <br>
生成AI（Generative AI）モデルの有効なユースケースはどれですか？ <br>
**選択肢** <br>
*   ✅ **Using generative AI to create photorealistic images from textual descriptions** <br>生成AIを用いて、テキストによる説明からフォトリアルな画像を生成する
*   Utilizing generative AI to predict housing prices based on historical market data
*   Classifying medical images to detect anomalies or diagnose diseases using generative AI
*   Applying generative AI for financial analysis to forecast stock market trends <br>
**🐒 猿でもわかる解説** <br> 
*   **生成AI**：その名の通り、新しい「コンテンツ（画像、文章、音楽など）」を作るのが得意です。 <br>
*   ❌ **価格予測・株価予測**：これらは「回帰（数値予測）」であり、従来の機械学習の領域です。 <br>
*   ❌ **画像分類**：これは「識別（どのカテゴリか当てる）」であり、生成ではありません。 <br>
**🧠 暗記方法** <br>
👉 「生成AI＝新しいものを作る（Create）」

---

**問題4：基盤モデル（FM）の学習特徴** <br>
**English Question (Original)** <br>
Which of the following statements is correct regarding Foundation Models (FMs) in the context of generative AI? <br>
**日本語訳** <br> 
生成AIにおける基盤モデル（FM）に関する記述として正しいものはどれですか？ <br>
**選択肢** <br>
*   FMs use self-supervised learning to create labels and fine-tuning is also self-supervised
*   ✅ **FMs use self-supervised learning to create labels, however, fine-tuning an FM is a supervised learning process** <br>基盤モデル（FM）は自己教師あり学習を用いてラベルを作成しますが、基盤モデルのファインチューニングは教師あり学習のプロセスです。
*   FMs use supervised learning and fine-tuning is also supervised
*   FMs use supervised learning, however, fine-tuning an FM is a self-supervised process <br>
**🐒 猿でもわかる解説** <br>
*   **FMの最初（事前学習）**：大量のデータから自分で勝手に学習する「自己教師あり学習（Self-supervised）」です。 <br>
*   **微調整（Fine-tuning）**：人間が用意した正解ラベル付きデータで教え込む「教師あり学習（Supervised）」です。 <br>
**🧠 暗記方法** <br>
👉 「最初＝自己教師（Self）」「仕上げ＝教師あり（Supervised）」 <br>

---

**問題5：AWSで生成AIを使う利点** <br>
**English Question (Original)** <br>
What is one of the primary advantages of using generative AI in the AWS cloud environment? <br>
**日本語訳** <br>
AWSクラウド環境で生成AIを使用する主な利点の1つは何ですか？ <br>
**選択肢** <br>
*   Generative AI can perform all cloud maintenance without human intervention
*   Generative AI ensures 100% security against all cyber threats
*   ✅ **Generative AI can automate the creation of new data based on existing patterns, enhancing productivity and innovation** <br>生成AIは、既存のパターンに基づいて新しいデータの作成を自動化することができ、生産性とイノベーションを向上させる。
*   Generative AI can replace all human roles in software development <br>
**🐒 猿でもわかる解説** <br>
*   既存のパターンから「新しいデータ作成を自動化」することで、生産性が爆上がりします。 <br>
*   ❌ **100%セキュリティ**：AIでも完璧な保証は不可能です。 <br>
*   ❌ **人間を置き換える**：AIはあくまで「支援」するもので、全てを置き換えるものではありません。 <br>
**🧠 暗記方法** <br>
👉 「利点＝新しいデータの自動作成による革新」

---

**問題6：モデルの汎化能力（過学習）の改善** <be>
**English Question (Original)** <br>
The company needs to improve the model's ability to generalize and perform well on new data, ensuring reliable predictions in the production setting.
What would be the most effective approach to fix this problem? <br>
**日本語訳** <br>
本番環境の新しいデータに対して精度が落ちてしまう（過学習）問題を解決する最も効果的な方法は？ <br>
**選択肢** <br>
*   ✅ **The company should use hyperparameters for model tuning (regularization, learning rates, etc.) to enhance generalization** <br>企業は、モデルのチューニング（正則化、学習率など）にハイパーパラメータを使用することで、汎化性能を向上させるべきである。
*   The company should increase the amount of training data
*   The company should reduce the amount of training data
*   The company should swap the existing model with a generative AI model <br>
**🐒 猿でもわかる解説** <br>
*   **ハイパーパラメータ調整**：正則化やドロップアウトなどを調整して、未知のデータにも対応できるように「汎化性能」を高めます。 <br>
*   ❌ **データ削減**：データが足りなくなると、そもそも学習不足（アンダーフィッティング）になります。 <br>
**🧠 暗記方法** <br>
👉 「本番で精度低下＝過学習対策＝パラメータ調整」

---

**問題7：最適なモデル選択のための定義** <br>
**English Question (Original)** <br>
What should the developer ask the research team to do in order to ensure that the best model is selected for the AI application? <br>
**日本語訳** <br>
AIアプリに最適なモデルを選ぶために、研究チームに何を依頼すべきですか？ <br>
**選択肢** <br>
*   Determine the cost constraints
*   ✅ **Define the use case of the application narrowly** <br>アプリケーションのユースケースを限定的に定義する。
*   Identify potential data sources
*   Define the target audience broadly <br>
**🐒 猿でもわかる解説** <br>
*   **ユースケースを狭く定義**：目的がはっきり（顧客離反の特定など）していれば、それに最適なモデルを選びやすくなります。 <br>
*   ❌ **ターゲットを広く定義**：要件が曖昧になり、モデルの選択ミスにつながります。 <br>
**🧠 暗記方法** <br>
👉 「良いモデル選び＝使い道を具体的に（狭く）決める」

---

**問題8：モデル精度の向上方法** <br>
**English Question (Original)** <br>
Which approach would you recommend to enhance the accuracy of the company's machine learning models? <br>
**日本語訳** <br>
機械学習モデルの精度を高めるために推奨されるアプローチは？ <br>
**選択肢** <br>
*   Reduce the batch size
*   ✅ **The company should increase the number of epochs, which involves training the model for more iterations over the dataset** <br>エポック数を増やす（データセットに対する反復回数を増やす）
*   Decrease the learning rate
*   Increase regularization
**🐒 猿でもわかる解説** <br>
*   **エポック数（Epochs）**：学習回数を増やすことで、データ内の複雑なパターンをより深く理解させます。 <br>
*   ❌ **正則化を増やす**：学習を制限するため、やりすぎると逆に精度が下がる（アンダーフィッティング）ことがあります。 <br>
**🧠 暗記方法** <br>
👉 「精度アップ＝反復回数（Epoch）を増やす」

---

**問題9：AI生成エッセイの検出目的** <br>
**English Question (Original)** <br>
What specific issue is the admissions committee primarily trying to address by detecting the use of generative AI in application essays? <br>
**日本語訳** <br>
入試委員会がエッセイにおける生成AI利用を検出しようとする主な目的は何ですか？ <br>
**選択肢** <br>
*   ✅ **Plagiarism**
*   Hallucination
*   Misinterpretation
*   Bias <br>
**🐒 猿でもわかる解説** <br>
*   **盗用（Plagiarism）**：AIが作った文章を自分のものとして出すのは、誠実さや公平性に欠ける行為です。 <br>
*   ❌ **ハルシネーション**：AIの嘘情報のことで、入試における「自分の作品か」という問題とは別です。 <br>
**🧠 暗記方法** <br>
👉 「エッセイ偽造＝盗用（Plagiarism）」

---

**問題10：Amazon MLサービスの特徴（2つ選択）** <br>
**English Question (Original)** <br>
Which of the following represent the CORRECT statements regarding the Amazon ML services?  (Select two) <br>
**日本語訳** <br>
Amazon MLサービスに関する記述として正しいものはどれですか？ <br>（2つ選択）
**選択肢** <br>
*   ✅ **Amazon Polly is used to deploy natural-sounding human voices** <br>Amazon Pollyは、数十の言語で高品質で自然な響きの人間のような音声を生成するために使用されます。
*   Amazon Transcribe is for building conversational interfaces
*   ✅ **Amazon Comprehend uses ML to find insights and relationships in text** <br>Amazon Comprehendサービスは、機械学習を使用してテキスト内の洞察や関連性を見つけ出します。
*   Amazon Comprehend converts speech to text
*   Amazon Rekognition organizes text files by topic <br>
**🐒 猿でもわかる解説** <br>
*   **Polly**：文字を音声（声）に変えます。 <br>
*   **Comprehend**：テキストの意味や関係性を分析します。 <br>
*   ❌ **Transcribe**：声を文字にするサービス（Lexが会話インターフェース担当）です。 <br>
*   ❌ **Rekognition**：画像・動画用です。 <br>
**🧠 暗記方法** <br>
👉 「Polly＝おしゃべり」「Comprehend＝理解」

---

**問題11：強化学習（RL）の仕組み** <br>
**English Question (Original)** <br>
How does reinforcement learning work? <br>
**日本語訳** <br>
強化学習（Reinforcement Learning）はどのように動作しますか？ <br>
**選択肢** <br>
*   ✅ **Reinforcement learning involves an agent interacting with an environment, receiving rewards or penalties to maximize cumulative rewards** <br>強化学習とは、エージェントが環境と相互作用し、報酬や罰則を受け取りながら、累積報酬を最大化することを目指す学習方法である。
*   Relies on unsupervised learning to cluster data points
*   Uses supervised learning to label data
*   Transforms raw data to reduce dimensionality <br>
**🐒 猿でもわかる解説** <br>
*   **アメとムチ**：ロボット（エージェント）が行動し、報酬（アメ）をもらうことで「どうすれば得か」を学びます。 <br>
*   ❌ **教師あり学習**：正解ラベルを与える学習方法です。 <br>
**🧠 暗記方法** <br>
👉 「強化学習＝報酬（Rewards）と行動」

---

**問題12：Amazon Personalizeの説明**
**English Question (Original)**
Which statement best describes the Amazon Personalize service? <br>
**日本語訳** <br>
Amazon Personalizeサービスの説明として最も適切なものは？ <br>
**選択肢** <br>
*   Derive insights from text within documents
*   Automatically convert speech to text
*   ✅ **Elevate the customer experience with ML-powered personalization** <br>機械学習を活用したパーソナライゼーションで顧客体験を向上させましょう。
*   Deploy natural-sounding human voices <br>
**🐒 猿でもわかる解説** <br>
*   **レコメンドのプロ**：ユーザーの過去の行動（購入履歴など）から、その人にぴったりの商品を提案します。 <br>
*   ❌ **Polly/Transcribe/Comprehend**：これらは音声や文章の解析用です。 <br>
**🧠 暗記方法** <br>
👉 「Personalize＝パーソナライズ（おすすめ）」

---

**問題13：AWSグローバルインフラ（2つ選択）** <br>
**English Question (Original)** <br>
Which of the following are correct statements regarding the AWS Global Infrastructure? <br> (Select two)
**日本語訳** <br>
AWSグローバルインフラストラクチャに関する正しい記述は？ <br>（2つ選択）
**選択肢** <br>
*   ✅ **Each Availability Zone (AZ) consists of one or more discrete data centers**
*   Each AWS Region consists of a minimum of two AZs
*   Each AZ consists of two or more data centers
*   ✅ **Each AWS Region consists of a minimum of three AZs**
*   Each Region consists of two or more Edge Locations
**🐒 猿でもわかる解説** <br>
*   **リージョン**：地理的なエリアで、その中に**最低3つ**のAZがあります。 <br>
*   **AZ**：1つ以上のデータセンターが集まったものです。 <br>
**🧠 暗記方法** <br>
👉 「1リージョン＝最低3AZ」「1AZ＝1つ以上のデータセンター」

---

**問題14：Amazon Bedrockのコスト最小化** <br>
**English Question (Original)** <br>
Which approach would be the most effective in minimizing the costs associated with model usage on Amazon Bedrock? <br>
**日本語訳** <br>
Amazon Bedrockのモデル利用コストを最小限に抑える最も効果的な方法は？ <br>
**選択肢** <br>
*   ✅ **The company should reduce the number of tokens in the input** <br>会社は入力に含まれるトークンの数を減らすべきだ。
*   The company should reduce the batch size while training
*   The company should reduce the temperature parameter
*   The company should reduce the top-P parameter <br>
**🐒 猿でもわかる解説** <br>
*   **トークン課金**：Bedrockの料金は処理した「トークン数」で決まります。 <br>入力を短くすれば安くなります。 <br>
*   ❌ **Temperature/Top-P**：これらは回答の「質（多様性）」を変える設定で、料金には関係ありません。 <br>
**🧠 暗記方法** <br>
👉 「コスト削減＝トークンを減らす」

---

**問題15：Amazon Bedrockの可視化ログ** <br>
**English Question (Original)** <br>
Which of the following solutions would be the most suitable for providing detailed visibility into all model invocations? <br>
**日本語訳** <br>
モデル呼び出しの詳細な可視化（入力・出力の監視）に最適なソリューションは？ <br>
**選択肢** <br>
*   ✅ **The company should enable model invocation logging, which allows for detailed logging of all requests and responses during model invocations in Amazon Bedrock** <br>同社は、Amazon Bedrockにおけるモデル呼び出し時のすべてのリクエストとレスポンスを詳細に記録できる、モデル呼び出しログ機能を有効にするべきです。
*   Analyze events in Amazon EventBridge
*   Use AWS CloudTrail logs for API calls
*   Use AWS Config to monitor configurations <br>
**🐒 猿でもわかる解説** <br>
*   **モデル呼び出しログ**：これを有効にすると「何を入力して、AIが何と答えたか」の中身まで記録できます。 <br
*   ❌ **CloudTrail**：APIを「いつ、誰が叩いたか」は分かりますが、中身（データ）までは見えません。 <br>
**🧠 暗記方法** <br>
👉 「推論の中身を見る＝Invocation Logging」

---

**問題16：LLM開発に推奨されるサービス（2つ選択）** <br>
**English Question (Original)**
Which AWS services would you recommend for developing LLM-based solutions? <br> (Select two) <br>
**日本語訳** <br>
大規模言語モデル（LLM）ベースのソリューション開発に推奨されるサービスは？ <br>（2つ選択）
**選択肢** <br>
*   AWS Trainium
*   ✅ **Amazon Bedrock**
*   ✅ **Amazon SageMaker JumpStart**
*   Amazon Q <br>
*   AWS Inferentia <br>
**🐒 猿でもわかる解説** <br>
*   **Bedrock**：API経由で簡単に最新モデルを使えます。 <br>
*   **JumpStart**：モデルのハブで、事前学習済みモデルをすぐにデプロイ・微調整できます。 <br>
*   ❌ **Trainium/Inferentia**：これらはチップ（ハードウェア）そのものです。 <br>
**🧠 暗記方法** <br>
👉 「LLM開発＝Bedrock ＆ JumpStart」

---

**問題17：AWS責任共有モデル** <br>
**English Question (Original)** <br>
In the context of the shared responsibility model, which of the following best describes the division of responsibilities? <br>
**日本語訳** <br>
AWS責任共有モデルにおける、責任の分担を正しく説明しているのは？ <br>
**選択肢** <br>
*   AWS is responsible for app security, customer for hardware
*   AWS handles all security including encryption
*   Customers are responsible for physical security of data centers
*   ✅ **AWS is responsible for the security "of" the cloud, while the customer is responsible for security "in" the cloud** <br>
**🐒 猿でもわかる解説** <br>
*   **AWSの責任**：クラウドを支える「インフラ（箱）」を守ること。 <br>
*   **顧客の責任**：クラウドの中に入れる「データやアプリ」を守ること。 <br>
**🧠 暗記方法** <br>
👉 「AWSはクラウドの箱を守る、客は中身を守る」

---

**問題18：コンピュータビジョン（CV）の推奨サービス** <br>
**English Question (Original)** <br>
What do you suggest for pre-trained and customizable computer vision (CV) capabilities? <br>
**日本語訳** <br>
事前学習済みでカスタマイズ可能なコンピュータビジョン（画像認識）機能はどれ？ <br>
**選択肢** <br>
*   Amazon Textract
*   ✅ **Amazon Rekognition**
*   Amazon SageMaker
*   Amazon DeepRacer <br>
**🐒 猿でもわかる解説** <br>
*   **Rekognition**：写真や動画の中の物体・顔・テキストを検知するCVのプロです。 <br>
*   ❌ **Textract**：ドキュメントからの文字抽出に特化しています。 <br>
**🧠 暗記方法** <br>
👉 「画像認識（CV）＝Rekognition」

---

**問題19：在庫監視・再注文の自動化（エージェント）** <br>
**English Question (Original)** <br>
A company aims to create a generative AI application that automates the monitoring of inventory and recommends optimal reorder points. What do you recommend? <br>
**日本語訳** <br>
在庫を監視し、最適な再注文タイミングを自動で推奨する生成AIアプリを作るには？ <br>
**選択肢** <br>
*   ✅ **Agents for Amazon Bedrock**
*   Knowledge Bases for Amazon Bedrock
*   Watermark detection for Amazon Bedrock
*   Guardrails for Amazon Bedrock <br>
**🐒 猿でもわかる解説** <br>
*   **エージェント**：複数のステップ（在庫確認→計算→注文）を「自律的に」こなす機能です。 <br>
*   ❌ **Knowledge Bases**：検索（RAG）用です。 <br>
*   ❌ **Guardrails**：不適切な発言を防ぐフィルターです。 <br>
**🧠 暗記方法** <br>
👉 「AIがタスクを自動実行＝Agents」

---

**問題20：分類モデルの評価（混同行列）** <br>
**English Question (Original)** <br>
Which of the following options would be the most suitable for assessing the performance of the classification model? <br>
**日本語訳** <br>
分類モデルの精度やエラーを詳しく分析するのに最適な方法は？ <br>
**選択肢** <br>
*   Root Mean Squared Error (RMSE)
*   ✅ **Confusion matrix**
*   Mean Absolute Error (MAE)
*   Correlation matrix <br>
**🐒 猿でもわかる解説** <br>
*   **混同行列**：どのカテゴリをどのカテゴリと「間違えた」かが一目で分かる表です。 <br>
*   ❌ **RMSE/MAE**：これらは「数値予測（回帰）」の誤差を測るものです。 <br>
**🧠 暗記方法** <br>
👉 「分類の評価＝混同行列（Confusion matrix）」

---

**問題21：モデル推論とモデル評価の違い** <br>
**English Question (Original)** <br>
Which of the following options best summarizes the differences between model inference and model evaluation in the context of generative AI? <br>
**日本語訳** <br>
生成AIにおける「モデル推論（Inference）」と「モデル評価（Evaluation）」の違いを最もよくまとめているのはどれですか？ <br>
**選択肢** <br>
*  Both model inference and model evaluation refer to the process of a model generating an output (response) from a given input (prompt)
*   ✅ **Model evaluation is the process of evaluating and comparing model outputs to determine the model that is best suited for a use case, whereas, model inference is the process of a model generating an output (response) from a given input (prompt)** <br>モデル評価とは、モデルの出力を評価および比較して、特定のユースケースに最適なモデルを決定するプロセスであり、一方、モデル推論とは、モデルが与えられた入力（プロンプト）から出力（応答）を生成するプロセスである。
*   Model inference is the process of evaluating and comparing model outputs to determine the model that is best suited for a use case, whereas, model evaluation is the process of a model generating an output (response) from a given input (prompt)
*   Both model inference and model evaluation refer to the process of evaluating and comparing model outputs to determine the model that is best suited for a use case <br>
**🐒 猿でもわかる解説** <br>
*   **モデル推論**：AIに質問して「答えを出してもらう」ことそのものです。 <br>
*   **モデル評価**：出された答えがどれくらい正しいか、どのAIが一番優秀かを「テスト・比較」することです。 <br>
**🧠 暗記方法** <br>
👉 「推論＝AIが喋る」「評価＝人間が採点・比較する」

---

**問題22：SageMakerでのMLflowの役割** <br>
**English Question (Original)** <br>
Given this context, which statement best defines the use of MLflow with Amazon SageMaker? <br>
**日本語訳** <br>
Amazon SageMakerでMLflowを使用する目的を最も適切に説明しているのはどれですか？ <br>
**選択肢** <br>
*   Label data using human-in-the-loop
*   Perform automatic model tuning
*   ✅ **Manage machine learning experiments**
*   Leverage no-code ML <br>
**🐒 猿でもわかる解説** <br>
*   **MLflow**：機械学習の「実験（Experiment）」を管理するツールです。 <br>色々な設定で試した結果を記録・比較して、一番良いものを見つけるのに役立ちます。 <br>
*   ❌ **Ground Truth**：データのラベル付け用です。 <br>
*   ❌ **Canvas**：ノーコードML用です。 <br>
**🧠 暗記方法** <br>
👉 「MLflow＝実験（Experiment）の整理棚」

---

**問題23：生成AI（Generative AI）の定義** <br>
**English Question (Original)** <br>
Which of the following best describes generative AI? <br>
**日本語訳** <br>
生成AI（Generative AI）を最もよく説明しているのはどれですか？ <br>
**選択肢** <br>
*   ✅ **Generative AI encompasses models and algorithms capable of creating new content such as text, images, and audio based on patterns learned from existing data**
*   Refers to AI systems limited to performing predefined tasks
*   Focuses exclusively on improving data retrieval efficiency
*   Analyzes existing data to generate insights without creating new content <br>
**🐒 猿でもわかる解説** <br>
*   **生成AI**：既存のデータからパターンを学び、テキストや画像、音楽などの「新しいコンテンツ」を自ら作り出すAIのことです。 <br>
*   ❌ **分析のみ**：新しいものを作らないのは従来のAI（識別系など）です。 <br>
**🧠 暗記方法** <br>
👉 「生成（Generate）＝新しいものを作る」

---

**問題24：特徴量の寄与を説明するサービス** <br>
**English Question (Original)** <br>
Which of the following services is specifically designed to provide insights into model predictions by explaining how input features contribute to the final output? <br>
**日本語訳** <br>
入力データのどの要素（特徴量）が最終的な予測にどう影響したかを説明（可視化）するサービスはどれですか？ <br>
**選択肢** <br>
*   ✅ **Amazon SageMaker Clarify**
*   Amazon SageMaker Feature Store
*   Amazon SageMaker Canvas
*   Amazon SageMaker Model Monitor <br>
**🐒 猿でもわかる解説** <br>
*   **SageMaker Clarify**：モデルが「なぜその答えを出したのか」を説明（説明可能性）してくれます。 <br>Shapley値などを使って、どのデータが重要だったか教えてくれます。 <br>
*   ❌ **Feature Store**：データを保存・共有する場所です。 <br>
**🧠 暗記方法** <br>
👉 「Clarify（明確にする）＝AIの理由をはっきりさせる」

---

**問題25：Bedrockでのクリエイティブ設定** <br>
**English Question (Original)** <br>
What do you recommend to get more creative responses for the same prompt on Amazon Bedrock? <br>
**日本語訳** <br>
Amazon Bedrockで同じプロンプトに対してより「クリエイティブ（独創的）」な回答を得るには、どの設定を推奨しますか？ <br>
**選択肢** <br>
*   Use lower Temperature
*   Use lower Top-P
*   ✅ **Use higher Temperature to get more creative responses**
*   Use higher Top-P <br>
**🐒 猿でもわかる解説** <br>
*   **Temperature（温度）**：これを上げるとAIが「冒険」するようになり、回答に多様性とクリエイティビティが生まれます。 <br>
*   逆に、正確さや一貫性を求めるなら温度を下げます。 <br>
**🧠 暗記方法** <br>
👉 「温度（Temperature）が高い＝AIが熱くなってノリノリで答える」

---

**問題26：回答から機密情報を隠す方法** <br>
**English Question (Original)** <br>
What is the most efficient approach to ensure customized model's responses do not contain confidential information? <br>
**日本語訳** <br>
カスタマイズしたモデルの回答に機密情報が含まれないようにする、最も効率的な方法はどれですか？ <br>
**選択肢** <br>
*   Swap Amazon Bedrock with Amazon SageMaker
*   Use encryption to protect information in responses
*   Delete the model and fine-tune again without confidential data
*   ✅ **The company should mask the confidential information from the model responses by leveraging Amazon Bedrock Guardrails** <br>
**🐒 猿でもわかる解説** <br>
*   **Amazon Bedrock Guardrails**：これを使うと、回答に含まれる個人情報（PII）や機密情報をリアルタイムで「マスク（隠蔽）」できます。 <br>モデルを作り直す必要がないので非常に効率的です。 <br>
**🧠 暗記方法** <br>
👉 「情報の目隠し＝Guardrails」

---

**問題27：RAGに最適な検索用データベース** <br>
**English Question (Original)** <br>
Which database solution would be most appropriate for fast index lookups and similarity searches in a RAG framework? <br>
**日本語訳** <br>
RAG（検索拡張生成）フレームワークにおいて、高速な索引検索や「類似性検索」を行うのに最も適切なデータベースはどれですか？ <br>
**選択肢** <br>
*   The company should use Amazon DocumentDB (with MongoDB compatibility), a managed NoSQL document database service designed for storing semi-structured data to facilitate search capabilities
*   ✅ **The company should use Amazon OpenSearch Service, which is designed to provide fast search capabilities and supports full-text search, indexing, and similarity scoring** <br>同社は、高速な検索機能を提供するように設計されており、全文検索、インデックス作成、類似度スコアリングをサポートするAmazon OpenSearch Serviceを使用すべきです。
*   The company should use Amazon DynamoDB, a fully managed NoSQL database service that offers low-latency data retrieval to handle fast index lookups as well as search operations
*   The company should use Amazon Aurora, a managed relational database service that is optimized for high-performance transactional workloads that can be useful for search operations <br>
**🐒 猿でもわかる解説** <br>
*   **Amazon OpenSearch Service**：ベクトル検索や全文検索が得意で、RAGで「質問に近いデータ」を探し出すのに最適です。 <br>
*   ❌ **DynamoDB/Aurora**：一般的なデータ保存には強いですが、AI用の類似検索（ベクトル検索）専用ではありません。 <br>
**🧠 暗記方法** <br>
👉 「RAGの検索エンジン＝OpenSearch」

---

**問題28：事前に訓練されたモデルを別で使い回す手法** <br>
**English Question (Original)** <br>
the company wants these models to learn from each other by sharing the latest data insights and patterns discovered by each model.Given this objective, which approach would be the most suitable for achieving cross-model optimization? <br>
**日本語訳** <br>
あるタスクで学習済みのモデルを、関連する別のタスクの性能向上のために再利用する手法は何ですか？ <br>
**選択肢** <br>
*   The company should use reinforcement learning, a strategy where an agent learns to make decisions by interacting with an environment and receiving rewards or penalties based on its actions
*   The company should use self-supervised learning, a technique where the model learns patterns and representations from unlabeled data without relying on explicit supervision or labeled datasets
*   ✅ **The company should use transfer learning, a method where a model pre-trained on one task is adapted to improve performance on a different but related task by leveraging knowledge from the original task** <br>同社は転移学習を用いるべきだ。これは、あるタスクで事前に訓練されたモデルを、元のタスクから得られた知識を活用することで、別の関連するタスクにおけるパフォーマンスを向上させる手法である。
*   The company should use incremental training, an approach that allows models to be updated incrementally with new data without needing a complete retraining from scratch <br>
**🐒 猿でもわかる解説** <br>
*   **転移学習（Transfer learning）**：すでに基礎知識があるモデルを「転校」させて、新しい環境で少しだけ勉強し直させる手法です。 <br>ゼロから学習するよりずっと効率的です。 <br>
**🧠 暗記方法** <br>
👉 「Transfer（移動・転校）＝知識の使い回し」

---

**問題29：Amazon Q Developerのエンジン** <br>
**English Question (Original)** <br>
Which of the following AWS services powers Amazon Q Developer? <br>
**日本語訳** <br>
Amazon Q Developerのコア機能を支えているAWSサービスはどれですか？ <br>
**選択肢** <br>
*   Amazon Kendra
*   ✅ **Amazon Bedrock**
*   Amazon Q Apps
*   Amazon SageMaker Jumpstart <br>
**🐒 猿でもわかる解説** <br>
*   **Amazon Q Developer**：開発を助けてくれるAIですが、その中身（脳みそ）は **Amazon Bedrock** の基盤モデルによって動かされています。 <br>
**🧠 暗記方法** <br>
👉 「Qの脳みそ＝Bedrock」

---

**問題30：フューショット（few-shots）のプロンプト構成** <br>
**English Question (Original)** <br>
What type of data should be included in the few-shots examples to help the model recognize the correct user intent? <br>
**日本語訳** <br>
ユーザーの意図をAIに正しく理解させるための「フューショット（few-shots）」プロンプトには、どのようなデータを含めるべきですか？ <br>
**選択肢** <br>
*   Model-response along with correct user intent
*   User-input along with model-response
*   User-input along with correct model-response
*   ✅ **The data should include user-input along with the correct user intent, providing examples of user queries and the corresponding intent** <br>データには、ユーザー入力と正しいユーザー意図が含まれている必要があり、ユーザーの質問例とそれに対応する意図を示す必要があります。 <br>
**🐒 猿でもわかる解説** <br>
*   **フューショット**：AIに「例題」をいくつか見せる手法です。 <br>「ユーザーの入力例」と「その時の正解（意図）」をセットで教えることで、AIが学習します。 <br>
**🧠 暗記方法** <br>
👉 「例題＝入力 ＋ 正解」

---

**問題31：Amazon Q Businessの技術（2つ選択）** <br>
**English Question (Original)** <br>
Which of the following generative AI techniques are used in the Amazon Q Business web application workflow? <br> (Select two)
**日本語訳** <br>
Amazon Q Businessのワークフローで使用されている生成AI技術はどれですか？ <br>（2つ選択）
**選択肢** <br>
*   ✅ **Retrieval-Augmented Generation (RAG)**
*   Generative adversarial network (GAN)
*   Diffusion Model
*   ✅ **Large Language Model (LLM)**
*   Variational autoencoders (VAE) <br>
**🐒 猿でもわかる解説** <br>
*   **LLM**：言葉を生成する脳みそです。 <br>
*   **RAG**：社内の最新ドキュメントを探してきて、それを元に答える仕組みです。 <br>
**🧠 暗記方法** <br>
👉 「Amazon Q ＝ LLM（脳） ＋ RAG（社内データ検索）」

---

**問題32：Bedrockのカスタマイズ（ラベルの有無）** <br>
**English Question (Original)** <br>
Which of the following statements is correct regarding the model customization methods for Amazon Bedrock? <br>
**日本語訳** <br>
Amazon Bedrockのモデルカスタマイズ手法について、正しい説明はどれですか？ <br>
**選択肢** <br>
*   Continued pre-training uses labeled data to pre-train a model and fine-tuning also uses labeled data to train a model
*   Continued pre-training uses unlabeled data to pre-train a model and fine-tuning also uses unlabeled data to train a model
*   ✅ **Continued pre-training uses unlabeled data to pre-train a model, whereas, fine-tuning uses labeled data to train a model** <br>継続的な事前学習では、ラベル付けされていないデータを使用してモデルを事前学習させるのに対し、ファインチューニングでは、ラベル付けされたデータを使用してモデルを学習させる。
*   Continued pre-training uses labeled data to pre-train a model, whereas, fine-tuning uses unlabeled data to train a model <br>
**🐒 猿でもわかる解説** <br>
*   **継続的な事前学習**：ラベルのない大量のデータ（専門書など）を読ませて知識を深めます。 <br>
*   **微調整（Fine-tuning）**：正解ラベルが付いたデータで、「この質問にはこう答えて」と特定のタスクを教え込みます。 <br>
**🧠 暗記方法** <br>
👉 「継続学習＝本を読む（ラベルなし）」「微調整＝問題集を解く（ラベルあり）」

---

**問題33：FMとLLMの違い** <br>
**English Question (Original)** <br>
What is a key difference between Foundation Models (FMs) and Large Language Models (LLMs)? <br>
**日本語訳** <br>
基盤モデル（FM）と大規模言語モデル（LLM）の主な違いは何ですか？ <br>
**選択肢** <br>
*   ✅ **Foundation Models serve as a broad base for various AI applications by providing generalized capabilities, whereas Large Language Models are specialized for understanding and generating human language** <br>基礎モデルは、一般化された機能を提供することで、さまざまなAIアプリケーションの幅広い基盤として機能しますが、大規模言語モデルは
*   LLMs are pre-trained... FMs are built from scratch
*   FMs are for text only... LLMs for images
*   FMs are academic... LLMs are commercial <br>
**🐒 猿でもわかる解説** <br>
*   **基盤モデル（FM）**：テキスト、画像、音声など色々こなせる「万能な土台」です。 <br>
*   **大規模言語モデル（LLM）**：その中でも特に「人間の言葉」の理解と生成に特化したモデルです。 <br>
**🧠 暗記方法** <br>
👉 「FM＝何でも屋」「LLM＝言葉の専門家」

---

**問題34：バラバラなデータを一括検索するサービス** <br>
**English Question (Original)** <br>
Which Machine Learning powered AWS service offers a unified search solution connecting multiple data repositories and FAQs? <br>
**日本語訳** <br>
複数のリポジトリやFAQに接続し、従業員が答えを効率的に見つけられる「統一検索ソリューション」はどれですか？ <br>
**選択肢** <br>
*   Amazon SageMaker Data Wrangler
*   Amazon Textract
*   Amazon Comprehend
*   ✅ **Amazon Kendra** <br>
*   **🐒 猿でもわかる解説** <br>
*   **Amazon Kendra**：企業内の色々な場所（S3, SharePointなど）にあるドキュメントを、AI（自然言語）で検索できるようにする賢い検索エンジンです。 <br>
**🧠 暗記方法** <br>
👉 「社内ドキュメントのGoogle検索＝Kendra」

---

**問題35：探索的データ分析（EDA）のフェーズ** <br>
**English Question (Original)** <br>
Which phase of the data science process involves calculating statistical measures and using visualizations to uncover patterns? <br>
**日本語訳** <br>
統計量を計算したりグラフで見える化したりして、データのクセを調べるフェーズはどれですか？ <br>
**選択肢** <br>
*   Data Augmentation
*   Model Evaluation
*   ✅ **Exploratory Data Analysis (EDA)**
*   Data Preparation <br>
**🐒 猿でもわかる解説** <br>
*   **EDA（探索的データ分析）**：料理に例えると、材料（データ）が腐っていないか、どれくらいあるかを下調べする段階です。 <br>
*   統計量（平均、中央値など）やグラフ（ヒストグラムなど）を駆使します。 <br>
**🧠 暗記方法** <br>
👉 「分析前の下調べ＝EDA」

---

**問題36：データの偏り（サンプリングバイアス）** <br>
**English Question (Original)** <br>
Which type of bias is most likely responsible for the system disproportionately flagging individuals based on their ethnic group? <br>
**日本語訳** <br>
AIシステムが特定の民族グループを不当に多く検知してしまう場合、最も考えられるバイアスの種類は何ですか？ <br>
**選択肢** <br>
*   Observer bias
*   ✅ **Sampling bias** disproportionatelyデータの偏り　不均等
*   Measurement bias
*   Confirmation bias <br>
**🐒 猿でもわかる解説** <br>
*   **サンプリングバイアス**：学習データが世の中の現実を正しく反映しておらず、特定のグループのデータが多すぎたり少なすぎたりすることで起こる偏りです。 <br>
**🧠 暗記方法** <br>
👉 「データの集め方の偏り＝サンプリングバイアス」

---

**問題37：透明性の高い「決定木」** <br>
**English Question (Original)** <br>
Which of the following machine learning algorithms would be the most suitable for providing clear insights into how decisions are made? <br>
**日本語訳** <br>
AIが「どうやってその判断を下したか」が人間に分かりやすく、透明性が高いアルゴリズムはどれですか？ <br>
**選択肢** <br>
*   Support Vector Machines (SVMs)
*   ✅ **Decision Trees**
*   Neural Networks
*   Logistic Regression <br>
**🐒 猿でもわかる解説** <br>
*   **決定木（Decision Trees）**：YES/NOの枝分かれで判断していくため、プロセスが丸見えで非常に理解しやすい（解釈性が高い）のが特徴です。 <br>
*   ❌ **ニューラルネットワーク**：中身が複雑すぎて「ブラックボックス」と呼ばれます。 <br>
**🧠 暗記方法** <br>
👉 「理由が丸見え＝決定木」

---

**問題38：もっともらしい嘘（ハルシネーション）** <br>
**English Question (Original)** <br>
A Large Language Model (LLM) chatbot is generating responses that appear plausible but are actually incorrect. What is this phenomenon called? <br>
**日本語訳** <br>
LLMが「もっともらしいけれど、事実に反するデタラメ」を回答する現象を何と言いますか？ <br>
**選択肢** <br>
*   ✅ **Hallucination**
*   Data drift
*   Overfitting
*   Underfitting <br>
**🐒 猿でもわかる解説** <br>
*   **ハルシネーション（幻覚）**：AIが知らないことを、あたかも知っているかのように堂々と嘘をつく現象です。 <br>
**🧠 暗記方法** <br>
👉 「AIの自信満々な嘘＝幻覚（Hallucination）」

---

**問題39：Amazon QとAmazon Bedrockの違い（2つ選択）** <br>
**English Question (Original)** <br>
Which of the following represent the correct options for the core differences between Amazon Q and Amazon Bedrock? <br> (Select two)
**日本語訳** <br>
Amazon QとAmazon Bedrockの主な違いについて、正しい記述はどれですか？ <br>（2つ選択）
**選択肢** <br>
*   With Amazon Q, you can choose the FM... Bedrock does not
*   Bedrock is a pre-packaged assistant... Q is for building
*   Both are pre-packaged assistants
*   ✅ **With Amazon Bedrock, you can choose the underlying Foundation Model. However, Amazon Q does not allow you to choose the underlying Foundation Model** <br>Amazon Bedrockでは、基盤となるファウンデーションモデルを選択できます。しかし、Amazon Qでは基盤となるファウンデーションモデルを選択することはできません。
*   ✅ **Amazon Q is a generative AI–powered assistant that allows you to create pre-packaged apps, whereas, Amazon Bedrock provides an environment to build and scale applications** <br>Amazon Qは、生成AIを活用したアシスタントであり、事前にパッケージ化された生成AIアプリケーションを作成できます。一方、Amazon Bedrockは、基盤モデル（FM）を使用して生成AIアプリケーションを構築および拡張するための環境を提供します。 <br>
**🐒 猿でもわかる解説** <br>
*   **Bedrock**：色々なモデル（Claude, Llamaなど）を選んで「自分でアプリを作るための道具箱」です。 <br>
*   **Amazon Q**：すでにAIアシスタントとして完成されている「パッケージ品」です。 <br>
**🧠 暗記方法** <br>
👉 「Bedrock＝モデルを選べる工房」「Q＝モデルを選べない完成品アシスタント」

---

**問題40：Bedrockでのフル管理型RAG** <br>
**English Question (Original)** <br>
What solution or approach would you recommend for implementing fully managed support for a RAG workflow in Amazon Bedrock? <br>
**日本語訳** <br>
Amazon BedrockでRAG（検索拡張生成）のワークフローを、フル管理型で実装する機能はどれですか？ <br>
**選択肢** <br>
*   ✅ **Knowledge Bases for Amazon Bedrock**
*   Guardrails for Amazon Bedrock
*   Watermark detection for Amazon Bedrock
*   Continued pretraining in Amazon Bedrock <br>
**🐒 猿でもわかる解説** <br>
*   **Knowledge Bases（ナレッジベース）**：社内データを登録するだけで、検索から回答生成までのRAGの仕組みを丸ごと提供してくれます。 <br>
**🧠 暗記方法** <br>
👉 「RAGをやるなら＝ナレッジベース」

---

**問題41：良いプロンプトの構成要素** <br>
**English Question (Original)** <br>
What are the key constituents of a good prompting technique? <br>
**日本語訳** <br>
効果的なプロンプト（AIへの命令文）を構成する4つの主要な要素は何ですか？ <br>
**選択肢** <br>
*   Hyperparameters, Context, Input data, Output Indicator
*   ✅ **Instructions, Context, Input data, Output Indicator**
*   Instructions, Parameters, Input data, Output Indicator
*   Instructions, Hyperparameters, Input data, Output Indicator <br>
**🐒 猿でもわかる解説** <br>
*   **指示（Instructions）**：やってほしいこと。 <br>
*   **背景（Context）**：参考情報。 <br>
*   **入力データ（Input data）**：処理対象。 <br>
*   **出力指示（Output Indicator）**：フォーマット指定。 <br>
**🧠 暗記方法** <br>
👉 「指示・背景・材料・形式」のセットが基本。 <br>

---

**問題42：テキストの処理単位（トークン）** <br>
**English Question (Original)** <br>
What is the concept called to represent words, sub-words, or characters that the model processes as discrete units of text? <br>
**日本語訳** <br>
生成AIモデルがテキストを処理する際の最小単位（単語や文字の一部など）を何と呼びますか？ <br>
**選択肢** <br>
*   Vectors
*   Embeddings
*   ✅ **Tokens**
*   Context window <br>
**🐒 猿でもわかる解説** <br>
*   **トークン（Tokens）**：AIが言葉をバラバラにして理解するための「かけら」です。 <br>単語だったり、文字の組み合わせだったりします。 <br>
**🧠 暗記方法** <br>
👉 「AIの文字の数え方＝トークン」

---

**問題43：機械翻訳の精度指標（BLEU）** <br>
**English Question (Original)** <br>
Which metric would be most appropriate for assessing the accuracy of the translations? <br>
**日本語訳** <br>
機械翻訳がどれくらい正しいかを評価するのに最も適した指標はどれですか？ <br>
**選択肢** <br>
*   ROUGE
*   Accuracy
*   BERT score
*   ✅ **BLEU (Bilingual Evaluation Understudy) score** <br>
**🐒 猿でもわかる解説** <br>
*   **BLEUスコア**：翻訳の質を測るための定番指標です。 <br>人間が書いた「正解の翻訳」とどれくらい似ているかを数値化します。 <br>
*   ❌ **ROUGE**：主に「要約」の評価に使われます。 <br>
**🧠 暗記方法** <br>
👉 「翻訳のテスト結果＝BLEU」

---

**問題44：基盤モデルをドメイン専門家にする方法（2つ選択）** <br>
**English Question (Original)** <br>
Which of these approaches would be the most effective for turning the Foundation Model into a domain-specific expert? <br> (Select two)
**日本語訳** <br>
基盤モデルを特定の専門分野（ゲノム解析など）の「専門家」にするための最も効果的な方法は？ <br>（2つ選択）
**選択肢** <br>
*   Supervised Learning
*   ✅ **Domain Adaptation Fine-Tuning**
*   ✅ **Continued Pre-Training**
*   Reinforcement Learning
*   Incremental Learning <br>
**🐒 猿でもわかる解説** <br>
*   **継続的な事前学習（Continued Pre-Training）**：専門用語を大量に浴びせて知識を増やします。 <br>
*   **ドメイン適応微調整（Domain Adaptation Fine-Tuning）**：専門分野の特定のタスクができるように調整します。 <br>
**🧠 暗記方法** <br>
👉 「専門家にする＝継続学習 ＆ 微調整」

---

**問題45：Transformerモデルの仕組み** <br>
**English Question (Original)** <br>
Which of the following best summarizes the way Transformer models work? <br>
**日本語訳** <br>
Transformer（トランスフォーマー）モデルの動作原理を最もよく説明しているのはどれですか？ <br>
**選択肢** <br>
*   Learning a compact representation called latent space
*   Iteratively making controlled random changes
*   ✅ **Transformer models use a self-attention mechanism and implement contextual embeddings** <br>トランスフォーマーモデルは自己注意機構を使用し、文脈に応じた埋め込み表現を実装している。
*   Training two neural networks in a competitive manner <br>
**🐒 猿でもわかる解説** <br>
*   **Self-attention（自己注意）**：文の中のどの言葉が重要か、お互いの関係性を計算する仕組みです。 <br>これにより、言葉の「文脈（コンテキスト）」を深く理解できます。 <br>
**🧠 暗記方法** <br>
👉 「Transformer ＝ 自己注意（Attention）で文脈を読む」

---

**問題46：特定の情報を除外するプロンプト** <br>
**English Question (Original)** <br>
What type of prompting technique involves guiding a model to exclude competitive brand names or sensitive topics? <br>
**日本語訳** <br>
「競合他社の名前を出さないで」など、特定の情報を除外するように指示するプロンプト手法は何ですか？ <br>
**選択肢** <br>
*   Chain-of-thought prompting
*   Zero-shot Prompting
*   ✅ **Negative prompting**
*   Few-shot Prompting <br>
**🐒 猿でもわかる解説** <br>
*   **ネガティブプロンプト**：「〜しないで（NOT）」という禁止事項を伝えることで、AIの回答をコントロールします。 <br>
**🧠 暗記方法** <br>
👉 「禁止・除外＝ネガティブ（Negative）」

---

**問題47：教師あり学習の例（2つ選択）** <br>
**English Question (Original)** <br>
Which of the following are examples of supervised learning? <br> (Select two)
**日本語訳** <br>
教師あり学習（Supervised learning）の例はどれですか？ <br>（2つ選択）
**選択肢** <br>
*   Document classification
*   ✅ **Linear regression**
*   Clustering
*   Association rule learning
*   ✅ **Neural network** <br>
**🐒 猿でもわかる解説** <br>
*   **線形回帰（Linear regression）**：過去のデータ（正解あり）から数値を予測します。 <br>
*   **ニューラルネットワーク**：ラベル付きデータで学習する複雑なモデルの代表です。 <br>
*   ❌ **クラスタリング**：正解がないデータを分ける「教師なし学習」です。 <br>
**🧠 暗記方法** <br>
👉 「正解を見て学ぶ＝教師あり学習」

---

**問題48：AIの記憶の限界（コンテキストウィンドウ）** <br>
**English Question (Original)** <br>
What is this concept called that defines the maximum amount of text or characters the AI model can process at one time? <br>
**日本語訳** <br>
AIモデルが一度に処理・考慮できるテキストの最大量を何と呼びますか？ <br>
**選択肢** <br>
*   Tokens
*   Embeddings
*   Character count
*   ✅ **Context window:This concept is referred to as a context window, which determines the amount of text or information the model can consider at once while generating a response, typically measured in tokens rather than characters** <br>この概念はコンテキストウィンドウと呼ばれ、モデルが応答を生成する際に一度に考慮できるテキストまたは情報の量を決定するもので、通常は文字数ではなくトークン数で測定されます。 <br>
**🐒 猿でもわかる解説** <br>
*   **コンテキストウィンドウ**：AIが「一度に読める量（短期記憶の容量）」のようなものです。 <br>これを超えた分は忘れてしまいます。 <br>
**🧠 暗記方法** <br>
👉 「AIの視界・記憶の広さ＝ウィンドウ」

---

**問題49：電話の感情分析に適したサービス** <br>
**English Question (Original)** <br>
Which AWS services would you recommend for performing sentiment analysis for customer service audio calls? <br>
**日本語訳** <br>
カスタマーサービスの電話音声から感情分析を行うのに適した組み合わせはどれですか？ <br>
**選択肢** <br>
*   Amazon Rekognition and Amazon Transcribe
*   Amazon Translate and Amazon Comprehend
*   ✅ **Amazon Transcribe and Amazon Comprehend**
*   Amazon Transcribe and Amazon Translate <br>
**🐒 猿でもわかる解説** <br>
*   **Amazon Transcribe**：音声をテキスト（文字）に変換します。 <br>
*   **Amazon Comprehend**：そのテキストを分析して、ポジティブかネガティブか（感情）を判別します。 <br>
**🧠 暗記方法** <br>
👉 「耳（Transcribe） ＋ 心を読み取る脳（Comprehend）」

---

**問題50：微調整したモデルを使うための課金モード** <br>
**English Question (Original)** <br>
To test and deploy your fine-tuned model in Amazon Bedrock, which approach is most suitable? <br>
**日本語訳** <br>
Amazon Bedrockで微調整（Fine-tune）した自作モデルをテスト・公開する際に、必須となるモードは何ですか？ <br>
**選択肢** <br>
*   Batch inference
*   On-Demand mode
*   ✅ **Provisioned Throughput mode** <br>The company should use Provisioned Throughput mode, which allows the company to reserve a specific amount of capacity in advance <br>同社はプロビジョンドスループットモードを使用すべきです。このモードでは、企業は特定の容量を事前に予約することができます。
*   Amazon Bedrock playground <br>
**🐒 猿でもわかる解説** <br>
*   **プロビジョンドスループット（Provisioned Throughput）**：自作したカスタムモデルを動かすには、専用の計算能力を「予約（購入）」する必要があります。 <br>標準の従量課金（On-Demand）では使えません。 <br>
**🧠 暗記方法** <br>
👉 「自作モデル＝予約席（Provisioned）が必要」

---

**問題51：候補の「数」を絞る設定（Top K）** <br>
**English Question (Original)** <br>
Which inference parameter regulates the number of most-likely candidates considered for the next word? <br>
**日本語訳** <br>
次に続く単語の候補として考慮する「数（上位何個か）」を制限するパラメータはどれですか？ <br>
**選択肢** <br>
*   Top P
*   Stop sequences
*   Temperature
*   ✅ **Top K** <br>
**🐒 猿でもわかる解説** <br>
*   **Top K**：確率が高い単語を「上位K個（例：50個）」に絞り込んでから選ぶ設定です。 <br>
*   ❌ **Top P**：累積確率（例：上位75%まで）で絞ります。 <br>
**🧠 暗記方法** <br>
👉 「K ＝ 個数（数のK）」

---

**問題52：Amazon Forecastのユースケース** <br>
**English Question (Original)** <br>
Which of the following is the best-fit for the Amazon Forecast service? <br>
**日本語訳** <br>
Amazon Forecastサービスが最も適しているユースケースはどれですか？ <br>
**選択肢** <br>
*   Recommendations tailored to user behavior
*   Design conversational solutions for FAQs
*   Detect and categorize toxic audio
*   ✅ **Predict product demand to accurately vary inventory and pricing at different store locations** <br>製品需要を予測することで、各店舗の在庫と価格を正確に調整する。 <br>
**🐒 猿でもわかる解説** <br>
*   **Amazon Forecast**：時系列データ（過去の売上など）から、将来の需要を予測する専用のAIです。 <br>在庫管理の最適化などに使われます。 <br>
**🧠 暗記方法** <br>
👉 「需要予測（Forecast）＝在庫の未来を当てる」

---

**問題53：SageMaker JumpStartの特徴（2つ選択）** <br>
**English Question (Original)** <br>
Which of the following represent the key features of Amazon SageMaker JumpStart? <br> (Select two)
**日本語訳** <br>
Amazon SageMaker JumpStartの主な特徴はどれですか？ <br>（2つ選択）
**選択肢** <br>
*   Build ML models using a visual interface without code
*   Provides only public models
*   Training data will be used to train the base model
*   ✅ **Pre-trained models are fully customizable for your use case with your data** <br>事前学習済みモデルは、お客様のデータを使用して、お客様のユースケースに合わせて完全にカスタマイズ可能です。
*   ✅ **You can evaluate, compare, and select Foundation Models quickly based on pre-defined metrics** <br>事前定義された指標に基づいて、ファウンデーションモデルを迅速に評価、比較、選択できます。 <br>
**🐒 猿でもわかる解説** <br>
*   **モデルのデパート**：たくさんの事前学習済みモデルが揃っており、自分のデータでカスタマイズ（微調整）してすぐに使えます。 <br>
*   モデルの評価や比較も簡単に行えます。 <br>
**🧠 暗記方法** <br>
👉 「JumpStart＝モデルのハブ（評価・比較・即利用）」

---

**問題54：文脈理解のプロ（BERT）** <br>
**English Question (Original)** <br>
Which of the following embedding models would be most suitable for differentiating the contextual meanings of words? <br>
**日本語訳** <br>
同じ単語でも文脈によって意味が異なる（例：川の「バンク」と銀行の「バンク」）のを正確に見分けるのに適したモデルはどれですか？ <br>
**選択肢** <br>
*   Singular Value Decomposition (SVD)
*   Word2Vec
*   Principal Component Analysis (PCA)
*   ✅ **Bidirectional Encoder Representations from Transformers (BERT)** <br>
**🐒 猿でもわかる解説** <br>
*   **BERT**：文章を「双方向（Bidirectional）」から読み取ります。 <br>単語の前後を同時に見るので、文脈を捉える力が非常に強いです。 <br>
**🧠 暗記方法** <br>
👉 「文脈のプロ ＝ 前後を見るBERT」

---

**問題55：Shapley値（個別）とPDP（全体）の違い** <br>
**English Question (Original)** <br>
Which explanation BEST describes the differences between Shapley values and Partial Dependence Plots (PDP)? <br>
**日本語訳** <br>
Shapley値と部分依存プロット（PDP）の違いを正しく説明しているのはどれですか？ <br>
**選択肢** <br>
*   ✅ **Shapley values provide a local explanation by quantifying the contribution of each feature to the prediction for a specific instance, while PDP provides a global explanation by showing the marginal effect of a feature on the model’s predictions across the dataset. Use Shapley values to explain individual predictions and PDP to understand the model's behavior at a dataset level** <br>シャプレー値は、特定事例の予測に対する各特徴量の貢献度を定量化することで局所的な説明を提供し、一方、部分依存プロット（PDP）は、データセット全体におけるモデルの予測に対する特徴量の限界効果を示すことで全体的な説明を提供します。個々の予測を説明するにはシャプレー値を、データセットレベルでのモデルの挙動を理解するにはPDPを使用してください。
*   Both are global methods
*   Shapley is visual, PDP is numeric
*   Shapley is global, PDP is local <br>
**🐒 猿でもわかる解説** <br>
*   **Shapley値**：その「1件」のデータに対して、どの項目がどう効いたか（ローカルな説明）を示します。 <br>
*   **PDP**：データセット「全体」で、ある項目が変わると予測がどう変わるか（グローバルな説明）を示します。 <br>
**🧠 暗記方法** <br>
👉 「Shapley ＝ 個別の理由」「PDP ＝ 全体の傾向」

---

**問題56：BedrockナレッジベースのデフォルトDB** <br>
**English Question (Original)** <br>
Which is the default vector database supported by Knowledge Bases for Amazon Bedrock? <br>
**日本語訳** <br>
Amazon Bedrockのナレッジベースを作成する際、自分で用意しない場合に「デフォルト」で作成されるベクトルデータベースは何ですか？ <br>
**選択肢** <br>
*   MongoDB
*   ✅ **OpenSearch Serverless vector store**
*   Amazon Aurora
*   Redis Enterprise Cloud <br>
**🐒 猿でもわかる解説** <br>
*   ナレッジベースの設定時、既存のDBがない場合はAWSが裏側で **Amazon OpenSearch Serverless** のベクトルストアを自動的に用意してくれます。 <br>
**🧠 暗記方法** <br>
👉 「RAGのデフォルト箱 ＝ OpenSearch Serverless」

---

**問題57：PDFに基づいた回答を安価に行う方法** <br>
**English Question (Original)** <br>
Which of the following approaches represents the most cost-effective solution for current responses based on product catalog PDFs? <br>
**日本語訳** <br>
製品カタログ（PDF）の内容に基づいた回答を、最もコスト効率よく提供する方法はどれですか？ <br>
**選択肢** <br>
*   Attach all PDFs to each query
*   Fine-tune the LLM with PDF data
*   ✅ **Utilize a Retrieval-Augmented Generation (RAG) system by indexing all product catalog PDFs and configuring the LLM chatbot to reference this system for answering queries** <br>すべての製品カタログPDFをインデックス化し、LLMチャットボットがこのシステムを参照して質問に回答するように設定することで、検索拡張生成（RAG）システムを活用します。
*   Attach a single PDF to each query <br>
**🐒 猿でもわかる解説** <br>
*   **RAG（検索拡張生成）**：モデルを何度も学習（微調整）し直すのはお金がかかります。 <br>PDFを検索可能な状態にして、必要な時だけ「カンニング」させるRAGが最も安上がりです。 <br>
**🧠 暗記方法** <br>
👉 「最新データ ＋ 低コスト ＝ RAG（検索）」

---

**問題58：非同期推論（Asynchronous inference）** <br>
**English Question (Original)** <br>
Which inference method would be the most suitable for processing datasets < 1GB where immediate responses are not required? <br>
**日本語訳** <br>
データ量が1GB未満で、即時のレスポンス（リアルタイム性）が求められない場合に最適な推論方法はどれですか？ <br>
**選択肢** <br>
*   Serverless inference
*   Real-time inference
*   Batch inference
*   ✅ **Asynchronous inference** <br>
**🐒 猿でもわかる解説** <br>
*   **非同期推論**：リクエストをキュー（待ち行列）に入れて、順番に処理します。 <br>1GBまでのデータに対応でき、急がない処理ならこれが効率的です。 <br>
**🧠 暗記方法** <br>
👉 「急がない ＋ 1GB未満 ＝ 非同期（Async）」

---

**問題59：AWSのベストプラクティス提供ツール** <br>
**English Question (Original)** <br>
Which AWS tool provides recommendations for governance, cost savings, performance, and security? <br>
**日本語訳** <br>
AWS環境のセキュリティ、コスト、パフォーマンスなどをチェックし、ベストプラクティス（改善案）を提案してくれるツールはどれですか？ <br>
**選択肢** <br>
*   AWS Audit Manager
*   AWS Config
*   ✅ **AWS Trusted Advisor**
*   AWS CloudTrail <br>
**🐒 猿でもわかる解説** <br>
*   **AWS Trusted Advisor**：あなたのAWS利用状況を「信頼できるアドバイザー」としてチェックし、「ここをもっと安くできますよ」「ここが危険ですよ」と教えてくれます。 <br>
**🧠 暗記方法** <br>
👉 「AWSの健康診断 ＝ Trusted Advisor」

---

**問題60：SageMakerモデルダッシュボード** <br>
**English Question (Original)** <br>
Which Amazon SageMaker service can help track and manage deployed models effectively? <br>
**日本語訳** <br>
デプロイ済みの複数のモデルのパフォーマンスや利用状況を一元管理し、監視するのに役立つサービスはどれですか？ <br>
**選択肢** <br>
*   Amazon SageMaker Ground Truth
*   Amazon SageMaker JumpStart
*   Amazon SageMaker Clarify
*   ✅ **Amazon SageMaker Model Dashboard** <br>
**🐒 猿でもわかる解説** <br>
*   **Model Dashboard**：稼働中のモデルやエンドポイントが「ちゃんと動いているか」「リソースをどれくらい使っているか」をまとめて見れる管理画面です。 <br>
**🧠 暗記方法** <br>
👉 「動いてるモデルの監視板 ＝ モデルダッシュボード」

---

**問題61：客の反応から学び続ける（強化学習）** <br>
**English Question (Original)** <br>
Which approach is most suitable for enabling ongoing self-improvement of a chatbot based on customer interaction? <br>
**日本語訳** <br>
チャットボットが顧客との会話（フィードバック）からリアルタイムに学び、改善し続けるために最適な手法はどれですか？ <br>
**選択肢** <br>
*   ✅ **The company should leverage reinforcement learning (RL), where rewards are generated from positive customer feedback to train the chatbot in optimizing its responses** <br>同社は、強化学習（RL）を活用すべきだ。強化学習では、顧客からの肯定的なフィードバックから報酬が生成され、それに基づいてチャットボットが応答を最適化するように訓練される。
*   The company should leverage transfer learning
*   The company should leverage incremental training
*   The company should leverage supervised learning <br>
**🐒 猿でもわかる解説** <br>
*   **強化学習（RL）**：お客さんが「今の答え、良かったよ！」と反応してくれたらそれを「報酬」として受け取り、次はもっと良い答えを出せるように学習します。 <br>
**🧠 暗記方法** <br>
👉 「褒められて（報酬）伸びるAI ＝ 強化学習」

---

**問題62：不確実な量に適した「オンデマンド」** <br>
**English Question (Original)** <br>
Which pricing model is most appropriate for a company uncertain about its usage and avoiding long-term contracts? <br>
**日本語訳** <br>
どれくらい使うか分からず、長期契約もしたくない場合に最適な料金プランは何ですか？ <br>
**選択肢** <br>
*   ✅ **On-demand pricing:The company should opt for on-demand pricing, which allows it to pay only for the actual usage of resources without any long-term commitments** <br> 同社はオンデマンド料金体系を選択すべきだ。これにより、長期契約を結ぶことなく、実際に使用したリソース分だけを支払うことができる。
*   Spot instances
*   Reserved instances
*   Provisioned throughput <br>
**🐒 猿でもわかる解説** <br>
*   **オンデマンド料金**：使った分だけ支払う「従量課金」です。 <br>いつでもやめられるし、最初に大きな金額を払う必要もありません。 <br>
**🧠 暗記方法** <br>
👉 「とりあえず試すなら ＝ オンデマンド」

---

**問題63：高品質な正解データを作る（Ground Truth）** <br>
**English Question (Original)** <br>
Which Amazon SageMaker service helps build high-quality labeled training datasets? <br>
**日本語訳** <br>
機械学習の学習に必要な、高品質な「ラベル付き（正解付き）データ」を作成するのを助けるサービスはどれですか？ <br>
**選択肢** <br>
*   Amazon SageMaker Feature Store
*   Amazon SageMaker JumpStart
*   Amazon SageMaker Canvas
*   ✅ **Amazon SageMaker Ground Truth** <br>
**🐒 猿でもわかる解説** <br>
*   **SageMaker Ground Truth**：人間（クラウドワーカーや自社チーム）が画像やテキストに正解ラベルを貼る作業を効率化してくれるツールです。 <br>
**🧠 暗記方法** <br>
👉 「正解（ラベル）を作る ＝ Ground Truth」

---

**問題64：Amazon Rekognitionに向かない仕事** <br>
**English Question (Original)** <br>
Which of the following use cases is NOT the right fit for Amazon Rekognition? <br>
**日本語訳** <br>
Amazon Rekognitionのユースケースとして**不適切**なものはどれですか？ <br>
**選択肢** <br>
*   Searchable media libraries
*   Face-based user identity verification
*   ✅ **Enable multilingual user experiences in your applications**
*   Celebrity recognition <br>
**🐒 猿でもわかる解説** <br>
*   **Rekognition**は「画像や動画を見る目」です。 <br>
*   ❌ **多言語対応（翻訳）**：これは文字を翻訳する **Amazon Translate** の仕事です。 <br>
**🧠 暗記方法** <br>
👉 「Rekognitionは画像、翻訳はTranslate」

---

**問題65：確率の累積で絞る（Top P）** <br>
**English Question (Original)** <br>
How does the inference parameter Top P influence the model response for Amazon Bedrock? <br>
**日本語訳** <br>
推論パラメータ「Top P」は、Amazon Bedrockの回答にどのような影響を与えますか？ <br>
**選択肢** <br>
*   Specifies stop sequences
*   ✅ **Influences the percentage of most-likely candidates that the model considers for the next token**
*   Influences likelihood of lower-probability outputs (Temperature)
*   Influences the number of candidates (Top K) <br>
**🐒 猿でもわかる解説** <br>
*   **Top P**：単語を確率が高い順に並べて、「合計〇〇％（パーセンテージ）」になるまでの単語を候補にします。 <br>
*   ❌ **Top K**：パーセントではなく「個数」で絞ります。 <br>
**🧠 暗記方法** <br>
👉 「P ＝ Percentage（パーセントのP）」
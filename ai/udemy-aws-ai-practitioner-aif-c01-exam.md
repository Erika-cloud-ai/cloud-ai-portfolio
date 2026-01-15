# AWS AI Practitioner AIF-C01 Practice exam
| １st Time    | 2nd time    |  3rd Time   | 4th Time |
|:---------------|:-----------|:----------|:----------|
| 25% | 45%    | 85% |.   |


## 1 <br>
A legal research firm is seeking to implement a cutting-edge AI solution that can generate detailed responses to complex legal queries by retrieving relevant information from their extensive database of legal documents. The company wants to use Amazon Bedrock to deploy a fully managed solution that supports an end-to-end Retrieval Augmented Generation (RAG) workflow, ensuring that the AI can pull contextually accurate information and generate high-quality answers efficiently.
What solution or approach would you recommend for implementing fully managed support for a RAG workflow in Amazon Bedrock? <br>
<br>
ある法律調査会社は、膨大な法律文書データベースから関連情報を取得することで、複雑な法律上の質問に対して詳細な回答を生成できる最先端のAIソリューションの導入を目指しています。同社は、Amazon Bedrockを活用して、エンドツーエンドのRetrieval Augmented Generation（RAG）ワークフローをサポートするフルマネージドソリューションを導入し、AIが文脈に沿った正確な情報を取得し、高品質な回答を効率的に生成できるようにしたいと考えています。
Amazon BedrockでRAGワークフローのフルマネージドサポートを実現するには、どのようなソリューションまたはアプローチを推奨しますか？ <br>
* Answer <br>
***Knowledge Bases for Amazon Bedrock***

* Sumamary <br>
Amazon Bedrock × RAG <br>
大量の法律文書を検索して、それを元にAIが答えを作る（RAG）仕組みを、フルマネージドで使いたい。どれ？<br>
AIに「資料を調べさせてから答えさせたい」 <br>
でも 検索システム + AI + 管理 を自分で作るのは大変 <br>
<br>
Knowledge Bases は <br>
* 「資料を保存」 <br>
* 「必要な情報を探す」 <br>
* 「AIに渡す」 <br>
* 「答えを作る」 <br>
を 全部まとめてやってくれる <br>
つまり「AI用のカンニングペーパー倉庫」 <br>
<br>
**不正解**（超重要） <br>
Continued pretraining → モデル再学習（RAGじゃない） <br>
Guardrails → 安全対策 <br>
Watermark detection → 透かし検出 <br>

## 2 <br>

Match the following Amazon SageMaker services to the respective use cases:

A) SageMaker Data Wrangler

B) SageMaker Canvas

C) SageMaker Ground Truth

1) Harnessing human input across the ML lifecycle to improve the accuracy and relevancy of models

2) Offers 300+ pre-configured data transformations to prepare data for ML

3) No-code service with an intuitive, point-and-click interface <br>
<br>
* Answer <br>
***A-2, B-3, C-1*** <br>
<br>
* Sumamary <br>

| サービス           | 何する？      | イメージ      |
|:---------------|:-----------|:----------|
| Data  Wrangler | データ整理    | Excel職人 |
| Canvas         | ノーコードML    | マウスだけAI   |
| Ground Truth   | 人が正解付け | 人間先生  |
***
対応関係 <br>
A) Data Wrangler → ② データ変換 <br>
B) Canvas → ③ ノーコード <br>
C) Ground Truth → ① 人の力で精度UP <br>
***
🇬🇧 英語まとめ <br>
Data Wrangler → data preparation <br>
Canvas → no-code ML <br>
Ground Truth → human labeling <br>

## 3
As a developer specializing in Large Language Models (LLMs) at a technology company, you have been tasked with migrating the company’s AI infrastructure to AWS Cloud to support the development of LLM-based solutions for various applications, such as natural language processing, text generation, and chatbots. The company is looking for AWS services that offer robust support for training, deploying, and managing LLMs while ensuring scalability, security, and integration with other cloud services.
Which AWS services would you recommend for developing LLM-based solutions in this environment? (Select two)<br>
<br>
テクノロジー企業で大規模言語モデル（LLM）を専門とする開発者であるあなたは、自然言語処理、テキスト生成、チャットボットなど、さまざまなアプリケーション向けLLMベースソリューションの開発を支援するため、会社のAIインフラストラクチャをAWSクラウドに移行するよう指示されました。会社は、スケーラビリティ、セキュリティ、および他のクラウドサービスとの統合を確保しながら、LLMのトレーニング、デプロイ、管理を強力にサポートするAWSサービスを探しています。
この環境でLLMベースソリューションを開発するために、どのAWSサービスをお勧めしますか？（2つ選択してください） <br>
LLMを作るAWSサービス（2つ） <br>
<br>
* Answer <br>
***Amazon SageMaker JumpStart*** <br>
***Amazon Bedrock*** <br>
<br>
* Sumamary <br>
JumpStart → LLMのテンプレ＋学習＋デプロイ <br>
Bedrock → ChatGPTみたいなAIをすぐ使う <br>
<br>
なぜ他は違う？<br>
Amazon Q → ビジネス用AI（開発向けじゃない） <br>
Inferentia / Trainium → チップ（ハード） <br>
🇬🇧 英語まとめ <br>Services for training, deploying, and managing LLMs <br>
→ Bedrock & SageMaker系 <br>
## 4 <br>

A retail company is exploring advanced AI solutions to enhance customer experience by integrating both visual and textual data for tasks such as product recommendations, automated image tagging, and customer support. The team is considering using multimodal models, which can process and understand multiple types of input data, but they need a clear understanding of how these models work and their key advantages. To help make an informed decision, the company wants to clarify the capabilities of multimodal models.
Which of the following summarizes the capabilities of a multimodal model?<br>
<br>
ある小売企業は、商品レコメンデーション、画像自動タグ付け、顧客サポートといったタスクにおいて、視覚データとテキストデータの両方を統合することで顧客体験を向上させるため、高度なAIソリューションの導入を検討しています。チームは、複数の種類の入力データを処理・理解できるマルチモーダルモデルの利用を検討していますが、これらのモデルがどのように機能するのか、そしてその主な利点について明確に理解する必要があります。十分な情報に基づいた意思決定を行うために、同社はマルチモーダルモデルの能力を明確に把握したいと考えています。
どの選択肢が、マルチモーダルモデルの能力を最もよく要約していますか？ <br>
<br>
* Answer <br>
  ***A multimodal model can accept a mix of input types such as audio/text and create a mix of output types such as video/image*** <br>
  マルチモーダルモデルは、音声やテキストなどの複数の入力タイプを同時に受け入れ、ビデオや画像などの複数の出力タイプを生成することができる。
<br>
* Summary <br>
<br>
マルチモーダルモデルとは、
**「目・耳・口を全部持ったAI」** です。

* 文字を読む（text）
* 画像を見る（image）
* 音を聞く（audio）

👉 **全部まとめて理解できる** <br>
👉 **出力も文字・画像・動画など自由** <br>

つまり
**入力も複数OK、出力も複数OK** ← これが最大の特徴

---

**不正解**

* 「入力が1種類だけ」→ マルチじゃない
* 「出力が1種類だけ」→ もったいない

---

## 5 <br>

In the context of the shared responsibility model for AWS cloud services, which of the following best describes the division of responsibilities between the customer and AWS? <br>

AWSクラウドサービスにおける責任共有モデルについて、顧客とAWSの責任分担を最も適切に説明しているのはどれですか？ <br>

<br>

* Answer <br>
  ***AWS is responsible for the security "of" the cloud, while the customer is responsible for security "in" the cloud　including data, applications, and access management*** <br>
AWSは、インフラストラクチャ、ハードウェア、ソフトウェアなど、クラウド自体のセキュリティを担当し、一方、顧客はデータ、アプリケーション、アクセス管理など、クラウド内におけるセキュリティを担当します。
<br>

* Summary <br>
AWSクラウドは **賃貸マンション** だと思ってください。

* 🏢 建物・耐震・電気 → **AWSの責任**
* 🔑 鍵の管理・中の荷物 → **あなたの責任**

つまり

* AWS：**クラウドそのものの安全**
* ユーザー：**クラウドの中の使い方**<vr>
<br>
**不正解** <br>
* AWS is responsible for configuring and managing the security settings of the customer's applications, while the customer is responsible for the underlying hardware infrastructure <br>AWSは顧客のアプリケーションのセキュリティ設定の構成と管理を担当し、顧客は基盤となるハードウェアインフラストラクチャを担当します。
* AWS handles all security aspects including data encryption, user access management, and application security, while the customer only needs to manage their virtual machines <br>AWSはデータ暗号化、ユーザーアクセス管理、アプリケーションセキュリティなど、セキュリティに関するあらゆる側面を処理するため、顧客は仮想マシンの管理のみに集中できます。
* Customers are responsible for ensuring the physical security of data centers, while AWS is responsible for monitoring network traffic and managing user identities <br>顧客はデータセンターの物理的なセキュリティを確保する責任があり、AWSはネットワークトラフィックの監視とユーザーIDの管理を担当します。
---

**不正解**
* AWS handles all security aspects including data encryption, user access management, and application security, while the customer only needs to manage their virtual machines <br>
AWSはデータ暗号化、ユーザーアクセス管理、アプリケーションセキュリティなど、セキュリティに関するあらゆる側面を処理するため、顧客は仮想マシンの管理のみに集中できます。 <br>
*AWS is responsible for configuring and managing the security settings of the customer's applications, while the customer is responsible for the underlying hardware infrastructure <br>
AWSは顧客のアプリケーションのセキュリティ設定の構成と管理を担当し、顧客は基盤となるハードウェアインフラストラクチャを担当します。<br>
Customers are responsible for ensuring the physical security of data centers, while AWS is responsible for monitoring network traffic and managing user identities<br>
顧客はデータセンターの物理的なセキュリティを確保する責任があり、AWSはネットワークトラフィックの監視とユーザーIDの管理を担当します。<br>

----

## 6 <br>

A healthcare company is implementing a machine learning solution to predict patient outcomes and improve treatment plans. The data science team is working to structure their workflow effectively, ensuring that they follow the correct steps in the machine learning process. Understanding the proper sequence of these steps will help the team streamline their project and ensure a successful implementation.
Given this context, which of the following would you recommend as the correct sequence of steps in the machine learning process? <br>
<br>
ある医療関連企業は、患者の予後を予測し、治療計画を改善するために機械学習ソリューションを導入しようとしています。データサイエンスチームは、機械学習プロセスにおける正しい手順を確実に実行できるよう、ワークフローの構築に取り組んでいます。これらの手順の適切な順序を理解することは、チームがプロジェクトを効率化し、導入を成功させる上で非常に重要です。
この状況を踏まえ、機械学習プロセスにおける正しい手順の順序として、以下のうちどれを推奨しますか？機械学習プロセスの正しい手順として推奨されるのはどれですか？ <br>

<br>

* Answer <br>
  ***Data collection → Data preprocessing → Model training → Model evaluation*** <br>データ収集、データ前処理、モデル学習、モデル評価

<br>

* Summary <br>
機械学習は **料理** と同じ 🍳

1. 🛒 材料を集める（Data collection）
2. 🔪 下ごしらえ（Preprocessing）
3. 🍳 料理する（Training）
4. 👅 味見（Evaluation）

👉 いきなり料理はできない！ <br>
<br>
 **不正解** <br>
* Data preprocessing, Model evaluation, Model training, Data collection <br>データ前処理、モデル評価、モデルトレーニング、データ収集 <br>
* Model evaluation, Model training, Data collection, Data preprocessing <br>
モデル評価、モデルトレーニング、データ収集、データ前処理 <br>
* Model training, Data collection, Data preprocessing, Model evaluation <br>モデル学習、データ収集、データ前処理、モデル評価 <br>
---

## 7 <br>

Which of the following are correct statements regarding the AWS Global Infrastructure? (Select two) <br>

AWSのグローバルインフラストラクチャについて正しいものはどれですか？（2つ選択） <br>

<br>

* Answer <br>
  ***Each AWS Region consists of a minimum of three Availability Zones (AZ)*** <br>各AWSリージョンは、最低3つのアベイラビリティゾーン（AZ）で構成されています。 <br>
  ***Each Availability Zone (AZ) consists of one or more discrete data centers*** <br>1つ以上の独立したデータセンターで構成される

<br>

* Summary <br>
AWSの世界構造 🌍

* Region → 国・都道府県
* AZ → 市
* Data Center → 建物

だから

* Region には **複数AZ**
* AZ には **1つ以上のデータセンター** <br>
<br>
**不正解** <br>
* Each AWS Region consists of two or more Edge Locations <br>各AWSリージョンは、2つ以上のエッジロケーションで構成されています。
* Each AWS Region consists of a minimum of two Availability Zones (AZ) <br>各AWSリージョンは、最低2つのアベイラビリティゾーン（AZ）で構成されています。
* Each Availability Zone (AZ) consists of two or more discrete data centers <br>各アベイラビリティゾーン（AZ）は、2つ以上の独立したデータセンターで構成されています。

---

## 8 <br>

A financial services company is exploring Amazon Bedrock to streamline its AI development for use cases such as fraud detection, personalized customer service, and automated reporting. The company is particularly interested in understanding the key features and benefits of Amazon Bedrock, including its ability to simplify access to powerful foundation models, support customizations, and integrate with existing AWS services.
To make an informed decision, the company needs to identify which of the following accurately applies to Amazon Bedrock and its capabilities? (Select two) <br>ある金融サービス企業は、不正検出、パーソナライズされた顧客サービス、自動レポート作成といったユースケースにおけるAI開発を効率化するために、Amazon Bedrockの導入を検討しています。同社は特に、強力な基盤モデルへのアクセスを簡素化する機能、カスタマイズへの対応、既存のAWSサービスとの統合など、Amazon Bedrockの主要な機能と利点について理解を深めたいと考えています。
十分な情報に基づいた意思決定を行うために、同社は以下の選択肢のうち、Amazon Bedrockとその機能について正確に説明しているものを2つ選択する必要があります。
次のうち、Amazon Bedrockの特徴として正しいものはどれですか？（2つ選択） <br>

<br>

* Answer <br>
  ***Smaller models are cheaper to use than larger models*** <br>小型モデルは大型モデルよりも使用料金が安価です。 <br>
  ***You can use a customized model in the Provisioned Throughput or On-Demand mode*** <br>
カスタマイズされたモデルは、プロビジョニング済みスループットモードまたはオンデマンドモードで使用できます。

<br>

* Summary <br>
* 🧠 小さい脳 → 電気代安い
* 🧠 大きい脳 → 電気代高い

Bedrockは
* すぐ使う → On-Demand
* 予約して安定 → Provisioned <br>
👉 **カスタムモデルでも両方OK** <br>
<br>
**不正解** <br>
* You can use a customized model in the Provisioned Throughput or On-Demand mode <br>カスタマイズされたモデルは、プロビジョニング済みスループットモードまたはオンデマンドモードで使用できます。
* You can use the On-Demand mode only with time-based term commitments <br>オンデマンドモードは、時間ベースの契約期間でのみ使用できます。
* Larger models are cheaper to use than smaller models <br>大規模モデルは小規模モデルよりも使用料金が安くなります。

---

## 9 <br>

Which of the following best describes the Amazon SageMaker Canvas ML tool? <br>

Amazon SageMaker Canvasを最もよく表しているのはどれですか？ <br>

<br>

* Answer <br>
  ***Gives the ability to use machine learning to generate predictions without the need to write any code*** <br>機械学習を使用して予測を生成する際に、コードを一切記述する必要なく、その機能を利用できるようにします。

<br>

* Summary <br>
Canvas = **コード禁止のAI**

* プログラミング不要
* クリックだけ
* Excel感覚

👉 非エンジニア向けMLツール <br>
<br>
**不正解** <br>
* Provides one-click, end-to-end solutions for many common machine learning use cases <br>多くの一般的な機械学習ユースケースに対し、ワンクリックでエンドツーエンドのソリューションを提供します。
* The fastest and easiest way to prepare tabular and image data for machine learning <br>機械学習のために表形式データと画像データを準備する最速かつ最も簡単な方法
* Explains how input features contribute to the model predictions during model development and inference <br>モデル開発時および推論時において、入力特徴量がモデルの予測結果にどのように貢献しているかを説明します。

---

## 10 <br>

The marketing department at a media company wants to leverage Amazon Bedrock for making creative scripts for an upcoming ad campaign.
What do you recommend?<br>あるメディア企業のマーケティング部門は、今後の広告キャンペーンのためにクリエイティブなスクリプトを作成する目的で、Amazon Bedrockを活用したいと考えています。
どのような方法をお勧めしますか？

Amazon Bedrockでより創造的な文章を生成するために推奨される設定はどれですか？ <br>

<br>

* Answer <br>
  ***Use higher Temperature to get more creative responses*** <br>

<br>

* Summary <br>
* Temperature 低 → 真面目・安定
* Temperature 高 → ノリノリ・創作向き 🎨

👉 **クリエイティブ = Temperature 高** <br>
<br>
**不正解** <br>
* Use lower Top-P to get more creative responses for the same prompt on Amazon Bedrock <br>Amazon Bedrockで同じプロンプトに対してより創造的な応答を得るには、Top-Pの値を低く設定してください。
* Use lower Temperature to get more creative responses for the same prompt on Amazon Bedrock <br>Amazon Bedrockで同じプロンプトに対してより創造的な応答を得るには、温度設定を低くしてください。
* Use higher Top-P to get more creative responses for the same prompt on Amazon Bedrock <br>Amazon Bedrockで同じプロンプトに対してより創造的な応答を得るには、Top-Pの値を高く設定してください。
---

## 11 <br>

A retail company is embarking on a machine learning project to enhance customer segmentation and personalize marketing campaigns. As the data science team begins planning the implementation, the team wants to identify the primary challenges in machine learning implementation. Understanding these challenges will help the team anticipate potential roadblocks and develop strategies to overcome them.
Which of the following represents the best option for the given use case?<br>ある小売企業は、顧客セグメンテーションを強化し、マーケティングキャンペーンをパーソナライズするために、機械学習プロジェクトに着手しようとしています。データサイエンスチームは実装計画を立て始めるにあたり、機械学習の実装における主要な課題を特定したいと考えています。これらの課題を理解することで、チームは潜在的な障害を予測し、それらを克服するための戦略を策定することができます。
以下の選択肢のうち、このユースケースに最適なものはどれでしょうか？
機械学習実装における主な課題はどれですか？ <br>

<br>

* Answer <br>
  ***Difficulty in collecting and preparing high-quality data*** <br>モデルのトレーニングに必要な高品質データの収集と準備が困難である。

<br>

* Summary <br>
AIは賢い
でも **エサ（データ）が悪いとバカになる**

👉 ML最大の敵 = **データ不足・データ汚い** <br>
<br>
**不正解**
* Limited applications of machine learning in real-world scenarios <br>機械学習の現実世界における応用事例は限られている。
* Insufficient computational power to run basic machine learning models <br>Insufficient computational power to run basic machine learning models
* Lack of available machine learning algorithms <br>利用可能な機械学習アルゴリズムの不足

---

## 12 <br>

A healthcare company has deployed a machine learning model using Amazon SageMaker to predict patient health outcomes based on various clinical parameters. A data analyst at the company inputs new patient data, such as age, blood pressure, and cholesterol levels, into the SageMaker model to receive a prediction on the likelihood of a cardiovascular event. The analyst needs to understand the specific term for this process, where the trained model uses its learned patterns to provide a prediction or output based on new input data.
What is this term called? <br>ある医療関連企業は、Amazon SageMaker を使用して機械学習モデルを導入し、様々な臨床パラメータに基づいて患者の健康状態を予測しています。同社のデータアナリストは、年齢、血圧、コレステロール値などの新しい患者データを SageMaker モデルに入力し、心血管疾患の発症リスクに関する予測結果を受け取ります。アナリストは、訓練済みのモデルが学習したパターンを用いて新しい入力データに基づいて予測や出力を行う、このプロセスを表す専門用語を知りたいと考えています。
この用語は何と呼ばれますか？
学習済みモデルが新しいデータから予測を行うプロセスは何と呼ばれますか？ <br>このプロセスは推論と呼ばれ、モデルは学習済みのパラメータを使用して、ユーザーから提供された新しい入力データに基づいて予測または出力を生成します。

<br>

* Answer <br>
  ***Inference推論:This process is called inference, where the model uses its trained parameters to generate a prediction or output based on new input data provided by the user*** <br>このプロセスは推論と呼ばれ、モデルは学習済みのパラメータを使用して、ユーザーから提供された新しい入力データに基づいて予測または出力を生成します。

<br>

* Summary <br>
* 勉強 → Training
* 成績チェック → Evaluation
* 実際に使う → **Inference**

👉 本番利用 = Inference <br>
<br>
**不正解**
* This process is called testing, which involves assessing the model's final performance on an unseen dataset after training is complete to estimate its generalization ability to predict an output <br>このプロセスはテストと呼ばれ、トレーニング完了後に未知のデータセットを用いてモデルの最終的な性能を評価し、出力予測における汎化能力を推定するものです。
* This process is referred to as validation, here the model uses its trained parameters to generate a prediction or output based on new input data provided by the user <br>このプロセスは検証と呼ばれ、ここではモデルが学習済みのパラメータを使用して、ユーザーから提供された新しい入力データに基づいて予測または出力を生成します。
* This process is known as training, which involves using labeled data to adjust the model's parameters so it can generate a prediction or output based on new input data provided by the user <br>このプロセスはトレーニングと呼ばれ、ラベル付けされたデータを使用してモデルのパラメータを調整することで、ユーザーから提供された新しい入力データに基づいて予測または出力を生成できるようにするものです。


---

## 13 <br>

A company is exploring Amazon Q to streamline its internal business processes through automation and generative AI capabilities. The team is particularly interested in understanding how Amazon Q integrates generative AI techniques within its web application workflow to enhance tasks such as automating report generation, creating summaries, and analyzing large datasets. They want to know which specific generative AI techniques are employed in Amazon Q to achieve these outcomes.
Which of the following generative AI techniques are used in the Amazon Q Business web application workflow? (Select two) <br>ある企業は、自動化と生成AI機能を活用して社内ビジネスプロセスを効率化するために、Amazon Qの導入を検討しています。特に、Amazon Qがウェブアプリケーションのワークフロー内で生成AI技術をどのように統合し、レポート作成の自動化、要約作成、大規模データセットの分析といったタスクを強化しているのかに関心を持っています。彼らは、これらの成果を達成するためにAmazon Qで具体的にどのような生成AI技術が使用されているのかを知りたいと考えています。
Amazon Q Businessのウェブアプリケーションワークフローで使用されている生成AI技術は次のうちどれですか？（2つ選択してください）
Amazon Q Businessのワークフローで使われている生成AI技術はどれですか？（2つ選択） <br>

<br>

* Answer <br>
  ***Large Language Model (LLM)*** <br>
  ***Retrieval-Augmented Generation (RAG)*** <br>

<br>

* Summary <br>
Amazon Qは

* 脳みそ → LLM
* 社内資料検索 → RAG

👉 「会社専用ChatGPT」 <br>
<br>
**不正解**
* Generative adversarial network (GAN) <br>
* Diffusion Model <br>
* Variational autoencoders (VAE)<br>
---

## 14 <br>
A financial services company is exploring machine learning to automate credit scoring and fraud detection. The leadership team, new to this technology, needs to understand the core concept behind machine learning. Gaining clarity on this central idea will help them decide how to best apply machine learning to their business operations. The company has tasked you, as an AI Practitioner, to convey the central idea behind machine learning to the leadership team.
What do you recommend? <br>ある金融サービス会社は、信用スコアリングと不正検出の自動化のために機械学習の導入を検討しています。この技術に不慣れな経営陣は、機械学習の基本概念を理解する必要があります。この中心的な考え方を明確に理解することで、機械学習を自社の事業運営にどのように最適に活用できるかを判断できるようになります。同社は、AI専門家であるあなたに、機械学習の基本概念を経営陣に説明するよう依頼しました。
あなたはどのような説明を提案しますか？
機械学習の中核となる考え方は何ですか？ <br>

<br>

* Answer <br>
  ***Machine learning involves training algorithms on large datasets to identify patterns and make predictions or decisions based on new data*** <br>機械学習とは、大量のデータセットを用いてアルゴリズムを訓練し、パターンを識別することである。

<br>

* Summary <br>
ルールを書く ❌ <br>
データから学ばせる ⭕ <br>

👉 **経験から学ぶAI** <br>
<br>
**不正解**
* Machine learning works by using predefined rules to generate outcomes without the need for data input<br>機械学習は、事前に定義されたルールを使用して、データ入力を必要とせずに結果を生成することで機能する。
* Machine learning is primarily based on hardware configurations and does not rely on software algorithms or data analysis <br>機械学習は主にハードウェア構成に基づいており、ソフトウェアアルゴリズムやデータ分析には依存しない。
* Machine learning only functions effectively when data is manually labeled and categorized by humans <br>機械学習は、データが人間によって手作業でラベル付けされ、分類された場合にのみ効果的に機能する。

---

## 15 <br>

A retail company is building a machine learning model to forecast demand for its products, but the data science team is facing challenges in balancing model complexity and accuracy. They are trying to avoid overfitting as well as underfitting, since understanding the differences between these two issues is crucial for optimizing the model's performance on both historical and unseen data.
How would you differentiate between overfitting and underfitting in the context of machine learning? <br>
ある小売企業は、自社製品の需要を予測するために機械学習モデルを構築していますが、データサイエンスチームはモデルの複雑さと精度とのバランスを取ることに苦慮しています。過学習と過小学習の両方を避ける必要があるため、これらの問題の違いを理解することが、過去のデータと未知のデータの両方におけるモデルのパフォーマンスを最適化する上で非常に重要です。
機械学習の文脈において、過学習と過小学習をどのように区別しますか？
過学習と未学習の違いは何ですか？ <br>

<br>

* Answer <br>
  ***Overfitting occurs when a model performs well on the training data but poorly on new, unseen data, while underfitting occurs when a model performs poorly on both the training data and new, unseen data*** <br>過学習とは、モデルが訓練データに対しては良好な性能を示すものの、新しい未知のデータに対しては性能が低下する現象であり、一方、過小適合とは、モデルが訓練データと新しい未知のデータの両方に対して性能が低い現象である。

<br>

* Summary <br>
* 過学習 → 暗記バカ <br>
* 未学習 → そもそも理解してない <br>
<br>
**不正解**
* Overfitting and underfitting both refer to a model performing equally well on both the training data and new, unseen data <br>過学習と過小学習はどちらも、モデルが訓練データと新しい未知のデータの両方に対して同程度の性能を発揮することを指します。
* Overfitting occurs when a model is too simple to capture the underlying patterns in the data, while underfitting occurs when a model is too complex and captures noise rather than the actual patterns <br>過学習とは、モデルが単純すぎてデータの根本的なパターンを捉えきれない場合に発生する現象であり、一方、過小適合とは、モデルが複雑すぎ、実際のパターンではなくノイズを捉えてしまう場合に発生する現象である。
* Overfitting is desirable as it ensures the model captures all nuances in the training data, while underfitting is desirable as it ensures the model generalizes well to new data <br>過学習は、モデルが訓練データ内のあらゆるニュアンスを捉えることを保証するため望ましい一方、過小適合は、モデルが新しいデータに対して適切に一般化することを保証するため望ましい。

---

## 16 <br>

A healthcare analytics company is exploring the use of Foundation Models to automate the process of labeling vast amounts of medical data, such as patient records and clinical notes, to enhance its machine learning models for diagnosis and treatment recommendations. The company wants to understand the specific techniques that Foundation Models use to generate labels from raw input data, helping streamline the data annotation process without requiring extensive manual effort.
Which of the following techniques is used by Foundation Models to create labels from input data? <br>ある医療データ分析企業は、患者記録や臨床メモといった膨大な医療データのラベリングプロセスを自動化するために、基盤モデルの活用を検討しています。これにより、診断や治療勧告のための機械学習モデルの精度向上を目指しています。同社は、基盤モデルが未加工の入力データからラベルを生成する際に使用する具体的な手法を理解したいと考えており、広範な手作業を必要とせずにデータアノテーションプロセスを効率化することを目指しています。
基盤モデルが入力データからラベルを作成するために使用する手法は、次のうちどれでしょうか？
基盤モデルが入力データからラベルを生成するために使う技術はどれですか？ <br>

<br>

* Answer <br>
  ***Self-supervised learning*** <br>

<br>

* Summary <br>
先生がいない <br>
でも **自分で問題と答えを作って学ぶ** <br>
<br>
**不正解**
* Supervised learning
* Unsupervised learning
* Reinforcement learning
---

## 17 <br>

A healthcare technology company is developing AI-driven applications to assist doctors in diagnosing diseases. As part of its commitment to ethical standards, the company wants to ensure that its AI models are fair, transparent, and free from bias. To achieve this, the data science team is exploring AWS services and tools that can help implement Responsible AI practices, as understanding which AWS services support these practices is critical for the company’s AI development strategy.
Which AWS services/tools can be used to implement Responsible AI practices? (Select two) <br>あるヘルスケアテクノロジー企業は、医師の疾病診断を支援するAI搭載アプリケーションを開発しています。倫理基準への取り組みの一環として、同社はAIモデルが公平で透明性が高く、偏りのないものであることを保証したいと考えています。これを実現するために、データサイエンスチームは責任あるAIの実践を支援するAWSサービスとツールを検討しています。どのAWSサービスがこれらの実践をサポートしているかを理解することは、同社のAI開発戦略にとって非常に重要だからです。
責任あるAIの実践を実装するために使用できるAWSサービス/ツールはどれですか？（2つ選択してください）
Responsible AIを実装するために使えるAWSサービスはどれですか？（2つ選択） <br>

<br>

* Answer <br>
  ***Amazon SageMaker Clarify*** <br>
  ***Amazon SageMaker Model Monitor*** <br>

<br>

* Summary <br>
* Clarify → 偏りチェック <br>
* Monitor → 劣化監視 <br>

👉 **AIの健康診断** <br>
<br>
**不正解**
* Amazon SageMaker JumpStart
* AWS Audit Manager
* Amazon Inspector

---

## 18 <br>

A healthcare company is developing a machine learning model to predict patient outcomes based on medical data. To ensure the model generalizes well, the company needs to understand the balance between underfitting and overfitting and how to address these issues.
Which of the following would you identify as correct regarding underfitting and overfitting in machine learning? <br>ある医療関連企業は、医療データに基づいて患者の予後を予測する機械学習モデルを開発しています。モデルの汎化性能を確保するためには、過学習と過小学習のバランスを理解し、これらの問題にどのように対処すべきかを把握する必要があります。
機械学習における過学習と過小学習に関して、以下の記述のうち正しいものはどれでしょうか？
未学習と過学習について正しい記述はどれですか？ <br>

<br>

* Answer <br>
  ***Underfit models experience high bias, whereas, overfit models experience high variance*** <br>アンダーフィットモデルはバイアスが高く、オーバーフィットモデルは分散が高いという特徴がある。

<br>

* Summary <br>
* 未学習 → 思い込み強い（高バイアス） <br>
* 過学習 → ブレブレ（高分散） <br>
アンダーフィッティングとは、機械学習モデルが訓練データに対して十分に学習できていない状態を指します。これは、モデルがデータの特徴を捉えきれず、訓練データとテストデータの両方で低い性能を示す場合に起こります。 <br>
<br>
**不正解**
* Underfit models experience low bias, whereas, overfit models experience low variance <br>アンダーフィットモデルはバイアスが低い一方、オーバーフィットモデルは分散が低い。
* Underfit models experience high bias, whereas, overfit models experience low variance <br>アンダーフィットモデルはバイアスが高く、オーバーフィットモデルは分散が低いという特徴がある。
* Underfit models experience low bias, whereas, overfit models experience high variance <br>アンダーフィットモデルはバイアスが低い一方、オーバーフィットモデルは分散が高いという特徴があります。

---

## 19 <br>

A healthcare company is evaluating the use of Foundation Models (FMs) in generative AI to automate tasks such as medical report generation, data analysis, and personalized patient communications. The company's data science team wants to better understand the key features and benefits of Foundation Models, particularly how they can be applied to various tasks with minimal fine-tuning and customization. To ensure they choose the right model for their needs, the team is seeking to clarify the essential characteristics of FMs in generative AI.
Which of the following is correct regarding Foundation Models (FMs) in the context of generative AI? <br>ある医療関連企業は、生成AIにおける基盤モデル（FM）の活用を検討しており、医療レポート作成、データ分析、患者への個別対応といったタスクの自動化を目指しています。同社のデータサイエンスチームは、基盤モデルの主要な特徴と利点、特に最小限のファインチューニングやカスタマイズで様々なタスクにどのように適用できるかをより深く理解したいと考えています。ニーズに最適なモデルを選択するために、チームは生成AIにおける基盤モデルの本質的な特性を明確にしようとしています。
生成AIにおける基盤モデル（FM）に関して、以下のうち正しいのはどれですか？
基盤モデルについて正しいものはどれですか？ <br>

<br>

* Answer <br>
  ***FMs use unlabeled training data sets for self-supervised learning*** <br>

<br>

* Summary <br>
* ラベルなし大量データ <br>
* 自己学習 <br>

👉 **事前にめちゃくちゃ賢い** <br>
<br>
**不正解**
* FMs use labeled training data sets for supervised learning <br>FM（ファクターマシン）は、教師あり学習のためにラベル付きの訓練データセットを使用します。
* FMs use labeled training data sets for self-supervised learning <br>大規模言語モデルは、自己教師あり学習のためにラベル付きトレーニングデータセットを使用する。
* FMs use unlabeled training data sets for supervised learning <br>FM（ファウンデーションモデル）は、教師あり学習のためにラベル付けされていない訓練データセットを使用する。

---

## 20 <br>

A retail company is developing machine learning models to analyze customer behavior and optimize inventory management. The data science team is working with both structured data as well as unstructured data and needs to understand how these two types of data differ in terms of how they are processed and used in machine learning models. Understanding this key difference will help the team select the right algorithms and preprocessing methods.
Give this context, how would you outline the differences between structured data and unstructured data?<br>ある小売企業は、顧客行動を分析し、在庫管理を最適化するために機械学習モデルを開発しています。データサイエンスチームは、構造化データと非構造化データの両方を扱っており、これらの2種類のデータが機械学習モデルにおいてどのように処理され、利用されるかという点で、どのような違いがあるのか​​を理解する必要があります。この重要な違いを理解することで、チームは適切なアルゴリズムと前処理方法を選択できるようになります。
この状況を踏まえ、構造化データと非構造化データの違いをどのように説明しますか？
構造化データと非構造化データの違いは何ですか？ <br>

<br>

* Answer <br>
  ***Structured data is organized in a predefined manner, often in rows and columns, making it easy to search and analyze, while unstructured data lacks a specific format and includes data like text, images, and videos*** <br>構造化データは、多くの場合、行と列といった事前に定義された形式で整理されているため、検索や分析が容易です。一方、非構造化データは特定の形式を持たず、テキスト、画像、動画などのデータが含まれます。

<br>

* Summary <br>
* Structured data　構造化 → Excel <br>
* unstructured data　非構造化 → 文章・画像・動画 <br>
<br>
**不正解**
* Structured data is typically freeform text that lacks any specific format, whereas unstructured data is organized in a tabular format with rows and columns <br>構造化データは通常、特定の形式を持たない自由形式のテキストであるのに対し、非構造化データは行と列を持つ表形式で整理されている。
* Structured data includes data like text, images, and videos, whereas unstructured data is limited to numerical data only <br>構造化データにはテキスト、画像、動画などのデータが含まれるのに対し、非構造化データは数値データのみに限定される。
* Structured data is used exclusively for training machine learning models, whereas unstructured data is used solely for storing information without any analytical purpose <br>構造化データは機械学習モデルのトレーニングにのみ使用されるのに対し、非構造化データは分析目的を持たずに情報を保存するためだけに用いられる。
---
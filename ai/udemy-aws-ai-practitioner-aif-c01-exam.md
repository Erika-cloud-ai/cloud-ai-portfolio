# AWS AI Practitioner AIF-C01 Practice exam

## 1 <br>
A legal research firm is seeking to implement a cutting-edge AI solution that can generate detailed responses to complex legal queries by retrieving relevant information from their extensive database of legal documents. The company wants to use Amazon Bedrock to deploy a fully managed solution that supports an end-to-end Retrieval Augmented Generation (RAG) workflow, ensuring that the AI can pull contextually accurate information and generate high-quality answers efficiently.
What solution or approach would you recommend for implementing fully managed support for a RAG workflow in Amazon Bedrock? <br>

* Answer <br>
***Knowledge Bases for Amazon Bedrock***

* Sumamary <br>
Amazon Bedrock × RAG
問題（要約）
大量の法律文書を検索して、それを元にAIが答えを作る（RAG）仕組みを、フルマネージドで使いたい。どれ？<br>
<br>
正解 <br>
✅ Knowledge Bases for Amazon Bedrock <br>
🐒 猿でも分かる説明 <br>
AIに「資料を調べさせてから答えさせたい」 <br>
でも 検索システム + AI + 管理 を自分で作るのは大変 <br>
Knowledge Bases は <br>
👉「資料を保存」 <br>
👉「必要な情報を探す」 <br>
👉「AIに渡す」 <br>
👉「答えを作る」 <br>
を 全部まとめてやってくれる <br>
つまり <br>
🧠「AI用のカンニングペーパー倉庫」 <br>
<br>
❌ 他がダメな理由（超重要） <br>
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
🐒 猿でも分かる説明 <br>

サービス	何する？	イメージ
Data Wrangler	データ整理	Excel職人
Canvas	ノーコードML	マウスだけAI
Ground Truth	人が正解付け	人間先生
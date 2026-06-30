# 生成 AI を触ってみましょう

* **今回の環境はトレーニング内で使用する時間帯だけで利用できます。**

## テキストを生成してみましょう
      
1. ページ上部の入力エリアに下記を入力します。

    - ```
      生成 AI についてブログ記事を書いてください。
      ```

1. [**生成**] をクリックします。

1. 生成 AI に関するブログ記事が出力されることを確認します。


## 要約してみましょう


1. ページ上部の入力エリアに下記を入力します。

    - ```
      以下の文章を100文字程度に要約して下さい。

      AWSは顧客からのすべてのフィードバックを受け、今日、私たちは AI 21ラボ、アンソロピック、スタビリティAI、そしてアマゾンのFMにAPIを介してアクセスできる新しいサービス「Amazon Bedrock」の発表を喜んで行います。
      Bedrockは、顧客がFMを使用して生成AIベースのアプリケーションを構築およびスケーリングする最も簡単な方法であり、すべてのビルダーにアクセスを民主化します。
      Bedrockは、スケーラブル、信頼性、セキュリティが高いAWS管理サービスを通じて、テキストと画像の強力なFM(アマゾンの新しい2つのLLMを含むTitan FMを含む)にアクセスする機能を提供します。
      Bedrockのサーバーレス体験により、顧客は自分が行おうとしていることに適したモデルを簡単に見つけ、すぐに開始し、独自のデータでFMをプライベートにカスタマイズし、インフラストラクチャを管理する必要なく(Amazon SageMakerのMLの機能であるExperimentsを使って異なるモデルをテストしたり、Pipelinesを使ってFMを大規模に管理したりするインテグレーションを含む)、慣れ親しんだAWSのツールと機能を使ってそれらを簡単にアプリケーションに統合およびデプロイできます。
      ```

1. [**生成**] をクリックします。

1. 要約された文章が出力されることを確認します。


## 翻訳してみましょう
   
1. ページ上部の入力エリアに下記を入力します。

    - ```
      以下の英文を日本語に翻訳して下さい。

      AWS took all of that feedback from customers, and today we are excited to announce Amazon Bedrock, 
      a new service that makes FMs from AI21 Labs, Anthropic, Stability AI, and Amazon accessible via an API. 
      Bedrock is the easiest way for customers to build and scale generative AI-based applications using FMs, 
      democratizing access for all builders. Bedrock will offer the ability to access a range of powerful FMs 
      for text and images—including Amazons Titan FMs, which consist of two new LLMs we’re also announcing 
      today—through a scalable, reliable, and secure AWS managed service. With Bedrock’s serverless experience, 
      customers can easily find the right model for what they’re trying to get done, get started quickly, privately 
      customize FMs with their own data, and easily integrate and deploy them into their applications using the AWS 
      tools and capabilities they are familiar with, without having to manage any infrastructure (including integrations 
      with Amazon SageMaker ML features like Experiments to test different models and Pipelines to manage their FMs at scale).
      ```
   　 
   
1. 翻訳された結果が日本語で表示されることを確認します。

## チャットで質問してみましょう

1. ページ上部の入力エリアに下記の例の質問を入力して実行してみましょう。

    - 正しい回答が得られているかも確認してみましょう。
    - 同じ質問を何度か繰り返してきいてみましょう。

* 例1:
     ```
     ショッピングサイトで有名なAmazon社を創設したのは誰でしょう？
     ```

* 例2:
    ```
    明日は何日ですか？
    ```

* 例3:
    ```
   （ご自身の会社や組織）では社員が結婚するときに何日間休暇をもらえますか？
    ```

## 画像を生成してみましょう

1. ページ上部で 「**画像生成**」を選択して下さい。

1. ページ上部の入力エリアで下記を入力して 「**生成**」ボタンをクリックして下さい。
     ```
     ショッピングサイトで有名なAmazon社を創設したのは誰でしょう？
     ```


## マルチモーダルの処理を試してみましょう

1. [こちら](https://dl39k3l39to9h.cloudfront.net/cat.jpg) を右クリックして、リンク先を保存し、猫の画像: **cat.jpg** をダウンロードして下さい。
1. ページ下部の入力エリアに下記を入力します。
    ```
    添付の画像の内容について説明して下さい。
    ```
1. デモアプリで、入力エリアの下側にある **添付** ボタン をクリックします。
1. ダウンロードした **cat.jpg** を選択します。
1. [**生成**] をクリックします。
1. 画像の内容を説明しているテキストが生成されたことを確認します。

















































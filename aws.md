# AWS

## AWS CLI

* [AWS Cli自分用Tips - Qiita](http://qiita.com/takachan/items/421928dc61c51af97fb1)  jqと組み合わせてさまざまな情報を表示する
* [awslabs/awscli-aliases: Repository for AWS CLI aliases.](https://github.com/awslabs/awscli-aliases) AWS CLI用のalias
* [AWSで構築した環境にありがちなシェルスクリプトたち まとめ ｜ Developers.IO](http://dev.classmethod.jp/cloud/aws/aws-shellscript-summary/)

## EC2

* [EC2起動時にスクリプトを実行する - notebook](http://swfz.hatenablog.com/entry/2015/10/15/202128)

## Lambda

* [AWS LambdaのIAMポリシーとリソースポリシーを理解しよう ｜ Developers.IO](http://dev.classmethod.jp/cloud/aws/policies-for-lambda/)
* [初めてのLambda ｜ Developers.IO](http://dev.classmethod.jp/cloud/aws/sugano-002-lambda/)

* [AWS Lambdaを紐解く](https://www.slideshare.net/keisuke69/aws-lambda-46129981) AWSの概要説明
* [Lambda + RDS benchmark - Qiita](http://qiita.com/taruhachi/items/3f95ae3e84f56edb3787)
* [Apexを使ってGoでlambdaを動かす - Qiita](http://qiita.com/dora56/items/b3acb3f4e45e68dce6a8)
* [AWS Lambdaで効率的にgoバイナリを実行する — そこはかとなく書くよん。](http://tdoc.info/blog/2016/01/07/lambda.html)

AWS Lambdaの関数の開発、デプロイを行なうツールApexについて。
実際の手順が書かれている。Goもサポートしている。

* [ApexでAWS Lambdaファンクションを管理する ｜ Developers.IO](http://dev.classmethod.jp/cloud/aws/how-to-manage-aws-lambda-functions-with-apex/)

Lambdaのサンプル。LambdaをCronで起動して、AWSの利用料金をチェックする。

* [AWSの料金をLambdaのcronで定期チェックしてSlackに通知する - Qiita](http://qiita.com/saku/items/fc6b70a420a5c510de2b)

AWS LambdからRDSへ接続するチュートリアル。

* [AWS LambdaでRDS（MySQL）に接続してみた - Qiita](http://qiita.com/Keisuke69/items/cba4b501e91da95188f8)

ちょっと古い(2014/12)が、Lambdaの実行環境を調べてみたという話

* [AWS Lambdaをいろいろ暴く - Qiita](http://qiita.com/Keisuke69/items/9951a93fd711360a61c5)

* [AWS Lambdaを使うときに注意する４つのこと -> ３つになりました - Qiita](http://qiita.com/imafuku/items/55844535dcc8e3861bd0#%E3%81%9D%E3%81%AE%EF%BC%92%E5%88%B6%E9%99%90)
* [AWS Lambdaのログまわりに関すること まとめ ｜ Developers.IO](http://dev.classmethod.jp/cloud/aws/lambda-and-cloudwatch/)

## IAM

* [IAM のベストプラクティス - AWS Identity and Access Management](http://docs.aws.amazon.com/ja_jp/IAM/latest/UserGuide/best-practices.html)
* [IAMロールを持たないEC2に対して、一括でIAMロールを付与する - Qiita](http://qiita.com/tkimura/items/b4711739496a0fdac06f)
* [[AWS]セキュアにIAMユーザのMFA有効化する手順2017年度版 ｜ Developers.IO](http://dev.classmethod.jp/cloud/aws/20170120-enabel-mfa/)
* [IAMロール徹底理解 〜 AssumeRoleの正体 ｜ Developers.IO](http://dev.classmethod.jp/cloud/aws/iam-role-and-assumerole/)
* [【鍵管理】~/.aws/credentials を唯一のAPIキー管理場所とすべし【大指針】 ｜ Developers.IO](http://dev.classmethod.jp/cloud/aws/exclusive-aws-credentials-location/)

## DynamoDB

* [DynamoDB の基礎知識とまとめ - Qiita](http://qiita.com/hshimo/items/e5ad98b21786d796f1da)
* [AWS再入門 Amazon DynamoDB 編 ｜ Developers.IO](http://dev.classmethod.jp/cloud/aws/cm-advent-calendar-2015-aws-re-entering-dynamodb/)
* [AWS Black Belt Tech シリーズ 2015 - Amazon DynamoDB](https://www.slideshare.net/AmazonWebServicesJapan/20150805-aws-blackbeltdynamodb)
* [DynamoDBの並列処理によるデータの欠損とProvisioning超過の対策 - VASILY DEVELOPERS BLOG](http://tech.vasily.jp/entry/dynamodb_feedback)
* [API Gatewayから、AWS Lambdaを使わずにDynamoDBにアクセスする - Taste of Tech Topics](http://acro-engineer.hatenablog.com/entry/2016/09/23/120000)
* [AWS DynamoDBの(新機能)TTLについて - クリエイティブ - ブログ - 株式会社テレビ朝日メディアプレックス](http://www.mediaplex.co.jp/blogs/creative/aws-dynamodb%E3%81%AE%E6%96%B0%E6%A9%9F%E8%83%BDttl%E3%81%AB%E3%81%A4%E3%81%84%E3%81%A6/)
* [DynamoDBのパーティション分割問題について｜ハンズラボエンジニアブログ｜ハンズラボ株式会社](https://www.hands-lab.com/tech/entry/1592.html)

## Misc

* [【AWS】クラウドデザインパターン実践編／仮想IPアドレスによるFloating IPパターン ｜ Developers.IO](http://dev.classmethod.jp/cloud/aws-cdp-floating-ip-pattern/)

子育て家族アプリFamm が、Amazon RDS for MySQL から Amazon Aurora へと移行した話。

* [RDS for MySQLからAmazon Auroraに移行した話 - Timers Tech Blog](http://techblog.timers-inc.com/entry/2016/03/02/135607)

* [[新ツール] AWS Serverless Application Model (AWS SAM) を使ってサーバーレスアプリケーションを構築する ｜ Developers.IO](http://dev.classmethod.jp/cloud/aws/aws-serverless-application-model/)
* [【登壇資料】AWSを使うサーバーサイドレシピ - ElastiCache, Amazon ECS, WAF + Lambda #gbfukuoka ｜ Developers.IO](http://dev.classmethod.jp/server-side/aws-serverside-recipe/)
* [PHPアプリケーションのセッション管理にAWS ElastiCacheを使う ｜ Developers.IO](http://dev.classmethod.jp/cloud/aws/php-session-elasticache/)

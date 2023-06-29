# 職務経歴書

## 基本情報
- Name: 岩下 拳勝
- Twitter: [@iwashi623](https://twitter.com/iwashi623)
- PR TIMES開発者プログ [公開エントリ](https://developers.prtimes.jp/author/kenshoiwashita/)
- [Wantedly](https://www.wantedly.com/id/kensho_iwashita)
- [Speaker Deck](https://speakerdeck.com/iwashi623)
- [Qiita](https://qiita.com/iwashi623)
- [Zenn](https://zenn.dev/iwashi623)
- [note](https://note.com/iwashi623)

## スキル
### 言語
PHP | Ruby | Go

### フレームワーク、Middleware
Laravel | Ruby on Rails | MySQL | PostgreSQL | nginx

### AWS
EC2 | ECS | Fargate | ECR | Lambda | ALB | VPC | VPC Peering | IAM | CloudFront | Route53 | RDS(MySQL | PostgreSQL) | Aurora | S3 | ElastiCache(Redis) | SQS | SNS | Chatbot | Parameter Store | Glue | EventBridge | CloudWatch | DirectConnect

### その他
GitHub | GitHub Actions | Terraform | NewRelic | Fastly | ecspresso | lambroll

### 資格等
 - AWS Certified Solutions Architect – Associate（2021/08）
 - AWS Certified Developer - Associate（2022/03）
 - AWS Certified SysOps Administrator - Associate（2022/08）
 - AWS Certified Solutions Architect - Professional（2022/10）

## 言語
- 日本語
  - ネイティブ
- 英語
  - 読み書きレベル

## バリューを発揮しやすい業務
 - PHPやRubyを使用したサーバーサイドのWebアプリケーション・API開発
 - CI/CDパイプラインの構築や改善
 - クラウドサービスを使ったアーキテクチャ設計
 - クラウドサービスのインフラ構築･環境のコード化

## 価値観
なにか一つのことに集中して数年単位で何かを成し遂げるよりも､多くの失敗を重ねながらたくさんのチャレンジをすることに価値を感じる性格です｡
[16Personalities性格診断テスト](https://www.16personalities.com/ja)の結果は[ENTP](https://www.16personalities.com/ja/entp%E5%9E%8B%E3%81%AE%E6%80%A7%E6%A0%BC)です｡

一方で､型にはまった作業や踏襲されてきた歴史などを無心で重んじるのが苦手で､そういった状況に陥るとバリューの低下やメンタルの不健康を感じます｡

## 興味・関心
ソフトウェア開発､とりわけWeb業界は知識の幅が広く､執筆時点で(2023/3 現在)はすべての分野を一通り触ったとは全く言えない状況です｡そのため前述したような性格でも毎日楽しく学習ができています｡エンジニアの業務は十分知的好奇心を刺激されて楽しく働くことができているため､しばらくはエンジニアとしてキャリアを築いていきたいです｡

エンジニアの中では､これまでのキャリアで主にサーバーサイドやクラウドサービスを利用したインフラ構築を担当してきました｡ただ､そこにこだわりがあるわけではなく､むしろ幅を更に広げていきたいと考えています｡GoやKotlinなどの静的型付け言語やTypeScrip+FWを使ったフロントエンド開発､ネイティブアプリケーション開発にも興味があります｡

## 職務経歴
### 2021/04 - 2023/07 : 株式会社PR TIMES
#### 職務内容
 - Webアプリケーションバックエンド開発･クラウドインフラ構築運用｡
 - 2021/07より､[PRTIMES STORY](https://prtimes.jp/story)開発リーダー｡
 おもにアプリケーションのリアーキテクチャや開発環境改善､CDNの導入などを担当した｡
 - PR TIMES AWS移行プロジェクトのメンバー｡インフラのコード化や関連サービスのDBの接続先変更(VPC Peering､DirectConnectの設定)を担当｡
#### 職務の中で学んだことや得られた知識・スキルなど
技術的な内容は下記の開発実績をご参照ください｡ここではその他の経験を述べます｡

チームメンバーは4〜6人の少数チームでしたが、開発リーダーとして工数管理や実装優先度の決定をしていました｡手を動かしてコードを書く以外の主な業務は､ビジネスサイドの要望に対して､開発をすすめるにあたっての要件の切り出しやDesing Docの作成です｡

担当しているプロダクトがユーザーの少ない新規サービスで､さらに開発がなかなか進んでいない状況でした｡そこで最小工数でできるだけ早くリリースして､社内の信頼を勝ち取ることを目標にしていました｡

また､技術的な情報発信を会社が運営しているブログ上で行いました｡インターネットに知識を還元することはもちろん､自分自身や会社の開発組織の価値向上につながると肌で感じることができました｡

## 開発実績
### Fastly lmage Optimizerを利用したWebP, AVIFでのサムネイル画像配信基盤作成
#### 公開エントリ
 - [AVIF・WebPでサムネイル画像を配信して､ブラウザでのパフォーマンスを大幅に改善した話](https://developers.prtimes.jp/2023/03/02/use_avif_and_webp_for_story_thumbnail_images/)

#### 概要
担当サービスでブラウザ表示の際にパフォーマンス上の問題点があった｡主たるボトルネックになっていたのは各記事のサムネイル画像がJPEGやPNGといった古い画像フォーマットを使用していたことだった｡[社内で採用実績のある](https://developers.prtimes.jp/2022/02/24/press_release_image_optimization/)､Fastlyの[Image Optimizer](https://www.fastly.com/jp/products/image-optimization)を使用して新しい画像フォーマットへ変換した後配信すれば､こちらのボトルネックは解消できることがわかっていたため導入した｡

また､WebPだけではなくAVIFという更に新しい画像フォーマットも導入して､Fastly Service上でVCLを使って柔軟に画像配信を行える基盤を整えた｡

#### 担当
Fastly Serviceの作成と設定･Image Optimizerの設定値の決定･PHPアプリケーションコードの修正

#### 実装内容
Image Optimizerを使用したサムネイル配信画像基盤導入のきっかけは､担当サービスのブラウザ上でのパフォーマンスが悪い事が挙げられる｡Lighthouseを使って計測したところ､
 - mobileのPerfomanceの項目が25
 - DesktopのPerfomanceの項目が64

であった｡ボトルネックとなっている理由を見ていくと､サムネイル画像で使っているJPEGやPNGといった画像フォーマットよりも､WebPやAVIFという新しい高圧縮の画像フォーマットを使用したほうが良いことがわかった｡

古いサムネイル画像は､ユーザーにアップロードしてもらったオリジナル画像から､3枚の大きさ別(width200, 400,800)の画像を生成して配信していた｡これを､新しいサムネイル配信基盤ではかなり大きい画像一枚だけを生成する方式に改修している｡FastlyのImage Optimizerでは､Originから受け取った画像のりサイズや変換を動的に行うことができるため､ある程度大きな一枚だけを作るだけで良いためである｡

ユーザーごとに､
 - AVIF対応ブラウザにはAVIFを返す
 - AVIF非対応かつWebP対応ブラウザにはWebPを返す
 - AVIF・WebPともに非対応ブラウザにはJPEGを返す

といった､柔軟なサムネイル画像配信が行えるように､VCLのカスタマイズも行った｡詳細は公開エントリ(開発者ブログ)に記載してある｡

キャッシュのパージを個別の画像ごとに行うことができるように､アップロードするサムネイル画像にはSurrogateKeyの付与も行った｡これにより､一括のCDNキャッシュパージ以外にも柔軟な対応ができるようになった｡

結果として､Lighthouseの結果が､
 - mobileのPerfomanceの項目が66
 - DesktopのPerfomanceの項目が99

まで向上した｡
AVIFを導入することにより､画像の容量を
 - 改善前 → content-length: 642954
 - 改善後 → content-length: 23141

まで圧縮できた画像もあった｡

また､いままでのサムネイル画像よりも大きなサイズで画像をレスポンスするようにしたため､画像の容量が減っているにも関わらず､画像の画質(見た目)も向上している｡

#### 使用技術
PHP | Laravel | Fastly(VCL変更も含む) | Image Optimizer | S3 | Terraform 


### Webアプリケーションのリアーキテクチャと運用(〜現在)
#### 公開エントリ
 - [PR TIMES STORYを別リポジトリに移植した話](https://developers.prtimes.jp/2022/10/05/transportation_story_program/)

#### 概要
担当サービスが変に分割されており､また分割された片方がもう一方と全く違うFWを採用していた｡また､開発組織のエンジニア以外にその事実を知っていることが少ないことなどが原因となり､開発速度が出しづらい環境であった｡加えて､社内のサービスと一つだけ別ドメインを使用していることでCDNの設定やCORSの設定を独自で行う必要があり､少ないエンジニアリソースが無駄になっている面もある状況でもあった｡

そこで､そのような状況を打開するために分割されたサービスの統合やドメイン変更などを行い､以後の変更や機能開発で余計な工数がかからないようにした｡

#### 担当
バックエンド･フロントエンド全ての移植やインフラ構成の変更を一人で担当

#### 実装内容
アプリケーション移植プロジェクト
 - 分割されたサービスの統合では､独自FWで管理されているコードを､Laravelに移植した｡基本は同じPHPなので動作するが､バージョンの差異により一部deprecatedになっている関数や無意味なリクエストをしているところもある｡そこで慎重にTestを書きながら1ページずつWebアプリケーションを移植する手法をとった｡
 - 1ページずつ移植するために､ALBのホストベース･パスベースのルーティング機能を使用した｡具体的にはページごとにリスナールールを書き足していくことにより実現できた｡また､既存ECSに2つのサービス分のリクエストが流れてくるため､NewRelicのエージェントを用いたECSの監視も追加した｡

ドメイン変更プロジェクト
 - 基本はLaravelのルーティングファイルを変更して､移植先ドメインで使用するパスへリクエストが来たら､対応するControllerを呼び出すようにた｡これだけであたらしいエンドポイントへも今まで通りの形でレスポンスを返せるようになる｡
 - ただし､エンドポイントの名前が変更されることもあり､動作はするがリポジトリのアーキテクチャ上あるべき場所に無いコードが大量に発生した｡それらは､リファクタリングデーで移植することで地道に正常な状態へ戻した｡
 - すでに古いドメインをブックマークしているユーザーがいることも考慮に入れて､古いエンドポイントは消さず､内部処理で新ドメインのエンドポイントへリダイレクトさせる設計をとった｡

Desing Docを実装前に丁寧に書くことで､スコープ内･外のことやリリースの方法(1ページずつリリースするなど)を予めきめて走り切った｡

#### 使用技術
PHP | Laravel | ECS | ALB | NewRelic | Terraform 

### ECSのマルチステージ環境開発(2022/03頃)
#### 公開エントリ
 - [ECSでマルチステージング環境を実現した設計と実装](https://developers.prtimes.jp/2022/04/22/ecs-multistg-deploy/)
 - [CloudFrontのディストリビューションを分割して、マルチステージング環境をさらに便利にした話](https://developers.prtimes.jp/2022/11/09/divide_cloudfront_distribution_for_multi_staging/)

#### 概要
担当していたサービスの"検証環境が一つしかない"という状況だった｡この状況では､チームが大きくなった際に並行でプロジェクトを動かしていく際にQA確認などですべての開発が詰まることは明白であった｡実際､開発チームが少人数の状況でも､QAやエンジニアの検証作業が開発の流れのボトルネックになっていた｡

そのため､誰でも自由にそれぞれがデプロイできる環境の作成をして､チームの開発速度向上に貢献した｡また､社内の別アプリケーションにも取り入れられる仕組みとなり､別チームがこちらの機能を導入する際は実装のレビュアーやアドバイスなども行った｡

#### 担当
アーキテクチャ設計･実装･ドキュメント作成･部署内への周知をほぼ一人で担当

#### やったこと
 - 設計は既存環境をECSとほぼ同じ構成で､検証環境のサブドメインとして各人の環境がデプロイできるようにした｡
   - 仮に検証環境のドメインが`example.com`だとすると､`hoge.example.com`のドメインで各人が自由な環境をデプロイすることができる｡
 - デプロイはGitHub Actionsを使用して､[ecspresso](https://github.com/kayac/ecspresso)コマンドを使うことによって実現した｡
 - DBまわりは他のステージング環境と共用している｡これはステージング毎にDBを分けると「起動･停止に時間がかかること」や「コストのかかる割に､それに見合うリターンが現状見込めないこと」に起因している｡
   - 実現しようと思ったら､ecspressoのタスク定義ファイルを､GitHub Actionsのinputの値をもとにデプロイするECSのDBHostの値を書き換える､もしくはアプリケーションにDBの参照先を変更する管理画面に入れるなどして対応予定できる｡
 - ECS以外のAWSリソースはTerrafromを使って作成した｡
   - ECSやALB､Security Groupの設定などは初めて一人で行ったが､公式ドキュメントやAWS認定資格の際に勉強した知識を活かして実装を進めた｡
   - 「ALBには2つのドメインの証明書を関連付けられる」や「CloudFrontではホストベースのルーティングは不可」などの知見を実装しながら学んでいった｡

結果として､複数のプロジェクトの並行実施やリファクタリングデーの定期実行､デザイナーへの確認などがスムーズに行えるようになった｡
#### 使用技術
ECS | ECR | ALB | ACM | ALB | CloudFront | GitHub Actions | ecspresso | Terraform

### BigQueryをつかった社内のデータ分析基盤整理(2021/11-2022/01頃)
#### 公開エントリ
 - [AuroraからBigQueryへデータ転送する際のシステム構成
](https://developers.prtimes.jp/2022/03/02/aurora_to_bigquery/)

#### 担当
BigQueryへのデータ転送の自動化･DBのスナップショット取得アプリケーションの実装

#### やったこと
 - データをBigQueryにエクスポートするにあたって転送すべきではないデータも含まれていた｡
   - サービスの性質上､公開前情報なども扱うため安易にDBのデータをそのままBigQueryに転送はできない｡そのため､秘匿情報などマスキングや転送データから削除するべきデータは､[AWS Glue](https://aws.amazon.com/jp/glue/)を使用したETL処理を行った｡Glueを使って変換処理を終えたファイルをS3に書き出し､そのファイルをBigQueryに転送することで要件を満たした｡
 - Aurora MySQLのsnapshotの機能を使用して､リードレプリカなどを使わずにデータをGlueで読み込む｡
   - DBサーバーへの負荷を考慮して､本番DBからのデータ取得は選択肢から外れた｡
   - Glueの処理用にAurora MySQLのリードレプリカを新たにたてる方法もあったが､その方法ではDBサーバーの料金が無駄になると考えた｡そのため､AuroraのSnapshotをつかって､Glueでデータを読み込む手法を選定した｡
   - スナップショットの定期的なS3への転送にはLambdaでデプロイしたGoアプリケーションを実装･デプロイした｡[ブログ](https://developers.prtimes.jp/2022/03/02/aurora_to_bigquery)に実際がコード記載｡
     - データの取得→変換→転送の処理を完全に自動化するために､EvendbridgeやBigQueryの定期実行Jobを使用した｡
 - ただBigQueryでデータを閲覧できるようにしただけでは､ビジネスサイドの人がデータを見るのには障壁(クエリの作成･実行)がある｡そのため､Google DataStudioとBigQueryの定期実行Jobを使用して､毎日更新されるダッシュボードを作成した｡これにより､ビジネスサイドの方でも簡単に毎日の配信件数などを把握できるようになった｡
   - 実際にビジネスサイドの人にどういったデータがほしいか(Ex: 毎日の新規投稿数､週ごとの新規投稿企業数など)をヒアリングして､ダッシュボードに日々アップデートをかけていった｡
#### 使用技術
Python | Go | Lambda | lambroll | S3 | KMS | Aurora MySQL | Glue | EventBridge | CloudWatch | BigQuery

## 課外活動
### 登壇など
 - PHPカンファレンス2022 スポンサーLT登壇
   - [登壇資料](https://speakerdeck.com/iwashi623/aa-wo-ranoecs-1)
   - [映像](https://www.youtube.com/watch?v=wFjGeFafagU)

 - PHPカンファレンス福岡 2023 登壇
   - [登壇資料](https://speakerdeck.com/iwashi623/phpermoiacwoshi-ou-17nian-wu-noinhurawoterraformnida-yi-xing)
   - [映像(後日追加予定)]()

### 社外プロジェクト(OSSなど)
特になし

## 個人開発
### gjobctl
 - リポジトリ: https://github.com/iwashi623/gjobctl
 - 機能: [README](https://github.com/iwashi623/gjobctl/blob/main/README.md)
 - 概要: Glue Jobを作成･管理をするときにほしいAPIをラップしたツール｡

#### 作成背景
1. スクリプトをリポジトリで管理したいこと
2. Jobをコンソールから作成するのが手間だったこと

があげられる｡

1は自身がGlue Jobのスクリプトをデバッグのために編集を加えたり･戻する際に感じた課題感である｡リポジトリ管理がされておらず､現状の実装が何を意図して実装されたのかわからなくなることが多かった｡

これはGitHubのリポジトリでスクリプトを管理することで解決できる｡GitHubでスクリプトを管理するようになると､当然GitHub Actionsを使用して自動デプロイもできたら嬉しいという要望も出てくる｡これだけであればGitHub Actionsで`aws s3`コマンドを叩けば実現できる｡

ただ､別件で2も常々思っていた｡ソースデータのテーブル･カラムが追加されるたびに､AWSのコンソールに行って同じような設定のJobをポチポチ作るのも､一回一回はそれほど手間でもないが積み重なると辛い｡

そこで､スクリプトのデプロイとJobの作成･更新ができるツールを作成した｡
 - Jobの管理はTerraform
 - スクリプトはリポジトリ管理して`aws s3`コマンド

という運用も悪くないかと思ったが､スクリプトファイルとJobの設定ファイルを近く(同じリポジトリ)におくという運用にもメリットを感じたので製作した｡言語選定については､勉強したかったという理由とバイナリ配布が容易である点からGoを選択した｡

### terrapolice（作成途中）
 - リポジトリ：https://github.com/iwashi623/terrapolice
 - 機能：[README](https://github.com/iwashi623/terrapolice/blob/main/README.md)
 - 概要： Terraform Planを簡単に一気に通すためのCLIツール

 #### 作成背景
 [こちら](https://speakerdeck.com/iwashi623/phpermoiacwoshi-ou-17nian-wu-noinhurawoterraformnida-yi-xing?slide=57)にあるように、Terraformは差分ができると誰も触りたくなくなるという課題感があった。
 
 上記の課題を解決するためには、本来であればCIツールを使ってPlanの定期実行を行いたい。

 しかしながら、Terraformのディレクトリ構成は組織によって千差万別で、stateファイルの量もそれぞれ異なる。そんな時、シェルスクリプトを書いてCIを無理やり作るのもエンジニアの腕の見せ所ではあるが、terrapoliceを利用すれば設定ファイルに書いたディレクトリ全てで`terraform plan`を実行できるので、難しいシェルスクリプトを書く必要がなく、planの定期実行が行えるようになる。

# 職務経歴書

## 基本情報
- 岩下 拳勝(@iwashi623)
- [Twitter](https://twitter.com/iwashi623)
- [PR TIMES開発者プログ](https://developers.prtimes.jp/author/kenshoiwashita/)
- [バイセル Tech Blog](https://tech.buysell-technologies.com/archive/category/iwashi623)
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

### GCP
BigQuery | Cloud Run | Cloud Run Jobs | Cloud SQL | Cloud Load Balancing | Cloud Strage | Cloud Functions

### その他
GitHub | GitHub Actions | Terraform | NewRelic | Fastly | ecspresso | lambroll

### 資格等
 - AWS Certified Solutions Architect – Associate（2021/08）
 - AWS Certified Developer - Associate（2022/03）
 - AWS Certified SysOps Administrator - Associate（2022/08）
 - AWS Certified Solutions Architect - Professional（2022/10）
 - GCP Associate Cloud Engineer（2023/11）

## 言語
- 日本語
  - ネイティブ
- 英語
  - 読み書きレベル

## バリューを発揮しやすい業務
 - PHPやGoを使用したサーバーサイドのWebアプリケーション・API開発
 - CI/CDパイプラインの構築や改善
 - クラウドサービスを使ったアーキテクチャ設計
 - クラウドサービスのインフラ構築･環境のコード化

## 価値観
なにか一つのことに集中して数年単位で何かを成し遂げるよりも､多くの失敗を重ねながらたくさんのチャレンジをすることに価値を感じる性格です｡
[16Personalities性格診断テスト](https://www.16personalities.com/ja)の結果は[ENTP](https://www.16personalities.com/ja/entp%E5%9E%8B%E3%81%AE%E6%80%A7%E6%A0%BC)です｡

一方で､型にはまった作業や踏襲されてきた歴史などを無心で重んじるのが苦手で､そういった状況に陥るとバリューの低下やメンタルの不健康を感じます｡

## 興味・関心
ソフトウェア開発､とりわけWeb業界は知識の幅が広く､執筆時点で(2024/06 現在)はすべての分野を一通り触ったとは全く言えない状況です｡そのため前述したような性格でも毎日楽しく学習ができています｡エンジニアの業務は十分知的好奇心を刺激されて楽しく働くことができているため､しばらくはエンジニアとしてキャリアを築いていきたいです｡

エンジニアの中では､これまでのキャリアで主にサーバーサイドやクラウドサービスを利用したインフラ構築を担当してきました｡ただ､そこにこだわりがあるわけではなく､むしろ幅を更に広げていきたいと考えています｡GoやKotlinなどの静的型付け言語やTypeScrip+FWを使ったフロントエンド開発､ネイティブアプリケーション開発にも興味があります｡

個人的な趣味としては､[ISUCON](https://isucon.net/)にハマっており､次回の開催がされたらいい成績を残せるように準備中です｡

## 職務経歴
### 2023/07 - 現職 : 株式会社BuySell Technologies
#### 職務内容
 - リユースプラットフォーム[Cosmos](https://speakerdeck.com/buyselltechnologies/enziniacai-yong-buysell-technologieshui-she-shuo-ming-zi-liao?slide=26)の店舗買取アプリ**Store**･訪問買い取り査定アプリ**Visit**を担当
 - 担当領域はバックエンド･インフラ周り｡
   - Golangで作成されたGraphQLサーバー(gqlgen)を使っている｡[Hasura](https://hasura.io/)のクエリで補えない複雑なロジックはsidecarと呼ばれる別アプリケーションで定義している｡
   - アプリケーションのデプロイ先はCloud Run
   - DBにはCloud SQL(PostgreSQL)とCloud Spanner
 - 主にグループ内の会社の方が使うアプリケーションだったため､直接現場へアプリへのフィードバックや要望を聞ける環境だった｡ただし､現場の意見をそのまますべて取り入れているとSaasとして機能しないものが完成するため､現場から頂いた意見をどうやって機能に落とし込むか?を大切にしていた｡
 - 初めての転職だったこともあり､ジョイン当初は技術的な挑戦はあまりできなかった｡
   - しかしながら前職で取り組んでいた､「MTGの録画文化」や「DMでのコミュニケーションを減らす」などの文化を取り組みをチームの中に吹き込んだ｡

### 2021/04 - 2023/07 : 株式会社PR TIMES
#### 職務内容
 - Webアプリケーションバックエンド開発･クラウドインフラ構築運用｡
 - 2021/07より､[PRTIMES STORY](https://prtimes.jp/story)開発リーダー｡
 おもにアプリケーションのリアーキテクチャや開発環境改善､CDNの導入などを担当した｡
 - PR TIMES AWS移行プロジェクトのメンバー｡インフラのコード化や関連サービスのDBの接続先変更(VPC Peering､DirectConnectの設定)を担当｡
#### 職務の中で学んだことや得られた知識・スキルなど
チームメンバーは4〜6人の少数チームだった｡その中で開発リーダーとして工数管理や実装優先度の決定をしていた｡手を動かしてコードを書く以外の主な業務は､ビジネスサイドの要望に対して､開発をすすめるにあたっての要件の切り出しやDesing Docの作成を担当した｡

担当しているプロダクトがユーザーの少ない新規サービスで､さらに開発がなかなか進んでいない状況だった｡そこで最小工数でできるだけ早くリリースして､社内の信頼を勝ち取ることを目標にしていた｡

また､技術的な情報発信を会社が運営しているブログ上で行いました｡インターネットに知識を還元することはもちろん､自分自身や会社の開発組織の価値向上につながると肌で感じることができた｡

## 開発実績
### Terraformリポジトリの構成変更
#### 概要
Terraformのコードが複数人で作業をできる環境になっておらず､またデプロイのフローも非常に煩雑なものになっていた｡
それを､誰でも作成､リリースができる状況を作って､チームの中でIaCでクラウドリソースが作られることが当たり前の状況を作った｡

#### 担当
- 現状の課題分析と共有
- シングルModuleで管理されていたコードを各環境ごとへ分離
- mainブランチにMergeすることでリリースされるようにTerraform Cloudの設定変更とCI/CDの導入

#### 実装内容
DEV, STG, PRODすべての環境のコードが､共通moduleとして定義されており､設定値を外部からvariableとして流すような構成になっていた｡
この構成は､限られた人員でクラウドリソースを触る場合だと重複されたコードが生まれず開発速度が出る.

しかしながらこの構成の問題点として､module内のコードを少しでもいじると､試したい環境以外でも､差分が生まれてしまうことがあった｡例えば､DEV環境にのみなにか変更を入れて試したいとき､もれなくSTGやPROD環境でも差分が生じる｡
そうすると､誰かがインフラリソースを変更をかけているときに､他の誰かが新しいPull Requestを作った場合､必ず自分と関係のない差分が発生している状況であるため､Applyをする前にその都度調査が必要となる｡
また､たとえばDevとSTG環境だけはIP制限をかけたいなどの独自の設定も､共通Moduleを使っているうちはいれることができない･または難しいことをしなければいけなくなる｡

チームのモチベーションとしては､チームのメンバーが各々アプリケーションからインフラまで一気通貫した開発ができる状況のほうが望ましい状況であった｡
しかしながら､このような状況ではチームのメンバーがTerrafromのコードを編集ことが難しくなり､結果としてインフラリソースの作成や更新が他人事になってしまう｡
そのため､この問題を解消した｡

具体的には､一つのmoduleとして各環境のコードとは別に定義されていたコードを､各環境配下に複製した｡また､共通moduleのオリジナルのコードは削除した｡

**Before**
```bash:Beforeのコード
.
├── modules
├── development/
│   ├── main.tf
│   └── *.tf
├── staging/
│   ├── main.tf
│   └── *.tf
└── production/
    ├── main.tf
    └── *.tf
```

**After**
```bash:After
.
├── development/
│   ├── modules
│   ├── main.tf
│   └── *.tf
├── staging/
│   ├── modules
│   ├── main.tf
│   └── *.tf
└── production/
    ├── modules
    ├── main.tf
    └── *.tf
```

たったこれだけの変更で､共通moduleからは解放されて､それぞれのメンバーが自分の設定変更に注力して作業が可能になる｡各環境配下に生まれたmoduleディレクトリの中身は､剥がしやすいものからmoduleから外出ししたファイルに移植することで減少していった｡

また､同時にリリースフローの課題も解消した｡
それまでのリリースフローは､
- mainブランチにマージされたらdevelopment環境
- stagingブランチにマージされたらstaging環境
- productionブランチにマージされたらproduction環境

にデプロイされるようになっていた｡これは､共通Moduleを使っている都合上､各環境にデプロイされるブランチを分けないと､検証ができずに常に一斉リリースになってしまうためである｡
つまり全員がmainから作業ブランチを切るとしても､一つの変更をすべての環境に反映するまで､計6個のPull Requestが必要になる｡これは非常に煩雑な状況だった｡

また､仮にstagingブランチでリリースがストップしているような状況の変更があると､他の人がstagingブランチに向けてPRを作ったときに差分が出る状況でもあった｡

しかしながら前述の通り､共通Moduleの問題は解消したため､開発者は常に変更を与えたい環境配下のコードのみを触るようになっている｡
例えば､staging環境に変更をいれる場合､触るのは`statging`配下のファイルのみである｡

この状況であれば､mainにマージされたときにどの環境のコードが変更されたかを検知できる｡つまり変更が入った環境でのみ､`terraform apply`が走るようにできると考えた｡
この設定変更は､すでに導入されていた[Terraform Cloud](https://www.hashicorp.com/products/terraform/pricing)の`VCS Branch`と`Terrafrom Working Directory`､`Automatic Run Triggering`の設定を変更することで実現した｡

作業者は何個もPull Requestを作る必要から解放されて､自分のPull Requestがmainにマージされればその環境にリリースされるという安心感を得ることができた｡

### DBと接続したCloud　Run　Jobsの基盤作成
#### 概要
背景として､提供している店舗買取アプリケーションで､締結済み契約で本来必要なデータで不足しているものがあった｡アプリケーションは既に運用に乗っており､
 - これから契約されるデータ
 - これまでの契約のデータ

のそれぞれに対してデータを作る処理が必要になった｡
これからの契約データに関しては､契約が締結されるタイミングでデータをINSERTする処理をすれば問題なく､そちらは複雑なことはせずAPIを作成した｡
一方で､これまでの契約データに対応するデータ作成は､既存アプリケーションの動きとは別にデータをINSERTする必要がある｡

担当していたアプリケーションに､任意の作業Jobを実行するための基盤がなかったため､基盤を作成して､Jobを実行することで既に締結済みの契約に関してもデータを作成した｡

#### 担当
 - 必要なデータを作るタイミングの要件定義､及び調整
 - データのテーブル設計
 - APIの機能改修
 - 既に契約締結済みのデータに対して､必要なデータを作成するため方法を検討･設計
 - Cloud Run Jobsの基盤作成
 - Cloud Run Jobsで実行されるCLIアプリケーションの作成
 - CI/CDパイプラインの構築

#### 実装内容
最小工数で実装するのであれば､既に動作しているCloud Runのアプリケーション上に､単発のAPIエンドポイントを生やせば対応できた｡しかしながら､アプリケーション上で実行すると､仮に負荷が高いJobだったときに全体に影響が出るかもしれない懸念があった｡

元々､アプリケーションとは別にJobを実行する基盤がなかったため､今回アプリケーションとは切り離したJobを作ることを選択した｡
インフラ基盤にはCloud Run Jobsを選択した｡理由は､Cloud Runを普段からチームで使用しており､他の選択肢を取るよりもキャッチアップが容易であったことが挙げられる｡

JobのCLIアプリケーションは､[cobra](https://github.com/spf13/cobra)を使用して作成して､サブコマンドをJob実行時に渡すことで任意の振る舞いができるになっている｡

CLIアプリケーションはDocker化されているため､アプリケーションをBuildしてGCPのArtifact RegistryにPushするためのパイプラインも作成した｡
本番実行前に､Cloud SQLのスナップショットから作成したDBを立てて､そこでリハーサルを行い､負荷的に問題がないことを確認した｡
インフラはすべてTerraform化されている｡

#### 使用技術
Go | [Bun(ORM)](https://bun.uptrace.dev/) | Cloud Run Jobs | Cloud SQL | Secret Manager | Terraform | GitHub Actions


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

 - [PHPカンファレンス福岡 2023 登壇](https://fortee.jp/phpconfukuoka-2023/proposal/833744fc-9816-4a3a-ab56-a82e964b97fa)
   - [登壇資料](https://speakerdeck.com/iwashi623/phpermoiacwoshi-ou-17nian-wu-noinhurawoterraformnida-yi-xing)
   - [映像](https://www.youtube.com/watch?v=xzt1QDk1hYQ)

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

### terrapolice
 - リポジトリ：https://github.com/iwashi623/terrapolice
 - 機能：[README](https://github.com/iwashi623/terrapolice/blob/main/README.md)
 - 概要： Terraform Planを簡単に一気に通すためのCLIツール

 #### 作成背景
 [こちら](https://speakerdeck.com/iwashi623/phpermoiacwoshi-ou-17nian-wu-noinhurawoterraformnida-yi-xing?slide=57)にあるように、Terraformは差分ができると誰も触りたくなくなるという課題感があった。
 
 上記の課題を解決するためには、本来であればCIツールなどを使ってPlanの定期実行を行って、
  - 定期的に差分を検知
  - 差分を解消するPR作成

というフローを組織内に作る必要がある。

 しかしながら、Terraformのディレクトリ構成は組織によって千差万別で、stateファイルの量もそれぞれ異なる。そんな時、シェルスクリプトを書いてCIを無理やり作るのもエンジニアの腕の見せ所ではあるが、terrapoliceを利用すれば設定ファイルに書いたディレクトリ全てで`terraform plan`を実行できる。結果として難しいシェルスクリプトを書く必要がなく、planの定期実行が行えるようになる。

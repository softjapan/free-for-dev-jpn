# free-for.dev［日本語版］

開発者とオープンソースの作者にとって、多くのサービスが無料プランを提供していますが、それらを見つけて適切に判断するには時間がかかります。

このリストは、開発者向けの無料プランを提供するソフトウェア(SaaS、PaaS、IaaS等)およびその他のサービスをまとめたものです。

対象範囲は、インフラ開発者(システム管理者、DevOps実践者など)にとって有用と思われるものに限定しています。無料のサービスは歓迎しますが、トピックに沿った内容を維持したいと考えています。判断が難しい場合もありますので、これは主観的な基準となります。貢献が受け入れられなかった場合でも、ご理解いただければ幸いです。

このリストは、1600人以上の方々によるプルリクエスト、レビュー、アイデア、作業の成果です。[プルリクエスト](https://github.com/ripienaar/free-for-dev)を通じて、新しいサービスの追加や、内容が変更・廃止されたサービスの削除にご協力いただけます。

[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/ripienaar/free-for-dev)

**注意**: このリストはサービスとしての提供(as-a-Service)のみを対象としており、セルフホスト型のソフトウェアは含まれません。掲載されるサービスは、単なる無料トライアルではなく、無料プランを提供している必要があります。期間限定の場合は、最低1年間の無料プランであることが条件です。また、セキュリティの観点から無料プランを評価しており、SSOは問題ありませんが、TLSを有料プランのみに制限するサービスは対象外とします。

# 目次

  * [主要クラウドプロバイダーの常時無料枠](#major-cloud-providers)
  * [クラウド管理ソリューション](#cloud-management-solutions)
  * [分析、イベント、統計](#analytics-events-and-statistics)
  * [API、データ、ML](#apis-data-and-ml)
  * [アーティファクトリポジトリ](#artifact-repos)
  * [BaaS](#baas)
  * [ローコードプラットフォーム](#low-code-platform)
  * [CDNと保護](#cdn-and-protection)
  * [CIとCD](#ci-and-cd)
  * [CMS](#cms)
  * [コード生成](#code-generation)
  * [コード品質](#code-quality)
  * [コード検索とブラウジング](#code-search-and-browsing)
  * [クラッシュと例外処理](#crash-and-exception-handling)
  * [地図上のデータ可視化](#data-visualization-on-maps)
  * [マネージドデータサービス](#managed-data-services)
  * [デザインとUI](#design-and-ui)
  * [デザインインスピレーション](#design-inspiration)
  * [開発者ブログサイト](#dev-blogging-sites)
  * [DNS](#dns)
  * [Docker関連](#docker-related)
  * [ドメイン](#domain)
  * [教育とキャリア開発](#education-and-career-development)
  * [メール](#email)
  * [機能トグル管理プラットフォーム](#feature-toggles-management-platforms)
  * [フォント](#font)
  * [フォーム](#forms)
  * [生成AI](#generative-ai)
  * [IaaS](#iaas)
  * [IDEとコード編集](#ide-and-code-editing)
  * [国際携帯電話番号認証APIとSDK](#international-mobile-number-verification-api-and-sdk)
  * [課題追跡とプロジェクト管理](#issue-tracking-and-project-management)
  * [ログ管理](#log-management)
  * [モバイルアプリの配布とフィードバック](#mobile-app-distribution-and-feedback)
  * [管理システム](#management-system)
  * [メッセージングとストリーミング](#messaging-and-streaming)
  * [その他](#miscellaneous)
  * [モニタリング](#monitoring)
  * [PaaS](#paas)
  * [パッケージビルドシステム](#package-build-system)
  * [支払いと課金の統合](#payment-and-billing-integration)
  * [プライバシー管理](#privacy-management)
  * [スクリーンショットAPI](#screenshot-apis)
  * [Flutter関連とMacなしでのiOSアプリ開発](#flutter-related-and-building-ios-apps-without-mac)
  * [検索](#search)
  * [セキュリティとPKI](#security-and-pki)
  * [認証、認可、ユーザー管理](#authentication-authorization-and-user-management)
  * [ソースコードリポジトリ](#source-code-repos)
  * [ストレージとメディア処理](#storage-and-media-processing)
  * [トンネリング、WebRTC、WebSocketサーバー、その他のルーター](#tunneling-webrtc-web-socket-servers-and-other-routers)
  * [テスト](#testing)
  * [チームとコラボレーションのためのツール](#tools-for-teams-and-collaboration)
  * [翻訳管理](#translation-management)
  * [Vagrant関連](#vagrant-related)
  * [訪問者セッション記録](#visitor-session-recording)
  * [Webホスティング](#web-hosting)
  * [コメントプラットフォーム](#commenting-platforms)
  * [ブラウザベースのハードウェアエミュレーション](#browser-based-hardware-emulation-written-in-javascript)
  * [リモートデスクトップツール](#remote-desktop-tools)
  * [ゲーム開発](#game-development)
  * [その他の無料リソース](#other-free-resources)

## 主要クラウドプロバイダー

  * [Google Cloud Platform](https://cloud.google.com)
    * App Engine - 1日28時間のフロントエンドインスタンス、9時間のバックエンドインスタンス
    * Cloud Firestore - 1GBのストレージ、1日50,000回の読み取り、20,000回の書き込み、20,000回の削除
    * Compute Engine - 1台の非プリエンプティブルe2-micro、30GB HDD、5GBスナップショットストレージ(特定のリージョンに制限)、北米から全リージョン向け(中国とオーストラリアを除く)に月1GBのネットワークエグレス
    * Cloud Storage - 5GB、1GBのネットワークエグレス
    * Cloud Shell - WebベースのLinuxシェル/プライマリIDE、5GBの永続ストレージ。週60時間の制限
    * Cloud Pub/Sub - 月10GBのメッセージ
    * Cloud Functions - 月200万回の呼び出し(バックグラウンドとHTTP呼び出しを含む)
    * Cloud Run - 月200万リクエスト、360,000GB-秒のメモリ、180,000 vCPU-秒の計算時間、北米から月1GBのネットワークエグレス
    * Google Kubernetes Engine - 1つのゾーンクラスターに対してクラスター管理料金なし。各ユーザーノードは標準のCompute Engine価格で課金
    * BigQuery - 月1TBのクエリ、月10GBのストレージ
    * Cloud Build - 1日120ビルド分
    * Cloud Source Repositories - 最大5ユーザー、50GBストレージ、50GBエグレス
    * [Google Colab](https://colab.research.google.com/) - 無料のJupyterノートブック開発環境
    * [idx.dev](https://idx.dev) Google Project IDX。Google Cloud上で動作するオンラインVSCode
    * 詳細な一覧 - https://cloud.google.com/free

  * [Amazon Web Services](https://aws.amazon.com)
    * [CloudFront](https://aws.amazon.com/cloudfront/) - 月1TBのエグレスと200万回のFunction呼び出し
    * [CloudWatch](https://aws.amazon.com/cloudwatch/) - 10個のカスタムメトリクスと10個のアラーム
    * [CodeBuild](https://aws.amazon.com/codebuild/) - 月100分のビルド時間
    * [CodeCommit](https://aws.amazon.com/codecommit/) - 5アクティブユーザー、50GBストレージ、月10,000リクエスト
    * [CodePipeline](https://aws.amazon.com/codepipeline/) - 月1アクティブパイプライン
    * [DynamoDB](https://aws.amazon.com/dynamodb/) - 25GB NoSQL DB
    * [EC2](https://aws.amazon.com/ec2/) - 月750時間のt2.microまたはt3.micro(12ヶ月)。月100GBのエグレス
    * [EBS](https://aws.amazon.com/ebs/) - 月30GBの汎用(SSD)またはマグネティック(12ヶ月)
    * [Elastic Load Balancing](https://aws.amazon.com/elasticloadbalancing/) - 月750時間(12ヶ月)
    * [RDS](https://aws.amazon.com/rds/) - 月750時間のdb.t2.micro、db.t3.micro、またはdb.t4g.micro、20GBの汎用(SSD)ストレージ、20GBのストレージバックアップ(12ヶ月)
    * [S3](https://aws.amazon.com/s3/) - 5GB標準オブジェクトストレージ、20,000回のGet要求と2,000回のPut要求(12ヶ月)
    * [Glacier](https://aws.amazon.com/glacier/) - 10GB長期オブジェクトストレージ
    * [Lambda](https://aws.amazon.com/lambda/) - 月100万リクエスト
    * [SNS](https://aws.amazon.com/sns/) - 月100万パブリッシュ
    * [SES](https://aws.amazon.com/ses/) - 月3,000メッセージ(12ヶ月)
    * [SQS](https://aws.amazon.com/sqs/) - 100万メッセージングキューリクエスト
    * 詳細な一覧 - https://aws.amazon.com/free/

  * [Microsoft Azure](https://azure.microsoft.com)
    * [Virtual Machines](https://azure.microsoft.com/services/virtual-machines/) - 1台のB1S Linux VM、1台のB1S Windows VM(12ヶ月)
    * [App Service](https://azure.microsoft.com/services/app-service/) - 10個のWeb、モバイル、またはAPIアプリ(1日60 CPU分)
    * [Functions](https://azure.microsoft.com/services/functions/) - 月100万リクエスト
    * [DevTest Labs](https://azure.microsoft.com/services/devtest-lab/) - 高速、簡単、リーンな開発テスト環境の有効化
    * [Active Directory](https://azure.microsoft.com/services/active-directory/) - 500,000オブジェクト
    * [Active Directory B2C](https://azure.microsoft.com/services/active-directory/external-identities/b2c/) - 月50,000保存ユーザー
    * [Azure DevOps](https://azure.microsoft.com/services/devops/) - 5アクティブユーザー、無制限のプライベートGitリポジトリ
    * [Azure Pipelines](https://azure.microsoft.com/services/devops/pipelines/) - オープンソース向けに10個の無料並列ジョブ(Linux、macOS、Windows)で無制限の分数
    * [Microsoft IoT Hub](https://azure.microsoft.com/services/iot-hub/) - 1日8,000メッセージ
    * [Load Balancer](https://azure.microsoft.com/services/load-balancer/) - 1つの無料パブリックロードバランサーIP(VIP)
    * [Notification Hubs](https://azure.microsoft.com/services/notification-hubs/) - 100万プッシュ通知
    * [Bandwidth](https://azure.microsoft.com/pricing/details/bandwidth/) - 15GBインバウンド(12ヶ月)と月5GBエグレス
    * [Cosmos DB](https://azure.microsoft.com/services/cosmos-db/) - 25GBストレージと1,000 RUのプロビジョニングされたスループット
    * [Static Web Apps](https://azure.microsoft.com/pricing/details/app-service/static/) - 静的アプリとサーバーレス関数の構築、デプロイ、ホスティング。無料SSL、認証/認可、カスタムドメイン付き
    * [Storage](https://azure.microsoft.com/services/storage/) - 5GB LRSファイルまたはBlobストレージ(12ヶ月)
    * [Cognitive Services](https://azure.microsoft.com/services/cognitive-services/) - AI/ML API(コンピュータービジョン、翻訳、顔検出、ボットなど)に限定された取引を含む無料プラン
    * [Cognitive Search](https://azure.microsoft.com/services/search/#features) - AI基盤の検索とインデックス作成サービス、10,000ドキュメントまで無料
    * [Azure Kubernetes Service](https://azure.microsoft.com/services/kubernetes-service/) - マネージドKubernetesサービス、クラスター管理無料
    * [Event Grid](https://azure.microsoft.com/services/event-grid/) - 月10万操作
    * 詳細な一覧 - https://azure.microsoft.com/free/

  * [Oracle Cloud](https://www.oracle.com/cloud/)
    * Compute
       - 1/8 OCPUと1GBメモリを持つ2台のAMDベースのCompute VM
       - 4つのArm-based Ampere A1コアと24GBのメモリを1台のVMまたは最大4台のVMとして使用可能
       - インスタンスは[アイドル状態と判断された場合](https://docs.oracle.com/en-us/iaas/Content/FreeTier/freetier_topic-Always_Free_Resources.htm#compute__idleinstances)に回収される
    * Block Volume - 2ボリューム、合計200GB(コンピュート用)
    * Object Storage - 10GB
    * Load Balancer - 10Mbpsの1インスタンス
    * Databases - 20GBずつの2つのDB
    * Monitoring - 5億のデータポイント取り込み、10億のデータポイント取得
    * Bandwidth - 月10TBエグレス、x64ベースVMは50Mbps、ARMベースVMはコア数×500Mbpsに速度制限
    * Public IP - VM用に2つのIPv4、ロードバランサー用に1つのIPv4
    * Notifications - 月100万配信オプション、月1,000送信メール
    * 詳細な一覧 - https://www.oracle.com/cloud/free/

  * [IBM Cloud](https://www.ibm.com/cloud/free/)
    * Cloudantデータベース - 1GBのデータストレージ
    * Db2データベース - 100MBのデータストレージ
    * API Connect - 月50,000 APIコール
    * Availability Monitoring - 月300万データポイント
    * Log Analysis - 日500MBのログ
    * 詳細な一覧 - https://www.ibm.com/cloud/free/

  * [Cloudflare](https://www.cloudflare.com/)
    * [Application Services](https://www.cloudflare.com/plans/) - 無制限のドメイン数に対する無料DNS、DDoS保護、CDN(無料SSLを含む)、ファイアウォールルールとページルール、WAF、ボット対策、ドメインごとに1つのルールの無料無制限レート制限、アナリティクス、メール転送
    * [Zero Trust & SASE](https://www.cloudflare.com/plans/zero-trust-services/) - 最大50ユーザー、24時間のアクティビティログ、3つのネットワークロケーション
    * [Cloudflare Tunnel](https://www.cloudflare.com/products/tunnel/) - ローカルで実行中のHTTPポートをtrycloudflare.comのランダムサブドメインを通じてトンネル経由で公開できます。[Quick Tunnels](https://developers.cloudflare.com/cloudflare-one/connections/connect-networks/do-more-with-tunnels/trycloudflare/)を使用、アカウント不要。より多くの機能(TCPトンネル、ロードバランシング、VPN)は[Zero Trust](https://www.cloudflare.com/products/zero-trust/)無料プランで利用可能。
    * [Workers](https://developers.cloudflare.com/workers/) - Cloudflareのグローバルネットワーク上で無料のサーバーレスコードを展開—1日10万リクエスト。
    * [Workers KV](https://developers.cloudflare.com/kv) - 1日10万読み取りリクエスト、1日1,000書き込みリクエスト、1日1,000削除リクエスト、1日1,000リストリクエスト、1GB保存データ
    * [R2](https://developers.cloudflare.com/r2/) - 月10GB、月100万Class A操作、月1,000万Class B操作
    * [D1](https://developers.cloudflare.com/d1/) - 1日500万行読み取り、1日10万行書き込み、1GBストレージ
    * [Pages](https://developers.cloudflare.com/pages/) - Cloudflareの高速で安全なグローバルネットワーク上でWebアプリを開発およびデプロイ。月500ビルド、100カスタムドメイン、統合SSL、無制限のアクセス可能なシート、無制限のプレビューデプロイメント、およびCloudflare Workers統合によるフルスタック機能。
    * [Queues](https://developers.cloudflare.com/queues/) - 月100万操作
    * [TURN](https://developers.cloudflare.com/calls/turn/) – 月1TBの無料(アウトバウンド)トラフィック。

**[⬆️ 目次に戻る](#table-of-contents)**

## クラウド管理ソリューション

  * [Brainboard](https://www.brainboard.co) - クラウドインフラストラクチャをエンドツーエンドで視覚的に構築および管理するためのコラボレーションソリューション。
  * [Cloud 66](https://www.cloud66.com/) - 個人プロジェクト向けに無料(1つのデプロイメントサーバー、1つの静的サイトを含む)。Cloud 66は、「サーバー関連」の頭痛の種なしに、任意のクラウド上でアプリケーションを構築、デプロイ、成長させるために必要なすべてを提供します。
  * [Pulumi](https://www.pulumi.com/) - 馴染みのあるプログラミング言語とツールを使用してクラウドインフラストラクチャを構築、デプロイ、管理するためのモダンなインフラストラクチャ・アズ・コード・プラットフォーム。
  * [terraform.io](https://www.terraform.io/) - Terraform Cloud。最大500リソースまでの無料リモート状態管理とチームコラボレーション。
  * [scalr.com](https://scalr.com/) - ScalrはTerraformの自動化とコラボレーション(TACO)製品で、Terraformで管理されるインフラストラクチャと構成に関するより良いコラボレーションと自動化に使用されます。完全なTerraform CLIサポート、OPA統合、階層的な構成モデル。SSOの制限なし。すべての機能が含まれています。月50回の実行まで無料で使用できます。
  * [deployment.io](https://deployment.io) - Deployment.ioは開発者がAWS上でデプロイメントを自動化するのを支援します。無料プランでは、開発者(単一ユーザー)は無制限の静的サイト、Webサービス、環境をデプロイできます。無料プランではプレビューと自動デプロイを含む月20回のジョブ実行を提供します。

**[⬆️ 目次に戻る](#table-of-contents)**

## ソースコードリポジトリ

  * [Bitbucket](https://bitbucket.org/) - CI/CD用のPipelinesを含む、最大5ユーザーまでの無制限のパブリックおよびプライベートGitリポジトリ
  * [chiselapp.com](https://chiselapp.com/) - 無制限のパブリックおよびプライベートFossilリポジトリ
  * [codebasehq.com](https://www.codebasehq.com/) - 100MBのスペースと2ユーザーで1つの無料プロジェクト
  * [Codeberg](https://codeberg.org/) - 無料およびオープンソースプロジェクト向けの無制限のパブリックおよびプライベートGitリポジトリ(無制限のコラボレーター付き)。[Forgejo](https://forgejo.org/)を基盤としています。[Codeberg Pages](https://codeberg.page/)による静的Webサイトホスティング。[CodebergのCI](https://docs.codeberg.org/ci/)によるCI/CDホスティング。[Codeberg Translate](https://translate.codeberg.org/)による翻訳ホスティング。パッケージとコンテナのホスティング、プロジェクト管理、課題追跡を含みます
  * [GitGud](https://gitgud.io) - GitLabとSapphireを基盤とした無制限のプライベートおよびパブリックリポジトリ。永久に無料。CI/CDは提供されません。
  * [GitHub](https://github.com/) - 無制限のパブリックリポジトリと無制限のプライベートリポジトリ(無制限のコラボレーター付き)。CI/CD、開発環境、静的ホスティング、パッケージとコンテナのホスティング、プロジェクト管理、AIコパイロットを含みます
  * [gitlab.com](https://about.gitlab.com/) - 最大5コラボレーターまでの無制限のパブリックおよびプライベートGitリポジトリ。CI/CD、静的ホスティング、コンテナレジストリ、プロジェクト管理、課題追跡を含みます
  * [framagit.org](https://framagit.org/) - FramagitはGitlabソフトウェアに基づくFramasoftのソフトウェアフォージで、CI、静的ページ、プロジェクトページ、課題追跡を含みます。
  * [heptapod.net](https://foss.heptapod.net/) - HeptapodはGitLab Community Editionのフレンドリーなフォークで、Mercurialのサポートを提供します
  * [ionicframework.com](https://ionicframework.com/appflow) - Ionicを使用したアプリケーションを開発するためのリポジトリとツール。ionicリポジトリも含みます
  * [NotABug](https://notabug.org) - NotABug.orgは自由なソフトウェアのコードコラボレーションプラットフォームで、自由にライセンスされたプロジェクト向け、Gitベース
  * [OSDN](https://osdn.net/) - OSDN.netはオープンソースソフトウェア開発者向けの無料サービスで、SVN/Git/Mercurial/Bazaar/CVSリポジトリを提供します。
  * [Pagure.io](https://pagure.io) - Pagure.ioは自由でオープンソースのソフトウェアコードコラボレーションプラットフォームで、FOSSライセンスのプロジェクト向け、Gitベース
  * [perforce.com](https://www.perforce.com/products/helix-teamhub) - 1GBのクラウドとGit、Mercurial、またはSVNリポジトリが無料。
  * [pijul.com](https://pijul.com/) - 無制限の無料でオープンソースの分散バージョン管理システム。その特徴的な機能はパッチの健全な理論に基づいており、学習、使用、配布が容易です。git/hg/svn/darcsの多くの問題を解決します。
  * [plasticscm.com](https://plasticscm.com/) - 個人、OSS、非営利組織向けに無料
  * [projectlocker.com](https://projectlocker.com) - 50MBのスペースで1つの無料プライベートプロジェクト(GitとSubversion)
  * [RocketGit](https://rocketgit.com) - Gitに基づくリポジトリホスティング。無制限のパブリックおよびプライベートリポジトリ。
  * [savannah.gnu.org](https://savannah.gnu.org/) - GNUプロジェクト向けの自由ソフトウェアプロジェクトのコラボレーティブソフトウェア開発管理システムとして機能します
  * [savannah.nongnu.org](https://savannah.nongnu.org/) - 非GNUプロジェクト向けの自由ソフトウェアプロジェクトのコラボレーティブソフトウェア開発管理システムとして機能します

**[⬆️ 目次に戻る](#table-of-contents)**

## API、データ、ML

  * [JSONGrid](https://jsongrid.com) - 複雑なJSONデータを視覚化、編集、フィルタリングして美しい表形式のグリッドに変換する無料ツール。リンクを介してJSONデータを保存および共有できます。
  * [Zerosheets](https://zerosheets.com) - Google Sheetsスプレッドシートを強力なAPIに変換し、プロトタイプ、Webサイト、アプリなどを迅速に開発できます。月500リクエストまで無料。
  * [IP.City](https://ip.city) - 1日100回の無料IPジオロケーションリクエスト
  * [Abstract API](https://www.abstractapi.com) - IPジオロケーション、性別検出、メール検証などの様々なユースケース向けのAPIスイート。
  * [Apify](https://www.apify.com/) - WebスクレイピングとオートメーションプラットフォームでWebサイトのAPIを作成しデータを抽出します。準備済みのスクレイパー、統合されたプロキシ、カスタムソリューション。無料プランには$5のプラットフォームクレジットが毎月含まれます。
  * [主要クラウドプロバイダーの常時無料枠](#major-cloud-providers)
  * [クラウド管理ソリューション](#cloud-management-solutions)
  * [分析、イベント、統計](#analytics-events-and-statistics)
  * [API、データ、ML](#apis-data-and-ml)
  * [アーティファクトリポジトリ](#artifact-repos)
  * [BaaS](#baas)
  * [ローコードプラットフォーム](#low-code-platform)
  * [CDNと保護](#cdn-and-protection)
  * [CIとCD](#ci-and-cd)
  * [CMS](#cms)
  * [コード生成](#code-generation)
  * [コード品質](#code-quality)
  * [コード検索とブラウジング](#code-search-and-browsing)
  * [クラッシュと例外処理](#crash-and-exception-handling)
  * [地図上のデータ可視化](#data-visualization-on-maps)
  * [マネージドデータサービス](#managed-data-services)
  * [デザインとUI](#design-and-ui)
  * [デザインインスピレーション](#design-inspiration)
  * [開発者ブログサイト](#dev-blogging-sites)
  * [DNS](#dns)
  * [Docker関連](#docker-related)
  * [ドメイン](#domain)
  * [教育とキャリア開発](#education-and-career-development)
  * [メール](#email)
  * [機能トグル管理プラットフォーム](#feature-toggles-management-platforms)
  * [フォント](#font)
  * [フォーム](#forms)
  * [生成AI](#generative-ai)
  * [IaaS](#iaas)
  * [IDEとコード編集](#ide-and-code-editing)
  * [国際携帯電話番号認証APIとSDK](#international-mobile-number-verification-api-and-sdk)
  * [課題追跡とプロジェクト管理](#issue-tracking-and-project-management)
  * [ログ管理](#log-management)
  * [モバイルアプリの配布とフィードバック](#mobile-app-distribution-and-feedback)
  * [管理システム](#management-system)
  * [メッセージングとストリーミング](#messaging-and-streaming)
  * [その他](#miscellaneous)
  * [モニタリング](#monitoring)
  * [PaaS](#paas)
  * [パッケージビルドシステム](#package-build-system)
  * [支払いと課金の統合](#payment-and-billing-integration)
  * [プライバシー管理](#privacy-management)
  * [スクリーンショットAPI](#screenshot-apis)
  * [Flutter関連とMacなしでのiOSアプリ開発](#flutter-related-and-building-ios-apps-without-mac)
  * [検索](#search)
  * [セキュリティとPKI](#security-and-pki)
  * [認証、認可、ユーザー管理](#authentication-authorization-and-user-management)
  * [ソースコードリポジトリ](#source-code-repos)
  * [ストレージとメディア処理](#storage-and-media-processing)
  * [トンネリング、WebRTC、WebSocketサーバー、その他のルーター](#tunneling-webrtc-web-socket-servers-and-other-routers)
  * [テスト](#testing)
  * [チームとコラボレーションのためのツール](#tools-for-teams-and-collaboration)
  * [翻訳管理](#translation-management)
  * [Vagrant関連](#vagrant-related)
  * [訪問者セッション記録](#visitor-session-recording)
  * [Webホスティング](#web-hosting)
  * [コメントプラットフォーム](#commenting-platforms)
  * [ブラウザベースのハードウェアエミュレーション](#browser-based-hardware-emulation-written-in-javascript)
  * [リモートデスクトップツール](#remote-desktop-tools)
  * [ゲーム開発](#game-development)
  * [その他の無料リソース](#other-free-resources)

## 主要クラウドプロバイダー

  * [Google Cloud Platform](https://cloud.google.com)
    * App Engine - 1日あたりフロントエンドインスタンス28時間、バックエンドインスタンス9時間
    * Cloud Firestore - 1GBのストレージ、1日あたり50,000回の読み取り、20,000回の書き込み、20,000回の削除
    * Compute Engine - 非プリエンプティブルe2-micro 1台、30GB HDD、5GBスナップショットストレージ(特定のリージョンに制限)、北米から全リージョン(中国とオーストラリアを除く)への1GBのネットワークエグレス/月
    * Cloud Storage - 5GB、1GBネットワークエグレス
    * Cloud Shell - WebベースのLinuxシェル/プライマリIDE、5GBの永続ストレージ付き。週60時間の制限
    * Cloud Pub/Sub - 月10GBのメッセージ
    * Cloud Functions - 月200万回の呼び出し(バックグラウンドとHTTP呼び出しを含む)
    * Cloud Run - 月200万リクエスト、360,000 GB秒のメモリ、180,000 vCPU秒の計算時間、北米から月1GBのネットワークエグレス
    * Google Kubernetes Engine - ゾーンクラスタ1つのクラスタ管理料金無料。各ユーザーノードは標準Compute Engine料金で課金
    * BigQuery - 月1TBのクエリ、月10GBのストレージ
    * Cloud Build - 1日120ビルド分
    * Cloud Source Repositories - 最大5ユーザー、50GBストレージ、50GBエグレス
    * [Google Colab](https://colab.research.google.com/) - 無料のJupyter Notebooks開発環境
    * [idx.dev](https://idx.dev) Google Project IDX。Google Cloud上で動作するオンラインVSCode
    * 完全な詳細リスト - https://cloud.google.com/free

  * [Amazon Web Services](https://aws.amazon.com)
    * [CloudFront](https://aws.amazon.com/cloudfront/) - 月1TBのエグレスと月200万回のFunction呼び出し
    * [CloudWatch](https://aws.amazon.com/cloudwatch/) - 10個のカスタムメトリクスと10個のアラーム
    * [CodeBuild](https://aws.amazon.com/codebuild/) - 月100分のビルド時間
    * [CodeCommit](https://aws.amazon.com/codecommit/) - 5アクティブユーザー、50GBストレージ、月10,000リクエスト
    * [CodePipeline](https://aws.amazon.com/codepipeline/) - 月1アクティブパイプライン
    * [DynamoDB](https://aws.amazon.com/dynamodb/) - 25GB NoSQL DB
    * [EC2](https://aws.amazon.com/ec2/) - t2.microまたはt3.microの750時間/月(12ヶ月)。月100GBエグレス
    * [EBS](https://aws.amazon.com/ebs/) - 汎用(SSD)または磁気の30GB/月(12ヶ月)
    * [Elastic Load Balancing](https://aws.amazon.com/elasticloadbalancing/) - 750時間/月(12ヶ月)
    * [RDS](https://aws.amazon.com/rds/) - db.t2.micro、db.t3.micro、またはdb.t4g.microの750時間/月、汎用(SSD)ストレージ20GB、ストレージバックアップ20GB(12ヶ月)
    * [S3](https://aws.amazon.com/s3/) - 標準オブジェクトストレージ5GB、20,000回のGetリクエストと2,000回のPutリクエスト(12ヶ月)
    * [Glacier](https://aws.amazon.com/glacier/) - 長期オブジェクトストレージ10GB
    * [Lambda](https://aws.amazon.com/lambda/) - 月100万リクエスト
    * [SNS](https://aws.amazon.com/sns/) - 月100万パブリッシュ
    * [SES](https://aws.amazon.com/ses/) - 月3,000メッセージ(12ヶ月)
    * [SQS](https://aws.amazon.com/sqs/) - 100万メッセージングキューリクエスト
    * 完全な詳細リスト - https://aws.amazon.com/free/

  * [Microsoft Azure](https://azure.microsoft.com)
    * [Virtual Machines](https://azure.microsoft.com/services/virtual-machines/) - B1S Linux VM 1台、B1S Windows VM 1台(12ヶ月)
    * [App Service](https://azure.microsoft.com/services/app-service/) - 10個のWeb、モバイル、またはAPIアプリ(1日60 CPU分)
    * [Functions](https://azure.microsoft.com/services/functions/) - 月100万リクエスト
    * [DevTest Labs](https://azure.microsoft.com/services/devtest-lab/) - 高速、簡単、リーンな開発テスト環境を実現
    * [Active Directory](https://azure.microsoft.com/services/active-directory/) - 500,000オブジェクト
    * [Active Directory B2C](https://azure.microsoft.com/services/active-directory/external-identities/b2c/) - 月50,000保存ユーザー
    * [Azure DevOps](https://azure.microsoft.com/services/devops/) - 5アクティブユーザー、無制限のプライベートGitリポジトリ
    * [Azure Pipelines](https://azure.microsoft.com/services/devops/pipelines/) - オープンソース向けに10個の無料並列ジョブと無制限の分数(Linux、macOS、Windows)
    * [Microsoft IoT Hub](https://azure.microsoft.com/services/iot-hub/) - 1日8,000メッセージ
    * [Load Balancer](https://azure.microsoft.com/services/load-balancer/) - 1つの無料パブリックロードバランサーIP(VIP)
    * [Notification Hubs](https://azure.microsoft.com/services/notification-hubs/) - 100万プッシュ通知
    * [Bandwidth](https://azure.microsoft.com/pricing/details/bandwidth/) - インバウンド15GB(12ヶ月)&月5GBエグレス
    * [Cosmos DB](https://azure.microsoft.com/services/cosmos-db/) - 25GBストレージと1,000 RUのプロビジョニングされたスループット
    * [Static Web Apps](https://azure.microsoft.com/pricing/details/app-service/static/) - 無料SSL、認証/認可、カスタムドメインを備えた静的アプリとサーバーレス関数のビルド、デプロイ、ホスティング
    * [Storage](https://azure.microsoft.com/services/storage/) - 5GB LRSファイルまたはBlobストレージ(12ヶ月)
    * [Cognitive Services](https://azure.microsoft.com/services/cognitive-services/) - 限定トランザクションを含む無料枠のAI/ML API(コンピュータービジョン、翻訳、顔検出、ボットなど)
    * [Cognitive Search](https://azure.microsoft.com/services/search/#features) - AIベースの検索・インデックス作成サービス、10,000ドキュメントまで無料
    * [Azure Kubernetes Service](https://azure.microsoft.com/services/kubernetes-service/) - マネージドKubernetesサービス、クラスター管理無料
    * [Event Grid](https://azure.microsoft.com/services/event-grid/) - 月10万オペレーション
    * 完全な詳細リスト - https://azure.microsoft.com/free/

  * [Oracle Cloud](https://www.oracle.com/cloud/)
    * コンピュート
       - 1/8 OCPUと1GBメモリを持つAMDベースのコンピュートVM 2台
       - 4つのArm-basedのAmpere A1コアと24GBのメモリを1台のVMまたは最大4台のVMとして使用可能
       - インスタンスは[アイドル状態と判断された場合](https://docs.oracle.com/en-us/iaas/Content/FreeTier/freetier_topic-Always_Free_Resources.htm#compute__idleinstances)に回収される
    * ブロックボリューム - 2ボリューム、合計200GB(コンピュート用)
    * オブジェクトストレージ - 10GB
    * ロードバランサー - 10Mbpsの1インスタンス
    * データベース - 2つのDB、各20GB
    * モニタリング - 5億のデータポイント取り込み、10億のデータポイント取得
    * 帯域幅 - 月10TBのエグレス、x64ベースVMは50Mbpsに速度制限、ARMベースVMはコア数×500Mbps
    * パブリックIP - VM用に2つのIPv4、ロードバランサー用に1つのIPv4
    * 通知 - 月100万の配信オプション、月1000通の送信メール
    * 完全な詳細リスト - https://www.oracle.com/cloud/free/

  * [IBM Cloud](https://www.ibm.com/cloud/free/)
    * Cloudantデータベース - 1GBのデータストレージ
    * Db2データベース - 100MBのデータストレージ
    * API Connect - 月50,000回のAPI呼び出し
    * 可用性モニタリング - 月300万データポイント
    * ログ分析 - 日次500MBのログ
    * 完全な詳細リスト - https://www.ibm.com/cloud/free/

  * [Cloudflare](https://www.cloudflare.com/)
    * [アプリケーションサービス](https://www.cloudflare.com/plans/) - 無制限のドメインに対する無料DNS、DDoS保護、CDN、無料SSL、ファイアウォールルールとページルール、WAF、ボット対策、無制限の無料レート制限(ドメインあたり1ルール)、アナリティクス、メール転送
    * [ゼロトラスト & SASE](https://www.cloudflare.com/plans/zero-trust-services/) - 最大50ユーザー、24時間のアクティビティログ、3つのネットワークロケーション
    * [Cloudflare Tunnel](https://www.cloudflare.com/products/tunnel/) - [Quick Tunnels](https://developers.cloudflare.com/cloudflare-one/connections/connect-networks/do-more-with-tunnels/trycloudflare/)を使用してローカルで実行中のHTTPポートをtrycloudflare.comのランダムサブドメインにトンネル経由で公開可能。アカウント不要。より多くの機能(TCPトンネル、ロードバランシング、VPN)は[Zero Trust](https://www.cloudflare.com/products/zero-trust/)無料プランで利用可能。
    * [Workers](https://developers.cloudflare.com/workers/) - Cloudflareのグローバルネットワーク上で無料でサーバーレスコードをデプロイ - 日次10万リクエスト。
    * [Workers KV](https://developers.cloudflare.com/kv) - 日次10万読み取りリクエスト、1000書き込みリクエスト、1000削除リクエスト、1000一覧リクエスト、1GBの保存データ
    * [R2](https://developers.cloudflare.com/r2/) - 月10GB、月100万のクラスA操作、月1000万のクラスB操作
    * [D1](https://developers.cloudflare.com/d1/) - 日次500万行の読み取り、日次10万行の書き込み、1GBストレージ
    * [Pages](https://developers.cloudflare.com/pages/) - Cloudflareの高速で安全なグローバルネットワーク上でWebアプリを開発・デプロイ。月500ビルド、100カスタムドメイン、統合SSL、無制限のアクセス可能なシート、無制限のプレビューデプロイメント、Cloudflare Workers統合によるフルスタック機能。
    * [Queues](https://developers.cloudflare.com/queues/) - 月100万操作
    * [TURN](https://developers.cloudflare.com/calls/turn/) - 月1TBの無料(アウトバウンド)トラフィック。

**[⬆️ 目次に戻る](#table-of-contents)**

## クラウド管理ソリューション

  * [Brainboard](https://www.brainboard.co) - クラウドインフラをエンドツーエンドで視覚的に構築・管理するコラボレーションソリューション。
  * [Cloud 66](https://www.cloud66.com/) - 個人プロジェクト向けに無料(1つのデプロイメントサーバー、1つの静的サイトを含む)。Cloud 66は「サーバー関連」の頭痛の種なしに、任意のクラウド上でアプリケーションを構築、デプロイ、成長させるために必要なすべてを提供。
  * [Pulumi](https://www.pulumi.com/) - 馴染みのあるプログラミング言語とツールを使用してクラウドインフラを構築、デプロイ、管理できる最新のインフラストラクチャ・アズ・コード・プラットフォーム。
  * [terraform.io](https://www.terraform.io/) - Terraform Cloud。最大500リソースまでのリモート状態管理とチームコラボレーションが無料。
  * [scalr.com](https://scalr.com/) - ScalrはTerraformで管理されるインフラストラクチャと構成のより良いコラボレーションと自動化のためのTerraform Automation and COllaboration (TACO)製品。完全なTerraform CLIサポート、OPA統合、階層的構成モデル。SSOの制限なし。すべての機能が含まれます。月50実行まで無料で使用可能。
  * [deployment.io](https://deployment.io) - Deployment.ioは開発者がAWS上でのデプロイメントを自動化するのを支援。無料枠では、開発者(単一ユーザー)は無制限の静的サイト、Webサービス、環境をデプロイ可能。無料枠にはプレビューと自動デプロイを含む月20ジョブ実行を提供。

**[⬆️ 目次に戻る](#table-of-contents)**

## アーティファクトリポジトリ

  * [Artifactory](https://jfrog.com/start-free/) — Maven、Docker、Cargo、Helm、PyPI、CocoaPods、GitLFSなど多数のパッケージフォーマットをサポートするアーティファクトリポジトリ。パッケージスキャンツールXRayとCI/CDツールPipelines(旧Shippable)を含み、月2,000 CI/CD分の無料枠があります。
  * [central.sonatype.org](https://central.sonatype.org) — Apache Maven、SBT、その他のビルドシステム向けのデフォルトアーティファクトリポジトリ。
  * [cloudrepo.io](https://cloudrepo.io) - クラウドベースのプライベートおよびパブリックなMavenとPyPiリポジトリ。オープンソースプロジェクトは無料。
  * [cloudsmith.io](https://cloudsmith.io) — Java/Maven、RedHat、Debian、Python、Ruby、Vagrantなど向けのシンプルで安全な一元化されたリポジトリサービス。無料枠あり + オープンソース向けに無料。
  * [jitpack.io](https://jitpack.io/) — GitHubのJVMとAndroidプロジェクト向けのMavenリポジトリ。パブリックプロジェクトは無料。
  * [packagecloud.io](https://packagecloud.io/users/new?plan=free_usage_plan) — Maven、RPM、DEB、PyPi、NPM、RubyGemパッケージ向けの使いやすいリポジトリホスティング(無料枠あり)。
  * [repsy.io](https://repsy.io) — 1GBの無料プライベート/パブリックMavenリポジトリ。
  * [Gemfury](https://gemfury.com) — Maven、PyPi、NPM、Go Module、Nuget、APT、RPMリポジトリ向けのプライベートおよびパブリックアーティファクトリポジトリ。パブリックプロジェクトは無料。
  * [paperspace](https://www.paperspace.com/) — AIモデルの構築とスケーリング、AI アプリケーションの開発、トレーニング、デプロイ。無料プラン：パブリックプロジェクト、5GBストレージ、基本インスタンス。
  * [RepoForge](https://repoforge.io) - Python、Debian、NPMパッケージとDockerレジストリ向けのプライベートクラウドホストリポジトリ。オープンソース/パブリックプロジェクトは無料。
  * [RepoFlow](https://repoflow.io) - RepoFlowはnpm、PyPI、Docker、Go、Helmなどのパッケージ管理をシンプル化。クラウドで10GBストレージ、10GBの帯域幅、100パッケージ、無制限のユーザーを無料で試用可能。個人使用のみのセルフホストも可能。

**[⬆️ 目次に戻る](#table-of-contents)**

## チームとコラボレーション向けツール

  * [3Cols](https://3cols.com/) - 個人およびコラボレーティブなコード向けの無料クラウドベースのコードスニペット管理ツール。
  * [Bitwarden](https://bitwarden.com) — 個人、チーム、ビジネス組織が機密データを保存、共有、同期する最も簡単で安全な方法。
  * [Braid](https://www.braidchat.com/) — チーム向けに設計されたチャットアプリ。パブリックアクセスグループ、無制限のユーザー、履歴、統合が無料。セルフホスト可能なオープンソースバージョンも提供。
  * [cally.com](https://cally.com/) — ミーティングの最適な日時を見つけます。使いやすく、小規模および大規模グループに最適。
  * [Calendly](https://calendly.com) — ミーティングの接続とスケジューリングのためのツール。無料プランではユーザーあたり1つのカレンダー接続と無制限のセッションを提供。デスクトップとモバイルアプリも提供。
  * [Discord](https://discord.com/) — パブリック/プライベートルームでチャット。Markdownテキスト、音声、ビデオ、画面共有機能。無制限のユーザーに対して無料。
  * [Telegram](https://telegram.org/) — 高速で信頼性の高いメッセージングと通話を求める全ての人向け。ビジネスユーザーと小規模チームは大規模グループ、ユーザー名、デスクトップアプリ、強力なファイル共有オプションを気に入るでしょう。
  * [Dubble](https://dubble.so/) — 無料のステップバイステップガイド作成ツール。スクリーンショットを撮影し、プロセスを文書化し、チームとコラボレーション。非同期画面録画もサポート。
  * [Duckly](https://duckly.com/) — チームとリアルタイムで会話とコラボレーション。IDE、ターミナル共有、音声、ビデオ、画面共有によるペアプログラミング。小規模チームは無料。
  * [Dyte](https://dyte.io) - 最も開発者フレンドリーなライブビデオ＆オーディオSDKで、生産性と関与を高めるコラボレーティブプラグインを特徴とします。無料枠には月10,000分のライブビデオ/オーディオ使用が含まれます。
  * [evernote.com](https://evernote.com/) — 情報を整理するためのツール。メモを共有し他者と協力
  * [Fibery](https://fibery.io/) — 接続されたワークスペースプラットフォーム。シングルユーザーは2GBのディスク容量まで無料。
  * [flock.com](https://flock.com) — チームがより速くコミュニケーションを取るための方法。無制限のメッセージ、チャンネル、ユーザー、アプリ、統合が無料。
  * [Gather](https://www.gather.town/) - オンラインで会うためのより良い方法。完全にカスタマイズ可能な空間を中心に、コミュニティと時間を過ごすことを実生活と同じように簡単にします。最大10人の同時ユーザーまで無料。
  * [gokanban.io](https://gokanban.io) - 登録不要の構文ベースの高速利用向けかんばんボード。制限なしで無料。
  * [flat.social](https://flat.social) - チームミーティングとハッピーアワーソーシャル向けのインタラクティブでカスタマイズ可能な空間。無制限のミーティング、最大8人の同時ユーザーまで無料。
  * [GitDailies](https://gitdailies.com) - GitHubのコミットとプルリクエストアクティビティに関するチームの日次レポート。プッシュ可視化、ピア認識システム、カスタムアラートビルダーを含みます。無料枠には無制限のユーザー、3つのリポジトリ、3つのアラート設定が含まれます。
  * [gitter.im](https://gitter.im/) — GitHub向けのチャット。最大25人のチームまで無制限のパブリックおよびプライベートルームが無料。
  * [Hackmd.io](https://hackmd.io/) - マークダウン形式のドキュメント/ファイル向けのリアルタイムコラボレーション＆執筆ツール。マークダウンファイル向けのGoogle Docsのような機能。無制限の数の「ノート」が無料ですが、プライベートノートとテンプレートのコラボレーター(招待者)の数は[制限](https://hackmd.io/pricing)されます。
  * [hangouts.google.com](https://hangouts.google.com/) — すべての会話を1つの場所に。Googleアカウントが必要で無料。
  * [HeySpace](https://hey.space) - チャット、カレンダー、タイムライン、ビデオ通話付きのタスク管理ツール。最大5ユーザーまで無料。
  * [helplightning.com](https://www.helplightning.com/) — 拡張現実を使用したビデオによるヘルプ。分析、暗号化、サポートなしで無料。
  * [ideascale.com](https://ideascale.com/) — 1コミュニティで25メンバーまでクライアントがアイデアを提出して投票することが可能。
  * [Igloo](https://www.igloosoftware.com/) — ドキュメント、ブログ、カレンダーなどを共有するための内部ポータル。最大10ユーザーまで無料。
  * [Keybase](https://keybase.io/) — KeybaseはSlackのFOSS代替で、家族からコミュニティ、企業まで、全員のチャットとファイルを安全に保ちます。
  * [Google Meet](https://meet.google.com/) — ビジネスのオンラインビデオミーティングニーズにGoogle Meetを使用。Meetは安全で参加が簡単なオンラインミーティングを提供します。
  * [/meet for Slack](https://meetslack.com) - 任意のチャンネル、グループ、DMで/meetを使用してSlackから直接Google Meetingを開始。制限なしで無料。
  * [Livecycle](https://www.livecycle.io/) — Livecycleは、クロスファンクショナルなプロダクトチームとオープンソースプロジェクトのワークフローをスムーズにする包括的なコラボレーションプラットフォームです。
  * [Lockitbot](https://www.lockitbot.com/) — Slack内で部屋、開発環境、サーバーなどの共有リソースを予約とロック。最大2つのリソースまで無料。
  * [MarkUp](https://www.markup.io/) — MarkUpを使用すると、ウェブサイト、PDF、画像の上に直接フィードバックを収集できます。
  * [Proton Pass](https://proton.me/pass) — メールエイリアス、2FA認証、共有、パスキーを内蔵したパスワードマネージャー。ウェブ、ブラウザ拡張機能、モバイルアプリ、デスクトップで利用可能。

**[⬆️ 目次に戻る](#table-of-contents)**

## アーティファクトリポジトリ

  * [Artifactory](https://jfrog.com/start-free/) — Maven、Docker、Cargo、Helm、PyPI、CocoaPods、GitLFSなど多数のパッケージフォーマットをサポートするアーティファクトリポジトリ。パッケージスキャンツールXRayとCI/CDツールPipelines(旧Shippable)を含み、月2,000 CI/CD分の無料枠があります。
  * [central.sonatype.org](https://central.sonatype.org) — Apache Maven、SBT、その他のビルドシステム向けのデフォルトアーティファクトリポジトリ。
  * [cloudrepo.io](https://cloudrepo.io) - クラウドベースのプライベートおよびパブリックなMavenとPyPiリポジトリ。オープンソースプロジェクトは無料。
  * [cloudsmith.io](https://cloudsmith.io) — Java/Maven、RedHat、Debian、Python、Ruby、Vagrantなど向けのシンプルで安全な一元化されたリポジトリサービス。無料枠あり + オープンソース向けに無料。
  * [jitpack.io](https://jitpack.io/) — GitHubのJVMとAndroidプロジェクト向けのMavenリポジトリ。パブリックプロジェクトは無料。
  * [packagecloud.io](https://packagecloud.io/users/new?plan=free_usage_plan) — Maven、RPM、DEB、PyPi、NPM、RubyGemパッケージ向けの使いやすいリポジトリホスティング(無料枠あり)。
  * [repsy.io](https://repsy.io) — 1GBの無料プライベート/パブリックMavenリポジトリ。
  * [Gemfury](https://gemfury.com) — Maven、PyPi、NPM、Go Module、Nuget、APT、RPMリポジトリ向けのプライベートおよびパブリックアーティファクトリポジトリ。パブリックプロジェクトは無料。
  * [paperspace](https://www.paperspace.com/) — AIモデルの構築とスケーリング、AI アプリケーションの開発、トレーニング、デプロイ。無料プラン：パブリックプロジェクト、5GBストレージ、基本インスタンス。
  * [RepoForge](https://repoforge.io) - Python、Debian、NPMパッケージとDockerレジストリ向けのプライベートクラウドホストリポジトリ。オープンソース/パブリックプロジェクトは無料。
  * [RepoFlow](https://repoflow.io) - RepoFlowはnpm、PyPI、Docker、Go、Helmなどのパッケージ管理をシンプル化。クラウドで10GBストレージ、10GBの帯域幅、100パッケージ、無制限のユーザーを無料で試用可能。個人使用のみのセルフホストも可能。

**[⬆️ 目次に戻る](#table-of-contents)**

## チームとコラボレーション向けツール

  * [3Cols](https://3cols.com/) - 個人およびコラボレーティブなコード向けの無料クラウドベースのコードスニペット管理ツール。
  * [Bitwarden](https://bitwarden.com) — 個人、チーム、ビジネス組織が機密データを保存、共有、同期する最も簡単で安全な方法。
  * [Braid](https://www.braidchat.com/) — チーム向けに設計されたチャットアプリ。パブリックアクセスグループ、無制限のユーザー、履歴、統合が無料。セルフホスト可能なオープンソースバージョンも提供。
  * [cally.com](https://cally.com/) — ミーティングの最適な日時を見つけます。使いやすく、小規模および大規模グループに最適。
  * [Calendly](https://calendly.com) — ミーティングの接続とスケジューリングのためのツール。無料プランではユーザーあたり1つのカレンダー接続と無制限のセッションを提供。デスクトップとモバイルアプリも提供。
  * [Discord](https://discord.com/) — パブリック/プライベートルームでチャット。Markdownテキスト、音声、ビデオ、画面共有機能。無制限のユーザーに対して無料。
  * [Telegram](https://telegram.org/) — 高速で信頼性の高いメッセージングと通話を求める全ての人向け。ビジネスユーザーと小規模チームは大規模グループ、ユーザー名、デスクトップアプリ、強力なファイル共有オプションを気に入るでしょう。
  * [Dubble](https://dubble.so/) — 無料のステップバイステップガイド作成ツール。スクリーンショットを撮影し、プロセスを文書化し、チームとコラボレーション。非同期画面録画もサポート。
  * [Duckly](https://duckly.com/) — チームとリアルタイムで会話とコラボレーション。IDE、ターミナル共有、音声、ビデオ、画面共有によるペアプログラミング。小規模チームは無料。
  * [Dyte](https://dyte.io) - 最も開発者フレンドリーなライブビデオ＆オーディオSDKで、生産性と関与を高めるコラボレーティブプラグインを特徴とします。無料枠には月10,000分のライブビデオ/オーディオ使用が含まれます。
  * [evernote.com](https://evernote.com/) — 情報を整理するためのツール。メモを共有し他者と協力
  * [Fibery](https://fibery.io/) — 接続されたワークスペースプラットフォーム。シングルユーザーは2GBのディスク容量まで無料。
  * [flock.com](https://flock.com) — チームがより速くコミュニケーションを取るための方法。無制限のメッセージ、チャンネル、ユーザー、アプリ、統合が無料。
  * [Gather](https://www.gather.town/) - オンラインで会うためのより良い方法。完全にカスタマイズ可能な空間を中心に、コミュニティと時間を過ごすことを実生活と同じように簡単にします。最大10人の同時ユーザーまで無料。
  * [gokanban.io](https://gokanban.io) - 登録不要の構文ベースの高速利用向けかんばんボード。制限なしで無料。
  * [flat.social](https://flat.social) - チームミーティングとハッピーアワーソーシャル向けのインタラクティブでカスタマイズ可能な空間。無制限のミーティング、最大8人の同時ユーザーまで無料。
  * [GitDailies](https://gitdailies.com) - GitHubのコミットとプルリクエストアクティビティに関するチームの日次レポート。プッシュ可視化、ピア認識システム、カスタムアラートビルダーを含みます。無料枠には無制限のユーザー、3つのリポジトリ、3つのアラート設定が含まれます。
  * [gitter.im](https://gitter.im/) — GitHub向けのチャット。最大25人のチームまで無制限のパブリックおよびプライベートルームが無料。
  * [Hackmd.io](https://hackmd.io/) - マークダウン形式のドキュメント/ファイル向けのリアルタイムコラボレーション＆執筆ツール。マークダウンファイル向けのGoogle Docsのような機能。無制限の数の「ノート」が無料ですが、プライベートノートとテンプレートのコラボレーター(招待者)の数は[制限](https://hackmd.io/pricing)されます。
  * [hangouts.google.com](https://hangouts.google.com/) — すべての会話を1つの場所に。Googleアカウントが必要で無料。
  * [HeySpace](https://hey.space) - チャット、カレンダー、タイムライン、ビデオ通話付きのタスク管理ツール。最大5ユーザーまで無料。
  * [helplightning.com](https://www.helplightning.com/) — 拡張現実を使用したビデオによるヘルプ。分析、暗号化、サポートなしで無料。
  * [ideascale.com](https://ideascale.com/) — 1コミュニティで25メンバーまでクライアントがアイデアを提出して投票することが可能。
  * [Igloo](https://www.igloosoftware.com/) — ドキュメント、ブログ、カレンダーなどを共有するための内部ポータル。最大10ユーザーまで無料。
  * [Keybase](https://keybase.io/) — KeybaseはSlackのFOSS代替で、家族からコミュニティ、企業まで、全員のチャットとファイルを安全に保ちます。
  * [Google Meet](https://meet.google.com/) — ビジネスのオンラインビデオミーティングニーズにGoogle Meetを使用。Meetは安全で参加が簡単なオンラインミーティングを提供します。
  * [/meet for Slack](https://meetslack.com) - 任意のチャンネル、グループ、DMで/meetを使用してSlackから直接Google Meetingを開始。制限なしで無料。
  * [Livecycle](https://www.livecycle.io/) — Livecycleは、クロスファンクショナルなプロダクトチームとオープンソースプロジェクトのワークフローをスムーズにする包括的なコラボレーションプラットフォームです。
  * [Lockitbot](https://www.lockitbot.com/) — Slack内で部屋、開発環境、サーバーなどの共有リソースを予約とロック。最大2つのリソースまで無料。
  * [MarkUp](https://www.markup.io/) — MarkUpを使用すると、ウェブサイト、PDF、画像の上に直接フィードバックを収集できます。
  * [Proton Pass](https://proton.me/pass) — メールエイリアス、2FA認証、共有、パスキーを内蔵したパスワードマネージャー。ウェブ、ブラウザ拡張機能、モバイルアプリ、デスクトップで利用可能。
  * [Visual Debug](https://visualdebug.com) - クライアントと開発者のコミュニケーションを改善するビジュアルフィードバックツール
  * [meet.jit.si](https://meet.jit.si/) — ワンクリックのビデオ会話と画面共有が無料
  * [Microsoft Teams](https://products.office.com/microsoft-teams/free) — Microsoft Teamsは、会話、コンテンツ、アプリを1つの場所に集めるチャットベースのデジタルハブです。最大500kユーザーまで無料。
  * [Miro](https://miro.com/) - 分散チーム向けのスケーラブルで安全なクロスデバイス対応のエンタープライズ対応コラボレーションホワイトボード。フリーミアムプラン付き。
  * [nootiz](https://www.nootiz.com/) - あらゆるウェブサイトのビジュアルフィードバックを収集・管理するためのツール
  * [Notion](https://www.notion.so/) - Notionはマークダウンをサポートするノート作成とコラボレーションアプリケーションで、タスク、ウィキ、データベースを統合します。会社はこのアプリをノート作成、プロジェクト管理、タスク管理のためのオールインワンワークスペースとして説明しています。クロスプラットフォームアプリに加えて、ほとんどのウェブブラウザからアクセスできます。
  * [Nuclino](https://www.nuclino.com) - チームのすべての知識、ドキュメント、メモのための軽量なコラボレーティブウィキ。すべての必須機能、最大50アイテム、5GBストレージを含む無料プラン。
  * [OnlineInterview.io](https://onlineinterview.io/) - 組み込みのビデオチャット、描画ボード、ブラウザ上でコードをコンパイルして実行できるオンラインコードエディタを備えた無料のコードインタビュープラットフォーム。ワンクリックでリモートインタビュールームを作成できます。
  * [Quidlo Timesheets](https://www.quidlo.com/timesheets) - チーム向けのシンプルなタイムシートと時間追跡アプリ。無料プランには最大10ユーザーまでの時間追跡とレポート生成機能があります。
  * [PageShare.dev](https://www.pageshare.dev) - ウェブサイトをデプロイする必要なく、GitHubプルリクエストにビジュアルレビュー機能を追加。毎月最大10ページと合計100MBのストレージまで無料。
  * [Pendulums](https://pendulums.io/) - Pendulumsは使いやすいインターフェースと有用な統計情報で、より良い時間管理を支援する無料の時間追跡ツールです。
  * [Pumble](https://pumble.com) - 無料のチームチャットアプリ。無制限のユーザーとメッセージ履歴が永久に無料。
  * [Raindrop.io](https://raindrop.io) - macOS、Windows、Android、iOS、Webのためのプライベートで安全なブックマークアプリ。無制限のブックマークとコラボレーションが無料。
  * [element.io](https://element.io/) — Matrixで構築された分散型でオープンソースのコミュニケーションツール。グループチャット、ダイレクトメッセージング、暗号化されたファイル転送、音声とビデオチャット、他のサービスとの簡単な統合。
  * [Rocket.Chat](https://rocket.chat/) - オムニチャネル機能、Matrix Federation、他のアプリとのブリッジ、無制限のメッセージング、完全なメッセージ履歴を備えたオープンソースコミュニケーションプラットフォーム。
  * [seafile.com](https://www.seafile.com/) — プライベートまたはクラウドストレージ、ファイル共有、同期、ディスカッション。クラウドバージョンは1GBのみ。
  * [Sema](https://www.semasoftware.com/) - 複数のリポジトリからの貢献を1つのレポートに統合してスナップショットを作成できる無料の開発者ポートフォリオツール。
  * [Screen Sharing via Browser](https://screensharing.net) - 無料の画面共有ツール。ダウンロードや登録不要で、ブラウザから直接コラボレーターと画面を共有。無料。
  * [Slab](https://slab.com/) — チーム向けのモダンな知識管理サービス。最大10ユーザーまで無料。
  * [slack.com](https://slack.com/) — 一部の機能制限付きで無制限のユーザーに対して無料
  * [Spectrum](https://spectrum.chat/) - パブリックまたはプライベートコミュニティを無料で作成。
  * [StatusPile](https://www.statuspile.com/) - ステータスページのステータスページ。上流プロバイダーのステータスページを追跡できますか？
  * [Stickies](https://stickies.app/) - ブレインストーミング、コンテンツキュレーション、メモに使用されるビジュアルコラボレーションアプリ。最大3つのウォール、無制限のユーザー、1GBストレージまで無料。
  * [Stacks](https://betterstacks.com/) - 情報過多に対処するための統合されたノート、リンク、ファイルストレージを備えたコンテンツワークスペース。永久に無料の個人プラン。
  * [talky.io](https://talky.io/) — 無料のグループビデオチャット。匿名。ピアツーピア。プラグイン、サインアップ、支払い不要
  * [Teamhood](https://teamhood.com/) - 無料のプロジェクト、タスク、課題追跡ソフトウェア。スイムレーン付きかんばんと完全なスクラム実装をサポート。統合された時間追跡機能あり。5ユーザーと3つのプロジェクトポートフォリオまで無料。
  * [Teamplify](https://teamplify.com) - チーム分析とスマートデイリースタンドアップでチーム開発プロセスを改善。リモートファースト向けの完全な機能を備えた休暇管理を含みます。最大5ユーザーの小規模グループまで無料。
  * [Tefter](https://tefter.io) - 強力なSlack統合を備えたブックマークアプリ。オープンソースチーム向けに無料。
  * [TeleType](https://teletype.oorja.io/) — ターミナル、音声、コード、ホワイトボードなどを共有。エンドツーエンドの暗号化されたコラボレーションのためのサインインは不要。
  * [TimeCamp](https://www.timecamp.com/) - 無制限のユーザー向けの無料時間追跡ソフトウェア。Jira、Trello、Asanaなどのプロジェクト管理ツールと簡単に統合。
  * [Huly](https://huly.io/) - オールインワンプロジェクト管理プラットフォーム(Linear、Jira、Slack、Notion、Motionの代替) - 無制限のユーザー、ワークスペースあたり10GBストレージ、10GBビデオ(オーディオ)トラフィック。
  * [Teamcamp](https://www.teamcamp.app) - ソフトウェア開発会社向けのオールインワンプロジェクト管理アプリケーション。
  * [twist.com](https://twist.com) — 会話が整理され、トピックに沿って進む非同期フレンドリーなチームコミュニケーションアプリ。無料プランと無制限プランが利用可能。対象チームには割引が提供されます。
  * [tldraw.com](https://tldraw.com) — インテリジェントな矢印、スナッピング、付箋、SVGエクスポート機能を備えた無料のオープンソースホワイトボードおよび図表作成ツール。共同編集のためのマルチプレイヤーモード。公式のVS Code拡張機能も無料で利用可能。
  * [BookmarkOS.com](https://bookmarkos.com) - フォルダコラボレーション機能を備えたカスタマイズ可能なオンラインデスクトップでの無料のオールインワンブックマークマネージャー、タブマネージャー、タスクマネージャー。
  * [typetalk.com](https://www.typetalk.com/) — ウェブまたはモバイルでのインスタントメッセージングを通じてチームとアイデアを共有・議論
  * [Tugboat](https://tugboat.qa) - すべてのプルリクエストのプレビューを自動化およびオンデマンドで提供。すべてのユーザーに無料で、非営利団体には無料のNanoティアを提供。
  * [whereby.com](https://whereby.com/) — ワンクリックのビデオ会話が無料(以前はappear.inとして知られていた)
  * [windmill.dev](https://windmill.dev/) - Windmillは、最小限のPythonとTypescriptスクリプトから本番グレードのマルチステップ自動化と内部アプリを素早く構築するためのオープンソース開発者プラットフォームです。無料ユーザーは、最大3つの非プレミアムワークスペースのメンバーになることができます。
  * [vadoo.tv](https://vadoo.tv/) — ビデオホスティングとマーケティングをシンプルに。ワンクリックでビデオをアップロード。録画、管理、共有など。無料枠には最大10本のビデオ、1GBのストレージ、月間10GBの帯域幅が含まれます。
  * [userforge.com](https://userforge.com/) - 相互接続されたオンラインペルソナ、ユーザーストーリー、コンテキストマッピング。最大3つのペルソナと2人のコラボレーターまで無料。
  * [wistia.com](https://wistia.com/) — 視聴者分析、HDビデオ配信、訪問者を理解するためのマーケティングツールを備えたビデオホスティング。25本のビデオとWistiaブランドのプレーヤーが無料。
  * [wormhol.org](https://www.wormhol.org/) — 直感的なファイル共有サービス。無制限のファイルを5GBまで、好きな数のピアと共有可能。
  * [Wormhole](https://wormhole.app/) - エンドツーエンド暗号化で最大24時間、5GBまでのファイルを共有。5GB以上のファイルには、ピアツーピア転送を使用してファイルを直接送信。
  * [zoom.us](https://zoom.us/) — セキュアなビデオおよびウェブ会議アドオンが利用可能。無料プランは40分に制限。
  * [Zulip](https://zulip.com/) — ユニークなメールのようなスレッディングモデルを備えたリアルタイムチャット。無料プランには10,000メッセージの検索履歴と5GBまでのファイルストレージが含まれます。セルフホスト可能なオープンソースバージョンも提供。
  * [robocorp.com](https://robocorp.com) - 自動化オペレーションを強化するオープンソーススタック。クラウド機能を試して簡単な自動化を無料で実装。ロボット作業時間240分/月、10回のアシスタント実行、100MBのストレージ。
  * [Fleep.io](https://fleep.io/) — Slackの代替。完全なメッセージ履歴、無制限の1:1会話、1つのグループ会話、1GBのファイルストレージを含む小規模チーム向けの無料プランがあります。
  * [Chanty.com](https://chanty.com/) — Slackのもう1つの代替。無制限のパブリックおよびプライベート会話、検索可能な履歴、無制限の1:1音声通話、無制限の音声メッセージ、10の統合、チームあたり20GBストレージを含む小規模チーム(最大10人)向けの永久無料プラン。
  * [ruttl.com](https://ruttl.com/) — ウェブサイト、PDF、画像のデジタルフィードバックを収集するための最高のオールインワンフィードバックツール。
  * [Mattermost](https://mattermost.com/) — 技術チーム向けのセキュアなコラボレーション。無制限のチャンネル、プレイブック、ボード、ユーザー、10GBストレージなどを含む無料プラン。
  * [Webvizio](https://webvizio.com) - ライブウェブサイトやウェブアプリ、画像、PDF、デザインファイル上で直接タスクをコラボレーションするためのウェブ開発コラボレーションを効率化するウェブサイトフィードバックツール、ウェブサイトレビューソフトウェア、バグ報告ツール。
  * [Pullflow](https://pullflow.com) - PullflowはGitHub、Slack、VS CodeにわたるコードレビューコラボレーションのためのAI強化プラットフォームを提供します。
  * [Webex](https://www.webex.com/) - 100人の参加者で1ミーティング40分までの無料プランを提供するビデオミーティング。
  * [RingCentral](https://www.ringcentral.com/) - 100人の参加者で1ミーティング50分までの無料プランを提供するビデオミーティング。
  * [GitBook](https://www.gitbook.com/) - 技術的な知識を取得・文書化するためのプラットフォーム - 製品ドキュメントから内部ナレッジベースやAPIまで。個人開発者向けの永久無料プラン。
  * [transfernow](https://www.transfernow.net/) - 最もシンプルで高速、安全なインターフェースでファイルを転送・共有。必須のサブスクリプションなしで写真、ビデオ、その他の大容量ファイルを送信。
  * [paste.sh](https://paste.sh/) - JavaScriptと暗号化ベースのシンプルな貼り付けサイト。
  * [Revolt.chat](https://revolt.chat/) - プライバシーを尊重する[Discord](https://discord.com/)のオープンソース代替。Discordの大部分の独自機能を無料で提供。Revoltは安全で高速な、100%無料のオールインワンアプリケーションです。すべての機能が無料です。主流のチャットアプリケーションとは異なり、(公式および非公式の)プラグインサポートもあります。
  * [Tencent RTC](https://trtc.io/) - Tencent Real-Time Communication (TRTC)はグループ音声/ビデオ通話のソリューションを提供。初年度は月10,000分まで無料。
  * [Pastefy](https://pastefy.app/) - オプションのクライアント暗号化、マルチタブペースト、API、ハイライトエディタなどを備えた美しくシンプルなPastebin。
  * [SiteDots](https://sitedots.com/) - ウェブサイトプロジェクトのフィードバックを、エミュレーション、キャンバス、回避策なしで直接ウェブサイト上で共有。完全に機能する無料枠。

**[⬆️ 目次に戻る](#table-of-contents)**

## CMS

  * [acquia.com](https://www.acquia.com/) — Drupalサイトのホスティング。開発者向けの無料枠あり。無料の開発ツール(Acquia Dev Desktopなど)も利用可能。
  * [Contentful](https://www.contentful.com/) — ヘッドレスCMS。クラウドでのコンテンツ管理と配信API。5ユーザー、25,000レコード、48コンテンツタイプ、2ロケールを含む1つの無料コミュニティスペースが提供されます。
  * [Cosmic](https://www.cosmicjs.com/) — ヘッドレスCMSとAPIツールキット。開発者向けの無料個人プランあり。
  * [Crystallize](https://crystallize.com) — eコマースサポート付きヘッドレスPIM。組み込みのGraphQL API。無料版には無制限のユーザー、1,000カタログアイテム、月5GB帯域幅、月25,000 APIコールが含まれます。
  * [DatoCMS](https://www.datocms.com/) - 小規模プロジェクト向けに無料枠を提供。DatoCMSはGraphQLベースのCMS。下位層では月10万コールが可能。
  * [Directus](https://directus.io) — ヘッドレスCMS。オンプレミスまたはクラウドでアセットとデータベースコンテンツを管理するための完全に無料でオープンソースのプラットフォーム。制限や有料の壁はありません。
  * [FrontAid](https://frontaid.io/) — JSONコンテンツを直接Gitリポジトリに保存するヘッドレスCMS。制限なし。
  * [kontent.ai](https://www.kontent.ai) - マーケターにも力を与えながら、ヘッドレスCMSのすべての利点を提供するContent-as-a-Serviceプラットフォーム。開発者プランでは2ユーザーに対して、無制限のプロジェクト(各2環境)、500コンテンツアイテム、2言語、配信・管理API、カスタム要素のサポートを提供。
  * [Prismic](https://www.prismic.io/) — ヘッドレスCMS。完全にホストされスケーラブルなAPIを備えたコンテンツ管理インターフェース。コミュニティプランでは1ユーザーに対して、無制限のAPIコール、ドキュメント、カスタムタイプ、アセット、ロケールを提供。オープンコンテンツ/オープンソースプロジェクトにはより大きな無料プランが利用可能。
  * [Sanity.io](https://www.sanity.io/) - オープンソースの編集環境とリアルタイムホストデータストアを備えた構造化コンテンツのためのプラットフォーム。無制限のプロジェクト。プロジェクトごとに無制限の管理ユーザー、3人の非管理ユーザー、2つのデータセット、500,000 API CDNリクエスト、10GB帯域幅、5GBアセットが無料で含まれます。
  * [sensenet](https://sensenet.com) - あらゆる規模のビジネスにエンタープライズグレードのソリューションを提供するAPI優先のヘッドレスCMS。開発者プランでは3ユーザー、500コンテンツアイテム、3つの組み込みロール、25+5コンテンツタイプ、完全にアクセス可能なREST API、ドキュメントプレビュー生成、Office Onlineでの編集を提供。
  * [TinaCMS](https://tina.io/) — Forestry.ioの後継。Markdown、MDX、JSONをサポートするオープンソースのGitバックエンドヘッドレスCMS。基本プランは2ユーザーまで無料。
  * [GatsbyjsCMS](https://www.gatsbyjs.com/) - Gatsbyは、任意のCMS、API、またはデータベースでウェブサイトを構築することを再び楽しくする高速で柔軟なフレームワークです。より多くのトラフィックを生み出し、より良い変換を実現し、より多くの収益を得るヘッドレスウェブサイトを構築・デプロイ！
  * [Hygraph](https://hygraph.com/) - 小規模プロジェクト向けに無料枠を提供。GraphQL優先のAPI。レガシーソリューションからGraphQLネイティブのヘッドレスCMSに移行し、オムニチャネルコンテンツをAPI優先で提供。
  * [Squidex](https://squidex.io/) - 小規模プロジェクト向けに無料枠を提供。API / GraphQL優先。イベントソーシング(すべての変更を自動的にバージョン管理)に基づくオープンソース。
  * [InstaWP](https://instawp.com/) - 数秒でWordPressサイトを立ち上げ。5つのアクティブサイト、500MBスペース、48時間のサイト有効期限を含む無料枠。
  * [Storyblok](https://www.storyblok.com) - すべての最新フレームワークで動作する開発者とマーケター向けのヘッドレスCMS。コミュニティ(無料)枠では、管理API、ビジュアルエディタ、10ソース、カスタムフィールドタイプ、国際化(無制限の言語/ロケール)、アセットマネージャー(最大2500アセット)、画像最適化サービス、検索クエリ、Webhook + 月250GBトラフィックを含みます。
  * [WPJack](https://wpjack.com) - 5分以内に任意のクラウドでWordPressをセットアップ！無料枠には1サーバー、2サイト、無料SSL証明書、無制限のcronジョブが含まれます。時間制限や有効期限なし - あなたのウェブサイト、あなたのやり方で。

**[⬆️ 目次に戻る](#table-of-contents)**

## コード生成

  * [Appinvento](https://appinvento.io/) — AppInventoは無料のノーコードアプリビルダーです。自動生成されたバックエンドコードでは、ユーザーはソースコードへの完全なアクセスと無制限のAPIとルートを持ち、広範な統合が可能です。無料プランには3つのプロジェクト、5つのテーブル、Googleアドオンが含まれます。
  * [Cody AI](https://sourcegraph.com/cody) - CodyはAIとコードベースの深い理解を使用して、コードの作成と理解を高速化するコーディングAIアシスタントです。Codyは開発者にLLMの選択肢(ローカル推論を含む)を提供し、様々なIDEをサポートし、すべての一般的なプログラミング言語をサポートし、無料プランがあります。無料プランでは、開発者に毎月20のチャットメッセージ(Claude 3 Sonnetを使用)と500の自動補完(Starcoder 16bを使用)を提供します。
  * [DhiWise](https://www.dhiwise.com/) — DhiWiseの革新的なコード生成技術により、FigmaデザインをFlutterとReactのダイナミックなアプリケーションにシームレスに変換し、ワークフローを最適化し、これまで以上に速くモバイルとウェブの優れた体験を作成できます。
  * [Codeium](https://www.codeium.com/) — Codeiumは無料のAI駆動コード補完ツールです。20以上のプログラミング言語(Python、JavaScript、Java、TypeScript、PHP、C/C++、Goなど)をサポートし、すべての主要なスタンドアロンおよびウェブIDEと統合されています。
  * [Fern](https://buildwithfern.com) - API定義を書き、それを使用してTypeScript、Python、Java、Goなどの人気言語でSDK/クライアントライブラリを生成します。OpenAPIを完全にサポート。無料枠では最大20エンドポイントまでのコード生成が可能です。
  * [Metalama](https://www.postsharp.net/metalama) - C#のみ。Metalamaはコンパイル時にコードのボイラープレートをその場で生成し、ソースコードをクリーンに保ちます。オープンソースプロジェクトには無料で、商用フレンドリーな無料枠には3つのアスペクトが含まれます。
  * [Supermaven](https://www.supermaven.com/) — SupermavenはVSCode、JetBrains、Neovim用の高速AIコード補完プラグインです。無料枠では無制限のインライン補完を提供します。
  * [tabnine.com](https://www.tabnine.com/) — Tabnineは、世界中のすべてのコードから学んだ洞察を提供することで、開発者がより良いソフトウェアをより速く作成するのを支援します。プラグインが利用可能。
  * [v0.dev](https://v0.dev/) — v0はAIモデルを使用して単純なテキストプロンプトに基づいてコードを生成します。shadcn/uiとTailwind CSSに基づいてコピー＆ペースト可能なReactコードを生成し、プロジェクトで使用できます。各生成には最低30クレジットが必要です。最初に1200クレジットが付与され、毎月200クレジットが無料で追加されます。

**[⬆️ 目次に戻る](#table-of-contents)**

## コード品質

  * [beanstalkapp.com](https://beanstalkapp.com/) — コードの作成、レビュー、デプロイのための完全なワークフロー、1ユーザーと100MBストレージの1リポジトリの無料アカウント
  * [browserling.com](https://www.browserling.com/) — ライブインタラクティブなクロスブラウザテスト、Vista上のMS IE 9で1024 x 768解像度での3分間のセッションのみ無料
  * [codacy.com](https://www.codacy.com/) — PHP、Python、Ruby、Java、JavaScript、Scala、CSS、CoffeeScriptの自動コードレビュー、無制限のパブリックおよびプライベートリポジトリに対して無料
  * [Codeac.io](https://www.codeac.io/infrastructure-as-code.html?ref=free-for-dev) - DevOps向けの自動インフラストラクチャ・アズ・コードレビューツールで、GitHub、Bitbucket、GitLab(セルフホスト型も含む)と統合。標準的な言語に加えて、Ansible、Terraform、CloudFormation、Kubernetesなども分析。(オープンソース無料)
  * [CodeBeat](https://codebeat.co) — SlackとEメール統合を備えた自動コードレビュープラットフォームで、多くの言語に対応。パブリックリポジトリは永久に無料。
  * [codeclimate.com](https://codeclimate.com/) — 自動コードレビュー、オープンソースと無制限の組織所有プライベートリポジトリ(最大4人のコラボレーター)に対して無料。また、学生と教育機関にも無料。
  * [codecov.io](https://codecov.io/) — コードカバレッジツール(SaaS)、オープンソースと1つの無料プライベートリポジトリに対して無料
  * [CodeFactor](https://www.codefactor.io) — Git用の自動コードレビュー。無料版には無制限のユーザー、パブリックリポジトリ、1つのプライベートリポジトリが含まれます。
  * [coderabbit.ai](https://coderabbit.ai) — GitHub/GitLabと統合するAI駆動のコードレビューツール。無料枠には時間あたり200ファイル、3レビュー、50会話が含まれます。オープンソースプロジェクトは永久に無料。
  * [codescene.io](https://codescene.io/) - CodeSceneは、開発者がコードとどのように作業しているかに基づいて技術的負債を優先順位付けし、チーム結合やシステム習熟度などの組織的要因を視覚化します。オープンソースに対して無料。
  * [CodSpeed](https://codspeed.io) - CIパイプラインでのパフォーマンス追跡を自動化。正確で一貫した指標により、デプロイ前にパフォーマンスの低下を検出。オープンソースプロジェクトは永久に無料。
  * [coveralls.io](https://coveralls.io/) — テストカバレッジレポートの表示、オープンソースに対して無料
  * [dareboost](https://dareboost.com) - 毎月ウェブパフォーマンス、アクセシビリティ、セキュリティの分析レポートを5件無料で提供
  * [deepcode.ai](https://www.deepcode.ai) — DeepCodeはAIに基づいてバグ、セキュリティ脆弱性、パフォーマンス、API問題を発見します。DeepCodeの分析速度により、コードをリアルタイムで分析し、IDEで保存ボタンを押したときに結果を提供できます。サポートされている言語はJava、C/C++、JavaScript、Python、TypeScript。GitHub、BitBucket、GitLabとの統合。オープンソースとプライベートリポジトリ、最大30人の開発者まで無料。
  * [deepscan.io](https://deepscan.io) — JavaScriptコードのランタイムエラーを自動的に発見するための高度な静的分析、オープンソースに対して無料
  * [DeepSource](https://deepsource.io/) - DeepSourceは、セキュリティ、パフォーマンス、アンチパターン、バグリスク、ドキュメント、スタイルにカテゴリ分けされた問題を見つけて修正し、ソースコードの変更を継続的に分析します。GitHub、GitLab、Bitbucketとのネイティブ統合。
  * [DiffText](https://difftext.com) - 2つのコードブロック間の違いを即座に見つけます。完全に無料で使用可能。
  * [eversql.com](https://www.eversql.com/) — EverSQL - データベース最適化のための#1プラットフォーム。データベースとSQLクエリに関する重要な洞察を自動的に得られます。
  * [gerrithub.io](https://review.gerrithub.io/) — GitHubリポジトリ用のGerritコードレビューを無料で提供
  * [gocover.io](https://gocover.io/) — 任意の[Go](https://golang.org/)パッケージのコードカバレッジ
  * [goreportcard.com](https://goreportcard.com/) — Goプロジェクトのコード品質、オープンソースに対して無料
  * [gtmetrix.com](https://gtmetrix.com/) — ウェブサイトを最適化するためのレポートと詳細な推奨事項
  * [holistic.dev](https://holistic.dev/) - Postgresql最適化のための#1静的コード分析ツール。パフォーマンス、セキュリティ、アーキテクトデータベースの問題を自動検出するサービス
  * [houndci.com](https://houndci.com/) — コード品質に関するGitHubコミットへのコメント、オープンソースに対して無料
  * [Moderne.io](https://app.moderne.io) — 自動ソースコードリファクタリング。Moderneはフレームワークの移行、修正を伴うコード分析、比類のないスケールでのコード変換を提供し、開発者が古いものを維持するのではなく新しいものを構築することに時間を費やせるようにします。オープンソースに対して無料。
  * [reviewable.io](https://reviewable.io/) — GitHubリポジトリのコードレビュー、パブリックまたは個人リポジトリに対して無料。
  * [parsers.dev](https://parsers.dev/) - 抽象構文木パーサーと中間表現コンパイラをサービスとして提供
  * [scan.coverity.com](https://scan.coverity.com/) — Java、C/C++、C#、JavaScriptの静的コード分析、オープンソースに対して無料
  * [scrutinizer-ci.com](https://scrutinizer-ci.com/) — 継続的インスペクションプラットフォーム、オープンソースに対して無料
  * [semanticdiff.com](https://app.semanticdiff.com/) — GitHubプルリクエストとコミット用のプログラミング言語対応の差分、パブリックリポジトリに対して無料
  * [shields.io](https://shields.io) — オープンソースプロジェクト用の品質メタデータバッジ
  * [sonarcloud.io](https://sonarcloud.io) — Java、JavaScript、C/C++、C#、VB.NET、PHP、Objective-C、Swift、Python、Groovyなどさらに多くの言語の自動ソースコード分析、オープンソースに対して無料
  * [SourceLevel](https://sourcelevel.io/) — 自動コードレビューとチーム分析。オープンソースと最大5人のコラボレーターまでの組織に対して無料。
  * [webceo.com](https://www.webceo.com/) — SEOツールだけでなく、コード検証と異なるタイプのデバイスも
  * [zoompf.com](https://zoompf.com/) — ウェブサイトのパフォーマンスを修正、詳細な分析

**[⬆️ 目次に戻る](#table-of-contents)**

## コード検索とブラウジング

  * [libraries.io](https://libraries.io/) — 32の異なるパッケージマネージャーの検索と依存関係更新通知、オープンソースに対して無料
  * [Namae](https://namae.dev/) - GitHub、Gitlab、Heroku、Netlifyなど様々なウェブサイトでプロジェクト名の利用可能性を検索。
  * [searchcode.com](https://searchcode.com/) — 包括的なテキストベースのコード検索、オープンソースに対して無料
  * [tickgit.com](https://www.tickgit.com/) — `TODO`コメント(および他のマーカー)を表面化させ、改善のために戻る価値のあるコード領域を特定。
  * [CodeKeep](https://codekeep.io) - コードスニペット用のGoogle Keep。プリセットテンプレートを備えた強力なコードスクリーンショットツールとリンク機能を特徴とする、コードスニペットの整理、発見、共有。

**[⬆️ 目次に戻る](#table-of-contents)**

## CI/CD

  * [AccessLint](https://github.com/marketplace/accesslint) — AccessLintは、開発ワークフローにウェブアクセシビリティテストを組み込みます。オープンソースと教育目的に対して無料です。
  * [appcircle.io](https://appcircle.io) — より速く効率的なリリースサイクルのために、モバイルアプリのビルド、テスト、ストア公開を自動化するエンタープライズグレードのモバイルDevOpsプラットフォーム。ビルドあたり最大30分のビルド時間、月20ビルド、1同時ビルドまで無料。
  * [appveyor.com](https://www.appveyor.com/) — Windows向けのCDサービス、オープンソースに対して無料
  * [LocalOps](https://localops.co/) - 30分以内にAWS/GCP/Azureにアプリをデプロイ。継続的デプロイメント自動化と高度な監視機能を備えた標準化されたアプリ環境をあらゆるクラウドで設定。無料プランでは1ユーザーと1アプリ環境が利用可能。
  * [Argonaut](https://argonaut.dev/) - 数分でアプリとインフラをクラウドにデプロイ。KubernetesとLambda環境でのカスタムおよびサードパーティアプリのデプロイメントをサポート。無料枠では5つのドメインと2ユーザーに対して無制限のアプリとデプロイメントが可能。
  * [bitrise.io](https://www.bitrise.io/) — モバイルアプリ向けのCI/CD、ネイティブまたはハイブリッド。月200ビルド、10分のビルド時間、2チームメンバーまで無料。OSSプロジェクトは45分のビルド時間、+1の同時実行、無制限のチームサイズが利用可能。
  * [buddy.works](https://buddy.works/) — 5つの無料プロジェクトと1つの同時実行(月120実行)を提供するCI/CD
  * [Buildkite](https://buildkite.com) — 3ユーザーと月5,000ジョブ分まで無料のCIパイプライン。テスト分析の無料開発者枠には月10万回のテスト実行が含まれ、オープンソースプロジェクトにはさらに無料枠があります。
  * [bytebase.com](https://www.bytebase.com/) — データベースCI/CDとDevOps。20ユーザーと10データベースインスタンスまで無料
  * [CircleCI](https://circleci.com/) — GitHub、GitLab、BitBucketリポジトリ向けのホステッドCI/CDサービスの包括的な無料プラン。Docker、Windows、Mac OS、ARMエグゼキューター、ローカルランナー、テスト分割、Dockerレイヤーキャッシングなどの高度なCI/CD機能を含む。月6,000分までの実行時間、無制限のコラボレーター、プライベートプロジェクトで30の並列ジョブ、オープンソースプロジェクトで最大80,000分のビルド時間が無料。
  * [cirrus-ci.org](https://cirrus-ci.org) - パブリックGitHubリポジトリに対して無料
  * [cirun.io](https://cirun.io) - パブリックGitHubリポジトリに対して無料
  * [codefresh.io](https://codefresh.io) — Free-for-Lifeプラン: 1ビルド、1環境、共有サーバー、無制限のパブリックリポジトリ
  * [codemagic.io](https://codemagic.io/) — 月500ビルド分まで無料
  * [codeship.com](https://codeship.com/) — 月100プライベートビルド、5プライベートプロジェクト、オープンソースは無制限
  * [deploybot.com](https://www.deploybot.com/) — 10デプロイメントを持つ1リポジトリ、オープンソースに対して無料
  * [deployhq.com](https://www.deployhq.com/) — 1プロジェクトで1日10デプロイメント(月30ビルド分)
  * [drone](https://cloud.drone.io/) - Drone Cloudは開発者がx86とArm(32ビットと64ビットの両方)を含む複数のアーキテクチャにわたって継続的デリバリーパイプラインを実行することを可能にします
  * [LayerCI](https://layerci.com) — フルスタックプロジェクト向けCI。5GBメモリと3 CPUを持つ1つのフルスタックプレビュー環境。
  * [semaphoreci.com](https://semaphoreci.com/) — オープンソースに対して無料、月100プライベートビルド
  * [Squash Labs](https://www.squash.io/) — 各ブランチ用のVMを作成し、ユニークなURLからアプリを利用可能にします。無制限のパブリック&プライベートリポジトリ、最大2 GB VMサイズまで。
  * [styleci.io](https://styleci.io/) — パブリックGitHubリポジトリのみ
  * [Mergify](https://mergify.io) — GitHub向けのワークフロー自動化とマージキュー — パブリックGitHubリポジトリに対して無料
  * [Make](https://www.make.com/en) — UIを使用してアプリを接続しワークフローを自動化するツール。多くのアプリと最も一般的なAPIをサポート。パブリックGitHubリポジトリに対して無料で、100 Mb、1000オペレーション、15分の最小間隔を含む無料枠があります。
  * [Spacelift](https://spacelift.io/) — Infrastructure as Codeの管理プラットフォーム。無料プランの機能: IaCコラボレーション、Terraformモジュールレジストリ、ChatOps統合、Open Policy Agentによる継続的リソースコンプライアンス、SAML 2.0によるSSO、パブリックワーカープールへのアクセス: 月200分まで
  * [microtica.com](https://microtica.com/) — 準備済みのインフラストラクチャコンポーネントを持つスタートアップ環境、AWSでのアプリの無料デプロイ、本番ワークロードのサポート。無料枠には1環境(AWSアカウント上)、2 Kubernetesサービス、月100ビルド分、月20デプロイメントが含まれます。
  * [Nx Cloud](https://nx.dev/ci) - Nx Cloudはリモートキャッシング、マシン間のタスク分散、e2eテスト実行の自動分割などの機能により、CIでのモノレポの速度を向上させます。最大30人の貢献者に対して、寛大な150kクレジットを含む無料プランが提供されます。
  * [blacksmith](https://www.blacksmith.sh/) - GitHub Actions用の管理されたパフォーマンスランナーを提供し、クレジットカード不要で月3,000分まで無料。
  * [Terramate](https://terramate.io/) - TerramateはTerraform、OpenTofu、Terragruntなどのインフラストラクチャ・アズ・コード(IaC)ツールのオーケストレーションと管理プラットフォームです。2ユーザーまで全機能が無料。
  * [Terrateam](https://terrateam.io) - プルリクエスト駆動のワークフロー、セルフホステッドランナーによるプロジェクト分離、順序付けられた操作のためのレイヤー実行を備えたGitOpsファーストのTerraform自動化。3ユーザーまで無料。

**[⬆️ 目次に戻る](#table-of-contents)**

## テスト

  * [Applitools.com](https://applitools.com/) — ウェブ、ネイティブモバイル、デスクトップアプリのスマートな視覚的検証。ほぼすべての自動化ソリューション(SeleniumやKarmaなど)とリモートランナー(Sauce Labs、Browser Stack)と統合。オープンソースに対して無料。単一ユーザーに対して週あたり限定されたチェックポイントを含む無料枠。
  * [Appetize](https://appetize.io) — このクラウドベースのAndroidフォン/タブレットエミュレーターとiPhone/iPadシミュレーターで、直接ブラウザでiOS & Androidアプリをテスト。無料枠には2つの同時セッションと月30分の使用時間が含まれ、アプリサイズに制限はありません。
  * [Apptim](https://apptim.com) — パフォーマンスエンジニアリングのスキルがない人々がアプリのパフォーマンスとユーザーエクスペリエンス(UX)を評価できるモバイルテストツール。自身のデバイスを使用するデスクトップバージョンは、iOSとAndroidの両方で無制限のテストが100%無料。
  * [Argos](https://argos-ci.com) - 開発者向けのオープンソースビジュアルテスト。無制限のプロジェクトで、月5,000スクリーンショットまで。オープンソースプロジェクトに対して無料。
  * [Bencher](https://bencher.dev/) - CIパフォーマンスの回帰を検出する継続的ベンチマークツールスイート。すべてのパブリックプロジェクトに対して無料。
  * [browserstack.com](https://www.browserstack.com/) — 手動および自動ブラウザテスト、[オープンソースに対して無料](https://www.browserstack.com/open-source?ref=pricing)
  * [BugBug](https://bugbug.io/) - ウェブアプリケーション向けの軽量テスト自動化ツール。学習が容易でコーディングは不要です。自分のコンピュータで無制限のテストを無料で実行できます。クラウド監視とCI/CD統合は追加の月額料金で利用可能です。
  * [Checkly](https://checklyhq.com) - 現代のDevOps向けのコードファーストの合成監視。APIとアプリを従来のプロバイダーの価格の一部で監視。Monitoring as CodeワークフローとPlaywrightを採用。開発者向けの寛大な無料枠。
  * [checkbot.io](https://www.checkbot.io/) — 50以上のSEO、速度、セキュリティのベストプラクティスに従っているかウェブサイトをテストするブラウザ拡張機能。小規模なウェブサイト向けの無料枠。
  * [CORS-Tester](https://cors-error.dev/cors-tester/) - 開発者とAPIテスターがAPIがCORS対応かどうかを確認し、ギャップを特定するための無料ツール。実用的な洞察を得られます。
  * [cypress.io](https://www.cypress.io/) - ブラウザで実行されるものに対する高速、簡単、信頼性のあるテスト。Cypress Test Runnerは常に無料でオープンソースで、制限や制約なし。Cypress Dashboardはオープンソースプロジェクトに対して5ユーザーまで無料。
  * [Cypress Recorder by Preflight](https://cypress.preflight.com/) - ブラウザ上でAI駆動のCypressテスト/POMモデルを作成。自己修復スクリプト、メール、ビジュアルテストを含む月5テスト作成まで無料のオープンソース(AI部分を除く)。
  * [everystep-automation.com](https://www.everystep-automation.com/) — ウェブブラウザで行われたすべてのステップを記録して再生し、スクリプトを作成、より少ないオプションで無料
  * [Gremlin](https://www.gremlin.com/gremlin-free-software) — Gremlinのカオスエンジニアリングツールを使用すると、顧客に影響を与える問題が発生する前に、システムの弱点を安全かつ確実に見つけることができます。Gremlin Freeは最大5つのホストまたはコンテナに対してシャットダウンとCPU攻撃へのアクセスを提供します。
  * [gridlastic.com](https://www.gridlastic.com/) — 最大4つの同時セレニウムノード/10グリッド開始/月4,000テスト分の無料プランを提供するSeleniumグリッドテスト
  * [katalon.com](https://katalon.com) - すべてのサイズのチームに対して、異なるテスト成熟度レベルでのテストを支援できるテストプラットフォームを提供。Katalon Studio、TestOps(+ Visual Testing無料)、TestCloud、Katalon Recorderを含みます。
  * [Keploy](https://keploy.io/) - Keployは開発者向けの機能テストツールキットです。APIコールの記録によりAPIのE2Eテスト(KTests)とモックまたはスタブ(KMocks)を生成します。オープンソースプロジェクトに対して無料。
  * [knapsackpro.com](https://knapsackpro.com) - あらゆるCIプロバイダーでの最適なテストスイート並列化によりテストを高速化。時間を節約するために並列CIノードでRuby、JavaScriptテストを分割。テストファイル10分までの無料プランとオープンソースプロジェクトに対する無制限の無料プラン。
  * [lambdatest.com](https://www.lambdatest.com/) — seleniumとcypressでの手動、視覚的、スクリーンショット、自動ブラウザテスト、[オープンソースに対して無料](https://www.lambdatest.com/open-source-cross-browser-testing-tool)
  * [loadmill.com](https://www.loadmill.com/) - ネットワークトラフィックを分析してAPIとロードテストを自動的に作成。月に最大50の同時ユーザーを60分まで無料でシミュレート。
  * [lost-pixel.com](https://lost-pixel.com) - Storybook、Ladle、Histoireストーリーとウェブアプリ向けの包括的なビジュアル回帰テスト。無制限のチームメンバー、オープンソースに対して完全無料、月7,000スナップショット。
  * [octomind.dev](https://www.octomind.dev/) - AIアシストのテストケース生成を備えた自動生成、実行、メンテナンスされるPlaywright UIテスト
  * [percy.io](https://percy.io) - ウェブアプリ、静的サイト、スタイルガイド、コンポーネントライブラリにビジュアルテストを追加。無制限のチームメンバー、デモアプリ、無制限のプロジェクト、月5,000スナップショット。
  * [preflight.com](https://preflight.com) - ノーコードの自動化されたウェブテスト。ブラウザでUI変更に耐性のあるテストを記録し、Windowsマシンで実行。CI/CDと統合可能。無料プランには月50回のテスト実行、ビデオ、HTMLセッションなどが含まれます。
  * [qase.io](https://qase.io) - 開発者とQAチーム向けのテスト管理システム。テストケースの管理、テスト実行の構成、テストの実行、欠陥の追跡、影響の測定。無料枠にはすべてのコア機能が含まれ、添付ファイル用に500MBと最大3ユーザーまで利用可能。
  * [Repeato](https://repeato.app/) - コンピュータビジョンとAIを基盤としたノーコードのモバイルアプリテスト自動化ツール。ネイティブアプリ、flutter、react-native、web、ionicなど多くのアプリフレームワークで動作。無料プランはiOSで10テスト、Androidで10テストに制限されますが、無制限のテスト実行を含む有料プランのほとんどの機能が含まれています。
  * [Requestly](https://requestly.com/) - HTTPリクエストのインターセプト、リダイレクト、モックを行うオープンソースのChrome拡張機能。[デバッガー](https://requestly.com/products/web-debugger/)、[モックサーバー](https://requestly.com/products/mock-server/)、[APIクライアント](https://requestly.com/products/api-client/)、[セッション記録](https://requestly.com/products/session-book/)を特徴とします。URLのリダイレクト、HTTPヘッダーの変更、APIのモック、カスタムJSの注入、GraphQLリクエストの変更、モックAPIエンドポイントの生成、ネットワーク&コンソールログを含むセッションの記録が可能。無料枠で10ルールまで作成可能。オープンソースに対して無料。
  * [seotest.me](https://seotest.me/) — 無料のオンページSEOウェブサイトテスター。1日10回の無料ウェブサイトクロール。技術に関係なく、あらゆるウェブサイトのオンページSEO結果を改善する方法に関する有用なSEO学習リソースと推奨事項。
  * [snippets.uilicious.com](https://snippets.uilicious.com) - CodePenのようなクロスブラウザテスト向けのもの。UI-liciousではユーザーストーリーのようにテストを書くことができ、無料プラットフォーム - UI-licious Snippets - を提供し、サインアップ不要でChromeで無制限のテストを実行できます(テスト実行あたり3分まで)。バグを見つけた場合、テストのユニークURLを開発者に共有して、バグの再現方法を正確に示すことができます。
  * [TestCollab](https://testcollab.com) - ユーザーフレンドリーなテスト管理ソフトウェア。無料プランにはJira統合、無制限のプロジェクト、CSV/XLSxによるテストケースのインポート、時間追跡、1 GBのファイルストレージが含まれます。
  * [testingbot.com](https://testingbot.com/) — Seleniumブラウザとデバイステスト、[オープンソースに対して無料](https://testingbot.com/open-source)
  * [Testspace.com](https://testspace.com/) - 自動化されたテスト結果を公開するためのダッシュボードとGitHubを使用してマニュアルテストをコードとして実装するためのフレームワーク。このサービスは[オープンソースに対して無料](https://github.com/marketplace/testspace-com)で、月450結果のアカウントを提供。
  * [tesults.com](https://www.tesults.com) — テスト結果のレポートとテストケース管理。一般的なテストフレームワークと統合。オープンソースソフトウェア開発者、個人、教育者、小規模チームは基本的な無料プロジェクトを超えた割引および無料提供を要求できます。
  * [UseWebhook.com](https://usewebhook.com) - ブラウザからwebhookをキャプチャして検査。localhostに転送、または履歴から再生。使用は無料。
  * [Vaadin](https://vaadin.com) — JavaまたはTypeScriptでスケーラブルなUIを構築し、統合されたツール、コンポーネント、デザインシステムを使用して、より速く反復し、より良くデザインし、開発プロセスを簡素化します。5年間の無料メンテナンスを含む無制限のプロジェクト。
  * [websitepulse.com](https://www.websitepulse.com/tools/) — 様々な無料のネットワークとサーバーツール。
  * [webhook-test.com](https://webhook-test.com) - 統合中にユニークなURLでwebhookとHTTPリクエストをデバッグして検査。完全に無料で、無制限のURLを作成して推奨事項を受け取ることができます。
  * [webhook.site](https://webhook.site) - カスタムURLでwebhook、アウトバウンドHTTPリクエスト、またはメールを検証。一時的なURLとメールアドレスは常に無料。
  * [webhookbeam.com](https://webhookbeam.com) - webhookを設定し、プッシュ通知とメールで監視。

**[⬆️ 目次に戻る](#table-of-contents)**

## セキュリティとPKI

  * [aikido.dev](https://www.aikido.dev) — SCA、SAST、CSPM、DAST、シークレット、IaC、マルウェア、コンテナスキャン、EOLなどをカバーするオールインワンのアプセクプラットフォーム。無料プランには2ユーザー、10リポジトリのスキャン、1クラウド、2コンテナ、1ドメインが含まれます。
  * [alienvault.com](https://www.alienvault.com/open-threat-exchange/reputation-monitor) — ネットワーク内の侵害されたシステムを発見
  * [Altcha.org](https://altcha.org/anti-spam) - ウェブサイトとAPI向けの自然言語処理と機械学習を活用したスパムフィルター。無料プランには1日200リクエスト/ドメインが含まれます。
  * [atomist.com](https://atomist.com/) — 様々な開発タスクを自動化するより迅速で便利な方法。現在ベータ版。
  * [cloudsploit.com](https://cloudsploit.com/) — Amazon Web Services (AWS)のセキュリティと準拠性の監査とモニタリング
  * [Public Cloud Threat Intelligence](https://cloudintel.himanshuanand.com/) — パブリッククラウドインフラストラクチャを標的とする高信頼性の侵害指標(IOC)、一部はgithubで利用可能(https://github.com/unknownhad/AWSAttacks)。完全なリストはAPI経由で利用可能。
  * [CodeNotary.io](https://www.codenotary.io/) — コード、ファイル、ディレクトリ、またはコンテナを公証する消えない証明を持つオープンソースプラットフォーム
  * [crypteron.com](https://www.crypteron.com/) — クラウドファースト、開発者フレンドリーなセキュリティプラットフォームが.NETとJavaアプリケーションでのデータ侵害を防止
  * [CyberChef](https://gchq.github.io/CyberChef/) — 複雑なツールやプログラミング言語を扱うことなく、データの分析と符号化/復号化を行うためのシンプルで直感的なウェブアプリ。暗号化と暗号のスイスアーミーナイフのような存在。すべての機能は制限なく無料で使用可能。セルフホストも可能なオープンソース。
  * [DAS](https://signup.styra.com/) — Styra DAS Free、Open Policy Agent(OPA)認可の作成、デプロイ、管理のためのフルライフサイクルポリシー管理
  * [Datree](https://www.datree.io/) — マニフェストとHelmチャートがベストプラクティスと組織のポリシーに従っていることを確認することで、Kubernetesの設定ミスを防ぐオープンソースCLIツール
  * [Dependabot](https://dependabot.com/) — Ruby、JavaScript、Python、PHP、Elixir、Rust、Java(MavenとGradle)、.NET、Go、Elm、Docker、Terraform、Git Submodules、GitHub Actionsの自動依存関係更新。
  * [DJ Checkup](https://djcheckup.com) — この無料の自動チェックアップツールでDjangoサイトのセキュリティの欠陥をスキャン。Pony Checkupサイトからフォーク。
  * [Doppler](https://doppler.com/) — アプリケーションのシークレットと設定のためのユニバーサルシークレットマネージャー。様々なクラウドプロバイダーとの同期をサポート。基本的なアクセス制御を含む5ユーザーまで無料。
  * [Dotenv](https://dotenv.org/) — .envファイルを素早く安全に同期。Slackやメールなどのセキュアでないチャネルでの.envファイルの共有を停止し、重要な.envファイルを二度と失わないようにします。3人のチームメイトまで無料。
  * [GitGuardian](https://www.gitguardian.com) — 自動化されたシークレット検出と修復でソースコードからシークレットを排除。350以上のタイプのシークレットと機密ファイルをgitリポジトリでスキャン — 個人と25人以下の開発者チームに対して無料。
  * [Have I been pwned?](https://haveibeenpwned.com) — 侵害に関する情報を取得するためのREST API。
  * [hostedscan.com](https://hostedscan.com) — ウェブアプリケーション、サーバー、ネットワーク向けのオンライン脆弱性スキャナー。月10回の無料スキャン。
  * [Infisical](https://infisical.com/) — 開発者シークレットをチームとインフラストラクチャ全体で管理できるオープンソースプラットフォーム: ローカル開発からステージング/本番の第三者サービスまでどこでも。5人の開発者まで無料。
  * [Internet.nl](https://internet.nl) — IPv6、DNSSEC、HTTPS、DMARC、STARTTLS、DANEなどの最新のインターネット標準のテスト
  * [AccessLint](https://github.com/marketplace/accesslint) — AccessLintは自動化されたウェブアクセシビリティテストを開発ワークフローに組み込みます。オープンソースと教育目的に対して無料。
  * [appcircle.io](https://appcircle.io) — モバイルアプリのより迅速で効率的なリリースサイクルのために、ビルド、テスト、ストア公開を自動化するエンタープライズグレードのモバイルDevOpsプラットフォーム。ビルドあたり最大30分のビルド時間、月20ビルド、1同時ビルドまで無料。
  * [appveyor.com](https://www.appveyor.com/) — Windows向けのCDサービス、オープンソースに対して無料
  * [LocalOps](https://localops.co/) - 30分以内にAWS/GCP/Azureにアプリをデプロイ。任意のクラウドで標準化されたアプリ環境をセットアップし、継続的デプロイメント自動化と高度な監視機能を備えています。無料プランでは1ユーザーと1アプリ環境が利用可能。
  * [Argonaut](https://argonaut.dev/) - 数分でクラウドにアプリとインフラをデプロイ。KubernetesとLambda環境でのカスタムおよびサードパーティアプリのデプロイメントをサポート。無料枠では5ドメインと2ユーザーに対して無制限のアプリとデプロイメントが可能。
  * [bitrise.io](https://www.bitrise.io/) — モバイルアプリ(ネイティブまたはハイブリッド)向けのCI/CD。月200回の無料ビルド、10分のビルド時間、2チームメンバーまで。OSSプロジェクトは45分のビルド時間、+1の同時実行、無制限のチームサイズを利用可能。
  * [buddy.works](https://buddy.works/) — 5つの無料プロジェクトと1つの同時実行(月120実行)を提供するCI/CD
  * [Buildkite](https://buildkite.com) — 3ユーザーと月5,000ジョブ分まで無料のCIパイプライン。テスト分析の無料開発者枠には月100,000テスト実行が含まれ、オープンソースプロジェクトにはさらに無料枠があります。
  * [bytebase.com](https://www.bytebase.com/) — データベースCI/CDとDevOps。20ユーザーと10データベースインスタンスまで無料
  * [CircleCI](https://circleci.com/) — GitHub、GitLab、BitBucketリポジトリ向けのホステッドCI/CDサービスのすべての機能を含む包括的な無料プラン。複数のリソースクラス、Docker、Windows、Mac OS、ARMエグゼキューター、ローカルランナー、テスト分割、Dockerレイヤーキャッシングなどの高度なCI/CD機能を提供。月6,000分まで実行時間、無制限のコラボレーター、プライベートプロジェクトで30の並列ジョブ、オープンソースプロジェクトに対して最大80,000分の無料ビルド時間を提供。
  * [cirrus-ci.org](https://cirrus-ci.org) - パブリックGitHubリポジトリに対して無料
  * [cirun.io](https://cirun.io) - パブリックGitHubリポジトリに対して無料
  * [codefresh.io](https://codefresh.io) — 無期限無料プラン: 1ビルド、1環境、共有サーバー、無制限のパブリックリポジトリ
  * [codemagic.io](https://codemagic.io/) — 月500ビルド分まで無料
  * [codeship.com](https://codeship.com/) — 月100プライベートビルド、5プライベートプロジェクト、オープンソースに対して無制限
  * [deploybot.com](https://www.deploybot.com/) — 10デプロイメントを持つ1リポジトリ、オープンソースに対して無料
  * [deployhq.com](https://www.deployhq.com/) — 1プロジェクトに対して1日10デプロイメント(月30ビルド分)
  * [drone](https://cloud.drone.io/) - Drone Cloudは開発者が複数のアーキテクチャ(x86とArm(32ビットと64ビット両方)を含む)にわたって継続的デリバリーパイプラインを実行することを可能にします
  * [LayerCI](https://layerci.com) — フルスタックプロジェクト向けCI。5GBメモリと3 CPUを持つ1つのフルスタックプレビュー環境。
  * [semaphoreci.com](https://semaphoreci.com/) — オープンソースに対して無料、月100プライベートビルド
  * [Squash Labs](https://www.squash.io/) — 各ブランチに対してVMを作成し、ユニークなURLからアプリを利用可能にします。無制限のパブリック&プライベートリポジトリ、最大2 GBのVMサイズまで。
  * [styleci.io](https://styleci.io/) — パブリックGitHubリポジトリのみ
  * [Mergify](https://mergify.io) — GitHubのワークフロー自動化とマージキュー — パブリックGitHubリポジトリに対して無料
  * [Make](https://www.make.com/en) — UIを使用してアプリを接続しワークフローを自動化できるツール。多くのアプリと最も一般的なAPIをサポート。パブリックGitHubリポジトリに対して無料で、100 Mb、1000オペレーション、15分の最小間隔を含む無料枠を提供。
  * [Spacelift](https://spacelift.io/) - Infrastructure as Codeの管理プラットフォーム。無料プランの機能: IaCコラボレーション、Terraformモジュールレジストリ、ChatOps統合、Open Policy Agentによる継続的リソースコンプライアンス、SAML 2.0によるSSO、パブリックワーカープールへのアクセス: 月最大200分まで
  * [microtica.com](https://microtica.com/) - 準備済みのインフラストラクチャコンポーネントを持つスタートアップ環境、AWSへの無料アプリデプロイ、本番ワークロードのサポート。無料枠には1環境(AWSアカウント上)、2 Kubernetesサービス、月100ビルド分、月20デプロイメントが含まれます。
  * [Nx Cloud](https://nx.dev/ci) - Nx Cloudは、リモートキャッシング、マシン間のタスク分散、e2eテスト実行の自動分割などの機能でCIでのモノレポの速度を向上させます。最大30人の貢献者に対して150,000クレジットを含む無料プランが提供されます。
  * [blacksmith](https://www.blacksmith.sh/) - GitHub Actions向けの管理されたパフォーマンスランナーで、クレジットカード不要で月3,000分の無料利用を提供。
  * [Terramate](https://terramate.io/) - TerramateはTerraform、OpenTofu、Terragruntなどのインフラストラクチャアズコード(IaC)ツール向けのオーケストレーションおよび管理プラットフォームです。すべての機能を含む2ユーザーまで無料。
  * [Terrateam](https://terrateam.io) - プルリクエスト駆動のワークフロー、セルフホステッドランナーによるプロジェクト分離、順序付けられた操作のためのレイヤー実行を備えたGitOpsファーストのTerraform自動化。3ユーザーまで無料。

**[⬆️ Back to Top](#table-of-contents)**

## テスト

  * [Applitools.com](https://applitools.com/) — ウェブ、ネイティブモバイル、デスクトップアプリのスマートな視覚的検証。ほとんどの自動化ソリューション(SeleniumやKarmaなど)とリモートランナー(Sauce Labs、Browser Stack)と統合。オープンソースに対して無料。単一ユーザーに対して週あたりの制限付きチェックポイントを含む無料枠あり。
  * [Appetize](https://appetize.io) — このクラウドベースのAndroidフォン/タブレットエミュレーターとiPhone/iPadシミュレーターで、AndroidとiOSアプリを直接ブラウザでテスト。無料枠には月30分の使用時間で2つの同時セッションが含まれます。アプリサイズに制限なし。
  * [Apptim](https://apptim.com) — パフォーマンスエンジニアリングのスキルがなくてもアプリのパフォーマンスとユーザー体験(UX)を評価できるモバイルテストツール。自身のデバイスを使用するデスクトップバージョンは100%無料で、iOSとAndroid両方で無制限のテストが可能。
  * [Argos](https://argos-ci.com) - 開発者向けオープンソースの視覚的テスト。無制限のプロジェクトで、月5,000スクリーンショットまで。オープンソースプロジェクトに対して無料。
  * [Bencher](https://bencher.dev/) - CIパフォーマンスの低下を検出する継続的ベンチマーキングツールスイート。すべてのパブリックプロジェクトに対して無料。
  * [browserstack.com](https://www.browserstack.com/) — 手動および自動ブラウザテスト、[オープンソースに対して無料](https://www.browserstack.com/open-source?ref=pricing)
  * [BugBug](https://bugbug.io/) - ウェブアプリケーション向けの軽量テスト自動化ツール。学習が容易でコーディングは不要。自分のコンピュータで無制限のテストを無料で実行可能。追加の月額料金でクラウド監視とCI/CD統合も利用可能。
  * [Checkly](https://checklyhq.com) - モダンなDevOps向けのコードファーストな合成監視。従来のプロバイダーの価格の一部でAPIとアプリを監視。Monitoring as CodeワークフローとPlaywrightを活用。開発者向けの寛大な無料枠あり。
  * [checkbot.io](https://www.checkbot.io/) — ウェブサイトが50以上のSEO、速度、セキュリティのベストプラクティスに従っているかテストするブラウザ拡張機能。小規模なウェブサイト向けの無料枠あり。
  * [CORS-Tester](https://cors-error.dev/cors-tester/) - 開発者とAPIテスター向けの無料ツールで、APIが特定のドメインに対してCORS対応しているかを確認し、ギャップを特定。実用的な洞察を得られます。
  * [cypress.io](https://www.cypress.io/) - ブラウザで実行されるあらゆるものに対する高速、簡単、信頼性の高いテスト。Cypress Test Runnerは常に制限や制約なしで無料でオープンソース。Cypress Dashboardはオープンソースプロジェクトに対して5ユーザーまで無料。
  * [Cypress Recorder by Preflight](https://cypress.preflight.com/) - ブラウザ上でAI駆動のCypressテスト/POMモデルを作成。AIの部分を除いてオープンソース。セルフヒーリングスクリプト、メール、ビジュアルテストを含む月5回のテスト作成まで無料。
  * [everystep-automation.com](https://www.everystep-automation.com/) — ウェブブラウザで行われたすべてのステップを記録・再生してスクリプトを作成、より少ないオプションで無料
  * [Gremlin](https://www.gremlin.com/gremlin-free-software) — Gremlinのカオスエンジニアリングツールを使用すると、顧客に影響を与える問題が発生する前に、システムの弱点を安全かつ確実に注入して見つけることができます。Gremlin Freeは最大5台のホストまたはコンテナに対してシャットダウンとCPU攻撃へのアクセスを提供します。
  * [gridlastic.com](https://www.gridlastic.com/) — 最大4つの同時セレニウムノード/10グリッド開始/月4,000テスト分の無料プランを提供するSelenium Gridテスト
  * [katalon.com](https://katalon.com) - Katalon Studio、TestOps(+ Visual Testing無料)、TestCloud、Katalon Recorderを含む、異なるテストレベルのあらゆる規模のチームを支援できるテストプラットフォームを提供。
  * [Keploy](https://keploy.io/) - Keployは開発者向けの機能テストツールキット。APIコールの記録からAPIのE2Eテスト(KTests)とモックまたはスタブ(KMocks)を生成。オープンソースプロジェクトに対して無料。
  * [knapsackpro.com](https://knapsackpro.com) - 任意のCIプロバイダーでテストスイートの最適な並列化により、テストを高速化。時間を節約するためにRuby、JavaScriptテストを並列CIノードで分割。テストファイル10分までの無料プランとオープンソースプロジェクトに対する無制限の無料プラン。
  * [lambdatest.com](https://www.lambdatest.com/) — seleniumとcypressでの手動、視覚的、スクリーンショット、自動ブラウザテスト、[オープンソースに対して無料](https://www.lambdatest.com/open-source-cross-browser-testing-tool)
  * [loadmill.com](https://www.loadmill.com/) - ネットワークトラフィックを分析してAPIとロードテストを自動的に作成。無料で月に最大50の同時ユーザーを最大60分間シミュレート可能。
  * [lost-pixel.com](https://lost-pixel.com) - Storybook、Ladle、Histoireストーリーとウェブアプリの包括的な視覚的回帰テスト。チームメンバー数無制限、オープンソースに対して完全無料、月7,000スナップショット。
  * [octomind.dev](https://www.octomind.dev/) - AIアシストのテストケース生成による自動生成、実行、メンテナンスされるPlaywright UIテスト
  * [percy.io](https://percy.io) - ウェブアプリ、静的サイト、スタイルガイド、またはコンポーネントライブラリに視覚的テストを追加。チームメンバー無制限、デモアプリ、無制限のプロジェクト、月5,000スナップショット。
  * [preflight.com](https://preflight.com) - ノーコードの自動ウェブテスト。UI変更に強いテストをブラウザで記録し、Windowsマシンで実行。CI/CDと統合可能。無料プランには動画、HTMLセッションなどを含む月50回のテスト実行が含まれます。
  * [qase.io](https://qase.io) - 開発者とQAチーム向けのテスト管理システム。テストケースの管理、テスト実行の構成、テストの実施、欠陥の追跡、影響の測定。無料枠にはすべてのコア機能が含まれ、添付ファイル用に500MBまで利用可能で、最大3ユーザーまで。
  * [Repeato](https://repeato.app/) コンピュータビジョンとAIを基盤としたノーコードのモバイルアプリテスト自動化ツール。ネイティブアプリ、flutter、react-native、web、ionicなど多くのアプリフレームワークで動作。無料プランはiOSとAndroidそれぞれ10テストに制限されますが、無制限のテスト実行を含む有料プランのほとんどの機能を利用できます。
  * [Requestly](https://requestly.com/) HTTPリクエストのインターセプト、リダイレクト、モックを行うオープンソースのChrome拡張機能。[デバッガー](https://requestly.com/products/web-debugger/)、[モックサーバー](https://requestly.com/products/mock-server/)、[APIクライアント](https://requestly.com/products/api-client/)、[セッション記録](https://requestly.com/products/session-book/)を特徴とします。URLのリダイレクト、HTTPヘッダーの変更、APIのモック、カスタムJSの注入、GraphQLリクエストの変更、モックAPIエンドポイントの生成、ネットワークとコンソールログを含むセッション記録が可能。無料枠で10個のルールまで作成可能。オープンソースに対して無料。
  * [seotest.me](https://seotest.me/) — 無料のオンページSEOウェブサイトテスター。1日10回の無料ウェブサイトクロール。技術に関係なく、任意のウェブサイトのオンページSEO結果を改善する方法についての有用なSEO学習リソースと推奨事項。
  * [snippets.uilicious.com](https://snippets.uilicious.com) - クロスブラウザテスト用のCodePenのようなもの。UI-liciousではユーザーストーリーのようにテストを書くことができ、無料プラットフォーム - UI-licious Snippets - を提供し、サインアップ不要でテスト実行あたり最大3分まで、Chrome上で無制限のテストを実行できます。バグを見つけた場合、テストの一意のURLをコピーして開発者に正確なバグの再現方法を示すことができます。
  * [TestCollab](https://testcollab.com) - ユーザーフレンドリーなテスト管理ソフトウェア。無料プランにはJira統合、無制限のプロジェクト、CSV/XLSxを使用したテストケースのインポート、時間追跡、1GBのファイルストレージが含まれます。
  * [testingbot.com](https://testingbot.com/) — Seleniumブラウザとデバイステスト、[オープンソースに対して無料](https://testingbot.com/open-source)
  * [Testspace.com](https://testspace.com/) - 自動テスト結果の公開用ダッシュボードとGitHubを使用してマニュアルテストをコードとして実装するためのフレームワーク。このサービスは[オープンソースに対して無料](https://github.com/marketplace/testspace-com)で、月450件の結果のアカウントを提供。
  * [tesults.com](https://www.tesults.com) - テスト結果のレポートとテストケース管理。一般的なテストフレームワークと統合。オープンソースソフトウェア開発者、個人、教育者、および小規模チームは、基本的な無料プロジェクトを超えた割引および無料提供を要求可能。
  * [UseWebhook.com](https://usewebhook.com) - ブラウザからウェブフックをキャプチャして検査。localhostへの転送、または履歴からの再生が可能。使用は無料。
  * [Vaadin](https://vaadin.com) — JavaまたはTypeScriptでスケーラブルなUIを構築し、統合されたツール、コンポーネント、デザインシステムを使用して、より速く反復し、より良いデザインを行い、開発プロセスを簡素化。無制限のプロジェクトに5年間の無料メンテナンス。
  * [websitepulse.com](https://www.websitepulse.com/tools/) — 様々な無料のネットワークおよびサーバーツール。
  * [webhook-test.com](https://webhook-test.com) - 統合時に一意のURLでウェブフックとHTTPリクエストをデバッグおよび検査。完全に無料で、無制限のURLを作成し、推奨事項を受け取ることができます。
  * [webhook.site](https://webhook.site) - カスタムURLでウェブフック、アウトバウンドHTTPリクエスト、またはメールを検証。一時的なURLとメールアドレスは常に無料。
  * [webhookbeam.com](https://webhookbeam.com) - プッシュ通知とメールを介してウェブフックを設定および監視。

**[⬆️ 目次に戻る](#table-of-contents)**

## セキュリティとPKI

  * [aikido.dev](https://www.aikido.dev) - SCA、SAST、CSPM、DAST、シークレット、IaC、マルウェア、コンテナスキャン、EOLなどをカバーするオールインワンのアプリセキュリティプラットフォーム。無料プランには2ユーザー、10リポジトリのスキャン、1クラウド、2コンテナ、1ドメインが含まれます。
  * [alienvault.com](https://www.alienvault.com/open-threat-exchange/reputation-monitor) — ネットワーク内の侵害されたシステムを発見
  * [Altcha.org](https://altcha.org/anti-spam) - 自然言語処理と機械学習を活用したウェブサイトとAPI向けのスパムフィルター。無料プランにはドメインごとに1日200リクエストが含まれます。
  * [atomist.com](https://atomist.com/) — 様々な開発タスクを自動化するより迅速で便利な方法。現在ベータ版。
  * [cloudsploit.com](https://cloudsploit.com/) — Amazon Web Services (AWS)のセキュリティと準拠性の監査とモニタリング
  * [Public Cloud Threat Intelligence](https://cloudintel.himanshuanand.com/) — パブリッククラウドインフラストラクチャを標的とする高信頼性の侵害指標(IOC)、一部はgithubで利用可能(https://github.com/unknownhad/AWSAttacks)。完全なリストはAPI経由で利用可能。
  * [CodeNotary.io](https://www.codenotary.io/) — コード、ファイル、ディレクトリ、またはコンテナを公証する消えない証明を持つオープンソースプラットフォーム
  * [crypteron.com](https://www.crypteron.com/) — クラウドファースト、開発者フレンドリーなセキュリティプラットフォームが.NETとJavaアプリケーションでのデータ侵害を防止
  * [CyberChef](https://gchq.github.io/CyberChef/) — 複雑なツールやプログラミング言語を扱うことなく、データの分析と符号化/復号化を行うためのシンプルで直感的なウェブアプリ。暗号化と暗号のスイスアーミーナイフのような存在。すべての機能は制限なく無料で使用可能。セルフホストも可能なオープンソース。
  * [DAS](https://signup.styra.com/) — Styra DAS Free、Open Policy Agent(OPA)認可の作成、デプロイ、管理のためのフルライフサイクルポリシー管理
  * [Datree](https://www.datree.io/) — マニフェストとHelmチャートがベストプラクティスと組織のポリシーに従っていることを確認することで、Kubernetesの設定ミスを防ぐオープンソースCLIツール
  * [Dependabot](https://dependabot.com/) — Ruby、JavaScript、Python、PHP、Elixir、Rust、Java(MavenとGradle)、.NET、Go、Elm、Docker、Terraform、Git Submodules、GitHub Actionsの自動依存関係更新。
  * [DJ Checkup](https://djcheckup.com) — この無料の自動チェックアップツールでDjangoサイトのセキュリティの欠陥をスキャン。Pony Checkupサイトからフォーク。
  * [Doppler](https://doppler.com/) — アプリケーションのシークレットと設定のためのユニバーサルシークレットマネージャー。様々なクラウドプロバイダーとの同期をサポート。基本的なアクセス制御を含む5ユーザーまで無料。
  * [Dotenv](https://dotenv.org/) — .envファイルを素早く安全に同期。Slackやメールなどのセキュアでないチャネルでの.envファイルの共有を停止し、重要な.envファイルを二度と失わないようにします。3人のチームメイトまで無料。
  * [GitGuardian](https://www.gitguardian.com) — 自動化されたシークレット検出と修復でソースコードからシークレットを排除。350以上のタイプのシークレットと機密ファイルをgitリポジトリでスキャン — 個人と25人以下の開発者チームに対して無料。
  * [Have I been pwned?](https://haveibeenpwned.com) — 侵害に関する情報を取得するためのREST API。
  * [hostedscan.com](https://hostedscan.com) — ウェブアプリケーション、サーバー、ネットワーク向けのオンライン脆弱性スキャナー。月10回の無料スキャン。
  * [Infisical](https://infisical.com/) — 開発者シークレットをチームとインフラストラクチャ全体で管理できるオープンソースプラットフォーム: ローカル開発からステージング/本番の第三者サービスまでどこでも。5人の開発者まで無料。
  * [Internet.nl](https://internet.nl) — IPv6、DNSSEC、HTTPS、DMARC、STARTTLS、DANEなどの最新のインターネット標準のテスト
  * [keychest.net](https://keychest.net) - SSL有効期限管理と統合CTデータベースを持つ証明書購入
  * [letsencrypt.org](https://letsencrypt.org/) — すべての主要ブラウザで信頼される証明書を提供する無料のSSL認証局
  * [meterian.io](https://www.meterian.io/) - Java、Javascript、.NET、Scala、Ruby、NodeJSプロジェクトの依存関係のセキュリティ脆弱性を監視。1つのプライベートプロジェクトに対して無料、オープンソースプロジェクトに対して無制限。
  * [Mozilla Observatory](https://observatory.mozilla.org/) — サイトのセキュリティ脆弱性を発見して修正。
  * [opswat.com](https://www.opswat.com/) — コンピュータ、デバイス、アプリケーション、設定のセキュリティ監視、25ユーザーまで無料で30日間の履歴。
  * [openapi.security](https://openapi.security/) - OpenAPI / SwaggerベースのAPIのセキュリティを素早くチェックする無料ツール。サインアップ不要。
  * [pixee.ai](https://pixee.ai) - 自動化されたプロダクトセキュリティエンジニアとして、無料のGitHubボットがJavaコードベースの脆弱性を自動的に解決するPRを提出。他の言語も近日対応予定！
  * [pyup.io](https://pyup.io) - Pythonの依存関係のセキュリティ脆弱性を監視し、自動的に更新。1つのプライベートプロジェクトに対して無料、オープンソースプロジェクトに対して無制限。
  * [qualys.com](https://www.qualys.com/community-edition) — ウェブアプリの脆弱性を発見し、OWASPリスクを監査
  * [report-uri.io](https://report-uri.io/) — CSPとHPKP違反のレポート
  * [ringcaptcha.com](https://ringcaptcha.com/) — 電話番号をIDとして使用するツール、無料で利用可能
  * [seclookup.com](https://www.seclookup.com/) - Seclookup APIはSIEMでドメインの脅威指標を強化し、ドメイン名に関する包括的な情報を提供し、脅威の検出と対応を改善できます。[こちら](https://account.seclookup.com/)から50,000回の無料ルックアップを取得。
  * [snyk.io](https://snyk.io) — オープンソースの依存関係の既知のセキュリティ脆弱性を発見して修正できます。オープンソースプロジェクトに対して無制限のテストと修復。プライベートプロジェクトは月200テストまで制限。
  * [ssllabs.com](https://www.ssllabs.com/ssltest/) — SSLウェブサーバーの設定の詳細な分析
  * [SOOS](https://soos.io) - オープンソースプロジェクトに対する無料で無制限のSCAスキャン。リリース前にセキュリティの脅威を検出して修正。シンプルで効果的なソリューションでプロジェクトを保護。
  * [StackHawk](https://www.stackhawk.com/) セキュリティバグが本番環境に到達する前に発見して修正するために、パイプライン全体でアプリケーションスキャンを自動化。1つのアプリに対して無制限のスキャンと環境。
  * [Sucuri SiteCheck](https://sitecheck.sucuri.net) - 無料のウェブサイトセキュリティチェックとマルウェアスキャナー
  * [Protectumus](https://protectumus.com) - PHPのウェブサイトセキュリティチェック、サイトアンチウイルス、サーバーファイアウォール(WAF)。無料枠では登録ユーザーにメール通知。
  * [TestTLS.com](https://testtls.com) - HTTPSに限らず、SSL/TLSサービスのセキュアなサーバー設定、証明書、チェーンなどをテスト。
  * [threatconnect.com](https://threatconnect.com) - 脅威インテリジェンス: サイバー脅威インテリジェンスについて学び始める個人の研究者、アナリスト、組織向けに設計。3ユーザーまで無料
  * [tinfoilsecurity.com](https://www.tinfoilsecurity.com/) — 自動化された脆弱性スキャン。無料プランでは週次XSSスキャンが可能
  * [Ubiq Security](https://ubiqsecurity.com/) — 3行のコードと自動キー管理でデータの暗号化と復号化。1つのアプリケーションと月100万回の暗号化まで無料。
  * [Virgil Security](https://virgilsecurity.com/) — デジタルソリューションにエンドツーエンドの暗号化、データベース保護、IoTセキュリティなどを実装するためのツールとサービス。250ユーザーまでのアプリケーションに対して無料。
  * [Vulert](https://vulert.com) - Vulertは、コードベースへのインストールやアクセスを必要とせずに、オープンソースの依存関係の新しい脆弱性を継続的に監視し、修正を推奨します。オープンソースプロジェクトに対して無料。
  * [Escape GraphQL Quickscan](https://escape.tech/) - GraphQLエンドポイントのワンクリックセキュリティスキャン。無料でログイン不要。
  * [HasMySecretLeaked](https://gitguardian.com/hasmysecretleaked) - パブリックGitHubリポジトリ、gist、issue、コメントで公開された2,000万以上の露出したシークレットを無料で検索
  * [Project Gatekeeper](https://gatekeeper.binarybiology.top/) - プライベートキー & CSRジェネレーター、SSL証明書デコーダー、証明書マッチャー、SSL証明書注文など、様々な機能を提供するオールインワンSSLツールキット。TXTレコードではなくCNAMEレコードを使用して、Let's Encrypt、Google Trust、BuyPassから無料のSSL証明書を生成することをユーザーに提供します。

**[⬆️ 目次に戻る](#table-of-contents)**

## 認証、認可、ユーザー管理

  * [Aserto](https://www.aserto.com) - アプリケーションとAPIのための細かい粒度の認可サービス。1000 MAUと100認可インスタンスまで無料。
  * [asgardeo.io](https://wso2.com/asgardeo) - SSO、MFA、パスワードレス認証などのシームレスな統合。フロントエンドとバックエンドアプリ用のSDKを含む。1000 MAUと5つのアイデンティティプロバイダーまで無料。
  * [Auth0](https://auth0.com/) — ホステッドSSO。無料プランには25,000 MAU、無制限のソーシャル接続、カスタムドメインなどが含まれます。
  * [Authgear](https://www.authgear.com) - パスワードレス、OTP、2FA、SSOを数分でアプリに追加。すべてのフロントエンドを含む。5000 MAUまで無料。
  * [Authress](https://authress.io/) — 認証ログインとアクセス制御、プロジェクトに対する無制限のアイデンティティプロバイダー。Facebook、Google、Twitterなど。最初の1000 APIコールは無料。
  * [Authy](https://authy.com) - 複数デバイスでの二要素認証(2FA)、バックアップ付き。Google認証システムの代替として使用可能。100回の認証成功まで無料。
  * [Cerbos Hub](https://www.cerbos.dev/product-cerbos-hub) - アクセスポリシーの作成、テスト、デプロイのための完全な認可管理システム。細かい粒度の認可とアクセス制御、月間アクティブプリンシパル100まで無料。
  * [Clerk](https://clerk.com) — ユーザー管理、認証、2FA/MFA、サインイン・サインアップ・ユーザープロファイル用の事前構築UIコンポーネントなど。月間アクティブユーザー10,000人まで無料。
  * [Cloud-IAM](https://www.cloud-iam.com/) — Keycloakアイデンティティとアクセスマネジメントをサービスとして提供。100ユーザーと1レルムまで無料。
  * [Corbado](https://www.corbado.com/) — 新規または既存のアプリにパスキーファーストの認証を追加。無制限のMAUに対して無料。
  * [Descope](https://www.descope.com/) — 高度にカスタマイズ可能な認証フロー、ノーコードとAPI/SDKの両方のアプローチを提供、月間アクティブユーザー7,500人、50テナント(最大5 SAML/SSOテナント)まで無料。
  * [duo.com](https://duo.com/) — ウェブサイトやアプリの二要素認証(2FA)。10ユーザーまで無料、すべての認証方法、無制限の統合、ハードウェアトークン。
  * [Kinde](https://kinde.com/) - 数分で製品に統合できるシンプルで堅牢な認証。7,500 MAUまで無料で始められる。
  * [logintc.com](https://www.logintc.com/) — プッシュ通知による二要素認証(2FA)、10ユーザー、VPN、ウェブサイト、SSHまで無料
  * [MojoAuth](https://mojoauth.com/) - MojoAuthを使用すると、数分でウェブ、モバイル、またはあらゆるアプリケーションにパスワードレス認証を実装できます。
  * [Okta](https://developer.okta.com/signup/) — ユーザー管理、認証、認可。月間アクティブユーザー100人まで無料。
  * [onelogin.com](https://www.onelogin.com/) — IDaaS、シングルサインオンアイデンティティプロバイダー、クラウドSSO IdP、3つの企業アプリと5つの個人アプリ、無制限のユーザー
  * [Ory](https://ory.sh/) - AuthN/AuthZ/OAuth2.0/ゼロトラスト管理セキュリティプラットフォーム。すべてのセキュリティ機能、無制限のチームメンバー、200日間アクティブユーザー、月25,000回の権限チェックを含む開発者アカウントが永久無料。
  * [Permit.io](https://permit.io) - マイクロサービス向けのRBAC、ABAC、ReBAC対応の認可サービスプラットフォーム。リアルタイム更新とノーコードポリシーUIを提供。月間アクティブユーザー1,000人まで無料。
  * [Phase Two](https://phasetwo.io) - Keycloakオープンソースアイデンティティとアクセス管理。1,000ユーザーまでのレルム、最大10のSSO接続、[Organization](https://phasetwo.io/product/organizations/)拡張機能を含むPhase TwoのKeycloak拡張コンテナを利用可能。
  * [SSOJet](https://ssojet.com/) - 認証を再構築せずにエンタープライズSSOを追加。無料プランには無制限の月間アクティブユーザー、無制限の組織、2つのSSO & 2つのSCIM接続が含まれます。
  * [Stytch](https://www.stytch.com/) - 認証と不正防止のためのAPIとSDKを提供するオールインワンプラットフォーム。無料プランには月間アクティブユーザー10,000人、無制限の組織、5つのSSO/SCIM接続、1,000のM2Mトークンが含まれます。
  * [Stack Auth](https://stack-auth.com) — 面倒でない、オープンソースの認証。最も開発者フレンドリーなソリューションで、わずか5分で始められます。無料でセルフホスト可能、または月間アクティブユーザー10,000人まで無料のマネージドSaaSバージョンを提供。
  * [SuperTokens](https://supertokens.com/) - アプリにネイティブに統合されるオープンソースの認証。素早く始められ、ユーザーと開発者のエクスペリエンスをコントロールできます。月間アクティブユーザー5,000人まで無料。
  * [Warrant](https://warrant.dev/) — アプリ向けのホステッド型エンタープライズグレードの認可とアクセス制御サービス。無料枠には月間100万APIリクエストと1,000の認可ルールが含まれます。
  * [ZITADEL Cloud](https://zitadel.com) — マルチテナント(B2B)ユースケースをサポートする、あなたのために機能するターンキーのユーザーとアクセス管理。認証リクエスト25,000回まで無料で、すべてのセキュリティ機能を利用可能(OTP、パスワードレス、ポリシーなどに課金なし)。
  * [PropelAuth](https://propelauth.com) - 数行のコードで即座にあらゆる規模の企業に販売可能。200ユーザーと10,000のトランザクションメールまで無料(「Powered by PropelAuth」というウォーターマークブランディング付き)。
  * [Logto](https://logto.io/) - 認証と認可の両方に対応する製品のユーザーアイデンティティを開発、保護、管理。月間アクティブユーザー5,000人まで無料で、オープンソースのセルフホストオプションも利用可能。
  * [WorkOS](https://workos.com/) - 月間アクティブユーザー100万人までの無料のユーザー管理と認証。メール+パスワード、ソーシャル認証、Magic Auth、MFAなどをサポート。

**[⬆️ 目次に戻る](#table-of-contents)**

## モバイルアプリの配布とフィードバック

  * [TestApp.io](https://testapp.io) - モバイルアプリが期待通りに動作することを確認するためのプラットフォーム。無料プラン：1アプリ、アナリティクス、無制限のバージョンとインストール、フィードバック収集。
  * [Loadly](https://loadly.io) - iOS & Androidベータアプリの配布サービス。無制限のダウンロード、高速ダウンロード、無制限のアップロードを完全無料で提供。
  * [Diawi](https://www.diawi.com) - iOS & Androidアプリを直接デバイスに配布。無料プラン：アップロード、パスワード保護リンク、1日の有効期限、10回のインストール。
  * [InstallOnAir](https://www.installonair.com) - iOS & Androidアプリを無線で配布。無料プラン：無制限のアップロード、プライベートリンク、ゲストは2日間有効、登録ユーザーは60日間有効。
  * [GetUpdraft](https://www.getupdraft.com) - テスト用のモバイルアプリ配布。無料プランには1アプリプロジェクト、3アプリバージョン、500MBストレージ、月間100アプリインストールが含まれます。
  * [Appho.st](https://appho.st) - モバイルアプリのホスティングプラットフォーム。無料プランには5アプリ、月間50ダウンロード、最大ファイルサイズ100MBが含まれます。

**[⬆️ 目次に戻る](#table-of-contents)**

## 管理システム

  * [bitnami.com](https://bitnami.com/) — IaaS上で準備済みアプリをデプロイ。1つのAWSマイクロインスタンスの管理が無料
  * [Esper](https://esper.io) — AndroidデバイスのMDMとMAM(DevOps対応)。1ユーザーライセンスと25MBアプリケーションストレージで100デバイスまで無料。
  * [jamf.com](https://www.jamf.com/) — iPad、iPhone、Macのデバイス管理、3デバイスまで無料
  * [Miradore](https://miradore.com) — デバイス管理サービス。デバイスフリートを最新に保ち、無制限のデバイスを無料でセキュアに。無料プランは基本機能を提供。
  * [moss.sh](https://moss.sh) - 開発者がウェブアプリとサーバーをデプロイ・管理するのを支援。月間25回のgitデプロイメントまで無料
  * [runcloud.io](https://runcloud.io/) - 主にPHPプロジェクトに焦点を当てたサーバー管理。1サーバーまで無料。
  * [ploi.io](https://ploi.io/) - サーバーとサイトを簡単に管理・デプロイできるサーバー管理ツール。1サーバーまで無料。

**[⬆️ 目次に戻る](#table-of-contents)**

## メッセージングとストリーミング

  * [Ably](https://www.ably.com/) - プレゼンス、永続性、配信保証付きのリアルタイムメッセージングサービス。無料プランには月間300万メッセージ、ピーク時100接続、ピーク時100チャンネルが含まれます。
  * [cloudamqp.com](https://www.cloudamqp.com/) — RabbitMQをサービスとして提供。Little Lemurプラン：月間最大100万メッセージ、最大20同時接続、最大100キュー、最大10,000キューメッセージ、複数AZのノード
  * [courier.com](https://www.courier.com/) — プッシュ、アプリ内、メール、チャット、SMS、その他のメッセージングチャネルをテンプレート管理などの機能付きで単一のAPIで提供。無料プランには月間10,000メッセージが含まれます。
  * [engagespot.co](https://engagespot.co/) — アプリ内インボックスとノーコードテンプレートエディタを備えた開発者向けマルチチャネル通知インフラストラクチャ。無料プランには月間10,000メッセージが含まれます。
  * [HiveMQ](https://www.hivemq.com/mqtt-cloud-broker/) - MQTTデバイスをクラウドネイティブIoTメッセージングブローカーに接続。100デバイスまで永久に無料で接続可能(クレジットカード不要)。
  * [knock.app](https://knock.app) – 開発者向け通知インフラストラクチャ。アプリ内、メール、SMS、Slack、プッシュなど複数のチャネルに単一のAPIコールで送信。無料プランには月間10,000メッセージが含まれます。
  * [NotificationAPI.com](https://www.notificationapi.com/) — 5分でどんなソフトウェアにもユーザー通知を追加。無料プランには月間10,000通知 + 100 SMSと自動通話が含まれます。
  * [Novu.co](https://novu.co) — 開発者向けオープンソース通知インフラストラクチャ。メール、SMS、ダイレクト、アプリ内、プッシュなどすべての通信チャネルを1か所で管理するためのシンプルなコンポーネントとAPI。無料プランには90日間の保持期間付きで月間30,000通知が含まれます。
  * [pusher.com](https://pusher.com/) — リアルタイムメッセージングサービス。最大100同時接続と1日200,000メッセージまで無料
  * [scaledrone.com](https://www.scaledrone.com/) — リアルタイムメッセージングサービス。最大20同時接続と1日100,000イベントまで無料
  * [synadia.com](https://synadia.com/ngs) — [NATS.io](https://nats.io)をサービスとして提供。グローバル、AWS、GCP、Azure。4kメッセージサイズ、50アクティブ接続、月間5GBデータまで永久無料。
  * [cloudkarafka.com](https://www.cloudkarafka.com/) - 共有Kafkaクラスター無料、最大5トピック、トピックあたり10MBデータ、28日間のデータ保持。
  * [pubnub.com](https://www.pubnub.com/) - Swift、Kotlin、Reactメッセージングを月間100万トランザクションまで。トランザクションには複数のメッセージを含めることが可能。
  * [eyeson API](https://developers.eyeson.team/) - WebRTC(SFU、MCU)ベースのビデオ通信APIサービスでビデオプラットフォームを構築。リアルタイムデータインジェクション、ビデオレイアウト、録画、完全な機能を備えたホステッドウェブUI(クイックスタート)またはカスタムUI用のパッケージを提供。開発者向けに[月間1000会議分無料枠](https://apiservice.eyeson.com/api-pricing)あり。
  * [webpushr](https://www.webpushr.com/) - Webプッシュ通知 - 最大10,000購読者まで無料、無制限のプッシュ通知、ブラウザ内メッセージング
  * [httpSMS](https://httpsms.com) - AndroidフォンをSMSゲートウェイとして使用してテキストメッセージを送受信。月間200メッセージまで無料で送受信可能。
  * [EMQX Serverless](https://www.emqx.com/en/cloud/serverless-mqtt) - 数秒で利用可能なスケーラブルで安全なサーバーレスMQTTブローカー。月間100万セッション分無料(クレジットカード不要)。
  * [Pocket Alert](https://pocketalert.app) - iOSとAndroidデバイスにプッシュ通知を送信。APIまたはWebhooksで簡単に統合でき、アラートを完全にコントロール可能。無料プラン：1デバイス・1アプリケーションに対して1日50メッセージ。

**[⬆️ 目次に戻る](#table-of-contents)**

## ログ管理

  * [bugfender.com](https://bugfender.com/) — 1日10万行のログまで無料、24時間保持
  * [logentries.com](https://logentries.com/) — 月5GBまで無料、7日間保持
  * [loggly.com](https://www.loggly.com/) — シングルユーザーは無料、1日200MB、7日間保持
  * [logz.io](https://logz.io/) — 1日1GBまで無料、1日保持
  * [ManageEngine Log360 Cloud](https://www.manageengine.com/cloud-siem/) — Manage Engineが提供するログ管理サービス。無料プランでは50GBのストレージ、15日間のストレージ保持、7日間の検索が可能。
  * [papertrailapp.com](https://papertrailapp.com/) — 48時間の検索、7日間のアーカイブ、月50MB
  * [sematext.com](https://sematext.com/logsene) — 1日500MBまで無料、7日間保持
  * [sumologic.com](https://www.sumologic.com/) — 1日500MBまで無料、7日間保持
  * [logflare.app](https://logflare.app/) — アプリ1つにつき月1,296万エントリーまで無料、3日間保持
  * [logtail.com](https://logtail.com/) — ClickHouseベースのSQL互換ログ管理。月1GBまで無料、3日間保持。
  * [logzab.com](https://logzab.com/) — 監査証跡管理システム。月1,000ユーザーアクティビティログまで無料、1ヶ月保持、最大5プロジェクトまで。
  * [openobserve.ai](https://openobserve.ai/) - 月200GB取り込み無料、15日間保持

**[⬆️ 目次に戻る](#table-of-contents)**

## 翻訳管理

  * [crowdin.com](https://crowdin.com/) — オープンソース向けに無制限のプロジェクト、文字列、コラボレーターを提供
  * [gitlocalize.com](https://gitlocalize.com) - プライベート・パブリックリポジトリともに無料で無制限
  * [Lecto](https://lecto.ai/) - 機械翻訳API、無料枠あり(30リクエスト無料、1リクエストあたり1000文字まで翻訳可能)。Loco Translate Wordpressプラグインと統合。
  * [lingohub.com](https://lingohub.com/) — 3ユーザーまで無料、オープンソースは常に無料
  * [localazy.com](https://localazy.com) - ソース言語1000文字列まで無料、言語数無制限、貢献者無制限、スタートアップとオープンソース向けの特別プラン
  * [Localeum](https://localeum.com) - 1000文字列まで無料、1ユーザー、言語数無制限、プロジェクト数無制限
  * [localizely.com](https://localizely.com/) — オープンソース向けに無料
  * [Loco](https://localise.biz/) — 2000翻訳まで無料、翻訳者数無制限、プロジェクトあたり10言語、プロジェクトあたり1000翻訳可能アセット
  * [oneskyapp.com](https://www.oneskyapp.com/) — 5ユーザーまでの限定無料版、オープンソースは無料
  * [POEditor](https://poeditor.com/) — 1000文字列まで無料
  * [SimpleLocalize](https://simplelocalize.io/) - 100翻訳キーまで無料、文字列数無制限、言語数無制限、スタートアップ向けプラン
  * [Texterify](https://texterify.com/) - シングルユーザーは無料
  * [Tolgee](https://tolgee.io) - 制限付き翻訳の無料SaaS提供、永久無料のセルフホスト版
  * [transifex.com](https://www.transifex.com/) — オープンソース向けに無料
  * [Translation.io](https://translation.io) - オープンソース向けに無料
  * [Translized](https://translized.com) - 1000文字列まで無料、1ユーザー、言語数無制限、プロジェクト数無制限
  * [webtranslateit.com](https://webtranslateit.com/) — 500文字列まで無料
  * [weblate.org](https://weblate.org/) — 自由なプロジェクト向けに10,000文字列ソースまで無料、無制限のセルフホストオンプレミス
  * [Free PO editor](https://pofile.net/free-po-editor) — 誰でも無料
  * [Lingo.dev](https://lingo.dev) – オープンソースのAI駆動CLIによるウェブ＆モバイルローカライゼーション。独自のLLMを使用するか、Lingo.dev管理のローカライゼーションエンジンで月10,000ワード無料。

**[⬆️ 目次に戻る](#table-of-contents)**

## モニタリング

  * [UptimeObserver.com](https://uptimeobserver.com) - 5分間隔で20のアップタイムモニターとカスタマイズ可能なステータスページを商用利用も含めて提供。メールとTelegramによるリアルタイム通知が無制限。クレジットカード不要で開始可能。
  * [Pingmeter.com](https://pingmeter.com/) - 10分間隔で5つのアップタイムモニター。SSH、HTTP、HTTPS、およびカスタムTCPポートの監視が可能。
  * [alerty.ai](https://www.alerty.ai) - FE、BE、DBなどの無料APMとモニタリング + 無料エージェント実行。
  * [appdynamics.com](https://www.appdynamics.com/) — 24時間のメトリクスが無料、アプリケーションパフォーマンス管理エージェントは各1つまで(Java、.NET、PHP、Node.js)
  * [appneta.com](https://www.appneta.com/) — 1時間のデータ保持で無料
  * [appspector.com](https://appspector.com/) - iOS/Android/Flutterのリモートデバッグ用ミッションコントロール。小規模トラフィック(64MBのログ)まで無料。
  * [assertible.com](https://assertible.com) — 自動化されたAPIテストとモニタリング。チームと個人向けの無料プラン。
  * [bleemeo.com](https://bleemeo.com) - 3サーバー、5アップタイムモニター、ユーザー数無制限、ダッシュボード無制限、アラートルール無制限まで無料。
  * [Core Web Vitals History](https://punits.dev/core-web-vitals-historical/) - URLまたはウェブサイトのCore Web Vitals履歴を確認。
  * [checklyhq.com](https://checklyhq.com) - 開発者向けのオープンソースE2E/合成モニタリングと詳細なAPIモニタリング。無料プランでは5ユーザーと50k+チェック実行が可能。
  * [cloudsploit.com](https://cloudsploit.com) — AWSのセキュリティと設定モニタリング。無料：無制限のオンデマンドスキャン、無制限のユーザー、無制限の保存アカウント。サブスクリプション：自動スキャン、APIアクセスなど。
  * [cronitor.io](https://cronitor.io/) - cronジョブ、ウェブサイト、API等のパフォーマンスインサイトとアップタイムモニタリング。5モニターまでの無料枠。
  * [datadoghq.com](https://www.datadoghq.com/) — 5ノードまで無料
  * [deadmanssnitch.com](https://deadmanssnitch.com/) — cronジョブのモニタリング。1つの無料スニッチ(モニター)、他のユーザーを紹介すると追加可能
  * [downtimemonkey.com](https://downtimemonkey.com/) — 5分間隔で60のアップタイムモニター。メール、Slackアラート。
  * [economize.cloud](https://economize.cloud) — Economizeはクラウドインフラコストを整理・最適化・レポートすることでクラウドインフラコストを明確化。Google Cloud Platformで月5,000ドルまでの支出を無料で分析。
  * [elastic.co](https://www.elastic.co/solutions/apm) — JSデベロッパー向けの即時パフォーマンスインサイト。24時間のデータ保持で無料
  * [Grafana Cloud](https://grafana.com/products/cloud/) - Grafana Cloudはメトリクスとログを統合する組み合わせ可能な監視プラットフォーム。無料：3ユーザー、10ダッシュボード、100アラート、PrometheusとGraphiteでのメトリクス保存(10,000シリーズ、14日保持)、Lokiでのログ保存(50GBのログ、14日保持)
  * [healthchecks.io](https://healthchecks.io) — cronジョブとバックグラウンドタスクのモニタリング。20チェックまで無料。
  * [Hydrozen.io](https://hydrozen.io) — アップタイムモニタリング＆ステータスページ、無料プラン：10アップタイムモニター、5ハートビートモニター、1ドメインモニター、1ステータスページ無料。
  * [incidenthub.cloud](https://incidenthub.cloud/) — クラウドとSaaSのステータスページアグリゲーター - 20モニターと2通知チャネル(SlackとDiscord)が永久無料。
  * [inspector.dev](https://www.inspector.dev) - 1分以内に完全なリアルタイムモニタリングダッシュボードを提供、永久無料枠あり。
  * [instrumentalapp.com](https://instrumentalapp.com) - 美しく使いやすいアプリケーションとサーバーモニタリング、500メトリクスと3時間のデータ可視性まで無料
  * [keychest.net/speedtest](https://keychest.net/speedtest) - Digital Ocean に対する独立したスピードテストとTLSハンドシェイクレイテンシーテスト
  * [letsmonitor.org](https://letsmonitor.org) - SSLモニタリング、5モニターまで無料
  * [linkok.com](https://linkok.com) - オンラインのリンク切れチェッカー、小規模ウェブサイト(100ページまで)は無料、オープンソースプロジェクトは完全無料。
  * [loader.io](https://loader.io/) — 制限付きの無料負荷テストツール
  * [netdata.cloud](https://www.netdata.cloud/) — Netdataはリアルタイムメトリクスを収集するオープンソースツール。成長中の製品で、GitHubでも見つけることができます！
  * [newrelic.com](https://www.newrelic.com) — エンジニアがより完璧なソフトウェアを作るために構築された New Relic 監視プラットフォーム。モノリスからサーバーレスまで、すべてを計測し、分析、トラブルシューティング、最適化できます。無料枠では月100GBの無料データ取り込み、1人の無料フルアクセスユーザー、無制限の無料基本ユーザーを提供。
  * [Middleware.io](https://middleware.io/) - Middleware監視プラットフォームはアプリとスタックの完全な可視性を提供し、大規模な監視と診断を可能にします。開発者コミュニティ向けの永久無料プランでは、100万ログイベントまでのログモニタリング、2ホストまでのインフラ監視とAPMを提供。
  * [nixstats.com](https://nixstats.com) - 1サーバーまで無料。メール通知、公開ステータスページ、60秒間隔など。
  * [OnlineOrNot.com](https://onlineornot.com/) - ウェブサイトとAPIのアップタイムモニタリング、cronジョブとスケジュールタスクのモニタリングを提供。また、ステータスページも提供。3分間隔で最初の5つのチェックが無料。無料枠ではSlack、Discord、メールでアラートを送信。
  * [OntarioNet.ca CN Test](https://cntest.ontarionet.ca) — グレートファイアウォールによってウェブサイトが中国でブロックされているかチェック。中国とアメリカのサーバーで検出されたDNS結果とASN情報を比較してDNS汚染を特定。
  * [opsgenie.com](https://www.opsgenie.com/) — 常時稼働サービスの運用のための強力なアラートと待機管理。5ユーザーまで無料。
  * [paessler.com](https://www.paessler.com/) — 強力なインフラと

ネットワークモニタリングソリューション。アラート、強力な可視化機能、基本的なレポート機能を含む。100センサーまで無料。
  * [pagecrawl.io](https://pagecrawl.io/) - ウェブサイトの変更を監視、毎日のチェックで6モニターまで無料。
  * [syagent.com](https://syagent.com/) — 非商用の無料サーバーモニタリングサービス、アラートとメトリクス。
  * [pagerly.io](https://pagerly.io/) - Slack上でのオンコール管理(PagerdutyやOpsGenieと統合)。1チーム(1チームは1つのオンコールを指す)まで無料
  * [pagertree.com](https://pagertree.com/) - アラートとオンコール管理のシンプルなインターフェース。5ユーザーまで無料。
  * [phare.io](https://phare.io/) - 無制限のプロジェクトと無制限のステータスページに対して100,000イベントまで無料のアップタイムモニタリング。
  * [pingbreak.com](https://pingbreak.com/) — モダンなアップタイムモニタリングサービス。無制限のURLをチェックし、Discord、Slack、メールでダウンタイム通知を受け取れる。
  * [pingpong.one](https://pingpong.one/) — モニタリング機能付きの高度なステータスページプラットフォーム。無料枠にはSSLサブドメイン付きの1つのカスタマイズ可能な公開ステータスページが含まれる。Proプランはオープンソースプロジェクトと非営利団体に無料で提供。
  * [robusta.dev](https://home.robusta.dev/) — Prometheusベースの強力なKubernetesモニタリング。独自のPrometheusを持ち込むか、オールインワンバンドルをインストール。無料枠は最大20 Kubernetesノードまで。Slack、Microsoft Teams、Discord等でアラート。PagerDuty、OpsGenie、VictorOps、DataDog、その他多くのツールと統合。
  * [sematext.com](https://sematext.com/) — 24時間のメトリクス、無制限のサーバー、10カスタムメトリクス、500,000カスタムメトリクスデータポイント、無制限のダッシュボード、ユーザーなどが無料。
  * [sitemonki.com](https://sitemonki.com/) — ウェブサイト、ドメイン、Cron＆SSLモニタリング、各カテゴリー5モニターまで無料
  * [sitesure.net](https://sitesure.net) - ウェブサイトとcronモニタリング - 2モニターまで無料
  * [skylight.io](https://www.skylight.io/) — 最初の100,000リクエストまで無料(Railsのみ)
  * [speedchecker.xyz](https://probeapi.speedchecker.xyz/) — パフォーマンスモニタリングAPI、Ping、DNSなどをチェック。
  * [stathat.com](https://www.stathat.com/) — 10の統計情報から無料で開始、期限なし
  * [statuscake.com](https://www.statuscake.com/) — ウェブサイトモニタリング、制限付きで無制限のテストが無料
  * [statusgator.com](https://statusgator.com/) — ステータスページモニタリング、3モニターまで無料
  * [SweetUptime](https://dicloud.net/sweetuptime-server-uptime-monitoring/) — サーバーモニタリング、アップタイムモニタリング、DNS＆ドメインモニタリング。10サーバー、10アップタイム、10ドメインまで無料。
  * [thousandeyes.com](https://www.thousandeyes.com/) — ネットワークとユーザーエクスペリエンスモニタリング。3ロケーションと主要ウェブサービスの20データフィードが無料
  * [uptimetoolbox.com](https://uptimetoolbox.com/) — 5ウェブサイトまで無料モニタリング、60秒間隔、公開ステータスページ。
  * [zenduty.com](https://www.zenduty.com/) — ネットワーク運用、サイト信頼性エンジニアリング、DevOpsチーム向けのエンドツーエンドのインシデント管理、アラート、オンコール管理、レスポンスオーケストレーションプラットフォーム。5ユーザーまで無料。
  * [instatus.com](https://instatus.com) - 10秒で美しいステータスページを取得。無制限のサブスクリプションと無制限のチームで永久無料。
  * [Squadcast.com](https://squadcast.com) - SquadcastはSREベストプラクティスを促進するように設計されたエンドツーエンドのインシデント管理ソフトウェア。10ユーザーまでの永久無料プランを提供。
  * [RoboMiri.com](https://robomiri.com/) - RoboMiriは、cronjob、キーワード、ウェブサイト、ポート、pingなど幅広いモニターを提供する安定したアップタイムモニター。3分間隔で25のアップタイムチェックが無料。電話、SMS、メール、Webhooksでアラート。
  * [Better Stack](https://betterstack.com/better-uptime) - アップタイムモニタリング、インシデント管理、オンコールスケジューリング/アラート、ステータスページを1つの製品で提供。無料プランには3分間隔のチェックとステータスページ付きで10モニターが含まれる。
  * [Pulsetic](https://pulsetic.com) - 10モニター、6ヶ月の履歴アップタイム/ログ、無制限のステータスページ、カスタムドメインを含む！無期限で無制限のメールアラートが無料。クレジットカード不要。
  * [Wachete](https://www.wachete.com) - 5ページまでモニター、24時間ごとにチェック。
  * [Xitoring.com](https://xitoring.com/) — アップタイムモニタリング：20無料、LinuxとWindowsサーバーモニタリング：5無料、ステータスページ：1無料 - モバイルアプリ、複数の通知チャネル、その他多数！
  * [Servervana](https://servervana.com) - 大規模プロジェクトとチーム向けの高度なアップタイムモニタリング。HTTPモニタリング、ブラウザベースのモニタリング、DNSモニタリング、ドメインモニタリング、ステータスページなどをサポート。無料枠には10 HTTPモニター、1 DNSモニター、1ステータスページが含まれる。

**[⬆️ 目次に戻る](#table-of-contents)**

## クラッシュと例外処理

  * [CatchJS.com](https://catchjs.com/) - スクリーンショットとクリックトレイルを含むJavaScriptエラートラッキング。オープンソースプロジェクトは無料。
  * [bugsnag.com](https://www.bugsnag.com/) — 初期トライアル後、月2,000エラーまで無料
  * [elmah.io](https://elmah.io/) — Web開発者向けのエラーログとアップタイムモニタリング。オープンソースプロジェクト向けに無料のSmall Businessサブスクリプション。
  * [Embrace](https://embrace.io/) — モバイルアプリモニタリング。小規模チーム向けに年間100万ユーザーセッションまで無料。
  * [exceptionless](https://exceptionless.com) — リアルタイムのエラー、機能、ログレポートなど。月3,000イベント/1ユーザーまで無料。オープンソースで、無制限に使用できる自己ホスティングが可能。
  * [GlitchTip](https://glitchtip.com/) — シンプルなオープンソースエラートラッキング。オープンソースのSentry SDKsと互換性あり。月1000イベントまで無料、または制限なしで自己ホスティング可能
  * [honeybadger.io](https://www.honeybadger.io) - 例外、アップタイム、cronモニタリング。小規模チームとオープンソースプロジェクト向けに無料(月12,000エラー)。
  * [memfault.com](https://memfault.com) — クラウドデバイスの観察とデバッグプラットフォーム。[Nordic](https://app.memfault.com/register-nordic)、[NXP](https://app.memfault.com/register-nxp)、[Laird](https://app.memfault.com/register-laird)デバイス向けに100デバイスまで無料。
  * [rollbar.com](https://rollbar.com/) — 例外とエラーモニタリング、無料プランでは月5,000エラー、無制限ユーザー、30日間保持
  * [sentry.io](https://sentry.io/) — Sentryはアプリの例外をリアルタイムで追跡し、小規模な無料プランを提供。月5,000エラー/1ユーザーまで無料、自己ホスティングの場合は無制限に使用可能
  * [Axiom](https://axiom.co/) — 30日間の保持期間で最大0.5 TBのログを保存。VercelなどのプラットフォームとのインテグレーションとEmail/Discord通知機能付きの高度なデータクエリを含む。
  * [Semaphr](https://semaphr.com) — モバイルアプリ向けの無料オールインワンキルスイッチ。
  * [Jam](https://jam.dev) - ワンクリックで開発者フレンドリーなバグレポート。無制限のjamを含む無料プラン。
  * [Whitespace](https://whitespace.dev) – ブラウザ内でワンクリックのバグレポート。個人利用向けに無制限の録画を含む無料プラン。

**[⬆️ トップに戻る](#table-of-contents)**

## 検索

  * [algolia.com](https://www.algolia.com/) — タイプミス許容、関連性、UIライブラリを備えた、簡単に検索体験を作成できるホスト型検索ソリューション。無料の「Build」プランには100万ドキュメントと月1万検索が含まれます。また、[開発者ドキュメント検索](https://docsearch.algolia.com/)も無料で提供。
  * [bonsai.io](https://bonsai.io/) — 1 GBメモリと1 GBストレージまで無料
  * [CommandBar](https://www.commandbar.com/) - 統合検索バーをサービスとして提供。ウェブベースのUIウィジェット/プラグインで、ユーザーが製品内のコンテンツ、ナビゲーション、機能などを検索できるようにし、発見可能性を向上。月間アクティブユーザー1,000人まで無料、無制限のコマンド。
  * [Orama Cloud](https://orama.com/pricing) — 3つのインデックス、インデックスあたり10万ドキュメント、無制限の全文/ベクトル/ハイブリッド検索、60日間の分析が無料
  * [searchly.com](http://www.searchly.com/) — 2つのインデックスと20 MBストレージまで無料
  * [easysitesearch.com](https://easysitesearch.com/) — 自動ウェブクローラーベースのインデックス作成による検索ウィジェットとAPI。50サブページまで無制限の検索が無料。

**[⬆️ トップに戻る](#table-of-contents)**

## 教育とキャリア開発

  * [FreeCodeCamp](https://www.freecodecamp.org/) - データ分析、情報セキュリティ、Web開発などの無料コースと認定を提供するオープンソースプラットフォーム。
  * [The Odin Project](https://www.theodinproject.com/) - Web開発向けのJavaScriptとRubyに焦点を当てた、無料のオープンソースプラットフォーム。
  * [Free Professional Resume Templates & Editor](https://www.overleaf.com/latex/templates/tagged/cv) - 経験豊富なプロフェッショナル向けの多数の履歴書テンプレートを提供する無料プラットフォーム。クローン、編集、ダウンロードが可能で、ATS最適化済み。
  * [DeepLearning.AI Short Courses](https://www.deeplearning.ai/short-courses/) - 業界をリードする専門家による無料の短期コース。1時間以内で最新の生成AIツールとテクニックを実践的に学べる。
  * [LabEx](https://labex.io) - インタラクティブなラボと実世界のプロジェクトを通じて、Linux、DevOps、サイバーセキュリティ、プログラミング、データサイエンスなどのスキルを開発。
  * [Roadmap.sh](https://roadmap.sh) - ブロックチェーンからUXデザインまで、開発のあらゆる側面をカバーする無料の学習ロードマップ。
  * [Cisco Networking Academy, Skills for All](https://skillsforall.com/) - サイバーセキュリティ、ネットワーキング、Pythonなどのトピックで認定資格に準拠した無料コースを提供。
  * [MIT OpenCourseWare](https://ocw.mit.edu/) - MITの2,500以上のコースの教材をオンラインで公開し、世界中の学習者と教育者に知識を無料で共有。YouTubeチャンネルは[@mitocw](https://www.youtube.com/@mitocw/featured)で見つけることができます。
  * [W3Schools](https://www.w3schools.com/) - HTML、CSS、JavaScriptなどのWeb開発技術に関する無料チュートリアルを提供。
  * [Khan Academy](https://www.khanacademy.org/computing/computer-programming) - 基本的および高度なHTML/CSS、JavaScript、SQLを学ぶための無料オンラインガイド。
  * [Full Stack Open](https://fullstackopen.com/en/) – React、Node.js、GraphQL、TypeScriptなどのモダンなWeb開発に関する大学レベルの無料コース。完全にオンラインで自己ペース。
  * [Django-tutorial.dev](https://django-tutorial.dev) - 初めてのフレームワークとしてDjangoを学ぶための無料オンラインガイドを提供し、ユーザーが書いた記事に無料のdofollowバックリンクを提供。

**[⬆️ トップに戻る](#table-of-contents)**

## メール

  * [10minutemail](https://10minutemail.com) - テスト用の無料の一時的なメール。
  * [AhaSend](https://ahasend.com) - トランザクショナルメールサービス、月1000メールまで無料。無料プランには無制限のドメイン、チームメンバー、webhooks、メッセージルートが含まれる。
  * [AnonAddy](https://anonaddy.com) - オープンソースの匿名メール転送、無制限のメールエイリアスを無料で作成可能
  * [Antideo](https://www.antideo.com) - 無料枠では1時間あたり10 APIリクエストでメール検証、IP、電話番号の検証が可能。クレジットカード不要。
  * [Brevo](https://www.brevo.com/) — 月9,000メール、1日300メールまで無料
  * [OneSignal](https://onesignal.com/) — 月10,000メール、クレジットカード不要。
  * [Bump](https://bump.email/) - 10個のBumpメールアドレス、1つのカスタムドメインまで無料
  * [Burnermail](https://burnermail.io/) – 5つのバーナーメールアドレス、1つのメールボックス、7日間のメールボックス履歴まで無料
  * [Buttondown](https://buttondown.email/) — ニュースレターサービス。100購読者まで無料
  * [CloudMailin](https://www.cloudmailin.com/) - HTTP POSTによる受信メールとトランザクショナルな送信メール - 月10,000メールまで無料
  * [Contact.do](https://contact.do/) — コンタクトフォームをリンクで提供(コンタクトフォーム用のbitly)
  * [debugmail.io](https://debugmail.io/) — 開発者向けの使いやすいテストメールサーバー
  * [DNSExit](https://dnsexit.com/) - ドメイン下で2つのメールアドレスまで無料、100MBのストレージスペース付き。IMAP、POP3、SMTP、SPF/DKIMサポート。
  * [EmailLabs.io](https://emaillabs.io/en) — 毎月最大9,000メール、毎日最大300メールまで無料で送信可能。
  * [EmailOctopus](https://emailoctopus.com) - 2,500購読者と月10,000メールまで無料
  * [EmailJS](https://www.emailjs.com/) – これは完全なメールサーバーではなく、資格情報を露出せずにクライアントから直接メールを送信できるメールクライアント。無料枠では月200リクエスト、2つのメールテンプレート、50Kbまでのリクエスト、制限付きの連絡先履歴を提供。
  * [EtherealMail](https://ethereal.email) - Etherealは主にNodemailerとEmailEngineユーザー向けの偽のSMTPサービス(ただし制限はない)。メッセージが配信されることのない完全に無料の非トランザクショナルメールサービス。
  * [Temp-Mail.org](https://temp-mail.org/en/) - さまざまなドメインを利用した一時的/使い捨てメール生成。メールアドレスはページをリロードするたびに更新される。完全に無料でサービスに料金は含まれない。
  * [TempMailDetector.com](https://tempmaildetector.com/) - 月200メールまで無料で検証し、メールが一時的なものかどうかを確認可能。
  * [Emailvalidation.io](https://emailvalidation.io) - 月100メールまで無料で検証
  * [FakeMailGenerator.com](https://www.fakemailgenerator.com/) - ドイツの一時的/使い捨てメール生成サービス。10のドメインをサポートし、無制限のアドレス作成が可能。(広告あり)ただし、それ以外のサービスに料金は含まれず、完全に無料。
  * [forwardemail.net](https://forwardemail.net) - カスタムドメイン用の無料メール転送。ドメイン名で無制限のメールアドレスを作成して転送可能(**注**: スパムのため.casa、.cf、.click、.email、.fit、.ga、.gdn、.gq、.lat、.loan、.london、.men、.ml、.pl、.rest、.ru、.tk、.top、.workのTLDを使用する場合は料金が必要)
  * [Imitate Email](https://imitate.email) - ビルド/QAやCI/CD全体でメール機能をテストするためのサンドボックスメールサーバー。無料アカウントは永久に1日15メールまで。
  * [ImprovMX](https://improvmx.com) – 無料のメール転送。
  * [EForw](https://www.eforw.com) – 1つのドメインの無料メール転送。ドメインからメールを受信および送信可能。
  * [Inboxes App](https://inboxesapp.com) - 1日最大3つの一時的なメールを作成し、便利なChrome拡張機能から使用が終わったら削除可能。サインアップフローのテストに最適。
  * [inboxkitten.com](https://inboxkitten.com/) - 最大3日間のメール自動削除機能付きの無料一時的/使い捨てメールボックス。オープンソースで自己ホスティング可能。
  * [mail-tester.com](https://www.mail-tester.com) - メールのDNS/SPF/DKIM/DMARCの設定が正しいかテスト、月20回まで無料。
  * [dkimvalidator.com](https://dkimvalidator.com/) - メールのDNS/SPF/DKIM/DMARCの設定が正しいかテスト、roundsphere.comによる無料サービス
  * [mailcatcher.me](https://mailcatcher.me/) — メールをキャッチしてウェブインターフェースで提供。
  * [mailchannels.com](https://www.mailchannels.com) - REST APIとSMTPインテグレーションを備えたメールAPI、月3,000メールまで無料。
  * [Mailcheck.ai](https://www.mailcheck.ai/) - 一時的なメールアドレスでのユーザー登録を防止、1時間あたり120リクエスト(月約86,400)
  * [Mailchimp](https://mailchimp.com/) — 500購読者と月1,000メールまで無料。
  * [Maildroppa](https://maildroppa.com) - 100購読者まで無料で、無制限のメールと自動化も含む。
  * [MailerLite.com](https://www.mailerlite.com) — 月1,000購読者、12,000メールまで無料
  * [MailerSend.com](https://www.mailersend.com) — トランザクショナルメール用のメールAPI、SMTP、月3,000メールまで無料
  * [mailinator.com](https://www.mailinator.com/) — 好きなインボックスを使用できる無料の公開メールシステム
  * [Mailjet](https://www.mailjet.com/) — 月6,000メールまで無料(1日200メールの送信制限)
  * [Mailnesia](https://mailnesia.com) - 登録リンクを自動訪問する無料の一時的/使い捨てメール
  * [mailsac.com](https://mailsac.com) - 一時的なメールテスト用の無料API、無料の公開メールホスティング、送信キャプチャ、email-to-slack/websocket/webhook(月1,500 API制限)
  * [Mailtrap.io](https://mailtrap.io/) — 開発用の偽のSMTPサーバー、1つのインボックス、100メッセージ、チームメンバーなし、2メール/秒、転送ルールなしの無料プラン。
  * [Mail7.io](https://www.mail7.io/) — QA開発者向けの無料一時メールアドレス。ウェブインターフェースまたはAPIを使用してメールアドレスを即座に作成。
  * [Momentary Email](https://www.momentaryemail.com/) — 無料の一時的なメールアドレス。ウェブサイトまたはRSSフィードで受信メールを読むことが可能。
  * [Mutant Mail](https://www.mutantmail.com/) – 10個のメールID、1つのドメイン、1つのメールボックスまで無料。すべてのメールIDに対して単一のメールボックス。
  * [Outlook.com](https://outlook.live.com/owa/) - 無料の個人用メールとカレンダー。
  * [Parsio.io](https://parsio.io) — 無料のメールパーサー(メールを転送、データを抽出、サーバーに送信)
  * [pepipost.com](https://pepipost.com) — 最初の月は30,000メール無料、その後は最初の100メール/日が無料。
  * [Plunk](https://useplunk.com) - 月3,000メールまで無料
  * [Postmark](https://postmarkapp.com/) - 月100メール無料、無制限のDMARC週次ダイジェスト。
  * [Proton Mail](https://proton.me/mail) - エンドツーエンドの暗号化が組み込まれた無料のセキュアメールアカウントサービスプロバイダー。1GB無料ストレージ。
  * [Queuemail.dev](https://queuemail.dev) - 信頼性の高いメール配信API。無料枠(月10,000メール)。非同期送信。複数のSMTPサーバーを使用可能。ブロックリスト、ログ記録、トラッキング、Webhooksなど。
  * [QuickEmailVerification](https://quickemailverification.com) - 無料枠では、DEA検出、DNSルックアップ、SPF検出などの他の無料APIと共に、1日100メールまで無料で検証可能。
  * [Resend](https://resend.com) - 開発者向けトランザクショナルメールAPI。月3,000メール、1日100メール、1つのカスタムドメインまで無料。
  * [Sender](https://www.sender.net) 月15,000メール、2,500購読者まで
  * [SendGrid](https://sendgrid.com/) — 1日100メールと2,000連絡先まで無料
  * [Sendpulse](https://sendpulse.com) — 月500購読者、15,000メールまで無料
  * [SimpleLogin](https://simplelogin.io/) – オープンソース、自己ホスト可能なメールエイリアス/転送ソリューション。5エイリアス、無制限の帯域幅、無制限の返信/送信まで無料。教育スタッフ(学生、研究者など)は無料。
  * [Substack](https://substack.com) — 無制限の無料ニュースレターサービス。課金を開始したときに支払い開始。
  * [Sweego](https://www.sweego.io/) - 開発者向けのヨーロッパのトランザクショナルメールAPI。1日500メールまで無料。
  * [Takeout](https://takeout.bysourfruit.com) - メール送信を簡単にする常に更新されているメールサービス。月500トランザクショナルメールまで無料。
  * [temp-mail.io](https://temp-mail.io) — 複数のメールと転送機能を備えた無料の使い捨て一時メールサービス
  * [tinyletter.com](https://tinyletter.com/) — 月5,000購読者まで無料
  * [Touchlead](https://touchlead.app) - リード管理、フォームビルダー、自動化を備えたマルチパーパスマーケティング自動化ツール。リードと自動化の数に制限あり
  * [trashmail.com](https://www.trashmail.com) - 転送機能とアドレスの自動期限切れ機能を備えた無料の使い捨てメールアドレス
  * [Tuta](https://tuta.com/) - エンドツーエンドの暗号化が組み込まれた無料のセキュアメールアカウントサービスプロバイダー。広告なし、トラッキングなし。1GBストレージ、1カレンダー無料(Tutaには[有料プラン](https://tuta.com/pricing)もあります)。Tutaは部分的に[オープンソース](https://github.com/tutao/tutanota)なので、自己ホスティングも可能。
  * [Verifalia](https://verifalia.com/email-verification-api) — メールボックス確認と使い捨てメールアドレス検出機能を備えたリアルタイムのメール検証API。1日25メール検証まで無料。
  * [verimail.io](https://verimail.io/) — バルクおよびAPIメール検証サービス。月100検証まで無料
  * [Zoho](https://www.zoho.com) — メールプロバイダーとして始まりましたが、現在は無料プランを持つサービスのスイートを提供しています。無料プランを持つサービスのリスト:
     - [Email](https://zoho.com/mail) 5ユーザーまで無料。ユーザーあたり5GB、添付ファイル25MB制限、1ドメイン。
     - [Zoho Assist](https://www.zoho.com/assist) — Zoho Assistの永久無料プランには、1つの同時リモートサポートライセンスと5つの無人コンピューターライセンスへの無制限アクセスが含まれ、プロフェッショナルおよび個人利用が可能。
     - [Sprints](https://zoho.com/sprints) 5ユーザー、5プロジェクト、500MBストレージまで無料。
     - [Docs](https://zoho.com/docs) — 5ユーザーまで無料、1GBアップロード制限、5GBストレージ。Zoho Office Suite(Writer、Sheets、Show)がバンドル。
     - [Projects](https://zoho.com/projects) — 3ユーザー、2プロジェクト、10MB添付ファイル制限まで無料。同じプランが[Bugtracker](https://zoho.com/bugtracker)にも適用。
     - [Connect](https://zoho.com/connect) — 25ユーザーまでのチームコラボレーションが無料。3グループ、3カスタムアプリ、3ボード、3マニュアル、チャンネル、イベント、フォーラムと共に10の統合を含む。
     - [Meeting](https://zoho.com/meeting) — 3参加者のミーティングと10参加者のウェビナーまで。
     - [Vault](https://zoho.com/vault) — パスワード管理は個人向けにアクセス可能。
     - [Showtime](https://zoho.com/showtime) — 最大5参加者のリモートセッショントレーニング用のもう1つのミーティングソフトウェア。
     - [Notebook](https://zoho.com/notebook) — Evernoteの無料代替。
     - [Wiki](https://zoho.com/wiki) — 3ユーザーまで無料。50MBストレージ、無制限ページ、zipバックアップ、RSS＆Atomフィード、アクセス制御、カスタマイズ可能なCSS。
     - [Subscriptions](https://zoho.com/subscriptions) — 20顧客/サブスクリプションと1ユーザーまで無料の定期課金管理。すべての支払いホスティングはZohoが行う。最後の40サブスクリプションメトリクスが保存される
     - [Checkout](https://zoho.com/checkout) — 3ページと50支払いまでの製品課金管理。
     - [Desk](https://zoho.com/desk) — 3エージェント、プライベートナレッジベース、メールチケットを含むカスタマーサポート管理。1リモート技術者と5無人コンピューター用の[Assist](https://zoho.com/assist)と統合。
     - [Cliq](https://zoho.com/cliq) — 100GBストレージ、無制限ユーザー、チャンネルあたり100ユーザー、SSOを備えたチームチャットソフトウェア。
     - [Campaigns](https://zoho.com/campaigns) - メールマーケティング
     - [Forms](https://zoho.com/forms) - フォーム作成
     - [Sign](https://zoho.com/sign) - ペーパーレス署名
     - [Surveys](https://zoho.com/surveys) - オンラインサーベイ
     - [Bookings](https://zoho.com/bookings) - 予約スケジューリング
  * [Maileroo](https://maileroo.com) - 開発者向けのSMTPリレーとメールAPI。月5,000メール、無制限ドメイン、無料メール検証、ブラックリストモニタリング、メールテスターなど。

**[⬆️ トップに戻る](#table-of-contents)**

## フィーチャートグル管理プラットフォーム

  * [ConfigCat](https://configcat.com) - ConfigCatは開発者中心のフィーチャーフラグサービスで、チームサイズ無制限、優れたサポート、リーズナブルな価格が特徴です。無料プランでは10個のフラグ、2つの環境、1つのプロダクト、月500万リクエストまで利用可能です。
  * [Flagsmith](https://flagsmith.com) - 自信を持って機能をリリース。Web、モバイル、サーバーサイドアプリケーション全体でフィーチャーフラグを管理。ホストされたAPIを使用するか、プライベートクラウドにデプロイするか、オンプレミスで実行することができます。
  * [GrowthBook](https://growthbook.io) - ベイズ統計分析エンジンを内蔵したオープンソースのフィーチャーフラグおよびA/Bテストプロバイダー。3ユーザーまで無料で、フィーチャーフラグと実験は無制限。
  * [Hypertune](https://www.hypertune.com) - 型安全なフィーチャーフラグ、A/Bテスト、分析、アプリ設定。Gitスタイルのバージョン管理と同期的なインメモリのローカルフラグ評価を提供。チームメンバー5名まで無料で、フィーチャーフラグとA/Bテストは無制限。
  * [Molasses](https://www.molasses.app) - パワフルなフィーチャーフラグとA/Bテスト。3つの環境まで無料で、各環境5つのフィーチャーフラグまで。
  * [Toggled.dev](https://www.toggled.dev) - エンタープライズ対応でスケーラブルなマルチリージョンのフィーチャートグル管理プラットフォーム。無料プランでは10個のフラグ、2つの環境、リクエスト無制限。SDK、分析ダッシュボード、リリースカレンダー、Slackの通知など、すべての機能が無制限の無料プランに含まれています。
  * [Statsig](https://www.statsig.com) - フィーチャー管理、A/Bテスト、分析などのための堅牢なプラットフォーム。寛大な無料プランでは、シート数、フラグ、実験、動的設定が無制限で、月100万イベントまでサポートしています。
  * [Abby](https://www.tryabby.com) - オープンソースのフィーチャーフラグ＆A/Bテスト。コードとしての設定＆完全な型付けTypescript SDKs。Next.jsやReactなどのフレームワークとの強力な統合。寛大な無料枠と手頃なスケーリングオプション。


**[⬆️ トップに戻る](#table-of-contents)**

## フォント

  * [dafont](https://www.dafont.com/) - このウェブサイトで提供されているフォントは、作者の所有物であり、フリーウェア、シェアウェア、デモバージョン、またはパブリックドメインのいずれかです。
  * [Everything Fonts](https://everythingfonts.com/) - @font-face、単位コンバーター、フォントヒンター、フォント投稿者など、複数のツールを提供。
  * [Font Squirrel](https://www.fontsquirrel.com/) - 商用利用が許可されたフリーウェアフォント。これらの書体を手作業で選別し、使いやすい形式で提供。
  * [Google Fonts](https://fonts.google.com/) - 多くの無料フォントがダウンロードまたはGoogleのCDNへのリンクを通じて、ウェブサイトに簡単かつ迅速にインストール可能。
  * [FontGet](https://www.fontget.com/) - ダウンロード可能な様々なフォントを提供し、タグで整理されています。
  * [Fontshare](https://www.fontshare.com/) - 無料フォントサービス。個人利用および商用利用が100%無料のプロフェッショナルグレードフォントのコレクションを拡大中。
  * [Befonts](https://befonts.com/) - 個人用または商用利用のためのユニークなフォントを提供。
  * [Font of web](https://fontofweb.com/) - ウェブサイトで使用されているすべてのフォントとその使用方法を特定。
  * [Bunny](https://fonts.bunny.net) - プライバシー重視のGoogle Fonts
  * [FontsKey](https://www.fontskey.com/) - 個人使用向けの無料および商用有料フォントを提供し、テキストを入力して素早くフィルタリングが可能。
  * [fonts.xz.style](https://fonts.xz.style/) - CSSを使用してウェブサイトにフォントファミリーを配信する無料でオープンソースのサービス。
  * [Fontsensei](https://fontsensei.com/) - ユーザーによってタグ付けされたオープンソースのGoogleフォント。CJK（中国語、日本語、韓国語）フォントタグ付き。

**[⬆️ トップに戻る](#table-of-contents)**

## フォーム

  * [Feathery](https://feathery.io) - パワフルで開発者フレンドリーなフォームビルダー。サインアップ＆ログイン、ユーザーオンボーディング、支払いフロー、複雑な金融アプリケーションなどを構築可能。無料プランでは月250件の送信と5つのアクティブフォームまで。
  * [Form-Data](https://form-data.com) - ノーコードフォームバックエンド。スパムフィルター、メール通知と自動応答、webhooks、zapier、リダイレクト、AJAXまたはPOSTなど。無料プランでは無制限のフォーム、月20件の送信、Form-Dataバッジ付きで追加2000件の送信が可能。
  * [FabForm](https://fabform.io/) - インテリジェントな開発者向けフォームバックエンドプラットフォーム。無料プランでは月250件のフォーム送信が可能。フレンドリーでモダンなGUI。Google Sheets、Airtable、Slack、メール、その他との統合。
  * [Form.taxi](https://form.taxi/) - HTMLフォーム送信のエンドポイント。通知、スパムブロッカー、GDPRに準拠したデータ処理付き。基本的な使用は無料プラン。
  * [Formcarry.com](https://formcarry.com) - HTTP POSTフォームエンドポイント、無料プランでは月100件の送信が可能。
  * [formingo.co](https://www.formingo.co/)- 静的ウェブサイト用の簡単なHTMLフォーム。アカウント登録なしで無料で始められます。無料プランでは月500件の送信とカスタマイズ可能な返信先メールアドレスが可能。
  * [FormKeep.com](https://www.formkeep.com/) - 月50件の送信、スパム保護、メール通知、HTMLをエクスポート可能なドラッグ＆ドロップデザイナーを備えた無制限のフォーム。追加機能にはカスタムフィールドルール、チーム、Google Sheets、Slack、ActiveCampaign、Zapierとの統合が含まれます。
  * [formlets.com](https://formlets.com/) - オンラインフォーム、月無制限のシングルページフォーム、月100件の送信、メール通知。
  * [formspark.io](https://formspark.io/) - フォームからメールへのサービス、無料プランでは無制限のフォーム、月250件の送信、カスタマーアシスタンスチームによるサポート。
  * [Formspree.io](https://formspree.io/) - HTTP POSTリクエストを使用してメールを送信。無料枠はフォームごとに月50件の送信まで。
  * [Formsubmit.co](https://formsubmit.co/) - HTMLフォーム用の簡単なエンドポイント。永久無料。登録不要。
  * [Formlick.com](https://formlick.com) - ライフタイムディール付きのTypeform代替。ユーザーは1つの無料フォームを作成し、無制限の送信を受け取ることができます。プレミアムでは、無制限のフォームと無制限の送信が可能。
  * [getform.io](https://getform.io/) - デザイナーと開発者向けのフォームバックエンドプラットフォーム、1フォーム、50件の送信、シングルファイルアップロード、100MBのファイルストレージ。
  * [HeroTofu.com](https://herotofu.com/) - ボット検出と暗号化アーカイブを備えたフォームバックエンド。UIを通じてメール、Slack、またはZapierに送信を転送。独自のフロントエンドを使用。サーバーコード不要。無料プランでは無制限のフォームと月100件の送信が可能。
  * [HeyForm.net](https://heyform.net/) - ドラッグ＆ドロップオンラインフォームビルダー。無料枠では無制限のフォームと無制限の送信が可能。事前構築されたテンプレート、アンチスパム、100MBのファイルストレージ付き。
  * [Tally.so](https://tally.so/) - すべての機能の99%が無料。無料枠では：無制限のフォーム、無制限の送信、メール通知、フォームロジック、支払い収集、ファイルアップロード、カスタムサンクスページなど多数の機能が利用可能。
  * [Hyperforms.app](https://hyperforms.app/) - バックエンドコードなしで数秒でメールなどのフォームを作成。個人アカウントでは月50件のフォーム送信まで無料。
  * [Kwes.io](https://kwes.io/) - 機能豊富なフォームエンドポイント。静的サイトで優れた働きをします。無料プランには月50件の送信まで1つのウェブサイトが含まれます。
  * [Pageclip](https://pageclip.co/) - 無料プランでは1サイト、1フォーム、月1,000件の送信が可能。
  * [Qualtrics Survey](https://qualtrics.com/free-account) - このファーストクラスツールを使用してプロフェッショナルなフォーム＆調査を作成。50以上の専門家が設計した調査テンプレート。無料アカウントでは1つのアクティブな調査、調査あたり100件の回答＆8種類の回答タイプに制限。
  * [Screeb](https://screeb.app/) - アプリ内調査とユーザー行動を解読するための製品分析。永久無料プランでは月500アクティブユーザー、無制限の回答とイベント、多数の統合、エクスポート、定期レポートが可能。
  * [smartforms.dev](https://smartforms.dev/) - ウェブサイト用のパワフルで簡単なフォームバックエンド、永久無料プランでは月50件の送信、250MBのファイルストレージ、Zapier統合、CSV/JSONエクスポート、カスタムリダイレクト、カスタムレスポンスページ、Telegram＆Slackボット、シングルメール通知が可能。
  * [Survicate](https://survicate.com/) - すべてのソースからフィードバックを収集し、1つのツールでフォローアップ調査を送信。AIを使用してフィードバックを自動分析し、洞察を抽出。無料のメール、ウェブサイト、製品内またはモバイル調査、AI調査作成者、月25件の回答。
  * [staticforms.xyz](https://www.staticforms.xyz/) - サーバーサイドコードなしで簡単にHTMLフォームを統合。無料。ユーザーがフォームを送信すると、フォームの内容を含むメールが登録されたアドレスに送信されます。
  * [stepFORM.io](https://stepform.io) - クイズとフォームビルダー。無料プランでは5つのフォーム、フォームあたり最大3ステップ、月50件の回答が可能。
  * [Typeform.com](https://www.typeform.com/) - ウェブサイトに美しくデザインされたフォームを含めることができます。無料プランではフォームあたり10フィールドと月100件の回答に制限。
  * [WaiverStevie.com](https://waiverstevie.com) - REST APIを備えた電子署名プラットフォーム。webhooksで通知を受け取ることができます。無料プランでは署名済み文書にウォーターマークが付きますが、無制限の封筒＋署名が可能。
  * [Web3Forms](https://web3forms.com) - バックエンドコードを書かずに静的＆JAMStackウェブサイト用のコンタクトフォーム。無料プランでは無制限のフォーム、無制限のドメイン＆月250件の送信が可能。
  * [WebAsk](https://webask.io) - 調査とフォームビルダー。無料プランではアカウントあたり3つの調査、月100件の回答、調査あたり10要素が可能。
  * [Wufoo](https://www.wufoo.com/) - ウェブサイトで使用する簡単なフォーム。無料プランでは月100件の送信に制限。
  * [formpost.app](https://formpost.app) - 無料、無制限のフォームからメールへのサービス。カスタムリダイレクト、自動応答、webhooksなどを無料で設定可能。
  * [Formester.com](https://formester.com) - ユニークな外観のフォームをウェブサイトで共有および埋め込み - フォーム数や機能に制限なし。無料で月100件の送信が可能。
  * [SimplePDF.eu](https://simplepdf.eu/embed) - PDFエディターをウェブサイトに埋め込み、任意のPDFを入力可能なフォームに変換。無料プランでは無制限のPDFとPDFあたり3件の送信が可能。
  * [forms.app](https://forms.app/) - 条件付きロジック、自動スコア計算機、AIなどのパワフルな機能を備えたオンラインフォームを作成。無料プランでは月100件の回答を収集可能、フォームをウェブサイトに埋め込むか、リンクで使用可能。
  * [Qualli](https://usequalli.com) - モバイル向けに設計されたアプリ内調査。Qualli AIを使用して完璧な質問を作成。無料プランで試すことができ、500 MAUまで、無制限のフォームとトリガーを作成可能。
  * [Sprig](https://sprig.com/) - 月1回の製品内調査またはリプレイ付き調査、GPT搭載のAI分析付き。
  * [feedback.fish](https://feedback.fish/) - 無料プランでは合計25件のフィードバック送信を収集可能。ReactとVueコンポーネントが提供され、簡単に統合可能。
  * [Vidhook](https://vidhook.io/) - 高い回答率を持つ魅力的な調査でフィードバックを収集。無料プランには1つのアクティブな調査、調査あたり25件の回答、カスタマイズ可能なテンプレートが含まれます。

**[⬆️ トップに戻る](#table-of-contents)**

## 生成AI

  * [Keywords AI](https://keywordsai.co) - 最高のLLMモニタリングプラットフォーム。2行のコードで200以上のLLMを呼び出せる統一フォーマット。毎月10,000リクエストまで無料で、プラットフォーム機能は$0!
  * [Portkey](https://portkey.ai/) - 監視スイートとAIゲートウェイを備えたGen AIアプリのコントロールパネル。毎月最大10,000リクエストまで無料で送信・ログ記録可能。
  * [Braintrust](https://www.braintrustdata.com/) - Gen AI用の評価、プロンプトプレイグラウンド、データ管理。無料プランでは週1,000件のプライベート評価行が可能。
  * [Findr](https://www.usefindr.com/) - すべてのアプリを一度に検索できるユニバーサル検索。情報を使って質問に答えられる検索アシスタント。無料プランでは無制限の統合検索と1日5回のコパイロットクエリが可能。
  * [ReportGPT](https://ReportGPT.app) - AI搭載の文章作成アシスタント。独自のAPIキーを使用する限り、プラットフォーム全体が無料。
  * [Clair](https://askclair.ai/) - 臨床AIリファレンス。学生は、オープンサーチ、臨床サマリー、薬剤レビュー、薬物相互作用、ICD-10コード、スチュワードシップを含むプロフェッショナルツールスイートに無料でアクセス可能。また、プロフェッショナルスイートの無料トライアルも利用可能。
  * [Langtrace](https://langtrace.ai) - 開発者がLLMアプリケーションのパフォーマンスに関連するトレース、評価、プロンプトとデータセットの管理、問題のデバッグを可能にします。任意のLLM用のオープンテレメトリ標準トレースを作成し、可観測性を支援し、任意の可観測性クライアントと連携します。無料プランでは月50Kトレースが提供されます。
  * [LangWatch](https://langwatch.ai) - AIチームがLLMアプリケーションの信頼性、コスト効率、パフォーマンスを測定、監視、最適化するのを支援するLLMOpsプラットフォーム。強力なDSPyコンポーネントにより、エンジニアと非技術チームが協力してGenAI製品を微調整し本番環境に移行できます。無料プランにはすべてのプラットフォーム機能、月1kトレース、1つのワークフローDSPyオプティマイザーが含まれます。[#オープンソース](https://github.com/langwatch/langwatch)
  * [Ultra AI](https://ultraai.app) - 製品用のAIコマンドセンター。マルチプロバイダーAIゲートウェイ、プロンプトマネージャー、キャッシング、ログ、分析、モデルフォールバック、ユーザーレート制限などの機能を提供。無料永久プランでは月10k以上のリクエストとキャッシング以外のすべての機能を提供。
  * [Comet Opik](https://www.comet.com/site/products/opik/) - 開発環境と本番環境のライフサイクル全体でLLMアプリケーションを評価、テスト、デプロイ。[#オープンソース](https://github.com/comet-ml/opik/)
  * [Langfuse](https://langfuse.com/) - チームがLLMアプリケーションを協力してデバッグ、分析、反復できるようにするオープンソースLLMエンジニアリングプラットフォーム。無料永久プランには月50k観測とすべてのプラットフォーム機能が含まれます。[#オープンソース](https://github.com/langfuse/langfuse)
  * [Pollinations.AI](https://pollinations.ai/) - 使いやすい無料の画像生成AIで、無料APIも利用可能。サインアップやAPIキーは不要で、ウェブサイトやワークフローへの統合オプションも複数あります。[#オープンソース](https://github.com/pollinations/pollinations)
  * [Othor AI](https://othor.ai/) - Tableau、Power BI、Lookerなどの一般的なビジネスインテリジェンスソリューションに代わるAIネイティブな高速、シンプル、安全な選択肢。OthorはLLMを活用して、数分でカスタムビジネスインテリジェンスソリューションを提供します。無料永久プランでは、1ユーザーに対して5つのデータソース接続を持つ1つのワークスペースを提供し、分析に制限はありません。[#オープンソース](https://github.com/othorai/othor.ai)
  * [OpenRouter](https://openrouter.ai/models?q=free) - DeepSeek R1、V3、Llama、Moonshot AIなど、様々な無料AIモデルを提供。これらのモデルは自然言語処理に優れており、多様な開発ニーズに適しています。これらのモデルは無料で使用できますが、レート制限があることに注意してください。さらに、OpenRouterはより高度な要件向けに、Claude、OpenAI、Grok、Gemini、Novaなどの有料モデルも提供しています。

**[⬆️ トップに戻る](#table-of-contents)**

## CDNと保護

  * [bootstrapcdn.com](https://www.bootstrapcdn.com/) - bootstrap、bootswatchとfontawesome.io用のCDN
  * [cdnjs.com](https://cdnjs.com/) - シンプル。高速。信頼性。最高のコンテンツ配信。cdnjsはCloudflareが提供する、全ウェブサイトの11%以上に信頼される無料でオープンソースのCDNサービス。
  * [developers.google.com](https://developers.google.com/speed/libraries/) - Google Hosted Librariesは、最も人気のあるオープンソースJavaScriptライブラリ用のコンテンツ配信ネットワーク
  * [Stellate](https://stellate.co/) - Stellateは、GraphQL API用の超高速で信頼性の高いCDNで、2つのサービスまで無料。
  * [jsdelivr.com](https://www.jsdelivr.com/) - 無料、高速、信頼性の高いオープンソースCDN。npm、GitHub、WordPress、Denoなどをサポート。
  * [Microsoft Ajax](https://docs.microsoft.com/en-us/aspnet/ajax/cdn/overview) - Microsoft Ajax CDNはjQueryなどの人気のあるサードパーティJavaScriptライブラリをホストし、Webアプリケーションに簡単に追加できます
  * [ovh.ie](https://www.ovh.ie/ssl-gateway/) - 無料のDDoS保護とSSL証明書
  * [Skypack](https://www.skypack.dev/) - 100%ネイティブESモジュールJavaScript CDN。ドメインあたり月100万リクエストまで無料。
  * [raw.githack.com](https://raw.githack.com/) - Cloudflareを使用してファイルを単純にホストする**rawgit.com**の最新の代替
  * [section.io](https://www.section.io/) - Varnish Cacheソリューションを簡単に立ち上げて管理する方法。1サイトは永久に無料とされています
  * [statically.io](https://statically.io/) - Git repos（GitHub、GitLab、Bitbucket）、WordPress関連アセット、画像用のCDN
  * [toranproxy.com](https://toranproxy.com/) - PackagistとGitHub用のプロキシ。CDを失敗させません。個人使用、1開発者は無料、サポートなし
  * [UNPKG](https://unpkg.com/) - npm上のすべてのもの用のCDN
  * [weserv](https://images.weserv.nl/) - 画像キャッシュ＆リサイズサービス。世界規模のキャッシュで画像をその場で操作。
  * [Namecheap Supersonic](https://www.namecheap.com/supersonic-cdn/#free-plan) - 無料のDDoS保護
  * [Gcore](https://gcorelabs.com/) - グローバルコンテンツ配信ネットワーク、毎月1 TBと100万リクエストまで無料、DNSホスティングも無料
  * [CacheFly](https://portal.cachefly.com/signup/free2023) - 月最大5 TBの無料CDNトラフィック、19のコアPoP、1ドメインとユニバーサルSSL。

**[⬆️ トップに戻る](#table-of-contents)**

## PaaS

  * [anvil.works](https://anvil.works) - Pythonだけでウェブアプリ開発。無制限のアププリと30秒のタイムアウトを含む無料枠。
  * [appwrite](https://appwrite.io) - プロジェクトの一時停止なしで無制限のプロジェクト（WebSocketをサポート）と認証サービス。無料枠では1プロジェクトあたり1データベース、3バケット、5関数。
  * [configure.it](https://www.configure.it/) - モバイルアプリ開発プラットフォーム、2プロジェクトまで無料、機能は制限されていますがリソース制限なし
  * [codenameone.com](https://www.codenameone.com/) - Java/Kotlin開発者向けのオープンソース、クロスプラットフォーム、モバイルアプリ開発ツールチェーン。商用利用は無制限のプロジェクトで無料
  * [deco.cx](https://www.deco.cx/en/dev) - TypeScriptコードから自動生成されたビジュアルCMSを備えたエッジネイティブフロントエンドプラットフォーム。A/Bテスト、コンテンツセグメンテーション、リアルタイム分析が組み込まれています。コンテンツが豊富なエンタープライズeコマースウェブサイトに最適。月5kページビューまたはオープンソース/個人プロジェクトは無料。
  * [Deno Deploy](https://deno.com/deploy) - JavaScript、TypeScript、WebAssemblyをエッジで世界中で実行する分散システム。無料枠には1日100,000リクエストと月100 GiBのデータ転送が含まれます。
  * [domcloud.co](https://domcloud.co) - GitHubでのCI/CD、SSH、MariaDB/Postgresデータベースを提供するLinuxホスティングサービス。無料バージョンには1 GBのストレージと月1 GBのネットワーク制限があり、無料ドメインに制限されています。
  * [encore.dev](https://encore.dev/) - 静的分析を使用して自動インフラストラクチャ、ボイラープレートフリーコードなどを提供するバックエンドフレームワーク。趣味プロジェクト用の無料クラウドホスティングを含みます。
  * [flightcontrol.dev](https://flightcontrol.dev/) - Gitプッシュスタイルのワークフローで、ウェブサービス、データベースなどを独自のAWSアカウントにデプロイ。個人のGitHubリポジトリで1開発者のユーザーに無料枠。AWSコストはAWSを通じて請求されますが、クレジットとAWS無料枠を使用できます。
  * [gigalixir.com](https://gigalixir.com/) - GigalixirはElixir/Phoenixアプリ用に、スリープしない1つの無料インスタンスと、2接続、10,000行に制限され、バックアップのない無料枠PostgreSQLデータベースを提供します。
  * [Glitch](https://glitch.com/) - コード共有とリアルタイムコラボレーション機能を備えた無料のパブリックホスティング。無料プランには月1000時間の制限があります。
  * [Lade](https://www.lade.io/) - Ladeはデベロッパーのためのクラウドプラットフォームです。無料枠には3つのサービスが含まれ、アプリまたはデータベースのいずれかを選択できます。各サービスには128 MB RAMと1 GBストレージが含まれます。
  * [leapcell](https://leapcell.io/) - Leapcellは信頼性の高い分散アプリケーションプラットフォームで、急速な成長をシームレスにサポートするために必要なすべてを提供します。無料プランには10万回のサービス呼び出し、1万回の非同期タスク、10万回のRedisコマンドが含まれます。
  * [pipedream.com](https://pipedream.com) - 開発者向けの統合プラットフォーム。任意のトリガーに基づく任意のワークフローを開発。ワークフローは[無料で](https://docs.pipedream.com/pricing/)実行できるコードです。管理するサーバーやクラウドリソースはありません。
  * [pythonanywhere.com](https://www.pythonanywhere.com/) - クラウドPythonアプリホスティング。ビギナーアカウントは無料で、your-username.pythonanywhere.comドメインで1つのPythonウェブアプリケーション、512 MBのプライベートファイルストレージ、1つのMySQLデータベースを提供
  * [ampt.dev](https://getampt.com/) - AmptはチームがAWS上でJavaScriptアプリを構築、デプロイ、スケーリングすることを、複雑な設定やインフラストラクチャ管理なしで可能にします。無料プレビュープランには時間あたり500回の呼び出し、1日2,500回の呼び出し、月50,000回の呼び出しが含まれます。カスタムドメインは有料プランでのみ許可されています。
  * [Koyeb](https://www.koyeb.com) - Koyebは、アプリをグローバルにデプロイするための開発者フレンドリーなサーバーレスプラットフォームです。Gitベースのデプロイメント、ネイティブオートスケーリング、グローバルエッジネットワーク、組み込みのサービスメッシュとディスカバリーを使用して、Dockerコンテナ、ウェブアプリ、APIをシームレスに実行します。無料インスタンスでは、フランクフルト（ドイツ）またはワシントンD.C.（米国）でウェブサービスをデプロイできます。無料のマネージドPostgresデータベースはフランクフルト（ドイツ）、ワシントンD.C.（米国）、シンガポールで利用可能です。512MBメモリ、2GBストレージ、0.1 CPU。開始にクレジットカードは必要ありません。
  * [Napkin](https://www.napkin.io/) - 500Mbのメモリ、デフォルトタイムアウト15秒、月5,000回の無料API呼び出し（5呼び出し/秒にレート制限）のFaaS。
  * [Meteor Cloud](https://www.meteor.com/cloud) - Galaxyホスティング。Meteorのプラットフォームとしてのサービスには、無料のMongoDB共有ホスティングと自動SSLが含まれます。
  * [Northflank](https://northflank.com) - パワフルなUI、API＆CLIでマイクロサービス、ジョブ、マネージドデータベースを構築・デプロイ。バージョン管理と外部Dockerレジストリからコンテナをシームレスにスケール。無料枠には2つのサービス、2つのcronジョブ、1つのデータベースが含まれます。
  * [YepCode](https://yepcode.io) - サーバーレス環境でAPIとサービスを接続するオールインワンプラットフォーム。NoCodeツールのすべての俊敏性と利点を、プログラミング言語を使用するすべてのパワーとともに提供します。無料枠には[1,000 yeps](https://yepcode.io/pricing/)が含まれます。
  * [WunderGraph](https://cloud.wundergraph.com) - 最新のAPIを迅速に構築、出荷、管理できるオープンソースプラットフォーム。組み込みのCI/CD、GitHub統合、自動HTTPS。[無料プラン](https://wundergraph.com/pricing)では3プロジェクト、1GBの送信、月300分のビルド時間。
  * [Zeabur](https://zeabur.com) - ワンクリックでサービスをデプロイ。3つのサービスまで無料で、月US$ 5の無料クレジット付き。
  * [mogenius](https://mogenius.com) - 簡単にKubernetes上でサービスを構築、デプロイ、実行。無料枠では、個々の開発者がマシン上に本番環境に似たテスト環境を作成できるように、ローカルKubernetesとmogeniusの接続をサポート。
  * [genezio](https://genezio.com/) - サーバーレス関数プロバイダーで、非商用または学術利用に限り、月100万回の関数呼び出し、100GBの帯域幅、10のcronジョブを無料で提供。

**[⬆️ トップに戻る](#table-of-contents)**

## BaaS

  * [Activepieces](https://www.activepieces.com) - アプリのバックエンドで複数のアプリを接続する自動化フローを構築。例えば、アプリでイベントが発生した時にSlackメッセージを送信したり、Google Sheetに行を追加したりできます。月5,000タスクまで無料。
  * [back4app.com](https://www.back4app.com) - Back4AppはParse Platformをベースにした使いやすく、柔軟でスケーラブルなバックエンドです。
  * [backendless.com](https://backendless.com/) — モバイルおよびWebのBaaS。1GBのファイルストレージ、月50,000のプッシュ通知、テーブルに1000のデータオブジェクトまで無料。
  * [bismuth.cloud](https://www.bismuth.cloud/) — AIが関数ランタイムとホストされたストレージ上でPython APIをブートストラップし、オンラインエディタまたはお気に入りのツールでローカルに無料でビルドとホストを行います。
  * [BMC Developer Program](https://developers.bmc.com/site/global/bmc_helix_platform/program/overview/index.gsp) — BMC Developer Programはデジタルイノベーションを構築・デプロイするためのドキュメントとリソースを提供。プラットフォーム、SDK、アプリのビルドとカスタマイズに使用できるコンポーネントライブラリを含む包括的な個人用サンドボックスにアクセス可能。
  * [connectycube.com](https://connectycube.com) - 無制限のチャットメッセージ、P2Pの音声・ビデオ通話、ファイル添付、プッシュ通知。1000ユーザーまでのアプリは無料。
  * [convex.dev](https://convex.dev/) - リアクティブなバックエンドサービス。データ（リレーションシップとシリアライズ可能なACIDトランザクションを持つドキュメント）、サーバーレス関数、更新をさまざまなクライアントにストリーミングするWebSocketをホスティング。小規模プロジェクトは無料 - 100万レコード、月500万関数呼び出しまで。
  * [darklang.com](https://darklang.com/) - エディタとインフラストラクチャを組み合わせたホステッド言語。ベータ期間中はアクセス可能で、ベータ後は寛大な無料枠を予定。
  * [Firebase](https://firebase.com) — Firebaseはアプリの構築と運用を支援。無料のSparkプランには認証、ホスティング、Firebase ML、Realtime Database、Cloud Storage、Testlabが含まれます。A/Bテスト、Analytics、App Distribution、App Indexing、Cloud Messaging (FCM)、Crashlytics、Dynamic Links、In-App Messaging、Performance Monitoring、Predictions、Remote Configは常に無料。
  * [Flutter Flow](https://flutterflow.io) — コードを1行も書かずにFlutter AppのUIを構築。Firebaseとの統合も。無料プランにはUIビルダーと無料テンプレートへの完全アクセスが含まれます。
  * [getstream.io](https://getstream.io/) — 数週間ではなく数時間でスケーラブルなアプリ内チャット、メッセージング、ビデオ・音声、フィードを構築
  * [hasura.io](https://hasura.io/) — Hasuraは既存のデータベースをホストされている場所で拡張し、Web、モバイル、データ統合ワークロード用に安全にアクセスできる即時のGraphQL APIを提供。月1GBのデータパススルーまで無料。
  * [iron.io](https://www.iron.io/) — AWS Lambda類似の非同期タスク処理。無料枠と1ヶ月の無料トライアル付き
  * [nhost.io](https://nhost.io) - Webおよびモバイルアプリのためのサーバーレスバックエンド。無料プランにはPostgreSQL、GraphQL (Hasura)、認証、ストレージ、サーバーレス関数が含まれます。
  * [onesignal.com](https://onesignal.com/) — 無制限の無料プッシュ通知。無制限の連絡先とAuto Warm Upアクセス付きで月10,000メール送信。
  * [paraio.com](https://paraio.com) — 柔軟な認証、全文検索、キャッシングを備えたバックエンドサービスAPI。1つのアプリ、1GBのアプリデータまで無料。
  * [progress.com](https://www.progress.com/kinvey) — モバイルバックエンド。スタータープランは無制限のリクエスト/秒、1GBのデータストレージ付き。エンタープライズアプリケーションサポート付き
  * [pubnub.com](https://www.pubnub.com/) — 月100万メッセージと100アクティブデバイル/日まで無料のプッシュ通知
  * [pushbots.com](https://pushbots.com/) — プッシュ通知サービス。月150万プッシュまで無料
  * [pushcrew.com](https://pushcrew.com/) — プッシュ通知サービス。2,000購読者まで無制限の通知
  * [pusher.com](https://pusher.com/beams) — 2000月間アクティブユーザーまで無料、無制限のプッシュ通知。iOSとAndroidデバイス用の単一API。
  * [quickblox.com](https://quickblox.com/) — インスタントメッセージング、ビデオ・音声通話、プッシュ通知用のコミュニケーションバックエンド
  * [restspace.io](https://restspace.io/) — 認証、データ、ファイル、メールAPI、テンプレートなどのサービスでサーバーを構成し、パイプラインに組み合わせてデータを変換。
  * [Salesforce Developer Program](https://developer.salesforce.com/signup) — ドラッグ＆ドロップツールでLightningアプリを高速に構築。クリックでデータモデルをカスタマイズ。Apexコードでさらに拡張。強力なAPIで何とでも統合。エンタープライズグレードのセキュリティで保護。クリックまたは最新のWebフレームワークでUIをカスタマイズ。無料Developer Programで完全なLightning Platformにアクセス可能。
  * [ServiceNow Developer Program](https://developer.servicenow.com/) — 組織の業務をより良くするアプリケーションを迅速に構築、テスト、デプロイ。無料インスタンスとプレビュー版への早期アクセス。
  * [simperium.com](https://simperium.com/) — データをどこでも即座に自動的に移動。マルチプラットフォーム、構造化データの無制限送信と保存、月2,500ユーザーまで
  * [Singlebase.cloud](https://singlebase.cloud) — SinglebaseCloudはアプリ開発を加速するAI駆動のオールインワンバックエンドプラットフォーム。Vector DB、Relational Document DB、Auth、Search、Storageなどのツールを提供し、バックエンド開発を簡素化することを目指しています。無料/スタータープランではRelational Document DB、Auth、Search、Storageを提供。
  * [stackstorm.com](https://stackstorm.com/) — アプリ、サービス、ワークフロー用のイベント駆動型自動化。フロー、アクセス制御、LDAPなしで無料
  * [streamdata.io](https://streamdata.io/) — 任意のREST APIをイベント駆動型ストリーミングAPIに変換。無料プランは100万メッセージと10の同時接続まで。
  * [Supabase](https://supabase.com) — オープンソースのFirebase代替バックエンド構築。無料プランには認証、リアルタイムデータベース、オブジェクトストレージが含まれます。
  * [tyk.io](https://tyk.io/) — 認証、クォータ、モニタリング、分析付きのAPI管理。無料クラウドオファリング
  * [zapier.com](https://zapier.com/) — アプリを接続してタスクを自動化。15分ごとに5つのzapと月100タスクまで無料
  * [IFTTT](https://ifttt.com) — お気に入りのアプリとデバイスを自動化。2つのAppletまで無料
  * [Integrately](https://integrately.com) — ワンクリックで面倒なタスクを自動化。100タスク、15分更新時間、5つのアクティブな自動化、Webhookまで無料。
  * [LeanCloud](https://leancloud.app/) — モバイルバックエンド。1GBのデータストレージ、256MBインスタンス、日3,000 APIリクエスト、日10,000プッシュまで無料。（APIはParse Platformと非常に似ています）

**[⬆️ 目次に戻る](#table-of-contents)**

## ドメイン

  * [pp.ua](https://nic.ua/) — 無料pp.uaサブドメイン。
  * [us.kg](https://nic.us.kg/) - 無料us.kgサブドメイン。

**[⬆️ 目次に戻る](#table-of-contents)**

## IaaS

  * [4EVERLAND](https://www.4everland.org/) — AWS S3互換 - API、インターフェース操作、CLI、その他のアップロード方法、IPFSとArweaveネットワークからのファイルを安全、便利、効率的にアップロードおよび保存。登録ユーザーは6 GBのIPFSストレージと300MBのArweaveストレージを無料で取得可能。150 KB未満のArweaveファイルのアップロードは無料。
  * [backblaze.com](https://www.backblaze.com/b2/) — Backblaze B2クラウドストレージ。無制限期間で10 GB（Amazon S3類似）のオブジェクトストレージが無料
  * [filebase.com](https://filebase.com/) - ブロックチェーンを活用したS3互換オブジェクトストレージ。無制限期間で5 GBの無料ストレージ。
  * [Tebi](https://tebi.io/) - S3互換オブジェクトストレージ。25 GBの無料ストレージと250GBのアウトバウンド転送。
  * [Idrive e2](https://www.idrive.com/e2/) - S3互換オブジェクトストレージ。10 GBの無料ストレージと月間10 GBのダウンロード帯域幅。
  * [C2 Object Storage](https://c2.synology.com/en-us/pricing/object-storage) - S3互換オブジェクトストレージ。15 GBの無料ストレージと月間15 GBのダウンロード。

**[⬆️ 目次に戻る](#table-of-contents)**

## マネージドデータサービス

  * [Aiven](https://aiven.io/) - Aivenはオープンソースデータプラットフォーム上で、PostgreSQL、MySQLおよびRedisの無料プランを提供しています。シングルノード、1 CPU、1GB RAM、PostgreSQLとMySQLの場合は5GBストレージ。より大規模なプランやクラウド間の簡単な移行が可能です。
  * [airtable.com](https://airtable.com/) — スプレッドシートのように見えますが、リレーショナルデータベースです。無制限のベース、ベースあたり1,200行、月間1,000 APIリクエストまで無料
  * [Astra](https://www.datastax.com/products/datastax-astra/) — [80GB無料枠](https://www.datastax.com/products/datastax-astra/pricing)のクラウドネイティブCassandraサービス
  * [codehooks.io](https://codehooks.io/) — JavaScript用の使いやすいサーバーレスAPI/バックエンドとNoSQLデータベースサービス。関数、MongoDB風のクエリ、キー/値検索、ジョブシステム、リアルタイムメッセージ、ワーカーキュー、強力なCLI、Webベースのデータマネージャーを提供。無料プランでは5GBストレージと毎分60回のAPI呼び出し。2人の開発者まで。クレジットカード不要。
  * [CrateDB](https://crate.io/) - リアルタイム分析用の分散オープンソースSQLデータベース。[無料プランCRFREE](https://crate.io/lp-crfree): 2 CPU、2 GiBメモリ、8 GiBストレージの1ノード。組織あたり1クラスター、支払い方法不要。
  * [Upstash](https://upstash.com/) — サーバーレスRedis。1日10,000リクエストまで、最大データベースサイズ256MB、20同時接続まで無料
  * [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) — 無料枠で512 MB提供
  * [redsmin.com](https://www.redsmin.com/) — Redisのオンラインリアルタイムモニタリングと管理サービス。1つのRedisインスタンスのモニタリングが無料
  * [redislabs](https://redislabs.com/try-free/) - 30MBのRedisインスタンスを無料提供
  * [MemCachier](https://www.memcachier.com/) — マネージドMemcacheサービス。25MBまで、1プロキシサーバー、基本的な分析機能が無料
  * [scalingo.com](https://scalingo.com/) — 主にPaaSですが、MySQL、PostgreSQL、またはMongoDBの128MBから192MBの無料枠を提供
  * [SeaTable](https://seatable.io/) — Seafileチームが開発した柔軟なスプレッドシート型データベース。無制限のテーブル、2,000行、1ヶ月のバージョン管理、最大25チームメンバーまで。
  * [skyvia.com](https://skyvia.com/) — クラウドデータプラットフォームが無料枠を提供。ベータ期間中はすべてのプランが完全無料
  * [StackBy](https://stackby.com/) — スプレッドシートの柔軟性、データベースのパワー、お気に入りのビジネスアプリとの組み込み統合を1つのツールで実現。無料プランには無制限のユーザー、10スタック、スタックあたり2GBの添付ファイルが含まれます。
  * [TiDB Cloud](https://en.pingcap.com/tidb-cloud/) — TiDBはオープンソースのMySQL互換分散HTAPデータベースです。TiDBサーバーレスは毎月5GBの行ストレージ、5GBの列ストレージ、5000万リクエストユニット(RU)を無料で提供します。
  * [Turso by ChiselStrike](https://chiselstrike.com/) - TursoはエッジデータベースにおけるSQLite開発者体験を提供します。Tursoは永久無料のスタータープランを提供し、合計9GBのストレージ、最大500データベース、最大3ロケーション、月間10億行の読み取り、SQLiteによるローカル開発サポートを含みます。
  * [InfluxDB](https://www.influxdata.com/) — 時系列データベース。5分あたり3MBの書き込み、5分あたり30MBの読み取り、10,000のカーディナリティシリーズまで無料
  * [restdb.io](https://restdb.io/) - 高速でシンプルなNoSQLクラウドデータベースサービス。スキーマ、リレーション、自動REST API（MongoDB風のクエリ対応）、データ操作用の効率的なマルチユーザー管理UIを提供。無料プランでは3ユーザー、2500レコード、毎秒1 APIリクエストまで。
  * [cockroachlabs.com](https://www.cockroachlabs.com/free-tier/) — 5GBと1vCPUまでのCockroachDBが無料（[リクエストユニット](https://www.cockroachlabs.com/docs/cockroachcloud/serverless-faqs.html#what-are-the-usage-limits-of-cockroachdb-serverless-beta)に制限あり）
  * [Neo4j Aura](https://neo4j.com/cloud/aura/) — Cypherクエリ言語とREST APIを備えたマネージドネイティブグラフDBMS/分析プラットフォーム。グラフサイズに制限あり（ノード50k、リレーションシップ175k）。
  * [Neon](https://neon.tech/) — マネージドPostgreSQL。0.5GBのストレージ（合計）、1プロジェクト、10ブランチ、無制限のデータベース、常時利用可能なプライマリブランチ（5分後に自動停止）、非プライマリブランチの計算時間が月20時間まで。
  * [Dgraph Cloud](https://cloud.dgraph.io/pricing?type=free) — GraphQL APIを備えたマネージドネイティブグラフDBMS。1日のデータ転送が1MBまでに制限。
  * [Tinybird](https://tinybird.co) - コネクションレスのHTTPデータ取り込みとSQLクエリをマネージドHTTP APIとして公開できるサーバーレスマネージドClickHouse。無料枠に時間制限はなく、10GBのストレージと1日1000 APIリクエストまで。
  * [TigerGraph Cloud](https://www.tigergraph.com/cloud/) — SQL風のグラフクエリ言語とREST APIを備えたマネージドネイティブグラフDBMS/分析プラットフォーム。2vCPU、8GBメモリ、50GBストレージの無料インスタンスを1つ提供（1時間の非アクティブ後にスリープ）。
  * [TerminusCMS](https://terminusdb.com/pricing) — PrologとRustで書かれたドキュメントおよびグラフデータベースTerminusDBのマネージド無料サービス。開発用は無料、エンタープライズデプロイメントとサポートは有料。
  * [filess.io](https://filess.io) - filess.ioは以下のDBMSのデータベースを2つまで、データベースあたり10MBまで無料で作成できるプラットフォーム：MySQL、MariaDB、MongoDB、PostgreSQL。
  * [xata.io](https://xata.io) - Xataは強力な検索と分析機能を内蔵したサーバーレスデータベース。1つのAPI、複数のタイプセーフなクライアントライブラリ、開発ワークフローに最適化。趣味の開発者向けの永久無料枠はXata 3ユニットまで提供（ユニットの定義はウェブサイトを参照）。
  * [8base.com](https://www.8base.com/) - 8baseはMySQLとGraphQLおよびサーバーレスバックエンドサービスを基盤としたJavaScript開発者向けのフルスタック低コード開発プラットフォーム。UIアプリビルダーを使用して迅速にWebアプリケーションの構築を開始し、素早くスケールアップできます。無料枠には行数：2,500、ストレージ：500、サーバーレスコンピューティング：1Gb/h、クライアントアプリユーザー：5が含まれます。
  * [Nile](https://www.thenile.dev/) — B2Bアプリ向けのPostgresプラットフォーム。無制限のデータベース、シャットダウンなしで常時利用可能、1GBのストレージ（合計）、5000万クエリトークン、自動スケーリング、無制限のベクトル埋め込み

**[⬆️ 目次に戻る](#table-of-contents)**

## トンネリング、WebRTC、WebSocketサーバーおよびその他のルーター

  * [Pinggy](https://pinggy.io) — 単一のコマンドでローカルホストに公開URLを提供、ダウンロード不要。HTTPS/TCP/TLSトンネル。無料プランではトンネルの有効期間が60分。
  * [conveyor.cloud](https://conveyor.cloud/) — Visual Studio拡張機能。IIS Expressをローカルネットワークまたはトンネルを介して公開URLに公開。
  * [Hamachi](https://www.vpn.net/) — LogMeIn Hamachiは、分散チームにLAN風のネットワークを安全に拡張できるホステッドVPNサービス。無料プランでは最大5人まで無制限のネットワークを作成可能。
  * [Mirna Sockets](https://mirna.cloud/) - WebSocketサーバーコードをデプロイすると、wss://URLを提供し、パフォーマンスのモニタリングも可能な無料のSocket as a Serviceプラットフォーム。
  * [localhost.run](https://localhost.run/) — ローカルで実行中のサーバーをトンネルを介して公開URLに公開。
  * [localtunnel](https://theboroer.github.io/localtunnel-www/) — ローカルで実行中のサーバーをトンネルを介して公開URLに公開。無料のホステッドバージョンと[オープンソース](https://github.com/localtunnel/localtunnel)を提供。
  * [ngrok.com](https://ngrok.com/) — ローカルで実行中のサーバーをトンネルを介して公開URLに公開。
  * [cname.dev](https://cname.dev/) — 無料で安全な動的リバースプロキシサービス。
  * [serveo](https://serveo.net/) — ローカルサーバーをインターネットに公開。インストール不要、サインアップ不要。無料サブドメイン、制限なし。
  * [Radmin VPN](https://www.radmin-vpn.com/) — VPNを介して複数のコンピュータをLAN風のネットワークで接続。無制限のピア。（Hamachiの代替）
  * [segment.com](https://segment.com/) — 他のサードパーティサービスにイベントを変換・ルーティングするハブ。月10万イベントまで無料
  * Google STUN — [stun:stun.l.google.com:19302](stun:stun.l.google.com:19302)
  * Twilio STUN — [stun:global.stun.twilio.com:3478?transport=udp](stun:global.stun.twilio.com:3478?transport=udp)
  * [Tailscale](https://tailscale.com/) — オープンソースのWireGuardプロトコルを使用するゼロコンフィグVPN。MacOS、iOS、Windows、Linux、Androidデバイスにインストール可能。個人使用向けの無料プランでは100デバイスと3ユーザーまで。
  * [webhookrelay.com](https://webhookrelay.com) — すべてのwebhookを公開または内部（localhost等）の宛先に管理、デバッグ、ファンアウト、プロキシ。また、プライベートネットワーク内のサーバーを公開HTTPエンドポイント（`https://yoursubdomain.webrelay.io <----> http://localhost:8080`）を介して公開可能。
  * [Hookdeck](https://hookdeck.com/pricing) — どこからでもwebhookの開発、テスト、モニタリングが可能。月10万リクエストと10万試行、3日間の保持期間付き。
  * [Xirsys](https://www.xirsys.com/pricing/) — 無制限のSTUN使用 + 月間500MBのTURN帯域幅、帯域幅制限あり、単一地理リージョン。
  * [ZeroTier](https://www.zerotier.com) — FOSSのマネージド仮想イーサネットサービス。無料プランでは25クライアントまでのエンドツーエンド暗号化ネットワークを無制限に作成可能。デスクトップ/モバイル/NAのクライアント；プライベートネットワーク上のカスタムルーティングルールの設定と新規クライアントノードの承認用Webインターフェース
  * [LocalXpose](https://localxpose.io) — localhostサーバーをインターネットに公開するリバースプロキシ。無料プランではトンネルの有効期間が15分。
  * [Traefik-Hub](https://traefik.io/traefik-hub/) - ローカルで実行中のサービスをトンネルを介してカスタム公開URLに公開し、アクセス制御で保護。1クラスターで5サービスまで無料。
  * [Expose](https://expose.dev/) - セキュアなトンネルを介してローカルサイトを公開。無料プランにはEUサーバー、ランダムサブドメイン、シングルユーザーが含まれます。
  * [btunnel](https://www.btunnel.in/) — localhostとローカルTCPサーバーをインターネットに公開。無料プランにはファイルサーバー、カスタムHTTPリクエストとレスポンスヘッダー、基本認証保護、1時間のトンネルタイムアウトが含まれます。

**[⬆️ 目次に戻る](#table-of-contents)**

## 課題管理とプロジェクト管理

  * [acunote.com](https://www.acunote.com/) — 最大5チームメンバーまで無料のプロジェクト管理とSCRUMソフトウェア
  * [asana.com](https://asana.com/) — コラボレーター付きのプライベートプロジェクトが無料
  * [Backlog](https://backlog.com) — チームが優れたプロジェクトをリリースするために必要なすべてを1つのプラットフォームで。無料プランでは1プロジェクト、10ユーザー、100MBのストレージを提供。
  * [Basecamp](https://basecamp.com/personal) - ToDoリスト、マイルストーン管理、フォーラム形式のメッセージング、ファイル共有、時間追跡。最大3プロジェクト、20ユーザー、1GBのストレージスペースまで。
  * [bitrix24.com](https://www.bitrix24.com/) — イントラネットとプロジェクト管理ツール。無料プランでは無制限のユーザーに対して5GBを提供。
  * [cacoo.com](https://cacoo.com/) — オンラインリアルタイム図表作成：フローチャート、UML、ネットワーク。無料で1図表あたり最大15ユーザー、25シートまで
  * [Chpokify](https://chpokify.com/) — スプリント見積もりの時間を節約するチームベースのプランニングポーカー。5ユーザーまで無料、Jira統合無料、無制限のビデオ通話、無制限のチーム、無制限のセッション。
  * [clickup.com](https://clickup.com/) — プロジェクト管理。クラウドストレージ付きの無料版とプレミアム版。モバイルアプリケーションとGit統合が利用可能。
  * [Clockify](https://clockify.me) - プロジェクト全体の作業時間を追跡できる時間トラッカーとタイムシートアプリ。無制限のユーザー、永久無料。
  * [Cloudcraft](https://cloudcraft.co/) — インテリジェントなコンポーネントでライブデータも表示できるAWS向けに最適化されたCloudcraftビジュアルデザイナーで、数分でプロフェッショナルなアーキテクチャ図を作成。無料プランでは単一ユーザーに対して無制限のプライベート図を提供。
  * [Codegiant](https://codegiant.io) — リポジトリホスティングとCI/CD付きのプロジェクト管理。無料プランでは5チームメンバーまで無制限のリポジトリ、プロジェクト、ドキュメントを提供。月500 CI/CD分。月30000サーバーレスコード実行分。1GBリポジトリストレージ。
  * [Confluence](https://www.atlassian.com/software/confluence) - Atlassianのコンテンツコラボレーションツールで、チームが効率的に協力して知識を共有するのに役立ちます。10ユーザーまで無料プラン。
  * [contriber.com](https://www.contriber.com/) — カスタマイズ可能なプロジェクト管理プラットフォーム、スタータープランが無料、5ワークスペース
  * [Crosswork](https://crosswork.app/) - 多目的プロジェクト管理プラットフォーム。3プロジェクトまで無料、無制限のユーザー、1GBストレージ。
  * [diagrams.net](https://app.diagrams.net/) — Google Drive、OneDrive、またはDropboxにローカルに保存されるオンライン図表。すべての機能とストレージレベルが無料
  * [freedcamp.com](https://freedcamp.com/) - タスク、ディスカッション、マイルストーン、時間追跡、カレンダー、ファイル、パスワードマネージャー。無制限のプロジェクト、ユーザー、ファイルストレージを含む無料プラン。
  * [easyretro.io](https://www.easyretro.io/) — シンプルで直感的なスプリントレトロスペクティブツール。無料プランでは3つのパブリックボードと1つのボードあたり月1回のアンケートを提供。
  * [GForge](https://gforge.com) — 複雑なプロジェクト向けのプロジェクト管理と課題追跡ツールセット。自社運用とSaaSオプションあり。SaaS無料プランでは最初の5ユーザーが無料、オープンソースプロジェクトは無料。
  * [gleek.io](https://www.gleek.io) — 開発者向けの無料の説明図作成ツール。キーワードを使用してインフォーマルなUMLクラス図、オブジェクト図、またはエンティティ関係図を作成。
  * [GraphQL Inspector](https://github.com/marketplace/graphql-inspector) - GraphQL Inspectorは2つのGraphQLスキーマ間の変更リストを出力。各差分は破壊的、非破壊的、または危険として正確に説明され、マークされます。
  * [huboard.com](https://huboard.com/) — GitHubの課題用のインスタントプロジェクト管理、オープンソースは無料
  * [Hygger](https://hygger.io) — プロジェクト管理プラットフォーム。無料プランでは100MBのストレージで無制限のユーザー、プロジェクト、ボードを提供。
  * [Instabug](https://instabug.com) — モバイルアプリ向けの包括的なバグレポートとアプリ内フィードバックSDK。1アプリと1メンバーまで無料プラン。
  * [WishKit](https://wishkit.io) — iOS/macOSアプリのアプリ内ユーザーフィードバックを収集し、ユーザー投票に基づいて機能の優先順位付け。1アプリまで無料プラン。
  * [Ilograph](https://www.ilograph.com/) — ユーザーがインフラストラクチャを複数の視点と詳細レベルで見ることができるインタラクティブな図表。図表はコードで表現可能。無料枠では3人のビューアーまで無制限のプライベート図表を提供。
  * [Jira](https://www.atlassian.com/software/jira) — 多くの企業環境で使用される高度なソフトウェア開発プロジェクト管理ツール。10ユーザーまで無料プラン。
  * [kanbanflow.com](https://kanbanflow.com/) — ボードベースのプロジェクト管理。無料版とより多くのオプションを含むプレミアム版
  * [kanbantool.com](https://kanbantool.com/) — カンバンボードベースのプロジェクト管理。無料プランでは添付ファイルやファイルなしで2つのボードと2人のユーザーを提供。
  * [Kitemaker.co](https://kitemaker.co) - 製品開発プロセスのすべてのフェーズでコラボレーションし、Slack、Discord、Figma、Githubにわたる作業を追跡。無制限のユーザー、無制限のスペース。無料プランでは250の作業項目まで。
  * [Kiter.app](https://www.kiter.app/) - 誰でも求職活動を整理し、面接、機会、つながりを追跡できます。パワフルなWebアプリとChrome拡張機能。完全無料。
  * [Kumu.io](https://kumu.io/) — アニメーション、装飾、フィルター、クラスタリング、スプレッドシートインポートなどを備えた関係マップ。無料枠では無制限のパブリックプロジェクトを提供。グラフサイズは無制限。学生向けの無料プライベートプロジェクト。ファイルをオンラインで公開したくない場合はサンドボックスモードが利用可能（アップロード、編集、ダウンロード、破棄）。
  * [Linear](https://linear.app/) — 合理化されたインターフェースを持つ課題トラッカー。無制限のメンバー、最大10MBのファイルアップロードサイズ、250の課題（アーカイブを除く）まで無料
  * [leiga.com](https://www.leiga.com/) — LeigaはAIを使用してプロジェクトを自動管理し、チームが集中力を保ち、大きな可能性を引き出すのを支援し、プロジェクトが計画通りに進むことを保証するSaaS製品です。10ユーザーまで無料、20のカスタムフィールド、2GBのストレージスペース、ビデオ1本あたり5分までのAI録画、ユーザーあたり月20回の自動化実行。
  * [Lucidchart](https://www.lucidchart.com/) - コラボレーション機能を備えたオンライン図表ツール。無料プランでは3つの編集可能なドキュメント、100のプロフェッショナルテンプレート、基本的なコラボレーション機能を提供。
  * [MeisterTask](https://www.meistertask.com/) — チーム向けのオンラインタスク管理。3プロジェクトと無制限のプロジェクトメンバーまで無料。
  * [MeuScrum](https://www.meuscrum.com/en) - カンバンボード付きの無料オンラインスクラムツール
  * [nTask](https://www.ntaskmanager.com/) — チームのコラボレーション、計画、分析、日常タスクの管理を可能にするプロジェクト管理ソフトウェア。エッセンシャルプランは100MBのストレージと5ユーザー/チームまで永久無料。無制限のワークスペース、ミーティング、割り当て、タイムシート、課題追跡。
  * [Ora](https://ora.pm/) - アジャイルタスク管理とチームコラボレーション。3ユーザーまで無料、ファイルは10MBまで制限。
  * [pivotaltracker.com](https://www.pivotaltracker.com/) — 無制限のパブリックプロジェクトと、合計3人のアクティブユーザー（読み書き）と無制限のパッシブユーザー（読み取り専用）を持つ2つのプライベートプロジェクトまで無料。
  * [plan.io](https://plan.io/) — リポジトリホスティングなどのオプション付きプロジェクト管理。2ユーザー、10顧客、500MBストレージまで無料
  * [Plane](https://plane.so/) - Planeはシンプルで拡張可能なオープンソースのプロジェクトおよび製品管理ツール。無制限のメンバー、最大5MBのファイルアップロードサイズ、1000の課題まで無料。
  * [planitpoker.com](https://www.planitpoker.com/) — 無料オンラインプランニングポーカー（見積もりツール）
  * [point.poker](https://www.point.poker/) - オンラインプランニングポーカー（合意に基づく見積もりツール）。無制限のユーザー、チーム、セッション、ラウンド、投票が無料。登録不要。
  * [ScrumFast](https://www.scrumfast.com) - 非常に直感的なインターフェースを持つスクラムボード、5ユーザーまで無料。
  * [Shake](https://www.shakebugs.com/) - モバイルアプリ向けのアプリ内バグレポートとフィードバックツール。無料プラン、アプリあたり月10件のバグレポート。
  * [Shortcut](https://shortcut.com/) - プロジェクト管理プラットフォーム。10ユーザーまで永久無料。
  * [Tadum](https://tadum.app) - 定期的なミーティング向けに設計された議題と議事録アプリ、10人までのチームに無料
  * [taiga.io](https://taiga.io/) — スタートアップとアジャイル開発者向けプロジェクト管理プラットフォーム、オープンソースは無料
  * [Tara AI](https://tara.ai/) — シンプルなスプリント管理サービス。無料プランではユーザー制限なしで無制限のタスク、スプリント、ワークスペースを提供。
  * [targetprocess.com](https://www.targetprocess.com/) — カンバンやスクラムからほぼすべての運用プロセスまでのビジュアルプロジェクト管理。無制限のユーザー、最大1,000のデータエンティティまで無料 {[詳細](https://www.targetprocess.com/pricing/)}
  * [taskade.com](https://www.taskade.com/) — リアルタイムのコラボレーティブタスクリストとチームアウトライン。無料プランでは1つのワークスペースに無制限のタスクとプロジェクト、1GBのファイルストレージ、1週間のプロジェクト履歴、ビデオミーティングあたり5人の参加者を提供。
  * [taskulu.com](https://taskulu.com/) — ロールベースのプロジェクト管理。5ユーザーまで無料。GitHub/Trello/Dropbox/Google Driveとの統合
  * [Teaminal](https://www.teaminal.com) - リモートチーム向けのスタンドアップ、レトロ、スプリントプランニングツール。15ユーザーまで無料。
  * [teamwork.com](https://teamwork.com/) — プロジェクト管理とチームチャット。5ユーザーと2プロジェクトまで無料。プレミアムプランも利用可能。
  * [teleretro.com](https://www.teleretro.com/) — アイスブレーカー、GIF、絵文字を備えたシンプルで楽しいレトロスペクティブツール。無料プランには3回のレトロと無制限のメンバーが含まれます。
  * [testlio.com](https://testlio.com/) — 課題追跡、テスト管理、ベータテストプラットフォーム。個人使用は無料
  * [terrastruct.com](https://terrastruct.com/) — ソフトウェアアーキテクチャに特化したオンライン図表作成ツール。無料枠では図表あたり4レイヤーまで。
  * [todoist.com](https://todoist.com/) — コラボレーティブおよび個人のタスク管理。無料プランには：5つのアクティブプロジェクト、プロジェクト内5ユーザー、5MBまでのファイルアップロード、3つのフィルター、1週間のアクティビティ履歴が含まれます。
  * [trello.com](https://trello.com/) — ボードベースのプロジェクト管理。無制限の個人ボード、10のチームボード。
  * [Tweek](https://tweek.so/) — シンプルな週間ToDoカレンダーとタスク管理。
  * [ubertesters.com](https://ubertesters.com/) — テストプラットフォーム、統合、クラウドテスター、2プロジェクト、5メンバー
  * [Wikifactory](https://wikifactory.com/) — プロジェクト、VCS、課題を備えた製品設計サービス。無料プランでは無制限のプロジェクト、コラボレーター、3GBのストレージを提供。
  * [Yodiz](https://www.yodiz.com/) — アジャイル開発と課題追跡。3ユーザーまで無料、無制限のプロジェクト。
  * [YouTrack](https://www.jetbrains.com/youtrack/buy/#edition=incloud) — FOSSプロジェクトとプライベートプロジェクト（3ユーザーまで無料）向けの無料ホステッドYouTrack（InCloud）。時間追跡とアジャイルボードを含む
  * [zenhub.com](https://www.zenhub.com) — GitHub内唯一のプロジェクト管理ソリューション。パブリックリポジトリ、OSS、非営利組織は無料
  * [zenkit.com](https://zenkit.com) — プロジェクト管理とコラボレーションツール。5メンバー、5GBの添付ファイルまで無料。
  * [Zube](https://zube.io) — 4プロジェクトと4ユーザーまで無料プランのプロジェクト管理。GitHub統合が利用可能。
  * [Toggl](https://toggl.com/) — 2つの無料生産性ツールを提供。時間管理と追跡アプリの[Toggl Track](https://toggl.com/track/)は、フリーランサーを念頭に置いて設計された無料プランで、無制限の追跡レコード、プロジェクト、クライアント、タグ、レポートなどを提供。そしてタスク計画用の[Toggl Plan](https://toggl.com/plan/)は、無制限のタスク、マイルストーン、タイムラインを備えたソロ開発者向けの無料プラン。
  * [Sflow](https://sflow.io) — sflow.ioは、アジャイルソフトウェア開発、マーケティング、セールス、カスタマーサポート向けのプロジェクト管理ツールで、特にアウトソーシングと組織間コラボレーションプロジェクト向け。3プロジェクトと5メンバーまで無料プラン。
  * [Pulse.red](https://pulse.red) — プロジェクト向けの無料ミニマリストな時間トラッカーとタイムシートアプリ。

**[⬆️ 目次に戻る](#table-of-contents)**

## ストレージとメディア処理

  * [AndroidFileHost](https://androidfilehost.com/) - 無制限の速度、帯域幅、ファイル数、ダウンロード数などを提供する無料のファイル共有プラットフォーム。主にAPKビルド、カスタムROM、改造などのAndroid開発関連ファイル向けですが、他のファイルも受け付けているようです。
  * [borgbase.com](https://www.borgbase.com/) — Borg Backup用のシンプルで安全なオフサイトバックアップホスティング。10 GBの無料バックアップスペースと2つのリポジトリを提供。
  * [icedrive.net](https://www.icedrive.net/) - シンプルなクラウドストレージサービス。10 GBの無料ストレージ
  * [sync.com](https://www.sync.com/) - エンドツーエンドのクラウドストレージサービス。5 GBの無料ストレージ
  * [pcloud.com](https://www.pcloud.com/) - クラウドストレージサービス。最大10 GBの無料ストレージ
  * [sirv.com](https://sirv.com/) — オンザフライでの画像最適化とリサイズ機能を備えたスマートイメージCDN。無料枠には500 MBのストレージと2 GBの帯域幅が含まれます。
  * [cloudimage.io](https://www.cloudimage.io/en/home) — 世界中に1500以上のポイントオブプレゼンスを持つ完全な画像最適化とCDNサービス。様々な画像のリサイズ、圧縮、透かし機能を提供。レスポンシブ画像、360度画像作成、画像編集用のオープンソースプラグイン。月間25GBのCDNトラフィック、25GBのキャッシュストレージ、無制限の変換を含む無料月間プラン。
  * [cloudinary.com](https://cloudinary.com/) — Ruby、Python、Java、PHP、Objective-Cなどのライブラリを使用したサイトやアプリ向けの画像アップロード、強力な操作、ストレージ、配信。無料枠には月間25クレジットが含まれます。1クレジットは1,000回の画像変換、1 GBのストレージ、または1 GBのCDN使用量に相当。
  * [embed.ly](https://embed.ly/) — Webページへのメディア埋め込み、レスポンシブな画像スケーリング、Webページからの要素抽出のためのAPIを提供。毎月5,000 URLまで15リクエスト/秒まで無料
  * [filestack.com](https://www.filestack.com/) — ファイルピッカー、変換、配信。250ファイル、500変換、3 GBの帯域幅まで無料
  * [file.io](https://www.file.io) - 2 GBのファイルストレージ。ファイルは1回ダウンロードすると自動削除。ストレージと対話するためのREST API。レート制限は1リクエスト/分。
  * [freetools.site](https://freetools.site/) — 無料のオンラインツール。ドキュメント、画像、音声、動画などの変換や編集が可能。
  * [GoFile.io](https://gofile.io/) - WebベースのUIとAPIで利用できる無料のファイル共有・ストレージプラットフォーム。ファイルサイズ、帯域幅、ダウンロード数などに制限なし。ただし、ファイルが非アクティブ（10日間ダウンロードなし）になると削除されます。
  * [gumlet.com](https://www.gumlet.com/) — CDNを通じた画像・動画のホスティング、処理、ストリーミング。動画は月間250 GB、画像は月間30 GBの寛大な無料枠を提供。
  * [image-charts.com](https://www.image-charts.com/) — 透かし付きの無制限の画像チャート生成
  * [Imgbot](https://github.com/marketplace/imgbot) — Imgbotは画像を最適化して時間を節約する親しみやすいロボット。最適化された画像は品質を損なうことなくファイルサイズを小さくします。オープンソース向けに無料。
  * [ImgBB](https://imgbb.com/) — ImgBBは無制限の画像ホスティングサービス。画面上の任意の場所に画像をドラッグ&ドロップ。画像あたり32 MBの制限。画像アップロード後、直接画像リンク、BBコード、HTMLサムネイルを受け取れます。ログインすると、アップロード履歴を確認できます。
  * [imgen](https://www.jitbit.com/imgen/) - 透かしなしの無制限ソーシャルカバー画像生成API
  * [imgix](https://www.imgix.com/) - 画像のキャッシュ、管理、CDN。無料プランには1000のオリジン画像、無制限の変換、100 GBの帯域幅が含まれます
  * [kraken.io](https://kraken.io/) — Webサイトのパフォーマンス向けの画像最適化サービス、無料プランではファイルサイズ1 MBまで
  * [kvstore.io](https://www.kvstore.io/) — キーバリューストレージサービス。無料枠では100キー、キーあたり1KB、時間あたり100コールまで
  * [npoint.io](https://www.npoint.io/) — 共同スキーマ編集機能付きJSONストア
  * [nitropack.io](https://nitropack.io/) - フロントエンド最適化（キャッシュ、画像とコードの最適化、CDN）による自動サイト高速化。月間5,000ページビューまで無料
  * [otixo.com](https://www.otixo.com/) — すべてのクラウドストレージファイルを1か所から暗号化、共有、コピー、移動。基本プランでは最大ファイルサイズ250 MBで無制限のファイル転送と5つの暗号化ファイルを提供
  * [packagecloud.io](https://packagecloud.io/) — YUM、APT、RubyGem、PyPI用のホステッドパッケージリポジトリ。リクエストによって限定的な無料プランとオープンソースプランが利用可能
  * [getpantry.cloud](https://getpantry.cloud/) — 個人プロジェクト、ハッカソン、モバイルアプリに最適なシンプルなJSONデータストレージAPI！
  * [Pinata IPFS](https://pinata.cloud) — Pinataは、IPFSでファイルをアップロードおよび管理する最もシンプルな方法です。フレンドリーなユーザーインターフェースとIPFS APIにより、プラットフォーム、クリエイター、コレクター向けに最も使いやすいIPFSピンニングサービスを提供します。APIアクセス付きで1 GBの無料ストレージ。
  * [placekitten.com](https://placekitten.com/) — プレースホルダーとして使用する子猫の写真を提供する迅速でシンプルなサービス
  * [plot.ly](https://plot.ly/) — データのグラフ化と共有。無料枠には無制限のパブリックファイルと10個のプライベートファイルが含まれます
  * [podio.com](https://podio.com/) — ユーザー管理を除く基本プランの機能を、最大5人のチームで試用可能
  * [QRME.SH](https://qrme.sh) - 高速で美しい一括QRコード生成 - ログイン不要、透かしなし、広告なし。一括エクスポートで最大100 URLまで。
  * [QuickChart](https://quickchart.io) — 埋め込み可能な画像チャート、グラフ、QRコードを生成
  * [redbooth.com](https://redbooth.com) — P2Pファイル同期、最大2ユーザーまで無料
  * [resmush.it](https://resmush.it) — reSmush.itは画像最適化を提供する無料のAPIです。WordPress、Drupal、Magentoなどの一般的なCMSに実装されています。reSmush.itは、すでに70億以上の画像を処理した最も使用されている画像最適化APIであり、依然として無料です。
  * [Shotstack](https://shotstack.io) - スケーラブルな動画生成・編集API。月間20分の動画レンダリングまで無料
  * [tinypng.com](https://tinypng.com/) — PNGとJPEG画像を圧縮・リサイズするAPI、毎月500回の圧縮まで無料
  * [transloadit.com](https://transloadit.com/) — ファイルのアップロードと動画、音声、画像、ドキュメントのエンコーディングを処理。GitHub Student Developer Packを通じて、オープンソース、慈善団体、学生向けに無料。商用アプリケーションはテスト用に2 GB無料
  * [twicpics.com](https://www.twicpics.com) - レスポンシブ画像をサービスとして提供。画像CDN、メディア処理API、画像最適化を自動化するフロントエンドライブラリを提供。月間3GBのトラフィックまで無料。
  * [uploadcare.com](https://uploadcare.com/hub/developers/) — Uploadcareは、最先端のアルゴリズムに基づく究極のツールキットを備えたメディアパイプラインを提供します。すべての機能が開発者向けに完全無料：ファイルアップロードAPIとUI、画像CDNとオリジンサービス、アダプティブデリバリー、スマート圧縮。無料枠には3000回のアップロード、3 GBのトラフィック、3 GBのストレージが含まれます。
  * [imagekit.io](https://imagekit.io) – 自動最適化、リアルタイム変換、ストレージを備えた画像CDNで、数分で既存のセットアップに統合できます。無料プランには月間最大20GBの帯域幅が含まれます。
  * [internxt.com](https://internxt.com) – Internxt Driveは、絶対的なプライバシーと妥協のないセキュリティに基づくゼロ知識ファイルストレージサービスです。サインアップして10 GBを永久に無料で取得できます！
  * [degoo.com](https://degoo.com/) – AI基づくクラウドストレージで、最大20 GB無料、3デバイス、5 GBの紹介ボーナス（90日間アカウント非アクティブ）。
  * [MConverter.eu](https://mconverter.eu/) – ファイルの一括変換。[AVIF](https://mconverter.eu/convert/to/avif/)などの多くのファイル形式をサポート。動画からすべての画像フレームを抽出。1日あたり最大10個の100MBファイルまで無料で、2つずつバッチ処理。
  * [ImageEngine](https://imageengine.io/) – ImageEngineは使いやすいグローバル画像CDNです。60秒未満でセットアップ。AVIFとJPEGXLのサポート、WordPress、Magento、React、Vueプラグインなど。[こちら](https://imageengine.io/developer-program/)で無料の開発者アカウントを申請できます。
  * [DocsParse](https://docsparse.com/) – GPT搭載のAIによるPDF、画像の処理で、JSON、CSV、EXCEL形式の構造化データに変換。毎月30クレジットまで無料。
  * [VaocherApp QR Code Generator](https://www.vaocherapp.com/qr-code-generator) – ギフトカード、ギフト券、プロモーション用のカスタムQRコードを簡単に作成。カスタムスタイル、色、ロゴなどをサポート。

**[⬆️ 目次に戻る](#table-of-contents)**

## デザインインスピレーション

  * [awwwards.](https://www.awwwards.com/) - [トップウェブサイト] デザイナーによって投票された最高のデザインのウェブサイトのショーケース。
  * [Behance](https://www.behance.net/) - [デザインショーケース] デザイナーが作品を展示する場所。UI/UXプロジェクトのカテゴリでフィルタリング可能。
  * [dribbble](https://dribbble.com/) - [デザインショーケース] 実際のアプリケーションとは異なる、ユニークなデザインインスピレーション。
  * [Landings](https://landings.dev/) - [Webスクリーンショット] 好みに応じた最高のランディングページをデザインインスピレーションとして見つけることができます。
  * [Lapa Ninja](https://www.lapa.ninja/) - [ランディングページ / UIキット / Webスクリーンショット] Lapa Ninjaは、ウェブ上から厳選された6025以上の最高のランディングページ例、デザイナー向けの無料本、無料UIキットを集めたギャラリーです。
  * [LovelyLanding.net](https://www.lovelylanding.net/) - [ランディングページデザイン] 定期的に更新されるランディングページのスクリーンショット。デスクトップ、タブレット、モバイルのスクリーンショットを含みます。
  * [Mobbin](https://mobbin.design/) - [モバイルスクリーンショット] 50,000以上の完全検索可能なモバイルアプリスクリーンショットライブラリで、UI & UXリサーチの時間を節約できます。
  * [Uiland Design](https://uiland.design/) - [モバイルスクリーンショット] アフリカと世界の主要企業のモバイルおよびWebのUIデザインを探索できます。
  * [Mobile Patterns](https://www.mobile-patterns.com/) - [モバイルスクリーンショット] デザイナー、開発者、プロダクトメーカーが参照できる、最高のUI UXパターン（iOSとAndroid）を特集するデザインインスピレーションライブラリ。
  * [Page Flows](https://pageflows.com/) - [モバイル/Webの動画とスクリーンショット] 多くのモバイルおよびWebアプリの完全なフローの動画。スクリーンショットも含まれます。高度な検索とインデックス付け。
  * [Screenlane](https://screenlane.com/) - [モバイルスクリーンショット] 最新のWebとモバイルアプリのUIデザイントレンドからインスピレーションを得ることができます。パターンとアプリでフィルタリング可能。
  * [scrnshts](https://scrnshts.club/) - [モバイルスクリーンショット] 厳選された最高のアプリストアデザインスクリーンショットのコレクション。
  * [UI Garage](https://uigarage.net/) - [モバイル/Webスクリーンショット] デザイナーと開発者がインスピレーション、ツール、プロジェクトに最適なリソースを見つけるための日々のUIインスピレーションとパターン。
  * [Refero](https://refero.design/) - [Webスクリーンショット] 優れたWebアプリケーションからのデザインリファレンスをタグ付けして検索可能なコレクション。


**[⬆️ トップに戻る](#table-of-contents)**

## 地図上のデータ可視化

  * [IP Geolocation](https://ipgeolocation.io/) — 開発者向けの無料プランで月30,000リクエストまで利用可能。
  * [carto.com](https://carto.com/) — あなたのデータと公開データから地図と地理空間APIを作成。
  * [Clockwork Micro](https://clockworkmicro.com/) — 時計仕掛けのように動作する地図ツール。月間50,000クエリまで無料（地図タイル、db2vector、標高）。
  * [developers.arcgis.com](https://developers.arcgis.com) — Web、デスクトップ、モバイル向けの地図、地理空間データストレージ、分析、ジオコーディング、ルーティングなどのAPIとSDK。月間200万の無料ベースマップタイル、20,000の非保存ジオコード、20,000のシンプルルート、5,000の所要時間計算、5GBの無料タイル+データストレージ。
  * [Foursquare](https://developer.foursquare.com/) - Places APIとPilgrim SDKによる位置情報の発見、会場検索、コンテキストを意識したコンテンツ。
  * [geoapify.com](https://www.geoapify.com/) - ベクターおよびラスタータイル地図、ジオコーディング、場所、ルーティング、等時線API。1日3,000リクエストまで無料。
  * [geocod.io](https://www.geocod.io/) — APIまたはCSVアップロードによるジオコーディング。1日2,500クエリまで無料。
  * [geocodify.com](https://geocodify.com/) — APIまたはCSVアップロードによるジオコーディングとジオパーシング。月間10,000クエリまで無料。
  * [geojs.io](https://www.geojs.io/) - 高可用性のREST/JSON/JSONP IPジオロケーション検索API。
  * [giscloud.com](https://www.giscloud.com/) — 地理データのオンラインでの可視化、分析、共有。
  * [graphhopper.com](https://www.graphhopper.com/) - ルーティング、ルート最適化、距離マトリックス、ジオコーディング、マップマッチングの無料開発者パッケージを提供。
  * [here](https://developer.here.com/) — 地図とロケーション対応アプリ用のAPIとSDK。月間250,000トランザクションまで無料。
  * [locationiq.com](https://locationiq.com/) — ジオコーディング、地図、ルーティングAPI。1日5,000リクエストまで無料。
  * [mapbox.com](https://www.mapbox.com/) — 地図データを表示するための地図、地理空間サービス、SDK。
  * [maptiler.com](https://www.maptiler.com/cloud/) — ベクター地図、地図サービス、地図可視化用SDK。週次更新の無料ベクタータイルと4つの地図スタイルを提供。
  * [nominatim.org](https://nominatim.org/) — OpenStreetMapの無料ジオコーディングサービスで、グローバルな住所検索機能と逆ジオコーディング機能を提供。
  * [nextbillion.ai](https://nextbillion.ai/) - 地図関連サービス：ジオコーディング、ナビゲーション（方向、ルーティング、ルート最適化、距離マトリックス）、Maps SDK（ベクター、静的、モバイルSDK）。各サービスに[指定された割り当て](https://nextbillion.ai/pricing)で無料。
  * [opencagedata.com](https://opencagedata.com) — OpenStreetMapと他のオープンな地理ソースを集約したジオコーディングAPI。1日2,500クエリまで無料。
  * [osmnames](https://osmnames.org/) — ジオコーディング、関連するWikipediaページの人気度によってランク付けされた検索結果。
  * [positionstack](https://positionstack.com/) - グローバルな場所と座標の無料ジオコーディング。個人利用の場合、月間25,000リクエストまで。
  * [stadiamaps.com](https://stadiamaps.com/) — 地図タイル、ルーティング、ナビゲーション、その他の地理空間API。非商用利用とテスト用に1日2,500の地図表示とAPIリクエストまで無料。
  * [maps.stamen.com](http://maps.stamen.com/) - 無料の地図タイルとタイルホスティング。
  * [ipstack](https://ipstack.com/) - IPアドレスによるウェブサイト訪問者の位置特定と識別
  * [Geokeo api](https://geokeo.com) - 言語修正などを備えたジオコーディングAPI。世界規模のカバレッジ。1日2,500クエリまで無料

**[⬆️ トップに戻る](#table-of-contents)**

## パッケージビルドシステム

  * [build.opensuse.org](https://build.opensuse.org/) — 複数のディストリビューション（SUSE、EL、Fedora、Debianなど）向けのパッケージビルドサービス。
  * [copr.fedorainfracloud.org](https://copr.fedorainfracloud.org) — FedoraとEL向けのMockベースのRPMビルドサービス。
  * [help.launchpad.net](https://help.launchpad.net/Packaging) — UbuntuとDebianのビルドサービス。

**[⬆️ トップに戻る](#table-of-contents)**

## IDEとコード編集

  * [3v4l](https://3v4l.org/) - 300以上のPHPバージョンでコードを実行できる無料オンラインPHPシェルとスニペット共有サイト
  * [Android Studio](https://developer.android.com/studio) — Android Studioは、あらゆる種類のAndroidデバイス向けアプリを構築するための最速ツールを提供します。オープンソースIDEは誰でも無料で使用でき、最高のAndroidアプリ開発が可能です。Windows、Mac、Linux、さらにはChromeOSでも利用可能！
  * [AndroidIDE](https://m.androidide.com/) — Androidデバイス上で実際のGradleベースのAndroidアプリケーションを開発するためのオープンソースIDE。
  * [Apache Netbeans](https://netbeans.apache.org/) — 開発環境、ツーリングプラットフォーム、アプリケーションフレームワーク。
  * [apiary.io](https://apiary.io/) — 即座のAPIモックと生成されたドキュメントを備えた共同設計API（無制限のAPIブループリントと1つの管理者アカウントとホストされたドキュメントを持つ無制限のユーザーに対して無料）。
  * [BBEdit](https://www.barebones.com/) - BBEditはmacOS向けの人気で拡張可能なエディタです。フリーモードでは[強力な基本機能セット](https://www.barebones.com/products/bbedit/comparison.html)と高度な機能へのアップグレードパスを提供します。
  * [Binder](https://mybinder.org/) - Gitリポジトリをインタラクティブなノートブックのコレクションに変換します。無料の公共サービスです。
  * [BlueJ](https://bluej.org) — 世界中の何百万人もの人々に使用されている、初心者向けに設計された無料のJava開発環境。Oracleによってパワーアップされており、初心者を支援するシンプルなGUIを備えています。
  * [Bootify.io](https://bootify.io/) - カスタムデータベースとREST APIを備えたSpring Bootアプリジェネレーター。
  * [Brackets](http://brackets.io/) - Bracketsは、Web開発のために特別に設計されたオープンソーステキストエディタです。軽量で使いやすく、高度にカスタマイズ可能です。
  * [cacher.io](https://www.cacher.io) — 100以上のプログラミング言語をサポートするラベル付きコードスニペットオーガナイザー。
  * [Code::Blocks](https://codeblocks.org) — FortranとC/C++用の無料IDE。オープンソースで、Windows、macOS、Linuxで動作します。
  * [Cody](https://sourcegraph.com/cody) - コードブロック、オートコンプリート、ユニットテストの作成、コードベース全体の理解、修正、検索が可能な無料のAIコーディングアシスタント。VS Code、JetBrains、オンラインで利用可能。
  * [codiga.io](https://codiga.io/) — IDE内で直接コードスニペットを検索、定義、再利用できるコーディングアシスタント。個人と小規模組織向けに無料。
  * [codesnip.com.br](https://codesnip.com.br) — カテゴリ、検索、タグを備えたシンプルなコードスニペットマネージャー。無料で無制限。
  * [cocalc.com](https://cocalc.com/) — （以前のcloud.sagemath.comのSageMathCloud）— クラウドでの共同計算。ブラウザからUbuntuに完全にアクセスでき、組み込みのコラボレーション機能と、数学、科学、データサイエンス向けの多くの無料ソフトウェアがプリインストールされています：Python、LaTeX、Jupyterノートブック、SageMath、scikitlearnなど。
  * [code.cs50.io](https://code.cs50.io/) - CS50向けのVisual Studio Codeは、GitHub Codespacesを学生と教師向けに適応させたcode.cs50.ioのWebアプリです。
  * [codepen.io](https://codepen.io/) — CodePenは、Webのフロントエンド側のプレイグラウンドです。
  * [codesandbox.io](https://codesandbox.io/) — React、Vue、Angular、Preactなどのオンラインプレイグラウンド。
  * [Components.studio](https://webcomponents.dev/) - コンポーネントを分離して開発し、ストーリーで視覚化し、テストし、npmで公開します。
  * [Eclipse Che](https://www.eclipse.org/che/) - 開発者チーム向けのKubernetesネイティブで複数言語をサポートするWebベースのIDE。オープンソースでコミュニティ主導。Red Hatがホストするオンラインインスタンスが[workspaces.openshift.com](https://workspaces.openshift.com/)で利用可能。
  * [fakejson.com](https://fakejson.com/) — FakeJSONは、APIを使用して素早くフェイクデータを生成するのに役立ちます。必要なものとその方法を説明するAPIリクエストを行うと、APIはすべてをJSONで返します。アイデアの市場投入までの時間を短縮し、成功するまでフェイクします。
  * [GetVM](https://getvm.io) - インスタントの無料LinuxとIDEのChromeサイドバー。無料枠には1日5つのVMが含まれます。
  * [GitPod](https://www.gitpod.io) - GitHubプロジェクト用のインスタント、すぐにコーディング可能な開発環境。無料枠には月50時間が含まれます。
  * [ide.goorm.io](https://ide.goorm.io) goormIDEはクラウド上の完全なIDEです。複数言語のサポート、完全な機能を備えたWebベースのターミナルを通じたLinuxベースのコンテナ、ポートフォワーディング、カスタムURL、リアルタイムコラボレーションとチャット、共有リンク、Git/Subversionサポートを提供。さらに多くの機能があります（無料枠にはコンテナごとに1GB RAMと10GBストレージ、5つのコンテナスロットが含まれます）。
  * [JDoodle](https://www.jdoodle.com) — 60以上のプログラミング言語に対応したオンラインコンパイラとエディタで、REST APIコードコンパイル用の無料プランでは1日200クレジットまで利用可能。
  * [jetbrains.com](https://jetbrains.com/products.html) — 生産性ツール、IDE、デプロイツール（[IntelliJ IDEA](https://www.jetbrains.com/idea/)、[PyCharm](https://www.jetbrains.com/pycharm/)など）。学生、教師、オープンソース、ユーザーグループ向けの無料ライセンス。
  * [jsbin.com](https://jsbin.com) — JS Binは、フロントエンドWeb（HTML、CSS、JavaScript。Markdown、Jade、Sassもサポート）のもう1つのプレイグラウンドとコード共有サイトです。
  * [jsfiddle.net](https://jsfiddle.net/) — JS Fiddleは、コラボレーションをサポートするフロントエンドWebのプレイグラウンドとコード共有サイトです。
  * [JSONPlaceholder](https://jsonplaceholder.typicode.com/) - JSON形式のフェイクデータを返すいくつかのREST APIエンドポイント。サーバーをローカルで実行したい場合はソースコードも利用可能です。
  * [Lazarus](https://www.lazarus-ide.org/) — LazarusはDelphi互換のクロスプラットフォームの高速アプリケーション開発IDE。
  * [MarsCode](https://www.marscode.com/) - 無料のAIパワードクラウドベースのIDE。
  * [micro-jaymock](https://micro-jaymock.now.sh/) - フェイクJSONデータを生成するための小さなAPIモックマイクロサービス。
  * [mockable.io](https://www.mockable.io/) — MockableはRESTful APIまたはSOAPウェブサービスをモックアウトするためのシンプルな設定可能なサービスです。このオンラインサービスでは、REST APIまたはSOAPエンドポイントを素早く定義し、JSONまたはXMLデータを返すことができます。
  * [mockaroo](https://mockaroo.com/) — Mockarooでは、CSV、JSON、SQL、Excelフォーマットで現実的なテストデータを生成できます。バックエンドAPIのモックも作成できます。
  * [Mocklets](https://mocklets.com) - より速い並行開発とより包括的なテストのために、HTTPベースのモックAPIシミュレータを提供し、永続的な無料枠があります。
  * [Paiza](https://paiza.cloud/en/) — ブラウザで何もセットアップする必要なくWebアプリを開発。無料プランでは、2 CPUコア、2 GB RAM、1 GBストレージを備えた24時間の寿命と1日4時間の実行時間を持つ1つのサーバーを提供。
  * [Prepros](https://prepros.io/) - PreposはSass、Less、Stylus、Pug/Jade、Haml、Slim、CoffeeScript、TypeScriptをすぐに使えるようにコンパイルし、ブラウザをリロードし、ウェブサイトの開発とテストを容易にして、完璧なものを作ることに集中できるようにします。数回クリックするだけで独自のツールを追加することもできます。
  * [Replit](https://replit.com/) — 様々なプログラミング言語に対応したクラウドコーディング環境。
  * [SoloLearn](https://code.sololearn.com) — コードスニペットの実行に適したクラウドプログラミングプレイグラウンド。様々なプログラミング言語をサポート。コードの実行には登録は必要ありませんが、プラットフォームにコードを保存する場合は必要です。また、初心者と中級者向けの無料コースも提供しています。
  * [stackblitz.com](https://stackblitz.com/) — フルスタックアプリを作成、編集、デプロイするためのオンライン/クラウドIDE。人気のあるNodeJsベースのフロントエンドとバックエンドフレームワークをサポート。新しいプロジェクトを作成するためのショートリンク：[https://node.new](https://node.new)。
  * [Sublime Text](https://www.sublimetext.com/) - Sublime Textは、コーディングとテキスト編集タスクに使用される人気で多用途な、高度にカスタマイズ可能なテキストエディタです。
  * [Visual Studio Code](https://code.visualstudio.com/) - モダンなWebとクラウドアプリケーションの構築とデバッグのために再定義され最適化されたコードエディタ。Microsoftによって開発。
  * [Visual Studio Community](https://visualstudio.microsoft.com/vs/community/) — 何千もの拡張機能、クロスプラットフォームアプリ開発（iOSとAndroid用のMicrosoft拡張機能がダウンロード可能）、デスクトップ、Web、クラウド開発、複数言語サポート（C#、C++、JavaScript、Python、PHPなど）を備えた完全な機能を持つIDE。
  * [VSCodium](https://vscodium.com/) - コミュニティ主導で、テレメトリ/トラッキングがなく、自由にライセンスされたMicrosoftのエディタVSCodeのバイナリ配布。
  * [wakatime.com](https://wakatime.com/) — テキストエディタプラグインを使用したコーディング活動に関する定量的な自己メトリクス、無料プランは制限付き。
  * [Wave Terminal](https://waveterm.dev/) - Waveは、シームレスなワークフロー用のオープンソースのクロスプラットフォームターミナルです。インラインで何でもレンダリング。セッションと履歴を保存。オープンWebスタンダードを活用。MacOSとLinux対応。
  * [WebComponents.dev](https://webcomponents.dev/) — 58のテンプレートを使用して、ストーリーとテストをサポートする分離環境でWebコンポーネントをコーディングするブラウザ内IDE。
  * [PHPSandbox](https://phpsandbox.io/) — PHP用のオンライン開発環境
  * [WebDB](https://webdb.app) - 無料の効率的なデータベースIDE。サーバー探索、ERD、データジェネレータ、AI、NoSQL構造マネージャー、データベースバージョニングなどの機能を提供。
  * [Zed](https://zed.dev/) - ZedはAtomとTree-sitterの作者によるハイパフォーマンスなマルチプレイヤーコードエディタです。
  * [OneCompiler](https://onecompiler.com/) - Java、Python、C++、JavaScriptを含む70以上の言語をサポートする無料のオンラインコンパイラ。
  

**[⬆️ Back to Top](#table-of-contents)**

## 分析、イベント、統計

  * [Dwh.dev](https://dwh.dev) - データクラウド監視ソリューション(Snowflake)。個人利用は無料。
  * [Hightouch](https://hightouch.com/) - Hightouchは、データウェアハウスから顧客データをCRM、マーケティング、サポートツールに同期するリバースETLプラットフォームです。無料プランでは1つの同期先を提供。
  * [Avo](https://avo.app/) — 分析リリースワークフローを簡素化。シングルソースオブトゥルースのトラッキングプラン、型安全な分析トラッキングライブラリ、アプリ内デバッガー、データ監視機能でリリース前のすべてのデータ問題を検出。2名のワークスペースメンバーと1時間のデータ監視ルックバックが無料。
  * [Branch](https://www.branch.io) — モバイル分析プラットフォーム。無料プランではディープリンクなどのサービスを含む最大1万モバイルアプリユーザーまで。
  * [Cauldron](https://cauldron.io) — 異なるタイプのデータソース(Git、Github、Gitlab)から複数のコラボレーションプラットフォームの情報を集約できるオープンソースの分析ソリューション。無料プランでは無制限のレポートを提供。
  * [Census](https://www.getcensus.com/) — リバースETL&オペレーショナル分析プラットフォーム。データウェアハウスから10フィールドを、Salesforce、Zendesk、Amplitudeなど60以上のSaaSに同期可能。
  * [Clicky](https://clicky.com) — ウェブサイト分析プラットフォーム。1ウェブサイトで3000ビューまでの分析が無料。
  * [Databox](https://databox.com) — 他の分析&BIプラットフォームを組み合わせたビジネスインサイト&分析。無料プランでは3ユーザー、ダッシュボード&データソースを提供。1100万件の履歴データレコード。
  * [Hitsteps.com](https://hitsteps.com/) — 1ウェブサイトにつき月間2,000ページビューまで
  * [amplitude.com](https://amplitude.com/) — 月間100万イベントまで、最大2アプリまで
  * [GoatCounter](https://www.goatcounter.com/) — GoatCounterは、ホステッドサービス(非商用利用は無料)またはセルフホストアプリとして利用できるオープンソースのウェブ分析プラットフォームです。Google AnalyticsやMatomoの代替として、使いやすく意味のあるプライバシーフレンドリーなウェブ分析を提供することを目指しています。無料プランは非商用利用向けで、無制限のサイト、6ヶ月のデータ保持、月間10万ページビューを含みます。
  * [Google Analytics](https://analytics.google.com/) — Google Analytics
  * [MetricsWave](https://metricswave.com) — 開発者向けのプライバシーフレンドリーなGoogle Analytics代替。無料プランではクレジットカード不要で月間2万ページビューまで。
  * [Expensify](https://www.expensify.com/) — 経費報告、個人報告の承認ワークフローが無料
  * [getinsights.io](https://getinsights.io) - プライバシー重視でクッキーを使用しない分析、月間3,000イベントまで無料。
  * [heap.io](https://heap.io) — iOSまたはWebアプリでのすべてのユーザーアクションを自動的にキャプチャ。月間1万セッションまで無料。
  * [Hotjar](https://hotjar.com) — ウェブサイト分析とレポート。無料プランでは1日2,000ページビュー、1日100スナップショット(最大容量:300)まで。3つのスナップショットヒートマップを365日保存可能。チームメンバー数は無制限。アプリ内およびスタンドアロンの調査、スクリーンショット付きフィードバックウィジェットも提供。無料プランでは3つの調査と3つのフィードバックウィジェットを作成でき、月間20件の回答を収集可能。
  * [Keen](https://keen.io/) — データ収集、分析、可視化のためのカスタム分析。月間1,000イベントまで無料
  * [Yandex.Datalens](https://datalens.yandex.com/) — Yandex Cloudのデータ可視化・分析サービス。無料で提供。ユーザー数とリクエスト数に制限なし。
  * [Yandex.Metrica](https://metrica.yandex.com/) — 無制限の無料分析
  * [Mixpanel](https://mixpanel.com/) — 月間10万トラッキングユーザー、無制限のデータ履歴とシート、USまたはEUのデータレジデンシー
  * [Moesif](https://www.moesif.com) — RESTとGraphQLのAPI分析。(月間50万APIコールまで無料)
  * [optimizely.com](https://www.optimizely.com) — A/Bテストソリューション、無料スタータープラン、1ウェブサイト、1 iOS、1 Androidアプリ
  * [Microsoft PowerBI](https://powerbi.com) — Microsoftによるビジネスインサイトおよび分析。無料プランでは100万ユーザーライセンスで制限付き使用が可能。
  * [Row Zero](https://rowzero.io) - 超高速な接続スプレッドシート。データベース、S3、APIに直接接続。数百万行を即座にインポート、分析、グラフ化、共有。3つの無料(永久)ワークブック。
  * [sematext.com](https://sematext.com/cloud/) — 月間最大5万アクション、1日のデータ保持、無制限のダッシュボード、ユーザーなどが無料。
  * [Similar Web](https://similarweb.com) — Webとモバイルアプリのアナリティクス。無料プランではメトリクスごとに5つの結果、1ヶ月分のモバイルアプリデータ、3ヶ月分のウェブサイトデータを提供。
  * [StatCounter](https://statcounter.com/) — ウェブサイト訪問者分析。無料プランでは最新500訪問者の分析が可能。
  * [Statsig](https://statsig.com) - 分析、フィーチャーフラグ、A/Bテストにまたがるオールインワンプラットフォーム。月間100万メータードイベントまで無料。
  * [Tableau Developer Program](https://www.tableau.com/developer) — 組織のためにTableauを完璧に動作させるための革新、作成、カスタマイズ。無料の開発者プログラムではTableau Onlineの個人開発用サンドボックスライセンスを提供。バージョンは最新のプレリリースバージョンなので、データ開発者はこの素晴らしいプラットフォームのすべての機能をテストできます。
  * [usabilityhub.com](https://usabilityhub.com/) — 実際の人々にデザインやモックアップをテストし、訪問者を追跡。1ユーザー、無制限のテストが無料
  * [woopra.com](https://www.woopra.com/) — 50万アクション、90日間のデータ保持、30以上のワンクリック統合が可能な無料ユーザー分析プラットフォーム。
  * [counter.dev](https://counter.dev) — シンプルで、そのためプライバシーフレンドリーなウェブ分析。無料または寄付による任意の支払い。
  * [PostHog](https://posthog.com) - 月間100万トラッキングイベントまでの完全なプロダクト分析スイートが無料。また、月間250件の回答付きの無制限アプリ内調査も提供。
  * [Uptrace](https://uptrace.dev) - 開発者が障害を特定しパフォーマンスのボトルネックを見つけるのに役立つ分散トレースツール。無料プランがあり、オープンソースプロジェクトには無料の個人サブスクリプションを提供し、オープンソースバージョンもあります。
  * [Microsoft Clarity](https://clarity.microsoft.com/) - Clarityは、実際のユーザーがサイトをどのように使用しているかを把握するための、無料で使いやすいツールです。
  * [Beampipe.io](https://beampipe.io) - Beampipeはシンプルでプライバシー重視のウェブ分析。最大5ドメインと月間1万ページビューまで無料。
  * [Aptabase](https://aptabase.com) — オープンソース、プライバシーフレンドリー、シンプルなモバイルおよびデスクトップアプリ向け分析。Swift、Kotlin、React Native、Flutter、Electron、その他多くのSDKを提供。月間2万イベントまで無料。
  * [Trackingplan](https://www.trackingplan.com/) - デジタル分析、マーケティングデータ、ピクセルの問題を自動的に検出し、トラッキングプランを最新の状態に保ち、シームレスなコラボレーションを促進。コードを書かずに本番環境での実トラフィックまたは回帰テストに分析カバレッジを追加できます。
  * [LogSpot](https://logspot.io) - 埋め込み可能な分析ウィジェットと自動化されたロボット(slack、telegram、webhooks)を含む、完全な統合ウェブおよびプロダクト分析プラットフォーム。無料プランには月間1万イベントが含まれます。
  * [Umami](https://umami.is/) - シンプル、高速、プライバシー重視のGoogle Analyticsのオープンソース代替。
  * [TrackWith Dicloud](https://dicloud.net/trackwith-privacy-focused-analytics/) - Google Analyticsの無料の軽量でプライバシー重視の代替。無制限のページビュー、無制限の訪問者、無制限のページヒートマップ&ゴールトラッキング。最大3ドメインとドメインごとに600のセッション再生が無料。
  * [AppFit](https://appfit.io) - AppFitは、分析とプロダクトアップデートのクロスプラットフォーム管理を容易にする包括的な分析およびプロダクト管理ツールです。無料プランには月間1万イベント、プロダクトジャーナル、週次インサイトが含まれます。
  * [Seline](https://seline.so) - Selineはシンプルでプライベートなウェブサイトおよびプロダクト分析です。クッキーレス、軽量、独立型。無料プランには月間3,000イベントが含まれ、ダッシュボード、ユーザージャーニー、ファネルなどのすべての機能にアクセスできます。
  * [Peasy](https://peasy.so) - Peasyは、ウェブサイトとプロダクト向けの軽量でプライバシー重視の分析ツールです。無料プランには月間3,000イベントが含まれます。

**[⬆️ 目次に戻る](#table-of-contents)**

## 訪問者セッション記録

  * [Reactflow.com](https://www.reactflow.com/) — サイトごと:1日1,000ページビュー、3つのヒートマップ、3つのウィジェット、無料のバグトラッキング
  * [OpenReplay.com](https://www.openreplay.com) - バグ再現用の開発者ツール、リアルタイムサポート用のライブセッション、プロダクト分析スイートを備えたオープンソースのセッション再生。すべての機能にアクセス可能で7日間のデータ保持付きで月間1,000セッションまで。
  * [LogRocket.com](https://www.logrocket.com) - 30日間のデータ保持とライブモードで月間1,000セッション
  * [FullStory.com](https://www.fullstory.com) — 1ヶ月のデータ保持と3ユーザーシートで月間1,000セッション。詳細は[こちら](https://help.fullstory.com/hc/en-us/articles/360020623354-FullStory-Free-Edition)。
  * [hotjar.com](https://www.hotjar.com/) — サイトごと:月間1,050ページビュー、無制限のヒートマップ、3ヶ月間のデータ保存
  * [inspectlet.com](https://www.inspectlet.com/) — 1ウェブサイトにつき月間2,500セッションまで無料
  * [Microsoft Clarity](https://clarity.microsoft.com/) - 「トラフィック制限なし」、プロジェクト制限なし、サンプリングなしで完全に無料のセッション記録
  * [mouseflow.com](https://mouseflow.com/) — 1ウェブサイトにつき月間500セッションまで無料
  * [mousestats.com](https://www.mousestats.com/) — 1ウェブサイトにつき月間100セッションまで無料
  * [smartlook.com](https://www.smartlook.com/) — Webとモバイルアプリのための無料パッケージ(月間1,500セッション)、3つのヒートマップ、1つのファネル、1ヶ月のデータ履歴
  * [howuku.com](https://howuku.com) — ユーザーインタラクション、エンゲージメント、イベントを追跡。月間5,000訪問まで無料
  * [UXtweak.com](https://www.uxtweak.com/) — 訪問者がウェブサイトやアプリをどのように使用しているかを記録して視聴。小規模プロジェクトは無制限に無料

**[⬆️ 目次に戻る](#table-of-contents)**

## 国際携帯電話番号認証APIとSDK

  * [numverify](https://numverify.com/) — グローバル電話番号の検証と検索用のJSON API。月間100 APIリクエストまで
  * [veriphone](https://veriphone.io/) — グローバル電話番号認証を提供する無料、高速、信頼性の高いJSON API。月間1,000リクエストまで

**[⬆️ 目次に戻る](#table-of-contents)**

## その他

  * [BackgroundStyler.com](https://backgroundstyler.com) - ソーシャルメディアで共有するためのコード、テキスト、画像の美しいスクリーンショットを作成。
  * [BinShare.net](https://binshare.net) - コードやバイナリを作成・共有。Twitter/Facebookの投稿用の美しい画像として、またはチャットやフォーラム用のリンクとして共有可能。
  * [Blynk](https://blynk.io) - IoTデバイスを制御、構築、評価するためのAPIを備えたSaaS。5デバイス、無料クラウド＆データストレージを含む無料開発者プラン。モバイルアプリも利用可能。
  * [Bricks Note Calculator](https://free.getbricks.app/) - 強力な組み込み多行電卓を備えたメモ帳アプリ(PWA)。
  * [Carbon.now.sh](https://carbon.now.sh) - 美しいスクリーンショットのような形式でコードスニペットを作成・共有。通常、Twitterやブログでコードスニペットを美しく共有/表示するために使用。
  * [Code Time](https://www.software.com/code-time) - VS Code、Atom、IntelliJ、Sublime Textなどで時間追跡とコーディングメトリクスを行うための拡張機能。
  * [Codepng](https://www.codepng.app) - ソーシャルメディアで共有するためのソースコードの優れたスナップショットを作成。
  * [CodeToImage](https://codetoimage.com/) - ソーシャルメディアで共有するためのコードやテキストのスクリーンショットを作成。
  * [Cronhooks](https://cronhooks.io/) - 一回限りまたは定期的なwebhookをスケジュール。無料プランでは5つのアドホックスケジュールが可能。
  * [cron-job.org](https://cron-job.org) - オンラインcronジョブサービス。無制限のジョブが無料。
  * [datelist.io](https://datelist.io) - オンライン予約/アポイント管理システム。月5予約まで無料で、1つのカレンダーを含む。
  * [Domain Forward](https://domain-forward.com/) - URLやドメインを転送するためのシンプルなツール。5つのドメインと月20万リクエストまで無料。
  * [Elementor](https://elementor.com) - WordPressウェブサイトビルダー。40以上の基本ウィジェットを含む無料プランあり。
  * [Format Express](https://www.format-express.dev) - JSON / XML / SQLのインスタントオンラインフォーマット。
  * [FOSSA](https://fossa.com/) - サードパーティコード、ライセンスコンプライアンス、脆弱性の拡張可能なエンドツーエンド管理。
  * [Hook Relay](https://www.hookrelay.dev/) - 面倒な作業なしでアプリにwebhookサポートを追加：キューイング、バックオフ付き再試行、ログ記録が提供される。無料プランでは1日100配信、14日間の保持、3つのフックエンドポイントを提供。
  * [http2.pro](https://http2.pro) - HTTP/2プロトコル対応テストとクライアントHTTP/2サポート検出API。
  * [kandi](https://kandi.openweaver.com/) - アプリケーション開発の迅速な開始：コードスニペットとオープンソースライブラリの再利用を通じて、カスタム機能、ユースケース、完全なアプリケーションをより速く構築。
  * [Base64 decoder/encoder](https://devpal.co/base64-decode/) - データのエンコード・デコード用のオンライン無料ツール。
  * [newreleases.io](https://newreleases.io/) - GitHub、GitLab、Bitbucket、Python PyPI、Java Maven、Node.js NPM、Node.js Yarn、Ruby Gems、PHP Packagist、.NET NuGet、Rust Cargo、Docker Hubの新リリースについて、メール、Slack、Telegram、Discord、カスタムwebhookで通知を受け取る。
  * [OnlineExifViewer](https://onlineexifviewer.com/) - GPSロケーションやメタデータを含む写真のEXIFデータをオンラインで即座に表示。
  * [PDFMonkey](https://www.pdfmonkey.io/) - ダッシュボードでPDFテンプレートを管理し、動的データでAPIを呼び出してPDFをダウンロード。月300ドキュメントまで無料。
  * [Pika Code Screenshots](https://pika.style/templates/code-image) - 拡張機能を使用してコードスニペットとVSCodeから美しくカスタマイズ可能なスクリーンショットを作成。
  * [QuickType.io](https://quicktype.io/) - JSON、スキーマ、GraphQLからモデル/クラス/型/インターフェースとシリアライザを素早く自動生成し、任意のプログラミング言語でデータを素早く安全に扱うことができます。JSONを任意の言語の美しい型安全なコードに変換。
  * [RandomKeygen](https://randomkeygen.com/) - アプリケーション、サービス、デバイスを保護するために使用できるランダムに生成されたキーとパスワードを提供するモバイルフレンドリーな無料ツール。
  * [ray.so](https://ray.so/) - コードスニペットの美しい画像を作成。
  * [readme.com](https://readme.com/) - 美しいドキュメントを簡単に作成、オープンソース向けに無料。
  * [redirection.io](https://redirection.io/) - ビジネス、マーケティング、SEO向けのHTTPリダイレクト管理SaaSツール。
  * [redirect.ing](https://redirect.ing/) - サーバーやSSL証明書を管理することなく、高速で安全なドメイン転送。無料プランには10のホスト名と月10万リクエストが含まれます。
  * [redirect.pizza](https://redirect.pizza/) - HTTPSサポート付きのリダイレクトを簡単に管理。無料プランには10のソースと月10万ヒットが含まれます。
  * [ReqBin](https://reqbin.com/) - オンラインでHTTPリクエストを投稿。一般的なリクエストメソッドにはGET、POST、PUT、DELETE、HEADが含まれます。ヘッダーとトークン認証をサポート。リクエストを保存するための基本的なログインシステムを含みます。
  * [Smartcar API](https://smartcar.com) - 車の位置確認、燃料タンク、バッテリーレベル、走行距離計、ドアのロック/アンロックなどを行うためのAPI。
  * [snappify](https://snappify.com) - 開発者が見事な視覚効果を作成できるようにします。美しいコードスニペットから完全な技術プレゼンテーションまで。無料プランには一度に最大3つのスナップと無制限のダウンロード、月5回のAIパワードコード説明が含まれます。
  * [Sunrise and Sunset](https://sunrisesunset.io/api/) - 指定された経度と緯度の日の出と日の入り時刻を取得。
  * [superfeedr.com](https://superfeedr.com/) - リアルタイムPubSubHubbub準拠フィード、エクスポート、分析。カスタマイズが少ない無料プラン。
  * [SurveyMonkey.com](https://www.surveymonkey.com) - オンラインアンケートを作成。結果をオンラインで分析。無料プランでは1つのアンケートにつき10問と100回答まで。
  * [Tiledesk](https://tiledesk.com) - チャットボットと会話アプリを作成。ウェブサイト(ライブチャットウィジェット)からWhatsAppまでオムニチャネルで提供。無制限のチャットボットを含む無料プラン。
  * [Versionfeeds](https://versionfeeds.com) - お気に入りのソフトウェアのリリース用カスタムRSSフィード。プログラミング言語、ライブラリ、または愛用ツールの最新バージョンを1つのフィードで。(最初の3フィードは無料)
  * [videoinu](https://videoinu.com) - スクリーン録画やその他の動画をオンラインで作成・編集。
  * [Webacus](https://webacus.dev) - エンコード、デコード、データ操作のための幅広い無料開発者ツールにアクセス。

**[⬆️ 目次に戻る](#table-of-contents)**

## リモートデスクトップツール

  * [Getscreen.me](https://getscreen.me) - 2デバイスまで無料、セッション数と時間の制限なし
  * [Apache Guacamole™](https://guacamole.apache.org/) - オープンソースのクライアントレスリモートデスクトップゲートウェイ
  * [RemSupp](https://remsupp.com) - オンデマンドサポートとデバイスへの永続的なアクセス(無料で1日2セッション)
  * [RustDesk](https://rustdesk.com/) - 誰でも使えるオープンソースの仮想/リモートデスクトップインフラストラクチャ！
  * [AnyDesk](https://anydesk.com) - 3デバイスまで無料、セッション数と時間の制限なし

**[⬆️ 目次に戻る](#table-of-contents)**

## ゲーム開発

  * [itch.io](https://itch.io/game-assets) - スプライト、タイルセット、キャラクターパックなどの無料/有料アセット。
  * [Gamefresco.com](https://gamefresco.com/) - 世界中のゲームアーティストによる無料のゲームアセットを発見、収集、共有。
  * [GameDevMarket](https://gamedevmarket.net) - 2D、3D、オーディオ、GUIなどの無料/有料アセット。
  * [OpenGameArt](https://opengameart.org) - 音楽、サウンド、スプライト、gifなどのオープンソースゲームアセット。
  * [CraftPix](https://craftpix.net) - 2D、3D、オーディオ、GUI、背景、アイコン、タイルセット、ゲームキットなどの無料/有料アセット。
  * [Game Icons](https://game-icons.net/) - CCBYライセンスで提供されるスタイル可能なSVG/PNGアイコン。
  * [LoSpec](https://lospec.com/) - ピクセルアートやその他の制限のあるデジタルアートを作成するためのオンラインツール、ゲーム用に選択できる多くのチュートリアル/パレットリストを提供
  * [ArtStation](https://www.artstation.com/) - 2D、3D、オーディオ、アイコン、タイルセット、ゲームキットの無料/有料マーケットプレイス。また、アートポートフォリオの展示にも使用可能。
  * [Rive](https://rive.app/community/) - コミュニティアセットと無料プランを使用して独自のゲームアセットを作成。
  * [Poly Pizza](https://poly.pizza/) - 無料の低ポリ3Dアセット
  * [3Dassets.one](https://3dassets.one/) - 8,000以上の無料/有料3Dモデルとテクスチャ作成用のPBRマテリアル。
  * [Kenney](https://www.kenney.nl/assets/) - CC0 1.0 Universalライセンスの無料2D、3D、オーディオ、UIゲームアセット。
  * [Poliigon](https://www.poliigon.com/) - 無料および有料のテクスチャ(可変解像度)、モデル、HDRI、ブラシ。Blenderなどのソフトウェアにエクスポートするための無料プラグインを提供。
  * [Freesound](https://freesound.org/) - 異なるCCライセンスで提供される無料の共同サウンドライブラリ。

**[⬆️ 目次に戻る](#table-of-contents)**

## その他の無料リソース

  * [Wikimint Developer](https://developer.wikimint.com/p/tools.html) - CSSの圧縮/非圧縮、画像最適化、画像リサイズ、大文字小文字変換、CSS検証、JavaScript コンパイル、HTMLエディタなど、Web開発者向けの常に無料のツール。
  * [ElevateAI](https://www.elevateai.com) - 毎月最大200時間の音声文字起こしを無料で利用可能。
  * [get.localhost.direct](https://get.localhost.direct) - サブドメインサポート付きのローカル開発用の改良された`*.localhost.direct`ワイルドカードパブリックCA署名SSL証明書
  * [Framacloud](https://degooglisons-internet.org/en/) - フランスの非営利団体[Framasoft](https://framasoft.org/en/)によるフリー/リブレオープンソースソフトウェアとSaaSのリスト。
  * [github.com — FOSS for Dev](https://github.com/tvvocold/FOSS-for-Dev) - 開発者向けの無料およびオープンソースソフトウェアのハブ。
  * [GitHub Education](https://education.github.com/pack) - 学生向けの無料サービスコレクション。登録が必要。
  * [Markdown Tools](https://markdowntools.com) - HTML、CSV、PDF、JSON、Excelファイルをマークダウンに、またはマークダウンからこれらの形式に変換するツール
  * [Microsoft 365 Developer Program](https://developer.microsoft.com/microsoft-365/dev-program) - Microsoft 365プラットフォーム向けのソリューションを構築するために必要な無料のサンドボックス、ツール、その他のリソースを入手。サブスクリプションは90日間の[Microsoft 365 E5 Subscription](https://www.microsoft.com/microsoft-365/enterprise/e5)(Windowsを除く)で更新可能。開発活動がある場合(テレメトリデータとアルゴリズムで測定)に更新されます。
  * [Pyrexp](https://pythonium.net/regex) - 正規表現をデバッグするための無料のウェブベースの正規表現テスターと可視化ツール。
  * [RedHat for Developers](https://developers.redhat.com) - RHEL、OpenShift、CodeReadyなどのRed Hat製品への無料アクセスを開発者専用に提供。個人プランのみ。参考用の無料電子書籍も提供。
  * [smsreceivefree.com](https://smsreceivefree.com/) - 無料の一時的な使い捨て電話番号を提供。
  * [sandbox.httpsms.com](https://sandbox.httpsms.com) - テストSMSの送受信を無料で行うことが可能。
  * [SimpleBackups.com](https://simplebackups.com/) - サーバーとデータベース(MySQL、PostgreSQL、MongoDB)のバックアップ自動化サービスで、クラウドストレージプロバイダー(AWS、DigitalOcean、Backblaze)に直接保存。1バックアップの無料プランを提供。
  * [SnapShooter](https://snapshooter.com/) - DigitalOcean、AWS、LightSail、Hetzner、Exoscale向けのバックアップソリューションで、s3ベースのストレージへの直接データベース、ファイルシステム、アプリケーションバックアップをサポート。1リソースの日次バックアップを含む無料プランを提供。
  * [Themeselection](https://themeselection.com/) - 選りすぐりの高品質で、モダンなデザイン、プロフェッショナルで使いやすい無料の管理ダッシュボードテンプレート、HTMLテーマ、UIキットでアプリケーションをより速く作成！
  * [Web.Dev](https://web.dev/measure/) - ウェブサイトのパフォーマンスを確認し、検索エンジンでより上位にランクされるようSEOを改善できる無料ツール。
  * [SmallDev.tools](https://smalldev.tools/) - 様々な形式のエンコード/デコード、HTML/CSS/Javascriptの圧縮、整形、JSON/CSVなどの形式でのフェイク/テストデータセットの生成など、多くの機能を備えた開発者向けの無料ツール。魅力的なインターフェースを提供。
  * [UseCSV by Layercode](https://layercode.com/usecsv) - 数分でウェブアプリにCSVとExcelのインポート機能を追加。ユーザーに楽しく堅牢なデータインポート体験を提供。クレジットカード情報なしで無料で始められ、今すぐUseCVSを統合できます。無制限のインポーターを作成し、100Mbまでのファイルをアップロードできます。
  * [Buttons Generator](https://markodenic.com/tools/buttons-generator/) - プロジェクトで使用できる100以上のボタン。
  * [WrapPixel](https://www.wrappixel.com/) - Angular、React、VueJs、NextJS、NuxtJSで作成された高品質の無料およびプレミアム管理ダッシュボードテンプレートをダウンロード！
  * [Utils.fun](https://utils.fun/en) - ブラウザの計算能力に基づくすべてのオフラインの日常開発ツール。透かし生成、画面録画、エンコード/デコード、暗号化/復号、コードフォーマットなどを含み、完全に無料で、データをクラウドに処理のためにアップロードすることはありません。
  * [It tools](it-tools.tech) - IT分野で働く開発者や人々のための便利なツール。
  * [Free Code Tools](https://freecodetools.org/) - 100%無料の効果的なコードツール。マークダウンエディタ、コード圧縮/整形、QRコード生成、Open Graph生成、Twitterカード生成など。
  * [regex101](https://regex101.com/) - 正規表現(regex)のテストとデバッグができる無料のウェブサイト。正規表現エディタとテスター、および正規表現を学ぶための役立つドキュメントとリソースを提供。
  * [Kody Tools](https://www.kodytools.com/dev-tools) - フォーマッタ、圧縮、コンバータを含む100以上の開発ツール。
  * [AdminMart](https://adminmart.com/) - Angular、Bootstrap、React、VueJs、NextJS、NuxtJSで作成された高品質の無料およびプレミアム管理ダッシュボードとウェブサイトテンプレート！
  * [Glob tester](https://globster.xyz/) - globパターンを設計およびテストできるウェブサイト。globパターンを学ぶためのリソースも提供。
  * [SimpleRestore](https://simplerestore.io) - 手間のかからないMySQLバックアップ復元。コードやサーバーなしでMySQLバックアップをリモートデータベースに復元。
  * [360Converter](https://www.360converter.com/) - 動画からテキスト、音声からテキスト、音声認識、リアルタイム音声からテキスト、YouTube動画からテキスト、動画字幕追加の変換に役立つ無料枠のあるウェブサイト。短い動画変換や短いYouTubeチュートリアルの変換に役立つかもしれません:)
  * [QRCodeBest](https://qrcode.best/) - 13のテンプレート、完全なプライバシー、個人ブランディングでカスタムQRコードを作成。トラッキングピクセル、プロジェクト分類、QRCode.Bestでの無制限のチームシートを提供。
  * [PostPulse](https://PostPulseAI.com) - オンラインプレゼンス、SEOとサイトランキングを向上させるために、SEO最適化されたドメインに月次のAI作成投稿を行います。無料プランでは毎月1つの投稿を手動でサイトに公開できます。
  * [PageTools](https://pagetools.co/) - 必要なウェブサイトポリシーの生成、ソーシャルメディアのバイオ、投稿、ウェブページの作成をシンプルなワンクリックインターフェースで支援する、永久に無料のAIパワードツールスイートを提供。
  * [MySQL Visual Explain](https://mysqlexplain.com) - 遅いクエリを最適化するための、理解しやすく無料のMySQL EXPLAIN出力可視化ツール。
  * [Killer Coda](https://killercoda.com/) - Linux、Kubernetes、コンテナ、プログラミング、DevOps、ネットワークを学ぶためのブラウザ内インタラクティブプレイグラウンド
  * [Axonomy App](https://axonomy-app.com/) - クライアントと請求書を作成、管理、共有するための無料ツール。月10件の無料請求書。

**[⬆️ 目次に戻る](#table-of-contents)**

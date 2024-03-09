# 職務経歴書

## 基本情報

| 項目     | 内容 |
| -------- | ------------- |
| 氏名     | 石川　透（Ishikawa Toru）|
| 居住地   | 東京都杉並区 |
| 最終学歴 | 東京理科大学理工学部 |
| GitHub   | <a href="https://github.com/1shikawa" target="_blank"><img alt="Github" src="https://img.shields.io/badge/1shikawa-%2312100E.svg?&style=flat-square&logo=Github&logoColor=white" /></a> |


## 概要

- クラウドインフラの設計・構築管理、CI/CDを含むDevOps推進が現在の専門です。\
  (元々はWindows系のエンジニアでしたが、現在はLinuxプラットフォームでの開発運用がメインです。)
- 小規模〜中規模サービスの新規開発フェーズや、サービスのリプレイスフェーズにおいて価値提供できると考えています。その過程ではクラウドのマネジメントサービスや周辺エコシステムの活用や自動化を推進することで、開発生産性向上や運用効率化に貢献したいと思います。


## 保有スキル
実務経験のある技術やツールなどを記載しています。

| カテゴリ           | 技術スタック                                                 | 主な役割/担当業務                                                             |
| ------------------ | ------------------------------------------------------------- | ----------------------------------------------------------------------- |
| クラウド           | AWS<br>VPC \| S3 \| CloudFront \| Lambda \| ELB \| EC2 \| EFS \| ECR \| ECS \| Fargate \| EKS(Kubernetes) \| App Runner \| Route53 \| ACM \| IAM \| RDS(MySQL\|PostgreSQL) \| Aurora \| Aurora Serverless V2 \| DynamoDB \| Kinesis firehose \| SQS \| SNS \| SES \| CloudFormation \| CloudWatch \| SSM \| EventBridge \| Backup \| CloudTrail \| AWS Config \| GuardDuty \| Security Hub \| KMS \| Secrets Manager \| Parameter Store \| VPC Peering \| VPC Lattice               | クラウドアーキテクチャ設計<br>クラウドインフラ構築・運用管理 |
| インフラのコード化(IaC)、構成管理     | Terraform \| AWS CloudFormation \| Ansible \| Chef | dev/stg/prod環境の構築と切り分け管理 |
| CI/CD | GitLab CI/CD \| GitHub Actions \| ArgoCD \| Screwdriver \| Ansible AWX | Self Hosted RunnerによるCI/CD基盤の構築<br>CI/CDパイプラインの設計・構築・運用|
| モニタリング、オブザーバビリティ | Prometheus \| Grafana \| NewRelic \| Amazon CloudWatch \| ELK (Elasticsearch,Logstash,Kibana) \| Fluentd \| Fluent Bit \| Zabbix \| Redash | 監視環境の設計・構築<br>ログ収集と分析基盤の構築 |
| 言語、フレームワーク等 | Python(Flask,Django) \| Go(Gin) \| Bash Script | 自動化スクリプト作成・運用<br>バッチアプリ作成<br>WebAPI作成 |
| DB | MySQL \| PostgreSQL \| Oracle \| SQL Server \| SAS | 設計構築・運用管理 |
| 開発ツール | Docker \| Kubernetes(Helm,Helmfile,Kustomize,k9s,krew) \| LocalStack \| Artifactory \| Trivy \| Yamory | コンテナ化<br>Manifest作成管理<br>コンテナ基盤運用管理 |
| コミュニケーション         | Jira \| Confluence \| Miro \| Slack \| Mattermost \| Chatwork | 課題/プロジェクト管理、ドキュメント共有、ディスカッションなど |


## 職務経歴詳細

### フリーランス（2022/03〜現在）
#### 会計系全社統合マスター管理サービスの新規開発（202３/0１〜04予定）
インフラエンジニア(SRE)として、クラウドネイティブベースの新規プロダクト開発業務に従事。

- **プロジェクト規模：**
    - 6人チームでのアジャイル(スクラム)開発
- **役割：**
    - インフラをメインとした要件定義、機能検討・調査、設計、実装、テスト、レビュー
- **担当業務：**
    - Terraformによる全インフラ環境のコード化と適用
    - AWS(ECS/CloudWatch)とNew Relicのインテグレーションとオブザーバビリティ環境構築
    - あ
    - クロスアカウントアクセス
    - AWS EKSを利用したCI/CD基盤構築と運用管理
    - ブランチ戦略に基づいたCI/CDパイプラインの設計構築と各種運用自動化
    - Golang（Gin）による技術検証およびデモ用Webapp,API作成とコンテナ化
- **環境・技術**
    -  AWS
    -  Kubernetes関連（カスタムオペレーター）
       - GitHub Actions Runner Controller/New Relic
- **その他：**
    - インフラ(SRE)領域のリーディングと他メンバーへの
    - チーム内外に対するCI/CD勉強会の主催、ハンズオン及びQA対応。
- **発揮したバリュー：**
  - GitLab CIやArgoCDについては未経験であったが、機能を速習することで短期間でキャッチアップ。CI/CD環境整備とチーム内外に対するDevSecOps導入推進を主導し、自動化による開発プロセスの改善や開発生産性向上に貢献。\
  また開発プロセス中に脆弱性チェックなどを組み込むことで継続的なセキュリティ対応にも貢献。

#### クラウドインフラをベースとしたCI/CD環境構築とDevOps推進支援（2022/03〜2022/12）
DevOpsエンジニアとしてクラウドネイティブベースの開発、本番環境の構築運用業務に従事。

- **プロジェクト規模：**
    - 平均3〜5人チームでのアジャイル(スクラム)開発
- **役割：**
    - インフラをメインとした要件定義、機能検討・調査、設計、実装、テスト、レビュー
- **担当業務：**
    - Terraformによるインフラのコード化とCI(tfint,tfsec)実装
    - GitLab CI、ArgoCDによるCI/CD基盤構築と運用
    - Prometheus,Alertmanager,Grafanaによるモニタリング基盤構築
    - Promtail,Loki,Grafana、FruentBit,ClouwWatchによるロギング基盤構築
    - Kubernetes(EKS)クラスター構築と開発スクラムチームへの展開
    - アプリケーション構成に基づいたManifest作成と管理、CI(Kubeconform,Polaris)実装
    - DevSecOps（シフトレフト）を意識したGitOpsスタイルのCI/CDパイプライン構築
    - Golang（Gin）による技術検証およびデモ用Webapp,API作成とコンテナ化
- **環境・技術**
    -  AWS
    -  Kubernetes関連（使用ツール、カスタムオペレーター等）
       - ALB Controller/External DNS/External Secrets/GitLab Runner/ArgoCD/Kube-prometheus-stack/Loki-stack/Redash/Velero
- **その他：**
    - DevOps推進活動のリード（課題抽出整理、スケジューリング、タスク実行）。
    - チーム内外に対するCI/CD勉強会の主催、ハンズオン及びQA対応。
- **発揮したバリュー：**
  - GitLab CIやArgoCDについては未経験であったが、機能を速習することで短期間でキャッチアップ。CI/CD環境整備とチーム内外に対するDevSecOps導入推進を主導し、自動化による開発プロセスの改善や開発生産性向上に貢献。\
  また開発プロセス中に脆弱性チェックなどを組み込むことで継続的なセキュリティ対応にも貢献。

### ヤフー株式会社（2021/04〜2022/03）
#### 全社成果物管理プラットフォームの開発、運用管理
DevOpsエンジニアとして、プライベートクラウド基盤ベースの全社成果物管理プラットフォームの開発・運用保守業務に従事。

- **プロジェクト規模：**
    - 平均4〜6人チームでのスクラム開発
- **役割：**
    - 機能検討・調査、設計、実装、テスト、レビュー
- **担当業務：**
    - Terraformによる成果物プラットフォームインフラのコード化
    - AnsibleによるVMインスタンスの構成管理
    - DC移転に伴う成果物プラットフォーム移行対応
    - 他部署からのQA対応
- **環境・技術**
    - OpenStack,Artifactory,Terraform,Docker-compose,MySQL,PostgreSQL,Ansible,Chef,Screwdriver(CI),AWS S3
- **その他：**
- **発揮したバリュー：**
  - DC移転に伴う新環境構築と移行対応により事業継続性とコスト削減に貢献。

### GMOグローバルサイン・ホールディングス株式会社（2016/05〜2021/03）
#### 基幹系業務システム及び周辺システムの開発、運用管理
コーポレートエンジニアとして、オンプレミスベースの基幹系業務システムや周辺システムの開発、運用保守業務に従事。
- **プロジェクト規模：**
    - 平均3〜15人チームでのウォーターフォール開発
- **役割：**
    - 要件定義、機能検討・調査、設計、実装、テスト、レビュー、ベンダー管理等
- **担当業務：**
    - 経理関連業務効率化を図るPython,DjangoによるWebアプリ開発
    - 基幹業務システムと電子契約サービスとの連携機能開発（Asteria,Oracle,MySQL）
    - Ansible/AWXによるCI/CD環境構築と定期メンテナンス作業やデプロイの自動化
    - ElasticStack(ElasticSearch,Kibana,Filebeat)によるログ統合管理基盤構築
    - 在庫管理システムリニューアルに伴う運用保守設計とバックアップ、監視基盤の構築
    - 基幹業務システムのバージョンアップに伴う影響調査分析と実行計画、ベンダー管理
    - 基幹業務システムや周辺システムの運用保守とヘルプデスク対応
- **環境・技術**
    - Windows Server/Linux/VMWare/Python/Django/Bash Script/Java/Tomcat/Weblogic/Docker/MySQL/PostgreSQL/Oracle/SQL Server/Ansible/ElasticSearch/Zabbix/Asteria/Kintone
- **その他：**
    - TCO削減につながる施策の提案と実行。
    - 既存業務の自動化推進を主導。
- **発揮したバリュー：**
  - 電子契約サービスの利用顧客増加による売上拡大に貢献。
  - 既存業務の自動化による属人化解消とオペミス削減、省力化に貢献。
  - 管理対象システム情報を自動同期するシステムを構築し、運用保守業務効率化に貢献。

### 富士ゼロックス株式会社（2005/04〜2015/11）
#### 自社他社ソフトウェア、ハードウェアをベースとした顧客向けシステム提案、開発
顧客対応システムエンジニアとして、様々な業界業種のお客様向けにオンプレミスベースのシステム提案・開発運用業務に従事。
- **プロジェクト規模：**
    - 平均3〜20人チームでのウォーターフォール開発
- **役割：**
    - 要件定義、機能検討・調査、設計、実装、テスト、レビュー、ベンダー管理等
- **担当業務：**
    - 病院向け診療記録管理システムの開発、運用
    - 中央省庁向け統計調査システムの開発、運用
    - 中央省庁向け調査研究に伴うWebシステム開発、運用
    - 総合電機メーカー向け設計業務管理システムの開発、運用
    - 銀行向け融資情報管理システムの開発、運用
    - 製造業・流通業向け図書管理システムの開発、運用
- **環境・技術**
    - Windows Server/VMWare/Java/Tomcat/Seasar/VBA/Oracle/MySQL/PostgreSQL/SAS/自社ソフト
- **その他：**
    - 体系的知識を向上させるため積極的に資格を取得（Oracle,MCP,IPA関連）
- **発揮したバリュー：**
  - ステークホルダー間調整や情報共有を心がけ、手戻りによるスケジュール遅延を防ぎ納期を遵守。
  - 顧客にシステム導入効果や満足度を実感頂き、次案件の継続受注に貢献。

---

## 意欲・興味
- バックエンド・クラウドインフラの新しい技術への興味関心が高く、今後も専門性を深めたいと考えています。
- サービスメッシュ構成のマイクロサービス基盤の構築と運用に興味があります。
- Golangによるバックエンドや基盤コード開発力を向上させたいと思っています。

---
<div style="text-align: right;">
以上
</div>

# 職務経歴書

## 基本情報

| key         | value                                                                       |
| ----------- | --------------------------------------------------------------------------- |
| 氏名        | 西山渉 (Nishiyama Wataru)                                                   |
| Github      | [runble1](https://github.com/runble1)                                       |
| SpeakerDeck | [Wataru Nishiyama](https://speakerdeck.com/runble1)                         |
| LinkedIn    | [Wataru Nishiyama](https://www.linkedin.com/in/wataru-nishiyama-a67362167/) |
| ブログ      | [空想ブログ](https://runble1.com/)                                          |

---

## 大事にしていること

- 開発スピードを落とさないセキュリティの実現
- 人に依存しない、プロダクト・組織に対するセキュリティのシステム化
- システムの実現は基本的にコードで行い、CICD・開発環境の構築など技術的な再現性

## 職務経歴詳細

### 合同会社DMM.com セキュリティ部（2018/05〜現在）

セキュリティ部門にて PCIDSS 環境のセキュリティ監視基盤の構築、AWS, GCP のクラウドセキュリティ監視体制の構築、WAF 導入支援に従事。
少数チームで 100 以上の開発チームへセキュリティアプローチを行うため、システム・ポリシーのコード化、開発者自身がセキュリティをチェックする文化醸成を行い、セキュアな組織作りをリード。

#### AWS セキュリティ監視体制（CSPM)の構築
- **概要**
  - 役割 : プロジェクトリーダー/テックリード
  - 時期 : 2020/01 ~ 現在
  - 規模 : 2〜4 人チーム
  - 技術 : AWS Organizations, GuardDuty, Config Rules, CloudFormation StackSets(service-managed), CircleCI, Github, Slack, JIRA
- **詳細：**
  - AWS 用 CSPM の構築
  - 300 以上の AWS アカウントを監視
  - 5000 以上のセキュリティアラートを解決
  - 70 以上のチームへ交渉、開発者がセキュリティ運用へ参加することを了承
  - AWS セキュリティポリシーの策定
- **その他：**
  - Github/CircleCI の整備
  - AWS セキュリティ勉強会の主催（100 名以上が参加）

AWS のセキュリティ監視体制を整えるうえで、「開発者がセキュリティも面倒を見る」という DMM の開発方針を組み込んだシステム・体制を実現。  
システムはコード化、CICD を整備し構築・運用の負荷を低減。開発部門への交渉は 1 チームづつ行い、計 74 チームにセキュリティ運用に参加いただく了承を得た。  
DMM の開発者がセキュリティに参加する文化を実現。

#### GCP セキュリティ監視体制の構築
- **概要**
  - 役割 : プロジェクトリーダー/テックリード
  - 時期 : 2021/09 ~ 現在
  - 規模 : 1〜2 人チーム
  - 技術 : GCP Security Command Center, NotificationConfig, Manage Resources, Terraform CircleCI, Github, Slack, JIRA
- **詳細：**
  - GCP 用 Cloud Security Posture Management(CSPM) の構築
  - 200 以上の GCP プロジェクトを監視
  - 800 以上のセキュリティアラートを解決
  - 40 以上のチームから開発者がセキュリティ運用へ参加することを了承
  - GCP セキュリティポリシーの策定
  - 800 以上の管轄不明 GCP プロジェクトを削除
- **その他：**
  - Github/CircleCI の整備
  - GCP セキュリティ勉強会の主催（50 名以上が参加）


#### クラウド WAF (AWS/GCP) 導入支援
- **概要**
  - 役割 : プロジェクトリーダー/テックリード
  - 時期 : 2020/01 ~ 現在
  - 規模 : 1〜3 人チーム
  - 技術 : AWS WAF, Cloud Armor, CloudFormation, Terraform
- **詳細：**
  - AWS WAF/Cloud Armor の IaC 化
  - ブロックルールの最適化
  - 7 サービスへの導入支援
- **その他：**
  - 最適化ルールを全開発チームへ共有


#### PCIDSS 基盤構築・保守
- **概要**
  - 役割 : インフラエンジニア、運用オペレータ
  - 時期 : 2018/06 ~ 現在
  - 規模 : 5 人チーム
  - 技術 : Splunk, McAfee NSM(IPS), DeepSecurity, Zabbix, Td-agent, SOC ベンダー
- **詳細：**
  - オンプレミス環境の PCIDSS セキュリティ監視基盤を構築
  - システム監視基盤を構築（LAMP システム）
  - 外部 SOC ベンダー選定・導入
- **その他：**
  - 

### 株式会社DMM.comラボ プラットフォーム開発部
#### 不正アクセス判定システムの開発
- **概要**
  - 役割 : テックリード
  - 時期 : 2014/06 〜 2018/05
  - 規模 : 3〜5 人チームのスクラム開発
  - 技術 : PHP(FuelPHP), Java(Spring Framework), Couchbase, GCP(BigQuery), Redash
- **詳細：**
  - API の開発・保守
  - Git を用いたチーム開発
  - BigQuery/Redash を用いたログ解析基盤の構築
- **その他：**
  - 

#### 不正アクセスログの解析
- **概要**
  - 役割 : アナリスト
  - 時期 : 2014/06 〜 2018/05
  - 規模 : 1 人
  - 技術 : SQL, Jupyter Notebook, Google スプレットシート
- **詳細：**
  - 不正ログイン試行の新パターンの発見
  - 自動分析システムの構築
- **その他：**


#### OS/ミドルウェア脆弱性対応
- **概要**
  - 役割 : プロジェクトリーダ
  - 時期 : 2015/06 ~ 2016/08
  - 規模 : 1 人チーム
  - 技術 : -
- **詳細：**
  - PHP の脆弱性（CVE-2015-4024)
  - OpenSSL の脆弱性 DROWN (CVE-2016-0800)
- **その他：**
  - アプリケーション開発部門とインフラ部門間の調整
  - ビジネス部門への説明
  - 全体の進行

#### Web アプリケーション脆弱性診断
- **概要**
  - 役割 : 診断員
  - 時期 : 2014/06 ~ 2014/12
  - 規模 : 2 人チーム
  - 技術 : AppScan, BurpSuite
- **詳細：**
  - PCIDSS 用セキュリティ監視基盤構築
  - システム監視基盤構築（
  - 外部 SOC ベンダー選定・導入


### 一般財団法人近畿健康管理センター（2011/04〜2014/05）

- PHP/JavaScript を利用した自社 HP の Web アプリケーション改修
- Photoshop/Fireworks を使った自社 HP の Web デザイン業務 
- 社内ヘルプデスク

---

## 保有スキル

- AWS/GCP ネイティブサービスを利用した CSPM の構築
- slackbot の構築
- 不正アクセスの分析
- アジャイル、スクラムの進行補助

---

## 業務外活動

### 勉強会での登壇

- **Architect New World on AWS 2022 (2022/04/14)**
  - [AWSセキュリティガードレールにより開発者がセキュリティ監視するように
なったDMM、課題と今後](https://speakerdeck.com/runble1/awssekiyuriteikatoreruniyorikai-fa-zhe-kasekiyuriteijian-shi-suruyouninatutadmm-ke-ti-tojin-hou-dot-pptx)
- **Security-JAWS【第 23 回】 [AWS Security Roadshow Japan 2021] 特別拡大版 (2021/11/11)**
  - [DMMでAWSセキュリティガードレールを作ったので、開発者がAWSセキュリティをチェックする文化を広げていきたい](https://speakerdeck.com/runble1/dmmdeawssekiyuriteigadoreruwozuo-tutafalsede-kai-fa-zhe-gaawssekiyuriteiwotietukusuruwen-hua-woguang-geteikitai)
- **: お客様事例から学ぶ - AWS における脅威検知と対応**
  - [DMMにおける300アカウント67チームのAWSセキュリティを「開発者」に監視してもらうまでの道のり](https://speakerdeck.com/runble1/dmmniokeru300akaunto67timufalseawssekiyuriteiwo-kai-fa-zhe-nijian-shi-sitemoraumadefalsedao-falseri)


### 表彰

- **DMM 開発 AWARD in 金沢**
  - [“技術の祭典” 再び！『DMM開発AWARD in 金沢』開催！](https://inside.dmm.com/entry/2018/03/16/DMM-developers-award-in-kanazawa)

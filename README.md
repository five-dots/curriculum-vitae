
# 職務経歴書

-   [略歴](https://github.com/five-dots/curriculum-vitae#略歴)
-   [概要](https://github.com/five-dots/curriculum-vitae#概要)
-   [技術・スキル](https://github.com/five-dots/curriculum-vitae#技術・スキル)
-   [主な業務経験](https://github.com/five-dots/curriculum-vitae#主な業務経験)

## 略歴

-   **1983 年**: 千葉県に生まれる。その後、静岡県に移住し、大学進学まで静岡で育つ。現在は、東京都品川区在住。
-   **2007 年**: 早稲田大学 政治経済学部 政治学科 卒業。
    -   研究テーマは、日本の選挙制度の計量分析。
    -   コンピューター系のサークルに所属し、Linux サーバー構築・ PC 自作などを楽しむ。
-   **2007 年**: シスコシステムズ株式会社に入社。
    -   約 10 年間、国内の大手通信キャリア向けの営業職として活動。
    -   IP 通信機器・クラウド基盤・セキュリティ・ Web 会議システム・サーバー・ビデオ配信システムなど多様な分野の提案活動を経験。
-   **2016 年**: 自身が代表を務める、法人を設立。
    -   主に米国金融マーケットへの投資事業を展開。
    -   投資戦略の研究過程で、プログラミングとデータサイエンスの領域と出会い、その面白さに魅了される。
    -   現在は、データサイエンティスト兼エンジニアとして、モデル開発やデータ基盤の整備、発注システムの開発などを行う。
    -   今後は、金融領域に限らず、実業界に蓄積されたデータ分析を通して、自身の価値を世の中に提供できないかを模索中。
-   **five-dots**: フリーランス・データサイエンティスト・エンジニア ([GitHub リポジトリ](https://github.com/five-dots?tab=repositories) | [Blog](https://objective-boyd-9b8f29.netlify.app/) | [Qiita](https://qiita.com/five-dots) | [Kaggle](https://www.kaggle.com/shasai))

## 概要

-   [ **フルスタック** ] データの収集・取得から、前処理、特徴量設計、モデル構築、クラウド環境利用、パフォーマンスチューニングと評価、レポーティングやダッシュボード開発までのデータ分析プロジェクトのフローを完結可能です。

-   [ **多様な分析手法** ] 金融マーケットのデータ分析を主戦場としてきましたので、他変量の線形モデルや時系列モデルを得意としていますが、一般的なテーブルデータへの統計的な解析、機械学習のモデリングやパフォーマンスチューニングにも知見があります。

-   [ **分析のコード化** ] アドホックなデータ分析などの「アナリスト」的な業務だけでなく、分析タスクをコード化していく「エンジニア」寄りのタスクに強みがあります。

-   [ **R 言語のプロフェッショナル** ] 分析用には、R 言語をメインで利用しており、CRAN パッケージを含む複数のパッケージを開発しています。実際のコードからコーディング能力を確かめたい場合は、 [GitHub リポジトリ](https://github.com/five-dots?tab=repositories) をご覧ください。

-   [ **コミュニケーション力・チームプレイ** ] コーディングやデータ分析業務だけでなく、営業職としての経験を活かした、社内外の多様な部門との協業による案件推進や、 社内外へ向けたプレゼンテーションや顧客との折衝まで対応可能です。

-   [ **その他** ] 英語力は、外資系企業 10 年の経験から、文章の読み書き (技術文書含む) は当然として、メールでの海外部門とのやりとり、多拠点での電話会議、対面での会議主催などの経験があります。また、基本的に、全ての技術を自学自習によって習得してきたため、未知の領域の技術への速習能力と自走能力に自信がございます。

## 技術・スキル

### プログラミング言語と分析手法

-   R 言語
    -   現在、データ分析では主に利用している言語
    -   主に金融時系列データなどの高頻度データの分析経験 (数億件のデータ)
    
    -   R パッケージを多数開発
        -   [ `{ml4e}` ](https://github.com/five-dots/ml4e): Machine Learning for Everyone (機械学習プロジェクトを簡素化するメタパッケージ)
        -   [ `{Dict}` ](https://github.com/five-dots/Dict): R6 による Dictionary データ構造を実装した [CRAN](https://cran.r-project.org/web/packages/Dict/index.html) パッケージ
        -   その他 [リポジトリ](https://github.com/five-dots) を参照
        -   `{testhat}` を利用したユニットテストや Defensive Programming の技術
    
    -   `{tidyverse}` などのモダンなパッケージを使ったデータのインポート・前処理・可視化などの一連の処理に精通
        -   経験した技術ノウハウ・パッケージの利用方法についての技術記事を自身の [notes リポジトリ](https://github.com/five-dots/notes) で公開
    
    -   主要な機械学習モデル・ライブラリを経験
        -   回帰モデル・時系列モデル・ GBDT など Tree 系モデル・ニューラルネットワークなど
        -   習得したモデル構築の知見を [ `{ml4e}` ](https://github.com/five-dots/ml4e) パッケージに展開中
            -   2020 年 5 月現在で 12 パッケージを収録
            -   `{glment}`, `{kernlab}`, `{kknn}`, `{rpart}`, `{ranger}`, `{extraTrees}`, `{RGF}`, `{xgboost}`, `{lightgbm}`, `{catboost}`, `{keras}`
    
    -   Rmarkdown, Jupyter notebook, Emacs org-mode を利用した Reproducible なレポート作成経験
    -   その他
        -   Shiny を利用したデータ可視化のためのダッシュボード構築の経験
        -   R からの REST API を利用したデータ収集の経験
        -   Web クローラーによるデータ収集の経験



-   Python
    -   R 言語では、カバーしにくい領域の開発に利用 (ディープラーニング や Web アプリケーション)
    -   Zappa + AWS + Flask を利用したサーバーレスアプリケーションとして API を開発
    -   TensorFlow, PyTorch に関しては、若干の経験
    -   R と同等のレベルで分析に利用できるように猛勉強中



-   SQL
    -   分析用クエリや Web アプリケーションのバックエンドとしてのクエリ作成経験
    -   RDBMS: PostgreSQL (+Redshift), MySQL, SQL Server, SQLite
    -   R 言語から `{dplyr}`, `{dbplyr}` を使ったデータベースからのデータ抽出



-   Stan
    -   主に金融時系列データの分析に利用
    -   R や Python の既存パッケージでは表現できないような複雑な階層型のベイズモデルの開発に利用



-   C#
    -   主にアルゴトレーディング戦略の開発言語として利用
    -   その他
        -   VSTO を利用した Excel アドイン開発
        -   WPF/XAML を利用したデスクトップアプリケーション開発
        -   HtmlAgilityPack を利用したクローラー開発
        -   EntitiyFramework を利用したデータベースアプリケーション開発



-   その他 (上記の言語ほどではないが、基本的な理解のあるもの)
    -   Shell Script, Emacs Lisp

### クラウド基盤

-   GCP
    -   R 言語を利用したデータ分析を分散化・高速化するために Compute Engine と Cloud Storage を利用
    -   Google Could SDK とシェルスクリプトを利用した GCP 上での高負荷データ分析タスクの自動化
    -   BigQuery の多少の経験



-   AWS
    -   API Gateway + Lambda + RDS でのサーバーレスアプリケーションの構築経験
    -   その他、EC2, S3, VPS の知見

### 開発環境

-   OS/Editor
    -   Linux: 現在、メインの開発環境として Ubuntu を利用
    -   MacOS: サブとして利用 (基本的に Linux と同等の環境を整備)
    -   Windows: 現在は積極的に利用していないが、過去に Visual Studio + C# + .NET framework での開発を経験
    -   全ての言語の開発環境として Emacs を利用



-   その他
    -   Git + Github を使ったソース管理
    -   Docker/Docker Compose を使った開発環境の構築
    -   CI, CD
        -   自身のレポジトリ向けに簡易的に TravisCI を利用した経験あり
    -   `{lintr}` などの静的解析ツールの利用

### 今後強化していきたい領域・関心のある領域

-   C++
-   ディープラーニングによる画像認識, 自然言語処理
-   Spark などの大規模並列処理
-   Cloud AutoML などのクラウド基盤

## 主な業務経験

### 機械学習プロジェクトのためのメタパッケージ開発 (R)

【業務内容と技術要素】

-   データ分析における「属人的なノウハウ」を誰にでも利用可能・再現可能にするためのパッケージを開発
-   R 言語を利用し、パッケージを開発 (現在はアルファ版のステージ)
-   機械学習プロジェクトの複雑なパラメタを管理し、クロスバリデーション〜アンサンブルまでを行う
-   実際には、以下の項目をパラメタとして管理し、ベストモデルの選定からスタッキングまでをサポート
    -   [ **データセット** ] 同一タスクでも特徴量の異なるデータセットを複数入力可能
    -   [ **モデル** ] 主要な教師あり機械学習モデルパッケージへの対応
    -   [ **パイパーパラメタ** ] モデル毎に取り得るパラメタの範囲のベストプラクティスの事前設定と実際の探索アルゴリズムパッケージを内部で利用可能 (グリッドサーチ・ランダムサーチ・ベイズ最適化)
    -   [ **前処理手法** ] モデル毎に必要な前処理手法のベストプラクティスの調査と実装
    -   [ **リサンプル手法** ] クロスバリデーションのための複数のリサンプル手法に対応
    -   [ **乱数シード** ] 同一モデルで乱数だけを変更したアンサンブルに対応
-   プロジェクト毎の重複作業を削減し、かつ検討漏れもなくしていくことが可能

### 機械学習分析結果のダッシュボード開発 (R/Python)

【業務内容と技術要素】

-   R + Shiny を利用したダッシュボード (フロント) 開発
-   Zappa (Python + Flask + AWS API Gateway + Lambda + RDS) を利用したサーバーレスでの機械学習 Web API の整備
-   日次の分析タスクを GCP の Compute Engine を利用してオフロード

### 投資アルゴリズムの調査・研究・開発 (R/Python)

【業務内容と技術要素】

-   R, Ptyhon を利用した投資アルゴリズムの調査研究業務
-   海外ジャーナル・書籍・ Web ・ Kaggle などの調査研究
-   主に R を使った、探索的なデータ解析 (EDA) とバックテストの経験
-   時系列クロスバリデーション手法等を利用した、過学習に陥らない評価手法

### 米国 ETF (上場投資信託) のポートフォリオ構築プラットフォーム (R/Stan/C#)

【業務内容と技術要素】

-   R + Stan で時系列モデルを構築し、収益率とボラティリティ (変動幅) の予測モデルを構築
-   古典的な ARMA モデルから、階層ベイズモデル、マルコフ転換モデルなどの様々なモデルを実装
-   ボラティリティ予測は、GARCH, GJR, eGARCH など複数のモデルを実装
-   予測された収益率とボラティリティをベースに CCC, DCC, Copula などの手法を利用して最適な資産配分を決定
-   C# で 証券会社の API に接続し、推定された資産配分になるようオーダー処理を実装し、自動でリバランスを実施
-   日々のパフォーマンスをトラッキングし、分析レポートを RMarkdown で自動生成

### 米国マーケットデータ基盤の構築 (C#)

【業務内容と技術要素】

-   Entity Framework + Miscrosoft SQL Server を利用した自社のデータ基盤構築 (数千万件レベル)
-   将来のデータ種別の追加や要件に変更に備えたテーブル設計
-   パフォーマンス向上のための、カラムストアインデックスの調査 (実際には導入せず)
-   外部のデータベンダー の API との接続モジュールを C# で開発
-   C# + HtmlAgilityPack を利用した
-   バッチスクリプトの開発とジョブ管理

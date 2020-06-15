
# 職務経歴書

## 略歴

-   1983 年: 千葉県に生まれる。その後、静岡県に移住し、大学進学まで静岡で育つ。現在は、東京都品川区在住。
-   2007 年: 早稲田大学政治経済学部政治学科卒業。
    -   学生時代は、コンピューター系のサークルに所属し、Linux サーバー構築・ PC 自作などを楽しむ。
-   2007 年: 新卒としてシスコシステムズ株式会社に入社。
    -   約 10 年間、国内の大手通信会社向けの営業職として活動。
    -   IP 通信機器・クラウド基盤・セキュリティ・ Web 会議システム・サーバー・ビデオ配信システムなど多様な分野の提案活動を経験。
-   2016 年: 自身が代表を務める、法人を設立。
    -   主に米国金融マーケットへの投資事業を展開。
    -   投資戦略の研究過程で、プログラミング言語とデータサイエンスの領域と出会い、その面白さに魅了される。
    -   現在は、日本の実業界に蓄積されたデータ分析を通して、自身の価値を世の中に提供できないかを模索中。

-   [GitHub リポジトリ](https://github.com/five-dots?tab=repositories) | [Blog](https://objective-boyd-9b8f29.netlify.app/) | [Qiita](https://qiita.com/five-dots) | [Kaggle](https://www.kaggle.com/shasai)

## 概要

-   金融マーケットのデータ分析を主戦場としてきましたしたので、マクロ経済分析や企業の財務情報分析を得意としていますが、一般的なテーブルデータへの統計的な解析、機械学習のモデリングやパフォーマンスチューニングにも知見があります。

-   データの収集・取得から、前処理、特徴量設計、モデル構築、パフォーマンスチューニングと評価、レポーティングまでのデータ分析フローを完結可能です。

-   アドホックなデータ分析などの「アナリスト」的な業務だけでなく、分析タスクをコード化していく「エンジニア」寄りのタスクに強みがあります。

-   分析用には、R 言語をメインで利用しており、CRAN パッケージを含むいくつかのパッケージを開発しています。実際のコードからコーディング能力を確かめたい場合は [GitHub リポジトリ](https://github.com/five-dots?tab=repositories) をご覧ください。

-   コーディングやデータ分析業務だけでなく、営業職としての経験を活かした、社内外へ向けたプレゼンテーションや顧客との折衝まで対応可能です。

-   英語力は、流暢というレベルではありませんが、外資系企業 10 年の経験から、文章の読み書き (技術文書含む) は当然として、メールでの海外部門とのやりとり、多拠点での電話会議、対面での会議主催などの経験があります。

-   基本的に、全ての技術を自学自習によって習得してきたため、未知の領域の技術への速習能力と自走能力に自信がございます。

## 技術

### プログラミング言語

-   R 言語
    -   現在、データ分析では主に利用している言語
    -   使用経験 約 2 年
    -   主に金融時系列データなどの高頻度データの分析経験
        -   数億件に上る株式ティックデータの分析経験
    
    -   R パッケージを多数開発
        -   [ `{Dict}` ](https://github.com/five-dots/Dict): R6 による Dictionary データ構造を実装した [CRAN](https://cran.r-project.org/web/packages/Dict/index.html) パッケージ
        -   [ `{ml4e}` ](https://github.com/five-dots/ml4e): Machine Learning for Eveyone (機械学習プロジェクトを簡素化するメタパッケージ)
        -   その他 [リポジトリ](https://github.com/five-dots) を参照
        -   `{testhat}` を利用したユニットテストや Defensive Programming の技術
    
    -   `{tidyverse}` などのモダンなパッケージを使ったデータのインポート・前処理・可視化などの一連の処理に精通
        -   経験した技術ノウハウ・パッケージの利用方法についての技術記事を自身の [notes リポジトリ](https://github.com/five-dots/notes) で公開
    
    -   主要な機械学習モデル・ライブラリを経験
        -   回帰モデル・時系列モデル・ GBDT など Tree モデル・ニューラルネットワークなど
        -   習得したモデル構築の知見を [ `{ml4e}` ](https://github.com/five-dots/ml4e) パッケージに展開中
            -   2020 年 5 月現在で 12 パッケージを収録
            -   `{glment}`, `{kernlab}`, `{kknn}`, `{rpart}`, `{ranger}`, `{extraTrees}`, `{RGF}`, `{xgboost}`, `{lightgbm}`, `{catboost}`, `{keras}`
    
    -   Rmarkdown, Jupyter notebook, Emacs org-mode を利用した Reproducible なレポート作成経験
    -   開発環境
        -   Emacs + [ESS](https://ess.r-project.org/index.php?Section=home) をメインで利用
        -   RStudio の利用経験もあり
        -   静的コード解析ツール `{lintr}` を利用したコードの品質向上
    -   その他
    -   R からの REST API を利用したデータ収集の経験
        -   Web クローラーによるデータ収集の経験



-   Python
    -   使用経験 約 1 年
    -   R で程の理解度ではないが、Jupyter Notebook などを利用して基本的な分析が可能なレベル



-   Stan
    -   使用経験 約 1 年
    -   主に金融時系列データの分析に利用



-   C#
    -   使用経験 約 2 年
    -   主にアルゴトレーディング戦略の開発言語として利用
    -   その他
        -   VSTO を利用した Excel アドイン開発
        -   WPF/XAML を利用したデスクトップアプリケーション開発
        -   HtmlAgilityPack を利用したクローラー開発
        -   EntitiyFramework を利用したデータベースアプリケーション開発



-   その他 (上記の言語ほどではないが、基本的な理解のあるもの)
    -   Shell Script, Emacs Lisp

### データベース

-   PostgreSQL, MySQL, SQL Server, SQLite
    -   使用経験 約 2 年
    -   SQL を使った基本的な操作
    -   R 言語から `{dplyr}`, `{dbplyr}` を使ったデータベースからのデータ抽出

### クラウド基盤

-   GCP
    -   R 言語を利用したデータ分析を分散化・高速化するために Compute Engine と Cloud Storage を利用
    -   Google Could SDK とシェルスクリプトを利用した GCP 上での高負荷データ分析タスクの自動化
    -   BigQuery の多少の経験

-   AWS
    -   EC2, Lambda, S3, RDS, VPC の多少の知見

### 開発環境

-   Linux
    -   現在、メインの開発環境として Ubuntu を利用
    -   全ての言語の開発環境として Emacs を利用

-   Mac
    -   サブとして利用
    -   基本的に Linux と同等の環境を整備

-   Windows
    -   現在は利用していないが、過去に Visual Studio + C# + .NET framework での開発を経験
    -   過去に R 言語も Visual Studio + RTVS で開発を実施

-   その他
    -   Git + Github を使ったソース管理
    -   Docker/Docker Compose を使った開発環境の構築
    -   CI, CD
        -   自身のレポジトリ向けに簡易的に TravisCI を利用した経験あり

### 今後強化していきたい領域・関心のある領域

-   C++
-   ディープラーニングによる画像認識, 自然言語処理
-   Spark などの大規模並列処理
-   Cloud AutoML などのクラウド基盤

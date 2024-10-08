### 何者か
- 2019年から福岡にてITエンジニア。 
- 居住地は福岡から絶対離れるつもりはないが、カンファレンスなどで東京に行くことはある。

ここにないその他の詳細プロフィール
https://scrapbox.io/murasame-works/%E8%87%AA%E5%B7%B1%E7%B4%B9%E4%BB%8B

#### 基本情報
|  Key  |  Value  |
| ---- | ---- |
|  名前  |  ムラサメ  |
|  GitHub  |  soundring  |

 ### ✨スキル
|  プログラミング言語  |  年数  |  フレームワーク、ライブラリ  |  備考  |
| ---- | ---- | ---- | ---- |
|  Dart  |  4年  |  Flutter  |    |
|  Ruby  | 5年  |  Rails  |    |
|  JavaScript  | 5年  |  jQuery |  |
|  TypeScript  | 2年  |  React |  |

|   エディタ  |  年数  |  備考  |
| ---- | ---- | ---- |
|  Visual Studio Code	  |  5年  |    |
|  RubyMine	  |  3年  |    |
|  Android Studio |  4年  |    |
|  Xcode  |  4年  |    |

|   DB  |  備考  |
| ---- | ---- |
|  MariaDB |  Rails案件にて使用 |
|  PostgreSQL |  Rails案件にて使用 |
|  Cloud Firestore |  副業のFlutter案件にて使用 |

|   OS  |  備考  |
| ---- | ---- |
|  Windows(XP~最新) |  私的利用  |
|  Mac(Sierra~最新)  |  開発、私的使用  |

|   バージョン管理  |  年数  |
| ---- | ---- |
|  Git |  5年 |
|  GitHub |  5年 |
|  Bitbucket |  4年 |

<details><summary>その他触ったことあるツール等</summary>

- RedMine
- Affinity Designer(iPad)
- Affinity Photo(iPad)
</details>

## 🔭仕事経歴
### ■福岡のIT企業（2019/11~現在）
<details><summary>自社の新規スマホアプリ開発(2020/2~2021/9)</summary>

[担当業務]
- Flutterの技術調査 
- Firebaseの技術調査 
- アプリのアイコン制作(Affinity Designerで制作)
- アプリのフロントエンド開発
- バックエンドのAPI開発
- 総合テスト
- アプリおよびサーバーサイドのリリース作業
- Flutterのアップデート(2.0⇨3.0)
- 状態管理パッケージをproviderからriverpodへ移行

社内にアプリエンジニアがおらず、まずFlutterをインプットからスタート。 
0からリリースまでアプリのフロントエンド開発を全て担当。
バックエンドのAPI開発も一部担当。
当時はFlutterの日本語情報が少なく、問題解決のために英語情報を見に行ったりGitHubのissueを見に行ったりした。

##### ［環境・構成］
- DB：MariaDB
- 言語：Dart、Ruby
- フレームワーク：Flutter、Rails、React
- その他：Docker、AWS(S3)、Firebase Dynamic Links、Firebase Crashlytics、Firebase Cloud Messaging

##### ［メンバー構成／役割］ 
2~3人/メンバー
</details>


<details><summary>自社の既存のWebアプリケーション改修(2021/9~2022/6)</summary>
 
[担当業務]
- 機能追加
- 機能改善
- バグ修正
- 総合テスト

#### 開発例
データの一括で複製(DelayedJob)

##### ［環境・構成］
- DB：MariaDB
- 言語：JavaScript、Ruby
- フレームワーク：Bootstrap3、Backbone.js、Rails
- その他：Docker、AWS EC2

##### ［メンバー構成／役割］ 
最大6人/メンバー
</details>

<details><summary>自社の既存のWeb/スマホアプリケーションのフロントエンド刷新(2022/11/1~2023/07/31)</summary>
 
##### [担当業務]
- Backbone.jsからReactへのフロントエンドの刷新
- Cordovaのアップデート作業(iOS/Android)
- 総合テスト

Cordovaのバージョンが古い影響でアプリのリリースができない状態になっていた。
Cordovaには初めて触れたがFlutterで得たモバイル関係の知識も活用しつつアップデートを行なった。

フロントエンドの環境の刷新も行なった。
状態管理はReact Hooksを使用。

##### ［メンバー構成／役割］ 
3~5人/メンバー

##### ［環境・構成］
- DB：PostgreSQL
- 言語：TypeScript、Ruby
- フレームワーク：Cordova、Backbone.js、React、Rails
- その他：Docker、AWS(EC2/S3/RDS/Amazon SNS/CloudWatch)
</details>

<details><summary>自社の既存のWeb/スマホアプリケーションの機能追加、改修(2023/8/1~)</summary>

##### [担当業務]
- 機能追加
- 機能改善
- バグ修正
- 総合テスト
- リリース作業(サーバ/スマホアプリ)
- プロジェクトリーダー(2024/3~)
  - 部会での進捗報告、週１のチーム内会議の進行、経営側との取り組むタスク等の打ち合わせ
  - 要件定義、設計

#### 開発したもの例
- CSVでの一括ダウンロード機能
- Excelファイルの取り込み機能(Roo使用)
- 使いやすいようにテストデータ(seedファイル)の改修
- ActionCable、Sidekiq、Redisを使用したリアルタイム通信を伴う機能
- rubocopのバージョンアップ & TODOになってるcopに対応
  - 警告件数：3000個くらい
- rubocop-rspecの導入
- rubocop-railsの導入

##### ［メンバー構成／役割］ 
最大４人/メンバー(2024/3〜リーダー)

##### ［環境・構成］
- DB：PostgreSQL
- 言語：TypeScript、Ruby
- フレームワーク：Cordova、React、Rails
- その他：Docker、AWS(EC2/S3/RDS/Amazon SNS/CloudWatch)
</details>



#### 社内文化への貢献
社内勉強会を立ち上げ、5年ほど運営(2020/2-現在　約５０回)

### ■業務委託案件
<details><summary>英語学習アプリの新規開発（2022/1~2023/7）リリース済み</summary>

##### [担当業務]
- アプリ開発全般(仕様打ち合わせ・検討、実装、CI/CD環境構築)
- デザインはデザイナーさんが担当
- 開発だけでなくクライアントさんに技術的なアドバイスなど行う技術顧問的なことも担当。

参画した際に作りかけで動作不十分であったため既存のコードも使いながら0から作り直した。
音声認識(speech_to_text)やテキスト読み上げ(flutter_tts)など、OS依存の機能を使用。
Flutter案件としてはネイティブの機能を使うところが結構珍しいかもしれない。
日本語情報があまりない中での開発経験を得られた。
エンジニアではない社長さんへのヒアリング・提案・説明の経験を得られた。

##### ［環境・構成］
- DB:Firebase Firestore
- 言語 Dart
- フレームワーク: Flutter
- その他:Codemagic、deploygate、Firebase Authentication、Cloud Firestore

##### ［メンバー構成／役割］ 
1人/開発担当
</details>

<details><summary>リリースされた上記英語学習アプリの改修およびメンター的な立ち位置（2023/7~)</summary>
 
##### [担当業務]
基本的に非エンジニアのクライアントさんの技術的な相談にのるメンターをやっている。
</details>

## 👀このさきやってみたいこと
- Webフロント/バックエンドの専門性を深める
- ソフトウェア工学の学習
- 自発的な成長をしたい人の支援(自己学習支援・クリエイター支援など)


<details><summary>仕事に選びにおいて重視するもの・自分の強みを発揮できる環境</summary>

心の安定 > 給与　の価値観

## 1.ワークライフバランス
- フルリモート
- 常にスケジュールかつかつではない
- 焦ることがない環境
- 2時間外出したらその分2時間作業するなど柔軟な働き方

## 2.ポジション
- 偉い人とメンバーの間の調整や集団をまとめるポジションは除く
- 開発メイン

## 3.人間関係
- 質問しやすい環境
- 言い方がきつい人がいない環境
- 雑談する機会がある環境
- 会議などで他人への叱責や言い争いを聞かされないこと

## 4. 開発環境
- デプロイの自動化
- リリース作業に対する心理的負担が少ない
- AIツールの活用(ChatGPT / Github Copilot)
</details>

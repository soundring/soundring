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

## 1.ワークライフバランス
- フルリモート
- 常にスケジュールかつかつではない
- 焦ることがない環境
- 2時間外出したらその分2時間作業するなど柔軟な働き方

## 2.ポジション
- メンバーの間の調整や集団をまとめるポジションは除く
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

<details><summary>English</summary>

### Who Am I
- IT engineer in Fukuoka since 2019.
- Intends to stay in Fukuoka but occasionally travels to Tokyo for conferences.

More details on my profile: [https://scrapbox.io/murasame-works/%E8%87%AA%E5%B7%B1%E7%B4%B9%E4%BB%8B](https://scrapbox.io/murasame-works/%E8%87%AA%E5%B7%B1%E7%B4%B9%E4%BB%8B)

#### Basic Information
|  Key  |  Value  |
| ---- | ---- |
|  Name  |  Murasame  |
|  GitHub  |  soundring  |

### ✨Skills
| Programming Language | Years | Frameworks/Libraries | Notes |
| ---- | ---- | ---- | ---- |
| Dart | 4 years | Flutter |  |
| Ruby | 5 years | Rails |  |
| JavaScript | 5 years | jQuery |  |
| TypeScript | 2 years | React |  |

| Editor | Years | Notes |
| ---- | ---- | ---- |
| Visual Studio Code | 5 years |  |
| RubyMine | 3 years |  |
| Android Studio | 4 years |  |
| Xcode | 4 years |  |

| DB | Notes |
| ---- | ---- |
| MariaDB | Used in Rails projects |
| PostgreSQL | Used in Rails projects |
| Cloud Firestore | Used in side Flutter projects |

| OS | Notes |
| ---- | ---- |
| Windows (XP~Latest) | Personal use |
| Mac (Sierra~Latest) | Development, personal use |

| Version Control | Years |
| ---- | ---- |
| Git | 5 years |
| GitHub | 5 years |
| Bitbucket | 4 years |

<details><summary>Other Tools I've Used</summary>

- RedMine
- Affinity Designer (iPad)
- Affinity Photo (iPad)
</details>

## 🔭 Work Experience
### ■ IT Company in Fukuoka (2019/11~Present)
<details><summary>Development of New Mobile App (2020/2~2021/9)</summary>

[Responsibilities]
- Conducted technology research for Flutter
- Conducted technology research for Firebase
- Created app icons using Affinity Designer
- Frontend app development
- Backend API development
- Comprehensive testing
- Release work for app and server-side
- Updated Flutter (2.0 to 3.0)
- Migrated state management from provider to riverpod

There were no app engineers in-house, so I started by learning Flutter. I was responsible for all frontend development from scratch to release and partially responsible for backend API development. At the time, Japanese resources for Flutter were scarce, so I often referred to English resources and GitHub issues for problem-solving.

##### [Environment/Configuration]
- DB: MariaDB
- Languages: Dart, Ruby
- Frameworks: Flutter, Rails, React
- Others: Docker, AWS (S3), Firebase Dynamic Links, Firebase Crashlytics, Firebase Cloud Messaging

##### [Team Structure/Role]
2-3 members
</details>

<details><summary>Modification of Existing Web Applications (2021/9~2022/6)</summary>

[Responsibilities]
- Feature additions
- Feature improvements
- Bug fixes
- Comprehensive testing

#### Example Development
Bulk data duplication (DelayedJob)

##### [Environment/Configuration]
- DB: MariaDB
- Languages: JavaScript, Ruby
- Frameworks: Bootstrap3, Backbone.js, Rails
- Others: Docker, AWS EC2

##### [Team Structure/Role]
Up to 6 members
</details>

<details><summary>Frontend Overhaul of Existing Web/Mobile Applications (2022/11/1~2023/07/31)</summary>

##### [Responsibilities]
- Overhauled frontend from Backbone.js to React
- Updated Cordova (iOS/Android)
- Comprehensive testing

The app couldn't be released due to the outdated Cordova version. Although new to Cordova, I utilized mobile knowledge gained from Flutter to perform the update. Also refreshed the frontend environment using React Hooks for state management.

##### [Team Structure/Role]
3-5 members

##### [Environment/Configuration]
- DB: PostgreSQL
- Languages: TypeScript, Ruby
- Frameworks: Cordova, Backbone.js, React, Rails
- Others: Docker, AWS (EC2/S3/RDS/Amazon SNS/CloudWatch)
</details>

<details><summary>Feature Additions and Modifications to Existing Web/Mobile Applications (2023/8/1~)</summary>

##### [Responsibilities]
- Feature additions
- Feature improvements
- Bug fixes
- Comprehensive testing
- Release work (Server/Mobile App)
- Project leader (from 2024/3)
  - Progress reporting in departmental meetings, weekly team meetings, tasks with management
  - Requirements definition, design

#### Example Developments
- Bulk download feature via CSV
- Excel file import feature (using Roo)
- Improved test data (seed files) for usability
- Real-time communication features using ActionCable, Sidekiq, Redis
- Upgraded rubocop and addressed TODOs
  - Around 3000 warnings
- Introduced rubocop-rspec
- Introduced rubocop-rails

##### [Team Structure/Role]
Up to 4 members (Leader from 2024/3)

##### [Environment/Configuration]
- DB: PostgreSQL
- Languages: TypeScript, Ruby
- Frameworks: Cordova, React, Rails
- Others: Docker, AWS (EC2/S3/RDS/Amazon SNS/CloudWatch)
</details>

#### Contributions to Company Culture
Started and have been running internal study sessions for about 5 years (2020/2-Present, ~50 sessions)

### ■ Freelance Projects
<details><summary>Development of a New English Learning App (2022/1~2023/7) Released</summary>

##### [Responsibilities]
- Overall app development (specification meetings, implementation, CI/CD setup)
- Design handled by a designer
- Acted as a technical advisor to the client, offering technical guidance

Rebuilt the app from scratch, using some existing code, as it was incomplete and not functioning properly. Used OS-dependent features like speech recognition (speech_to_text) and text-to-speech (flutter_tts). Gained development experience with limited Japanese resources. Acquired experience in client interactions, proposals, and explanations with non-engineering executives.

##### [Environment/Configuration]
- DB: Firebase Firestore
- Language: Dart
- Framework: Flutter
- Others: Codemagic, deploygate, Firebase Authentication, Cloud Firestore

##### [Team Structure/Role]
1 person/Developer
</details>

<details><summary>Maintenance and Mentoring for the Released English Learning App (2023/7~)</summary>

##### [Responsibilities]
Primarily mentoring the non-engineer client on technical consultations.
</details>

## 👀 Things I Want to Try Next
- Deepen expertise in web frontend/backend
- Study software engineering
- Support self-motivated growth (self-learning support, creator support, etc.)

<details><summary>What I Prioritize in Job Selection and Environments Where I Can Excel</summary>

## 1. Work-Life Balance
- Fully remote
- Not constantly on a tight schedule
- Stress-free environment
- Flexible work style, such as working extra hours after a 2-hour break

## 2. Position
- Exclude positions involving coordination or leadership among members
- Focus on development

## 3. Human Relations
- Environment where questions are easily asked
- No harsh communication
- Opportunities for casual conversation
- No exposure to reprimands or disputes in meetings

## 4. Development Environment
- Automated deployment
- Minimal psychological burden for release tasks
- Utilization of AI tools (ChatGPT / GitHub Copilot)
</details>

</details>

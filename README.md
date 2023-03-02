# AboutMe

## 大学 (2016~2020)

### 学部学科

- 九州大学 工学部 電気情報工学科 計算機工学コース (学士)
- GPA: `3.58/4.00` (専攻科目のみ)
- キーワード  
  `アルゴリズム論`,`インターネット`,`オペレーティングシステム`,`コンパイラ`,`コンピュータ・アーキテクチャ`,`コンピュータ・グラフィックス`,`システムLSI`,`セキュリティ`,`ソフトウェア基礎論`,`ソフトウェア工学`,`データベース`,`ニューラルネットワーク`,`パターン認識`,`ヒューマンインタフェース`,`プログラミング言語`,`マルチエージェント`,`マルチメディア`,`自然言語処理`,`ロボティクス`,`機械学習理論`,`データマイニング`,`情報ネットワーク`,`人工知能`,`認知科学`,`並列・分散・協調処理`  
  (引用元: https://www.eecs.kyushu-u.ac.jp/course.html)

### 研究室 (4年次)

- [九州大学 大学院システム情報科学研究院 倉爪・河村研究室 実世界情報ロボティクス](https://robotics.ait.kyushu-u.ac.jp/)
- 研究テーマ: [介護技術定量化のためのウェアラブル全身触覚センサの開発](https://robotics.ait.kyushu-u.ac.jp/kurazume/papers/ROBOMECH20-2.pdf)
- キーワード  
  `Python`,`ROS`,`(布状)触覚センサ`,`モーションキャプチャ`,`触覚グローブ`,`360度カメラ`,`ホロレンズ`

## 42tokyo (2020.10~)

### 概要

- 4週間に及ぶ入学試験Piscine (webテストを含む通算合格率4%) を受験して合格。
- 講師不在のため、ネットで調べたり、他の学生に聞いたりして、課題をこなす。
- 現在のレベルは11.52で、全学生で5位。(2023.3.1 時点)

### プロジェクト一覧

| プロジェクト名  | 概要 | キーワード |
| ----------- | --- | ------- |
| [ft\_printf](https://github.com/Masaya-Kamei/ft_printf)| printfを再実装 <ul><li>変換指定子: `c`,`s`,`p`,`d`,`i`,`u`,`x`,`X`,`%`</li><li>フラグ類: `0`,`*`,`最小フィールド幅`,`精度`</li></ul> | `C`,<br>`コマンドライン引数`,`可変長引数` |
| [ft\_containers](https://github.com/Masaya-Kamei/ft_containers) | C++のコンテナ`vector`,`map`,`stack`を再実装　<ul><li>vector: 動的配列を扱うテンプレートクラス</li><li>map: 連想配列 (AVL木で実装) を扱うテンプレートクラス</li><li>stack: スタックを扱うテンプレートクラス</li></ul> | `C++`,<br>`allocator`,`iterator`,<br>`平衡二分木`,`AVL木`,<br>`テンプレート`,`Google Test` |
| [webserv](https://github.com/Masaya-Kamei/webserv) | HTTP/1.1に準拠したHTTPサーバー (簡易版nginx) <ul><li>I/Oが入出力可能になると発火するイベント駆動型</li><li>シングルスレッド</li><li>対応メソッド: `GET`,`POST`,`DELETE`</li><li>CGI 使用可能</li><li>設定ファイルを読み込み可能</li><li>3人チーム</li></ul> | `C++`,`nginx`,<br>`HTTPリクエスト`,`HTTPレスポンス`,<br>`I/O多重化`,`CGI`,`socket通信`<br>`Google Test`　|
| [ft\_transcendence](https://github.com/Masaya-Kamei/ft_transcendence) | リアルタイムなオンライン対戦ゲーム(Pong)やチャットができるwebアプリ <ul><li>Demo https://transpong-42-mk.com <br> (シークレットウィンドウ or 別ブラウザ使うと2人同時ログイン可能) </li><li>シングルページアプリケーション</li><li>OAuth2を利用した認証</li><li>websocketを使ってリアルタイム通信</li><li>canvasで実装したPongGame</li><li>ゲームのマッチングシステム (ランダム, 招待)</li><li>DB, API 設計 (プロフィール,フレンド,ブロック,チャット,対戦記録など)</li><li>ワンタイムパスワードによる二要素認証</li><li>GithubActionsを使ってCI/CD (AWS ECSにデプロイ)</li><li>5人チーム (全員webアプリの開発は初めて)</li></ul> | `TypeScript`,<br>`React`,`NestJS`,`Vite`,<br>`42API`,`REST API`,<br>`JWT`,`Cookie`,<br>`OAuth2`,`2FA`,`CORS`,<br>`File Upload`,`File Stream`<br>`PostgreSQL`,`Prisma(ORM)`,<br>`Socket.IO`,`canvas`,`Swagger`,<br>`docker compose`,`nginx`,<br>`CI/CD`,`Github　Actions`,<br>`Jest`,`Cypress`,<br>`AWS ECS`,`AWS ECR`,<br>`AWS Route53`,`ACM` |


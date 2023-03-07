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

| プロジェクト名 | 概要 | キーワード |
| ----------- | --- | ------- |
| C言語 |
| [ft\_printf](https://github.com/Masaya-Kamei/ft_printf) | printfを再実装 <ul><li>変換指定子: `c`,`s`,`p`,`d`,`i`,`u`,`x`,`X`,`%`</li><li>フラグ類: `0`,`*`,`最小フィールド幅`,`精度`</li></ul> | `C`,<br>`可変長引数` |
| [philosophers](https://github.com/Masaya-Kamei/philosophers) | [食事する哲学者の問題](https://ja.wikipedia.org/wiki/%E9%A3%9F%E4%BA%8B%E3%81%99%E3%82%8B%E5%93%B2%E5%AD%A6%E8%80%85%E3%81%AE%E5%95%8F%E9%A1%8C)を題材にした並列処理に関する問題 <ul><li>哲学者の位置により右手か左手を優先する解法で実装</li><li>マルチスレッド、マルチプロセス</li><li>ミューテックスやセマフォによる排他制御</li></ul> | `C`,<br>`マルチスレッド`,<br>`マルチプロセス`,<br>`ミューテックス`,`セマフォ`,<br>`デッドロック` |
| [minishell](https://github.com/Masaya-Kamei/minishell) | bashの再実装 <ul><li>多段パイプ (`\|`)</li><li>リダイレクト,ヒアドキュメント (`>`,`<`,`>>`,`<<`)</li><li>$PATHにあるコマンド実行</li><li>ビルトイン関数(`echo`,`cd`,`pwd`,`export`,`unset`,`env`,`exit`)</li><li>クォーテーション(`'`,`"`)</li><li>環境変数のセットや展開</li><li>シグナルハンドル,EOF (`Ctrl+C`,`Ctrl+\`,`Ctrl+D`)</li><li>2人チーム</li></ul> | `C`,<br>`構文解析`,`マルチプロセス`,<br>`ファイルディスクリプタ`,<br>`パイプ`,`リダイレクト`,<br>`環境変数`,<br>`シグナルハンドリング` |
| 3D |
| [fdf](https://github.com/Masaya-Kamei/fdf) | 等角投影を使った3Dプロジェクション<ul><li>デモ動画: [fdf #demo -github](https://github.com/Masaya-Kamei/fdf#demo)</li><li>平行投影の一種である等角投影を実装</li><li>マップの回転やズームが可能</li><li>3次元の点をxy平面に正射影して基底変換する</li></ul> | `C`,<br>`3Dプロジェクション`,<br>`平行投影`,`等角投影`,<br>`ベクトル`,`正射影`,<br>`基底変換`,`軸周りの回転` |
| [term3d](https://github.com/Masaya-Kamei/term3d) | 透視投影を使った3Dプロジェクション<ul><li>デモ動画: [term3d #demo -github](https://github.com/Masaya-Kamei/term3d#demo)</li><li>透視投影を実装</li><li>等角投影法に加えてz値で割ることで奥行きを表現</li></ul> | `C`,<br>`3Dプロジェクション`,<br>`透視投影`,<br>`ベクトル`,`正射影`,<br>`基底変換`,`軸周りの回転` |
| [cub3d](https://github.com/Masaya-Kamei/cub3d) | レイキャスティングで実装した初期のFPSゲーム <ul><li>デモ動画: [cub3d #demo -github](https://github.com/Masaya-Kamei/cub3d#demo)</li><li>壁で囲まれたマップを自由に移動できる</li><li>障害物を設置できる</li><li>ゲーム画面をbmpで保存できる</li><li>設定ファイルでマップや画像などが設定できる</li><li>2次元のマップ上でプレイヤーの向きの一定範囲に<br>光線を飛ばして壁にぶつかったときの距離で<br>描写する壁の高さを決定して縦線1本引く</li></ul> | `C`,<br>`レイキャスティング`,<br>`ベクトル`,`内積`,<br>`bmp` |
| アセンブリ |
| [libasm](https://github.com/Masaya-Kamei/libasm) | アセンブリ言語でCの関数を再実装 <ul><li>メモリ、スタック、レジスタを使って操作</li><li>システムコールを呼ぶ</li><li>スタックフレームを用いてローカル変数を管理</li><li>メモリアライメントを意識</li></ul> | `アセンブリ言語`,<br>`メモリ`,`レジスタ`,<br>`スタック`,`スタックフレーム`,<br>`メモリアライメント`,<br>`セクション`,`システムコール`,<br>`x86-64`,`呼出規約` |
| インフラ |
| [netpractice](https://github.com/Masaya-Kamei/netpractice) | 小規模なネットワークを構成するクイズ <ul><li>アドレスクラスではなくCIDRで構成</li><li>スイッチとルーターを扱う</li><li>アドレスのレンジがかぶらないように設計する</li></ul> | `ネットワーク`,`IP`,<br>`CIDR`,`サブネットマスク`,<br>`スイッチ`,`ルーター`,<br>`ルーティングテーブル` |
| [inception](https://github.com/Masaya-Kamei/inception) | docker composeを使ったLEMP環境の構築　<ul><li>`nginx` <--> `wordpress+php-fpm` <--> `mariadb`</li><li>Dockerイメージはすべて`Alpine Linux`を使用</li><li>Docker volume を使用してデータ永続化</li></ul> | `docker compose`,<br>`alpine`,`nginx`,<br>`wordpress`,`php-fpm`,<br>`MariaDB`,`adminer`,<br>`redis` |
| [ft_services](https://github.com/Masaya-Kamei/ft_services) | kubernetesを使って複数のマイクロサービスを立ち上げる <ul><li>Dockerイメージはすべて`Alpine Linux`を使用</li><li>minikubeで単一ノードのKubernetes環境を構築</li><li>MetalLBでPodにアクセスを振り分ける</li><li>k8s のPod, Deployment, Serviceなどを使用</li><li>LEMP環境, phpmyadmin, FTPサーバーを構築</li><li>Telegraf, InfluxDB, Grafanaでメトリクスを収集, 可視化</li></ul> | `kubernetes`,`docker`,<br>`minikube`,`MetalLB`,<br>`alpine`,`nginx`,<br>`wordpress`,`mysql`,<br>`phpmyadmin`,`ftps`,<br>`Telegraf`,`InfluxDB`,<br>`Grafana` |
| C++ |
| [ft\_containers](https://github.com/Masaya-Kamei/ft_containers) | C++のコンテナ`vector`,`map`,`stack`を再実装　<ul><li>vector: 動的配列を扱うテンプレートクラス</li><li>map: 連想配列 (AVL木で実装) を扱うテンプレートクラス</li><li>stack: スタックを扱うテンプレートクラス</li></ul> | `C++`,<br>`allocator`,`iterator`,<br>`平衡二分木`,`AVL木`,<br>`Google Test` |
| [webserv](https://github.com/Masaya-Kamei/webserv) | HTTP/1.1に準拠したNginxライクなHTTPサーバー <ul><li>シングルスレッドで、I/O(`socket`,`file`) が<br>入出力可能になると発火するイベント駆動型</li><li>HTTPリクエストを解析して、HTTPメソッドを実行し、<br>HTTPレスポンスを作成して送る</li><li>対応メソッド: `GET`,`POST`,`DELETE`</li><li>CGI 使用可能</li><li>設定ファイルを読み込み可能</li><li>3人チーム</li></ul> | `C++`,`nginx`,<br>`HTTPリクエスト`,<br>`HTTPレスポンス`,<br>`I/O多重化`,`CGI`,<br>`socket通信`,<br>`Google Test`　|
| webアプリ |
| [ft\_transcendence](https://github.com/Masaya-Kamei/ft_transcendence) | オンライン対戦ゲームやチャットができるwebアプリ <ul><li>デモサイト: https://transpong-42-mk.com <br> (シークレットウィンドウ or 別ブラウザを使うと、<br>&nbsp;&nbsp;複数ユーザーでログイン可能) </li><li>React + NestJS</li><li>OAuth2を利用した認証</li><li>ワンタイムパスワードによる二要素認証</li><li>websocketを使ってリアルタイム通信</li><li>オンライン2人対戦ゲームPong</li><ul><li>他のユーザーは観戦できる</li><li>マッチングシステム (ランダム, 招待)</li></ul><li>チャットルーム</li><ul><li>パスワード付きの部屋を作れる</li><li>メンバーをBan,Muteなどできる</li></ul><li>DB, API 設計</li><ul><li>プロフィール,フレンド,チャット,対戦記録など</li></ul><li>docker compose CLI を使ってAWS ECS にデプロイ</li><li>GithubActionsを使ってCI/CD</li><li>5人チーム (全員webアプリの開発は初めて)</li></ul> | `TypeScript`,<br>`React`,`NestJS`,`Vite`,<br>`42API`,`REST API`,<br>`JWT`,`Cookie`,<br>`OAuth2`,`2FA`,`CORS`,<br>`File Upload`,<br>`File Stream`,<br>`PostgreSQL`,`Prisma`,<br>`Socket.IO`,`canvas`,<br>`Swagger`,<br>`docker compose`,<br>`nginx`,<br>`CI/CD`,`Github　Actions`,<br>`Jest`,`Cypress`,<br>`AWS ECS`,`AWS ECR`,<br>`AWS Route53`,`ACM` |

# アプリケーション名

モンハンお悩み相談アプリ　(MonhunTroubleshooting_app)

# アプリケーション概要

モンスターハンターの作品をプレイし始めた初心者を中心とした、ユーザー同士でお悩みを投稿し、それに対してのアドバイスをコメントとして投稿できるアプリ。

また、お気に入りのスクリーンショットの投稿もでき、それを見たユーザーもコメントを投稿できる。

# お悩み投稿の方法

1,トップページのヘッダーからユーザー新規登録ができる。

２,トップページ上部のお悩みを投稿するためのボタンがあるので、そこをクリックする。
3,お悩み投稿ページで、お悩み内容(タイトル・詳細)を入力し、投稿ボタンをクリックし、投稿する。
4,トップページのお悩み一覧から、投稿されたお悩みをクリックし、お悩みの詳細を確認する。
5,お悩み詳細ページにて、それについてのアドバイスをコメント投稿欄に入力し、投稿する。

# お気に入りスクリーンショットの投稿方法

1,トップページのヘッダーからユーザー新規登録ができる。
※すでに新規登録が済んでいれば、ヘッダーにログインボタンがあるので、そこをクリックしメールアドレス・パスワードを入力し、ログインする。
２,トップページ上部に、投稿されたお気に入りスクリーンショットの一覧ページへ遷移するためのボタンがあるので、そこをクリックする。
3,スクリーンショットの一覧ページ上部に、投稿ページへに遷移するためのボタンがあるので、そこをクリックする。
4,投稿したいスクリーンショットのファイルを指定し、説明を入力して投稿する。
5,スクリーンショットの一覧ページで、投稿されたスクリーンショットをクリックし、詳細ページへ遷移し内容を確認する。
6,スクリーンショット詳細ページにて、それについてのコメントをコメント投稿欄に入力し、投稿する。

# アプリケーションを作成した背景

一緒にモンスターハンターをプレイしているサークルの仲間にボイスチャットでヒアリングを実施し、ゲームの序盤で初心者が
なかなかクリアできない難関がいくつかある事が判明した。ネットで検索すればある程度の攻略情報は出てくるが、自分が
今ピンポイントで求める情報がいつもあるとは限らないし、お悩みの種類はプレイヤーによってさまざまで、ネットの攻略情報はそれらを
全てカバーできるものではない。
そこで、初心者が歴戦のプレイヤーからアドバイスをもらえる・いちプレイヤーからの生のアドバイスをもらえる場所が必要である
と考え、そういった場所を提供するSNS型のアプリケーションを開発することにした。

# 要件定義書のURL

https://docs.google.com/spreadsheets/d/1F2y_ijQk-2CwD3bgMGNudgCRUsU6LO5o77UQk2_7zDM/edit#gid=982722306

# 実装予定の機能

現在、データベース設計を実施中。
今後の実装予定は、
基本的な機能として、ベーシック認証の導入、ユーザー登録機能、お悩み投稿機能、お気に入りスクリーンショット投稿機能、コメント機能を実装予定。
発展的な内容として、ツイッターのいいねボタン機能、ユーザーのフォロー機能、レスポンシブウェブデザインの導入を実装予定。

# 開発環境

・フロントエンド：HTML,CSS/javascript
・バックエンド:Ruby(ver 2.6.5)/RubyOnRails(ver 6.0.0)
・インフラ:AWS(S3)/MySQL
・テスト:RSpec
・テキストエディタ:Visual Studio Code



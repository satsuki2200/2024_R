# グルメトレジャーマップ
<!-- プロダクト名に変更してください -->

![プロダクト名](https://kc3.me/cms/wp-content/uploads/2023/11/2b1b6d9083182c0ce0aeb60000b4d7a7.png)
<!-- プロダクト名・イメージ画像を差し変えてください -->


## チーム名
チームR 贅沢搾りサーモン
<!-- チームIDとチーム名を入力してください -->


## 背景・課題・解決されること

<!-- テーマ「関西をいい感じに」に対して、考案するプロダクトがどういった(Why)背景から思いついたのか、どのよう(What)な課題があり、どのよう(How)に解決するのかを入力してください -->
### 背景
関西といえばグルメだが美味しいグルメが多過ぎて店を選ぶのに大変な思いをしたことがある。おすすめの店ランキングを調べて行こうとするが該当する店がどこにあるのかをいちいち調べないといけなかったため苦労したことがあった。そのため今回はgoogleマップとランキングを組み合わせ一目でランキングと場所がわかるアプリを作ろうと考えた。

### 課題
店のランキングを調べた後、場所を調べないといけないという手間がかかる

### 解決方法
ランキングとマップを組み合わせて一目で情報を得られるようにする。

## プロダクト説明
指定したジャンル、距離内にあるお店をピックアップし、それをランキングとともにマップに表示する。
またログインすると店舗ごとの詳細情報を確認でき、さらにお気に入り登録できるようになる。そしてお気に入り登録した店舗を複数選んでルート検索する機能も実装した。
<!-- 開発したプロダクトの説明を入力してください -->


## 操作説明・デモ動画
<!--[デモ動画はこちら](https://www.youtube.com/watch?v=_FAA15ARmas)-->
<!-- 開発したプロダクトの操作説明について入力してください。また、操作説明デモ動画があれば、埋め込みやリンクを記載してください -->
### 環境の初期化
```bash
$ make init
# docker compose build
# docker compose up -d --build
# docker compose exec web rails db:create
# docker compose stop
# の4つを行います
```
### DB/Bootstrapの初期化
```bash
$ make migrate
$ make precompile
```
### ローカルサーバの起動
```bash
$ make up
```
### ローカルサーバへのアクセス
**http://localhost:3000**


## 注力したポイント

<!-- 開発したプロダクトの中で、特に注力して作成した箇所・ポイントについて入力してください -->
- 見やすい画面になるように力を入れました
- 特にルート検索機能を時間をかけて実装しました
- Makefileを用いてコマンドに統一感を持たせました


## 使用技術
- Ruby on Rails(Ruby)
- Bootstrap(css)
- MySQL
- Docker
- Google Maps API
<!-- 使用技術を入力してください -->


<!--
markdownの記法はこちらを参照してください！
https://docs.github.com/ja/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
-->
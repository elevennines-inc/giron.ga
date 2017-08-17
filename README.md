# Ruby on Rails チュートリアルのサンプルアプリケーション

これは、次の教材で作られたサンプルアプリケーションです。   
[*Ruby on Rails チュートリアル: 実例を使って Rails を学ぼう*](http://railstutorial.jp/)
[Michael Hartl](http://www.michaelhartl.com/) 著

## ライセンス

[Ruby on Rails チュートリアル](http://railstutorial.jp/)内にあるすべてのソースコードは
MIT ライセンスと Beerware ライセンスのもとに公開されています。
詳細は [LICENSE.md](LICENSE.md) をご覧ください。

## 本番環境（β）

https://hidden-beach-98037.herokuapp.com

## 使い方

このアプリケーションを動かす場合は、まずはリポジトリを手元にクローンしてください。
その後、次のコマンドで必要になる RubyGems をインストールします。

```
$ bundle install --without production
```

その後、データベースへのマイグレーションを実行します。

```
$ rails db:migrate
```

最後に、テストを実行してうまく動いているかどうか確認してください。

```
$ rails test
```

テストが無事に通ったら、Railsサーバーを立ち上げる準備が整っているはずです。

```
$ rails server
```

詳しくは、[*Ruby on Rails チュートリアル*](http://railstutorial.jp/)を参考にしてください。


## 実装済み機能

基本的なユーザ相互follow機能を持ったRuby on Railsアプリケーションとなっている。

- ユーザ登録機能
- ログイン機能
- ログイン状態保持機能
- ユーザ更新機能
- アカウント登録時アクティベーション機能
- パスワード再設定機能
- マイクロポスト機能
- ユーザフォロー機能


## 拡張機能案

- reply機能
- メッセージ機能
- フォロワーの通知
- RSSフィード
- REST API
- 検索機能
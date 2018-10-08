# README
選手登録をするためのアプリケーション

# 開発したアプリケーションの概要
サッカー、フットサル分野でのユーザーを対象としたアプリ
ユーザーが独自に選手名鑑を作成することができる
作成した選手名鑑をSNSでシェアできる

## バージョン
* Ruby 2.5.1
* Ruby on Rails 5.2.0
* psql (PostgreSQL) 9.6.3

## 準備

```
$ git clone　git@github.com:gijutu/Player_Entry_App.git
$ cd Player_Entry_App.git
$ yarn install # まだ環境にyarnが入っていなかったら
$ bundle install --path vendor/bundle
$ rails db:create db:migrate
$ rails db:seed_fu
```

## アプリケーション実行

```
$ rails s

## 開発フロー

```
$ git checkout develop
$ git checkout -b feature/issues-イシュー番号

開発を実施

開発完了後
$ git push origin feature/issues-イシュー番号

GitHub場でPull Requestを作成
レビューと修正を繰り返してマージ

新しくissueを割り振られたらgit checkout developして新たにfeatureブランチを切る
あとは臨機応変に
```

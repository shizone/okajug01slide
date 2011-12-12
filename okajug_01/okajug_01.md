!SLIDE
# はじめに

* このセッションはJIT(Just In Tsukkomi)対応です
* ハッシュタグ([#okajug](https://twitter.com/#!/search/%23okajug))つけてTwitterでツッコミ入れると下の字幕に出るよ

!SLIDE

![pic](img/01.png "01")

!SLIDE

![pic](img/02.png "02")

!SLIDE

![pic](img/03.png "03")

!SLIDE

![pic](img/04.png "04")

!SLIDE

## このwarをデプロイしたのは誰だあっ！！
### 〜至高のCI Jenkins〜

!SLIDE

# About me

![pic](img/me.png "pics")

Yuuki "Razon" Sumida

* [#tkscala](https://twitter.com/#!/search/%23tkscala) 言いだしっぺ
* [#okajug](https://twitter.com/#!/search/%23okajug) 幹事長

### <http://about.me/shizone>

!SLIDE

# Agenda

* 継続的インテグレーション(CI)とは？
* Jenkinsとは？
* Jenkinsによる自動化
    * インストール
    * 使ってみよう

!SLIDE

# 継続的インテグレーション(CI)とは？

継続的インテグレーション (Continuous Integration, CI) とは、主にプログラマーのアプリケーション作成時の品質改善や納期の短縮のための習慣のことである。エクストリーム・プログラミング (XP) のプラクティスの一つで、狭義にはビルドやテスト、インスペクションなどを継続的に実行していくことを意味する。

by Wikipedia

!SLIDE

# 継続的インテグレーション(CI)とは？

## 継続的に実行？

ソフトウェアは日々変化している

* 新規機能追加
* 仕様変更
* 不具合改修

!SLIDE

# 継続的インテグレーション(CI)とは？

## 継続的に実行？

変化するソフトウェアに対して、正しく動作するか検証したい

* 変更するごとに検証したい
* それはしんどい

!SLIDE

# 継続的インテグレーション(CI)とは？

## しんどい？

* ビルドしてデプロイするのが手間
* テストの工数がエグいことに

!SLIDE

# YOU、自動化しちゃいなYO

!SLIDE

# 覚えがありませんか？

* 開発サーバデプロイ手順書_20111217版.xls
* Excel方眼紙爆発し（ｒｙ

!SLIDE

# 覚えがありませんか？

* 頑張って作った、テストコード！
* （いまは、もう、動かない…）

!SLIDE

# そうだね、Jenkinsだね

!SLIDE

# Jenkinsとは？

* Java製のCIツール
* 元々はHudsonというツールだったが（お察しください）
* 様々な作業が自動化できる
    * ビルド
    * デプロイ
    * テスト
    * プラグインを突っ込めば可能性は無限大！

!SLIDE

# Jenkinsのインストール

1. OS/ディストリビューションのパッケージからのインストール
    * yum
    * apt-get
    * homebrew
2. 公式からインストーラを落としてくる
3. 公式からバイナリ（war）を落としてくる
    * winstoneでの単体起動
    * GlassFish/Tomcat/Jettyなどにデプロイ

!SLIDE

# Jenkinsを使う

## 痛Jenkins化

Jenkinsのおっさんを抹消してからが本当のJenkinsの始まりです（ｷﾘｯ

!SLIDE

# Jenkinsを使う

## ジョブを作る

!SLIDE

# Jenkinsを使う

## ビルド・デプロイを自動化する

様々なビルドツールによるビルド

* Ant
* Maven
* sbt(simple-build-tool)
* MS Build(!)
* Rake

!SLIDE

# Jenkinsを使う

## ユニットテストを自動化する

!SLIDE

# Jenkinsを使う

## さらにできること

* カバレッジの取得
* コードインスペクションの実施
* ステップ数のカウント
* 結果の通知
    * メール
    * IRC
    * Twitter

!SLIDE

# さらにJenkinsを知る

## [Jenkins実践入門 ビルド・テスト・デプロイを自動化する技術](http://gihyo.jp/book/2011/978-4-7741-4891-5)

!SLIDE

# さらにJenkinsを知る

## [Jenkinsではじめるビルド職人入門](https://gihyo.jp/dp/ebook/2011/978-4-7741-4952-3)
* 11月までは無料でした…

!SLIDE

# さらにJenkinsを知る

## [Jenkins Advent Calendar jp 2011](http://atnd.org/events/22048)
* Gihyo Digital Publishingより、電子書籍化されるそうです！

!SLIDE

# さいごに

## できるところから自動化しよう！


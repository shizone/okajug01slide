!SLIDE

# Jenkinsとは？

<br/>

* Java製のCIツール
* 元々はHudsonというツールだったが、Ora<span class="weak">（お察しください）</span>
* 様々な作業が自動化できる
    * ビルド
    * テスト
    * デプロイ
    * プラグインを突っ込めば可能性は無限大！

!SLIDE

# Jenkinsのインストール

<br/>

1. OS/ディストリビューションのパッケージからのインストール
    * yum
    * apt-get
    * homebrew
2. 公式からインストーラを落としてくる
3. 公式からバイナリ（war）を落としてくる
    * winstoneでの単体起動
    * JavaEEコンテナ/サーブレットコンテナなどにデプロイ

!SLIDE

# Jenkinsを使う

!SLIDE

# Jenkinsを使う

<br/>

## 痛Jenkins化

Jenkinsのおっさんを抹消してからが本当のJenkinsの始まりです（ｷﾘｯ

<center>
![pic](img/jenkins2.png "pics")

!SLIDE

# Jenkinsを使う

<br/>

## 痛Jenkins化

Jenkinsのおっさんを抹消してからが本当のJenkinsの始まりです（ｷﾘｯ

!SLIDE

# Jenkinsを使う

<br/>

## 痛Jenkins化

[Simple Theme Plugin](https://wiki.jenkins-ci.org/display/JENKINS/Simple+Theme+Plugin)

任意のCSS/JSを差し込める

!SLIDE

# Jenkinsを使う

<br/>

## ジョブを作る

* Jenkinsで自動化する処理のかたまりを、「ジョブ」という単位で扱う
* 複数のジョブを連携して動作させることも可能

!SLIDE

# Jenkinsを使う

<br/>

## ビルド・デプロイを自動化する

様々なビルドツールによるビルド

* Ant
* Maven
* sbt(simple-build-tool)
* MS Build(!)
* Rake

!SLIDE

# Jenkinsを使う

<br/>

## ユニットテストを自動化する
* xUnit
* Selenium

!SLIDE

# Jenkinsを使う

<br/>

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

<br/>

## [Jenkins実践入門 ビルド・テスト・デプロイを自動化する技術](http://gihyo.jp/book/2011/978-4-7741-4891-5)

<center>
![pic](img/book1.jpg "pics")

!SLIDE

# さらにJenkinsを知る

<br/>

## [Jenkinsではじめるビルド職人入門](https://gihyo.jp/dp/ebook/2011/978-4-7741-4952-3)
* 11月までは無料でした…

<center>
![pic](img/book2.jpg "pics")

!SLIDE

# さらにJenkinsを知る

<br/>

## [Jenkins Advent Calendar jp 2011](http://atnd.org/events/22048)
* Gihyo Digital Publishingより、電子書籍化されるそうです！

!SLIDE

# さいごに

<br/>

* できるところから自動化しよう！
    * まずはビルドの自動化から
    * テストコードを書いているなら、様々なフィードバックにも挑戦してみよう！

!SLIDE

# さいごに

## それでは皆様、よいCIライフを！

# 基本情報

|key|value|
|---|-----|
|Name|川辺 裕太(かわべ ゆうた)|
|Twitter|[@yaruki_00](https://twitter.com/yaruki_00)|
|Qiita|[Yaruki00](http://qiita.com/Yaruki00)|

# スキル

|key|value|
|---|-----|
|iOSアプリ開発|実務4年ほど、マンガアプリ/ゲーム攻略アプリを作りました|
|APIサーバ開発|実務1年ほど、上記アプリのためのAPIを作りました|
|バッチ開発|実務1年ほど、上記アプリのためのバッチを作りました|

## iOSアプリ開発

### 言語
現在はSwift5でやっています。始めたときのバージョンは2でした。Objective-Cも一応使えます。

### アーキテクチャ
現在はMVVM+Clean Architectureをアレンジして使っています。  
VMにはUnioというフレームワークを使うことで、記法が個人によってぶれないようにしています。  
極力処理をモデル層に寄せる&モデルを細かく分割することで、特定のファイルが大きくならないよう気をつけています。  
昔はMVPやMVCやVIPERを使っていたこともあります。  
Flux/Reduxはあまりやったことがありません。

### 通信
AlamofireとRxSwiftを組み合わせて使っています。  
共通通信クラスはSingle<Data>を返して、各API用のクラスがパースするようにしています。  
データとしてはjsonとprotoを扱ったことがあります。jsonのパースはCodableで行っています。

### ストレージ
UserDefaults, KeyChain, Realm, sqliteを使ったことがあります。

### テスト
XCTest, iOSSnapshotTestCase, Cuckoo, MockingJayを使ってユニットテストを少し書いています。カバレッジで言うと20~30%くらい・・・  
もっと書いたほうがいいかなとも思うし、でも書いてもあまり意味ないかなとも思うし、悩みながらやってます。  
テストを書くのは主にモデル層と、プレゼンテーションのロジックがある部分です。

### 課金
消費型、非消費型、定期購読の課金実装経験があります。  

### CI
travis&fastlaneを使っています。Appleアカウントが2段階認証必須になったことで、Bitriseも使い始めました。  
travis/Bitriseはブランチによる場合分けでfastlaneのlaneを叩くくらいです。  
fastlaneはimport_certificate, sigh, gym, deploygate, slackを使っています。

### レイアウト
IB+AutoLayoutでやっています。  
1Storyboardに1VC、Viewごとに対応するXibを作ります。

## APIサーバ開発
PHPとCodeIgniterを使っていました。  
最近はGoと自社フレームワークを使うこともあります。  
ドキュメント生成にはSwaggerを使っています。  
インフラについては予め用意された手順に従って作業をするだけなので、知識はあまりありません。  
さくらクラウド+Nginx+MySQLという組み合わせを使っています。

## バッチ開発
GoでスクレイピングやTwitter監視を行いました。

## その他

### 言語
多少触ったことがある程度： C, C++, Java, Python, JavaScript

ほんのちょっとは触った： Ruby, Haskell, D, R, Scala, Kotlin

### 経験のあるツール
- デザイン : Zeplin, Prott, Figma
- コミュニケーション : Slack, ChatWork
- ドキュメンテーション : esa, Confluence
- タスク管理 : Trello, Redmine, Backlog

# 職務経歴

### 2015/10 - 現在: and factory株式会社

- マンガアプリやゲーム攻略アプリのiOSを担当
- わずかですが上記アプリのためのAPIサーバも作成
- 採用プロセスに携わり、募集記事の作成協力や面接官を担当

### 2014/4 - 2015/9: 某SIer

- Exelをいじる日々
- コーディングしたかった

# 基本情報

|key|value|
|---|-----|
|Name|川辺 裕太(かわべ ゆうた)|
|Twitter|[@yaruki_00](https://twitter.com/yaruki_00)|
|Qiita|[Yaruki00](http://qiita.com/Yaruki00)|

# スキル

|key|value|
|---|-----|
|iOSアプリ開発|実務3年ほど、マンガアプリ/ゲーム攻略アプリを作りました|
|APIサーバ開発|実務1年ほど、上記アプリのためのAPIを作りました|
|バッチ開発|実務1年ほど、上記アプリのためのバッチを作りました|

## iOSアプリ開発

### 言語
ほとんどSwiftでやっています。Objective-Cも一応使えます。

### アーキテクチャ
最近はVIPERかClean Architectureをアレンジして使っています。  
極力処理をモデル層に寄せる&モデルを細かく分割することで、特定のファイルが大きくならないよう気をつけています。  
昔はMVPやMVCを使っていたこともあります。  
MVVMやFlux系はあまりやったことがありません。

### 通信
AlamofireとRxSwiftを組み合わせて使っています。  
共通通信クラスはSingle<Data>を返して、各API用のクラスがパースするようにしています。  
データとしてはjsonとprotoを扱ったことがあります。jsonのパースはCodableで行っています。

### ストレージ
UserDefaults, KeyChain, Realm, sqliteを使ったことがあります。

### テスト
XCTest, iOSSnapshotTestCase, Cuckooを使ってユニットテストを少し書いています。カバレッジで言うと20~30%くらい・・・  
もっと書いたほうがいいかなとも思うし、でも書いてもあまり意味ないかなとも思うし、悩みながらやってます。  
テストを書くのは主にモデル層と、プレゼンテーションのロジックがある部分です。

### 課金
消費型、非消費型、定期購読の課金実装経験があります。  

### CI
travis&fastlaneを使っています。  
travisはブランチによる条件分けとfastlaneのlaneを叩くくらいです。  
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
多少触ったことがある程度：C, C++, Java, Ruby, JavaScript

ほんのちょっとは触った：Haskell, D, R, Scala, Kotlin

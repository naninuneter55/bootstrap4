Bootstrap4 の

# 利用方法

Note:
このレクチャーではBootstrap4の利用方法についてお話しします。
+++

### Bootstrap4の利用方法

1. CDNの利用
1. Bootstrap4 をダウンロード
1. npmを利用

Note:
Bootstrap4には3つの利用方法があります。１つはCDNを利用する方法、２つ目はBootstrap4をダウンロードする方法、３つ目はnpmを利用する方法です。

+++

利用方法その1

# CDNを利用

Note:
それでは利用法その１「CDNの利用」をご説明します。
+++

CDN?

Note:
CDNとは何かお分かりでしょうか？
+++

CDNとは

Contents Delivary Network の略称。
CSSなどの静的コンテンツなどをインターネット配信する手法。
自分のWebサーバ以外のCDNサーバから高速にCSSやJavaScriptライブラリを取得することに利用される。

Note:
CDNとは、Contents Delivary Network の略称で、
CSSなどの静的コンテンツなどをインターネット配信する手法のひとつです。
自分のWebサーバ以外のCDNサーバから高速にCSSやJavaScriptライブラリを取得することに利用されます。

+++

CDNを利用するには

```
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link rel="stylesheet"
        href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css" 
        integrity="sha384-WskhaSGFgHYWDcbwN70/dfYBj47jz9qbsMId/iRN3ewGhXQFZCSftd1LZCfmhktB"
        crossorigin="anonymous">
    <title>Bootstrap4</title>
</head>
```
@[1,9](HTMLのHEADタグの中で)
@[4-7](BootstrapのcssファイルをCDNから読み込むように指定します。)
@[6](integrity属性はダウンロードされたCSSファイルが改ざんされていないかをチェックするハッシュ値です。変更しないでください。)

Note:
CDNを利用するには、HTMLのHEADタグの中で、BootstrapのcssファイルをCDNから読み込むように指定します。
integrity属性はダウンロードされたCSSファイルが改ざんされていないかをチェックするハッシュ値です。変更しないでください。

+++

利用方法その2

Bootstrap4 を
# ダウンロード

Note:
それでは利用法その2「Bootstrap4 をダウンロード」をご説明します。

+++

以下のURLにアクセスし

[https://github.com/twbs/bootstrap/releases/download/v4.1.1/bootstrap-4.1.1-dist.zip](https://github.com/twbs/bootstrap/releases/download/v4.1.1/bootstrap-4.1.1-dist.zip)

ZIPファイルをダウンロードする。

Note:
まずは、ご覧のURLにアクセスしてbootstrap-4.1.1-dist.zip をダウンロードします。

+++

ZIPファイルを解凍し

ご自身のHTML作成環境に配置

Note:
ダウンロードしたZIPファイルを解凍し<br>
ご自身のHTML作成環境に配置します。

+++

ダウンロードしたBootstrap4を利用するには

```
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link rel="stylesheet" href="./css/bootstrap.min.css">
    <title>Bootstrap4</title>
</head>
```
@[1,6](HTMLのHEADタグの中で)
@[4](解凍して配置したBootstrapのcssファイルを読み込むように指定します。)


Note:
ダウンロードしたBootstrap4を利用するには、
HTMLのHEADタグの中で、
解凍して配置したBootstrapのcssファイルを読み込むように指定します。

+++

利用方法その3

# npm

を利用

Note:
それでは利用法その3「npmを利用」をご説明します。

+++

npm?

Note:
npmとは何かお分かりでしょうか？
+++

npmとは

* Node Package Manager
* 本来Node.jsのライブラリを管理するもの
* Webで使われる各種ライブラリなどがnpmでダウンロード可能
* 今ではフロントエンドのライブラリフレームワーク全般を管理するツール

Note:
npm(Node Package Manager)は、本来Node.jsのライブラリを管理するものでしたが、
Webで使われる各種ライブラリなどがnpmでダウンロードできるようになり、
今ではフロントエンドのライブラリフレームワーク全般を管理するツールと使用されています。

+++

npm　のインストールイメージ

```shell
$ mkdir bs4sample
$ cd bs4sample
$ npm init
$ npm install bootstrap
```
@[1,2](フォルダを作成し、作成したフォルダに移動します。)
@[3](初期化処理を行います。npm init コマンドを実行することで、インストールするライブラリのバージョンなどを管理するpackage.jsonファイルが作成されます。)
@[4](npm install bootstrap コマンドで bootstrap のダウンロードとインストールを実行します。)

Note:
npm install コマンドのを使用したインストールイメージを紹介します。
まず、フォルダを作成し、作成したフォルダに移動します。
それから、npm init　コマンドで初期化処理を行います。
npm init コマンドを実行することで、インストールするライブラリのバージョンなどを管理するpackage.jsonファイルが作成されます。
最後に、npm install bootstrap コマンドで bootstrap のダウンロードとインストールを実行します。

+++

このあとのレクチャーでは、npm を使用した環境構築を Mac, Windows それぞれでご説明します。

Note:
このあとのレクチャーでは、npm を使用した環境構築を Mac, Windows それぞれでご説明します。

+++

そして、動きのあるBootstarp4のコンポーネントのために、さらに2つのライブラリをインストールする必要があります。

Note:
そして、動きのあるBootstarp4のコンポーネントのために、さらに2つのライブラリをインストールする必要があります。

+++

# JQuery

* もっとも有名なJavaScriptライブラリ
* Bootstrap4(v4.1.1) を使用する場合は JQuery 3.3.1 を使用してください |

Note:
ひとつはJQueryです。Bootstrap4(v4.1.1) を使用する場合は JQuery 3.3.1 を使用してください

+++

# popper.js

* ポップオーバ表示などを行うためのライブラリです。|
* Bootstrap4(v4.1.1) を使用する場合は popper.js v1.14.3 を使用してください |

Note:
それから、ポップオーバ表示などを行うためのライブラリ popper.js です。
Bootstrap4(v4.1.1) を使用する場合は popper.js 1.14.3 を使用してください

+++

Bootstrap4 の

# 利用方法

Note:
このレクチャーではBootstrap4の利用方法についてお話しします。
+++

### Bootstrap4の利用方法

1. CDNの利用
1. Bootstrap4 をダウンロード
1. パッケージマネージャを利用

Note:
Bootstrap4には3つの利用方法があります。１つはCDNを利用する方法、２つ目はBootstrap4をダウンロードする方法、３つ目はパッケージマネージャを利用する方法です。

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
@[4](解凍した配置したBootstrapのcssファイルを読み込むように指定します。)


Note:
ダウンロードしたBootstrap4を利用するには、
HTMLのHEADタグの中で、
解凍した配置したBootstrapのcssファイルを読み込むように指定します。

+++


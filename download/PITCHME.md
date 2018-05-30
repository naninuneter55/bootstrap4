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

CDNの利用方法

```
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css" integrity="sha384-WskhaSGFgHYWDcbwN70/dfYBj47jz9qbsMId/iRN3ewGhXQFZCSftd1LZCfmhktB"
        crossorigin="anonymous">
    <title>Bootstrap4</title>
</head>
```
@[1](aaa)

---
### Code Presenting
コードブロックのハイライトができます。
```js
console.log("@[1]と書くと、1行目がハイライトされます。");
console.log("@[2-4]といったように");
console.log("複数行選択も");
console.log("可能です。");
console.log("eof");
```
@[1](ハイライト行の解説も記述できます。)
@[2-4](コメントは[]の右に記述します。)
---


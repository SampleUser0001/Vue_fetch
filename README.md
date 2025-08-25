# Vue.jsでfetchする

## 概要

Vue.jsでAPIをfetchして結果を表示するアプリケーションを作成してください。
レイアウトの構成にbulma.cssを使用してください。

1. htmlを1ファイルだけ作成してください。
2. 入力欄は郵便番号のみです。
3. 送信ボタンをクリックすることでAPIを実行して、取得した結果を画面に表示するようにしてください。

## Vueの導入

``` html
<script src="https://unpkg.com/vue@3/dist/vue.global.js"></script>
```

## bulma.cssの導入

``` html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/bulma@1.0.4/css/bulma.min.css"
>
```

## fetchするAPI

下記URLを参照してください。
https://zipcloud.ibsnet.co.jp/doc/api

### 出力する項目

- エラーが発生しない場合
    - address1とaddress2とaddress3を連結してください。
    - 1件目だけで良いです。
- エラーが発生した場合
    - messageを表示してください。

## Pages

[https://sampleuser0001.github.io/Vue_fetch/](https://sampleuser0001.github.io/Vue_fetch/)
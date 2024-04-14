# redirect

Cloudflare Pages を利用した、各サービスへのリダイレクト用サイト。

## 書き方

`_redirects` ファイルに以下の形式で記述することでリダイレクトさせられる。

```
<source> <destination> [code]
```

詳細は以下の公式ドキュメントを参照されたい。

https://developers.cloudflare.com/pages/configuration/redirects

## ここが良い

 - ユーザ名や ID などに変更があった場合に、過去の投稿やプロフィールなどのリンクを修正する手間がかからない
 - 編集ができない SNS や印刷物 (名刺での2次元コードなど) のリンク切れを防ぐことができる
 - サービスごとに長い URL を覚える必要がない
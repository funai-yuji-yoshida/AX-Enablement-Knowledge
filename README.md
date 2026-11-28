# AI活用ナレッジ

AX教育ユニット-AX Enablement Team- の知識HTMLを公開する場所です。GitHub Pages でWebページとして見られます。

**公開ページ**：https://funai-yuji-yoshida.github.io/AX-Enablement-Knowledge/

> このリポジトリと公開ページは、**誰でも見られます**。顧客情報・社外秘・個人情報は絶対に入れないでください。
> メンバーの課題や社内向けの資料は、非公開の AX-Enablement-Team に置きます。

## 記事の追加方法

1. 分類フォルダに HTML を置く：`<分類>/YYYYMMDD_テーマ.html`
2. CSS・画像は HTML の中に入れ、1ファイルで完結させる
3. 上部に Home に戻るボタン（`../index.html` へのリンク）を付ける。既存記事の `<nav class="topbar">` と `.topbar` `.home` のCSSをコピーすればよい
4. `index.html` の `ARTICLES` に1件書き足す
5. commit → push すると、数分で公開ページに反映される

## 分類

| フォルダ | 内容 |
|---|---|
| `lectures/` | AI Deep Dive の講義資料 |
| `basics/` | AIの仕組み・用語・安全な使い方 |
| `prompting/` | AIへの問いかけ方 |
| `tools/` | ツール・サービスの使い方 |
| `business/` | 業務活用・事例・提案 |
| `teaching/` | 講座運営・教え方 |
| `others/` | どれにも当てはまらないもの |

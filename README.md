# markdown-print-css

Markdown形式から変換したHTMLファイルを印刷時に読みやすく整形するためのCSSです。

## 利用方法

公開用には、再現可能なバージョン固定の jsDelivr URL を指定してください。

```html
<link rel="stylesheet"
  href="https://cdn.jsdelivr.net/gh/sorakakeru/markdown-print-css@v1.0.0/dist/css/style.css">
```

`@main` のような可変参照は、更新確認用にだけ使います。公開サイトでは使用しません。

## リリース手順

1. `package.json` の `version` を更新する。
2. `pnpm build` を実行し、生成された `dist/` をコミットする。
3. コミットに `v1.0.0` 形式の注釈付きタグを作成して GitHub へ push する。

`dist/css/style.css` が jsDelivr から配信する公開ファイルです。

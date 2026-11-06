# price-tracker-landing-page

Chrome拡張機能「PriceTracker For カーセンサー」のランディングページです。

## 開発

```sh
npm install
npm run dev    # CSSの変更を監視してビルド
npm run build  # 本番用に圧縮してビルド
```

`index.html` はCSSとして `dist/output.css` を読み込みます。`dist/` はGitの管理対象外なので、表示の前に上記のビルドが必要です。

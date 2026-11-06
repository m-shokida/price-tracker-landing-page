# price-tracker-landing-page

Chrome拡張機能「PriceTracker For カーセンサー」のランディングページです。

## 表示

ビルド済みのCSS(`css/style.css`)もコミットしているので、`index.html` はビルドなしで表示できます。

## 開発

```sh
npm install
npm run dev    # CSSの変更を監視してビルド
npm run build  # 圧縮してビルド
```

`css/style.css` は `src/input.css` から生成するファイルなので、直接編集しないでください。`index.html` のクラスや `src/input.css` を変更したら `npm run build` を実行し、`css/style.css` も一緒にコミットしてください。

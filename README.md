# yugo303.github.io

yugo303 のポートフォリオ（GitHub Pages）。

- `/` 作ったものの一覧
- `/photospot/` 撮りの目（とりのめ）の紹介と制作の記録
- `/photospot/s/` アプリ「撮りの目」の共有リンクで開くスポットのページ（`?id=…&n=名前&a=場所&lat=…&lon=…`）
- `/photospot/privacy/`・`/photospot/terms/`・`/photospot/support/` プライバシーポリシー、利用規約、サポート（photospot リポジトリの `tools/build_legal_pages.mjs` で作る。直接は直さない）
- `/photospot/data/` スポットのデータ（ODbL 1.0。同じスクリプトでアプリのデータを写す）
- `/.well-known/assetlinks.json` 共有リンクを Android のアプリで直接開くための設定（アプリの署名の指紋）

今は検索エンジンに載らないよう `noindex` を付けています。

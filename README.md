# Rina Matsuda | Community Portfolio

日南市役所職員・松田莉奈のコミュニティポートフォリオサイトです。
「人を想うことは、地域を想うこと。」というブランドコンセプトのもと、Hero / About / Philosophy / Community / Contact の5セクションで構成されています。

## 構成

```
.
├── index.html   ← サイト本体（CSS・JSはすべてインライン、単一ファイル構成）
└── README.md
```

- 外部ファイル依存なし（CSS・JSは `index.html` 内にすべて記述）
- 外部リソースは Google Fonts（Cormorant Garamond / Noto Serif JP / Noto Sans JP）のみ、CDN経由で読み込み
- ビルドステップ不要。`index.html` を開くだけで動作します

## GitHub Pagesでの公開手順

1. このリポジトリを GitHub に Push します。
2. GitHub上でリポジトリの **Settings → Pages** を開きます。
3. **Source** を `Deploy from a branch` に設定します。
4. **Branch** を `main`（または該当のデフォルトブランチ）、フォルダを `/ (root)` に設定して **Save** します。
5. 数分後、`https://<ユーザー名>.github.io/<リポジトリ名>/` で公開されます。

## 公開前に確認・更新してほしい項目

- `index.html` の `<head>` 内、`<link rel="canonical" href="https://example.com/">` を実際に公開されるURLに書き換えてください。
- Hero セクションの人物イラストは現在プレースホルダーです。実イラストが用意でき次第、`.hero__portrait-figure` 内のプレースホルダー `<div>` を `<img src="images/xxx.png" alt="...">` に差し替えてください（画像ファイルを追加する場合は `images/` フォルダを作成し、相対パスで参照してください）。

## 動作確認済み環境

- iPhone Safari
- Android Chrome
- PC Chrome
- PC Safari

## ライセンス・注意事項

日南市役所の所在地・電話番号・公式サイトURLは公開情報を参照しています。内容の更新が必要な場合は市の公式サイトで最新情報をご確認のうえ修正してください。

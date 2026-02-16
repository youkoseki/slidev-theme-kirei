# slidev-theme-kirei

日本語プレゼンのための、すっきりとした [Slidev](https://github.com/slidevjs/slidev) テーマです。

## インストール

`slides.md` の frontmatter に以下を追加してください。Slidev 起動時に自動でインストールされます。

<pre><code>---
theme: <b>kirei</b>
---</code></pre>

テーマの使い方について詳しくは [Slidev のドキュメント](https://sli.dev/guide/theme-addon#use-theme) をご覧ください。

## レイアウト

- **default** - 通常のスライド
- **cover** - タイトルスライド
- **intro** - 自己紹介
- **section** - セクション区切り
- **two-cols** - 2カラム
- **three-cols** - 3カラム
- **center** - 中央寄せ
- **quote** - 引用
- **fact** - 数値・ファクト
- **statement** - ステートメント
- **end** - 終了スライド

## フォント

- ゴシック体: Noto Sans JP
- 等幅: JetBrains Mono

## 開発

- `npm install` で依存関係をインストール
- `npm run dev` で `example.md` のプレビューを起動
- `npm run export` で PDF を生成
- `npm run screenshot` でスクリーンショットを生成

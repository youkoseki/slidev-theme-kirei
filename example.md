---
theme: ./
---

# slidev-theme-kirei

ミニマルな日本語対応 Slidev テーマ

by youkoseki

---

# デフォルトレイアウト

見出しと本文のシンプルな構成です。

- Noto Sans JP によるきれいなタイポグラフィ
- ライト／ダークモード両対応
	- ライトモードでは、読みやすい、ほんの少しだけ薄い黒テキストを使用

---

# サブヘッダーのデモ

## ヘッダーの補足や章立てに使えます

サブヘッダーは本文より少し大きく、ヘッダーよりは小さいサイズです。スライドの内容を整理するのに便利です。

## 複数のサブヘッダーも使えます

便利ですね。

---
layout: section
---

# セクションタイトル

sectionレイアウトの例

---
layout: center
---

::header::

# centerレイアウト

::default::

コンテンツが上下左右の中央に配置されます。

---
layout: two-cols
---

::header::

# 2カラムレイアウト

::default::

スライドの左側に表示されるコンテンツです。

- ポイント 1
- ポイント 2

::right::

スライドの右側に表示されるコンテンツです。

- ポイント 3
- ポイント 4

---
layout: three-cols
---

::header::

# 3カラムレイアウト

::default::

左カラム

- 項目 A
- 項目 B

::center::

中央カラム

- 項目 C
- 項目 D

::right::

右カラム

- 項目 E
- 項目 F

---
layout: intro
---

# introレイアウト

プレゼンテーションの導入部分に使えます。

カバーに似た構成ですが、よりシンプルです。

---
layout: quote
---

# 「かっこいい引用」

quoteレイアウト

---
layout: statement
---

# 力強いステートメント
statementレイアウト

---
layout: fact
---

# 驚きのファクト
factレイアウトはこんな感じ

---
layout: full
---

# fullレイアウト

コンテンツを画面いっぱいに表示します。画像やグラフなど、余白なく表示したい場合に便利です。

---
layout: image-right
image: https://cover.sli.dev
---

# 画像右レイアウト

左側にテキスト、右側に画像を配置します。

- テキストと画像を並べて表示
- 視覚的な説明に最適

---
layout: image-left
image: https://cover.sli.dev
---

# 画像左レイアウト

左側に画像、右側にテキストを配置します。

- 画像右レイアウトの逆パターン
- コンテンツに合わせて使い分け

---
layout: image
image: https://cover.sli.dev
---

# 画像レイアウト

背景全体に画像を表示します。

---
layout: none
---

# None レイアウト

装飾なしのレイアウトです。完全にカスタムなスタイリングをしたい場合に使います。

---

# コード例

インラインコード: `const x = 42`

```ts
function greet(name: string): string {
  return `こんにちは、${name}さん！`
}

console.log(greet('Slidev'))
```

---

# テーブル例

| 機能 | 状態 |
|------|------|
| ライトモード | 対応済み |
| ダークモード | 対応済み |

> ミニマルなデザインで、最大限の明瞭さを。

---
layout: end
---

# ありがとうございました

デモは以上です

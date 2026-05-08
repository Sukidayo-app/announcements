# Riamo 公式お知らせ・FAQ

カップル向けアプリ **Riamo** の公式お知らせ・FAQサイトです。  
GitHub Pages で公開しており、このリポジトリへの push が即デプロイされます。

🌐 **公開URL**: https://sukidayo-app.github.io/announcements/

---

## ページ構成

| ページ | URL |
|--------|-----|
| トップ | `/` |
| お知らせ一覧（ja） | `/notice/ja/` |
| お知らせ一覧（en/ko/es） | `/notice/en/` など |
| FAQ（ja） | `/faq/ja/` |
| FAQ（en/ko/es） | `/faq/en/` など |

- `/notice/` と `/faq/` にアクセスすると自動で `/ja/` にリダイレクト
- 各ページ上部の言語タブで切り替え可能

---

## ファイル構成

```
.
├── _notices_ja/        # お知らせ記事（日本語）
├── _notices_en/        # お知らせ記事（英語）
├── _notices_ko/        # お知らせ記事（韓国語）
├── _notices_es/        # お知らせ記事（スペイン語）
│
├── faq/
│   ├── ja/index.md     # FAQ（日本語）
│   ├── en/index.md     # FAQ（英語）
│   ├── ko/index.md     # FAQ（韓国語）
│   └── es/index.md     # FAQ（スペイン語）
│
├── notice/
│   ├── ja/index.html   # お知らせ一覧（日本語）
│   ├── en/index.html   # お知らせ一覧（英語）
│   ├── ko/index.html   # お知らせ一覧（韓国語）
│   └── es/index.html   # お知らせ一覧（スペイン語）
│
├── _layouts/
│   ├── default.html    # 共通レイアウト（ヘッダー・フッター）
│   └── post.html       # お知らせ詳細ページのレイアウト
│
├── _includes/
│   └── lang-tabs.html  # 言語切り替えタブ（共通パーツ）
│
└── _config.yml         # Jekyll 設定
```

---

## お知らせの追加方法

### ファイル名のルール

```
_notices_ja/YYYY-MM-DD-タイトルのslug.md
```

例: `_notices_ja/2026-06-01-new-feature.md`

### ファイルの中身（テンプレート）

```markdown
---
title: "【機能追加】○○機能の追加🎉"
date: 2026-06-01
---

こんにちは！Riamo運営チームです。

本文をここに書く。
```

### タイトルの絵文字ルール

| 種別 | タイトル形式 |
|------|------------|
| 機能追加 | `【機能追加】タイトル🎉` |
| お知らせ | `【お知らせ】タイトル` |
| その他 | 絵文字なし |

### 手順

1. `_notices_ja/` に日本語ファイルを作成
2. 同じ内容を `_notices_en/` `_notices_ko/` `_notices_es/` にも翻訳して追加
3. `main` ブランチに push → 数分で公開される

> **基本ルール**: jaを正として、en/ko/esは同内容を翻訳。jaが更新されたら他3言語も合わせて更新する。

---

## FAQの更新方法

`faq/ja/index.md` を編集したら、`faq/en/index.md` `faq/ko/index.md` `faq/es/index.md` も同様に更新する。

---

## Claudeで更新する方法

このリポジトリの更新はClaudeに依頼することができます。

**依頼例（Claude Code または claude.ai）:**

```
_notices_jaに新しいお知らせを追加して。
タイトル「○○機能を追加しました」、内容は以下の通り。
en/ko/esも翻訳して追加してgit pushまでやって。
[内容を貼り付け]
```

Claudeは以下を自動でやってくれます：
- ファイル名・front matter の整形
- 4言語への翻訳
- git commit & push

---

[Riamoをダウンロード](https://riamoapp.com/)

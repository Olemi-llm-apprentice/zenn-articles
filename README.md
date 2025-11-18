# Zenn記事管理リポジトリ

このリポジトリは、Zennの記事を管理するためのプライベートリポジトリです。

## ディレクトリ構成

```
.
├── articles/          # 記事ファイル
│   └── *.md
├── books/             # 本のファイル
└── README.md
```

## 使い方

### 記事の作成

```bash
npx zenn new:article
```

### プレビュー

```bash
npx zenn preview
```

### 公開

記事のfront matterで`published: true`に設定し、GitHubにプッシュすると自動的にZennに公開されます。

## Zennとの連携

このリポジトリをZennと連携させるには、[Zennのダッシュボード](https://zenn.dev/dashboard/deploys)からGitHubリポジトリを連携してください。

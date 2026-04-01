# 日記 (Personal Diary)

藤田さんのための、シンプルでミニマルな日記リポジトリです。

## ✍️ 日記の書き方
1. `content/diary/` フォルダに新しい Markdown ファイル（例：`2026-04-02.md`）を作成します。
2. 以下の形式で内容を記述して保存します。
   ```markdown
   ---
   title: "2026年4月2日の日記タイトル"
   date: 2026-04-02
   slug: "2026-04-02"
   ---
   本文をここに書きます。
   ```
3. GitHub に **Push** すれば、数分後にサイトが自動更新されます。

## 🦋 BlueSky への自動通知
新しい日記を追加すると、自動的に BlueSky に投稿される設定になっています。
※リポジトリの **Settings > Secrets and variables > Actions** で、`BLUESKY_IDENTIFIER` と `BLUESKY_PASSWORD` が設定されていることを確認してください。

## 🛠 カスタマイズ
- **タイトル下の説明文を変える**: `hugo.toml` の `params.description` を書き換えます。
- **デザインの調整**: `static/style.css` を編集します。

## 📂 開発ログ
これまでの開発の経緯や、発生した課題の解決策は `docs/management/` に記録されています。
- [要件ログ](docs/management/requirements_log.md)
- [トラブル対応ログ](docs/management/troubleshooting_log.md)
- [ミッション概要](.agent/mission.md)

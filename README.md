# 🧠 English Word Team App

英単語を覚えるための学習アプリです（チーム開発版）。

---

## 🚀 機能概要

- ✏️ 英単語の登録・編集・削除
- 🧪 4択クイズ形式でのテスト
- 🔐 ユーザーごとの認証と単語管理
- 📱 スマホ対応のレスポンシブデザイン

---

## 🛠 使用技術

- Laravel
- MySQL
- PHP
- TailwindCSS / Bootstrap

---

## ⚙️ 開発環境構築手順

```bash
git clone https://github.com/あなたのユーザー名/english-word-team-app.git
cd english-word-team-app
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve



---

#### ④ 保存（`Ctrl + S` / `⌘ + S`）

保存できたら、以下のコマンドでGitに反映👇

```bash
git add README.md
git commit -m "add README.md"
git push origin main

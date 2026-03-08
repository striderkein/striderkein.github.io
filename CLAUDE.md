# Project: striderkein.github.io

GitHub Pages で公開している履歴書（CV）サイト。

## Structure

- `index.html` — メインページ（履歴書）
- `encrypt-tool.html` — 個人情報暗号化ツール（AES-GCM）
- `images/` — プロフィール写真など

## Tech Stack

- 静的 HTML/CSS/JS（フレームワーク・ビルドツールなし）
- フォント: Noto Serif JP, JetBrains Mono (Google Fonts)
- 暗号化: Web Crypto API (PBKDF2 + AES-GCM)

## Conventions

- 言語: 日本語（HTML lang="ja"）
- デザイン: 和風・落ち着いたカラースキーム（`--bg: #f5f2eb`, `--accent: #8b3a2a`）
- 個人情報（住所・電話・メール）はパスワードで保護された暗号化ペイロードとして埋め込み

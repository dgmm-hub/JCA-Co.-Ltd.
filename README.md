# 日本語 5ページ会社サイト（Netlify + GitHub）スターター

## ファイル構成
- index.html（トップページ）
- about.html（会社概要）
- services.html（事業内容）
- contact.html（お問い合わせ：Netlify Forms対応）
- privacy.html（プライバシーポリシー）
- assets/css/style.css（スタイル）
- assets/img/og.png（OG画像）
- robots.txt / sitemap.xml

## 使い方（超速）
1. このフォルダをZIPごとダウンロード→解凍。
2. GitHubで新規リポジトリ作成 → これらのファイルをアップロード＆コミット。
3. Netlifyにログイン → "Add new site" → "Import from Git" → GitHubでこのリポジトリを選択。
4. Build設定は不要（静的サイト）。デプロイ後に自動で https://ランダム名.netlify.app で公開。
5. カスタムドメインを使う場合：Netlifyの「Domains」で追加 → DNSをNetlifyへ向ける → 自動SSL。
6. フォーム通知：Site settings → Forms → Notifications でメール通知を設定。

## 編集ポイント
- 「【会社名】」「【住所】」などのプレースホルダを置換。
- GA4やSearch Consoleを使う場合は、index.htmlにタグを追加してください。
- フォーム送信後はNetlifyの既定サンクス画面に遷移します（カスタム化も可能）。

© 2025 Your Company

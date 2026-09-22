# mannendokei-tiktok-assets

「萬年時計だより」をTikTokに自動投稿するための画像を公開するための
GitHub Pagesホスティング用リポジトリです。

- `img/` 配下に日付ごとの画像(`YYYY-MM-DD.jpg`)が自動でpushされます。
- 本体のロジックは https://github.com/RoboOkubo/mannendokei-threads-bot にあります。
- TikTok Content Posting APIの写真投稿(PULL_FROM_URL)は公開URLの取得のみ対応のため、
  このリポジトリのGitHub Pages URLを画像の公開先として使っています。

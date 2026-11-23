# PENTAROLL PRACTICE

ペンタロールの非公式CPU対戦練習アプリ。ブラウザだけで動くシングルHTMLです。

## 機能

- 6×6の盤面で、四辺から玉を入れたり押し込んだりする
- CPU対戦：初級・中級・上級
- 先手切り替え、待った、ヒント、対局履歴
- モバイル対応

## ローカル起動

`public/index.html` をブラウザで開くだけで動きます。

## GitHub Pagesへの公開

1. `main` ブランチにこのリポジトリのファイルを置く。
2. GitHub の **Settings → Pages → Build and deployment → Source** を **GitHub Actions** にする。
3. **Actions** タブで `Deploy Pentaroll Practice to GitHub Pages` の成功を確認する。必要なら `Run workflow` から手動実行する。
4. `https://<GitHubユーザー名>.github.io/<リポジトリ名>/` で公開される。

以後 `main` にプッシュすると GitHub Actions が自動デプロイします。

## 注意

本アプリは非公式です。ゲームのルール細則やCPUの棋力について、実物との違いがあれば検証・改善が必要です。
# MeetPitch LP

「日本代表は見るけど、Jリーグの現地観戦は未経験」——そんな新規ファンを、初心者同士のピア型マッチングで“現地観戦デビュー”へ導くサービス **MeetPitch** の事前登録LPです。

- ゴール：ユーザーインタビュー用Googleフォーム／LINE への誘導
- 構成：単一の `index.html`（CSS・JS 埋め込み、外部依存は Google Fonts のみ）

## ローカルで確認

`index.html` をブラウザで開くだけで表示できます。

## 公開（GitHub Pages）

このリポジトリの Settings → Pages で、Branch を `main` / フォルダを `/ (root)` に設定すると公開されます。

## 差し替えポイント

- Googleフォーム URL / LINE URL（`index.html` 内のリンク）
- 掲載試合（`Upcoming Matches` セクション、ヒーローの試合選択カード）

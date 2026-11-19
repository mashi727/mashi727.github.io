---
title: サポート｜PerspectiveCorrector（台形補正）
permalink: /perspective/support/
---

# サポート：PerspectiveCorrector（台形補正）

iPhone アプリ「PerspectiveCorrector」（ホーム画面の表示名「台形補正」）のサポートページです。

[English below](#support-perspectivecorrector)

## お問い合わせ

不具合の報告やご質問は、GitHub の Issues で受け付けています。

**[お問い合わせを書く（GitHub Issues）](https://github.com/mashi727/mashi727.github.io/issues/new?template=perspective.yml)**

- 書き込みには GitHub のアカウント（無料）が必要です。
- Issues の内容は誰でも見られます。**氏名・住所・電話番号などの個人情報や、スライドの写真・発表の資料は書き込まないでください。**
- 個人で開発しているため、お返事に時間がかかることがあります。

## よくある質問

### 会場でアプリを開く必要はありますか
ありません。スライドは標準のカメラで撮ってください。会期中や会議の後に、期間やアルバムを指定してまとめて補正します。

### 4 隅がうまく検出されません
一覧の「要確認」に出た写真をタップし、4 隅を直してください。写真をタップするといちばん近い隅がその位置へ移り、黄色いハンドルをドラッグすると細かく合わせられます。2 本指で広げると拡大できます。前の人の頭などで隅が隠れているときは、写真の外側にも置けます。

### スライド以外の写真を書き出しから外したい
一覧で写真の右上の丸をタップすると、「使う」（緑のチェック）と「使わない」（空の丸）が切り替わります。

### 同じスライドを何枚も撮ってしまいました
いちばん鮮明な 1 枚が自動で選ばれ、残りは「重複」として書き出しから外れます。別の写真を使いたいときは、長押しして「この写真を採用する」を選んでください。

### 発表の題目を付けたい
作業画面のメニューから「スケジュールと照合…」を選び、会議アプリのスケジュールや公式サイトのプログラムのスクリーンショットを読み取ります。出席した予定だけにチェックを付けて照合してください。

### 2 日目以降の写真を同じ作業に足したい
作業を作ったときの期間やアルバムに新しい写真が増えると、作業画面に「新しい写真を取り込む」が出ます。期間で作るときは、会期の最終日までを含めておいてください。

### 書き出せる形式は
写真（写真アプリのアルバム）、PDF（発表ごとの表紙・しおり付き、文字を検索できます）、Markdown（画像付き）、LaTeX（2 段組の報告書）です。Markdown と LaTeX は、文書と画像を 1 つの zip にまとめて書き出します。

### LaTeX の報告書はどうやって PDF にしますか
zip を展開し、LuaLaTeX で report.tex を 2 回コンパイルしてください。日本語は原ノ味フォント、欧文は Libertinus を使います。

### 撮影や録音をしてよいか分かりません
会議によっては、撮影や録音を禁止しています。主催者の規定に従ってください。

### 作業の記録を消したい
ホーム画面で作業を長押しし、「削除」を選んでください。元の写真と、書き出した写真は消えません。

## 動作環境

iPhone（iOS 17 以降）

## 関連ページ

- [プライバシーポリシー](../privacy/)

---

## Support: PerspectiveCorrector

This is the support page for the iPhone app "PerspectiveCorrector" (shown on the Home Screen as "Perspective").

### Contact

Please report bugs or ask questions on GitHub Issues: **[Open an issue](https://github.com/mashi727/mashi727.github.io/issues/new?template=perspective.yml)**.
Issues are public. **Do not post personal information, slide photos, or presentation materials.**

### FAQ

- **Do I need to open the app at the venue?** No. Shoot the slides with the regular Camera app, then correct them in bulk later by date or album.
- **The corners aren't detected well.** Tap a photo under "Needs Review" and adjust the corners: tap to move the nearest corner, drag a yellow handle to fine-tune, and pinch to zoom.
- **How do I leave out photos that aren't slides?** Tap the circle at the top right of a photo to switch between used (green check) and not used (empty circle).
- **How do I add talk titles?** Choose "Match with Schedule…" from the session menu and read screenshots of your conference schedule or the official program.
- **How do I add photos taken on later days?** "Import New Photos" appears on the session screen when new photos show up in the original date range or albums.
- **Export formats:** Photos, PDF (cover page and bookmarks per talk, searchable text), Markdown with images, and a two-column LaTeX report.
- **Photography and recording rules:** Some conferences prohibit them. Follow the organizer's rules.

### Requirements

iPhone with iOS 17 or later.

### Related

- [Privacy Policy](../privacy/)

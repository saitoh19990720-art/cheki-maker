# チェキメーカー

画像とひとことを入れるだけで、静かな水色のチェキ風PNGを書き出す1ファイルWebアプリ。
画像と入力内容は端末内で処理し、外部へ送信しません。表示用フォントはGoogle Fontsから取得します。印刷用(2160×2700px/300dpi級)の書き出しにも対応。

## 使い方
`index.html` をブラウザで開くだけ。画像を選び、ひとことを入れて「チェキを作る」→「PNGで保存」。ひとことは最大64文字入力でき、2行に収まらない部分は「…」で省略されます。

## 日本語 / English
画面右上のボタンで日本語と英語を切り替えられます。最初の表示はブラウザの言語に合わせ（日本語以外なら英語）、選んだ言語は次回も保たれます。URLに `?lang=en` / `?lang=ja` を付けると言語を指定して開けます。

## 技術
HTML / CSS / Canvas（Vanilla JS）。正本デザイントークン（淡色）＋明朝見出し（Shippori Mincho）。アクセントは6色（青／クリスタル水色／シルバー／くすみピンク／ラベンダー／パールホワイト）。

※ 旧パレット版（Ice Blue/ラベンダー・ゴシック）は `index-classic.html` に保存。

制作: Shizuku

---

<!-- 日本語訳：ここから下は海外の方向けの英語の説明です。内容は上の日本語と同じ＋「チェキ」「推し」の説明を足しています。 -->

## Cheki Maker (English)

A single-file web app that turns a photo and a short caption into a calm, pale-blue instant-photo card (PNG).

**What's a “cheki”?** In Japan, fans call instant photos *cheki* — especially the ones taken with your *oshi* (the idol, character or creator you support) at events. This app lets you make your own cheki-style keepsake from any photo.

- **Private by design** — your photo and caption are processed on your device and never uploaded. Only the display fonts are loaded from Google Fonts.
- **Two sizes** — 720×900 px for social media, 2160×2700 px for printing (300 dpi or more for small cards).
- **Six accent colors** — blue, crystal blue, silver, dusty pink, lavender, pearl white.
- **Japanese / English** — switch with the button at the top right, or open with `?lang=en`.
- Captions up to 64 characters; English wraps between words, Japanese wraps by character, and anything beyond two lines ends with “…”.
- The date on the card uses your device's local date in `YYYY-MM-DD` format, so it reads the same in every country.

**Tech:** plain HTML, CSS and Canvas — no libraries, no build step. Open `index.html` in a browser.

Made by Shizuku (Shizuku Studio).

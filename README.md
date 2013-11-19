cssdoc
======

スタイルガイドジェネレーターを作る(作ってみたい)

## 既存のもの

### StyleDocco
http://jacobrask.github.io/styledocco/
- Node.js製
- markdownで記述
- CSS/Sass(SCSS)/less/Stylusに対応
- あくまでスタイルガイドを作るためのもの
 - mixinやfunctionの記述には不向き
- プレビューエリアにバグあり(Safari以外)

### sassdoc
https://github.com/eoneill/sassdoc
- Ruby製
- markdownで記述
- Sass(SCSS)のみ対応(lessやStylusは試してない)
- mixinやfunctionのドキュメント生成
 - スタイルガイドとしての機能は無い

### KSS(Knyle Style Sheets)
http://warpspire.com/kss/
- Ruby製
- 独自のシンタックスで記述
- SynatraやRoRなどRuby周りの技術と相性がいい
- サーバーを起動できたりする
- Node.js版の[KSS-node](https://github.com/hughsk/kss-node)がある
- 見た目の変更ができる

### Kalei
http://kaleistyleguide.com/
- JS製
- bootstrapみたいな見た目のスタイルガイドが作れる
- cloneしてきてサーバー立てればすぐ使える

## 目指したいこと
- スタイルドキュメント(スタイルガイド&mixin/functionドキュメント)
- gruntで動かすことを想定
- 見た目の変更が用意
- 軽い


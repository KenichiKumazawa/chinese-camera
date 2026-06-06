# CLAUDE.md — chinese-camera

中国語カメラ学習アプリの固有ガイダンス。

## 技術スタック
- 単一HTMLファイル（index.html）で完結
- 外部ライブラリ: TensorFlow.js + COCO-SSD（CDNから読み込み）
- カメラ: getUserMedia API（environment カメラ優先）
- 発音: Web Speech API（lang='zh-CN'）

## 開発ルール
- 外部ライブラリはCDN経由で利用してOK（Projects全体ルールの例外として許可済み）
- ビルドツール・パッケージマネージャは使わない
- 動作確認は Mac の Chrome 最新版を基準とする
- 画面テキスト・ラベルはすべて日本語

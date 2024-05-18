---
title: "ローディングで理解したこと"
emoji: ""
type: "tech" # tech: 技術記事 / idea: アイデア
topics: [next.js, SSR]
published: false
---
# 読み込み遅い
前振り，動機
Nextでサイト作ったのをやってみたときに自前でデータをフェッチさせた？
動作が遅すぎたので何か改善をしてやろうと頑張った
ー＞ローディングとuse clientのuseDataFetchをしてみようとしたのでそれを記事にしようと考えた
今回はローディングについてNext.jsのloading.jsを読んでわかりやすかったから覚書していこうと思う。

## 序論


## 本論

### 仕組み


### 実装
react suspense での実装をした。
loading での経緯を説明しながらやるのと同時に
Fallback でのことを喋りながらやると良さそう

## まとめ
とてもわかりやすかった
画像とかデータをめちゃくちゃ使うんだったらレイアウト考えてlazy load使ったほうが楽では？と思った。

### 参考資料
loading.js and suspense
lazy load
react suspense


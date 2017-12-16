---
title: Markdownで作るスライド
author:
- 藤原 惟
- 藤原 由来
- "Twitter: @sky_y"
date: 2017年12月16日
---


## このスライドをどう作っているか

- [Markdown Preview Enhanced](https://shd101wyy.github.io/markdown-preview-enhanced/#/) (MPE)
    - VS Code/Atomのプラグインとして利用可能
    - すごく高機能なMarkdown処理系
    - 個人的にはVS Codeで使っています
- [mume](https://github.com/shd101wyy/mume)
    - MPEのコアにあたる変換エンジン (npmパッケージ)
    - 変換処理をスクリプト化するときに便利
- GitHub Pages: 静的ホスティング

## 参考：スライドのGitHubリポジトリ

- <https://github.com/sky-y/histudy-201712>
- GitHubリポジトリさえ設定できてれば、基本的には`npm run all`でスライド生成→デプロイまで完結します
- あとで整備して、ボイラープレートとして使えるようにしたい

## 執筆お助けツール

- [textlint](https://github.com/textlint/textlint)
    - 英語・日本語の文法誤りをしてくれるツール
    - プラグインでスタイルやルールをインストールできる
    - [Collection of textlint rule · textlint/textlint Wiki](https://github.com/textlint/textlint/wiki/Collection-of-textlint-rule)
- [prh](https://github.com/prh/prh)
    - textlintと組み合わせて使う
    - 辞書を作っておくと、用語の誤りを指摘してくれる
    - [サンプルルール](https://github.com/prh/rules)のtechboosterだけでもかなり使える

## 執筆のためのCI

- 技術書界隈でCIが流行ってる
    - 原稿をPush→完成品に近いPDF生成→GitHub/BitBucketのIssue/PRでフィードバック
    - [技術書同人誌を書きましょう！ - Qiita](https://qiita.com/erukiti/items/6b7e85f760476a997161)
- 執筆CIのメリット
    - 原稿を書いた片っ端から編集者さんが随時校正できる
        - 執筆フローは、伝統的にはウォーターフローモデル
    - リモートでの共同執筆やチームプレイが円滑になる

## 執筆に関するおすすめ資料

- [【もくもく執筆会】執筆お疲れさま！歓談＆LT パーティー](https://techbook-meetup.connpass.com/event/64235/)
    - [資料一覧](https://techbook-meetup.connpass.com/event/64235/presentation/) に上がってるLT資料が良い

## おわり
---
title: 執筆で使っているツール
presentation:
    width: 1200
    height: 700
    slideNumber: true
    controls: true
    transition: 'face'
    transitionSpeed: 'fast'
    center: false
---

<!-- slide  class="center" -->

# スライド作成や執筆で便利なツール

2017年12月16日

藤原 惟（すかいゆき、@sky_y）

<!-- slide -->

# このスライドをどう作っているか

- [Markdown Preview Enhanced](https://shd101wyy.github.io/markdown-preview-enhanced/#/) (MPE)
    - VS Code/Atomのプラグインとして利用可能
    - すごく高機能なMarkdown処理系
    - 個人的にはVS Codeで使っています
- [mume](https://github.com/shd101wyy/mume)
    - MPEのコアにあたる変換エンジン (npmパッケージ)
    - 変換処理をスクリプト化するときに便利
- GitHub Pages: 静的ホスティング

<!-- slide -->

# 執筆お助けツール

- [textlint](https://github.com/textlint/textlint)
    - 英語・日本語の文法誤りをしてくれるツール
    - プラグインでスタイルやルールをインストールできる
    - [Collection of textlint rule · textlint/textlint Wiki](https://github.com/textlint/textlint/wiki/Collection-of-textlint-rule)
- [prh](https://github.com/prh/prh)
    - textlintと組み合わせて使う
    - 辞書を作っておくと、用語の誤りを指摘してくれる
    - [サンプルルール](https://github.com/prh/rules)のtechboosterだけでもかなり使える
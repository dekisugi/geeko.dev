---
title: GitHub Pages＆Jekyllでサイト名を設定する方法
created_at: 2019-11-28T05:05:15+0900
updated_at: 2020-02-22T01:41+0900
kind: article
---

# たかだかサイト名設定するのにどんだけ時間かかってんだって話

早い話が、以下の行を_config.ymlに追記すればいい。
> title: "設定したいサイト名"

## ヘルプがヘルプしてない件
[GitHub Pagesのヘルプ](https://help.github.com/ja/github/working-with-github-pages/about-github-pages-and-jekyll)読んでも[Jekyllのdocs](https://jekyllrb.com/docs/)読んでもサイト名の変え方が解らん。というか判らん。載ってないだろ。

結局[GitHub PagesにJekyllを使ってブログサイトを作る · To the backbone](https://blog.pinekta.tech/jekyll/update/2017/02/13/jekyllblog/)というブログ記事を読んで、それっぽいものを見つけた。_config.ymlにtitle:行を追加するというもの。詳しくは[このサイトのソレ](https://github.com/dekisugi/dekisugi.github.io/blob/master/_config.yml)を見てくれ。というか上に書いた^^;

これはあれだ。「サイトをローカルでビルドする」を実践した人はたぶん判るんだ。(ホスティングを提供してないので当たり前ながら)Jekyllのdocsもそれを前提に書いてるから、基本中の基本は自動生成されるファイルを嫁ってことなんだ。

ただね、GitHubヘルプには一言書いておいて欲しかったね。

いや誰かしらに聞けば即答だってのは解る。でもあえて一人でやってみようと思ったんだ。Google先生に訊くしかないじゃん。クソみたいなブログばっかヒットするじゃん。いつまでたっても判らないじゃん。ふぁーっきゅ！ふぁーっきゅふぁーっきゅー！Ｆ゛Ａ゛Ｑ゛！！　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　の整備を所望す！

というクソみたいなお気持ちがこの文章だ。5時で消すからな！…もう5時じゃねーか^^;

## 2020/02/22追記

[ここ](https://github.com/pages-themes/minimal#configuration-variables)に書いとるやないか！


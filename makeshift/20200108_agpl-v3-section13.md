---
title: (下書き)素人が解説！ AGPLv3 第13条
---


# {{ page.title }}


## 注意: この記事は執筆中です

完成するかは解りませんし、あるいは1から書き直すかもしれません。  
そして1月12日からは初場所と。放置フラグじゃん^^;

何かしらツッコミがありましたら[このトゥートへリプライを生やして](https://mstdn.maud.io/@dekisugi/103448423535397788)くださると助かります。[他の連絡手段](/contacts.html)でも構いませんが。


## 執筆中ということで、良さそうな文献リンク集

- [ネットワーク分散型ソフトウェアを想定したFSFライセンスのリリース \| OSDN Magazine](https://mag.osdn.jp/07/11/22/0144209) 
  - 「ライセンスを特徴付ける規定」の項を読むだけでも、AGPLv3に対して強くなれると思います。
- [GNU GPL v3 逐条解説書（第1版）][GPLv3解説書]
  - これを超えるGPLv3に関する日本語文献があったら教えろくださいって感じ。
  - GPLv3とAGPLv3はほとんど同じなので…
    - 数%追記すればAGPLv3に関する最強の日本語文献が出来上がる！
      - ので差分を作ってほしかった…
        - 無いなら自分で作ろう？
      - 実はAGPLv3も軽く取り上げられているし、和訳も載っている。
      - たとえAGPLv3第13条第1パラグラフへの解説が不十分でも、今の時点で既にAGPLv3に関しても最強の日本語文献なんじゃないだろうか？
        - AGPLv3第13条第2パラグラフについては、GPLv3第13条第1パラグラフの説明を読めば足りる[^section13]。
  - なお、まだ読んでません^^;
    - つまみ食いしただけ。
- [GNU公式サイト](https://www.gnu.org/)
  - [GNUライセンスに関してよく聞かれる質問](https://www.gnu.org/licenses/gpl-faq.ja.html)
    - [Frequently Asked Questions about the GNU Licenses](https://www.gnu.org/licenses/gpl-faq.en.html)
  - [www.gnu.orgのウェブページを翻訳するガイド](https://www.gnu.org/server/standards/README.translations.html)
  - [GNUプロジェクトの理念](https://www.gnu.org/philosophy/philosophy.html)
- [AGPLv3]
  - [mhatta訳]

## 筆者のトゥートを適当に並べる

もうこのページ、ただのメモじゃん？…最初からそうだったわ^^;

- [GPLのソフトをネットで公開しても、ソースの公開は求められた時にその人にだけすればいいんだって！　GPLv3「ダメです」　GPLv2「アリかもしれない。ただし…」](https://mstdn.maud.io/@dekisugi/103459571674064880)
- [このページで言いたかったことを1トゥートにまとめてみた奴](https://mstdn.maud.io/@dekisugi/103459579915927910)
- [姉弟子](https://mstdn.maud.io/@dekisugi/103459663869286934)


## 前書き？

> ソースよこせ、ソース嫁の精神、今こそ大事にしたい。  
> #インターネット老人会

というお告げが聞こえたので、[AGPLv3]を読むことを試みた。…いや読んだのはほとんど[非公式日本語訳][mhatta訳]の方ですが^^;

そしたらまあ、AGPLのことをさっぱり理解できてなかったということが露呈したので、だらだら書いてみたというのがこの記事でありんす。


## 我らがIPA

> AGPLv3 の内容は、第 13 条以外は GPLv3 と全く同じである。[^IPA][^section13]

やっぱり……そうか……　　
そうかなとは……思ってたんだけど……

[AGPLv3]の第13条は和訳してみてなんとなく理解できたので、後は[ここのページ](https://www.ipa.go.jp/osc/osslegal.html)にある[GPLv3解説書]さえ読んでおけばGPLバイリンガルになれるな！

というわけで強そうなPDFには書いてなさそうな[AGPLv3]の第13条について、なんとなく書いていこうと思います。PDFはそのうち読みます…たぶん^^;


## 「改造版でネットサービスやったらソースを公開しなさい」 - AGPLv3の第13条はとってもカンタン？

というか[AGPLv3]の第13条自体、

> Notwithstanding any other provision of this License,[^AGPLv3]  
> このライセンスに定められた他のあらゆる規定によらず、[^dekisugi]

とあるので、別に難しいことは考える必要はないです。書いてある通りに読むだけです。

単純に、

> (if your version supports such interaction)[^AGPLv3]  
> 改変版が交信機能を有している場合、[^dekisugi]

に該当する場合は、

> all users interacting with it remotely through a computer network[^AGPLv3][^interacting]  
> コンピュータネットワークにより遠隔交信する全てのユーザ[^dekisugi]

に対して、

> Corresponding Source of your version by providing access to the Corresponding Source from a network server at no charge, through some standard or customary means of facilitating copying of software.[^AGPLv3]  
> 改変版の対応するソースを、ソフトウェアを容易に複製できる一般的あるいは慣習的な方法によって、ネットワークサーバより無償で利用できるようにしなければならない。[^dekisugi]

上記の義務を負うっていう、実にシンプルな内容となっております。[^komakexekotaxaiindayo]

これはざっくり言うと「AGPLv3のソフトを改造してネットサービスを提供したら、それに接続できる**全員がソースコードを無料でダウンロードできるようにしておきなさい**」ということになります。実にカンタンですね！

…カンタンだと思うじゃん？


## 「GPLv3のままだけど、AGPLv3の条文が適用されます」 - AGPLv3の第13条のもう1つの役割(明らかに書きかけ)

[GPLv3解説書]を眺めてみたんですけれど…129ページ(141ページかもしれない)強すぎてここの条書く気が失せちゃったんですけどぉ…^^;

実はAGPLv3の第13条にはもう一つの役割があります。以下書きかけです。

とりあえず、条文は引用せずに訳注だけ書いておくと、こういうことである。

AGPLv3においては、GPLv3の著作物はGPLv3としたままで、AGPLv3の著作物と組み合わせて使用することが可能である。ただし、この第13条の前段(とってもカンタン？で紹介した条文)については、AGPLv3の著作物と組み合わせて使う限りは、GPLv3の著作物にも適用される。  
GPLv3のままというよりも、元に戻せるAGPLv3化と考えた方が理解しやすいかもしれない。

このことは例えば、AGPLv3のソフトウェアに機能を追加したいとして、ソースコード公開義務を回避するためにGPLv3のプラグインとして作るという小細工は、無意味であるということを意味する。そのGPLv3のプラグインごとソースコード公開義務の対象になる。


## お断り - ソースコードをどういった形式で配布すべきかについてはまだよく解ってません(そもそも書いてない)

そのへんは第5条に定義されてるっぽいので…気になる人は自分で読んでください^^;

あるいは[GPLv3解説書]でも読んだらいいんじゃないかな^^;


## おまけ

[AGPLv3]本文にて、「section」という語を用いているから、[mhatta訳]では「項」と訳してるんだなぁ。  
ただ今回は、IPAの[GNU GPL v3 逐条解説書（第1版）][GPLv3解説書]に従って、「条」と書いています。わりとどうでもいいですね^^;


[^IPA]: [オープンソフトウェア・センター　『OSS ライセンスの比較および利用動向ならびに係争に関する調査　調査報告書』(2011年2月14日改訂版)　情報処理推進機構、2010、p. 6](https://www.ipa.go.jp/files/000028335.pdf#page=10)

[^AGPLv3]: [GNU Affero General Public License - GNU Project - Free Software Foundation][AGPLv3]

[^dekisugi]: 筆者による「[^AGPLv3]」の参考和訳である。

[^mhatta]: [GNU Affero 一般公衆利用許諾書 (八田真行氏による非公式な日本語訳)][mhatta訳]

[^komakexekotaxaiindayo]: 上記説明は細かいところをすっ飛ばしてますが、現時点においてこれ以上の説明を求められると、正直苦しい。

[^section13]: メモ: GPLv3第13条第1パラグラフと、AGPLv3第13条第2パラグラフとは、4分の3くらい一致しているようだ。違うのはライセンス名と、最後の方だけである。

[^interacting]: [「interacting」の定義についてのトゥート](https://mstdn.maud.io/@dekisugi/103459623720418812)


[AGPLv3]: https://www.gnu.org/licenses/agpl-3.0.en.html "GNU Affero General Public License (Version 3)"

[mhatta訳]: http://gpl.mhatta.org/agpl.ja.html "GNU Affero 一般公衆利用許諾書 (八田真行氏による非公式な日本語訳)"

[mhattaのGPLv3訳]: http://gpl.mhatta.org/gpl.ja.html "GNU 一般公衆利用許諾書 (八田真行氏による非公式な日本語訳)"

[調査報告書]: https://www.ipa.go.jp/files/000028335.pdf "OSS ライセンスの比較および利用動向ならびに係争に関する調査 調査報告書"

[GPLv3解説書]: https://www.ipa.go.jp/osc/license1.html "GNU GPL v3 解説書：IPA 独立行政法人 情報処理推進機構"

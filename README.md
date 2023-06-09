# RPG_GUI
RRPPGG
READMEとは、リポジトリに訪れた人に "このプロジェクトが何なのか" をわかりやすく伝えるための説明書のようなものです。
いきなりソースコードを見るのは辛いので、まずはREADMEを読んで概要を掴んでもらうことが重要です。

人の第一印象は見た目が大事と言いますが、GitHubのリポジトリも同じ。

初めてリポジトリに訪れた人が興味を持つかどうか
自分のプロジェクトを使ってくれるかどうか
は、READMEにかかっていると言っても過言ではないと思います。
ではどのようなREADMEが人を惹きつける素敵なREADMEなのでしょうか？？

素敵なREADMEとは？
どのようなことを書けば素敵なREADMEになるのでしょうか？

1. わかりやすく！
何はともあれ、わかりやすく書くことが何より大事です。
初めてリポジトリに訪れたユーザがおそらく最初に目にするであろうREADME。
プログラムコードと同じくらい気持ちを込めて書きましょう :shamrock:

2. 適度に改行・見出しを入れる
READMEに限った話ではないですが、
メリハリもなくつらつらと文章が続いていると、読むのが辛くなる上
何が書いてあるのか直感的に理解するのが難しいですよね。

GitHubのREADMEは、GitHub Flavored Markdownと呼ばれる
GitHub独自要素を加えたMarkdown記法で書く必要があり、
HTMLの<h1>〜<h6>タグのように、見出しを1〜6段階で表現することができます。
Markdownをうまく使いこなして見やすい文章を心がけましょう。

GitHub Flavored Markdownの詳細はこちら
:point_right_tone1: 基本的な書き方とフォーマットの構文

3. バッジを追加する
READMEにこのようなアイコンが表示されているのを見たことはありませんか？
Screen Shot 2019-12-21 at 15.54.03.png

これはバッジと呼ばれるアイコンで、様々な情報を簡潔にわかりやすく表示することができます。
例えば下記のような情報をREADMEの冒頭に表示していると、信頼性が上がりますね！

GitHubのStar数
合計ダウンロード数/月間ダウンロード数
ライセンス
使用しているパッケージのバージョン
テストをパスしたコードであること(build可能かどうか)
コードカバレッジ率(ソースコードがテストされた割合)
どうやってバッチを表示するの？
これらのバッチはGitHubと連携して各サービスを通して表示することができます。
下記にいくつかバッジサービスを記載しておきますので、是非試してみてください！

shields.io
GitHubのプロジェクトのURLを指定するだけで様々な情報を自動的に取得し、バッチを作成してくれる
色や形などスタイルのカスタマイズも可能
独自のバッチも作ることができる
travis-ci.org/
JENKINSなど、ビルド結果を表示
coveralls.io
コードカバレッジ率を表示
:star: 参考
shields.ioを使って私のとあるプロジェクトのFORKの数をバッジにしてみました
:point_down_tone2: :point_down_tone2:
my badge

4. ビジュアル的に訴える
文字ばかりのREADMEは見ていて楽しくないですよね。
プロジェクトのロゴやバナー、もしUIがあるのであればそのスクリーンショットを貼るのもわかりやすくてとても良いですし、
DemoをGifアニメで作成して表示するとよりわかりやすくなります :sparkles:
上記で記載したバッジもビジュアルで訴える１つの良い方法です。

実際に書いてみよう！
では、実際に何を書けば良いのか、何に気をつければ良いのか、具体的に見ていきましょう！

基本項目
「リポジトリの説明・概要」「目的」「使い方」は基本情報として書くようにしましょう。
初めてリポジトリに訪れたユーザにとって、これらの基本情報はとても有益です。

エンジニア向け情報
「使っている言語」「バージョン」などテクニカルなことを書くのも良いですね。
オープンソース化して誰かに使ってもらうことを意識しているのであれば、コントリビューションガイドのような項目を追加しても良いでしょう。

:bulb: コントリビューションガイド としては、Vue.js 公式サイト日本語翻訳ガイド がとてもわかりやすいです。
どのような流れでコントリビューションすれば良いのか、注意事項などがとてもわかりやすく記載されていますので、ご自身のリポジトリをOSS化することを検討している方は是非ご一読を！

文章が長くなるようであれば冒頭に目次を追加するなり、別のREADMEに分けて書くとよりわかりやすくなります。

ポートフォリオとして
中には自分のポートフォリオの一部として、GitHubを外部に公開する人もいるでしょう。
「使っている技術」はもちろんのこと、「システム構成図」「こだわったポイント」などを明記して、ガンガンアピールしましょう！

Webで公開できる物については、Heroku や Vercel のホスティングサービスを使って自分の作品もパブリックに公開しましょう！:rocket:

ちなみに、GitHub上でも GitHub Pages という機能を使って静的コンテンツのホスティングが可能です。

静的コンテンツのホスティングであれば、個人的におすすめなのは surge 。
Nuxt.js のHPにもデプロイ先の候補の１つとして書かれています。
マジで、手軽に、簡単に、即時に、ホスティングできるので自分のテスト環境として利用するのにもおすすめです！

その他
既にリポジトリを知っているユーザに対しては、アップデート情報や今後の機能拡張予定なども嬉しい情報です。

常に読む人の気持ちを考えながら書くことを忘れずに！:thumbsup_tone1:

READMEじゃないけど...
GitHubにはAboutという項目があります。ここにはリポジトリの短い説明文を載せることができます。

下記写真の赤枠内、右上にある歯車アイコンをクリックすると、
about.png

このようなポップアップが表示されますので入力しましょう。
ここに記載があると、READMEを読まなくてもリポジトリの概要を掴むことができますね。忙しいリクルーターやエンジニアの方々には嬉しい情報になるのではないでしょうか？:thumbsup_tone1:
detail.png

記載する項目をリストアップしてみましたので参考にしてください。

バッジ
プロジェクトのタイトル
ロゴやバナー画像
プロジェクトの概要説明
サービスのスクリーンショット画像 or GIFアニメ（デモ）
目次
必要条件
使用言語、環境、テクノロジー
システム構成図
使い方
インストール方法
テスト方法
デプロイ方法
こだわりポイント
ライセンス情報
今後の計画

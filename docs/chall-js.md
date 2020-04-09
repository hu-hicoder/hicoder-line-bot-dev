- このセクションではフロントエンドのJavaScript、npmの環境構築、バックエンドJavaScript(Node.js)を学びます。

# 課題の前に
- 前回の課題でhicoder-line-bot-devでbranchがdevのままで終わっていると思います。
- 他の人がセーブポイントを上書きしたとき、gitは自動で追従してくれません。`git pull`でそのセーブデータをリモート(GitHub側)からとってくる必要があります。
- masterに切り替えて、git pullしましょう
```
git branch master
git pull
```
- うまくマージされたでしょうか。うまく行かない場合、discordにエラーメッセージを添えて連絡してください。
- nanoというエディタが開くときがあります。mergeしてよいので、Ctrl+xで保存してください(画面下に使い方が出てくるのでそれを読めば大丈夫です)
- 再びプルリクを送るときはmasterではないブランチに移動してからプルリクを作ってください。
- masterはセーブデータ置き場だと思うとよいでしょう。どうしてもうまくいかなくなったら、リポジトリごと消してもう一度`git clone ...`(...はリポジトリのURL)からはじめていけば大丈夫です。


# 課題11
- JavaScriptを学ぶに当たって必要な基礎知識を調べてもらいます。

## 手順
- 以下の6つの質問に答えて、その答えを`hicoder-line-bot-dev/docs/workspace/<yourname>`以下のMarkdownファイルに書き込んでください。そしてこのリポジトリに対しpull requestを送ってください。
- Q1. JavaScriptはどんなところで使われていますか？
- Q2. ES2015, ES2016という単語はJavaScriptに関係しています。どういう意味でしょうか？
- Q3. Chrome DevToolsという言葉について調べてみてください。Chrome以外のブラウザの方は、これと同じようなものが自分の普段使っているブラウザにないか探してみてください。
- Q4. 文法を調べてみてください。まだ実際に書かなくても大丈夫です。`if`, `for`, `let`, `const`, `console.log()`について調べてください。この他にひとつ以上、自分で気になった文法について紹介してください。
- Q5. クライアントサイドJavaScriptとサーバーサイドJavaScriptの違いを自分なりに説明してください。
- Q6. Nodejsとは何でしょうか？調べてみてください。
- これらの質問に対し、以下のリンクが参考になります。
- https://developer.mozilla.org/ja/docs/Web/JavaScript/Guide/Introduction
- https://developer.mozilla.org/ja/docs/Web/JavaScript
- あまりJavaScriptを書ける気がしない人はチュートリアルをこなすと良いと思います。 https://prog-8.com/ などのサイトで練習してみてください。(無料版でも十分だと思います) 

# ###ここから未完成パート###

# 課題12
- glitchの使い方を見て、フロントエンドJavaScriptを書く環境構築をします。

## 手順
- https://glitch.com/ にアクセスして、hello-webpageからwebpageの雛形を作ります。
- ここでは、どこに何を書くかを知ることが大切です。
- 左のFileのところで編集したいファイルを選択します。
- index.htmlがHTMLを書く場所です。
- script.jsがJavaScriptを書く場所です。
- style.cssがCSSを書く場所です。
- HTMLは枠組みを作ります。
- CSSは見た目の装飾をします。
- JavaScriptはボタンを押したときの動作など、動きのあるものやイベントを扱います。

# 課題13
- glitchでフロントエンドJavaScriptを書いて、webpageを作ってみよう(HTML/CSSも多少書きます。)

## 手順
- 

## 課題13.1~
- 静的Websiteと動的website
- github.io
- /homeに作る
- localでホストする方法 https://docs.microsoft.com/ja-jp/windows/wsl/wsl2-ux-changes WSL1でのIPaddressの探し方、pythonの導入とpython3 -m http.serverの使い方 
- HTMLを書く
- CSSを書く
- JSを書く
- github.ioでのHosting
- 変更の仕方
- その後の選択肢 React, Vueの紹介, CSS Animation, hugoのようなstatic site generator

# 課題14
- glitchから離れて、GitHubに自分のwebpageを作ってみましょう。
- ここがひとつのゴールになります。成果として、自分のホームページが作れるので頑張りましょう！

# 課題15
- バックエンドJavaScriptを書く準備をします。環境構築です。

# 課題16
- バックエンドJavaScriptを書いてみましょう

# 課題17
- バックエンドJavaScriptでなにか作ってみましょう。.gitignoreの使い方も学びます。

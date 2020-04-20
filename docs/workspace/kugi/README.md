# kugi's TASKs

## Project Setup
- [x] 課題1

  工学研究科2年のkugiです!よろしくお願いします!
https://github.com/kugimasa

- [x] 課題2

  自分が使っている[配色ツール](https://coolors.co/74d3ae-a6c48a-f6e7cb-dd9787-6cbe40)を紹介します！
５色の配色をランダムで生成してくれるツールです。
一部ロックしたりもできます。

  あとGlitchで画像を入れたいときは

  `<img src="assets/[image_name]">`

  とかではなく、`assets`で生成されるURLをコピーして使う必要があるみたいです。
  ![](assets/chal_2.png)

- [x] 課題3

  VSCode入ってます👍
- [x] 課題4

  Macユーザです💻


## How2Use git and markdown
- [x] 課題5

  `htop`入れてみました！
- [x] 課題6・7・8・9・10

  `git`関連まとめちゃいました...💦🙇‍♂️

  `fork`したものからPR送りました👍
  `fork`したものからPR送るのは初だったのでちょっとドキドキしました👀

## Frontend & Backend in JavaScript
- [x] 課題11
  - Q1 : **JavaScript**はウェブページをインタラクティブにするために用いられる言語です。

  - Q2 : JavaScriptが広く世界で用いられるためにEcma Internationalが標準化を行っています。
    - **ES2015** : 別名ES6(ECMAScript 6th edition)で2015年に標準化されたものです。
    主に追加された機能として、`let`や`const`が追加されたことや、`=>`が使えるようになりました。

      詳しくは[ドキュメント(Standard ECMA-262)](https://www.ecma-international.org/publications/standards/Ecma-262.htm)を参照

    - **ES2016** : 2016年に標準化されたECMAScriptです。
      主に以下の機能が追加されました。

      `Array.prototype.includes` : 指定した要素が配列の中に含まれているかを判定します。
      `Exponentiation Operator` : べき乗計算ができるようになりました。

  - Q3 : **Chrome DevTools**はGoogle Chromeに組み込まれたウェブ作成およびデバッグツールのセットです。([引用](https://developers.google.com/web/tools/chrome-devtools?hl=ja))

    |ブラウザ|開発ツール|リンク|
    |:--|:--|:--|
    |Firefox|Firefox Browser Developer Edition|https://www.mozilla.org/ja/firefox/developer/|
    |Safari|Safari for Developers|https://developer.apple.com/safari/|
    |Microsoft Edge|Microsoft Edge Developer Tools|https://docs.microsoft.com/en-us/microsoft-edge/devtools-guide|

  - Q4 : JavaScript文法([リファレンス](https://developer.mozilla.org/ja/docs/Web/JavaScript/Reference)参照)
    - `if` : 指定された条件が**truthy**である場合文を実行する。

      **falsy** : `false`, `0`, `-0`, `0n`, `""`, `null`, `undefined`をとる値

      **truthy** : **falsy**以外の値

      ```js
      if (条件文) {
        実行する処理
      }
      ```
    - `for-in` : 指定したオブジェクトの列挙可能なプロパティに対して**順不同**で反復処理をする。
      ```js
      for (列挙可能なプロパティ in オブジェクト) {
        実行する反復処理
      }
      ```
    - `for-of` : `String`や`Array`といった反復可能オブジェクトに対して反復処理をする。
      ```js
      for (オブジェクトの要素 of 反復可能オブジェクト)
      {
        実行する反復処理
      }
      ```
    - `let` : 局所変数を宣言するキーワード。定義された変数はブロックスコープを持つ。
    - `const` : `let`キーワードで定義する変数と同様にブロックスコープを持ち、定数への再代入はできない。
    - `console.log()` : デバッガのWebコンソールにメッセージを出力する。
  
  - Q5 : **クライアントサイド**のJavaScriptはボタン操作やフォームへの入力などのユーザが行う操作に対してブラウザやDOMを制御するオブジェクトを用いることで応答できるようになります。
  
    **サーバーサイド**のJavaScriptはサーバーを稼働することでアプリケーションとデータベース間でデータのやりとりを行ったり、サーバー上のファイルをオブジェクトを介して操作することができます。
  
  - Q6 : **Node.js**は非同期型のイベント駆動のJavaScript環境でGoogleのV8 JavaScriptエンジン上に構築されています。Q2でも出てきた **ECMAScript 2015(ES6)** をベースに開発されています。特徴として必要なときにのみコールバックが発火されます。
  詳しくは[ドキュメント](https://nodejs.org/ja/docs/)を参照。


- [x] 課題12
  - [x] HTMLをつかっている
  - [x] CSSで見た目を整えている
  - [x] 重要: JavaScriptを用いて、動きのあるwebsiteを作っている
  
  - websiteの[リンク](https://kugi-web-gl.glitch.me/)
  - codeの[リンク](https://glitch.com/edit/#!/kugi-web-gl?path=index.html:1:0)

  使用したカラーコード
  ```
  PEARL AQUA: #84DCC6
  BRICK RED: #C33C54
  DARK SLATE GRAY: #254E70
  METALLIC SEAWEED: #0C7489
  TEAL BLUE: #37718E
  ```

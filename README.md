# web

- <b>import.css</b>
目的別に分割化したファイルをまとめてインクルードするためのcssファイル。
    - <b>normalice.css</b>
    ブラウザ間の表示差異をなくし、作成者の意図通りにスタイリングを行なうためのCSSファイルの一つ。
    以前はブラウザに初期設定されているものを完全にリセットするreset.cssが使用されていたが、初期設定の全てが悪くない理由から、長所はそのまま残すnormalize.cssが利用されている。
    - <b>base.css</b>
    wrapperやheader,footerなど、ベースとなる部分のcssを書く。
    - <b>common.css</b>
    汎用的に使用するaタグや、h1などの見出し要素、そのほか、汎用的なクラスのcssを書く。
    - <b>module.css</b>
    コンテンツのcssを書く。

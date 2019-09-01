# ヘッド要素

## JavaScript

```html
<script
    type="text/javascript"
    src="http://ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js"
></script>
<script type="text/javascript" src="js/common.js"></script>
```

-   `body`の`header`と`footer`の表示を行う為の js 読み込み。
-   レンダリングに必要な為、最初に `head` で読み込む必要がある。

## CSS

```html
<link
    href="https://fonts.googleapis.com/css?family=Open+Sans:300,400"
    rel="stylesheet"
/>
<link rel="stylesheet" href="/css/styles-merged.css" media="screen" />
<link rel="stylesheet" href="/css/style.min.css" media="screen" />
<link rel="stylesheet" href="/css/custom.css" media="screen" />
```

-   font の読み込み。
-   テンプレート css 読み込み。
-   カスタムテンプレート css の読み込み。

## Metadata

```html
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>ソフトメディア研究会</title>
<link
    rel="shortcut icon"
    href="/img/favicon.ico"
    type="image/vnd.microsoft.icon"
/>
<meta
    name="description"
    content="パソコン等を使い創作活動を行うサークルです。
    プログラム班、マルチメディア班、 DTM班があり、年に２回ある大きなイベント、文化の祭典と津田沼祭にサークルとして各自が作品を出品します。
    発表する作品は、基本的に日々の活動の中で制作したものです。制作物はゲーム、音楽、CG等があり、それぞれの班がコラボして一つの作品を作ります。"
/>
<meta name="keywords" content="ソフメ,ソフトメディア研究会,sofme" />
```

-   `favicon`の設定
-   `Title`の設定
-   `description`の設定 トップページのみ

## Twitter Card

別ページにて

-   [リンク]()

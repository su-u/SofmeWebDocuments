# Google Analytics

## 概要

サイトのアクセス解析に Google Analytics を利用してる。
ただしいデータを取得するためにも、全ページに正しく記述する必要がある。

## ページに記述するコード

```html
<script type="text/javascript" src="/js/analytics.js"></script>
```

上記のコードを記述する。

## 本体

```html
document.write('<script
    async
    src="https://www.googletagmanager.com/gtag/js?id=UA-123456789-1"
></script
>'); window.dataLayer = window.dataLayer || []; function gtag(){
dataLayer.push(arguments); } gtag('js', new Date()); gtag('config',
'UA-116699912-1'); gtag('js', new Date()); gtag('config', 'UA-116734797-1');
```

このコードを呼び出している。

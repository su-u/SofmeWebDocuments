# ヘッダー

## 概要

ヘッダーは全ページ共通している。現在してないのは、旧 M3 ページくらい。
全ページ共通しているものを別途用意するのは、更新時手間がかかるので共通部分として抜き出している。

## 読み出し

コードの読み出しは、`/js/common.js`の``header`関数が行っている。
事前に js の読み込みが必要。

## コード

```html
<header role="banner" class="probootstrap-header">
    <div class="container">
        <div class="icon-wrapper">
            <a href="/index.html"
                ><img class="header-icon" src="/img/sofme_icon.svg"
            /></a>
            <a href="/index.html" class="probootstrap-logo"
                >ソフトメディア研究会</a
            >
        </div>
        <a href="#" class="probootstrap-burger-menu visible-xs"> <i></i> </a>
        <div class="mobile-menu-overlay"></div>
        <nav role="navigation" class="probootstrap-nav hidden-xs">
            <ul class="probootstrap-main-nav">
                <li id="menu-home">
                    <a href="/index.html" title="ホーム">ホーム</a>
                </li>
                <li>
                    <a href="/join.html" title="新入生ページ" id="menu-join"
                        >新入生ページ</a
                    >
                </li>
                <li>
                    <a
                        href="/program/index.html"
                        title="プログラム班のページ"
                        id="menu-program"
                        >プログラム班</a
                    >
                </li>
                <li>
                    <a
                        href="/multi/index.html"
                        title="マルチメディア班のページ"
                        id="menu-multi"
                        >マルチ班</a
                    >
                </li>
                <li>
                    <a
                        href="/dtm/index.html"
                        title="DTM班のページ"
                        id="menu-dtm"
                        >DTM班</a
                    >
                </li>
            </ul>
            <div class="extra-text visible-xs">
                <a href="#" class="probootstrap-burger-menu"> <i>Menu</i> </a>
            </div>
        </nav>
    </div>
</header>
```

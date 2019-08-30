# トップページ

<!-- TOC -->

-   [トップページ](#トップページ)
    -   [スライドショー画像更新](#スライドショー画像更新)
    -   [メインメニュー](#メインメニュー)
    -   [イベント](#イベント)
        -   [アドベントカレンダーリンク](#アドベントカレンダーリンク)
    -   [ABOUT](#about)
        -   [ソフトメディア研究会とは](#ソフトメディア研究会とは)
        -   [活動内容について](#活動内容について)
    -   [トピック](#トピック)
    -   [メジェドについて](#メジェドについて)
    -   [以前あった要素](#以前あった要素)

<!-- /TOC -->

## スライドショー画像更新

トップにスライドショーがある。

スライドショー全体

```html
<section class="probootstrap-slider flexslider">
    <div id="slide" class="slider-pro">
        <div class="sp-slides">
            <div class="sp-slide">
                <img
                    class="sp-image"
                    src="/img/2019_05_26_BunsaiHeader.jpg"
                    alt="文祭ヘッダー画像 作:HarU"
                />
            </div>
            <div class="sp-slide">
                <img class="sp-image" src="/img/01.jpg" />
            </div>
            <div class="sp-slide">
                <img class="sp-image" src="/img/02.jpg" />
            </div>
            <div class="sp-slide">
                <img class="sp-image" src="/img/03.jpg" />
            </div>
        </div>
    </div>
</section>
```

各要素は

```html
<div class="sp-slide">
    <img class="sp-image" src="/img/03.jpg" />
</div>
```

-   時間的にも、操作的にも、4、5 枚がベストだと思う。
-   画像サイズが少々特殊なため、気を付ける。
-   FullHD での表示で、スライドショーの下にある「メインメニュー」の各班の要素が見えるようにしたかったため、このサイズになっている。
-   スライドショーには、`slider-pro`ライブラリを使用。[GitHub リンク](https://github.com/bqworks/slider-pro/)
-   スライドショーの設定は、別途`/js/slider-pro/slider-pro.js`に記述してある。仕様については GitHub を参照する。

## メインメニュー

現在は、3 班へのリンクがあり、その上に新入生向けのリンクがあります。
各自自分の好きなジャンルへ飛ぶことができる + 新入生向けのページへ誘導することが目的。

## イベント

イベントがあるときは、ここに書きます。
ここが古いままになるとサイト全体の印象が下がります。ある程度の頻度で更新してください。
例）

-   新入生歓迎会
-   コミケ
-   文化の祭典
-   津田沼祭
-   デジゲー博
-   M3
-   コミティア
-   アドベントカレンダー

各ページを作成し、簡単な説明を書いたあとにリンクを貼ってください。

### アドベントカレンダーリンク

```html
<div class="probootstrap-section">
    <div class="container">
        <div class="row">
            <div class="col-md-12 text-center section-heading">
                <h2>Event</h2>
            </div>
        </div>
        <div class="row">
            <div class="col-md-12">
                <h2 class="border">ソフメアドベントカレンダー</h2>
                <p>${アドベントカレンダーについての説明}</p>
                <p>
                    <a
                        href="_カレンダーへのリンク_"
                        role="button"
                        class="btn btn-primary btn-sm"
                        title="_title_"
                        >アドベントカレンダーページへ</a
                    >
                </p>
            </div>
        </div>
    </div>
</div>
```

## ABOUT

### ソフトメディア研究会とは

本研究会の概要だけ書いておく。

```html
<h2 class="border">ソフトメディア研究会とは？</h2>
<p>${説明}</p>
```

### 活動内容について

```html
<h2 class="border">活動内容について</h2>
<p>${説明}</p>
```

## トピック

ある程度の更新頻度を保つ。勝手に並んでいくので追加していく。
個人的には、2 列程(6 個)ほどあればいいのかと思う。

```html
<div class="col-md-4">
    <div class="probootstrap-card">
        <div class="probootstrap-card-media">
            <img
                src="/img/${画像}"
                class="img-responsive img-border"
                alt="${画像の説明}"
            />
        </div>
        <div class="probootstrap-card-text">
            <h2 class="probootstrap-card-heading mb0">${タイトル}</h2>
            <p class="category">${活動日]</p>
        </div>
    </div>
</div>
```

-   画像サイズは`360x270`にする。
-   画像サイズを変更する場合は、ほかの画像も同時に変更する。
-   画像の`alt`属性を忘れずに

## メジェドについて

ソースコードの下部にあるメジェドの AA はネタ。
特に深い意味はない。
気になる人は、めじぇ走で検索。
問題があれば消してしまっても構わない。

## 以前あった要素

-   部長挨拶
    挨拶のデータが来ない為削除

# トップページ

<!-- TOC -->

-   [トップページ](#トップページ)
    -   [メインメニュー](#メインメニュー)
    -   [イベント](#イベント)
        -   [アドベントカレンダーリンク](#アドベントカレンダーリンク)
    -   [ABOUT](#about)
        -   [ソフトメディア研究会とは](#ソフトメディア研究会とは)
        -   [活動内容について](#活動内容について)
    -   [トピック](#トピック)
    -   [以前あった要素](#以前あった要素)

<!-- /TOC -->

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

ある程度の更新頻度を保つ。

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

## 以前あった要素

-   部長挨拶
    挨拶のデータが来ない為削除

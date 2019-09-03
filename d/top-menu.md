# DTM 班トップメニュー

## 概要

DTM 班のアクセスポイント。
ここからすべてのページに飛べるようにする。
DTM 班の新譜や、新規イベントなどをのせてもよい。

## メニュー

コンポ―ネントへ

-   [コンポ―ネント/メニュー]()

## 新譜

新譜がでたら更新する。

```html
<div class="col-md-4">
    <div class="probootstrap-card with-hover">
        <div class="probootstrap-card-media">
            <img
                src="${新譜ジャケット画像リンク}"
                class="img-responsive img-border"
                alt="${新譜名}"
            />
        </div>
        <div class="probootstrap-card-text new-song">
            <h2 class="probootstrap-card-heading mb0">
                ${新譜名}
            </h2>
        </div>
        <a href="${新譜サイトへのリンク}"></a>
    </div>
</div>
```

## 活動紹介

現在放置気味。削除する可能性あり。

以下は、例としてとらえて貰えれば。

```html
<div class="col-md-4">
    <div class="probootstrap-card">
        <div class="probootstrap-card-media">
            <img
                src="${イベント画像}"
                class="img-responsive img-border"
                alt="${イベント名}"
            />
        </div>
        <div class="probootstrap-card-text">
            <h2 class="probootstrap-card-heading mb0">${イベント名}</h2>
            <p class="category">${イベント日程}</p>
        </div>
    </div>
</div>
```

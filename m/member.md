# マルチ 班メンバーページ

## 概要

唯一きちんと活動しているメンバーページ。
各自にアイコンを提出してもらい、一覧にする。

アイコンと一言が載っている。

基本的に活動してる回生(1 ～ 3)をメインに表示し、卒業生は別ページに移動している。

## メンバー 1 人

```html
<div class="member">
    <img
        src="${アイコンの画像}"
        class="img-responsive img-border"
        alt="${画像の説明}"
    />
    <div class="member-text">
        <p class="name">${名前}</p>
        <p class="message">${一言}</p>
    </div>
</div>
```

## 回生

```html
<div class="container">
    <h3 class="multi-member-grade">2回生</h3>
    <div class="row">
        <div class="member-wrapper">
            ${メンバーを並べる}
        </div>
    </div>
</div>
```

-   自動的に幅が調整される。
-   退部した部員を消し忘れないようにする。
-   OBOG ページもデザインは同一。

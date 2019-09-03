# プログラム班トップメニュー

## 概要

プログラム班へのアクセスページ。

## メニュー

コンポ―ネントへ

-   [コンポ―ネント/メニュー]()

## 最新の活動内容

適宜更新する。
現状、日付はない為放置してもそこまで問題ではないが、更新してほしい。

### 全体

```html
<div class="row">
    <div class="col-md-12 text-center section-heading">
        <h2>最新の活動情報</h2>
    </div>
</div>

${個別の要素}
```

### 個別の要素

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
            <h2 class="probootstrap-card-heading mb0">
                ${簡易的なメッセージ}
            </h2>
        </div>
    </div>
</div>
```

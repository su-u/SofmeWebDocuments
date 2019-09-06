# 各班ページメニュー

## 概要

各班の詳細ページへの繋ぎを担うメニューページ。
アイコンは、初期時パワーポイントで作成したものをそのまま使用している。
機会があれば新規作成してもらいたい。

メニューは全班共通。
変えるときはすべて一度に変えてある程度の統一感を。

## 個別

```html
<div class="col-md-4">
    <div class="probootstrap-card with-hover">
        <div class="probootstrap-card-media">
            <img
                src="${アイコンファイルパス}"
                class="img-responsive img-border"
                alt="${説明}"
            />
        </div>
        <div class="probootstrap-card-text">
            <h2 class="probootstrap-card-heading mb0">${タイトル}</h2>
        </div>
        <a href="${リンク先}"></a>
    </div>
</div>
```

## 全体

```html
<section class="probootstrap-section">
    <div class="container">
        <div class="row">
            <div class="col-md-12 text-center section-heading">
                <h2>メニュー</h2>
            </div>
        </div>
        <div class="row">
            <div class="col-md-4">
                <div class="probootstrap-card with-hover">
                    <div class="probootstrap-card-media">
                        <img
                            src="${アイコンファイルパス}"
                            class="img-responsive img-border"
                            alt="${説明}"
                        />
                    </div>
                    <div class="probootstrap-card-text">
                        <h2 class="probootstrap-card-heading mb0">
                            ${タイトル}
                        </h2>
                    </div>
                    <a href="${リンク先}"></a>
                </div>
            </div>
            ${次のメニュー}
        </div>
    </div>
</section>
```

## メモ

画像に文字が入ってるので、テキストの文字は要らないのではないか。
しかし、SEO 的には画像の文字ではなく、テキストの文字の方が好ましい。

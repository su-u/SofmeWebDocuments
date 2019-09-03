# プログラム班講座資料更新

## 概要

プログラム班の講座にて使用した資料を公開する。

## 年度/講座ごとの処理

```html
<div class="col-md-12 tableList">
    <div class="panel panel-default">
        <div class="panel-heading">
            <h3 class="panel-title">
                ${講座/年度}
            </h3>
        </div>
        <div class="panel-body">
            ${リスト}
        </div>
    </div>
</div>
```

## リストの中身

```html
<li>
    19/08/19
    <a
        class="program-linkColor"
        href="${資料へのリンク}"
        target="_blank"
        rel="noopener"
        >${講座名}</a
    >
    ${担当者やその他}
</li>
```

# マルチ班講座ページ

## 概要

-   マルチ班で行われた講座の資料を掲載する。
-   個人情報や、内部情報が資料に記述されていないか確認する。
-   2019 年度より、資料を Gooogle Drive に保存するようにした。

## 年度ごと

```html
<div class="col-md-12 tableList">
    <div class="panel panel-default">
        <div class="panel-heading">
            <h3 class="panel-title">${年度}</h3>
        </div>
        <div class="panel-body">
            ${リスト}
        </div>
    </div>
</div>
```

## 講座

```html
<li>
    ${日付}
    <a
        class=" multi-study multi-linkColor"
        href="https://drive.google.com/file/d/1VVsQNu_X4D12E2O-AECCsA3y_Js_vtxl/view?usp=sharing"
        target="_blank"
        rel="noopener"
        >${講座名}</a
    >
    ${担当者、メモ}
</li>
```

## 全体

```html
<section class="probootstrap-section">
    <div class="container">
        <div class="col-md-12 tableList">
            <div class="panel panel-default">
                <div class="panel-heading">
                    <h3 class="panel-title">${年度}</h3>
                </div>
                <div class="panel-body">
                    ${リスト}
                </div>
            </div>
        </div>
    </div>
</section>
```

# DTM 班講座ページ

## 年度ごとの処理

```html
<div class="col-md-6 tableList">
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

上記のコードを以下の部分に追加する。

```html

<section class="probootstrap-section">
        <div class="container">

            ${ここに追加}

            <div class="col-md-6 tableList">
                <div class="panel panel-default">
                    <div class="panel-heading">
                        <h3 class="panel-title">${前年度}</h3>
                    </div>
                    <div class="panel-body">
                        ${前年度リスト}
                    </div>
                </div>
            </div>
            <div class="col-md-6 tableList">
                <div class="panel panel-default">
                    <div class="panel-heading">
                        <h3 class="panel-title">${前々年度}</h3>
                    </div>
                    <div class="panel-body">
                        ${前々年度リスト}
                    </div>
                </div>
            </div>

            ${それ以前のリスト}
        </div>
    </div>
</section>

```

## リストの追加方法

```html
<div class="col-md-6 tableList">
    <div class="panel panel-default">
        <div class="panel-heading">
            <h3 class="panel-title">${年度}</h3>
        </div>
        <div class="panel-body">
            ${リストを追加する位置}
        </div>
    </div>
</div>
```

以下のリストを上記の部分に挿入する。

```html
<li>
    <a class="dtm-study" href="course/_年度_/_ファイル名_">${リンク名}</a>
</li>
```

例 2018 年度)

```html
<div class="col-md-6 tableList">
    <div class="panel panel-default">
        <div class="panel-heading">
            <h3 class="panel-title">2018年度</h3>
        </div>
        <div class="panel-body">
            <li>
                <a
                    class="dtm-study"
                    href="course/2018/2018_dtmterm_1(silver).pdf"
                    >DTM班 第一回講座 「DTMの概要」</a
                >
            </li>
            <li>
                <a
                    class="dtm-study"
                    href="course/2018/2018_dtmterm_2(silver).pdf"
                    >DTM班 第二回講座 「DAW」</a
                >
            </li>
            <li>
                <a
                    class="dtm-study"
                    href="course/2018/2018_dtmterm_3(silver).pdf"
                    >DTM班 第三回講座 「音楽理論」</a
                >
            </li>
            <li>
                <a
                    class="dtm-study"
                    href="course/2018/2018_dtmterm_4(silver).pdf"
                    >DTM班 第四回講座 「エフェクト」</a
                >
            </li>
        </div>
    </div>
</div>
```

-   リンク名は統一する。

```
DTM班 第_回数_講座 「${講座名}」
```

例 2018)

```
DTM班 第一回講座 「DTMの概要」
DTM班 第二回講座 「DAW」
```

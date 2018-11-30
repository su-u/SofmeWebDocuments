# アドベントカレンダー

## アドベントカレンダーカレンダーリスト

```html
<tr>
    <td class="date color">_日付_</td>
    <td class="title"><a href="_javascript:void(0)_">_タイトル_</a></td>
    <td class="icon"><img src="icon/_filename_" class="icon" /></td>
    <td class="author">_担当者_</td>
</tr>
```

-   `tr`タグの塊で 1 日分
-   `title`のリンクには記事のページのリンクを貼るが、公開前にはリンクを消さなければならないので`javascripst:void(0)`をリンク先に指定し、リンクを消す。
-   `icon`が無い場合には、タグごと消しておく。

## アドベントカレンダーリスト全体

```html
<section class="probootstrap-section">
    <div class="container">
        <div class="row">
            <div class="col-md-12">_アドベントカレンダーの説明_</div>
        </div>
        <div class="row calendar-date">
            <table>
                <thead>
                    <tr>
                        <th class="date">日付</th>
                        <th class="title">タイトル</th>
                        <th class="icon"></th>
                        <th class="author">担当</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td class="date color">_日付_</td>
                        <td class="title">
                            <a href="_リンク_">__記事タイトル</a>
                        </td>
                        <td class="icon">
                            <img src="icon/_アイコンファイル名_" class="icon" />
                        </td>
                        <td class="author">_担当者</td>
                    </tr>
                </tbody>
            </table>
        </div>
    </div>
</section>
```

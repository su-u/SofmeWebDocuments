# アドベントカレンダー

## ソフメアドベントカレンダーとは


## 活動履歴
- 2018年11月後半：企画
- 2018年11月30,31日ごろ：デザインなどの事前準備
- 2018年12月1日~2018年12月24日：手動更新

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
-   `icon`が無い場合には、`img`タグごと消しておく。

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

## アドベントカレンダー記事作成

1. md 形式の記事を提出してもらう。
    md以外の場合は人力にてmdに変換し、保存しておく。不明点などは執筆者に確認をとる。
1. md 記法にミスなどがある場合は修正する。(知識が必要)
1. 記事に誤字や権利的に問題が無いか確認する。
1. md 形式の記事を html に変換する。
1. 変換したものを所定の場所に張り付けする。

    ```html
    <section class="probootstrap-section">
        <div class="container">
            <div class="item">_ここに記事を入れる_</div>
        </div>
    </section>
    ```

1. タイトルを書く。
1. 担当者を書く。
1. 確認をする。**スマホ**表示も忘れずに。

```html
<section class="probootstrap-slider flexslider">
    <ul class="slides">
        <li style="background-image: url(/img/person_1.jpg);" class="overlay2">
            <div class="container">
                <div class="row">
                    <div class="col-md-12 text-center">
                        <div class="slides-text probootstrap-animate" data-animate-effect="fadeIn">
                            <h2>_記事タイトル_</h2>
                            <p>_担当者_</p>
                        </div>
                    </div>
                </div>
            </div>
        </li>
    </ul>
</section>
```

## アドベントカレンダー記事内画像

1. 画像を提出してもらう。
1. 画像を圧縮する。大きすぎる場合はリサイズする。縦500弱くらいが望ましいかと。
1. 指定のディレクトリに画像を置く。
   `img/_担当者名_/_ファイル名_`
   とする。担当者名は略名でも可。
1. リンクを記事内に張り付ける。
1. 以下の処理をする。

    ```html
    <img src="_リンク_" alt="_画像説明_" class="img-responsive" />
    ```

    - クラスを追加する。
        - 追加しないと、スマホで表示したときにデザインが崩れる。
    - `alt`属性に説明を書く。

1. 問題なく描画されているか、確認する。

## 前日までにやっておいた方が良い事
- 記事の提出
    - 前日には欲しいので公開の2日前締め切りが理想。
- 記事の更新
    - 人によっては修正箇所が多かったりするのでなるべく多く時間をとる
- ツイートの作成
    - コピーしてすぐにツイートできるように

## メモ
- アドベントカレンダー2018。12/21のページのみのデザイン修正をページにて直接指定。
- 記事の感想を集めたいとの要望あり。
- 今回はネ管長の方で前日更新したが、次回やるのであれば、周毎などで担当を決めるのがベストかと。
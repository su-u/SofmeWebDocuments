# robots.txt について

## 概要

robots.txt はクローラーへの命令を記述するファイル。
ただし、記述したからといって必ず実行されるわけではない。
記述内容は、

```
#全検索サイトに適用
User-agent: *

#旧サイトの検索回避
Disallow: /old/
Allow: /old/project/dtm/m3/
```

-   `/old/`は過去サイトが保存されている。

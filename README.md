### 画像全置換

ページ上のありとあらゆる画像を指定された画像(複数の場合ランダム)に置き換える。

※一部ページでは動作に支障あり(当然)

[Github](https://github.com/hi2ma-bu4/all-img-replace) | [Greasyfork](https://greasyfork.org/ja/scripts/496153-%E7%94%BB%E5%83%8F%E5%85%A8%E7%BD%AE%E6%8F%9B)

#### 対応Element
* svg
* link[rel="icon",rel="shortcut icon"]
* *[src,srcset]
* *[style(background,background-image)]

##### 非対応
* ::before
* ::after

##### 対応画像形式
* jpeg(jpg)
* png
* gif

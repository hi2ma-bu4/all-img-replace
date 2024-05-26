### 画像全置換

ページ上のありとあらゆる画像を指定された画像(複数の場合ランダム)に置き換える。

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

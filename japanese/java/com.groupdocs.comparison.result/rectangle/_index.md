---
title: "Rectangle"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "Rectangle クラスは、ドキュメント上の変更された領域を表します。"
type: docs
weight: 12
url: /ja/java/com.groupdocs.comparison.result/rectangle/
---
**Inheritance:**
java.lang.Object
```
public final class Rectangle
```

Rectangle クラスは、ドキュメント上の変更された領域を表します。


使用例:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare(resultFile);
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo change : changes) {
         final Rectangle box = change.getBox();
         // Print the changed area on page
         System.out.println("Changed area on a page: "
                 + box.getX() + ", " + box.getY() + ", " + box.getWidth() + ", " + box.getHeight());
     }
 }
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [Rectangle()](#Rectangle--) | Rectangle クラスの新しいインスタンスを初期化します。 |
|
|  | [Rectangle(Rectangle other)](#Rectangle-com.groupdocs.comparison.result.Rectangle-) | 指定された矩形のコピーとなる新しい Rectangle オブジェクトを作成します。 |
|
|  | [Rectangle(double x, double y, double width, double height)](#Rectangle-double-double-double-double-) | 指定された x、y、幅、高さを使用して Rectangle クラスの新しいインスタンスを作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getHeight()](#getHeight--) | 矩形の高さを取得します。 |
|
|  | [setHeight(double value)](#setHeight-double-) | 矩形の高さを設定します。 |
|
|  | [getWidth()](#getWidth--) | 矩形の幅を取得します。 |
|
|  | [setWidth(double value)](#setWidth-double-) | 矩形の幅を設定します。 |
|
|  | [getX()](#getX--) | 矩形の左上隅の x 座標を取得します。 |
|
|  | [setX(double value)](#setX-double-) | 矩形の左上隅の x 座標を設定します。 |
|
|  | [getY()](#getY--) | 矩形の左上隅の y 座標を取得します。 |
|
|  | [setY(double value)](#setY-double-) | 矩形の左上隅の y 座標を設定します。 |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | {@inheritDoc} |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
|  | [toString()](#toString--) | {@inheritDoc} |
|
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


Rectangle クラスの新しいインスタンスを初期化します。


### Rectangle(Rectangle other) {#Rectangle-com.groupdocs.comparison.result.Rectangle-}
```
public Rectangle(Rectangle other)
```


指定された矩形のコピーとなる新しい Rectangle オブジェクトを作成します。

<br />



**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | other | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | コピーされる矩形 |
|

### Rectangle(double x, double y, double width, double height) {#Rectangle-double-double-double-double-}
```
public Rectangle(double x, double y, double width, double height)
```


指定された x、y、幅、高さを使用して Rectangle クラスの新しいインスタンスを作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | x | double | 矩形の左上隅の x 座標 |
|
|  | y | double | 矩形の左上隅の y 座標 |
|
|  | 幅 | double | 矩形の幅 |
|
|  | 高さ | double | 矩形の高さ |
|

### getHeight() {#getHeight--}
```
public double getHeight()
```


矩形の高さを取得します。


**Returns:**
double - 矩形の高さ

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


矩形の高さを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | double | 矩形の高さ |
|

### getWidth() {#getWidth--}
```
public double getWidth()
```


矩形の幅を取得します。


**Returns:**
double - 矩形の幅

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


矩形の幅を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | double | 矩形の幅 |
|

### getX() {#getX--}
```
public double getX()
```


矩形の左上隅の x 座標を取得します。


**Returns:**
double - 矩形の左上隅の x 座標

### setX(double value) {#setX-double-}
```
public void setX(double value)
```


矩形の左上隅の x 座標を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | double | 矩形の左上隅の x 座標 |
|

### getY() {#getY--}
```
public double getY()
```


矩形の左上隅の y 座標を取得します。


**Returns:**
double - 四角形の左上隅の y 座標

### setY(double value) {#setY-double-}
```
public void setY(double value)
```


矩形の左上隅の y 座標を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | double | 矩形の左上隅の y 座標 |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| o | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String

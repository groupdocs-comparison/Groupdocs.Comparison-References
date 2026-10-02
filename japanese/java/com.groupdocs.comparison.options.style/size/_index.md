---
title: "サイズ"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "比較におけるドキュメントのサイズを表します。"
type: docs
weight: 11
url: /ja/java/com.groupdocs.comparison.options.style/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

比較におけるドキュメントのサイズを表します。


使用例:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final Size originalSize = new Size(100, 200);

     StyleSettings styleSettings = new StyleSettings();
     styleSettings.setOriginalSize(originalSize);

     final CompareOptions compareOptions = new CompareOptions();
     compareOptions.setInsertedItemStyle(styleSettings);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [Size()](#Size--) | Size クラスの新しいインスタンスを初期化します。 |
|
|  | [Size(int width, int height)](#Size-int-int-) | ドキュメントの幅と高さを使用して、Size クラスの新しいインスタンスを初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getWidth()](#getWidth--) | 元のドキュメントの幅を取得します。 |
|
|  | [setWidth(int value)](#setWidth-int-) | 元のドキュメントの幅を設定します。 |
|
|  | [getHeight()](#getHeight--) | 元のドキュメントの高さを取得します。 |
|
|  | [setHeight(int value)](#setHeight-int-) | 元のドキュメントの高さを設定します。 |
|
### Size() {#Size--}
```
public Size()
```


Size クラスの新しいインスタンスを初期化します。


### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


ドキュメントの幅と高さを使用して、Size クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 幅 | int |  |
| 高さ | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


元のドキュメントの幅を取得します。


**Returns:**
int - ドキュメントの幅

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


元のドキュメントの幅を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | int | ドキュメントの幅 |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


元のドキュメントの高さを取得します。


**Returns:**
int - ドキュメントの高さ

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


元のドキュメントの高さを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | int | ドキュメントの高さ |
|


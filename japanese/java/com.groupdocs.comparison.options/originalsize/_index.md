---
title: "OriginalSize"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "比較結果におけるドキュメントの元のサイズを表します。"
type: docs
weight: 14
url: /ja/java/com.groupdocs.comparison.options/originalsize/
---
**Inheritance:**
java.lang.Object
```
public class OriginalSize
```

比較結果におけるドキュメントの元のサイズを表します。


元のサイズには、ドキュメントのページの寸法（幅と高さ）が含まれます。


使用例:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     CompareOptions compareOptions = new CompareOptions();
     final OriginalSize originalSize = compareOptions.getOriginalSize();
     originalSize.setWidth(480);
     originalSize.setHeight(640);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [OriginalSize()](#OriginalSize--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getWidth()](#getWidth--) | ドキュメントのページの幅を取得します。 |
|
|  | [setWidth(int value)](#setWidth-int-) | ドキュメントのページの幅を設定します。 |
|
|  | [getHeight()](#getHeight--) | ドキュメントのページの高さを取得します。 |
|
|  | [setHeight(int value)](#setHeight-int-) | ドキュメントのページの高さを設定します。 |
|
### OriginalSize() {#OriginalSize--}
```
public OriginalSize()
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


ドキュメントのページの幅を取得します。


**Returns:**
int - ドキュメントのページの幅

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


ドキュメントのページの幅を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | int | ドキュメントのページの幅。 |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


ドキュメントのページの高さを取得します。


**Returns:**
int - ドキュメントのページの高さ

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


ドキュメントのページの高さを設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | int | ドキュメントのページの高さ。 |
|


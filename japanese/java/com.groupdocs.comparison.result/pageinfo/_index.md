---
title: "PageInfo"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "PageInfo クラスは、ドキュメント内の特定のページに関する情報を表します。"
type: docs
weight: 11
url: /ja/java/com.groupdocs.comparison.result/pageinfo/
---
**Inheritance:**
java.lang.Object
```
public class PageInfo
```

PageInfo クラスは、ドキュメント内の特定のページに関する情報を表します。


ページ番号、幅、高さ、その他の関連プロパティなどの詳細を提供します。
比較プロセス中にドキュメント内の個々のページに関する情報を取得するためにこのクラスを使用します。


使用例:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare(resultFile);
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo change : changes) {
         final PageInfo pageInfo = change.getPageInfo();
         // Print the page information
         System.out.println("Page Number: " + pageInfo.getPageNumber());
         System.out.println("Page Width: " + pageInfo.getWidth());
         System.out.println("Page Height: " + pageInfo.getHeight());
     }
 }
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [PageInfo(int pageNumber, int width, int height)](#PageInfo-int-int-int-) | pageNumber、幅、高さを設定して PageInfo クラスの新しいインスタンスを初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getWidth()](#getWidth--) | ページの幅を取得します |
|
|  | [setWidth(int value)](#setWidth-int-) | ページの幅を設定します |
|
|  | [getHeight()](#getHeight--) | ページの高さを取得します |
|
|  | [setHeight(int value)](#setHeight-int-) | ページの高さを設定します |
|
|  | [getPageNumber()](#getPageNumber--) | ページ番号を取得します |
|
|  | [setPageNumber(int value)](#setPageNumber-int-) | ページ番号を設定します |
|
| [toString()](#toString--) |  |
### PageInfo(int pageNumber, int width, int height) {#PageInfo-int-int-int-}
```
public PageInfo(int pageNumber, int width, int height)
```


pageNumber、幅、高さを設定して PageInfo クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | pageNumber | int | ページの番号 |
|
|  | 幅 | int | ページの幅 |
|
|  | 高さ | int | ページの高さ |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


ページの幅を取得します


**Returns:**
int - ページの幅

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


ページの幅を設定します


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | int | ページの幅 |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


ページの高さを取得します


**Returns:**
int - ページの高さ

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


ページの高さを設定します


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | int | ページの高さ |
|

### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


ページ番号を取得します


**Returns:**
int - ページの番号

### setPageNumber(int value) {#setPageNumber-int-}
```
public final void setPageNumber(int value)
```


ページ番号を設定します


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | int | ページの番号 |
|

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String

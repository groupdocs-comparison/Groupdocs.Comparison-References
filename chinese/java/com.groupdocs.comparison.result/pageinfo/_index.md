---
title: "PageInfo"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "PageInfo 类表示文档中特定页面的信息。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.comparison.result/pageinfo/
---
**Inheritance:**
java.lang.Object
```
public class PageInfo
```

PageInfo 类表示文档中特定页面的信息。


它提供页面编号、宽度、高度以及其他相关属性等详细信息。
在比较过程中使用此类检索文档中各个页面的信息。


示例用法：

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


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PageInfo(int pageNumber, int width, int height)](#PageInfo-int-int-int-) | 使用 pageNumber、宽度和高度初始化 PageInfo 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getWidth()](#getWidth--) | 获取页面的宽度 |
|
|  | [setWidth(int value)](#setWidth-int-) | 设置页面的宽度 |
|
|  | [getHeight()](#getHeight--) | 获取页面的高度 |
|
|  | [setHeight(int value)](#setHeight-int-) | 设置页面的高度 |
|
|  | [getPageNumber()](#getPageNumber--) | 获取页面的编号 |
|
|  | [setPageNumber(int value)](#setPageNumber-int-) | 设置页面的编号 |
|
| [toString()](#toString--) |  |
### PageInfo(int pageNumber, int width, int height) {#PageInfo-int-int-int-}
```
public PageInfo(int pageNumber, int width, int height)
```


使用 pageNumber、宽度和高度初始化 PageInfo 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | pageNumber | int | 页面的编号 |
|
|  | 宽度 | int | 页面的宽度 |
|
|  | 高度 | int | 页面的高度 |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


获取页面的宽度


**Returns:**
int - 页面宽度

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


设置页面的宽度


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 页面的宽度 |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


获取页面的高度


**Returns:**
int - 页面高度

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


设置页面的高度


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 页面的高度 |
|

### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


获取页面的编号


**Returns:**
int - 页面编号

### setPageNumber(int value) {#setPageNumber-int-}
```
public final void setPageNumber(int value)
```


设置页面的编号


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 页面的编号 |
|

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String

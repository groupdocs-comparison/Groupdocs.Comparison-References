---
title: "Size"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "表示比较中文档的大小。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.comparison.options.style/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

表示比较中文档的大小。


示例用法：

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


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [Size()](#Size--) | 初始化 Size 类的新实例。 |
|
|  | [Size(int width, int height)](#Size-int-int-) | 使用文档的宽度和高度初始化 Size 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getWidth()](#getWidth--) | 获取原始文档的宽度。 |
|
|  | [setWidth(int value)](#setWidth-int-) | 设置原始文档的宽度。 |
|
|  | [getHeight()](#getHeight--) | 获取原始文档的高度。 |
|
|  | [setHeight(int value)](#setHeight-int-) | 设置原始文档的高度。 |
|
### Size() {#Size--}
```
public Size()
```


初始化 Size 类的新实例。


### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


使用文档的宽度和高度初始化 Size 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | int |  |
| 高度 | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


获取原始文档的宽度。


**Returns:**
int - 文档的宽度

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


设置原始文档的宽度。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 文档的宽度 |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


获取原始文档的高度。


**Returns:**
int - 文档的高度

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


设置原始文档的高度。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 文档的高度 |
|


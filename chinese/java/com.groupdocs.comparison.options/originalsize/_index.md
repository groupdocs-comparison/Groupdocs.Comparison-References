---
title: "OriginalSize"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "表示比较结果中文档的原始尺寸。"
type: docs
weight: 14
url: /zh/java/com.groupdocs.comparison.options/originalsize/
---
**Inheritance:**
java.lang.Object
```
public class OriginalSize
```

表示比较结果中文档的原始尺寸。


原始大小包括文档页面的尺寸（宽度和高度）。


示例用法：

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


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OriginalSize()](#OriginalSize--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getWidth()](#getWidth--) | 获取文档页面的宽度。 |
|
|  | [setWidth(int value)](#setWidth-int-) | 设置文档页面的宽度。 |
|
|  | [getHeight()](#getHeight--) | 获取文档页面的高度。 |
|
|  | [setHeight(int value)](#setHeight-int-) | 设置文档页面的高度。 |
|
### OriginalSize() {#OriginalSize--}
```
public OriginalSize()
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


获取文档页面的宽度。


**Returns:**
int - 文档页面的宽度。

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


设置文档页面的宽度。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 文档页面的宽度。 |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


获取文档页面的高度。


**Returns:**
int - 文档页面的高度。

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


设置文档页面的高度。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 文档页面的高度。 |
|


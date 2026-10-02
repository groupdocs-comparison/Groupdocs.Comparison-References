---
title: "Rectangle"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Rectangle 类表示文档上的更改区域。"
type: docs
weight: 12
url: /zh/java/com.groupdocs.comparison.result/rectangle/
---
**Inheritance:**
java.lang.Object
```
public final class Rectangle
```

Rectangle 类表示文档上的更改区域。


示例用法：

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


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [Rectangle()](#Rectangle--) | 初始化 Rectangle 类的新实例。 |
|
|  | [Rectangle(Rectangle other)](#Rectangle-com.groupdocs.comparison.result.Rectangle-) | 创建一个新的 Rectangle 对象，该对象是指定矩形的副本。 |
|
|  | [Rectangle(double x, double y, double width, double height)](#Rectangle-double-double-double-double-) | 使用指定的 x、y、宽度和高度创建 Rectangle 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getHeight()](#getHeight--) | 获取矩形的高度。 |
|
|  | [setHeight(double value)](#setHeight-double-) | 设置矩形的高度。 |
|
|  | [getWidth()](#getWidth--) | 获取矩形的宽度。 |
|
|  | [setWidth(double value)](#setWidth-double-) | 设置矩形的宽度。 |
|
|  | [getX()](#getX--) | 获取矩形左上角的 x 坐标。 |
|
|  | [setX(double value)](#setX-double-) | 设置矩形左上角的 x 坐标。 |
|
|  | [getY()](#getY--) | 获取矩形左上角的 y 坐标。 |
|
|  | [setY(double value)](#setY-double-) | 设置矩形左上角的 y 坐标。 |
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


初始化 Rectangle 类的新实例。


### Rectangle(Rectangle other) {#Rectangle-com.groupdocs.comparison.result.Rectangle-}
```
public Rectangle(Rectangle other)
```


创建一个新的 Rectangle 对象，该对象是指定矩形的副本。

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | 要复制的矩形 |
|

### Rectangle(double x, double y, double width, double height) {#Rectangle-double-double-double-double-}
```
public Rectangle(double x, double y, double width, double height)
```


使用指定的 x、y、宽度和高度创建 Rectangle 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | x | double | 矩形左上角的 x 坐标 |
|
|  | y | double | 矩形左上角的 y 坐标 |
|
|  | 宽度 | double | 矩形的宽度 |
|
|  | 高度 | double | 矩形的高度 |
|

### getHeight() {#getHeight--}
```
public double getHeight()
```


获取矩形的高度。


**Returns:**
double - 矩形的高度

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


设置矩形的高度。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | double | 矩形的高度 |
|

### getWidth() {#getWidth--}
```
public double getWidth()
```


获取矩形的宽度。


**Returns:**
double - 矩形的宽度

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


设置矩形的宽度。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | double | 矩形的宽度 |
|

### getX() {#getX--}
```
public double getX()
```


获取矩形左上角的 x 坐标。


**Returns:**
double - 矩形左上角的 x 坐标

### setX(double value) {#setX-double-}
```
public void setX(double value)
```


设置矩形左上角的 x 坐标。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | double | 矩形左上角的 x 坐标 |
|

### getY() {#getY--}
```
public double getY()
```


获取矩形左上角的 y 坐标。


**Returns:**
double - 矩形左上角的 y 坐标

### setY(double value) {#setY-double-}
```
public void setY(double value)
```


设置矩形左上角的 y 坐标。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | double | 矩形左上角的 y 坐标 |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| 参数 | 类型 | 描述 |
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

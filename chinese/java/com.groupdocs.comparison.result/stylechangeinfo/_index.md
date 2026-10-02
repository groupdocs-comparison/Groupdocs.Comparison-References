---
title: "StyleChangeInfo"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "StyleChangeInfo 类表示已比较文档中样式更改的信息。"
type: docs
weight: 13
url: /zh/java/com.groupdocs.comparison.result/stylechangeinfo/
---
**Inheritance:**
java.lang.Object
```
public class StyleChangeInfo
```

StyleChangeInfo 类表示已比较文档中样式更改的信息。


它提供了诸如已更改属性名称、变更前后的值等详细信息。
在文档比较过程中使用此类检索样式更改信息。


示例用法：

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare();
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo change : changes) {
         // Access the style change information
         final List styleChanges = change.getStyleChanges();
         for (StyleChangeInfo styleChange : styleChanges) {
             // Print the style change information
             System.out.println("PropertyName: " + styleChange.getPropertyName());
             System.out.println("OldValue: " + styleChange.getOldValue());
             System.out.println("NewValue: " + styleChange.getNewValue());
         }
     }
 }
 
````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [StyleChangeInfo()](#StyleChangeInfo--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPropertyName()](#getPropertyName--) | 获取已更改属性的名称。 |
|
|  | [setPropertyName(String value)](#setPropertyName-java.lang.String-) | 设置已更改属性的名称。 |
|
|  | [getNewValue()](#getNewValue--) | 获取属性的新值。 |
|
|  | [setNewValue(Object value)](#setNewValue-java.lang.Object-) | 设置属性的新值。 |
|
|  | [getOldValue()](#getOldValue--) | 获取属性的旧值。 |
|
|  | [setOldValue(Object value)](#setOldValue-java.lang.Object-) | 设置属性的旧值。 |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | {@inheritDoc} |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
### StyleChangeInfo() {#StyleChangeInfo--}
```
public StyleChangeInfo()
```


### getPropertyName() {#getPropertyName--}
```
public final String getPropertyName()
```


获取已更改属性的名称。


**Returns:**
java.lang.String - 属性名称

### setPropertyName(String value) {#setPropertyName-java.lang.String-}
```
public final void setPropertyName(String value)
```


设置已更改属性的名称。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 属性名称 |
|

### getNewValue() {#getNewValue--}
```
public final Object getNewValue()
```


获取属性的新值。


**Returns:**
java.lang.Object - 属性的新值

### setNewValue(Object value) {#setNewValue-java.lang.Object-}
```
public final void setNewValue(Object value)
```


设置属性的新值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.Object | 属性的新值 |
|

### getOldValue() {#getOldValue--}
```
public final Object getOldValue()
```


获取属性的旧值。


**Returns:**
java.lang.Object - 属性的旧值

### setOldValue(Object value) {#setOldValue-java.lang.Object-}
```
public final void setOldValue(Object value)
```


设置属性的旧值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.Object | 属性的旧值 |
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

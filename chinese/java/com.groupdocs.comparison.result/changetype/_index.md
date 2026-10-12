---
title: "ChangeType"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "ChangeType 枚举表示文档比较过程中可能出现的更改类型。"
type: docs
weight: 14
url: /zh/java/com.groupdocs.comparison.result/changetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ChangeType extends Enum<ChangeType>
```

ChangeType 枚举表示文档比较过程中可能出现的更改类型。


此枚举中的每个常量表示特定的更改类型，并提供可读的描述和数值。


示例用法：

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo changeInfo : changes) {
         // Get the ChangeType for a specific change
         final ChangeType changeType = changeInfo.getType();
         // Print the ChangeType information
         System.out.println("Description: " + changeType.toString());
         System.out.println("Value: " + changeType.toInt());
     }
 }
 
````


## 字段

| 字段 | 描述 |
| --- | --- |
|  | [NONE](#NONE) | 表示没有更改。 |
|
|  | [MODIFIED](#MODIFIED) | 表示已修改的更改。 |
|
|  | [INSERTED](#INSERTED) | 表示已插入的更改。 |
|
|  | [DELETED](#DELETED) | 表示已删除的更改。 |
|
|  | [ADDED](#ADDED) | 表示已添加的更改。 |
|
|  | [NOT_MODIFIED](#NOT-MODIFIED) | 表示未修改的更改。 |
|
|  | [STYLE_CHANGED](#STYLE-CHANGED) | 表示样式已更改的更改。 |
|
|  | [RESIZED](#RESIZED) | 表示已调整大小的更改。 |
|
|  | [MOVED](#MOVED) | 表示已移动的更改。 |
|
|  | [MOVED_AND_RESIZED](#MOVED-AND-RESIZED) | 表示已移动且已调整大小的更改。 |
|
|  | [SHIFTED_AND_RESIZED](#SHIFTED-AND-RESIZED) | 表示已平移且已调整大小的更改。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | 解析 ChangeType 的字符串表示以获取枚举常量。 |
|
|  | [fromInt(int intValue)](#fromInt-int-) | 使用提供的数值创建 enum ChangeType 的新常量。 |
|
|  | [toString()](#toString--) | ChangeType 的字符串表示。 |
|
|  | [toInt()](#toInt--) | ChangeType 的数值表示。 |
|
### NONE {#NONE}
```
public static final ChangeType NONE
```


表示没有更改。


### MODIFIED {#MODIFIED}
```
public static final ChangeType MODIFIED
```


表示已修改的更改。


### INSERTED {#INSERTED}
```
public static final ChangeType INSERTED
```


表示已插入的更改。


### DELETED {#DELETED}
```
public static final ChangeType DELETED
```


表示已删除的更改。


### ADDED {#ADDED}
```
public static final ChangeType ADDED
```


表示已添加的更改。


### NOT_MODIFIED {#NOT-MODIFIED}
```
public static final ChangeType NOT_MODIFIED
```


表示未修改的更改。


### STYLE_CHANGED {#STYLE-CHANGED}
```
public static final ChangeType STYLE_CHANGED
```


表示样式已更改的更改。


### RESIZED {#RESIZED}
```
public static final ChangeType RESIZED
```


表示已调整大小的更改。


### MOVED {#MOVED}
```
public static final ChangeType MOVED
```


表示已移动的更改。


### MOVED_AND_RESIZED {#MOVED-AND-RESIZED}
```
public static final ChangeType MOVED_AND_RESIZED
```


表示已移动且已调整大小的更改。


### SHIFTED_AND_RESIZED {#SHIFTED-AND-RESIZED}
```
public static final ChangeType SHIFTED_AND_RESIZED
```


表示已平移且已调整大小的更改。


### values() {#values--}
```
public static ChangeType[] values()
```




**Returns:**
com.groupdocs.comparison.result.ChangeType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ChangeType valueOf(String name)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ChangeType fromString(String toStringValue)
```


解析 ChangeType 的字符串表示以获取枚举常量。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | toStringValue | java.lang.String | ChangeType 的字符串表示 |
|

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with input string

### fromInt(int intValue) {#fromInt-int-}
```
public static ChangeType fromInt(int intValue)
```


使用提供的数值创建 enum ChangeType 的新常量。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | intValue | int | ChangeType 的数值表示 |
|

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with numeric value

### toString() {#toString--}
```
public String toString()
```


ChangeType 的字符串表示。


**Returns:**
java.lang.String - 枚举常量的字符串值

### toInt() {#toInt--}
```
public int toInt()
```


ChangeType 的数值表示。


**Returns:**
int - 枚举常量的数值


---
title: "ComparisonAction"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "ComparisonAction 枚举表示在文档比较过程中可对更改执行的操作。"
type: docs
weight: 15
url: /zh/java/com.groupdocs.comparison.result/comparisonaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonAction extends Enum<ComparisonAction>
```

ComparisonAction 枚举表示在文档比较过程中可对更改执行的操作。


此枚举中的每个常量表示特定的操作，并提供可读的描述和数值。


示例用法：

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();

     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo changeInfo : changes) {
         if (changeInfo.getId() % 2 == 0) {
             changeInfo.setComparisonAction(ComparisonAction.REJECT);
         }
     }
     comparer.applyChanges(resultFile, changes);
 }
 
````


## 字段

| 字段 | 描述 |
| --- | --- |
|  | [NONE](#NONE) | 表示无操作。 |
|
|  | [ACCEPT](#ACCEPT) | 表示接受操作。 |
|
|  | [REJECT](#REJECT) | 表示拒绝操作。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | 解析 ComparisonAction 的字符串表示以获取枚举常量。 |
|
|  | [fromInt(int intValue)](#fromInt-int-) | 使用提供的数值创建 ComparisonAction 枚举的新常量。 |
|
|  | [toString()](#toString--) | ComparisonAction 的字符串表示。 |
|
|  | [toInt()](#toInt--) | ComparisonAction 的数值表示。 |
|
### NONE {#NONE}
```
public static final ComparisonAction NONE
```


表示无操作。此更改将不会产生任何影响。


### ACCEPT {#ACCEPT}
```
public static final ComparisonAction ACCEPT
```


表示接受操作。此更改将在结果文件中可见。


### REJECT {#REJECT}
```
public static final ComparisonAction REJECT
```


表示拒绝操作。此更改将在结果文件中不可见。


### values() {#values--}
```
public static ComparisonAction[] values()
```




**Returns:**
com.groupdocs.comparison.result.ComparisonAction[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ComparisonAction valueOf(String name)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonAction fromString(String toStringValue)
```


解析 ComparisonAction 的字符串表示以获取枚举常量。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | toStringValue | java.lang.String | ComparisonAction 的字符串表示 |
|

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with input string

### fromInt(int intValue) {#fromInt-int-}
```
public static ComparisonAction fromInt(int intValue)
```


使用提供的数值创建 ComparisonAction 枚举的新常量。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | intValue | int | ComparisonAction 的数值表示 |
|

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with numeric value

### toString() {#toString--}
```
public String toString()
```


ComparisonAction 的字符串表示。


**Returns:**
java.lang.String - 枚举常量的字符串值

### toInt() {#toInt--}
```
public int toInt()
```


ComparisonAction 的数值表示。


**Returns:**
int - 枚举常量的数值


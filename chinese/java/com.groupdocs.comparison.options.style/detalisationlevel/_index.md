---
title: "DetalisationLevel"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "指定比较细节的级别。"
type: docs
weight: 13
url: /zh/java/com.groupdocs.comparison.options.style/detalisationlevel/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetalisationLevel extends Enum<DetalisationLevel>
```

指定比较细节的级别。


示例用法：

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setDetectStyleChanges(false);
    compareOptions.setDetalisationLevel(DetalisationLevel.HIGH);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## 字段

| 字段 | 描述 |
| --- | --- |
|  | [LOW](#LOW) | 表示低比较级别。 |
|
|  | [MIDDLE](#MIDDLE) | 表示中等比较级别。 |
|
|  | [HIGH](#HIGH) | 表示高比较级别。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | 解析 DetalisationLevel 的字符串表示以获取枚举常量。 |
|
|  | [toString()](#toString--) | DetalisationLevel 的字符串表示。 |
|
### LOW {#LOW}
```
public static final DetalisationLevel LOW
```


表示低比较级别。


"Low" 级别在比较时提供最快的速度，但会牺牲比较质量。
比较按单词进行。


### MIDDLE {#MIDDLE}
```
public static final DetalisationLevel MIDDLE
```


表示中等比较级别。


"Middle" 级别在比较速度和质量之间提供了合理的折中。
比较按字符进行，但忽略字符大小写和空格计数。


### HIGH {#HIGH}
```
public static final DetalisationLevel HIGH
```


表示高比较级别。


"High" 级别提供最佳的比较质量，但速度最低。
比较按字符进行，考虑字符大小写和空格计数。


### values() {#values--}
```
public static DetalisationLevel[] values()
```




**Returns:**
com.groupdocs.comparison.options.style.DetalisationLevel[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static DetalisationLevel valueOf(String name)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static DetalisationLevel fromString(String toStringValue)
```


解析 DetalisationLevel 的字符串表示以获取枚举常量。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | toStringValue | java.lang.String | DetalisationLevel 的字符串表示 |
|

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - DetalisationLevel enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


DetalisationLevel 的字符串表示。


**Returns:**
java.lang.String - 枚举常量的字符串值


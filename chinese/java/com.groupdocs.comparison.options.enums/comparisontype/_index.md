---
title: "ComparisonType"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "表示要执行的比较类型。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.comparison.options.enums/comparisontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonType extends Enum<ComparisonType>
```

表示要执行的比较类型。


示例用法：

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setComparisonType(ComparisonType.CELLS);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## 字段

| 字段 | 描述 |
| --- | --- |
|  | [TEXT](#TEXT) | 文件必须作为文本文档进行比较。 |
|
|  | [SLIDES](#SLIDES) | 文件必须作为演示文稿进行比较。 |
|
|  | [WORDS](#WORDS) | 文件必须作为 Word 文档进行比较。 |
|
|  | [CELLS](#CELLS) | 文件必须作为 Excel 文档进行比较。 |
|
|  | [PDF](#PDF) | 文件必须作为 PDF 文档进行比较。 |
|
|  | [IMAGING](#IMAGING) | 文件必须作为图像文档进行比较。 |
|
|  | [EMAIL](#EMAIL) | 文件必须作为电子邮件文档进行比较。 |
|
|  | [NOTE](#NOTE) | 文件必须作为笔记文档进行比较。 |
|
|  | [HTML](#HTML) | 文件必须作为 HTML 文档进行比较。 |
|
|  | [DIAGRAM](#DIAGRAM) | 文件必须作为图表文档进行比较。 |
|
|  | [DIFFERENT](#DIFFERENT) | 文件必须作为不同格式的文档进行比较。 |
|
|  | [SVG](#SVG) | 文件必须作为 SVG 文档进行比较。 |
|
|  | [UNDEFINED](#UNDEFINED) | 仅供内部使用。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | 解析 ComparisonType 的字符串表示以获取枚举常量。 |
|
|  | [toString()](#toString--) | ComparisonType 的字符串表示。 |
|
### TEXT {#TEXT}
```
public static final ComparisonType TEXT
```


文件必须作为文本文档进行比较。


### SLIDES {#SLIDES}
```
public static final ComparisonType SLIDES
```


文件必须作为演示文稿进行比较。


### WORDS {#WORDS}
```
public static final ComparisonType WORDS
```


文件必须作为 Word 文档进行比较。


### CELLS {#CELLS}
```
public static final ComparisonType CELLS
```


文件必须作为 Excel 文档进行比较。


### PDF {#PDF}
```
public static final ComparisonType PDF
```


文件必须作为 PDF 文档进行比较。


### IMAGING {#IMAGING}
```
public static final ComparisonType IMAGING
```


文件必须作为图像文档进行比较。


### EMAIL {#EMAIL}
```
public static final ComparisonType EMAIL
```


文件必须作为电子邮件文档进行比较。


### NOTE {#NOTE}
```
public static final ComparisonType NOTE
```


文件必须作为笔记文档进行比较。


### HTML {#HTML}
```
public static final ComparisonType HTML
```


文件必须作为 HTML 文档进行比较。


### DIAGRAM {#DIAGRAM}
```
public static final ComparisonType DIAGRAM
```


文件必须作为图表文档进行比较。


### DIFFERENT {#DIFFERENT}
```
public static final ComparisonType DIFFERENT
```


文件必须作为不同格式的文档进行比较。


### SVG {#SVG}
```
public static final ComparisonType SVG
```


文件必须作为 SVG 文档进行比较。


### UNDEFINED {#UNDEFINED}
```
public static final ComparisonType UNDEFINED
```


仅供内部使用。


### values() {#values--}
```
public static ComparisonType[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.ComparisonType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ComparisonType valueOf(String name)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonType fromString(String toStringValue)
```


解析 ComparisonType 的字符串表示以获取枚举常量。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | toStringValue | java.lang.String | ComparisonType 的字符串表示 |
|

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - ComparisonType enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


ComparisonType 的字符串表示。


**Returns:**
java.lang.String - 枚举常量的字符串值


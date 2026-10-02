---
title: "PaperSize"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "表示文档比较的纸张尺寸选项。"
type: docs
weight: 13
url: /zh/java/com.groupdocs.comparison.options.enums/papersize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PaperSize extends Enum<PaperSize>
```

表示文档比较的纸张尺寸选项。


示例用法：

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPaperSize(PaperSize.A6);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## 字段

| 字段 | 描述 |
| --- | --- |
|  | [DEFAULT](#DEFAULT) | 默认纸张尺寸。 |
|
|  | [A0](#A0) | 标准纸张尺寸 A0 (841mm x 1189mm)。 |
|
|  | [A1](#A1) | 标准纸张尺寸 A1 (594mm x 841mm)。 |
|
|  | [A2](#A2) | 标准纸张尺寸 A2 (420mm x 594mm)。 |
|
|  | [A3](#A3) | 标准纸张尺寸 A3 (297mm x 420mm)。 |
|
|  | [A4](#A4) | 标准纸张尺寸 A4 (210mm x 297mm)。 |
|
|  | [A5](#A5) | 标准纸张尺寸 A5 (148mm x 210mm)。 |
|
|  | [A6](#A6) | 标准纸张尺寸 A6 (105mm x 148mm)。 |
|
|  | [A7](#A7) | 标准纸张尺寸 A7 (74mm x 105mm)。 |
|
|  | [A8](#A8) | 标准纸张尺寸 A8 (52mm x 74mm)。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | 解析 PaperSize 的字符串表示以获取枚举常量。 |
|
|  | [toString()](#toString--) | PaperSize 的字符串表示。 |
|
### DEFAULT {#DEFAULT}
```
public static final PaperSize DEFAULT
```


默认纸张尺寸。


### A0 {#A0}
```
public static final PaperSize A0
```


标准纸张尺寸 A0 (841mm x 1189mm)。


### A1 {#A1}
```
public static final PaperSize A1
```


标准纸张尺寸 A1 (594mm x 841mm)。


### A2 {#A2}
```
public static final PaperSize A2
```


标准纸张尺寸 A2 (420mm x 594mm)。


### A3 {#A3}
```
public static final PaperSize A3
```


标准纸张尺寸 A3 (297mm x 420mm)。


### A4 {#A4}
```
public static final PaperSize A4
```


标准纸张尺寸 A4 (210mm x 297mm)。


### A5 {#A5}
```
public static final PaperSize A5
```


标准纸张尺寸 A5 (148mm x 210mm)。


### A6 {#A6}
```
public static final PaperSize A6
```


标准纸张尺寸 A6 (105mm x 148mm)。


### A7 {#A7}
```
public static final PaperSize A7
```


标准纸张尺寸 A7 (74mm x 105mm)。


### A8 {#A8}
```
public static final PaperSize A8
```


标准纸张尺寸 A8 (52mm x 74mm)。


### values() {#values--}
```
public static PaperSize[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.PaperSize[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PaperSize valueOf(String name)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PaperSize fromString(String toStringValue)
```


解析 PaperSize 的字符串表示以获取枚举常量。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | toStringValue | java.lang.String | PaperSize 的字符串表示 |
|

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - PaperSize enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


PaperSize 的字符串表示。


**Returns:**
java.lang.String - 枚举常量的字符串值


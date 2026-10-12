---
title: "MergeType"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "يعدّد نوع دمج الخلايا."
type: docs
weight: 10
url: /ar/java/com.groupdocs.comparison.cells.style/mergetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MergeType extends Enum<MergeType>
```

يعدّد نوع دمج الخلايا.

## الحقول

| حقل | الوصف |
| --- | --- |
|  | [NONE](#NONE) | يشير إلى أن الخلية لا يتم دمجها. |
|
|  | [HORIZONTAL](#HORIZONTAL) | تشير إلى أن الخلية تندمج على طول الصف. |
|
|  | [VERTICAL](#VERTICAL) | تشير إلى أن الخلية تندمج على طول العمود. |
|
|  | [RANGE](#RANGE) | تشير إلى أن الخلية تندمج على طول الصف والعمود، مما يخلق منطقة. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### NONE {#NONE}
```
public static final MergeType NONE
```


يشير إلى أن الخلية لا يتم دمجها.


### HORIZONTAL {#HORIZONTAL}
```
public static final MergeType HORIZONTAL
```


تشير إلى أن الخلية تندمج على طول الصف.


### VERTICAL {#VERTICAL}
```
public static final MergeType VERTICAL
```


تشير إلى أن الخلية تندمج على طول العمود.


### RANGE {#RANGE}
```
public static final MergeType RANGE
```


تشير إلى أن الخلية تندمج على طول الصف والعمود، مما يخلق منطقة.


### values() {#values--}
```
public static MergeType[] values()
```




**Returns:**
com.groupdocs.comparison.cells.style.MergeType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static MergeType valueOf(String name)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

**Returns:**
[MergeType](../../com.groupdocs.comparison.cells.style/mergetype)

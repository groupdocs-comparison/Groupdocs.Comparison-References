---
title: "MergeType"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "セル結合のタイプを列挙します。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.comparison.cells.style/mergetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MergeType extends Enum<MergeType>
```

セル結合のタイプを列挙します。

## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [NONE](#NONE) | セルが結合しないことを示します。 |
|
|  | [HORIZONTAL](#HORIZONTAL) | セルが行方向に結合することを示します。 |
|
|  | [VERTICAL](#VERTICAL) | セルが列方向に結合することを示します。 |
|
|  | [RANGE](#RANGE) | セルが行と列の両方に結合し、領域を作成することを示します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### NONE {#NONE}
```
public static final MergeType NONE
```


セルが結合しないことを示します。


### HORIZONTAL {#HORIZONTAL}
```
public static final MergeType HORIZONTAL
```


セルが行方向に結合することを示します。


### VERTICAL {#VERTICAL}
```
public static final MergeType VERTICAL
```


セルが列方向に結合することを示します。


### RANGE {#RANGE}
```
public static final MergeType RANGE
```


セルが行と列の両方に結合し、領域を作成することを示します。


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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[MergeType](../../com.groupdocs.comparison.cells.style/mergetype)

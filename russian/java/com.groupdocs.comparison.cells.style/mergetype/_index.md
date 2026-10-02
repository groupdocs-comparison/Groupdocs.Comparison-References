---
title: "MergeType"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Перечисляет тип объединения ячеек."
type: docs
weight: 10
url: /ru/java/com.groupdocs.comparison.cells.style/mergetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MergeType extends Enum<MergeType>
```

Перечисляет тип объединения ячеек.

## Поля

| Поле | Описание |
| --- | --- |
|  | [NONE](#NONE) | Указывает, что ячейка не объединяется. |
|
|  | [HORIZONTAL](#HORIZONTAL) | Указывает, что ячейка объединяется по строке. |
|
|  | [VERTICAL](#VERTICAL) | Указывает, что ячейка объединяется по столбцу. |
|
|  | [RANGE](#RANGE) | Указывает, что ячейка объединяется по строке и столбцу, создавая область. |
|
## Методы

| Метод | Описание |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### NONE {#NONE}
```
public static final MergeType NONE
```


Указывает, что ячейка не объединяется.


### HORIZONTAL {#HORIZONTAL}
```
public static final MergeType HORIZONTAL
```


Указывает, что ячейка объединяется по строке.


### VERTICAL {#VERTICAL}
```
public static final MergeType VERTICAL
```


Указывает, что ячейка объединяется по столбцу.


### RANGE {#RANGE}
```
public static final MergeType RANGE
```


Указывает, что ячейка объединяется по строке и столбцу, создавая область.


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
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

**Returns:**
[MergeType](../../com.groupdocs.comparison.cells.style/mergetype)

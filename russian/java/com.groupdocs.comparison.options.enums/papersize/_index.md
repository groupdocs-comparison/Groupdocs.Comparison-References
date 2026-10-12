---
title: "PaperSize"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Представляет варианты размеров бумаги для сравнения документов."
type: docs
weight: 13
url: /ru/java/com.groupdocs.comparison.options.enums/papersize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PaperSize extends Enum<PaperSize>
```

Представляет варианты размеров бумаги для сравнения документов.


Пример использования:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPaperSize(PaperSize.A6);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Поля

| Поле | Описание |
| --- | --- |
|  | [DEFAULT](#DEFAULT) | Размер бумаги по умолчанию. |
|
|  | [A0](#A0) | Стандартный размер бумаги A0 (841 мм × 1189 мм). |
|
|  | [A1](#A1) | Стандартный размер бумаги A1 (594 мм × 841 мм). |
|
|  | [A2](#A2) | Стандартный размер бумаги A2 (420 мм × 594 мм). |
|
|  | [A3](#A3) | Стандартный размер бумаги A3 (297 мм × 420 мм). |
|
|  | [A4](#A4) | Стандартный размер бумаги A4 (210 мм × 297 мм). |
|
|  | [A5](#A5) | Стандартный размер бумаги A5 (148 мм × 210 мм). |
|
|  | [A6](#A6) | Стандартный размер бумаги A6 (105 мм × 148 мм). |
|
|  | [A7](#A7) | Стандартный размер бумаги A7 (74 мм × 105 мм). |
|
|  | [A8](#A8) | Стандартный размер бумаги A8 (52 мм × 74 мм). |
|
## Методы

| Метод | Описание |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Разбирает строковое представление PaperSize, чтобы получить константу перечисления. |
|
|  | [toString()](#toString--) | Строковое представление PaperSize. |
|
### DEFAULT {#DEFAULT}
```
public static final PaperSize DEFAULT
```


Размер бумаги по умолчанию.


### A0 {#A0}
```
public static final PaperSize A0
```


Стандартный размер бумаги A0 (841 мм × 1189 мм).


### A1 {#A1}
```
public static final PaperSize A1
```


Стандартный размер бумаги A1 (594 мм × 841 мм).


### A2 {#A2}
```
public static final PaperSize A2
```


Стандартный размер бумаги A2 (420 мм × 594 мм).


### A3 {#A3}
```
public static final PaperSize A3
```


Стандартный размер бумаги A3 (297 мм × 420 мм).


### A4 {#A4}
```
public static final PaperSize A4
```


Стандартный размер бумаги A4 (210 мм × 297 мм).


### A5 {#A5}
```
public static final PaperSize A5
```


Стандартный размер бумаги A5 (148 мм × 210 мм).


### A6 {#A6}
```
public static final PaperSize A6
```


Стандартный размер бумаги A6 (105 мм × 148 мм).


### A7 {#A7}
```
public static final PaperSize A7
```


Стандартный размер бумаги A7 (74 мм × 105 мм).


### A8 {#A8}
```
public static final PaperSize A8
```


Стандартный размер бумаги A8 (52 мм × 74 мм).


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
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PaperSize fromString(String toStringValue)
```


Разбирает строковое представление PaperSize, чтобы получить константу перечисления.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Строковое представление PaperSize |
|

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - PaperSize enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Строковое представление PaperSize.


**Returns:**
java.lang.String — строковое значение константы перечисления


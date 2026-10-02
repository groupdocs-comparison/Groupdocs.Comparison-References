---
title: "ComparisonType"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Представляет тип сравнения, который будет выполнен."
type: docs
weight: 10
url: /ru/java/com.groupdocs.comparison.options.enums/comparisontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonType extends Enum<ComparisonType>
```

Представляет тип сравнения, который будет выполнен.


Пример использования:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setComparisonType(ComparisonType.CELLS);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Поля

| Поле | Описание |
| --- | --- |
|  | [TEXT](#TEXT) | Файлы должны сравниваться как текстовые документы. |
|
|  | [SLIDES](#SLIDES) | Файлы должны сравниваться как презентационные документы. |
|
|  | [WORDS](#WORDS) | Файлы должны сравниваться как документы Word. |
|
|  | [CELLS](#CELLS) | Файлы должны сравниваться как документы Excel. |
|
|  | [PDF](#PDF) | Файлы должны сравниваться как документы PDF. |
|
|  | [IMAGING](#IMAGING) | Файлы должны сравниваться как графические документы. |
|
|  | [EMAIL](#EMAIL) | Файлы должны сравниваться как электронные письма. |
|
|  | [NOTE](#NOTE) | Файлы должны сравниваться как заметки. |
|
|  | [HTML](#HTML) | Файлы должны сравниваться как HTML-документы. |
|
|  | [DIAGRAM](#DIAGRAM) | Файлы должны сравниваться как диаграммные документы. |
|
|  | [DIFFERENT](#DIFFERENT) | Файлы должны сравниваться как документы в разных форматах. |
|
|  | [SVG](#SVG) | Файлы должны сравниваться как SVG-документы. |
|
|  | [UNDEFINED](#UNDEFINED) | Для внутреннего использования. |
|
## Методы

| Метод | Описание |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Разбирает строковое представление ComparisonType, чтобы получить константу перечисления. |
|
|  | [toString()](#toString--) | Строковое представление ComparisonType. |
|
### TEXT {#TEXT}
```
public static final ComparisonType TEXT
```


Файлы должны сравниваться как текстовые документы.


### SLIDES {#SLIDES}
```
public static final ComparisonType SLIDES
```


Файлы должны сравниваться как презентационные документы.


### WORDS {#WORDS}
```
public static final ComparisonType WORDS
```


Файлы должны сравниваться как документы Word.


### CELLS {#CELLS}
```
public static final ComparisonType CELLS
```


Файлы должны сравниваться как документы Excel.


### PDF {#PDF}
```
public static final ComparisonType PDF
```


Файлы должны сравниваться как документы PDF.


### IMAGING {#IMAGING}
```
public static final ComparisonType IMAGING
```


Файлы должны сравниваться как графические документы.


### EMAIL {#EMAIL}
```
public static final ComparisonType EMAIL
```


Файлы должны сравниваться как электронные письма.


### NOTE {#NOTE}
```
public static final ComparisonType NOTE
```


Файлы должны сравниваться как заметки.


### HTML {#HTML}
```
public static final ComparisonType HTML
```


Файлы должны сравниваться как HTML-документы.


### DIAGRAM {#DIAGRAM}
```
public static final ComparisonType DIAGRAM
```


Файлы должны сравниваться как диаграммные документы.


### DIFFERENT {#DIFFERENT}
```
public static final ComparisonType DIFFERENT
```


Файлы должны сравниваться как документы в разных форматах.


### SVG {#SVG}
```
public static final ComparisonType SVG
```


Файлы должны сравниваться как SVG-документы.


### UNDEFINED {#UNDEFINED}
```
public static final ComparisonType UNDEFINED
```


Для внутреннего использования.


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
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonType fromString(String toStringValue)
```


Разбирает строковое представление ComparisonType, чтобы получить константу перечисления.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Строковое представление ComparisonType |
|

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - ComparisonType enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Строковое представление ComparisonType.


**Returns:**
java.lang.String — строковое значение константы перечисления


---
title: "DetalisationLevel"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Указывает уровень детализации сравнения."
type: docs
weight: 13
url: /ru/java/com.groupdocs.comparison.options.style/detalisationlevel/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetalisationLevel extends Enum<DetalisationLevel>
```

Указывает уровень детализации сравнения.


Пример использования:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setDetectStyleChanges(false);
    compareOptions.setDetalisationLevel(DetalisationLevel.HIGH);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Поля

| Поле | Описание |
| --- | --- |
|  | [LOW](#LOW) | Представляет низкий уровень сравнения. |
|
|  | [MIDDLE](#MIDDLE) | Представляет средний уровень сравнения. |
|
|  | [HIGH](#HIGH) | Представляет высокий уровень сравнения. |
|
## Методы

| Метод | Описание |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Разбирает строковое представление DetalisationLevel, чтобы получить константу перечисления. |
|
|  | [toString()](#toString--) | Строковое представление DetalisationLevel. |
|
### LOW {#LOW}
```
public static final DetalisationLevel LOW
```


Представляет низкий уровень сравнения.


Уровень "Low" обеспечивает наилучшую скорость сравнения, но ухудшает качество сравнения.
Сравнение выполняется по словам.


### MIDDLE {#MIDDLE}
```
public static final DetalisationLevel MIDDLE
```


Представляет средний уровень сравнения.


Уровень "Middle" представляет собой разумный компромисс между скоростью сравнения и качеством.
Сравнение выполняется по символам, но игнорируя регистр символов и количество пробелов.


### HIGH {#HIGH}
```
public static final DetalisationLevel HIGH
```


Представляет высокий уровень сравнения.


Уровень "High" обеспечивает наилучшее качество сравнения, но самую низкую скорость.
Сравнение выполняется по символам с учётом регистра символов и количества пробелов.


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
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static DetalisationLevel fromString(String toStringValue)
```


Разбирает строковое представление DetalisationLevel, чтобы получить константу перечисления.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Строковое представление DetalisationLevel |
|

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - DetalisationLevel enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Строковое представление DetalisationLevel.


**Returns:**
java.lang.String — строковое значение константы перечисления


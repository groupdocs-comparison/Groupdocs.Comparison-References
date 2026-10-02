---
title: "ComparisonAction"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Перечисление ComparisonAction представляет действия, которые могут быть применены к изменению в процессе сравнения документов."
type: docs
weight: 15
url: /ru/java/com.groupdocs.comparison.result/comparisonaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonAction extends Enum<ComparisonAction>
```

Перечисление ComparisonAction представляет действия, которые могут быть применены к изменению в процессе сравнения документов.


Каждая константа в этом перечислении представляет конкретное действие и предоставляет человекочитаемое описание и числовое значение.


Пример использования:

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


## Поля

| Поле | Описание |
| --- | --- |
|  | [NONE](#NONE) | Представляет отсутствие действия. |
|
|  | [ACCEPT](#ACCEPT) | Представляет действие принятия. |
|
|  | [REJECT](#REJECT) | Представляет действие отклонения. |
|
## Методы

| Метод | Описание |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Разбирает строковое представление ComparisonAction, чтобы получить константу перечисления. |
|
|  | [fromInt(int intValue)](#fromInt-int-) | Создаёт новую константу перечисления ComparisonAction, используя предоставленное числовое значение. |
|
|  | [toString()](#toString--) | Строковое представление ComparisonAction. |
|
|  | [toInt()](#toInt--) | Числовое представление ComparisonAction. |
|
### NONE {#NONE}
```
public static final ComparisonAction NONE
```


Представляет отсутствие действия. Изменение не окажет никакого эффекта.


### ACCEPT {#ACCEPT}
```
public static final ComparisonAction ACCEPT
```


Представляет действие принятия. Изменение будет видно в результирующем файле.


### REJECT {#REJECT}
```
public static final ComparisonAction REJECT
```


Представляет действие отклонения. Изменение будет невидимо в результирующем файле.


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
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonAction fromString(String toStringValue)
```


Разбирает строковое представление ComparisonAction, чтобы получить константу перечисления.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Строковое представление ComparisonAction |
|

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with input string

### fromInt(int intValue) {#fromInt-int-}
```
public static ComparisonAction fromInt(int intValue)
```


Создаёт новую константу перечисления ComparisonAction, используя предоставленное числовое значение.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | intValue | int | Числовое представление ComparisonAction |
|

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with numeric value

### toString() {#toString--}
```
public String toString()
```


Строковое представление ComparisonAction.


**Returns:**
java.lang.String — строковое значение константы перечисления

### toInt() {#toInt--}
```
public int toInt()
```


Числовое представление ComparisonAction.


**Returns:**
int — числовое значение константы перечисления


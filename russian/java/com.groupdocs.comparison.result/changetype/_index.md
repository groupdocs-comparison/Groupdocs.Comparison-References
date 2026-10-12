---
title: "ChangeType"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Перечисление ChangeType представляет типы изменений, которые могут возникнуть в процессе сравнения документов."
type: docs
weight: 14
url: /ru/java/com.groupdocs.comparison.result/changetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ChangeType extends Enum<ChangeType>
```

Перечисление ChangeType представляет типы изменений, которые могут возникнуть в процессе сравнения документов.


Каждая константа в этом перечислении представляет конкретный тип изменения и предоставляет человекочитаемое описание и числовое значение.


Пример использования:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo changeInfo : changes) {
         // Get the ChangeType for a specific change
         final ChangeType changeType = changeInfo.getType();
         // Print the ChangeType information
         System.out.println("Description: " + changeType.toString());
         System.out.println("Value: " + changeType.toInt());
     }
 }
 
````


## Поля

| Поле | Описание |
| --- | --- |
|  | [NONE](#NONE) | Представляет отсутствие изменения. |
|
|  | [MODIFIED](#MODIFIED) | Представляет изменённое изменение. |
|
|  | [INSERTED](#INSERTED) | Представляет вставленное изменение. |
|
|  | [DELETED](#DELETED) | Представляет удалённое изменение. |
|
|  | [ADDED](#ADDED) | Представляет добавленное изменение. |
|
|  | [NOT_MODIFIED](#NOT-MODIFIED) | Представляет неизменённое изменение. |
|
|  | [STYLE_CHANGED](#STYLE-CHANGED) | Представляет изменение стиля. |
|
|  | [RESIZED](#RESIZED) | Представляет изменение размера. |
|
|  | [MOVED](#MOVED) | Представляет перемещённое изменение. |
|
|  | [MOVED_AND_RESIZED](#MOVED-AND-RESIZED) | Представляет перемещённое и изменённое по размеру изменение. |
|
|  | [SHIFTED_AND_RESIZED](#SHIFTED-AND-RESIZED) | Представляет сдвинутое и изменённое по размеру изменение. |
|
## Методы

| Метод | Описание |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Разбирает строковое представление ChangeType, чтобы получить константу перечисления. |
|
|  | [fromInt(int intValue)](#fromInt-int-) | Создаёт новую константу перечисления ChangeType, используя предоставленное числовое значение. |
|
|  | [toString()](#toString--) | Строковое представление ChangeType. |
|
|  | [toInt()](#toInt--) | Числовое представление ChangeType. |
|
### NONE {#NONE}
```
public static final ChangeType NONE
```


Представляет отсутствие изменения.


### MODIFIED {#MODIFIED}
```
public static final ChangeType MODIFIED
```


Представляет изменённое изменение.


### INSERTED {#INSERTED}
```
public static final ChangeType INSERTED
```


Представляет вставленное изменение.


### DELETED {#DELETED}
```
public static final ChangeType DELETED
```


Представляет удалённое изменение.


### ADDED {#ADDED}
```
public static final ChangeType ADDED
```


Представляет добавленное изменение.


### NOT_MODIFIED {#NOT-MODIFIED}
```
public static final ChangeType NOT_MODIFIED
```


Представляет неизменённое изменение.


### STYLE_CHANGED {#STYLE-CHANGED}
```
public static final ChangeType STYLE_CHANGED
```


Представляет изменение стиля.


### RESIZED {#RESIZED}
```
public static final ChangeType RESIZED
```


Представляет изменение размера.


### MOVED {#MOVED}
```
public static final ChangeType MOVED
```


Представляет перемещённое изменение.


### MOVED_AND_RESIZED {#MOVED-AND-RESIZED}
```
public static final ChangeType MOVED_AND_RESIZED
```


Представляет перемещённое и изменённое по размеру изменение.


### SHIFTED_AND_RESIZED {#SHIFTED-AND-RESIZED}
```
public static final ChangeType SHIFTED_AND_RESIZED
```


Представляет сдвинутое и изменённое по размеру изменение.


### values() {#values--}
```
public static ChangeType[] values()
```




**Returns:**
com.groupdocs.comparison.result.ChangeType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ChangeType valueOf(String name)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ChangeType fromString(String toStringValue)
```


Разбирает строковое представление ChangeType, чтобы получить константу перечисления.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Строковое представление ChangeType |
|

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with input string

### fromInt(int intValue) {#fromInt-int-}
```
public static ChangeType fromInt(int intValue)
```


Создаёт новую константу перечисления ChangeType, используя предоставленное числовое значение.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | intValue | int | Числовое представление ChangeType |
|

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with numeric value

### toString() {#toString--}
```
public String toString()
```


Строковое представление ChangeType.


**Returns:**
java.lang.String — строковое значение константы перечисления

### toInt() {#toInt--}
```
public int toInt()
```


Числовое представление ChangeType.


**Returns:**
int — числовое значение константы перечисления


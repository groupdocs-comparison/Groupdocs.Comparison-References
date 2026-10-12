---
title: "RevisionType"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Представляет типы ревизий в документе."
type: docs
weight: 14
url: /ru/java/com.groupdocs.comparison.words.revision/revisiontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionType extends Enum<RevisionType>
```

Представляет типы ревизий в документе.


Пример использования:

````

 try (RevisionHandler revisionHandler = new RevisionHandler(sourceFile)) {
     List revisionList = revisionHandler.getRevisions();

     for (RevisionInfo revisionInfo : revisionList) {
         if (revisionInfo.getType() == RevisionType.DELETION)
             // Set an action to be applied to the revision
             revisionInfo.setAction(RevisionAction.Accept);
     }
     // Create an instance of ApplyRevisionOptions
     ApplyRevisionOptions revisionChanges = new ApplyRevisionOptions();
     revisionChanges.setChanges(revisionList);
     // Apply the revisions using the options
     revisionHandler.applyRevisionChanges(resultFile, revisionChanges);
 }
 
````


## Поля

| Поле | Описание |
| --- | --- |
|  | [INSERTION](#INSERTION) | Представляет тип, когда новый контент был вставлен в документ. |
|
|  | [DELETION](#DELETION) | Представляет тип, когда контент был удалён из документа. |
|
|  | [FORMAT_CHANGE](#FORMAT-CHANGE) | Представляет тип, когда изменение форматирования было применено к родительскому узлу. |
|
|  | [STYLE_DEFINITION_CHANGE](#STYLE-DEFINITION-CHANGE) | Представляет тип, когда изменение форматирования было применено к родительскому стилю. |
|
|  | [MOVING](#MOVING) | Представляет тип, когда контент был перемещён в документе. |
|
## Методы

| Метод | Описание |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromInt(int toIntValue)](#fromInt-int-) | Создает новую константу перечисления RevisionType, используя предоставленное числовое значение. |
|
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Разбирает строковое представление RevisionType, чтобы получить константу перечисления. |
|
|  | [toInt()](#toInt--) | Числовое представление RevisionType. |
|
|  | [toString()](#toString--) | Строковое представление RevisionType. |
|
### INSERTION {#INSERTION}
```
public static final RevisionType INSERTION
```


Представляет тип, когда новый контент был вставлен в документ.


### DELETION {#DELETION}
```
public static final RevisionType DELETION
```


Представляет тип, когда контент был удалён из документа.


### FORMAT_CHANGE {#FORMAT-CHANGE}
```
public static final RevisionType FORMAT_CHANGE
```


Представляет тип, когда изменение форматирования было применено к родительскому узлу.


### STYLE_DEFINITION_CHANGE {#STYLE-DEFINITION-CHANGE}
```
public static final RevisionType STYLE_DEFINITION_CHANGE
```


Представляет тип, когда изменение форматирования было применено к родительскому стилю.


### MOVING {#MOVING}
```
public static final RevisionType MOVING
```


Представляет тип, когда контент был перемещён в документе.


### values() {#values--}
```
public static RevisionType[] values()
```




**Returns:**
com.groupdocs.comparison.words.revision.RevisionType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static RevisionType valueOf(String name)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype)
### fromInt(int toIntValue) {#fromInt-int-}
```
public static RevisionType fromInt(int toIntValue)
```


Создает новую константу перечисления RevisionType, используя предоставленное числовое значение.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | toIntValue | int | Числовое представление RevisionType |
|

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with numeric value

### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static RevisionType fromString(String toStringValue)
```


Разбирает строковое представление RevisionType, чтобы получить константу перечисления.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Строковое представление RevisionType |
|

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with input string

### toInt() {#toInt--}
```
public int toInt()
```


Числовое представление RevisionType.


**Returns:**
int — числовое значение константы перечисления

### toString() {#toString--}
```
public String toString()
```


Строковое представление RevisionType.


**Returns:**
java.lang.String — строковое значение константы перечисления


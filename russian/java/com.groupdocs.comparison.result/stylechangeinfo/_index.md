---
title: "StyleChangeInfo"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Класс StyleChangeInfo представляет информацию об изменении стиля в сравниваемом документе."
type: docs
weight: 13
url: /ru/java/com.groupdocs.comparison.result/stylechangeinfo/
---
**Inheritance:**
java.lang.Object
```
public class StyleChangeInfo
```

Класс StyleChangeInfo представляет информацию об изменении стиля в сравниваемом документе.


Он предоставляет детали, такие как имя изменённого свойства, значения до и после изменения, и т.д.
Используйте этот класс для получения информации об изменениях стилей во время процесса сравнения документов.


Пример использования:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare();
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo change : changes) {
         // Access the style change information
         final List styleChanges = change.getStyleChanges();
         for (StyleChangeInfo styleChange : styleChanges) {
             // Print the style change information
             System.out.println("PropertyName: " + styleChange.getPropertyName());
             System.out.println("OldValue: " + styleChange.getOldValue());
             System.out.println("NewValue: " + styleChange.getNewValue());
         }
     }
 }
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [StyleChangeInfo()](#StyleChangeInfo--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getPropertyName()](#getPropertyName--) | Получает имя свойства, которое было изменено. |
|
|  | [setPropertyName(String value)](#setPropertyName-java.lang.String-) | Устанавливает имя свойства, которое было изменено. |
|
|  | [getNewValue()](#getNewValue--) | Получает новое значение свойства. |
|
|  | [setNewValue(Object value)](#setNewValue-java.lang.Object-) | Устанавливает новое значение свойства. |
|
|  | [getOldValue()](#getOldValue--) | Получает старое значение свойства. |
|
|  | [setOldValue(Object value)](#setOldValue-java.lang.Object-) | Устанавливает старое значение свойства. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | {@inheritDoc} |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
### StyleChangeInfo() {#StyleChangeInfo--}
```
public StyleChangeInfo()
```


### getPropertyName() {#getPropertyName--}
```
public final String getPropertyName()
```


Получает имя свойства, которое было изменено.


**Returns:**
java.lang.String - имя свойства

### setPropertyName(String value) {#setPropertyName-java.lang.String-}
```
public final void setPropertyName(String value)
```


Устанавливает имя свойства, которое было изменено.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.lang.String | Имя свойства |
|

### getNewValue() {#getNewValue--}
```
public final Object getNewValue()
```


Получает новое значение свойства.


**Returns:**
java.lang.Object - новое значение свойства

### setNewValue(Object value) {#setNewValue-java.lang.Object-}
```
public final void setNewValue(Object value)
```


Устанавливает новое значение свойства.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.lang.Object | Новое значение свойства |
|

### getOldValue() {#getOldValue--}
```
public final Object getOldValue()
```


Получает старое значение свойства.


**Returns:**
java.lang.Object - старое значение свойства

### setOldValue(Object value) {#setOldValue-java.lang.Object-}
```
public final void setOldValue(Object value)
```


Устанавливает старое значение свойства.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.lang.Object | Старое значение свойства |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| o | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int

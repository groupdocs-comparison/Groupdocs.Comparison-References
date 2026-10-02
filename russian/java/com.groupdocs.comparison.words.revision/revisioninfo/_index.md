---
title: "RevisionInfo"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Представляет ревизию в документе."
type: docs
weight: 12
url: /ru/java/com.groupdocs.comparison.words.revision/revisioninfo/
---
**Inheritance:**
java.lang.Object
```
public class RevisionInfo
```

Представляет ревизию в документе.


Изменение содержит информацию об изменении, внесённом в документ.
Этот класс предоставляет методы для получения информации об изменении, например, его типа,
содержимое, автор и т.д.

Пример использования:

````

 try (RevisionHandler revisionHandler = new RevisionHandler(sourceFile)) {
     List revisionList = revisionHandler.getRevisions();

     for (RevisionInfo revisionInfo : revisionList) {
         System.out.println("Revision Type: " + revisionInfo.getType());
         System.out.println("Text: " + revisionInfo.getText());
         System.out.println("Author: " + revisionInfo.getAuthor());
     }
 }
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [RevisionInfo()](#RevisionInfo--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getAction()](#getAction--) | Получает действие, связанное с изменением (принять или отклонить). |
|
|  | [setAction(RevisionAction value)](#setAction-com.groupdocs.comparison.words.revision.RevisionAction-) | Устанавливает значение, связанное с изменением (принять или отклонить). |
|
|  | [getText()](#getText--) | Получает текстовое содержимое изменения. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Устанавливает значение содержимого изменения. |
|
|  | [getAuthor()](#getAuthor--) | Получает автора изменения. |
|
|  | [setAuthor(String value)](#setAuthor-java.lang.String-) | Устанавливает значение изменения. |
|
|  | [getType()](#getType--) | Получает тип изменения; в зависимости от типа логика действия (принять или отклонить) меняется. |
|
|  | [setType(RevisionType value)](#setType-com.groupdocs.comparison.words.revision.RevisionType-) | Устанавливает значение изменения; в зависимости от значения логика действия (принять или отклонить) меняется. |
|
### RevisionInfo() {#RevisionInfo--}
```
public RevisionInfo()
```


### getAction() {#getAction--}
```
public RevisionAction getAction()
```


Получает действие, связанное с изменением (принять или отклонить). Это поле позволяет влиять на отображение изменения.


**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the action associated with the revision.

### setAction(RevisionAction value) {#setAction-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setAction(RevisionAction value)
```


Устанавливает значение, связанное с изменением (принять или отклонить). Это поле позволяет влиять на отображение изменения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | Значение, связанное с изменением. |
|

### getText() {#getText--}
```
public String getText()
```


Получает текстовое содержимое изменения.


**Returns:**
java.lang.String - текстовое содержимое изменения.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Устанавливает значение содержимого изменения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.lang.String | Значение содержимого изменения. |
|

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Получает автора изменения.


**Returns:**
java.lang.String - автор изменения.

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


Устанавливает значение изменения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.lang.String | Значение изменения. |
|

### getType() {#getType--}
```
public RevisionType getType()
```


Получает тип изменения; в зависимости от типа логика действия (принять или отклонить) меняется.


**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - the type of the revision.

### setType(RevisionType value) {#setType-com.groupdocs.comparison.words.revision.RevisionType-}
```
public void setType(RevisionType value)
```


Устанавливает значение изменения; в зависимости от значения логика действия (принять или отклонить) меняется.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) | Значение изменения. |
|


---
title: "ApplyRevisionOptions"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Класс ApplyRevisionOptions позволяет обновлять состояние ревизий до их применения к окончательному документу."
type: docs
weight: 10
url: /ru/java/com.groupdocs.comparison.words.revision/applyrevisionoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyRevisionOptions
```

Класс ApplyRevisionOptions позволяет обновлять состояние ревизий до их применения к окончательному документу.


Он предоставляет различные конструкторы и свойства для настройки процесса применения изменений.


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


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [ApplyRevisionOptions()](#ApplyRevisionOptions--) | Инициализирует новый экземпляр класса ApplyRevisionOptions. |
|
|  | [ApplyRevisionOptions(List<RevisionInfo> changes)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | Создаёт новый объект ApplyRevisionOptions со списком указанных изменений. |
|
|  | [ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-) | Создает новый объект ApplyRevisionOptions с указанным списком правок и общей операцией правки. |
|
|  | [ApplyRevisionOptions(RevisionAction revisionAction)](#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-) | Создает новый объект ApplyRevisionOptions с общей операцией правки. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getChanges()](#getChanges--) | Получает список правок, которые будут применены. |
|
|  | [setChanges(List<RevisionInfo> changes)](#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | Устанавливает список правок, которые будут применены. |
|
|  | [getCommonHandler()](#getCommonHandler--) | Получает общую операцию правки, которая будет применена ко всем правкам. |
|
|  | [setCommonHandler(RevisionAction commonHandler)](#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-) | Устанавливает общую операцию правки, которая будет применена ко всем правкам. |
|
### ApplyRevisionOptions() {#ApplyRevisionOptions--}
```
public ApplyRevisionOptions()
```


Инициализирует новый экземпляр класса ApplyRevisionOptions.


### ApplyRevisionOptions(List<RevisionInfo> changes) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public ApplyRevisionOptions(List<RevisionInfo> changes)
```


Создаёт новый объект ApplyRevisionOptions со списком указанных изменений.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | изменения | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | Список правок, которые будут применены |
|

### ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)
```


Создает новый объект ApplyRevisionOptions с указанным списком правок и общей операцией правки.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | изменения | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | Список правок, которые будут применены |
|
|  | revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | Общая операция правки, которая будет применена ко всем правкам |
|

### ApplyRevisionOptions(RevisionAction revisionAction) {#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(RevisionAction revisionAction)
```


Создает новый объект ApplyRevisionOptions с общей операцией правки.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | Общая операция правки, которая будет применена ко всем правкам |
|

### getChanges() {#getChanges--}
```
public List<RevisionInfo> getChanges()
```


Получает список правок, которые будут применены.


**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - список правок

### setChanges(List<RevisionInfo> changes) {#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public void setChanges(List<RevisionInfo> changes)
```


Устанавливает список правок, которые будут применены.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | изменения | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | Список правок |
|

### getCommonHandler() {#getCommonHandler--}
```
public RevisionAction getCommonHandler()
```


Получает общую операцию правки, которая будет применена ко всем правкам.


**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the common revision action

### setCommonHandler(RevisionAction commonHandler) {#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setCommonHandler(RevisionAction commonHandler)
```


Устанавливает общую операцию правки, которая будет применена ко всем правкам.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | commonHandler | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | Общая операция правки |
|


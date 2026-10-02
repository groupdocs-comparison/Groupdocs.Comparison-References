---
title: "RevisionHandler"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Представляет класс, который контролирует обработку ревизий."
type: docs
weight: 11
url: /ru/java/com.groupdocs.comparison.words.revision/revisionhandler/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class RevisionHandler implements Closeable
```

Представляет класс, который контролирует обработку ревизий.


Класс RevisionHandler позволяет работать с правками в документах.
Он предоставляет методы для получения списка правок, применения изменений к правкам и сохранения изменённого документа.


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
|  | [RevisionHandler(String filePath)](#RevisionHandler-java.lang.String-) | Инициализирует новый экземпляр класса RevisionHandler с путем к файлу, содержащему правки. |
|
|  | [RevisionHandler(Path filePath)](#RevisionHandler-java.nio.file.Path-) | Инициализирует новый экземпляр класса RevisionHandler с путем к файлу, содержащему правки. |
|
|  | [RevisionHandler(InputStream file, FileType fileType)](#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-) | Инициализирует новый экземпляр класса RevisionHandler с файловым потоком, содержащим правки. |
|
|  | [RevisionHandler(Document document)](#RevisionHandler-com.aspose.words.Document-) | Инициализирует новый экземпляр класса RevisionHandler с документом. |
|
## Поля

| Поле | Описание |
| --- | --- |
| [SOURCE_PATH_IS_NULL](#SOURCE-PATH-IS-NULL) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getRevisions()](#getRevisions--) | Получает список всех правок. |
|
|  | [applyRevisionChanges(ApplyRevisionOptions changes)](#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Обрабатывает изменения в правках и применяет их к оригинальному файлу. |
|
|  | [applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Обрабатывает изменения в правках и записывает результат в указанный файл. |
|
|  | [applyRevisionChanges(String filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Обрабатывает изменения в правках и записывает результат в указанный файл. |
|
|  | [applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)](#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | Обрабатывает изменения в правках и записывает результат в поток документа. |
|
| [close()](#close--) |  |
### RevisionHandler(String filePath) {#RevisionHandler-java.lang.String-}
```
public RevisionHandler(String filePath)
```


Инициализирует новый экземпляр класса RevisionHandler с путем к файлу, содержащему правки.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к файлу. |
|

### RevisionHandler(Path filePath) {#RevisionHandler-java.nio.file.Path-}
```
public RevisionHandler(Path filePath)
```


Инициализирует новый экземпляр класса RevisionHandler с путем к файлу, содержащему правки.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Путь к файлу. |
|

### RevisionHandler(InputStream file, FileType fileType) {#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-}
```
public RevisionHandler(InputStream file, FileType fileType)
```


Инициализирует новый экземпляр класса RevisionHandler с файловым потоком, содержащим правки.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | файл | java.io.InputStream | Поток исходного документа. |
|
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | Тип файла. |
|

### RevisionHandler(Document document) {#RevisionHandler-com.aspose.words.Document-}
```
public RevisionHandler(Document document)
```


Инициализирует новый экземпляр класса RevisionHandler с документом.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | документ | com.aspose.words.Document | Документ. |
|

### SOURCE_PATH_IS_NULL {#SOURCE-PATH-IS-NULL}
```
public static final String SOURCE_PATH_IS_NULL
```


### getRevisions() {#getRevisions--}
```
public List<RevisionInfo> getRevisions()
```


Получает список всех правок.


Поскольку ревизии изначально были отсортированы в группе, ревизии необходимо брать из списка.
В списке одну ревизию можно разбить на несколько ревизий с одинаковым общим текстом.
Поскольку список может содержать ревизии с одинаковым общим текстом, это необходимо контролировать при создании списка ревизий для пользователя.
Это контролируется здесь с использованием групп List\<RevisionGroup\>.


**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - список ревизий.

### applyRevisionChanges(ApplyRevisionOptions changes) {#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(ApplyRevisionOptions changes)
```


Обрабатывает изменения в правках и применяет их к оригинальному файлу.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | Список изменённых ревизий. |
|

### applyRevisionChanges(Path filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)
```


Обрабатывает изменения в правках и записывает результат в указанный файл.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Путь к результирующему файлу. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | Список изменённых ревизий. |
|

### applyRevisionChanges(String filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(String filePath, ApplyRevisionOptions changes)
```


Обрабатывает изменения в правках и записывает результат в указанный файл.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к результирующему файлу. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | Список изменённых ревизий. |
|

### applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes) {#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)
```


Обрабатывает изменения в правках и записывает результат в поток документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | Поток результирующего документа. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | Список изменённых ревизий. |
|

### close() {#close--}
```
public void close()
```





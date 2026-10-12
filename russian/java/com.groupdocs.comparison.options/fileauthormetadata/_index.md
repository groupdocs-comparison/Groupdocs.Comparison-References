---
title: "FileAuthorMetadata"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Позволяет настраивать информацию о метаданных автора документа."
type: docs
weight: 12
url: /ru/java/com.groupdocs.comparison.options/fileauthormetadata/
---
**Inheritance:**
java.lang.Object
```
public class FileAuthorMetadata
```

Позволяет настраивать информацию о метаданных автора документа.


Пример использования:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     SaveOptions saveOptions = new SaveOptions();
     saveOptions.setCloneMetadataType(MetadataType.FILE_AUTHOR);

     final FileAuthorMetadata fileAuthorMetadata = new FileAuthorMetadata();
     fileAuthorMetadata.setAuthor("Tom");
     fileAuthorMetadata.setCompany("GroupDocs");
     fileAuthorMetadata.setLastSaveBy("Jack");

     saveOptions.setFileAuthorMetadata(fileAuthorMetadata);

     comparer.compare(resultFile, saveOptions);
 }
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [FileAuthorMetadata()](#FileAuthorMetadata--) | Инициализирует новый экземпляр класса FileAuthorMetadata. |
|
## Поля

| Поле | Описание |
| --- | --- |
| [GROUP_DOCS](#GROUP-DOCS) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getAuthor()](#getAuthor--) | Получает автора документа. |
|
|  | [setAuthor(String value)](#setAuthor-java.lang.String-) | Устанавливает автора документа. |
|
|  | [getLastSaveBy()](#getLastSaveBy--) | Получает имя человека, который последний раз сохранял документ. |
|
|  | [setLastSaveBy(String value)](#setLastSaveBy-java.lang.String-) | Устанавливает имя человека, который последний раз сохранял документ. |
|
|  | [getCompany()](#getCompany--) | Получает название компании, чей документ является. |
|
|  | [setCompany(String value)](#setCompany-java.lang.String-) | Устанавливает название компании, чей документ является. |
|
### FileAuthorMetadata() {#FileAuthorMetadata--}
```
public FileAuthorMetadata()
```


Инициализирует новый экземпляр класса FileAuthorMetadata.


### GROUP_DOCS {#GROUP-DOCS}
```
public static final String GROUP_DOCS
```


### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```


Получает автора документа.


**Returns:**
java.lang.String - автор

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```


Устанавливает автора документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.lang.String | Автор |
|

### getLastSaveBy() {#getLastSaveBy--}
```
public final String getLastSaveBy()
```


Получает имя человека, который последний раз сохранял документ.


**Returns:**
java.lang.String - имя

### setLastSaveBy(String value) {#setLastSaveBy-java.lang.String-}
```
public final void setLastSaveBy(String value)
```


Устанавливает имя человека, который последний раз сохранял документ.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.lang.String | Имя человека |
|

### getCompany() {#getCompany--}
```
public final String getCompany()
```


Получает название компании, чей документ является.


**Returns:**
java.lang.String - название компании

### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```


Устанавливает название компании, чей документ является.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.lang.String | Название компании |
|


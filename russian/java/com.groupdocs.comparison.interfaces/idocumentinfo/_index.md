---
title: "IDocumentInfo"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Обеспечивает доступ к свойствам документа."
type: docs
weight: 10
url: /ru/java/com.groupdocs.comparison.interfaces/idocumentinfo/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface IDocumentInfo extends Closeable
```

Обеспечивает доступ к свойствам документа.


Более подробную информацию об использовании можно найти в методе [Document.getDocumentInfo()](../../com.groupdocs.comparison/document#getDocumentInfo--) или в [документацию](../https://docs.groupdocs.com/comparison/java/get-file-info/).


Пример использования:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    try (IDocumentInfo documentInfo = comparer.getSource().getDocumentInfo()) {
      for (int i = 0; i < documentInfo.getPageCount(); i++) {
          System.out.printf("File type: %s%nNumber of pages: %d", documentInfo.getFileType().getFileFormat(), documentInfo.getPageCount());
      }
    }
 }
 
````


## Методы

| Метод | Описание |
| --- | --- |
|  | [getFileType()](#getFileType--) | Получает тип файла, представленный перечислением [FileType](../../com.groupdocs.comparison.result/filetype). |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | Устанавливает тип файла, используя перечисление [FileType](../../com.groupdocs.comparison.result/filetype). |
|
|  | [getPageCount()](#getPageCount--) | Получает количество файла. |
|
|  | [setPageCount(int value)](#setPageCount-int-) | Устанавливает количество файла. |
|
|  | [getSize()](#getSize--) | Получает размер файла. |
|
|  | [setSize(long value)](#setSize-long-) | Устанавливает размер файла. |
|
|  | [getPagesInfo()](#getPagesInfo--) | Получает информацию о каждой странице файла, используя класс [PageInfo](../../com.groupdocs.comparison.result/pageinfo). |
|
|  | [setPagesInfo(List<PageInfo> pageInfos)](#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--) | Устанавливает информацию о каждой странице файла, используя класс [PageInfo](../../com.groupdocs.comparison.result/pageinfo). |
|
|  | [close()](#close--) | Уничтожает объект, делая невозможным получение информации о документе с помощью этого экземпляра объекта [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo). |
|
### getFileType() {#getFileType--}
```
public abstract FileType getFileType()
```


Получает тип файла, представленный перечислением [FileType](../../com.groupdocs.comparison.result/filetype).


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public abstract void setFileType(FileType value)
```


Устанавливает тип файла, используя перечисление [FileType](../../com.groupdocs.comparison.result/filetype).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.comparison.result/filetype) | Тип файла |
|

### getPageCount() {#getPageCount--}
```
public abstract int getPageCount()
```


Получает количество файла.


**Returns:**
int - количество файла

### setPageCount(int value) {#setPageCount-int-}
```
public abstract void setPageCount(int value)
```


Устанавливает количество файла.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | int | Количество файла |
|

### getSize() {#getSize--}
```
public abstract long getSize()
```


Получает размер файла.


**Returns:**
long - размер файла

### setSize(long value) {#setSize-long-}
```
public abstract void setSize(long value)
```


Устанавливает размер файла.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | long | Размер файла |
|

### getPagesInfo() {#getPagesInfo--}
```
public abstract List<PageInfo> getPagesInfo()
```


Получает информацию о каждой странице файла, используя класс [PageInfo](../../com.groupdocs.comparison.result/pageinfo).


**Returns:**
java.util.List<com.groupdocs.comparison.result.PageInfo> - информация для каждой страницы файла

### setPagesInfo(List<PageInfo> pageInfos) {#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--}
```
public abstract void setPagesInfo(List<PageInfo> pageInfos)
```


Устанавливает информацию о каждой странице файла, используя класс [PageInfo](../../com.groupdocs.comparison.result/pageinfo).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | pageInfos | java.util.List<com.groupdocs.comparison.result.PageInfo> | Информация для каждой страницы файла |
|

### close() {#close--}
```
public abstract void close()
```


Уничтожает объект, делая невозможным получение информации о документе с помощью этого экземпляра объекта [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo).
Также удаляет временные файлы и освобождает используемые ресурсы.



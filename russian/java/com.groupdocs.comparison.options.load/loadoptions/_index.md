---
title: "LoadOptions"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Позволяет указывать дополнительные параметры при загрузке документа."
type: docs
weight: 10
url: /ru/java/com.groupdocs.comparison.options.load/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Позволяет указывать дополнительные параметры при загрузке документа.


Пример использования:

````

 final LoadOptions loadOptions = new LoadOptions();
 loadOptions.setPassword("passw");
 loadOptions.setFileType(FileType.PDF);

 try (Comparer comparer = new Comparer(sourceFile, loadOptions)) {
    comparer.add(targetFile);

    comparer.compare(resultFile);
 }
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Инициализирует новый экземпляр класса LoadOptions. |
|
|  | [LoadOptions(boolean isLoadText)](#LoadOptions-boolean-) | Инициализирует новый экземпляр класса LoadOptions с флагом, указывающим, что входная строка является текстом для сравнения, а не путём. |
|
|  | [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Инициализирует новый экземпляр класса LoadOptions с паролем для загрузки документа. |
|
|  | [LoadOptions(boolean isLoadText, String password)](#LoadOptions-boolean-java.lang.String-) | Инициализирует новый экземпляр класса LoadOptions с флагом, указывающим, что входная строка является текстом для сравнения, и паролем для загрузки документа. |
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.comparison.result.FileType-) | Инициализирует новый экземпляр класса LoadOptions с типом файла. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [isLoadText()](#isLoadText--) | Возвращает флаг, указывающий, что строка, переданная конструктору [Comparer](../../com.groupdocs.comparison/comparer) или методу [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-), является текстом сравнения, а не путями к файлам (только для сравнения текста). |
|
|  | [setLoadText(boolean value)](#setLoadText-boolean-) | Устанавливает флаг, указывающий, что строка, переданная конструктору [Comparer](../../com.groupdocs.comparison/comparer) или методу [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-), является текстом сравнения, а не путями к файлам (только для сравнения текста). |
|
|  | [getPassword()](#getPassword--) | Возвращает пароль, который будет использоваться для загрузки документа. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Устанавливает пароль, который следует использовать для загрузки документа. |
|
|  | [getFontDirectories()](#getFontDirectories--) | Возвращает список каталогов, где находятся файлы шрифтов для загрузки документа. |
|
|  | [setFontDirectories(List<String> value)](#setFontDirectories-java.util.List-java.lang.String--) | Устанавливает список каталогов, где находятся файлы шрифтов для загрузки документа. |
|
|  | [getFileType()](#getFileType--) | Возвращает тип загружаемого файла. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | Устанавливает тип загружаемого файла. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Инициализирует новый экземпляр класса LoadOptions.


### LoadOptions(boolean isLoadText) {#LoadOptions-boolean-}
```
public LoadOptions(boolean isLoadText)
```


Инициализирует новый экземпляр класса LoadOptions с флагом, указывающим, что входная строка является текстом для сравнения, а не путём.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | isLoadText | boolean | Флаг, означающий, что входная строка является текстом для сравнения, а не путём |
|

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Инициализирует новый экземпляр класса LoadOptions с паролем для загрузки документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | пароль | java.lang.String | Пароль для загрузки документа |
|

### LoadOptions(boolean isLoadText, String password) {#LoadOptions-boolean-java.lang.String-}
```
public LoadOptions(boolean isLoadText, String password)
```


Инициализирует новый экземпляр класса LoadOptions с флагом, указывающим, что входная строка является текстом для сравнения, и паролем для загрузки документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | isLoadText | boolean | Флаг, означающий, что входная строка является текстом для сравнения, а не путём |
|
|  | пароль | java.lang.String | Пароль для загрузки документа |
|

### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.comparison.result.FileType-}
```
public LoadOptions(FileType fileType)
```


Инициализирует новый экземпляр класса LoadOptions с типом файла.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | Тип файла |
|

### isLoadText() {#isLoadText--}
```
public boolean isLoadText()
```


Возвращает флаг, указывающий, что строка, переданная конструктору [Comparer](../../com.groupdocs.comparison/comparer) или методу [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-), является текстом сравнения, а не путями к файлам (только для сравнения текста).


**Returns:**
boolean - true, если входная строка является текстом для сравнения, иначе false

### setLoadText(boolean value) {#setLoadText-boolean-}
```
public void setLoadText(boolean value)
```


Устанавливает флаг, указывающий, что строка, переданная конструктору [Comparer](../../com.groupdocs.comparison/comparer) или методу [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-), является текстом сравнения, а не путями к файлам (только для сравнения текста).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | boolean | true, если входная строка является текстом для сравнения, иначе false |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Возвращает пароль, который будет использоваться для загрузки документа.


**Returns:**
java.lang.String - пароль для загрузки документа

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Устанавливает пароль, который следует использовать для загрузки документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.lang.String | Пароль для загрузки документа |
|

### getFontDirectories() {#getFontDirectories--}
```
public List<String> getFontDirectories()
```


Возвращает список каталогов, где находятся файлы шрифтов для загрузки документа.


**Returns:**
java.util.List<java.lang.String> - список каталогов с файлами шрифтов

### setFontDirectories(List<String> value) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> value)
```


Устанавливает список каталогов, где находятся файлы шрифтов для загрузки документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.util.List<java.lang.String> | Список каталогов с файлами шрифтов |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Возвращает тип загружаемого файла.


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType value)
```


Устанавливает тип загружаемого файла.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.comparison.result/filetype) | Тип файла |
|


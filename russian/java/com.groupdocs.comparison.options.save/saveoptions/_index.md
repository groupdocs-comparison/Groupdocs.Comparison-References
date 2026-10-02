---
title: "SaveOptions"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Позволяет указывать дополнительные параметры при сохранении документа."
type: docs
weight: 10
url: /ru/java/com.groupdocs.comparison.options.save/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

Позволяет указывать дополнительные параметры при сохранении документа.


Пример использования:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    final SaveOptions saveOptions = new SaveOptions();
    saveOptions.setPassword("passw");

    comparer.compare(resultFile, saveOptions);
 }
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [SaveOptions()](#SaveOptions--) | Инициализирует новый экземпляр класса SaveOptions. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getCloneMetadataType()](#getCloneMetadataType--) | Получает стратегию обработки сохранения метаданных результирующего документа. |
|
|  | [setCloneMetadataType(MetadataType value)](#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-) | Устанавливает стратегию обработки сохранения метаданных результирующего документа. |
|
|  | [getFileAuthorMetadata()](#getFileAuthorMetadata--) | Получает объект метаданных, который будет установлен в результирующий документ, когда [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) установлен в [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR). |
|
|  | [setFileAuthorMetadata(FileAuthorMetadata value)](#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-) | Устанавливает объект метаданных, который должен быть установлен в результирующий документ, когда [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) установлен в [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR). |
|
|  | [getPassword()](#getPassword--) | Получает пароль для результирующего документа. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Устанавливает пароль для результирующего документа. |
|
|  | [getFolderPath()](#getFolderPath--) | Получает путь к папке, в которую будут сохраняться результирующие изображения. |
|
|  | [setFolderPath(String value)](#setFolderPath-java.lang.String-) | Устанавливает путь к папке, в которую должны сохраняться результирующие изображения. |
|
|  | [setFolderPath(Path value)](#setFolderPath-java.nio.file.Path-) | Устанавливает путь к папке, в которую должны сохраняться результирующие изображения. |
|
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


Инициализирует новый экземпляр класса SaveOptions.


### getCloneMetadataType() {#getCloneMetadataType--}
```
public final MetadataType getCloneMetadataType()
```


Получает стратегию обработки сохранения метаданных результирующего документа.
Возможные значения находятся в перечислении [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)


**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - the stragegy of processing metadata

### setCloneMetadataType(MetadataType value) {#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-}
```
public final void setCloneMetadataType(MetadataType value)
```


Устанавливает стратегию обработки сохранения метаданных результирующего документа.
Возможные значения находятся в перечислении [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) | Стратегия обработки метаданных |
|

### getFileAuthorMetadata() {#getFileAuthorMetadata--}
```
public final FileAuthorMetadata getFileAuthorMetadata()
```


Получает объект метаданных, который будет установлен в результирующий документ, когда [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) установлен в [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR).


**Returns:**
[FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) - the metadata object

### setFileAuthorMetadata(FileAuthorMetadata value) {#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-}
```
public final void setFileAuthorMetadata(FileAuthorMetadata value)
```


Устанавливает объект метаданных, который должен быть установлен в результирующий документ, когда [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) установлен в [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) | Объект метаданных |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Получает пароль для результирующего документа.


**Returns:**
java.lang.String - пароль

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Устанавливает пароль для результирующего документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.lang.String | Пароль |
|

### getFolderPath() {#getFolderPath--}
```
public final String getFolderPath()
```


Получает путь к папке, в которую будут сохраняться результирующие изображения.
Используется только для сравнения изображений.


**Returns:**
java.lang.String - путь к папке для сохранения результирующих изображений

### setFolderPath(String value) {#setFolderPath-java.lang.String-}
```
public final void setFolderPath(String value)
```


Устанавливает путь к папке, в которую должны сохраняться результирующие изображения.
Используется только для сравнения изображений.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.lang.String | Путь к папке для сохранения результирующих изображений |
|

### setFolderPath(Path value) {#setFolderPath-java.nio.file.Path-}
```
public final void setFolderPath(Path value)
```


Устанавливает путь к папке, в которую должны сохраняться результирующие изображения.
Используется только для сравнения изображений.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.nio.file.Path | Путь к папке для сохранения результирующих изображений |
|


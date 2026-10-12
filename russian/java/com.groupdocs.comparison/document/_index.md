---
title: "Документ"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Представляет документ для процесса сравнения."
type: docs
weight: 12
url: /ru/java/com.groupdocs.comparison/document/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Document implements Closeable
```

Представляет документ для процесса сравнения.


Класс Document предоставляет методы для загрузки, создания предварительных изображений и манипулирования документами во время процесса сравнения.


Пример использования:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     try (IDocumentInfo info = comparer.getSource().getDocumentInfo()) {
         System.out.println("File type: " + info.getFileType());
         System.out.println("Number of pages: " + info.getPageCount());
         System.out.println("Document size: " + info.getSize());
     }
 }
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [Document(InputStream stream)](#Document-java.io.InputStream-) | Инициализирует новый экземпляр класса Document с указанным потоком документа. |
|
|  | [Document(String filePath)](#Document-java.lang.String-) | Инициализирует новый экземпляр класса Document с указанным путем к документу. |
|
|  | [Document(Path filePath)](#Document-java.nio.file.Path-) | Инициализирует новый экземпляр класса Document с указанным путем к документу. |
|
|  | [Document(Path filePath, String password)](#Document-java.nio.file.Path-java.lang.String-) | Инициализирует новый экземпляр класса Document с указанным путем к документу и паролем. |
|
|  | [Document(Path filePath, LoadOptions loadOptions)](#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Инициализирует новый экземпляр класса Document с указанным путем к документу и параметрами загрузки. |
|
|  | [Document(String filePath, String password)](#Document-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса Document с указанным путем к документу и паролем. |
|
|  | [Document(String filePath, LoadOptions loadOptions)](#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Инициализирует новый экземпляр класса Document с указанным путем к документу и параметрами загрузки. |
|
|  | [Document(InputStream stream, String password)](#Document-java.io.InputStream-java.lang.String-) | Инициализирует новый экземпляр класса Document с указанным потоком документа и паролем. |
|
|  | [Document(String filePathOrTextContent, boolean isLoadText)](#Document-java.lang.String-boolean-) | Инициализирует новый экземпляр класса Document с указанным путем к документу или текстовым содержимым и флагом, указывающим, что было передано. |
|
|  | [Document(InputStream inputStream, LoadOptions loadOptions)](#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Инициализирует новый экземпляр класса Document с указанным потоком документа и параметрами загрузки. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getChanges()](#getChanges--) | Получает список объектов [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo), представляющих изменения, обнаруженные во время процесса сравнения. |
|
|  | [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Устанавливает список объектов [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo), представляющих изменения, обнаруженные во время процесса сравнения. |
|
|  | [getName()](#getName--) | Получает имя документа. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Устанавливает имя документа. |
|
|  | [getFileType()](#getFileType--) | Получает тип документа. |
|
|  | [setFileType(FileType fileType)](#setFileType-com.groupdocs.comparison.result.FileType-) | Устанавливает тип документа. |
|
|  | [createStream()](#createStream--) | Создает новый поток с содержимым документа. |
|
|  | [getStreamLength()](#getStreamLength--) | Получает размер документа |
|
|  | [getPassword()](#getPassword--) | Получает пароль документа |
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.comparison.options.PreviewOptions-) | Создает предварительные просмотры документа на основе предоставленных [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions). |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Получает информацию о документе, включая тип документа, количество страниц, размеры страниц и многое другое. |
|
| [close()](#close--) |  |
### Document(InputStream stream) {#Document-java.io.InputStream-}
```
public Document(InputStream stream)
```


Инициализирует новый экземпляр класса Document с указанным потоком документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | поток | java.io.InputStream | Поток документа |
|

### Document(String filePath) {#Document-java.lang.String-}
```
public Document(String filePath)
```


Инициализирует новый экземпляр класса Document с указанным путем к документу.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к документу |
|

### Document(Path filePath) {#Document-java.nio.file.Path-}
```
public Document(Path filePath)
```


Инициализирует новый экземпляр класса Document с указанным путем к документу.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Путь к документу |
|

### Document(Path filePath, String password) {#Document-java.nio.file.Path-java.lang.String-}
```
public Document(Path filePath, String password)
```


Инициализирует новый экземпляр класса Document с указанным путем к документу и паролем.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Путь к документу |
|
|  | пароль | java.lang.String | Пароль документа |
|

### Document(Path filePath, LoadOptions loadOptions) {#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(Path filePath, LoadOptions loadOptions)
```


Инициализирует новый экземпляр класса Document с указанным путем к документу и параметрами загрузки.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Путь к документу |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Параметры загрузки |
|

### Document(String filePath, String password) {#Document-java.lang.String-java.lang.String-}
```
public Document(String filePath, String password)
```


Инициализирует новый экземпляр класса Document с указанным путем к документу и паролем.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к документу |
|
|  | пароль | java.lang.String | Пароль документа |
|

### Document(String filePath, LoadOptions loadOptions) {#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(String filePath, LoadOptions loadOptions)
```


Инициализирует новый экземпляр класса Document с указанным путем к документу и параметрами загрузки.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к документу |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Параметры загрузки |
|

### Document(InputStream stream, String password) {#Document-java.io.InputStream-java.lang.String-}
```
public Document(InputStream stream, String password)
```


Инициализирует новый экземпляр класса Document с указанным потоком документа и паролем.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | поток | java.io.InputStream | Поток документа |
|
|  | пароль | java.lang.String | Пароль документа |
|

### Document(String filePathOrTextContent, boolean isLoadText) {#Document-java.lang.String-boolean-}
```
public Document(String filePathOrTextContent, boolean isLoadText)
```


Инициализирует новый экземпляр класса Document с указанным путем к документу или текстовым содержимым и флагом, указывающим, что было передано.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePathOrTextContent | java.lang.String | путь к файлу |
|
|  | isLoadText | boolean | флаг загрузки текста |
|

### Document(InputStream inputStream, LoadOptions loadOptions) {#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(InputStream inputStream, LoadOptions loadOptions)
```


Инициализирует новый экземпляр класса Document с указанным потоком документа и параметрами загрузки.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | inputStream | java.io.InputStream | Поток документа |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Параметры загрузки |
|

### getChanges() {#getChanges--}
```
public final List<ChangeInfo> getChanges()
```


Получает список объектов [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo), представляющих изменения, обнаруженные во время процесса сравнения.


Используйте этот метод, чтобы получить подробную информацию об изменениях между исходным документом и целевыми документами.
Каждый объект [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) содержит информацию, такую как тип изменения, затронутая область,
и содержимое до и после изменения.


**Returns:**
java.util.List<com.groupdocs.comparison.result.ChangeInfo> - список объектов [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo), представляющих изменения, обнаруженные в процессе сравнения

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


Устанавливает список объектов [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo), представляющих изменения, обнаруженные во время процесса сравнения.


Используйте этот метод, чтобы получить подробную информацию об изменениях между исходным документом и целевыми документами.
Каждый объект [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) содержит информацию, такую как тип изменения, затронутая область,
и содержимое до и после изменения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | список объектов [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo), представляющих изменения, обнаруженные в процессе сравнения |
|

### getName() {#getName--}
```
public final String getName()
```


Получает имя документа.


**Returns:**
java.lang.String - имя документа

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Устанавливает имя документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.lang.String | имя документа |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Получает тип документа.


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the document

### setFileType(FileType fileType) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType fileType)
```


Устанавливает тип документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | тип документа |
|

### createStream() {#createStream--}
```
public InputStream createStream()
```


Создает новый поток с содержимым документа.


**Returns:**
java.io.InputStream - поток с содержимым документа

### getStreamLength() {#getStreamLength--}
```
public long getStreamLength()
```


Получает размер документа


**Returns:**
long - размер документа

### getPassword() {#getPassword--}
```
public String getPassword()
```


Получает пароль документа


**Returns:**
java.lang.String - пароль документа

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.comparison.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Создает предварительные просмотры документа на основе предоставленных [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions).


Этот метод генерирует предварительные просмотры страниц документа в соответствии с указанными параметрами, такими как формат предварительного просмотра,
номера страниц и поставщик выходного потока. Сгенерированные предварительные просмотры могут быть сохранены или дополнительно обработаны по мере необходимости.

* Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Generate+document+pages+preview)


Пример использования:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     PreviewOptions previewOptions = new PreviewOptions(
             pageNumber -> Files.newOutputStream(Paths.get("preview-image-page-" + pageNumber + ".png"))
     );
     previewOptions.setPreviewFormat(PreviewFormats.PNG);
     previewOptions.setPageNumbers(new int[]{1, 2});
     comparer.getSource().generatePreview(previewOptions);
 }
 
````



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) | Параметры предварительного просмотра, указывающие формат, номера страниц и т.д. |
|

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Получает информацию о документе, включая тип документа, количество страниц, размеры страниц и многое другое.

* Learn more about document file type, page count, size, and other format-specific properties: [How to get document info using GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Get+file+info)


**Returns:**
[IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) - the document information

### close() {#close--}
```
public void close()
```





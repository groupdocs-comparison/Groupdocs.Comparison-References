---
title: "Comparer"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Класс Comparer предоставляет функциональность для сравнения документов и создания результатов сравнения."
type: docs
weight: 10
url: /ru/java/com.groupdocs.comparison/comparer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class Comparer implements System.IDisposable, Closeable
```

Класс Comparer предоставляет функциональность для сравнения документов и создания результатов сравнения.


Он позволяет сравнивать различные типы документов, такие как PDF, Word, Excel, PowerPoint и другие.


Пример использования:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     CompareOptions compareOptions = new CompareOptions();
     compareOptions.setDetectStyleChanges(true);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [Comparer(String filePath)](#Comparer-java.lang.String-) | Инициализирует новый экземпляр класса Comparer с указанным путем к исходному файлу. |
|
|  | [Comparer(String filePath, CompareOptions compareOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Инициализирует новый экземпляр класса Comparer с указанным путем к папке и параметрами сравнения. |
|
|  | [Comparer(Path filePath)](#Comparer-java.nio.file.Path-) | Инициализирует новый экземпляр класса Comparer с указанным путем к исходному файлу. |
|
|  | [Comparer(String filePath, LoadOptions loadOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Инициализирует новый экземпляр Comparer с указанным путем к исходному файлу и [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Инициализирует новый экземпляр Comparer с указанным путем к исходному файлу и [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(Path filePath, CompareOptions compareOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Инициализирует новый экземпляр Comparer с указанным путем к исходному файлу и [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Инициализирует новый экземпляр класса Comparer с указанным путем к исходному файлу, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) и [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)](#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-) | Инициализирует новый экземпляр класса Comparer с указанным путем к исходному файлу, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) и [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(String filePath, ComparerSettings settings)](#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-) | Инициализирует новый экземпляр класса Comparer с указанным путем к исходному файлу и [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(Path filePath, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-) | Инициализирует новый экземпляр класса Comparer с указанным путем к исходному файлу и [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Инициализирует новый экземпляр класса Comparer с указанным путем к исходному файлу, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) и [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)](#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-) | Инициализирует новый экземпляр класса Comparer с указанным путем к исходному файлу, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) и [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(InputStream document)](#Comparer-java.io.InputStream-) | Инициализирует новый экземпляр класса Comparer с указанным потоком исходного документа. |
|
|  | [Comparer(InputStream document, LoadOptions loadOptions)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Инициализирует новый экземпляр класса Comparer с указанным потоком исходного документа и [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions). |
|
|  | [Comparer(InputStream document, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-) | Инициализирует новый экземпляр класса Comparer с указанным потоком исходного документа и [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)](#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-) | Инициализирует новый экземпляр класса Comparer с указанным потоком документа, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) и [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
|  | [Comparer(ComparerSettings settings)](#Comparer-com.groupdocs.comparison.ComparerSettings-) | Инициализирует новый экземпляр класса Comparer с указанными [ComparerSettings](../../com.groupdocs.comparison/comparersettings). |
|
## Поля

| Поле | Описание |
| --- | --- |
| [FILE_PATH](#FILE-PATH) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getSource()](#getSource--) | Получает исходный документ, который сравнивается. |
|
|  | [getTargets()](#getTargets--) | Список целевых документов для сравнения с исходным файлом. |
|
|  | [compare()](#compare--) | Сравнивает указанный файл с целевыми документами без сохранения результата, используя параметры по умолчанию. |
|
|  | [compare(String filePath)](#compare-java.lang.String-) | Сравнивает указанный файл с целевыми документами и генерирует результат сравнения. |
|
|  | [compare(Path filePath)](#compare-java.nio.file.Path-) | Сравнивает указанный файл с целевыми документами и генерирует результат сравнения. |
|
|  | [compare(OutputStream outputStream)](#compare-java.io.OutputStream-) | Сравнивает указанный файл с целевыми документами и записывает результат сравнения в выходной поток. |
|
|  | [compare(String filePath, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Сравнивает указанный файл с целевыми документами и записывает результат сравнения по указанному пути к файлу. |
|
|  | [compare(Path filePath, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Сравнивает указанный файл с целевыми документами и записывает результат сравнения по указанному пути к файлу. |
|
|  | [compare(OutputStream stream, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-) | Сравнивает указанный файл с целевыми документами и записывает результат сравнения в выходной поток. |
|
|  | [compare(SaveOptions saveOptions, CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Сравнивает указанный файл с целевыми документами без сохранения результата. |
|
|  | [compare(String filePath, SaveOptions saveOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-) | Сравнивает указанный файл с целевыми документами и записывает результат сравнения по указанному пути к файлу. |
|
|  | [compare(Path filePath, SaveOptions saveOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-) | Сравнивает указанный файл с целевыми документами и записывает результат сравнения по указанному пути к файлу. |
|
|  | [compare(OutputStream stream, SaveOptions saveOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-) | Сравнивает указанный файл с целевыми документами и записывает результат сравнения по указанному пути к файлу. |
|
|  | [compare(CompareOptions compareOptions)](#compare-com.groupdocs.comparison.options.CompareOptions-) | Сравнивает указанный файл с целевыми документами без сохранения результата. |
|
|  | [compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Сравнивает указанный файл с целевыми документами и записывает результат сравнения в предоставленный выходной поток. |
|
|  | [compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Сравнивает указанный файл с целевыми документами и записывает результат сравнения по указанному пути к файлу. |
|
|  | [compareDirectory(String filePath, CompareOptions compareOptions)](#compareDirectory-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Сравнивает указанный каталог с целевым каталогом и сохраняет результат сравнения по указанному пути к файлу. |
|
|  | [compareDirectory(Path filePath, CompareOptions compareOptions)](#compareDirectory-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Сравнивает указанный каталог с целевым каталогом и сохраняет результат сравнения по указанному пути к файлу. |
|
|  | [compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)](#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-) | Сравнивает указанный файл с целевыми документами и записывает результат сравнения по указанному пути к файлу. |
|
|  | [add(String filePath)](#add-java.lang.String-) | Добавляет указанный целевой документ в процесс сравнения. |
|
|  | [add(String filePath, CompareOptions compareOptions)](#add-java.lang.String-com.groupdocs.comparison.options.CompareOptions-) | Добавляет указанный целевой документ или папку в процесс сравнения. |
|
|  | [add(Path filePath)](#add-java.nio.file.Path-) | Добавляет указанный целевой документ в процесс сравнения. |
|
|  | [add(String[] filePaths)](#add-java.lang.String...-) | Добавляет указанные целевые документы в процесс сравнения. |
|
|  | [add(Path[] filePaths)](#add-java.nio.file.Path...-) | Добавляет указанные целевые документы в процесс сравнения. |
|
|  | [add(String filePath, LoadOptions loadOptions)](#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | Добавляет указанный целевой документ в процесс сравнения с указанными параметрами загрузки. |
|
|  | [add(Path filePath, LoadOptions loadOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | Добавляет указанный целевой документ в процесс сравнения с указанными параметрами загрузки. |
|
|  | [add(Path filePath, CompareOptions compareOptions)](#add-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-) | Добавляет указанный целевой документ в процесс сравнения с указанными параметрами загрузки. |
|
|  | [add(InputStream document)](#add-java.io.InputStream-) | Добавляет указанный целевой документ в процесс сравнения. |
|
|  | [add(InputStream[] documents)](#add-java.io.InputStream...-) | Добавляет указанные целевые документы в процесс сравнения. |
|
|  | [add(InputStream document, LoadOptions loadOptions)](#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | Добавляет указанный целевой документ в процесс сравнения с указанными параметрами загрузки. |
|
|  | [getChanges()](#getChanges--) | Получает массив объектов [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo), представляющих изменения, обнаруженные в процессе сравнения. |
|
|  | [getChanges(GetChangeOptions getChangeOptions)](#getChanges-com.groupdocs.comparison.options.GetChangeOptions-) | Получает массив объектов [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo), представляющих изменения, обнаруженные в процессе сравнения. |
|
|  | [applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-) | Принимает или отклоняет изменения и применяет их к результирующему документу. |
|
|  | [applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-) | Принимает или отклоняет изменения и применяет их к полученному документу. |
|
|  | [applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-) | Принимает или отклоняет изменения и применяет их к полученному документу. |
|
|  | [applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Принимает или отклоняет изменения и применяет их к полученному документу. |
|
|  | [applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Принимает или отклоняет изменения и применяет их к полученному документу. |
|
|  | [applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)](#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-) | Принимает или отклоняет изменения и применяет их к полученному документу. |
|
|  | [getResultString()](#getResultString--) | Получает строку результата после сравнения (только для текстового сравнения). |
|
|  | [getSourceFolder()](#getSourceFolder--) | Возвращает исходную папку, которая сравнивается. |
|
|  | [getTargetFolder()](#getTargetFolder--) | Возвращает целевую папку, которая сравнивается. |
|
|  | [selfComparisonCheck(Document source, Document target)](#selfComparisonCheck-com.groupdocs.comparison.Document-com.groupdocs.comparison.Document-) | Проверка самосравнения (e498c23). |
|
|  | [close()](#close--) | Освобождает ресурсы. |
|
### Comparer(String filePath) {#Comparer-java.lang.String-}
```
public Comparer(String filePath)
```


Инициализирует новый экземпляр класса Comparer с указанным путем к исходному файлу.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к исходному документу |
|

### Comparer(String filePath, CompareOptions compareOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(String filePath, CompareOptions compareOptions)
```


Инициализирует новый экземпляр класса Comparer с указанным путем к папке и параметрами сравнения.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к исходному документу или папке |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Параметры сравнения для сравнения папок |
|

### Comparer(Path filePath) {#Comparer-java.nio.file.Path-}
```
public Comparer(Path filePath)
```


Инициализирует новый экземпляр класса Comparer с указанным путем к исходному файлу.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Путь к исходному документу |
|

### Comparer(String filePath, LoadOptions loadOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions)
```


Инициализирует новый экземпляр Comparer с указанным путем к исходному файлу и [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к исходному документу |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Пользовательские параметры загрузки, применяемые к документу |
|

### Comparer(Path filePath, LoadOptions loadOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions)
```


Инициализирует новый экземпляр Comparer с указанным путем к исходному файлу и [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Путь к исходному документу |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Пользовательские параметры загрузки, применяемые к документу |
|

### Comparer(Path filePath, CompareOptions compareOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(Path filePath, CompareOptions compareOptions)
```


Инициализирует новый экземпляр Comparer с указанным путем к исходному файлу и [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Путь к исходному документу |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Параметры сравнения для сравнения папок |
|

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings)
```


Инициализирует новый экземпляр класса Comparer с указанным путем к исходному файлу, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) и [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к исходному документу |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Пользовательские параметры загрузки, применяемые к документу |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Настройки сравнивателя, используемые в процессе сравнения |
|

### Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions) {#Comparer-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(String filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)
```


Инициализирует новый экземпляр класса Comparer с указанным путем к исходному файлу, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) и [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к исходному документу, папке или тексту для сравнения |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Пользовательские параметры загрузки, применяемые к документу |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Настройки сравнивателя, используемые в процессе сравнения |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Параметры сравнения для сравнения папок |
|

### Comparer(String filePath, ComparerSettings settings) {#Comparer-java.lang.String-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(String filePath, ComparerSettings settings)
```


Инициализирует новый экземпляр класса Comparer с указанным путем к исходному файлу и [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к исходному документу |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Настройки сравнивателя, используемые в процессе сравнения |
|

### Comparer(Path filePath, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, ComparerSettings settings)
```


Инициализирует новый экземпляр класса Comparer с указанным путем к исходному файлу и [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Путь к исходному документу |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Настройки сравнивателя, используемые в процессе сравнения |
|

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings)
```


Инициализирует новый экземпляр класса Comparer с указанным путем к исходному файлу, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) и [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Путь к исходному документу |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Пользовательские параметры загрузки, применяемые к документу |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Настройки сравнивателя, используемые в процессе сравнения |
|

### Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions) {#Comparer-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-com.groupdocs.comparison.options.CompareOptions-}
```
public Comparer(Path filePath, LoadOptions loadOptions, ComparerSettings settings, CompareOptions compareOptions)
```


Инициализирует новый экземпляр класса Comparer с указанным путем к исходному файлу, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) и [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Путь к исходному документу или папке |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Пользовательские параметры загрузки, применяемые к документу |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Настройки сравнивателя, используемые в процессе сравнения |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Параметры сравнения для сравнения папок |
|

### Comparer(InputStream document) {#Comparer-java.io.InputStream-}
```
public Comparer(InputStream document)
```


Инициализирует новый экземпляр класса Comparer с указанным потоком исходного документа.

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | документ | java.io.InputStream | Входной поток исходного документа |
|

### Comparer(InputStream document, LoadOptions loadOptions) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Comparer(InputStream document, LoadOptions loadOptions)
```


Инициализирует новый экземпляр класса Comparer с указанным потоком исходного документа и [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | документ | java.io.InputStream | Входной поток исходного документа |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Пользовательские параметры загрузки, применяемые к документу |
|

### Comparer(InputStream document, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, ComparerSettings settings)
```


Инициализирует новый экземпляр класса Comparer с указанным потоком исходного документа и [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | документ | java.io.InputStream | Входной поток исходного документа |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Настройки сравнивателя, используемые в процессе сравнения |
|

### Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings) {#Comparer-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(InputStream document, LoadOptions loadOptions, ComparerSettings settings)
```


Инициализирует новый экземпляр класса Comparer с указанным потоком документа, [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) и [ComparerSettings](../../com.groupdocs.comparison/comparersettings).

* More about file types supported by GroupDocs.Comparison: [Document formats supported by GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Supported+Document+Formats)
* More about GroupDocs.Comparison for Java features: [Developer Guide](../https://docs.groupdocs.com/display/comparisonjava/Developer+Guide)
* More about how to open and compare password-protected documents: [Open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare document from URL, FTP, Amazon S3 and others: [Open and compare documents from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Loading)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | документ | java.io.InputStream | Поток с данными документа для сравнения |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Пользовательские параметры загрузки, применяемые к документу |
|
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | Настройки сравнивателя, используемые в процессе сравнения |
|

### Comparer(ComparerSettings settings) {#Comparer-com.groupdocs.comparison.ComparerSettings-}
```
public Comparer(ComparerSettings settings)
```


Инициализирует новый экземпляр класса Comparer с указанными [ComparerSettings](../../com.groupdocs.comparison/comparersettings).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | settings | [ComparerSettings](../../com.groupdocs.comparison/comparersettings) | настройки |
|

### FILE_PATH {#FILE-PATH}
```
public static final String FILE_PATH
```


### getSource() {#getSource--}
```
public final Document getSource()
```


Получает исходный документ, который сравнивается.


**Returns:**
[Document](../../com.groupdocs.comparison/document) - the source document

### getTargets() {#getTargets--}
```
public final List<Document> getTargets()
```


Список целевых документов для сравнения с исходным файлом.


**Returns:**
java.util.List<com.groupdocs.comparison.Document> - целевые документы

### compare() {#compare--}
```
public final Path compare()
```


Сравнивает указанный файл с целевыми документами без сохранения результата, используя параметры по умолчанию.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Returns:**
java.nio.file.Path - путь к результирующему документу или null

### compare(String filePath) {#compare-java.lang.String-}
```
public final Path compare(String filePath)
```


Сравнивает указанный файл с целевыми документами и генерирует результат сравнения.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к результирующему документу |
|

**Returns:**
java.nio.file.Path - путь к файлу результата или null. В некоторых ситуациях его расширение может быть изменено

### compare(Path filePath) {#compare-java.nio.file.Path-}
```
public final Path compare(Path filePath)
```


Сравнивает указанный файл с целевыми документами и генерирует результат сравнения.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Путь к результирующему документу |
|

**Returns:**
java.nio.file.Path - путь к файлу результата, в некоторых ситуациях его расширение может быть изменено

### compare(OutputStream outputStream) {#compare-java.io.OutputStream-}
```
public final Path compare(OutputStream outputStream)
```


Сравнивает указанный файл с целевыми документами и записывает результат сравнения в выходной поток.


Примечание: В случаях, когда возвращаемое значение равно null, используйте данные, записанные в outputStream

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | Поток результирующего документа |
|

**Returns:**
java.nio.file.Path - путь к файлу результата или null, когда необходимо использовать данные из  outputStream . В некоторых ситуациях расширение файла результата может быть изменено

### compare(String filePath, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, CompareOptions compareOptions)
```


Сравнивает указанный файл с целевыми документами и записывает результат сравнения по указанному пути к файлу.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к файлу результирующего документа |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Параметры сравнения, используемые в процессе сравнения |
|

**Returns:**
java.nio.file.Path - путь к файлу результата, в некоторых ситуациях его расширение может быть изменено

### compare(Path filePath, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, CompareOptions compareOptions)
```


Сравнивает указанный файл с целевыми документами и записывает результат сравнения по указанному пути к файлу.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Путь к файлу результирующего документа |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Параметры сравнения, используемые в процессе сравнения |
|

**Returns:**
java.nio.file.Path - путь к файлу результата, в некоторых ситуациях его расширение может быть изменено

### compare(OutputStream stream, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream stream, CompareOptions compareOptions)
```


Сравнивает указанный файл с целевыми документами и записывает результат сравнения в выходной поток.


Примечание: Если возвращаемое значение равно null, используйте данные, записанные в outputStream.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | поток | java.io.OutputStream | Поток результирующего документа |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Параметры сравнения, используемые в процессе сравнения |
|

**Returns:**
java.nio.file.Path - путь к файлу результата или null, когда необходимо использовать данные из  outputStream . В некоторых ситуациях расширение файла результата может быть изменено

### compare(SaveOptions saveOptions, CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(SaveOptions saveOptions, CompareOptions compareOptions)
```


Сравнивает указанный файл с целевыми документами без сохранения результата.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparison options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Параметры сохранения |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Параметры сравнения, используемые в процессе сравнения |
|

**Returns:**
java.nio.file.Path - путь к результирующему документу или null

### compare(String filePath, SaveOptions saveOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions)
```


Сравнивает указанный файл с целевыми документами и записывает результат сравнения по указанному пути к файлу.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к файлу результирующего документа |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Параметры сохранения |
|

**Returns:**
java.nio.file.Path - путь к файлу результата, в некоторых ситуациях его расширение может быть изменено

### compare(Path filePath, SaveOptions saveOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions)
```


Сравнивает указанный файл с целевыми документами и записывает результат сравнения по указанному пути к файлу.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Путь к файлу результирующего документа |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Параметры сохранения |
|

**Returns:**
java.nio.file.Path - путь к файлу результата, в некоторых ситуациях его расширение может быть изменено

### compare(OutputStream stream, SaveOptions saveOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-}
```
public final Path compare(OutputStream stream, SaveOptions saveOptions)
```


Сравнивает указанный файл с целевыми документами и записывает результат сравнения по указанному пути к файлу.


Примечание: Если возвращаемое значение равно null, используйте данные, записанные в outputStream

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | поток | java.io.OutputStream | Поток результирующего документа |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Параметры сохранения |
|

**Returns:**
java.nio.file.Path - путь к файлу результата или null, когда необходимо использовать данные из  outputStream . В некоторых ситуациях расширение файла результата может быть изменено

### compare(CompareOptions compareOptions) {#compare-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(CompareOptions compareOptions)
```


Сравнивает указанный файл с целевыми документами без сохранения результата.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Параметры сравнения, используемые в процессе сравнения |
|

**Returns:**
java.nio.file.Path — путь к результирующему файлу или null

### compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(OutputStream outputStream, SaveOptions saveOptions, CompareOptions compareOptions)
```


Сравнивает указанный файл с целевыми документами и записывает результат сравнения в предоставленный выходной поток.


Примечание: Если возвращаемое значение равно null, используйте данные, записанные в outputStream

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | Поток результирующего документа |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Параметры сохранения, используемые для сохранения результирующего документа |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Параметры сравнения, используемые в процессе сравнения |
|

**Returns:**
java.nio.file.Path - путь к файлу результата или null, когда необходимо использовать данные из  outputStream . В некоторых ситуациях расширение файла результата может быть изменено

### compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(String filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


Сравнивает указанный файл с целевыми документами и записывает результат сравнения по указанному пути к файлу.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparison options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к файлу результирующего документа |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Параметры сохранения, используемые для сохранения результирующего документа |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Параметры сравнения, используемые в процессе сравнения |
|

**Returns:**
java.nio.file.Path - путь к файлу результата, в некоторых ситуациях его расширение может быть изменено

### compareDirectory(String filePath, CompareOptions compareOptions) {#compareDirectory-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public void compareDirectory(String filePath, CompareOptions compareOptions)
```


Сравнивает указанный каталог с целевым каталогом и сохраняет результат сравнения по указанному пути к файлу.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к файлу, где будет сохранён результат сравнения. |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Параметры, которые будут использоваться для процесса сравнения каталогов. |
|

### compareDirectory(Path filePath, CompareOptions compareOptions) {#compareDirectory-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public void compareDirectory(Path filePath, CompareOptions compareOptions)
```


Сравнивает указанный каталог с целевым каталогом и сохраняет результат сравнения по указанному пути к файлу.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Путь к файлу, где будет сохранён результат сравнения. |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Параметры, которые будут использоваться для процесса сравнения каталогов. |
|

### compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions) {#compare-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.CompareOptions-}
```
public final Path compare(Path filePath, SaveOptions saveOptions, CompareOptions compareOptions)
```


Сравнивает указанный файл с целевыми документами и записывает результат сравнения по указанному пути к файлу.

* More about how to compare documents: [How to compare documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Compare+documents)
* More about how to compare contracts, drafts and legal documents in Java: [How to compare contracts, drafts and legal documents](../https://docs.groupdocs.com/comparison/java/comparison-use-cases/)
* More about advanced comparsion options - accepting and rejecting detected changes, adjusting comparison sensitivity etc.: [Advanced comparison options guide](../https://docs.groupdocs.com/comparison/java/comparison/)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Путь к файлу результирующего документа |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Параметры сохранения, используемые для сохранения результирующего документа |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Параметры сравнения, используемые в процессе сравнения |
|

**Returns:**
java.nio.file.Path - путь к файлу результата, в некоторых ситуациях его расширение может быть изменено

### add(String filePath) {#add-java.lang.String-}
```
public final void add(String filePath)
```


Добавляет указанный целевой документ в процесс сравнения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к целевому документу, который будет добавлен |
|

### add(String filePath, CompareOptions compareOptions) {#add-java.lang.String-com.groupdocs.comparison.options.CompareOptions-}
```
public void add(String filePath, CompareOptions compareOptions)
```


Добавляет указанный целевой документ или папку в процесс сравнения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к целевому документу или папке, которые будут добавлены |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Параметры сравнения |
|

### add(Path filePath) {#add-java.nio.file.Path-}
```
public final void add(Path filePath)
```


Добавляет указанный целевой документ в процесс сравнения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Путь к целевому документу, который будет добавлен |
|

### add(String[] filePaths) {#add-java.lang.String...-}
```
public final void add(String[] filePaths)
```


Добавляет указанные целевые документы в процесс сравнения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePaths | java.lang.String[] | Пути к целевым документам, которые будут добавлены |
|

### add(Path[] filePaths) {#add-java.nio.file.Path...-}
```
public final void add(Path[] filePaths)
```


Добавляет указанные целевые документы в процесс сравнения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePaths | java.nio.file.Path[] | Пути к целевым документам, которые будут добавлены |
|

### add(String filePath, LoadOptions loadOptions) {#add-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(String filePath, LoadOptions loadOptions)
```


Добавляет указанный целевой документ в процесс сравнения с указанными параметрами загрузки.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к целевому документу, который будет добавлен |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Пользовательские параметры загрузки, применяемые к документу |
|

### add(Path filePath, LoadOptions loadOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(Path filePath, LoadOptions loadOptions)
```


Добавляет указанный целевой документ в процесс сравнения с указанными параметрами загрузки.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Путь к целевому документу, который будет добавлен |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Пользовательские параметры загрузки, применяемые к документу |
|

### add(Path filePath, CompareOptions compareOptions) {#add-java.nio.file.Path-com.groupdocs.comparison.options.CompareOptions-}
```
public final void add(Path filePath, CompareOptions compareOptions)
```


Добавляет указанный целевой документ в процесс сравнения с указанными параметрами загрузки.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Путь к целевому документу или папке, которые будут добавлены |
|
|  | compareOptions | [CompareOptions](../../com.groupdocs.comparison.options/compareoptions) | Параметры сравнения |
|

### add(InputStream document) {#add-java.io.InputStream-}
```
public final void add(InputStream document)
```


Добавляет указанный целевой документ в процесс сравнения.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | документ | java.io.InputStream | Поток с данными документа для сравнения |
|

### add(InputStream[] documents) {#add-java.io.InputStream...-}
```
public final void add(InputStream[] documents)
```


Добавляет указанные целевые документы в процесс сравнения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | documents | java.io.InputStream[] | Потоки с данными документов, которые будут сравниваться |
|

### add(InputStream document, LoadOptions loadOptions) {#add-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public final void add(InputStream document, LoadOptions loadOptions)
```


Добавляет указанный целевой документ в процесс сравнения с указанными параметрами загрузки.

* More about how to open and compare password-protected documents using GroupDocs.Comparison for Java: [How to open and compare password-protected documents](../https://docs.groupdocs.com/display/comparisonjava/Load+password-protected+documents)
* More about how to open and compare documents stored at local disk: [How to open and compare files by file path](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+local+disk)
* More about how to open and compare documents from URL, FTP, Amazon S3 and other storages: [How to open and compare files from third-party storages](../https://docs.groupdocs.com/display/comparisonjava/Load+document+from+stream)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | документ | java.io.InputStream | Поток с данными документа для сравнения |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | Пользовательские параметры загрузки, применяемые к документу |
|

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


Получает массив объектов [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo), представляющих изменения, обнаруженные в процессе сравнения.


Используйте этот метод, чтобы получить подробную информацию об изменениях между исходным документом и целевыми документами.
Каждый объект [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) содержит информацию, такую как тип изменения, затронутая область,
и содержимое до и после изменения.

* More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically](../https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates)


**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] — массив объектов [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo), представляющих изменения, обнаруженные в процессе сравнения

### getChanges(GetChangeOptions getChangeOptions) {#getChanges-com.groupdocs.comparison.options.GetChangeOptions-}
```
public final ChangeInfo[] getChanges(GetChangeOptions getChangeOptions)
```


Получает массив объектов [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo), представляющих изменения, обнаруженные в процессе сравнения.


Используйте этот метод, чтобы получить подробную информацию об изменениях между исходным документом и целевыми документами.
Каждый объект [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) содержит информацию, такую как тип изменения, затронутая область,
и содержимое до и после изменения.


Параметр [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) позволяет фильтровать изменения различными способами.

* More about how to obtain collection of detected differences between compared documents in Java: [How to get list of changes between documents in Java](../https://docs.groupdocs.com/display/comparisonjava/Get+list+of+changes)
* More about how to get changes coordinates at pages image preview when comparing documents using GroupDocs.Comparison for Java: [How to get changes coordinates programmatically](../https://docs.groupdocs.com/display/comparisonjava/Get+changes+coordinates)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | getChangeOptions | [GetChangeOptions](../../com.groupdocs.comparison.options/getchangeoptions) | Объект, который позволяет фильтровать изменения |
|

**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] — массив объектов [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo), представляющих изменения, обнаруженные в процессе сравнения

### applyChanges(String filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, ApplyChangeOptions applyChangeOptions)
```


Принимает или отклоняет изменения и применяет их к результирующему документу.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к файлу результирующего документа |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Пользовательские параметры применения изменений для настройки процесса применения изменений |
|

### applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, ApplyChangeOptions applyChangeOptions)
```


Принимает или отклоняет изменения и применяет их к полученному документу.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Путь к файлу результирующего документа |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Пользовательские параметры применения изменений для настройки процесса применения изменений |
|

### applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, ApplyChangeOptions applyChangeOptions)
```


Принимает или отклоняет изменения и применяет их к полученному документу.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | документ | java.io.OutputStream | Поток вывода результирующего документа |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Пользовательские параметры применения изменений для настройки процесса применения изменений |
|

### applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.lang.String-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(String filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Принимает или отклоняет изменения и применяет их к полученному документу.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к файлу результирующего документа |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Параметры сохранения для настройки сохранения результирующего документа |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Пользовательские параметры применения изменений для настройки процесса применения изменений |
|

### applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.nio.file.Path-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(Path filePath, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Принимает или отклоняет изменения и применяет их к полученному документу.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Путь к файлу результирующего документа |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Параметры сохранения для настройки сохранения результирующего документа |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Пользовательские параметры применения изменений для настройки процесса применения изменений |
|

### applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions) {#applyChanges-java.io.OutputStream-com.groupdocs.comparison.options.save.SaveOptions-com.groupdocs.comparison.options.ApplyChangeOptions-}
```
public final void applyChanges(OutputStream document, SaveOptions saveOptions, ApplyChangeOptions applyChangeOptions)
```


Принимает или отклоняет изменения и применяет их к полученному документу.

* More about how apply or reject detected differences between compared documents in a resultant document: [How to apply or reject changes detected during document comparison in Java](../https://docs.groupdocs.com/display/comparisonjava/Accept+or+Reject+detected+changes)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | документ | java.io.OutputStream | Поток вывода результирующего документа |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.comparison.options.save/saveoptions) | Параметры сохранения для настройки сохранения результирующего документа |
|
|  | applyChangeOptions | [ApplyChangeOptions](../../com.groupdocs.comparison.options/applychangeoptions) | Пользовательские параметры применения изменений для настройки процесса применения изменений |
|

### getResultString() {#getResultString--}
```
public String getResultString()
```


Получает строку результата после сравнения (только для текстового сравнения).


**Returns:**
java.lang.String — строка результата

### getSourceFolder() {#getSourceFolder--}
```
public String getSourceFolder()
```


Возвращает исходную папку, которая сравнивается.


**Returns:**
java.lang.String — исходная папка

### getTargetFolder() {#getTargetFolder--}
```
public String getTargetFolder()
```


Возвращает целевую папку, которая сравнивается.


**Returns:**
java.lang.String — целевая папка

### selfComparisonCheck(Document source, Document target) {#selfComparisonCheck-com.groupdocs.comparison.Document-com.groupdocs.comparison.Document-}
```
public static void selfComparisonCheck(Document source, Document target)
```


Проверка самосравнения (e498c23). C# 7a7668c internal; оставлен публичным, чтобы тесты core.common могли вызывать.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [Document](../../com.groupdocs.comparison/document) |  |
| target | [Document](../../com.groupdocs.comparison/document) |  |

### close() {#close--}
```
public void close()
```


Освобождает ресурсы.



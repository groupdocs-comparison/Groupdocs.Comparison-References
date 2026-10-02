---
title: "FileFormatException"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Исключение, которое выбрасывается при сравнении файлов с разными типами сравнения."
type: docs
weight: 12
url: /ru/java/com.groupdocs.comparison.common.exceptions/fileformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.groupdocs.foundation.exception.GroupDocsException, [com.groupdocs.comparison.common.exceptions.ComparisonException](../../com.groupdocs.comparison.common.exceptions/comparisonexception)
```
public class FileFormatException extends ComparisonException
```

Исключение, которое выбрасывается при сравнении файлов с разными типами сравнения.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [FileFormatException(String sourceComparisonType, String targetComparisonType)](#FileFormatException-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса FileFormatException с типами сравнения источника и назначения. |
|
### FileFormatException(String sourceComparisonType, String targetComparisonType) {#FileFormatException-java.lang.String-java.lang.String-}
```
public FileFormatException(String sourceComparisonType, String targetComparisonType)
```


Инициализирует новый экземпляр класса FileFormatException с типами сравнения источника и назначения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | sourceComparisonType | java.lang.String | Тип сравнения источника |
|
|  | targetComparisonType | java.lang.String | Тип сравнения назначения |
|


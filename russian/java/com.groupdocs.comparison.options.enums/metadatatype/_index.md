---
title: "MetadataType"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Определяет, откуда документ результата будет получать метаданные."
type: docs
weight: 12
url: /ru/java/com.groupdocs.comparison.options.enums/metadatatype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MetadataType extends Enum<MetadataType>
```

Определяет, откуда документ результата будет получать метаданные.


Пример использования:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    SaveOptions saveOptions = new SaveOptions();
    saveOptions.setCloneMetadataType(MetadataType.FILE_AUTHOR);

    comparer.compare(resultFile, saveOptions);
 }
 
````


## Поля

| Поле | Описание |
| --- | --- |
|  | [DEFAULT](#DEFAULT) | Метаданные останутся без изменений. |
|
|  | [SOURCE](#SOURCE) | Метаданные будут взяты из исходного документа. |
|
|  | [TARGET](#TARGET) | Метаданные будут взяты из целевого документа. |
|
|  | [FILE_AUTHOR](#FILE-AUTHOR) | Метаданные будут заданы пользователем. |
|
## Методы

| Метод | Описание |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Разбирает строковое представление MetadataType, чтобы получить константу перечисления. |
|
|  | [toString()](#toString--) | Строковое представление MetadataType. |
|
### DEFAULT {#DEFAULT}
```
public static final MetadataType DEFAULT
```


Метаданные останутся без изменений.


### SOURCE {#SOURCE}
```
public static final MetadataType SOURCE
```


Метаданные будут взяты из исходного документа.


### TARGET {#TARGET}
```
public static final MetadataType TARGET
```


Метаданные будут взяты из целевого документа.


### FILE_AUTHOR {#FILE-AUTHOR}
```
public static final MetadataType FILE_AUTHOR
```


Метаданные будут заданы пользователем.


### values() {#values--}
```
public static MetadataType[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.MetadataType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static MetadataType valueOf(String name)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static MetadataType fromString(String toStringValue)
```


Разбирает строковое представление MetadataType, чтобы получить константу перечисления.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | toStringValue | java.lang.String | Строковое представление MetadataType |
|

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - MetadataType enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


Строковое представление MetadataType.


**Returns:**
java.lang.String — строковое значение константы перечисления


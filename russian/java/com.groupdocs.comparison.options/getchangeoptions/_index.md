---
title: "GetChangeOptions"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Позволяет настраивать фильтрацию для получения конкретных типов изменений из результата сравнения."
type: docs
weight: 13
url: /ru/java/com.groupdocs.comparison.options/getchangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class GetChangeOptions
```

Позволяет настраивать фильтрацию для получения конкретных типов изменений из результата сравнения.


Пример использования:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();

     GetChangeOptions getChangeOptions = new GetChangeOptions();

     getChangeOptions.setFilter(ChangeType.DELETED);

     ChangeInfo[] changes = comparer.getChanges(getChangeOptions);
     System.out.println(Arrays.toString(changes));
 }
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [GetChangeOptions()](#GetChangeOptions--) | Инициализирует новый экземпляр класса GetChangeOptions. |
|
|  | [GetChangeOptions(ChangeType filter)](#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-) | Инициализирует новый экземпляр класса GetChangeOptions для указанного типа фильтра. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getFilter()](#getFilter--) | Получает фильтр для получения конкретных типов изменений из результата сравнения. |
|
|  | [setFilter(ChangeType value)](#setFilter-com.groupdocs.comparison.result.ChangeType-) | Устанавливает фильтр для получения конкретных типов изменений из результата сравнения. |
|
### GetChangeOptions() {#GetChangeOptions--}
```
public GetChangeOptions()
```


Инициализирует новый экземпляр класса GetChangeOptions.


### GetChangeOptions(ChangeType filter) {#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-}
```
public GetChangeOptions(ChangeType filter)
```


Инициализирует новый экземпляр класса GetChangeOptions для указанного типа фильтра.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filter | [ChangeType](../../com.groupdocs.comparison.result/changetype) |  |

### getFilter() {#getFilter--}
```
public final ChangeType getFilter()
```


Получает фильтр для получения конкретных типов изменений из результата сравнения.


**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the filter specifying the types of changes to be retrieved.

### setFilter(ChangeType value) {#setFilter-com.groupdocs.comparison.result.ChangeType-}
```
public final void setFilter(ChangeType value)
```


Устанавливает фильтр для получения конкретных типов изменений из результата сравнения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [ChangeType](../../com.groupdocs.comparison.result/changetype) | Фильтр, указывающий типы изменений, которые следует получить. |
|


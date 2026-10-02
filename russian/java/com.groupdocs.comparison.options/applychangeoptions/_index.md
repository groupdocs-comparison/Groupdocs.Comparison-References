---
title: "ApplyChangeOptions"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Позволяет обновлять список изменений перед их применением к результирующему документу."
type: docs
weight: 10
url: /ru/java/com.groupdocs.comparison.options/applychangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyChangeOptions
```

Позволяет обновлять список изменений перед их применением к результирующему документу.


Пример использования:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();
     ChangeInfo[] changes = comparer.getChanges();
     changes[0].setComparisonAction(ComparisonAction.REJECT);

     final ApplyChangeOptions applyChangeOptions = new ApplyChangeOptions(changes);

     comparer.applyChanges(resultFile, applyChangeOptions);
 }
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [ApplyChangeOptions()](#ApplyChangeOptions--) | Инициализирует новый экземпляр класса ApplyChangeOptions. |
|
|  | [ApplyChangeOptions(List<ChangeInfo> changes)](#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Инициализирует новый экземпляр класса ApplyChangeOptions со списком изменений. |
|
|  | [ApplyChangeOptions(ChangeInfo[] changes)](#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---) | Инициализирует новый экземпляр класса ApplyChangeOptions с массивом изменений. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getChanges()](#getChanges--) | Получает массив изменений, которые должны быть применены к результирующему документу. |
|
|  | [setChanges(ChangeInfo[] value)](#setChanges-com.groupdocs.comparison.result.ChangeInfo---) | Устанавливает массив изменений, которые должны быть применены к результирующему документу. |
|
|  | [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | Устанавливает список изменений, которые должны быть применены к результирующему документу. |
|
|  | [isSaveOriginalState()](#isSaveOriginalState--) | Получает флаг, определяющий, следует ли сохранять исходное состояние. |
|
|  | [setSaveOriginalState(boolean saveOriginalState)](#setSaveOriginalState-boolean-) | Устанавливает флаг, определяющий, следует ли сохранять исходное состояние. |
|
### ApplyChangeOptions() {#ApplyChangeOptions--}
```
public ApplyChangeOptions()
```


Инициализирует новый экземпляр класса ApplyChangeOptions.


### ApplyChangeOptions(List<ChangeInfo> changes) {#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public ApplyChangeOptions(List<ChangeInfo> changes)
```


Инициализирует новый экземпляр класса ApplyChangeOptions со списком изменений.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | изменения | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | Список изменений, которые будут применены |
|

### ApplyChangeOptions(ChangeInfo[] changes) {#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---}
```
public ApplyChangeOptions(ChangeInfo[] changes)
```


Инициализирует новый экземпляр класса ApplyChangeOptions с массивом изменений.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | changes | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | Список изменений, которые будут применены |
|

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


Получает массив изменений, которые должны быть применены к результирующему документу.


**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - массив изменений, которые будут применены

### setChanges(ChangeInfo[] value) {#setChanges-com.groupdocs.comparison.result.ChangeInfo---}
```
public final void setChanges(ChangeInfo[] value)
```


Устанавливает массив изменений, которые должны быть применены к результирующему документу.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | Массив изменений, которые будут применены |
|

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


Устанавливает список изменений, которые должны быть применены к результирующему документу.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | Список изменений, которые будут применены |
|

### isSaveOriginalState() {#isSaveOriginalState--}
```
public boolean isSaveOriginalState()
```


Получает флаг, определяющий, следует ли сохранять исходное состояние. Значение по умолчанию: false.


**Returns:**
boolean - true, если исходное состояние следует сохранять, иначе false

### setSaveOriginalState(boolean saveOriginalState) {#setSaveOriginalState-boolean-}
```
public void setSaveOriginalState(boolean saveOriginalState)
```


Устанавливает флаг, определяющий, следует ли сохранять исходное состояние.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | saveOriginalState | boolean | True, если исходное состояние следует сохранять, иначе false |
|


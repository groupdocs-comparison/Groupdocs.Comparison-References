---
title: "DiagramMasterSetting"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Представляет настройки сравнения главной диаграммы."
type: docs
weight: 10
url: /ru/java/com.groupdocs.comparison.options.style/diagrammastersetting/
---
**Inheritance:**
java.lang.Object
```
public class DiagramMasterSetting
```

Представляет настройки сравнения главной диаграммы.


Пример использования:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    final DiagramMasterSetting diagramMasterSetting = new DiagramMasterSetting();
    diagramMasterSetting.setMasterPath(masterFilePath);

    final CompareOptions compareOptions = new CompareOptions();
    compareOptions.setDiagramMasterSetting(diagramMasterSetting);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [DiagramMasterSetting()](#DiagramMasterSetting--) | Инициализирует новый экземпляр класса DiagramMasterSetting. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [isUseSourceMaster()](#isUseSourceMaster--) | Получает флаг, указывающий, будет ли использоваться путь к исходному мастеру. |
|
|  | [setUseSourceMaster(boolean value)](#setUseSourceMaster-boolean-) | Получает флаг, указывающий, следует ли использовать путь к исходному мастеру. |
|
|  | [getMasterPath()](#getMasterPath--) | Получает основной путь, который будет использоваться для рендеринга документов. |
|
|  | [setMasterPath(String value)](#setMasterPath-java.lang.String-) | Устанавливает основной путь, который следует использовать для рендеринга документов. |
|
### DiagramMasterSetting() {#DiagramMasterSetting--}
```
public DiagramMasterSetting()
```


Инициализирует новый экземпляр класса DiagramMasterSetting.


### isUseSourceMaster() {#isUseSourceMaster--}
```
public final boolean isUseSourceMaster()
```


Получает флаг, указывающий, будет ли использоваться путь к исходному мастеру.


**Returns:**
boolean - true, если исходный основной путь будет отображён, иначе false

### setUseSourceMaster(boolean value) {#setUseSourceMaster-boolean-}
```
public final void setUseSourceMaster(boolean value)
```


Получает флаг, указывающий, следует ли использовать путь к исходному мастеру.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | boolean | true, если исходный основной путь должен быть отображён, иначе false |
|

### getMasterPath() {#getMasterPath--}
```
public final String getMasterPath()
```


Получает основной путь, который будет использоваться для рендеринга документов. MasterPath необходим для создания результирующего документа из набора стандартных фигур.


**Returns:**
java.lang.String - путь к основному документу, если он установлен, иначе путь к стандартному основному документу

### setMasterPath(String value) {#setMasterPath-java.lang.String-}
```
public final void setMasterPath(String value)
```


Устанавливает основной путь, который следует использовать для рендеринга документов. MasterPath необходим для создания результирующего документа из набора стандартных фигур.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.lang.String | Путь к основному документу, если он установлен, иначе путь к стандартному основному документу |
|


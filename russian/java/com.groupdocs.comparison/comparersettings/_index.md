---
title: "ComparerSettings"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Определяет настройки для настройки поведения класса."
type: docs
weight: 11
url: /ru/java/com.groupdocs.comparison/comparersettings/
---
**Inheritance:**
java.lang.Object
```
public class ComparerSettings
```

Определяет настройки для настройки поведения класса [Comparer](../../com.groupdocs.comparison/comparer).


Пример использования:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final ComparerSettings comparerSettings = new ComparerSettings();
     comparerSettings.setLogger(new ConsoleLogger(false, false, true, true));

     comparer.compare(resultFile, comparerSettings);
 }
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [ComparerSettings()](#ComparerSettings--) | Создаёт новый экземпляр класса ComparerSettings. |
|
|  | [ComparerSettings(ILogger logger)](#ComparerSettings-com.groupdocs.foundation.logging.ILogger-) | Создаёт новый экземпляр класса ComparerSettings. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getLogger()](#getLogger--) | Получает реализацию логгера, используемую для ведения журналов. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Устанавливает реализацию логгера для ведения журналов. |
|
### ComparerSettings() {#ComparerSettings--}
```
public ComparerSettings()
```


Создаёт новый экземпляр класса ComparerSettings.


### ComparerSettings(ILogger logger) {#ComparerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ComparerSettings(ILogger logger)
```


Создаёт новый экземпляр класса ComparerSettings.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | регистратор | com.groupdocs.foundation.logging.ILogger | логгер, который будет использоваться |
|

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Получает реализацию логгера, используемую для ведения журналов.


**Returns:**
com.groupdocs.foundation.logging.ILogger — регистратор

### setLogger(ILogger value) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


Устанавливает реализацию логгера для ведения журналов.


Используйте com.groupdocs.foundation.logging.NullLogger#NULL_LOGGER.NULL_LOGGER для отключения журналирования.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | com.groupdocs.foundation.logging.ILogger | реализацию логгера для установки |
|


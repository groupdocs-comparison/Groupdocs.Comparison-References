---
title: "ComparisonLogger"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Реализует методы логирования и способ настройки интегрированного или пользовательского логгера."
type: docs
weight: 10
url: /ru/java/com.groupdocs.comparison.logging/comparisonlogger/
---
**Inheritance:**
java.lang.Object
```
public class ComparisonLogger
```

Реализует методы логирования и способ настройки интегрированного или пользовательского логгера.


Класс позволяет настраивать интегрированный или пользовательский регистратор и записывать сообщения журнала.


Пример использования:

````

 ComparisonLogger.setLogger(new com.groupdocs.comparison.logging.ConsoleLogger(false, true, true, true));
 ComparisonLogger.warning(exceptionObject, "Warning message with parameters: {}, {}", "parameter1", 2);
 
````


## Методы

| Метод | Описание |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Записывает трассировочное сообщение в предварительно настроенный регистратор. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Записывает трассировочное сообщение, стек вызовов и сообщение из исключения в предварительно настроенный регистратор. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | Проверяет, включена ли трассировочная запись в предварительно настроенном регистраторе. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Записывает отладочное сообщение в предварительно настроенный регистратор. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Записывает отладочное сообщение, стек вызовов и сообщение из исключения в предварительно настроенный регистратор. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | Проверяет, включена ли отладочная запись в предварительно настроенном регистраторе. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Записывает предупреждающее сообщение в предварительно настроенный регистратор. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Записывает предупреждающее сообщение, стек вызовов и сообщение из исключения в предварительно настроенный регистратор. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | Проверяет, включена ли запись предупреждений в предварительно настроенном регистраторе. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Записывает сообщение об ошибке в предварительно настроенный регистратор. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Записывает сообщение об ошибке, стек вызовов и сообщение из исключения в предварительно настроенный регистратор. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | Проверяет, включена ли запись ошибок в предварительно настроенном регистраторе. |
|
|  | [getLogger()](#getLogger--) | Получает предварительно настроенный регистратор, который будет использоваться для записи всех типов журналов. |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Устанавливает регистратор, который будет использоваться для записи всех типов журналов. |
|
### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


Записывает трассировочное сообщение в предварительно настроенный регистратор.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | message | java.lang.String | Сообщение, если null, поведение зависит от регистратора |
|
|  | arguments | java.lang.Object[] | Аргументы, которые будут встроены в сообщение, если null, поведение зависит от регистратора |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
```


Записывает трассировочное сообщение, стек вызовов и сообщение из исключения в предварительно настроенный регистратор.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Объект throwable, который будет использоваться для получения стека вызовов, если null, поведение зависит от регистратора |
|
|  | message | java.lang.String | Сообщение, если null, поведение зависит от регистратора |
|
|  | arguments | java.lang.Object[] | Аргументы, которые будут встроены в сообщение, если null, поведение зависит от регистратора |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public static boolean isTraceEnabled()
```


Проверяет, включена ли трассировочная запись в предварительно настроенном регистраторе.


**Returns:**
boolean — true, если включено в предварительно настроенном регистраторе, иначе false

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


Записывает отладочное сообщение в предварительно настроенный регистратор.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | message | java.lang.String | Сообщение, если null, поведение зависит от регистратора |
|
|  | arguments | java.lang.Object[] | Аргументы, которые будут встроены в сообщение, если null, поведение зависит от регистратора |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
```


Записывает отладочное сообщение, стек вызовов и сообщение из исключения в предварительно настроенный регистратор.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Объект throwable, который будет использоваться для получения стека вызовов, если null, поведение зависит от регистратора |
|
|  | message | java.lang.String | Сообщение, если null, поведение зависит от регистратора |
|
|  | arguments | java.lang.Object[] | Аргументы, которые будут встроены в сообщение, если null, поведение зависит от регистратора |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public static boolean isDebugEnabled()
```


Проверяет, включена ли отладочная запись в предварительно настроенном регистраторе.


**Returns:**
boolean — true, если включено в предварительно настроенном регистраторе, иначе false

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


Записывает предупреждающее сообщение в предварительно настроенный регистратор.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | message | java.lang.String | Сообщение, если null, поведение зависит от регистратора |
|
|  | arguments | java.lang.Object[] | Аргументы, которые будут встроены в сообщение, если null, поведение зависит от регистратора |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
```


Записывает предупреждающее сообщение, стек вызовов и сообщение из исключения в предварительно настроенный регистратор.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Объект throwable, который будет использоваться для получения стека вызовов, если null, поведение зависит от регистратора |
|
|  | message | java.lang.String | Сообщение, если null, поведение зависит от регистратора |
|
|  | arguments | java.lang.Object[] | Аргументы, которые будут встроены в сообщение, если null, поведение зависит от регистратора |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public static boolean isWarningEnabled()
```


Проверяет, включена ли запись предупреждений в предварительно настроенном регистраторе.


**Returns:**
boolean — true, если включено в предварительно настроенном регистраторе, иначе false

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


Записывает сообщение об ошибке в предварительно настроенный регистратор.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | message | java.lang.String | Сообщение, если null, поведение зависит от регистратора |
|
|  | arguments | java.lang.Object[] | Аргументы, которые будут встроены в сообщение, если null, поведение зависит от регистратора |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
```


Записывает сообщение об ошибке, стек вызовов и сообщение из исключения в предварительно настроенный регистратор.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Объект throwable, который будет использоваться для получения стека вызовов, если null, поведение зависит от регистратора |
|
|  | message | java.lang.String | Сообщение, если null, поведение зависит от регистратора |
|
|  | arguments | java.lang.Object[] | Аргументы, которые будут встроены в сообщение, если null, поведение зависит от регистратора |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public static boolean isErrorEnabled()
```


Проверяет, включена ли запись ошибок в предварительно настроенном регистраторе.


**Returns:**
boolean — true, если включено в предварительно настроенном регистраторе, иначе false

### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


Получает предварительно настроенный регистратор, который будет использоваться для записи всех типов журналов.


**Returns:**
com.groupdocs.foundation.logging.ILogger — регистратор

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


Устанавливает регистратор, который будет использоваться для записи всех типов журналов.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | регистратор | com.groupdocs.foundation.logging.ILogger | Регистратор |
|


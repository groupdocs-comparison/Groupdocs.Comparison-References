---
title: "FileLogger"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Логгер, который записывает логи в файл."
type: docs
weight: 11
url: /ru/java/com.groupdocs.comparison.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

Логгер, который записывает логи в файл.


Должен использоваться вместе с [ComparisonLogger](../../com.groupdocs.comparison.logging/comparisonlogger).


Пример использования:

````

 ComparisonLogger.setLogger(new FileLogger("/path/to/file.log.txt", false, true, true, true));
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [FileLogger(String filePath)](#FileLogger-java.lang.String-) | Инициализирует новый экземпляр класса FileLogger с путем к файлу. |
|
|  | [FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | Инициализирует новый экземпляр класса FileLogger с путем к файлу и конфигурацией уровней журналирования. |
|
## Поля

| Поле | Описание |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Записывает трассировочное сообщение в файл. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Записывает трассировочное сообщение в файл. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | Проверяет, включено ли трассировочное журналирование. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Записывает отладочное сообщение в файл. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Записывает отладочное сообщение в файл. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | Проверяет, включено ли отладочное журналирование. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Записывает предупреждающее сообщение в файл. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Записывает предупреждающее сообщение в файл. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | Проверяет, включено ли предупреждающее журналирование. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Записывает сообщение об ошибке в файл. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Записывает сообщение об ошибке в файл. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | Проверяет, включено ли журналирование ошибок. |
|
### FileLogger(String filePath) {#FileLogger-java.lang.String-}
```
public FileLogger(String filePath)
```


Инициализирует новый экземпляр класса FileLogger с путем к файлу.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к файлу, который будет использоваться для записи журналов |
|

### FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


Инициализирует новый экземпляр класса FileLogger с путем к файлу и конфигурацией уровней журналирования.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к файлу, который будет использоваться для записи журналов |
|
|  | isTraceEnabled | boolean | True, чтобы включить трассировку журналов, false в противном случае |
|
|  | isDebugEnabled | boolean | True, чтобы включить отладочную запись журналов, false в противном случае |
|
|  | isWarningEnabled | boolean | True, чтобы включить запись предупреждений, false в противном случае |
|
|  | isErrorEnabled | boolean | True, чтобы включить запись ошибок, false в противном случае |
|

### MESSAGE {#MESSAGE}
```
public static final String MESSAGE
```


### EXCEPTION {#EXCEPTION}
```
public static final String EXCEPTION
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public void trace(String message, Object[] arguments)
```


Записывает трассировочное сообщение в файл.


Сообщения трассировки журнала предоставляют максимально подробную информацию о потоке приложения.
Сообщение может содержать одну или несколько {} , которые будут заменены соответствующими аргументами.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | message | java.lang.String | Сообщение. |
|
|  | arguments | java.lang.Object[] | Аргументы, заменяют {} в сообщении в порядке передачи, null будет записан как 'null' |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


Записывает трассировочное сообщение в файл.


Сообщения трассировки журнала предоставляют максимально подробную информацию о потоке приложения.
Сообщение может содержать одну или несколько {} , которые будут заменены соответствующими аргументами.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Объект throwable, который будет использоваться для получения трассировки стека |
|
|  | message | java.lang.String | Сообщение. |
|
|  | arguments | java.lang.Object[] | Аргументы, заменяют {} в сообщении в порядке передачи, null будет записан как 'null' |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


Проверяет, включено ли трассировочное журналирование.


**Returns:**
boolean — true, если включено, иначе false

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


Записывает отладочное сообщение в файл.


Сообщения отладочного журнала предоставляют информацию о различных процессах в потоке приложения.
Сообщение может содержать одну или несколько {} , которые будут заменены соответствующими аргументами.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | message | java.lang.String | Сообщение. |
|
|  | arguments | java.lang.Object[] | Аргументы, заменяют {} в сообщении в порядке передачи, null будет записан как 'null' |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


Записывает отладочное сообщение в файл.


Сообщения отладочного журнала предоставляют информацию о различных процессах в потоке приложения.
Сообщение может содержать одну или несколько {} , которые будут заменены соответствующими аргументами.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Объект throwable, который будет использоваться для получения трассировки стека |
|
|  | message | java.lang.String | Сообщение. |
|
|  | arguments | java.lang.Object[] | Аргументы, заменяют {} в сообщении в порядке передачи, null будет записан как 'null' |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


Проверяет, включено ли отладочное журналирование.


**Returns:**
boolean — true, если включено, иначе false

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


Записывает предупреждающее сообщение в файл.


Сообщения журнала предупреждений предоставляют информацию о неожиданных и восстанавливаемых событиях в потоке приложения.
Сообщение может содержать одну или несколько {} , которые будут заменены соответствующими аргументами.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | message | java.lang.String | Сообщение. |
|
|  | arguments | java.lang.Object[] | Аргументы, заменяют {} в сообщении в порядке передачи, null будет записан как 'null' |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


Записывает предупреждающее сообщение в файл.


Сообщения журнала предупреждений предоставляют информацию о неожиданных и восстанавливаемых событиях в потоке приложения.
Сообщение может содержать одну или несколько {} , которые будут заменены соответствующими аргументами.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Объект throwable, который будет использоваться для получения трассировки стека |
|
|  | message | java.lang.String | Сообщение. |
|
|  | arguments | java.lang.Object[] | Аргументы, заменяют {} в сообщении в порядке передачи, null будет записан как 'null' |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


Проверяет, включено ли предупреждающее журналирование.


**Returns:**
boolean — true, если включено, иначе false

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


Записывает сообщение об ошибке в файл.


Сообщения журнала ошибок предоставляют информацию о необратимых событиях в потоке приложения.
Сообщение может содержать одну или несколько {} , которые будут заменены соответствующими аргументами.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | message | java.lang.String | Сообщение. |
|
|  | arguments | java.lang.Object[] | Аргументы, заменяют {} в сообщении в порядке передачи, null будет записан как 'null' |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


Записывает сообщение об ошибке в файл.


Сообщения журнала ошибок предоставляют информацию о необратимых событиях в потоке приложения.
Сообщение может содержать одну или несколько {} , которые будут заменены соответствующими аргументами.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Объект throwable, который будет использоваться для получения трассировки стека |
|
|  | message | java.lang.String | Сообщение. |
|
|  | arguments | java.lang.Object[] | Аргументы, заменяют {} в сообщении в порядке передачи, null будет записан как 'null' |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


Проверяет, включено ли журналирование ошибок.


**Returns:**
boolean — true, если включено, иначе false


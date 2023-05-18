---
title: FileLogger
second_title: GroupDocs.Comparison for Java API Reference
description: Logger that writes logs to file.
type: docs
weight: 11
url: /java/com.groupdocs.comparison.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

Logger that writes logs to file.

Should be used together with [ComparisonLogger](../../com.groupdocs.comparison.logging/comparisonlogger).

Example usage:

```

 ComparisonLogger.setLogger(new FileLogger("/path/to/file.log.txt", false, true, true, true));
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [FileLogger(String filePath)](#FileLogger-java.lang.String-) | Initializes a new instance of the FileLogger class with file path. |
| [FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | Initializes a new instance of the FileLogger class with file path and logs levels configuration. |
## Fields

| Field | Description |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## Methods

| Method | Description |
| --- | --- |
| [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Writes a trace message to the file. |
| [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Writes a trace message to the file. |
| [isTraceEnabled()](#isTraceEnabled--) | Checks whether trace logging enabled. |
| [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Writes a debug message to the file. |
| [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Writes a debug message to the file. |
| [isDebugEnabled()](#isDebugEnabled--) | Checks whether debug logging enabled. |
| [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Writes a warning message to the file. |
| [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Writes a warning message to the file. |
| [isWarningEnabled()](#isWarningEnabled--) | Checks whether warning logging enabled. |
| [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Writes an error message to the file. |
| [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Writes an error message to the file. |
| [isErrorEnabled()](#isErrorEnabled--) | Checks whether error logging enabled. |
### FileLogger(String filePath) {#FileLogger-java.lang.String-}
```
public FileLogger(String filePath)
```


Initializes a new instance of the FileLogger class with file path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path to the file that will be used to write logs |

### FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


Initializes a new instance of the FileLogger class with file path and logs levels configuration.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path to the file that will be used to write logs |
| isTraceEnabled | boolean | True to enable trace logging, false otherwise |
| isDebugEnabled | boolean | True to enable debug logging, false otherwise |
| isWarningEnabled | boolean | True to enable warning logging, false otherwise |
| isErrorEnabled | boolean | True to enable error logging, false otherwise |

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


Writes a trace message to the file.

Trace log messages provide maximum detailed information about application flow. The message can contain one or few \{\} which will be replaced by corresponding arguments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message. |
| arguments | java.lang.Object[] | The arguments, replaces \{\} in message in order of passing, null will be written as 'null' |

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


Writes a trace message to the file.

Trace log messages provide maximum detailed information about application flow. The message can contain one or few \{\} which will be replaced by corresponding arguments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| throwable | java.lang.Throwable | The throwable object that will be used to get the stacktrace |
| message | java.lang.String | The message. |
| arguments | java.lang.Object[] | The arguments, replaces \{\} in message in order of passing, null will be written as 'null' |

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


Checks whether trace logging enabled.

**Returns:**
boolean - true if enabled, otherwise false
### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


Writes a debug message to the file.

Debug log messages provide information about different processes in application flow. The message can contain one or few \{\} which will be replaced by corresponding arguments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message. |
| arguments | java.lang.Object[] | The arguments, replaces \{\} in message in order of passing, null will be written as 'null' |

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


Writes a debug message to the file.

Debug log messages provide information about different processes in application flow. The message can contain one or few \{\} which will be replaced by corresponding arguments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| throwable | java.lang.Throwable | The throwable object that will be used to get the stacktrace |
| message | java.lang.String | The message. |
| arguments | java.lang.Object[] | The arguments, replaces \{\} in message in order of passing, null will be written as 'null' |

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


Checks whether debug logging enabled.

**Returns:**
boolean - true if enabled, otherwise false
### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


Writes a warning message to the file.

Warning log messages provide information about unexpected and recoverable events in application flow. The message can contain one or few \{\} which will be replaced by corresponding arguments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message. |
| arguments | java.lang.Object[] | The arguments, replaces \{\} in message in order of passing, null will be written as 'null' |

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


Writes a warning message to the file.

Warning log messages provide information about unexpected and recoverable events in application flow. The message can contain one or few \{\} which will be replaced by corresponding arguments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| throwable | java.lang.Throwable | The throwable object that will be used to get the stacktrace |
| message | java.lang.String | The message. |
| arguments | java.lang.Object[] | The arguments, replaces \{\} in message in order of passing, null will be written as 'null' |

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


Checks whether warning logging enabled.

**Returns:**
boolean - true if enabled, otherwise false
### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


Writes an error message to the file.

Error log messages provide information about unrecoverable events in application flow. The message can contain one or few \{\} which will be replaced by corresponding arguments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message. |
| arguments | java.lang.Object[] | The arguments, replaces \{\} in message in order of passing, null will be written as 'null' |

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


Writes an error message to the file.

Error log messages provide information about unrecoverable events in application flow. The message can contain one or few \{\} which will be replaced by corresponding arguments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| throwable | java.lang.Throwable | The throwable object that will be used to get the stacktrace |
| message | java.lang.String | The message. |
| arguments | java.lang.Object[] | The arguments, replaces \{\} in message in order of passing, null will be written as 'null' |

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


Checks whether error logging enabled.

**Returns:**
boolean - true if enabled, otherwise false

---
title: ComparisonLogger
second_title: GroupDocs.Comparison for Java API Reference
description: Implements logging methods and a way to configure integrated or set user defined logger.
type: docs
weight: 10
url: /java/com.groupdocs.comparison.logging/comparisonlogger/
---
**Inheritance:**
java.lang.Object
```
public class ComparisonLogger
```

Implements logging methods and a way to configure integrated or set user defined logger.

The class allows setting up integrated or custom logger and writing log messages.

Example usage:

```

 ComparisonLogger.setLogger(new com.groupdocs.comparison.logging.ConsoleLogger(false, true, true, true));
 ComparisonLogger.warning(exceptionObject, "Warning message with parameters: {}, {}", "parameter1", 2);
 
```
## Methods

| Method | Description |
| --- | --- |
| [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Writes trace message to pre-configured logger. |
| [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Writes trace message, stacktrace and message from an exception to pre-configured logger. |
| [isTraceEnabled()](#isTraceEnabled--) | Checks whether trace logging enabled in pre-configured logger. |
| [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Writes debug message to pre-configured logger. |
| [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Writes debug message, stacktrace and message from an exception to pre-configured logger. |
| [isDebugEnabled()](#isDebugEnabled--) | Checks whether debug logging enabled in pre-configured logger. |
| [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Writes warning message to pre-configured logger. |
| [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Writes warning message, stacktrace and message from an exception to pre-configured logger. |
| [isWarningEnabled()](#isWarningEnabled--) | Checks whether warning logging enabled in pre-configured logger. |
| [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Writes error message to pre-configured logger. |
| [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Writes error message, stacktrace and message from an exception to pre-configured logger. |
| [isErrorEnabled()](#isErrorEnabled--) | Checks whether error logging enabled in pre-configured logger. |
| [getLogger()](#getLogger--) | Gets pre-configured logger that will be used to write all types of logs. |
| [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Sets the logger that will be used to write all types of logs. |
### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


Writes trace message to pre-configured logger.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message, if null behaviour depends on logger |
| arguments | java.lang.Object[] | The arguments to be embedded into message, if null behaviour depends on logger |

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
```


Writes trace message, stacktrace and message from an exception to pre-configured logger.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| throwable | java.lang.Throwable | The throwable object that will be used to get the stacktrace, if null behaviour depends on logger |
| message | java.lang.String | The message, if null behaviour depends on logger |
| arguments | java.lang.Object[] | The arguments to be embedded into message, if null behaviour depends on logger |

### isTraceEnabled() {#isTraceEnabled--}
```
public static boolean isTraceEnabled()
```


Checks whether trace logging enabled in pre-configured logger.

**Returns:**
boolean - true if enabled in pre-configured logger, otherwise false
### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


Writes debug message to pre-configured logger.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message, if null behaviour depends on logger |
| arguments | java.lang.Object[] | The arguments to be embedded into message, if null behaviour depends on logger |

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
```


Writes debug message, stacktrace and message from an exception to pre-configured logger.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| throwable | java.lang.Throwable | The throwable object that will be used to get the stacktrace, if null behaviour depends on logger |
| message | java.lang.String | The message, if null behaviour depends on logger |
| arguments | java.lang.Object[] | The arguments to be embedded into message, if null behaviour depends on logger |

### isDebugEnabled() {#isDebugEnabled--}
```
public static boolean isDebugEnabled()
```


Checks whether debug logging enabled in pre-configured logger.

**Returns:**
boolean - true if enabled in pre-configured logger, otherwise false
### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


Writes warning message to pre-configured logger.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message, if null behaviour depends on logger |
| arguments | java.lang.Object[] | The arguments to be embedded into message, if null behaviour depends on logger |

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
```


Writes warning message, stacktrace and message from an exception to pre-configured logger.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| throwable | java.lang.Throwable | The throwable object that will be used to get the stacktrace, if null behaviour depends on logger |
| message | java.lang.String | The message, if null behaviour depends on logger |
| arguments | java.lang.Object[] | The arguments to be embedded into message, if null behaviour depends on logger |

### isWarningEnabled() {#isWarningEnabled--}
```
public static boolean isWarningEnabled()
```


Checks whether warning logging enabled in pre-configured logger.

**Returns:**
boolean - true if enabled in pre-configured logger, otherwise false
### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


Writes error message to pre-configured logger.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message, if null behaviour depends on logger |
| arguments | java.lang.Object[] | The arguments to be embedded into message, if null behaviour depends on logger |

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
```


Writes error message, stacktrace and message from an exception to pre-configured logger.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| throwable | java.lang.Throwable | The throwable object that will be used to get the stacktrace, if null behaviour depends on logger |
| message | java.lang.String | The message, if null behaviour depends on logger |
| arguments | java.lang.Object[] | The arguments to be embedded into message, if null behaviour depends on logger |

### isErrorEnabled() {#isErrorEnabled--}
```
public static boolean isErrorEnabled()
```


Checks whether error logging enabled in pre-configured logger.

**Returns:**
boolean - true if enabled in pre-configured logger, otherwise false
### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


Gets pre-configured logger that will be used to write all types of logs.

**Returns:**
com.groupdocs.foundation.logging.ILogger - the logger
### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


Sets the logger that will be used to write all types of logs.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| logger | com.groupdocs.foundation.logging.ILogger | The logger |


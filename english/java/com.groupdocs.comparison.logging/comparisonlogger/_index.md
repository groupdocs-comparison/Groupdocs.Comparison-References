---
title: ComparisonLogger
second_title: GroupDocs.Comparison for Java API Reference
description: Implements logging messages to integrated or user defined logger.
type: docs
weight: 10
url: /java/com.groupdocs.comparison.logging/comparisonlogger/
---
**Inheritance:**
java.lang.Object
```
public class ComparisonLogger
```

Implements logging messages to integrated or user defined logger.
## Methods

| Method | Description |
| --- | --- |
| [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Trace message |
| [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Trace message |
| [isTraceEnabled()](#isTraceEnabled--) | Checks is trace logging enabled |
| [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Debug message |
| [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Debug message |
| [isDebugEnabled()](#isDebugEnabled--) | Checks is debug logging enabled |
| [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Warning message |
| [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Warning message |
| [isWarningEnabled()](#isWarningEnabled--) | Checks is warning logging enabled |
| [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Error message |
| [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Error message |
| [isErrorEnabled()](#isErrorEnabled--) | Checks is error logging enabled |
| [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Sets the logger. |
### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


Trace message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The trace message, can contains \{\} to be replaced with arguments |
| arguments | java.lang.Object[] | The arguments, replaces \{\} in message in order of passing |

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
```


Trace message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| throwable | java.lang.Throwable | The exception message |
| message | java.lang.String | The trace message, can contains \{\} to be replaced with arguments |
| arguments | java.lang.Object[] | The arguments, replaces \{\} in message in order of passing |

### isTraceEnabled() {#isTraceEnabled--}
```
public static boolean isTraceEnabled()
```


Checks is trace logging enabled

**Returns:**
boolean - true if enabled
### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


Debug message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The debug message, can contains \{\} to be replaced with arguments |
| arguments | java.lang.Object[] | The arguments, replaces \{\} in message in order of passing |

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
```


Debug message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| throwable | java.lang.Throwable | The exception message |
| message | java.lang.String | The debug message, can contains \{\} to be replaced with arguments |
| arguments | java.lang.Object[] | The arguments, replaces \{\} in message in order of passing |

### isDebugEnabled() {#isDebugEnabled--}
```
public static boolean isDebugEnabled()
```


Checks is debug logging enabled

**Returns:**
boolean - true if enabled
### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


Warning message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The warning message, can contains \{\} to be replaced with arguments |
| arguments | java.lang.Object[] | The arguments, replaces \{\} in message in order of passing |

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
```


Warning message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| throwable | java.lang.Throwable | The exception message |
| message | java.lang.String | The warning message, can contains \{\} to be replaced with arguments |
| arguments | java.lang.Object[] | The arguments, replaces \{\} in message in order of passing |

### isWarningEnabled() {#isWarningEnabled--}
```
public static boolean isWarningEnabled()
```


Checks is warning logging enabled

**Returns:**
boolean - true if enabled
### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


Error message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The error message, can contains \{\} to be replaced with arguments |
| arguments | java.lang.Object[] | The arguments, replaces \{\} in message in order of passing |

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
```


Error message

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| throwable | java.lang.Throwable | The exception message |
| message | java.lang.String | The error message, can contains \{\} to be replaced with arguments |
| arguments | java.lang.Object[] | The arguments, replaces \{\} in message in order of passing |

### isErrorEnabled() {#isErrorEnabled--}
```
public static boolean isErrorEnabled()
```


Checks is error logging enabled

**Returns:**
boolean - true if enabled
### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


Sets the logger.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| logger | com.groupdocs.foundation.logging.ILogger | The input logger. |


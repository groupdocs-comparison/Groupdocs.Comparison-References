---
title: "ComparisonLogger"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Implementiert Protokollierungsmethoden und bietet eine Möglichkeit, einen integrierten oder benutzerdefinierten Logger zu konfigurieren."
type: docs
weight: 10
url: /de/java/com.groupdocs.comparison.logging/comparisonlogger/
---
**Inheritance:**
java.lang.Object
```
public class ComparisonLogger
```

Implementiert Protokollierungsmethoden und bietet eine Möglichkeit, einen integrierten oder benutzerdefinierten Logger zu konfigurieren.


Die Klasse ermöglicht das Einrichten eines integrierten oder benutzerdefinierten Loggers und das Schreiben von Log-Nachrichten.


Beispielverwendung:

````

 ComparisonLogger.setLogger(new com.groupdocs.comparison.logging.ConsoleLogger(false, true, true, true));
 ComparisonLogger.warning(exceptionObject, "Warning message with parameters: {}, {}", "parameter1", 2);
 
````


## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Schreibt Trace-Nachricht an den vorkonfigurierten Logger. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Schreibt Trace-Nachricht, Stacktrace und Nachricht einer Ausnahme an den vorkonfigurierten Logger. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | Überprüft, ob Trace-Logging im vorkonfigurierten Logger aktiviert ist. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Schreibt Debug-Nachricht an den vorkonfigurierten Logger. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Schreibt Debug-Nachricht, Stacktrace und Nachricht einer Ausnahme an den vorkonfigurierten Logger. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | Überprüft, ob Debug-Logging im vorkonfigurierten Logger aktiviert ist. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Schreibt Warnungsnachricht an den vorkonfigurierten Logger. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Schreibt Warnungsnachricht, Stacktrace und Nachricht einer Ausnahme an den vorkonfigurierten Logger. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | Überprüft, ob Warnungs-Logging im vorkonfigurierten Logger aktiviert ist. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Schreibt Fehlermeldung an den vorkonfigurierten Logger. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Schreibt Fehlermeldung, Stacktrace und Nachricht einer Ausnahme an den vorkonfigurierten Logger. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | Überprüft, ob Fehler-Logging im vorkonfigurierten Logger aktiviert ist. |
|
|  | [getLogger()](#getLogger--) | Liefert den vorkonfigurierten Logger, der zum Schreiben aller Log-Typen verwendet wird. |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Setzt den Logger, der zum Schreiben aller Log-Typen verwendet wird. |
|
### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


Schreibt Trace-Nachricht an den vorkonfigurierten Logger.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | message | java.lang.String | Die Nachricht, bei null hängt das Verhalten vom Logger ab |
|
|  | arguments | java.lang.Object[] | Die Argumente, die in die Nachricht eingebettet werden, bei null hängt das Verhalten vom Logger ab |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
```


Schreibt Trace-Nachricht, Stacktrace und Nachricht einer Ausnahme an den vorkonfigurierten Logger.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Das throwable-Objekt, das zum Abrufen des Stacktraces verwendet wird, bei null hängt das Verhalten vom Logger ab |
|
|  | message | java.lang.String | Die Nachricht, bei null hängt das Verhalten vom Logger ab |
|
|  | arguments | java.lang.Object[] | Die Argumente, die in die Nachricht eingebettet werden, bei null hängt das Verhalten vom Logger ab |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public static boolean isTraceEnabled()
```


Überprüft, ob Trace-Logging im vorkonfigurierten Logger aktiviert ist.


**Returns:**
boolean – true, wenn im vorkonfigurierten Logger aktiviert, sonst false

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


Schreibt Debug-Nachricht an den vorkonfigurierten Logger.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | message | java.lang.String | Die Nachricht, bei null hängt das Verhalten vom Logger ab |
|
|  | arguments | java.lang.Object[] | Die Argumente, die in die Nachricht eingebettet werden, bei null hängt das Verhalten vom Logger ab |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
```


Schreibt Debug-Nachricht, Stacktrace und Nachricht einer Ausnahme an den vorkonfigurierten Logger.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Das throwable-Objekt, das zum Abrufen des Stacktraces verwendet wird, bei null hängt das Verhalten vom Logger ab |
|
|  | message | java.lang.String | Die Nachricht, bei null hängt das Verhalten vom Logger ab |
|
|  | arguments | java.lang.Object[] | Die Argumente, die in die Nachricht eingebettet werden, bei null hängt das Verhalten vom Logger ab |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public static boolean isDebugEnabled()
```


Überprüft, ob Debug-Logging im vorkonfigurierten Logger aktiviert ist.


**Returns:**
boolean – true, wenn im vorkonfigurierten Logger aktiviert, sonst false

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


Schreibt Warnungsnachricht an den vorkonfigurierten Logger.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | message | java.lang.String | Die Nachricht, bei null hängt das Verhalten vom Logger ab |
|
|  | arguments | java.lang.Object[] | Die Argumente, die in die Nachricht eingebettet werden, bei null hängt das Verhalten vom Logger ab |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
```


Schreibt Warnungsnachricht, Stacktrace und Nachricht einer Ausnahme an den vorkonfigurierten Logger.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Das throwable-Objekt, das zum Abrufen des Stacktraces verwendet wird, bei null hängt das Verhalten vom Logger ab |
|
|  | message | java.lang.String | Die Nachricht, bei null hängt das Verhalten vom Logger ab |
|
|  | arguments | java.lang.Object[] | Die Argumente, die in die Nachricht eingebettet werden, bei null hängt das Verhalten vom Logger ab |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public static boolean isWarningEnabled()
```


Überprüft, ob Warnungs-Logging im vorkonfigurierten Logger aktiviert ist.


**Returns:**
boolean – true, wenn im vorkonfigurierten Logger aktiviert, sonst false

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


Schreibt Fehlermeldung an den vorkonfigurierten Logger.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | message | java.lang.String | Die Nachricht, bei null hängt das Verhalten vom Logger ab |
|
|  | arguments | java.lang.Object[] | Die Argumente, die in die Nachricht eingebettet werden, bei null hängt das Verhalten vom Logger ab |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
```


Schreibt Fehlermeldung, Stacktrace und Nachricht einer Ausnahme an den vorkonfigurierten Logger.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Das throwable-Objekt, das zum Abrufen des Stacktraces verwendet wird, bei null hängt das Verhalten vom Logger ab |
|
|  | message | java.lang.String | Die Nachricht, bei null hängt das Verhalten vom Logger ab |
|
|  | arguments | java.lang.Object[] | Die Argumente, die in die Nachricht eingebettet werden, bei null hängt das Verhalten vom Logger ab |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public static boolean isErrorEnabled()
```


Überprüft, ob Fehler-Logging im vorkonfigurierten Logger aktiviert ist.


**Returns:**
boolean – true, wenn im vorkonfigurierten Logger aktiviert, sonst false

### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


Liefert den vorkonfigurierten Logger, der zum Schreiben aller Log-Typen verwendet wird.


**Returns:**
com.groupdocs.foundation.logging.ILogger – der Logger

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


Setzt den Logger, der zum Schreiben aller Log-Typen verwendet wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Logger | com.groupdocs.foundation.logging.ILogger | Der Logger |
|


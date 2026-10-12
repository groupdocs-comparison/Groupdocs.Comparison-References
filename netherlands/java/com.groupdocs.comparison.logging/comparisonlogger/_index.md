---
title: "ComparisonLogger"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "Implementeert logmethoden en een manier om een geïntegreerde of door de gebruiker gedefinieerde logger te configureren."
type: docs
weight: 10
url: /nl/java/com.groupdocs.comparison.logging/comparisonlogger/
---
**Inheritance:**
java.lang.Object
```
public class ComparisonLogger
```

Implementeert logmethoden en een manier om een geïntegreerde of door de gebruiker gedefinieerde logger te configureren.


De klasse maakt het mogelijk een geïntegreerde of aangepaste logger in te stellen en logberichten te schrijven.


Voorbeeldgebruik:

````

 ComparisonLogger.setLogger(new com.groupdocs.comparison.logging.ConsoleLogger(false, true, true, true));
 ComparisonLogger.warning(exceptionObject, "Warning message with parameters: {}, {}", "parameter1", 2);
 
````


## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Schrijft trace-bericht naar pre-configured logger. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Schrijft trace-bericht, stacktrace en bericht van een uitzondering naar pre-configured logger. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | Controleert of trace-logging is ingeschakeld in pre-configured logger. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Schrijft debug-bericht naar pre-configured logger. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Schrijft debug-bericht, stacktrace en bericht van een uitzondering naar pre-configured logger. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | Controleert of debug-logging is ingeschakeld in pre-configured logger. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Schrijft waarschuwingsbericht naar pre-configured logger. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Schrijft waarschuwingsbericht, stacktrace en bericht van een uitzondering naar pre-configured logger. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | Controleert of waarschuwingslogging is ingeschakeld in pre-configured logger. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Schrijft foutbericht naar pre-configured logger. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Schrijft foutbericht, stacktrace en bericht van een uitzondering naar pre-configured logger. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | Controleert of foutlogging is ingeschakeld in pre-configured logger. |
|
|  | [getLogger()](#getLogger--) | Haalt pre-configured logger op die zal worden gebruikt om alle soorten logboeken te schrijven. |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Stelt de logger in die zal worden gebruikt om alle soorten logboeken te schrijven. |
|
### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


Schrijft trace-bericht naar pre-configured logger.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | message | java.lang.String | Het bericht, als null hangt het gedrag af van de logger. |
|
|  | arguments | java.lang.Object[] | De argumenten die in het bericht moeten worden ingebed, als null hangt het gedrag af van de logger. |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
```


Schrijft trace-bericht, stacktrace en bericht van een uitzondering naar pre-configured logger.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Het throwable-object dat wordt gebruikt om de stacktrace te verkrijgen, als null hangt het gedrag af van de logger. |
|
|  | message | java.lang.String | Het bericht, als null hangt het gedrag af van de logger. |
|
|  | arguments | java.lang.Object[] | De argumenten die in het bericht moeten worden ingebed, als null hangt het gedrag af van de logger. |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public static boolean isTraceEnabled()
```


Controleert of trace-logging is ingeschakeld in pre-configured logger.


**Returns:**
boolean - true als ingeschakeld in pre-configured logger, anders false

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


Schrijft debug-bericht naar pre-configured logger.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | message | java.lang.String | Het bericht, als null hangt het gedrag af van de logger. |
|
|  | arguments | java.lang.Object[] | De argumenten die in het bericht moeten worden ingebed, als null hangt het gedrag af van de logger. |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
```


Schrijft debug-bericht, stacktrace en bericht van een uitzondering naar pre-configured logger.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Het throwable-object dat wordt gebruikt om de stacktrace te verkrijgen, als null hangt het gedrag af van de logger. |
|
|  | message | java.lang.String | Het bericht, als null hangt het gedrag af van de logger. |
|
|  | arguments | java.lang.Object[] | De argumenten die in het bericht moeten worden ingebed, als null hangt het gedrag af van de logger. |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public static boolean isDebugEnabled()
```


Controleert of debug-logging is ingeschakeld in pre-configured logger.


**Returns:**
boolean - true als ingeschakeld in pre-configured logger, anders false

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


Schrijft waarschuwingsbericht naar pre-configured logger.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | message | java.lang.String | Het bericht, als null hangt het gedrag af van de logger. |
|
|  | arguments | java.lang.Object[] | De argumenten die in het bericht moeten worden ingebed, als null hangt het gedrag af van de logger. |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
```


Schrijft waarschuwingsbericht, stacktrace en bericht van een uitzondering naar pre-configured logger.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Het throwable-object dat wordt gebruikt om de stacktrace te verkrijgen, als null hangt het gedrag af van de logger. |
|
|  | message | java.lang.String | Het bericht, als null hangt het gedrag af van de logger. |
|
|  | arguments | java.lang.Object[] | De argumenten die in het bericht moeten worden ingebed, als null hangt het gedrag af van de logger. |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public static boolean isWarningEnabled()
```


Controleert of waarschuwingslogging is ingeschakeld in pre-configured logger.


**Returns:**
boolean - true als ingeschakeld in pre-configured logger, anders false

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


Schrijft foutbericht naar pre-configured logger.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | message | java.lang.String | Het bericht, als null hangt het gedrag af van de logger. |
|
|  | arguments | java.lang.Object[] | De argumenten die in het bericht moeten worden ingebed, als null hangt het gedrag af van de logger. |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
```


Schrijft foutbericht, stacktrace en bericht van een uitzondering naar pre-configured logger.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Het throwable-object dat wordt gebruikt om de stacktrace te verkrijgen, als null hangt het gedrag af van de logger. |
|
|  | message | java.lang.String | Het bericht, als null hangt het gedrag af van de logger. |
|
|  | arguments | java.lang.Object[] | De argumenten die in het bericht moeten worden ingebed, als null hangt het gedrag af van de logger. |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public static boolean isErrorEnabled()
```


Controleert of foutlogging is ingeschakeld in pre-configured logger.


**Returns:**
boolean - true als ingeschakeld in pre-configured logger, anders false

### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


Haalt pre-configured logger op die zal worden gebruikt om alle soorten logboeken te schrijven.


**Returns:**
com.groupdocs.foundation.logging.ILogger - de logger

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


Stelt de logger in die zal worden gebruikt om alle soorten logboeken te schrijven.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | De logger |
|


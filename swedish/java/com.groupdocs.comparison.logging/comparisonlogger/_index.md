---
title: "ComparisonLogger"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Implementerar loggningsmetoder och ett sätt att konfigurera integrerad eller ange en användardefinierad logger."
type: docs
weight: 10
url: /sv/java/com.groupdocs.comparison.logging/comparisonlogger/
---
**Inheritance:**
java.lang.Object
```
public class ComparisonLogger
```

Implementerar loggningsmetoder och ett sätt att konfigurera integrerad eller ange en användardefinierad logger.


Klassen tillåter att konfigurera en integrerad eller anpassad logger och skriva loggmeddelanden.


Exempel på användning:

````

 ComparisonLogger.setLogger(new com.groupdocs.comparison.logging.ConsoleLogger(false, true, true, true));
 ComparisonLogger.warning(exceptionObject, "Warning message with parameters: {}, {}", "parameter1", 2);
 
````


## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Skriver spårningsmeddelande till förkonfigurerad logger. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Skriver spårningsmeddelande, stackspårning och meddelande från ett undantag till förkonfigurerad logger. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | Kontrollerar om spårningsloggning är aktiverad i förkonfigurerad logger. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Skriver felsökningsmeddelande till förkonfigurerad logger. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Skriver felsökningsmeddelande, stackspårning och meddelande från ett undantag till förkonfigurerad logger. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | Kontrollerar om felsökningsloggning är aktiverad i förkonfigurerad logger. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Skriver varningsmeddelande till förkonfigurerad logger. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Skriver varningsmeddelande, stackspårning och meddelande från ett undantag till förkonfigurerad logger. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | Kontrollerar om varningsloggning är aktiverad i förkonfigurerad logger. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Skriver felmeddelande till förkonfigurerad logger. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Skriver felmeddelande, stackspårning och meddelande från ett undantag till förkonfigurerad logger. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | Kontrollerar om felloggning är aktiverad i förkonfigurerad logger. |
|
|  | [getLogger()](#getLogger--) | Hämtar förkonfigurerad logger som kommer att användas för att skriva alla typer av loggar. |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Ställer in loggern som kommer att användas för att skriva alla typer av loggar. |
|
### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


Skriver spårningsmeddelande till förkonfigurerad logger.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | message | java.lang.String | Meddelandet, om null beror beteendet på loggern |
|
|  | arguments | java.lang.Object[] | Argumenten som ska infogas i meddelandet, om null beror beteendet på loggern |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
```


Skriver spårningsmeddelande, stackspårning och meddelande från ett undantag till förkonfigurerad logger.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Det kastbara objektet som kommer att användas för att hämta stackspårning, om null beror beteendet på loggern |
|
|  | message | java.lang.String | Meddelandet, om null beror beteendet på loggern |
|
|  | arguments | java.lang.Object[] | Argumenten som ska infogas i meddelandet, om null beror beteendet på loggern |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public static boolean isTraceEnabled()
```


Kontrollerar om spårningsloggning är aktiverad i förkonfigurerad logger.


**Returns:**
boolean - true om aktiverad i förkonfigurerad logger, annars false

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


Skriver felsökningsmeddelande till förkonfigurerad logger.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | message | java.lang.String | Meddelandet, om null beror beteendet på loggern |
|
|  | arguments | java.lang.Object[] | Argumenten som ska infogas i meddelandet, om null beror beteendet på loggern |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
```


Skriver felsökningsmeddelande, stackspårning och meddelande från ett undantag till förkonfigurerad logger.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Det kastbara objektet som kommer att användas för att hämta stackspårning, om null beror beteendet på loggern |
|
|  | message | java.lang.String | Meddelandet, om null beror beteendet på loggern |
|
|  | arguments | java.lang.Object[] | Argumenten som ska infogas i meddelandet, om null beror beteendet på loggern |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public static boolean isDebugEnabled()
```


Kontrollerar om felsökningsloggning är aktiverad i förkonfigurerad logger.


**Returns:**
boolean - true om aktiverad i förkonfigurerad logger, annars false

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


Skriver varningsmeddelande till förkonfigurerad logger.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | message | java.lang.String | Meddelandet, om null beror beteendet på loggern |
|
|  | arguments | java.lang.Object[] | Argumenten som ska infogas i meddelandet, om null beror beteendet på loggern |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
```


Skriver varningsmeddelande, stackspårning och meddelande från ett undantag till förkonfigurerad logger.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Det kastbara objektet som kommer att användas för att hämta stackspårning, om null beror beteendet på loggern |
|
|  | message | java.lang.String | Meddelandet, om null beror beteendet på loggern |
|
|  | arguments | java.lang.Object[] | Argumenten som ska infogas i meddelandet, om null beror beteendet på loggern |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public static boolean isWarningEnabled()
```


Kontrollerar om varningsloggning är aktiverad i förkonfigurerad logger.


**Returns:**
boolean - true om aktiverad i förkonfigurerad logger, annars false

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


Skriver felmeddelande till förkonfigurerad logger.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | message | java.lang.String | Meddelandet, om null beror beteendet på loggern |
|
|  | arguments | java.lang.Object[] | Argumenten som ska infogas i meddelandet, om null beror beteendet på loggern |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
```


Skriver felmeddelande, stackspårning och meddelande från ett undantag till förkonfigurerad logger.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Det kastbara objektet som kommer att användas för att hämta stackspårning, om null beror beteendet på loggern |
|
|  | message | java.lang.String | Meddelandet, om null beror beteendet på loggern |
|
|  | arguments | java.lang.Object[] | Argumenten som ska infogas i meddelandet, om null beror beteendet på loggern |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public static boolean isErrorEnabled()
```


Kontrollerar om felloggning är aktiverad i förkonfigurerad logger.


**Returns:**
boolean - true om aktiverad i förkonfigurerad logger, annars false

### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


Hämtar förkonfigurerad logger som kommer att användas för att skriva alla typer av loggar.


**Returns:**
com.groupdocs.foundation.logging.ILogger - loggern

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


Ställer in loggern som kommer att användas för att skriva alla typer av loggar.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | Loggern |
|


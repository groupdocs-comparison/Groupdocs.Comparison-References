---
title: "ComparisonLogger"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "Implementa metodi di logging e un modo per configurare un logger integrato o impostare un logger definito dall'utente."
type: docs
weight: 10
url: /it/java/com.groupdocs.comparison.logging/comparisonlogger/
---
**Inheritance:**
java.lang.Object
```
public class ComparisonLogger
```

Implementa metodi di logging e un modo per configurare un logger integrato o impostare un logger definito dall'utente.


La classe consente di configurare un logger integrato o personalizzato e di scrivere messaggi di log.


Esempio di utilizzo:

````

 ComparisonLogger.setLogger(new com.groupdocs.comparison.logging.ConsoleLogger(false, true, true, true));
 ComparisonLogger.warning(exceptionObject, "Warning message with parameters: {}, {}", "parameter1", 2);
 
````


## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Scrive un messaggio di traccia al logger preconfigurato. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Scrive un messaggio di traccia, lo stacktrace e il messaggio di un'eccezione al logger preconfigurato. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | Verifica se il logging di traccia è abilitato nel logger preconfigurato. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Scrive un messaggio di debug al logger preconfigurato. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Scrive un messaggio di debug, lo stacktrace e il messaggio di un'eccezione al logger preconfigurato. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | Verifica se il logging di debug è abilitato nel logger preconfigurato. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Scrive un messaggio di avviso al logger preconfigurato. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Scrive un messaggio di avviso, lo stacktrace e il messaggio di un'eccezione al logger preconfigurato. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | Verifica se il logging di avviso è abilitato nel logger preconfigurato. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Scrive un messaggio di errore al logger preconfigurato. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Scrive un messaggio di errore, lo stacktrace e il messaggio di un'eccezione al logger preconfigurato. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | Verifica se il logging di errore è abilitato nel logger preconfigurato. |
|
|  | [getLogger()](#getLogger--) | Ottiene il logger preconfigurato che verrà utilizzato per scrivere tutti i tipi di log. |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Imposta il logger che verrà utilizzato per scrivere tutti i tipi di log. |
|
### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


Scrive un messaggio di traccia al logger preconfigurato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | message | java.lang.String | Il messaggio, se nullo, il comportamento dipende dal logger |
|
|  | arguments | java.lang.Object[] | Gli argomenti da incorporare nel messaggio, se nulli, il comportamento dipende dal logger |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
```


Scrive un messaggio di traccia, lo stacktrace e il messaggio di un'eccezione al logger preconfigurato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | L'oggetto throwable che verrà usato per ottenere lo stacktrace, se nullo, il comportamento dipende dal logger |
|
|  | message | java.lang.String | Il messaggio, se nullo, il comportamento dipende dal logger |
|
|  | arguments | java.lang.Object[] | Gli argomenti da incorporare nel messaggio, se nulli, il comportamento dipende dal logger |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public static boolean isTraceEnabled()
```


Verifica se il logging di traccia è abilitato nel logger preconfigurato.


**Returns:**
boolean - true se abilitato nel logger preconfigurato, altrimenti false

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


Scrive un messaggio di debug al logger preconfigurato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | message | java.lang.String | Il messaggio, se nullo, il comportamento dipende dal logger |
|
|  | arguments | java.lang.Object[] | Gli argomenti da incorporare nel messaggio, se nulli, il comportamento dipende dal logger |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
```


Scrive un messaggio di debug, lo stacktrace e il messaggio di un'eccezione al logger preconfigurato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | L'oggetto throwable che verrà usato per ottenere lo stacktrace, se nullo, il comportamento dipende dal logger |
|
|  | message | java.lang.String | Il messaggio, se nullo, il comportamento dipende dal logger |
|
|  | arguments | java.lang.Object[] | Gli argomenti da incorporare nel messaggio, se nulli, il comportamento dipende dal logger |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public static boolean isDebugEnabled()
```


Verifica se il logging di debug è abilitato nel logger preconfigurato.


**Returns:**
boolean - true se abilitato nel logger preconfigurato, altrimenti false

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


Scrive un messaggio di avviso al logger preconfigurato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | message | java.lang.String | Il messaggio, se nullo, il comportamento dipende dal logger |
|
|  | arguments | java.lang.Object[] | Gli argomenti da incorporare nel messaggio, se nulli, il comportamento dipende dal logger |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
```


Scrive un messaggio di avviso, lo stacktrace e il messaggio di un'eccezione al logger preconfigurato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | L'oggetto throwable che verrà usato per ottenere lo stacktrace, se nullo, il comportamento dipende dal logger |
|
|  | message | java.lang.String | Il messaggio, se nullo, il comportamento dipende dal logger |
|
|  | arguments | java.lang.Object[] | Gli argomenti da incorporare nel messaggio, se nulli, il comportamento dipende dal logger |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public static boolean isWarningEnabled()
```


Verifica se il logging di avviso è abilitato nel logger preconfigurato.


**Returns:**
boolean - true se abilitato nel logger preconfigurato, altrimenti false

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


Scrive un messaggio di errore al logger preconfigurato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | message | java.lang.String | Il messaggio, se nullo, il comportamento dipende dal logger |
|
|  | arguments | java.lang.Object[] | Gli argomenti da incorporare nel messaggio, se nulli, il comportamento dipende dal logger |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
```


Scrive un messaggio di errore, lo stacktrace e il messaggio di un'eccezione al logger preconfigurato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | L'oggetto throwable che verrà usato per ottenere lo stacktrace, se nullo, il comportamento dipende dal logger |
|
|  | message | java.lang.String | Il messaggio, se nullo, il comportamento dipende dal logger |
|
|  | arguments | java.lang.Object[] | Gli argomenti da incorporare nel messaggio, se nulli, il comportamento dipende dal logger |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public static boolean isErrorEnabled()
```


Verifica se il logging di errore è abilitato nel logger preconfigurato.


**Returns:**
boolean - true se abilitato nel logger preconfigurato, altrimenti false

### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


Ottiene il logger preconfigurato che verrà utilizzato per scrivere tutti i tipi di log.


**Returns:**
com.groupdocs.foundation.logging.ILogger - il logger

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


Imposta il logger che verrà utilizzato per scrivere tutti i tipi di log.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | Il logger |
|


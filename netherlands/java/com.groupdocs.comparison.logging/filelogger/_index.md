---
title: "FileLogger"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "Logger die logbestanden naar een bestand schrijft."
type: docs
weight: 11
url: /nl/java/com.groupdocs.comparison.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

Logger die logbestanden naar een bestand schrijft.


Moet samen worden gebruikt met [ComparisonLogger](../../com.groupdocs.comparison.logging/comparisonlogger).


Voorbeeldgebruik:

````

 ComparisonLogger.setLogger(new FileLogger("/path/to/file.log.txt", false, true, true, true));
 
````


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [FileLogger(String filePath)](#FileLogger-java.lang.String-) | Initialiseert een nieuw exemplaar van de FileLogger-klasse met bestandspad. |
|
|  | [FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | Initialiseert een nieuw exemplaar van de FileLogger-klasse met bestandspad en configuratie van logniveaus. |
|
## Velden

| Veld | Beschrijving |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Schrijft een trace-bericht naar het bestand. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Schrijft een trace-bericht naar het bestand. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | Controleert of trace-logging is ingeschakeld. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Schrijft een debug-bericht naar het bestand. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Schrijft een debug-bericht naar het bestand. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | Controleert of debug-logging is ingeschakeld. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Schrijft een waarschuwingsbericht naar het bestand. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Schrijft een waarschuwingsbericht naar het bestand. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | Controleert of waarschuwing-logging is ingeschakeld. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Schrijft een foutbericht naar het bestand. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Schrijft een foutbericht naar het bestand. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | Controleert of fout-logging is ingeschakeld. |
|
### FileLogger(String filePath) {#FileLogger-java.lang.String-}
```
public FileLogger(String filePath)
```


Initialiseert een nieuw exemplaar van de FileLogger-klasse met bestandspad.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het pad naar het bestand dat zal worden gebruikt om logs te schrijven |
|

### FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


Initialiseert een nieuw exemplaar van de FileLogger-klasse met bestandspad en configuratie van logniveaus.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het pad naar het bestand dat zal worden gebruikt om logs te schrijven |
|
|  | isTraceEnabled | boolean | True om trace-logging in te schakelen, false anders |
|
|  | isDebugEnabled | boolean | True om debug-logging in te schakelen, false anders |
|
|  | isWarningEnabled | boolean | True om waarschuwing-logging in te schakelen, false anders |
|
|  | isErrorEnabled | boolean | True om fout-logging in te schakelen, false anders |
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


Schrijft een trace-bericht naar het bestand.


Trace-logberichten bieden maximaal gedetailleerde informatie over de applicatiestroom.
Het bericht kan één of enkele {} bevatten die worden vervangen door de overeenkomstige argumenten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | message | java.lang.String | Het bericht. |
|
|  | arguments | java.lang.Object[] | De argumenten vervangen {} in het bericht in de volgorde van doorgeven; null wordt geschreven als 'null' |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


Schrijft een trace-bericht naar het bestand.


Trace-logberichten bieden maximaal gedetailleerde informatie over de applicatiestroom.
Het bericht kan één of enkele {} bevatten die worden vervangen door de overeenkomstige argumenten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Het throwable-object dat zal worden gebruikt om de stacktrace op te halen |
|
|  | message | java.lang.String | Het bericht. |
|
|  | arguments | java.lang.Object[] | De argumenten vervangen {} in het bericht in de volgorde van doorgeven; null wordt geschreven als 'null' |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


Controleert of trace-logging is ingeschakeld.


**Returns:**
boolean - true als ingeschakeld, anders false

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


Schrijft een debug-bericht naar het bestand.


Debug-logberichten bieden informatie over verschillende processen in de applicatiestroom.
Het bericht kan één of enkele {} bevatten die worden vervangen door de overeenkomstige argumenten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | message | java.lang.String | Het bericht. |
|
|  | arguments | java.lang.Object[] | De argumenten vervangen {} in het bericht in de volgorde van doorgeven; null wordt geschreven als 'null' |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


Schrijft een debug-bericht naar het bestand.


Debug-logberichten bieden informatie over verschillende processen in de applicatiestroom.
Het bericht kan één of enkele {} bevatten die worden vervangen door de overeenkomstige argumenten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Het throwable-object dat zal worden gebruikt om de stacktrace op te halen |
|
|  | message | java.lang.String | Het bericht. |
|
|  | arguments | java.lang.Object[] | De argumenten vervangen {} in het bericht in de volgorde van doorgeven; null wordt geschreven als 'null' |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


Controleert of debug-logging is ingeschakeld.


**Returns:**
boolean - true als ingeschakeld, anders false

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


Schrijft een waarschuwingsbericht naar het bestand.


Waarschuwing-logberichten bieden informatie over onverwachte en herstelbare gebeurtenissen in de applicatiestroom.
Het bericht kan één of enkele {} bevatten die worden vervangen door de overeenkomstige argumenten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | message | java.lang.String | Het bericht. |
|
|  | arguments | java.lang.Object[] | De argumenten vervangen {} in het bericht in de volgorde van doorgeven; null wordt geschreven als 'null' |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


Schrijft een waarschuwingsbericht naar het bestand.


Waarschuwing-logberichten bieden informatie over onverwachte en herstelbare gebeurtenissen in de applicatiestroom.
Het bericht kan één of enkele {} bevatten die worden vervangen door de overeenkomstige argumenten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Het throwable-object dat zal worden gebruikt om de stacktrace op te halen |
|
|  | message | java.lang.String | Het bericht. |
|
|  | arguments | java.lang.Object[] | De argumenten vervangen {} in het bericht in de volgorde van doorgeven; null wordt geschreven als 'null' |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


Controleert of waarschuwing-logging is ingeschakeld.


**Returns:**
boolean - true als ingeschakeld, anders false

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


Schrijft een foutbericht naar het bestand.


Fout-logberichten bieden informatie over onherstelbare gebeurtenissen in de applicatiestroom.
Het bericht kan één of enkele {} bevatten die worden vervangen door de overeenkomstige argumenten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | message | java.lang.String | Het bericht. |
|
|  | arguments | java.lang.Object[] | De argumenten vervangen {} in het bericht in de volgorde van doorgeven; null wordt geschreven als 'null' |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


Schrijft een foutbericht naar het bestand.


Fout-logberichten bieden informatie over onherstelbare gebeurtenissen in de applicatiestroom.
Het bericht kan één of enkele {} bevatten die worden vervangen door de overeenkomstige argumenten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Het throwable-object dat zal worden gebruikt om de stacktrace op te halen |
|
|  | message | java.lang.String | Het bericht. |
|
|  | arguments | java.lang.Object[] | De argumenten vervangen {} in het bericht in de volgorde van doorgeven; null wordt geschreven als 'null' |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


Controleert of fout-logging is ingeschakeld.


**Returns:**
boolean - true als ingeschakeld, anders false


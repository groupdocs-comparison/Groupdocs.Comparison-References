---
title: "FileLogger"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Logger, der Protokolle in eine Datei schreibt."
type: docs
weight: 11
url: /de/java/com.groupdocs.comparison.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

Logger, der Protokolle in eine Datei schreibt.


Sollte zusammen mit [ComparisonLogger](../../com.groupdocs.comparison.logging/comparisonlogger) verwendet werden.


Beispielverwendung:

````

 ComparisonLogger.setLogger(new FileLogger("/path/to/file.log.txt", false, true, true, true));
 
````


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [FileLogger(String filePath)](#FileLogger-java.lang.String-) | Initialisiert eine neue Instanz der FileLogger-Klasse mit Dateipfad. |
|
|  | [FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | Initialisiert eine neue Instanz der FileLogger-Klasse mit Dateipfad und Konfiguration der Protokollstufen. |
|
## Felder

| Feld | Beschreibung |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Schreibt eine Trace-Nachricht in die Datei. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Schreibt eine Trace-Nachricht in die Datei. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | Prüft, ob Trace-Logging aktiviert ist. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Schreibt eine Debug-Nachricht in die Datei. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Schreibt eine Debug-Nachricht in die Datei. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | Prüft, ob Debug-Logging aktiviert ist. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Schreibt eine Warnungsnachricht in die Datei. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Schreibt eine Warnungsnachricht in die Datei. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | Prüft, ob Warnungs-Logging aktiviert ist. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Schreibt eine Fehlermeldung in die Datei. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Schreibt eine Fehlermeldung in die Datei. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | Prüft, ob Fehler-Logging aktiviert ist. |
|
### FileLogger(String filePath) {#FileLogger-java.lang.String-}
```
public FileLogger(String filePath)
```


Initialisiert eine neue Instanz der FileLogger-Klasse mit Dateipfad.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Pfad zur Datei, die zum Schreiben von Protokollen verwendet wird |
|

### FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


Initialisiert eine neue Instanz der FileLogger-Klasse mit Dateipfad und Konfiguration der Protokollstufen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Pfad zur Datei, die zum Schreiben von Protokollen verwendet wird |
|
|  | isTraceEnabled | boolean | True, um die Trace-Protokollierung zu aktivieren, sonst false |
|
|  | isDebugEnabled | boolean | True, um die Debug-Protokollierung zu aktivieren, sonst false |
|
|  | isWarningEnabled | boolean | True, um die Warnungsprotokollierung zu aktivieren, sonst false |
|
|  | isErrorEnabled | boolean | True, um die Fehlerprotokollierung zu aktivieren, sonst false |
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


Schreibt eine Trace-Nachricht in die Datei.


Trace-Protokollnachrichten liefern maximal detaillierte Informationen über den Anwendungsablauf.
Die Nachricht kann ein oder mehrere {} enthalten, die durch die entsprechenden Argumente ersetzt werden.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | message | java.lang.String | Die Nachricht. |
|
|  | arguments | java.lang.Object[] | Die Argumente ersetzen {} in der Nachricht in der Reihenfolge der Übergabe, null wird als 'null' geschrieben |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


Schreibt eine Trace-Nachricht in die Datei.


Trace-Protokollnachrichten liefern maximal detaillierte Informationen über den Anwendungsablauf.
Die Nachricht kann ein oder mehrere {} enthalten, die durch die entsprechenden Argumente ersetzt werden.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Das Throwable-Objekt, das zum Abrufen des Stacktraces verwendet wird |
|
|  | message | java.lang.String | Die Nachricht. |
|
|  | arguments | java.lang.Object[] | Die Argumente ersetzen {} in der Nachricht in der Reihenfolge der Übergabe, null wird als 'null' geschrieben |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


Prüft, ob Trace-Logging aktiviert ist.


**Returns:**
boolean - true, wenn aktiviert, sonst false

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


Schreibt eine Debug-Nachricht in die Datei.


Debug-Protokollnachrichten liefern Informationen über verschiedene Prozesse im Anwendungsablauf.
Die Nachricht kann ein oder mehrere {} enthalten, die durch die entsprechenden Argumente ersetzt werden.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | message | java.lang.String | Die Nachricht. |
|
|  | arguments | java.lang.Object[] | Die Argumente ersetzen {} in der Nachricht in der Reihenfolge der Übergabe, null wird als 'null' geschrieben |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


Schreibt eine Debug-Nachricht in die Datei.


Debug-Protokollnachrichten liefern Informationen über verschiedene Prozesse im Anwendungsablauf.
Die Nachricht kann ein oder mehrere {} enthalten, die durch die entsprechenden Argumente ersetzt werden.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Das Throwable-Objekt, das zum Abrufen des Stacktraces verwendet wird |
|
|  | message | java.lang.String | Die Nachricht. |
|
|  | arguments | java.lang.Object[] | Die Argumente ersetzen {} in der Nachricht in der Reihenfolge der Übergabe, null wird als 'null' geschrieben |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


Prüft, ob Debug-Logging aktiviert ist.


**Returns:**
boolean - true, wenn aktiviert, sonst false

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


Schreibt eine Warnungsnachricht in die Datei.


Warnungsprotokollnachrichten liefern Informationen über unerwartete und wiederherstellbare Ereignisse im Anwendungsablauf.
Die Nachricht kann ein oder mehrere {} enthalten, die durch die entsprechenden Argumente ersetzt werden.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | message | java.lang.String | Die Nachricht. |
|
|  | arguments | java.lang.Object[] | Die Argumente ersetzen {} in der Nachricht in der Reihenfolge der Übergabe, null wird als 'null' geschrieben |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


Schreibt eine Warnungsnachricht in die Datei.


Warnungsprotokollnachrichten liefern Informationen über unerwartete und wiederherstellbare Ereignisse im Anwendungsablauf.
Die Nachricht kann ein oder mehrere {} enthalten, die durch die entsprechenden Argumente ersetzt werden.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Das Throwable-Objekt, das zum Abrufen des Stacktraces verwendet wird |
|
|  | message | java.lang.String | Die Nachricht. |
|
|  | arguments | java.lang.Object[] | Die Argumente ersetzen {} in der Nachricht in der Reihenfolge der Übergabe, null wird als 'null' geschrieben |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


Prüft, ob Warnungs-Logging aktiviert ist.


**Returns:**
boolean - true, wenn aktiviert, sonst false

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


Schreibt eine Fehlermeldung in die Datei.


Fehlerprotokollnachrichten liefern Informationen über nicht wiederherstellbare Ereignisse im Anwendungsablauf.
Die Nachricht kann ein oder mehrere {} enthalten, die durch die entsprechenden Argumente ersetzt werden.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | message | java.lang.String | Die Nachricht. |
|
|  | arguments | java.lang.Object[] | Die Argumente ersetzen {} in der Nachricht in der Reihenfolge der Übergabe, null wird als 'null' geschrieben |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


Schreibt eine Fehlermeldung in die Datei.


Fehlerprotokollnachrichten liefern Informationen über nicht wiederherstellbare Ereignisse im Anwendungsablauf.
Die Nachricht kann ein oder mehrere {} enthalten, die durch die entsprechenden Argumente ersetzt werden.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Das Throwable-Objekt, das zum Abrufen des Stacktraces verwendet wird |
|
|  | message | java.lang.String | Die Nachricht. |
|
|  | arguments | java.lang.Object[] | Die Argumente ersetzen {} in der Nachricht in der Reihenfolge der Übergabe, null wird als 'null' geschrieben |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


Prüft, ob Fehler-Logging aktiviert ist.


**Returns:**
boolean - true, wenn aktiviert, sonst false


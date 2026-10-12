---
title: "FileLogger"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Logger som skriver loggar till fil."
type: docs
weight: 11
url: /sv/java/com.groupdocs.comparison.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

Logger som skriver loggar till fil.


Ska användas tillsammans med [ComparisonLogger](../../com.groupdocs.comparison.logging/comparisonlogger).


Exempel på användning:

````

 ComparisonLogger.setLogger(new FileLogger("/path/to/file.log.txt", false, true, true, true));
 
````


## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [FileLogger(String filePath)](#FileLogger-java.lang.String-) | Initierar en ny instans av FileLogger-klassen med filväg. |
|
|  | [FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | Initierar en ny instans av FileLogger-klassen med filväg och konfiguration av loggnivåer. |
|
## Fält

| Fält | Beskrivning |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Skriver ett spårmeddelande till filen. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Skriver ett spårmeddelande till filen. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | Kontrollerar om spårloggning är aktiverad. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Skriver ett felsökningsmeddelande till filen. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Skriver ett felsökningsmeddelande till filen. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | Kontrollerar om felsökningsloggning är aktiverad. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Skriver ett varningsmeddelande till filen. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Skriver ett varningsmeddelande till filen. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | Kontrollerar om varningsloggning är aktiverad. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Skriver ett felmeddelande till filen. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Skriver ett felmeddelande till filen. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | Kontrollerar om felloggning är aktiverad. |
|
### FileLogger(String filePath) {#FileLogger-java.lang.String-}
```
public FileLogger(String filePath)
```


Initierar en ny instans av FileLogger-klassen med filväg.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Sökvägen till filen som kommer att användas för att skriva loggar |
|

### FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


Initierar en ny instans av FileLogger-klassen med filväg och konfiguration av loggnivåer.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Sökvägen till filen som kommer att användas för att skriva loggar |
|
|  | isTraceEnabled | boolean | Sant för att aktivera spårloggning, falskt annars |
|
|  | isDebugEnabled | boolean | Sant för att aktivera debugloggning, falskt annars |
|
|  | isWarningEnabled | boolean | Sant för att aktivera varningsloggning, falskt annars |
|
|  | isErrorEnabled | boolean | Sant för att aktivera felloggning, falskt annars |
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


Skriver ett spårmeddelande till filen.


Spårloggmeddelanden ger maximal detaljerad information om applikationsflödet.
Meddelandet kan innehålla en eller några {} som kommer att ersättas av motsvarande argument.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | message | java.lang.String | Meddelandet. |
|
|  | arguments | java.lang.Object[] | Argumenten ersätter {} i meddelandet i den ordning de skickas, null kommer att skrivas som 'null' |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


Skriver ett spårmeddelande till filen.


Spårloggmeddelanden ger maximal detaljerad information om applikationsflödet.
Meddelandet kan innehålla en eller några {} som kommer att ersättas av motsvarande argument.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Det throwable-objektet som kommer att användas för att hämta stacktrace |
|
|  | message | java.lang.String | Meddelandet. |
|
|  | arguments | java.lang.Object[] | Argumenten ersätter {} i meddelandet i den ordning de skickas, null kommer att skrivas som 'null' |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


Kontrollerar om spårloggning är aktiverad.


**Returns:**
boolean - sant om aktiverad, annars falskt

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


Skriver ett felsökningsmeddelande till filen.


Debugloggmeddelanden ger information om olika processer i applikationsflödet.
Meddelandet kan innehålla en eller några {} som kommer att ersättas av motsvarande argument.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | message | java.lang.String | Meddelandet. |
|
|  | arguments | java.lang.Object[] | Argumenten ersätter {} i meddelandet i den ordning de skickas, null kommer att skrivas som 'null' |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


Skriver ett felsökningsmeddelande till filen.


Debugloggmeddelanden ger information om olika processer i applikationsflödet.
Meddelandet kan innehålla en eller några {} som kommer att ersättas av motsvarande argument.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Det throwable-objektet som kommer att användas för att hämta stacktrace |
|
|  | message | java.lang.String | Meddelandet. |
|
|  | arguments | java.lang.Object[] | Argumenten ersätter {} i meddelandet i den ordning de skickas, null kommer att skrivas som 'null' |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


Kontrollerar om felsökningsloggning är aktiverad.


**Returns:**
boolean - sant om aktiverad, annars falskt

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


Skriver ett varningsmeddelande till filen.


Varningsloggmeddelanden ger information om oväntade och återhämtningsbara händelser i applikationsflödet.
Meddelandet kan innehålla en eller några {} som kommer att ersättas av motsvarande argument.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | message | java.lang.String | Meddelandet. |
|
|  | arguments | java.lang.Object[] | Argumenten ersätter {} i meddelandet i den ordning de skickas, null kommer att skrivas som 'null' |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


Skriver ett varningsmeddelande till filen.


Varningsloggmeddelanden ger information om oväntade och återhämtningsbara händelser i applikationsflödet.
Meddelandet kan innehålla en eller några {} som kommer att ersättas av motsvarande argument.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Det throwable-objektet som kommer att användas för att hämta stacktrace |
|
|  | message | java.lang.String | Meddelandet. |
|
|  | arguments | java.lang.Object[] | Argumenten ersätter {} i meddelandet i den ordning de skickas, null kommer att skrivas som 'null' |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


Kontrollerar om varningsloggning är aktiverad.


**Returns:**
boolean - sant om aktiverad, annars falskt

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


Skriver ett felmeddelande till filen.


Felloggmeddelanden ger information om oåterhämtningsbara händelser i applikationsflödet.
Meddelandet kan innehålla en eller några {} som kommer att ersättas av motsvarande argument.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | message | java.lang.String | Meddelandet. |
|
|  | arguments | java.lang.Object[] | Argumenten ersätter {} i meddelandet i den ordning de skickas, null kommer att skrivas som 'null' |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


Skriver ett felmeddelande till filen.


Felloggmeddelanden ger information om oåterhämtningsbara händelser i applikationsflödet.
Meddelandet kan innehålla en eller några {} som kommer att ersättas av motsvarande argument.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Det throwable-objektet som kommer att användas för att hämta stacktrace |
|
|  | message | java.lang.String | Meddelandet. |
|
|  | arguments | java.lang.Object[] | Argumenten ersätter {} i meddelandet i den ordning de skickas, null kommer att skrivas som 'null' |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


Kontrollerar om felloggning är aktiverad.


**Returns:**
boolean - sant om aktiverad, annars falskt


---
title: "FileLogger"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "Logger che scrive i log su file."
type: docs
weight: 11
url: /it/java/com.groupdocs.comparison.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

Logger che scrive i log su file.


Deve essere usato insieme a [ComparisonLogger](../../com.groupdocs.comparison.logging/comparisonlogger).


Esempio di utilizzo:

````

 ComparisonLogger.setLogger(new FileLogger("/path/to/file.log.txt", false, true, true, true));
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [FileLogger(String filePath)](#FileLogger-java.lang.String-) | Inizializza una nuova istanza della classe FileLogger con il percorso del file. |
|
|  | [FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | Inizializza una nuova istanza della classe FileLogger con il percorso del file e la configurazione dei livelli di log. |
|
## Campi

| Campo | Descrizione |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Scrive un messaggio di traccia nel file. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Scrive un messaggio di traccia nel file. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | Verifica se il logging di traccia è abilitato. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Scrive un messaggio di debug nel file. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Scrive un messaggio di debug nel file. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | Verifica se il logging di debug è abilitato. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Scrive un messaggio di avviso nel file. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Scrive un messaggio di avviso nel file. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | Verifica se il logging di avviso è abilitato. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Scrive un messaggio di errore nel file. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Scrive un messaggio di errore nel file. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | Verifica se il logging di errore è abilitato. |
|
### FileLogger(String filePath) {#FileLogger-java.lang.String-}
```
public FileLogger(String filePath)
```


Inizializza una nuova istanza della classe FileLogger con il percorso del file.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso del file che verrà usato per scrivere i log |
|

### FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


Inizializza una nuova istanza della classe FileLogger con il percorso del file e la configurazione dei livelli di log.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso del file che verrà usato per scrivere i log |
|
|  | isTraceEnabled | boolean | True per abilitare la registrazione di trace, false altrimenti |
|
|  | isDebugEnabled | boolean | True per abilitare la registrazione di debug, false altrimenti |
|
|  | isWarningEnabled | boolean | True per abilitare la registrazione di avviso, false altrimenti |
|
|  | isErrorEnabled | boolean | True per abilitare la registrazione di errore, false altrimenti |
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


Scrive un messaggio di traccia nel file.


I messaggi di log di trace forniscono informazioni dettagliate al massimo sul flusso dell'applicazione.
Il messaggio può contenere uno o pochi {} che saranno sostituiti dagli argomenti corrispondenti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | message | java.lang.String | Il messaggio. |
|
|  | arguments | java.lang.Object[] | Gli argomenti, sostituiscono {} nel messaggio nell'ordine di passaggio; null verrà scritto come 'null' |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


Scrive un messaggio di traccia nel file.


I messaggi di log di trace forniscono informazioni dettagliate al massimo sul flusso dell'applicazione.
Il messaggio può contenere uno o pochi {} che saranno sostituiti dagli argomenti corrispondenti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | L'oggetto throwable che verrà usato per ottenere lo stacktrace |
|
|  | message | java.lang.String | Il messaggio. |
|
|  | arguments | java.lang.Object[] | Gli argomenti, sostituiscono {} nel messaggio nell'ordine di passaggio; null verrà scritto come 'null' |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


Verifica se il logging di traccia è abilitato.


**Returns:**
boolean - true se abilitato, altrimenti false

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


Scrive un messaggio di debug nel file.


I messaggi di log di debug forniscono informazioni sui diversi processi nel flusso dell'applicazione.
Il messaggio può contenere uno o pochi {} che saranno sostituiti dagli argomenti corrispondenti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | message | java.lang.String | Il messaggio. |
|
|  | arguments | java.lang.Object[] | Gli argomenti, sostituiscono {} nel messaggio nell'ordine di passaggio; null verrà scritto come 'null' |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


Scrive un messaggio di debug nel file.


I messaggi di log di debug forniscono informazioni sui diversi processi nel flusso dell'applicazione.
Il messaggio può contenere uno o pochi {} che saranno sostituiti dagli argomenti corrispondenti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | L'oggetto throwable che verrà usato per ottenere lo stacktrace |
|
|  | message | java.lang.String | Il messaggio. |
|
|  | arguments | java.lang.Object[] | Gli argomenti, sostituiscono {} nel messaggio nell'ordine di passaggio; null verrà scritto come 'null' |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


Verifica se il logging di debug è abilitato.


**Returns:**
boolean - true se abilitato, altrimenti false

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


Scrive un messaggio di avviso nel file.


I messaggi di log di avviso forniscono informazioni su eventi inaspettati e recuperabili nel flusso dell'applicazione.
Il messaggio può contenere uno o pochi {} che saranno sostituiti dagli argomenti corrispondenti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | message | java.lang.String | Il messaggio. |
|
|  | arguments | java.lang.Object[] | Gli argomenti, sostituiscono {} nel messaggio nell'ordine di passaggio; null verrà scritto come 'null' |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


Scrive un messaggio di avviso nel file.


I messaggi di log di avviso forniscono informazioni su eventi inaspettati e recuperabili nel flusso dell'applicazione.
Il messaggio può contenere uno o pochi {} che saranno sostituiti dagli argomenti corrispondenti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | L'oggetto throwable che verrà usato per ottenere lo stacktrace |
|
|  | message | java.lang.String | Il messaggio. |
|
|  | arguments | java.lang.Object[] | Gli argomenti, sostituiscono {} nel messaggio nell'ordine di passaggio; null verrà scritto come 'null' |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


Verifica se il logging di avviso è abilitato.


**Returns:**
boolean - true se abilitato, altrimenti false

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


Scrive un messaggio di errore nel file.


I messaggi di log di errore forniscono informazioni su eventi non recuperabili nel flusso dell'applicazione.
Il messaggio può contenere uno o pochi {} che saranno sostituiti dagli argomenti corrispondenti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | message | java.lang.String | Il messaggio. |
|
|  | arguments | java.lang.Object[] | Gli argomenti, sostituiscono {} nel messaggio nell'ordine di passaggio; null verrà scritto come 'null' |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


Scrive un messaggio di errore nel file.


I messaggi di log di errore forniscono informazioni su eventi non recuperabili nel flusso dell'applicazione.
Il messaggio può contenere uno o pochi {} che saranno sostituiti dagli argomenti corrispondenti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | L'oggetto throwable che verrà usato per ottenere lo stacktrace |
|
|  | message | java.lang.String | Il messaggio. |
|
|  | arguments | java.lang.Object[] | Gli argomenti, sostituiscono {} nel messaggio nell'ordine di passaggio; null verrà scritto come 'null' |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


Verifica se il logging di errore è abilitato.


**Returns:**
boolean - true se abilitato, altrimenti false


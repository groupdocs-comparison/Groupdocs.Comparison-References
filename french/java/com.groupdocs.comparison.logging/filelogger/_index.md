---
title: "FileLogger"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "Logger qui écrit les journaux dans un fichier."
type: docs
weight: 11
url: /fr/java/com.groupdocs.comparison.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

Logger qui écrit les journaux dans un fichier.


Doit être utilisé avec [ComparisonLogger](../../com.groupdocs.comparison.logging/comparisonlogger).


Exemple d'utilisation :

````

 ComparisonLogger.setLogger(new FileLogger("/path/to/file.log.txt", false, true, true, true));
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [FileLogger(String filePath)](#FileLogger-java.lang.String-) | Initialise une nouvelle instance de la classe FileLogger avec le chemin du fichier. |
|
|  | [FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | Initialise une nouvelle instance de la classe FileLogger avec le chemin du fichier et la configuration des niveaux de journalisation. |
|
## Champs

| Champ | Description |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Écrit un message de trace dans le fichier. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Écrit un message de trace dans le fichier. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | Vérifie si la journalisation de trace est activée. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Écrit un message de débogage dans le fichier. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Écrit un message de débogage dans le fichier. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | Vérifie si la journalisation de débogage est activée. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Écrit un message d'avertissement dans le fichier. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Écrit un message d'avertissement dans le fichier. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | Vérifie si la journalisation d'avertissement est activée. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Écrit un message d'erreur dans le fichier. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Écrit un message d'erreur dans le fichier. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | Vérifie si la journalisation d'erreur est activée. |
|
### FileLogger(String filePath) {#FileLogger-java.lang.String-}
```
public FileLogger(String filePath)
```


Initialise une nouvelle instance de la classe FileLogger avec le chemin du fichier.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier qui sera utilisé pour écrire les journaux |
|

### FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


Initialise une nouvelle instance de la classe FileLogger avec le chemin du fichier et la configuration des niveaux de journalisation.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier qui sera utilisé pour écrire les journaux |
|
|  | isTraceEnabled | boolean | True pour activer la journalisation de trace, false sinon |
|
|  | isDebugEnabled | boolean | True pour activer la journalisation de débogage, false sinon |
|
|  | isWarningEnabled | boolean | True pour activer la journalisation d'avertissement, false sinon |
|
|  | isErrorEnabled | boolean | True pour activer la journalisation d'erreur, false sinon |
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


Écrit un message de trace dans le fichier.


Les messages de journal de trace fournissent le maximum d'informations détaillées sur le flux de l'application.
Le message peut contenir un ou plusieurs {} qui seront remplacés par les arguments correspondants.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | message | java.lang.String | Le message. |
|
|  | arguments | java.lang.Object[] | Les arguments, remplacent {} dans le message dans l'ordre de passage, null sera écrit comme 'null' |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


Écrit un message de trace dans le fichier.


Les messages de journal de trace fournissent le maximum d'informations détaillées sur le flux de l'application.
Le message peut contenir un ou plusieurs {} qui seront remplacés par les arguments correspondants.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | L'objet throwable qui sera utilisé pour obtenir la trace de pile |
|
|  | message | java.lang.String | Le message. |
|
|  | arguments | java.lang.Object[] | Les arguments, remplacent {} dans le message dans l'ordre de passage, null sera écrit comme 'null' |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


Vérifie si la journalisation de trace est activée.


**Returns:**
boolean - true si activé, sinon false

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


Écrit un message de débogage dans le fichier.


Les messages de journal de débogage fournissent des informations sur différents processus dans le flux de l'application.
Le message peut contenir un ou plusieurs {} qui seront remplacés par les arguments correspondants.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | message | java.lang.String | Le message. |
|
|  | arguments | java.lang.Object[] | Les arguments, remplacent {} dans le message dans l'ordre de passage, null sera écrit comme 'null' |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


Écrit un message de débogage dans le fichier.


Les messages de journal de débogage fournissent des informations sur différents processus dans le flux de l'application.
Le message peut contenir un ou plusieurs {} qui seront remplacés par les arguments correspondants.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | L'objet throwable qui sera utilisé pour obtenir la trace de pile |
|
|  | message | java.lang.String | Le message. |
|
|  | arguments | java.lang.Object[] | Les arguments, remplacent {} dans le message dans l'ordre de passage, null sera écrit comme 'null' |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


Vérifie si la journalisation de débogage est activée.


**Returns:**
boolean - true si activé, sinon false

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


Écrit un message d'avertissement dans le fichier.


Les messages de journal d'avertissement fournissent des informations sur les événements inattendus et récupérables dans le flux de l'application.
Le message peut contenir un ou plusieurs {} qui seront remplacés par les arguments correspondants.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | message | java.lang.String | Le message. |
|
|  | arguments | java.lang.Object[] | Les arguments, remplacent {} dans le message dans l'ordre de passage, null sera écrit comme 'null' |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


Écrit un message d'avertissement dans le fichier.


Les messages de journal d'avertissement fournissent des informations sur les événements inattendus et récupérables dans le flux de l'application.
Le message peut contenir un ou plusieurs {} qui seront remplacés par les arguments correspondants.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | L'objet throwable qui sera utilisé pour obtenir la trace de pile |
|
|  | message | java.lang.String | Le message. |
|
|  | arguments | java.lang.Object[] | Les arguments, remplacent {} dans le message dans l'ordre de passage, null sera écrit comme 'null' |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


Vérifie si la journalisation d'avertissement est activée.


**Returns:**
boolean - true si activé, sinon false

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


Écrit un message d'erreur dans le fichier.


Les messages de journal d'erreur fournissent des informations sur les événements irrécupérables dans le flux de l'application.
Le message peut contenir un ou plusieurs {} qui seront remplacés par les arguments correspondants.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | message | java.lang.String | Le message. |
|
|  | arguments | java.lang.Object[] | Les arguments, remplacent {} dans le message dans l'ordre de passage, null sera écrit comme 'null' |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


Écrit un message d'erreur dans le fichier.


Les messages de journal d'erreur fournissent des informations sur les événements irrécupérables dans le flux de l'application.
Le message peut contenir un ou plusieurs {} qui seront remplacés par les arguments correspondants.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | L'objet throwable qui sera utilisé pour obtenir la trace de pile |
|
|  | message | java.lang.String | Le message. |
|
|  | arguments | java.lang.Object[] | Les arguments, remplacent {} dans le message dans l'ordre de passage, null sera écrit comme 'null' |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


Vérifie si la journalisation d'erreur est activée.


**Returns:**
boolean - true si activé, sinon false


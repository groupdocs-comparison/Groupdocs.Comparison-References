---
title: "ComparisonLogger"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "Implémente les méthodes de journalisation et un moyen de configurer un logger intégré ou défini par l'utilisateur."
type: docs
weight: 10
url: /fr/java/com.groupdocs.comparison.logging/comparisonlogger/
---
**Inheritance:**
java.lang.Object
```
public class ComparisonLogger
```

Implémente les méthodes de journalisation et un moyen de configurer un logger intégré ou défini par l'utilisateur.


La classe permet de configurer un journaliseur intégré ou personnalisé et d'écrire des messages de journal.


Exemple d'utilisation :

````

 ComparisonLogger.setLogger(new com.groupdocs.comparison.logging.ConsoleLogger(false, true, true, true));
 ComparisonLogger.warning(exceptionObject, "Warning message with parameters: {}, {}", "parameter1", 2);
 
````


## Méthodes

| Méthode | Description |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Écrit un message de trace dans le journaliseur préconfiguré. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Écrit un message de trace, la pile d'appels et le message d'une exception dans le journaliseur préconfiguré. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | Vérifie si la journalisation de trace est activée dans le journaliseur préconfiguré. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Écrit un message de débogage dans le journaliseur préconfiguré. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Écrit un message de débogage, la pile d'appels et le message d'une exception dans le journaliseur préconfiguré. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | Vérifie si la journalisation de débogage est activée dans le journaliseur préconfiguré. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Écrit un message d'avertissement dans le journaliseur préconfiguré. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Écrit un message d'avertissement, la pile d'appels et le message d'une exception dans le journaliseur préconfiguré. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | Vérifie si la journalisation d'avertissement est activée dans le journaliseur préconfiguré. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Écrit un message d'erreur dans le journaliseur préconfiguré. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Écrit un message d'erreur, la pile d'appels et le message d'une exception dans le journaliseur préconfiguré. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | Vérifie si la journalisation d'erreur est activée dans le journaliseur préconfiguré. |
|
|  | [getLogger()](#getLogger--) | Obtient le journaliseur préconfiguré qui sera utilisé pour écrire tous les types de journaux. |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Définit le journaliseur qui sera utilisé pour écrire tous les types de journaux. |
|
### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


Écrit un message de trace dans le journaliseur préconfiguré.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | message | java.lang.String | Le message, si nul, le comportement dépend du journaliseur |
|
|  | arguments | java.lang.Object[] | Les arguments à intégrer dans le message, si nul, le comportement dépend du journaliseur |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
```


Écrit un message de trace, la pile d'appels et le message d'une exception dans le journaliseur préconfiguré.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | L'objet throwable qui sera utilisé pour obtenir la pile d'appels, si nul, le comportement dépend du journaliseur |
|
|  | message | java.lang.String | Le message, si nul, le comportement dépend du journaliseur |
|
|  | arguments | java.lang.Object[] | Les arguments à intégrer dans le message, si nul, le comportement dépend du journaliseur |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public static boolean isTraceEnabled()
```


Vérifie si la journalisation de trace est activée dans le journaliseur préconfiguré.


**Returns:**
booléen - vrai si activé dans le journaliseur préconfiguré, sinon faux

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


Écrit un message de débogage dans le journaliseur préconfiguré.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | message | java.lang.String | Le message, si nul, le comportement dépend du journaliseur |
|
|  | arguments | java.lang.Object[] | Les arguments à intégrer dans le message, si nul, le comportement dépend du journaliseur |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
```


Écrit un message de débogage, la pile d'appels et le message d'une exception dans le journaliseur préconfiguré.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | L'objet throwable qui sera utilisé pour obtenir la pile d'appels, si nul, le comportement dépend du journaliseur |
|
|  | message | java.lang.String | Le message, si nul, le comportement dépend du journaliseur |
|
|  | arguments | java.lang.Object[] | Les arguments à intégrer dans le message, si nul, le comportement dépend du journaliseur |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public static boolean isDebugEnabled()
```


Vérifie si la journalisation de débogage est activée dans le journaliseur préconfiguré.


**Returns:**
booléen - vrai si activé dans le journaliseur préconfiguré, sinon faux

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


Écrit un message d'avertissement dans le journaliseur préconfiguré.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | message | java.lang.String | Le message, si nul, le comportement dépend du journaliseur |
|
|  | arguments | java.lang.Object[] | Les arguments à intégrer dans le message, si nul, le comportement dépend du journaliseur |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
```


Écrit un message d'avertissement, la pile d'appels et le message d'une exception dans le journaliseur préconfiguré.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | L'objet throwable qui sera utilisé pour obtenir la pile d'appels, si nul, le comportement dépend du journaliseur |
|
|  | message | java.lang.String | Le message, si nul, le comportement dépend du journaliseur |
|
|  | arguments | java.lang.Object[] | Les arguments à intégrer dans le message, si nul, le comportement dépend du journaliseur |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public static boolean isWarningEnabled()
```


Vérifie si la journalisation d'avertissement est activée dans le journaliseur préconfiguré.


**Returns:**
booléen - vrai si activé dans le journaliseur préconfiguré, sinon faux

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


Écrit un message d'erreur dans le journaliseur préconfiguré.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | message | java.lang.String | Le message, si nul, le comportement dépend du journaliseur |
|
|  | arguments | java.lang.Object[] | Les arguments à intégrer dans le message, si nul, le comportement dépend du journaliseur |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
```


Écrit un message d'erreur, la pile d'appels et le message d'une exception dans le journaliseur préconfiguré.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | L'objet throwable qui sera utilisé pour obtenir la pile d'appels, si nul, le comportement dépend du journaliseur |
|
|  | message | java.lang.String | Le message, si nul, le comportement dépend du journaliseur |
|
|  | arguments | java.lang.Object[] | Les arguments à intégrer dans le message, si nul, le comportement dépend du journaliseur |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public static boolean isErrorEnabled()
```


Vérifie si la journalisation d'erreur est activée dans le journaliseur préconfiguré.


**Returns:**
booléen - vrai si activé dans le journaliseur préconfiguré, sinon faux

### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


Obtient le journaliseur préconfiguré qui sera utilisé pour écrire tous les types de journaux.


**Returns:**
com.groupdocs.foundation.logging.ILogger - le journaliseur

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


Définit le journaliseur qui sera utilisé pour écrire tous les types de journaux.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | journaliseur | com.groupdocs.foundation.logging.ILogger | Le journaliseur |
|


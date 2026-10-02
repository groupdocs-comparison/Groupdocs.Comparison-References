---
title: "ComparerSettings"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Definiert Einstellungen zur Anpassung des Verhaltens der Klasse."
type: docs
weight: 11
url: /de/java/com.groupdocs.comparison/comparersettings/
---
**Inheritance:**
java.lang.Object
```
public class ComparerSettings
```

Definiert Einstellungen zur Anpassung des Verhaltens der [Comparer](../../com.groupdocs.comparison/comparer)-Klasse.


Beispielverwendung:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final ComparerSettings comparerSettings = new ComparerSettings();
     comparerSettings.setLogger(new ConsoleLogger(false, false, true, true));

     comparer.compare(resultFile, comparerSettings);
 }
 
````


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [ComparerSettings()](#ComparerSettings--) | Instanziiert eine neue Instanz der ComparerSettings-Klasse. |
|
|  | [ComparerSettings(ILogger logger)](#ComparerSettings-com.groupdocs.foundation.logging.ILogger-) | Instanziiert eine neue Instanz der ComparerSettings-Klasse. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getLogger()](#getLogger--) | Ruft die Logger-Implementierung ab, die für das Protokollieren verwendet wird. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Setzt die Logger-Implementierung für das Protokollieren. |
|
### ComparerSettings() {#ComparerSettings--}
```
public ComparerSettings()
```


Instanziiert eine neue Instanz der ComparerSettings-Klasse.


### ComparerSettings(ILogger logger) {#ComparerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ComparerSettings(ILogger logger)
```


Instanziiert eine neue Instanz der ComparerSettings-Klasse.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Logger | com.groupdocs.foundation.logging.ILogger | zu verwendender Logger |
|

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Ruft die Logger-Implementierung ab, die für das Protokollieren verwendet wird.


**Returns:**
com.groupdocs.foundation.logging.ILogger – der Logger

### setLogger(ILogger value) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


Setzt die Logger-Implementierung für das Protokollieren.


Verwenden Sie com.groupdocs.foundation.logging.NullLogger#NULL_LOGGER.NULL_LOGGER, um das Protokollieren zu deaktivieren.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | com.groupdocs.foundation.logging.ILogger | die zu setzende Logger-Implementierung |
|


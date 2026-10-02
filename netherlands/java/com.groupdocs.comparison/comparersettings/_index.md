---
title: "ComparerSettings"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "Definieert instellingen voor het aanpassen van het gedrag van de klasse."
type: docs
weight: 11
url: /nl/java/com.groupdocs.comparison/comparersettings/
---
**Inheritance:**
java.lang.Object
```
public class ComparerSettings
```

Definieert instellingen voor het aanpassen van het gedrag van de [Comparer](../../com.groupdocs.comparison/comparer) klasse.


Voorbeeldgebruik:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final ComparerSettings comparerSettings = new ComparerSettings();
     comparerSettings.setLogger(new ConsoleLogger(false, false, true, true));

     comparer.compare(resultFile, comparerSettings);
 }
 
````


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [ComparerSettings()](#ComparerSettings--) | Instantieert een nieuw exemplaar van de ComparerSettings-klasse. |
|
|  | [ComparerSettings(ILogger logger)](#ComparerSettings-com.groupdocs.foundation.logging.ILogger-) | Instantieert een nieuw exemplaar van de ComparerSettings-klasse. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getLogger()](#getLogger--) | Haalt de logger-implementatie op die wordt gebruikt voor logging. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Stelt de logger-implementatie in voor logging. |
|
### ComparerSettings() {#ComparerSettings--}
```
public ComparerSettings()
```


Instantieert een nieuw exemplaar van de ComparerSettings-klasse.


### ComparerSettings(ILogger logger) {#ComparerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ComparerSettings(ILogger logger)
```


Instantieert een nieuw exemplaar van de ComparerSettings-klasse.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | logger die gebruikt moet worden |
|

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Haalt de logger-implementatie op die wordt gebruikt voor logging.


**Returns:**
com.groupdocs.foundation.logging.ILogger - de logger

### setLogger(ILogger value) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


Stelt de logger-implementatie in voor logging.


Gebruik com.groupdocs.foundation.logging.NullLogger#NULL_LOGGER.NULL_LOGGER om logging uit te schakelen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | com.groupdocs.foundation.logging.ILogger | de logger-implementatie om in te stellen |
|


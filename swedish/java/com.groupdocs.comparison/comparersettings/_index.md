---
title: "ComparerSettings"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Definierar inställningar för att anpassa beteendet hos klassen."
type: docs
weight: 11
url: /sv/java/com.groupdocs.comparison/comparersettings/
---
**Inheritance:**
java.lang.Object
```
public class ComparerSettings
```

Definierar inställningar för att anpassa beteendet hos klassen [Comparer](../../com.groupdocs.comparison/comparer).


Exempel på användning:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final ComparerSettings comparerSettings = new ComparerSettings();
     comparerSettings.setLogger(new ConsoleLogger(false, false, true, true));

     comparer.compare(resultFile, comparerSettings);
 }
 
````


## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [ComparerSettings()](#ComparerSettings--) | Skapar en ny instans av klassen ComparerSettings. |
|
|  | [ComparerSettings(ILogger logger)](#ComparerSettings-com.groupdocs.foundation.logging.ILogger-) | Skapar en ny instans av klassen ComparerSettings. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getLogger()](#getLogger--) | Hämtar logger-implementationen som används för loggning. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Ställer in logger-implementationen för loggning. |
|
### ComparerSettings() {#ComparerSettings--}
```
public ComparerSettings()
```


Skapar en ny instans av klassen ComparerSettings.


### ComparerSettings(ILogger logger) {#ComparerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ComparerSettings(ILogger logger)
```


Skapar en ny instans av klassen ComparerSettings.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | logger att använda |
|

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Hämtar logger-implementationen som används för loggning.


**Returns:**
com.groupdocs.foundation.logging.ILogger - loggern

### setLogger(ILogger value) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


Ställer in logger-implementationen för loggning.


Använd com.groupdocs.foundation.logging.NullLogger#NULL_LOGGER.NULL_LOGGER för att inaktivera loggning.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | com.groupdocs.foundation.logging.ILogger | logger-implementationen att ställa in |
|


---
title: "ComparerSettings"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "Definisce le impostazioni per personalizzare il comportamento della classe."
type: docs
weight: 11
url: /it/java/com.groupdocs.comparison/comparersettings/
---
**Inheritance:**
java.lang.Object
```
public class ComparerSettings
```

Definisce le impostazioni per personalizzare il comportamento della classe [Comparer](../../com.groupdocs.comparison/comparer).


Esempio di utilizzo:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final ComparerSettings comparerSettings = new ComparerSettings();
     comparerSettings.setLogger(new ConsoleLogger(false, false, true, true));

     comparer.compare(resultFile, comparerSettings);
 }
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [ComparerSettings()](#ComparerSettings--) | Crea una nuova istanza della classe ComparerSettings. |
|
|  | [ComparerSettings(ILogger logger)](#ComparerSettings-com.groupdocs.foundation.logging.ILogger-) | Crea una nuova istanza della classe ComparerSettings. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getLogger()](#getLogger--) | Ottiene l'implementazione del logger utilizzata per la registrazione. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Imposta l'implementazione del logger per la registrazione. |
|
### ComparerSettings() {#ComparerSettings--}
```
public ComparerSettings()
```


Crea una nuova istanza della classe ComparerSettings.


### ComparerSettings(ILogger logger) {#ComparerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ComparerSettings(ILogger logger)
```


Crea una nuova istanza della classe ComparerSettings.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | logger da utilizzare |
|

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Ottiene l'implementazione del logger utilizzata per la registrazione.


**Returns:**
com.groupdocs.foundation.logging.ILogger - il logger

### setLogger(ILogger value) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


Imposta l'implementazione del logger per la registrazione.


Usa com.groupdocs.foundation.logging.NullLogger#NULL_LOGGER.NULL_LOGGER per disabilitare la registrazione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | com.groupdocs.foundation.logging.ILogger | l'implementazione del logger da impostare |
|


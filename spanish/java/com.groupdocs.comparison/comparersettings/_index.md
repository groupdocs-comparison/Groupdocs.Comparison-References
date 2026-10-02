---
title: "ComparerSettings"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "Define la configuración para personalizar el comportamiento de la clase."
type: docs
weight: 11
url: /es/java/com.groupdocs.comparison/comparersettings/
---
**Inheritance:**
java.lang.Object
```
public class ComparerSettings
```

Define la configuración para personalizar el comportamiento de la clase [Comparer](../../com.groupdocs.comparison/comparer).


Ejemplo de uso:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final ComparerSettings comparerSettings = new ComparerSettings();
     comparerSettings.setLogger(new ConsoleLogger(false, false, true, true));

     comparer.compare(resultFile, comparerSettings);
 }
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [ComparerSettings()](#ComparerSettings--) | Crea una nueva instancia de la clase ComparerSettings. |
|
|  | [ComparerSettings(ILogger logger)](#ComparerSettings-com.groupdocs.foundation.logging.ILogger-) | Crea una nueva instancia de la clase ComparerSettings. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getLogger()](#getLogger--) | Obtiene la implementación del registrador utilizada para el registro. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Establece la implementación del registrador para el registro. |
|
### ComparerSettings() {#ComparerSettings--}
```
public ComparerSettings()
```


Crea una nueva instancia de la clase ComparerSettings.


### ComparerSettings(ILogger logger) {#ComparerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ComparerSettings(ILogger logger)
```


Crea una nueva instancia de la clase ComparerSettings.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | registrador a utilizar |
|

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Obtiene la implementación del registrador utilizada para el registro.


**Returns:**
com.groupdocs.foundation.logging.ILogger - el logger

### setLogger(ILogger value) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


Establece la implementación del registrador para el registro.


Utilice com.groupdocs.foundation.logging.NullLogger#NULL_LOGGER.NULL_LOGGER para desactivar el registro.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | com.groupdocs.foundation.logging.ILogger | la implementación del registrador a establecer |
|


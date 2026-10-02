---
title: "ComparerSettings"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "Définit les paramètres pour personnaliser le comportement de la classe."
type: docs
weight: 11
url: /fr/java/com.groupdocs.comparison/comparersettings/
---
**Inheritance:**
java.lang.Object
```
public class ComparerSettings
```

Définit les paramètres pour personnaliser le comportement de la classe [Comparer](../../com.groupdocs.comparison/comparer).


Exemple d'utilisation :

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final ComparerSettings comparerSettings = new ComparerSettings();
     comparerSettings.setLogger(new ConsoleLogger(false, false, true, true));

     comparer.compare(resultFile, comparerSettings);
 }
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [ComparerSettings()](#ComparerSettings--) | Instancie une nouvelle instance de la classe ComparerSettings. |
|
|  | [ComparerSettings(ILogger logger)](#ComparerSettings-com.groupdocs.foundation.logging.ILogger-) | Instancie une nouvelle instance de la classe ComparerSettings. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getLogger()](#getLogger--) | Obtient l’implémentation du logger utilisée pour la journalisation. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Définit l’implémentation du logger pour la journalisation. |
|
### ComparerSettings() {#ComparerSettings--}
```
public ComparerSettings()
```


Instancie une nouvelle instance de la classe ComparerSettings.


### ComparerSettings(ILogger logger) {#ComparerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ComparerSettings(ILogger logger)
```


Instancie une nouvelle instance de la classe ComparerSettings.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | journaliseur | com.groupdocs.foundation.logging.ILogger | logger à utiliser |
|

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Obtient l’implémentation du logger utilisée pour la journalisation.


**Returns:**
com.groupdocs.foundation.logging.ILogger - le journaliseur

### setLogger(ILogger value) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


Définit l’implémentation du logger pour la journalisation.


Utilisez com.groupdocs.foundation.logging.NullLogger#NULL_LOGGER.NULL_LOGGER pour désactiver la journalisation.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | com.groupdocs.foundation.logging.ILogger | l’implémentation du logger à définir |
|


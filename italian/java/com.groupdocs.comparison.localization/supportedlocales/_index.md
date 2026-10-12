---
title: "SupportedLocales"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "La classe SupportedLocales fornisce costanti che rappresentano le localizzazioni supportate per GroupDocs.Comparison."
type: docs
weight: 10
url: /it/java/com.groupdocs.comparison.localization/supportedlocales/
---
**Inheritance:**
java.lang.Object
```
public class SupportedLocales
```

La classe SupportedLocales fornisce costanti che rappresentano le localizzazioni supportate per GroupDocs.Comparison.


Consente di specificare la locale per operazioni specifiche della lingua, come la formattazione e la visualizzazione dei messaggi.


Per ulteriori informazioni sui locale, fare riferimento alla documentazione Java Locale:
[Java Locale](../https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Locale.html)


Esempio di utilizzo:

````

 final boolean localeSupported = SupportedLocales.isLocaleSupported(Locale.CANADA);
 
````


## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isLocaleSupported(String localeString)](#isLocaleSupported-java.lang.String-) | Determina se la locale è supportata o meno. |
|
|  | [isLocaleSupported(Locale locale)](#isLocaleSupported-java.util.Locale-) | Determina se la locale è supportata o meno. |
|
|  | [isLocaleSupported(CultureInfo culture)](#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-) | Determina se la locale, rappresentata come CultureInfo, è supportata o meno. |
|
### isLocaleSupported(String localeString) {#isLocaleSupported-java.lang.String-}
```
public static boolean isLocaleSupported(String localeString)
```


Determina se la locale è supportata o meno.
Il formato di localeString è xx-YY o xx_YY, esempi: en-US, en_US


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | localeString | java.lang.String | La locale da verificare, può essere null |
|

**Returns:**
boolean - true se supportata, altrimenti false

### isLocaleSupported(Locale locale) {#isLocaleSupported-java.util.Locale-}
```
public static boolean isLocaleSupported(Locale locale)
```


Determina se la locale è supportata o meno.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | locale | java.util.Locale | La locale da verificare, non null |
|

**Returns:**
boolean - true se supportata, altrimenti false

### isLocaleSupported(CultureInfo culture) {#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-}
```
public static boolean isLocaleSupported(CultureInfo culture)
```


Determina se la locale, rappresentata come CultureInfo, è supportata o meno.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | culture | com.groupdocs.foundation.utils.CultureInfo | La cultura da verificare, non null |
|

**Returns:**
boolean - true se supportata, altrimenti false


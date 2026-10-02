---
title: "SupportedLocales"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "La classe SupportedLocales fournit des constantes représentant les paramètres régionaux pris en charge pour GroupDocs.Comparison."
type: docs
weight: 10
url: /fr/java/com.groupdocs.comparison.localization/supportedlocales/
---
**Inheritance:**
java.lang.Object
```
public class SupportedLocales
```

La classe SupportedLocales fournit des constantes représentant les paramètres régionaux pris en charge pour GroupDocs.Comparison.


Il vous permet de spécifier la locale pour les opérations spécifiques à la langue, telles que le formatage et l'affichage des messages.


Pour plus d'informations sur les locales, consultez la documentation Java Locale :
[Java Locale](../https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Locale.html)


Exemple d'utilisation :

````

 final boolean localeSupported = SupportedLocales.isLocaleSupported(Locale.CANADA);
 
````


## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isLocaleSupported(String localeString)](#isLocaleSupported-java.lang.String-) | Détermine si la locale est prise en charge ou non. |
|
|  | [isLocaleSupported(Locale locale)](#isLocaleSupported-java.util.Locale-) | Détermine si la locale est prise en charge ou non. |
|
|  | [isLocaleSupported(CultureInfo culture)](#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-) | Détermine si la locale, représentée en tant que CultureInfo, est prise en charge ou non. |
|
### isLocaleSupported(String localeString) {#isLocaleSupported-java.lang.String-}
```
public static boolean isLocaleSupported(String localeString)
```


Détermine si la locale est prise en charge ou non.
Le format de localeString est xx-YY ou xx_YY, exemples : en-US, en_US


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | localeString | java.lang.String | La locale à vérifier, peut être nulle |
|

**Returns:**
booléen - true si prise en charge, sinon false

### isLocaleSupported(Locale locale) {#isLocaleSupported-java.util.Locale-}
```
public static boolean isLocaleSupported(Locale locale)
```


Détermine si la locale est prise en charge ou non.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | locale | java.util.Locale | La locale à vérifier, non nulle |
|

**Returns:**
booléen - true si prise en charge, sinon false

### isLocaleSupported(CultureInfo culture) {#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-}
```
public static boolean isLocaleSupported(CultureInfo culture)
```


Détermine si la locale, représentée en tant que CultureInfo, est prise en charge ou non.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | culture | com.groupdocs.foundation.utils.CultureInfo | La culture à vérifier, non nulle |
|

**Returns:**
booléen - true si prise en charge, sinon false


---
title: "SupportedLocales"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "De klasse SupportedLocales biedt constanten die de ondersteunde locales voor GroupDocs.Comparison vertegenwoordigen."
type: docs
weight: 10
url: /nl/java/com.groupdocs.comparison.localization/supportedlocales/
---
**Inheritance:**
java.lang.Object
```
public class SupportedLocales
```

De klasse SupportedLocales biedt constanten die de ondersteunde locales voor GroupDocs.Comparison vertegenwoordigen.


Het stelt u in staat om de locale op te geven voor taalspecifieke bewerkingen, zoals opmaak en het weergeven van berichten.


Voor meer informatie over locales, raadpleeg de Java Locale-documentatie:
[Java Locale](../https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Locale.html)


Voorbeeldgebruik:

````

 final boolean localeSupported = SupportedLocales.isLocaleSupported(Locale.CANADA);
 
````


## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isLocaleSupported(String localeString)](#isLocaleSupported-java.lang.String-) | Bepaalt of de locale wordt ondersteund of niet. |
|
|  | [isLocaleSupported(Locale locale)](#isLocaleSupported-java.util.Locale-) | Bepaalt of de locale wordt ondersteund of niet. |
|
|  | [isLocaleSupported(CultureInfo culture)](#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-) | Bepaalt of de locale, weergegeven als CultureInfo, wordt ondersteund of niet. |
|
### isLocaleSupported(String localeString) {#isLocaleSupported-java.lang.String-}
```
public static boolean isLocaleSupported(String localeString)
```


Bepaalt of de locale wordt ondersteund of niet.
Het formaat van localeString is xx-YY of xx_YY, voorbeelden: en-US, en_US


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | localeString | java.lang.String | De locale die moet worden gecontroleerd, mag null zijn |
|

**Returns:**
boolean - true als ondersteund, anders false

### isLocaleSupported(Locale locale) {#isLocaleSupported-java.util.Locale-}
```
public static boolean isLocaleSupported(Locale locale)
```


Bepaalt of de locale wordt ondersteund of niet.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | locale | java.util.Locale | De locale die moet worden gecontroleerd, niet null |
|

**Returns:**
boolean - true als ondersteund, anders false

### isLocaleSupported(CultureInfo culture) {#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-}
```
public static boolean isLocaleSupported(CultureInfo culture)
```


Bepaalt of de locale, weergegeven als CultureInfo, wordt ondersteund of niet.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | culture | com.groupdocs.foundation.utils.CultureInfo | De culture die moet worden gecontroleerd, niet null |
|

**Returns:**
boolean - true als ondersteund, anders false


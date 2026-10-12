---
title: "SupportedLocales"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Die Klasse SupportedLocales stellt Konstanten bereit, die die unterstützten Locale für GroupDocs.Comparison repräsentieren."
type: docs
weight: 10
url: /de/java/com.groupdocs.comparison.localization/supportedlocales/
---
**Inheritance:**
java.lang.Object
```
public class SupportedLocales
```

Die Klasse SupportedLocales stellt Konstanten bereit, die die unterstützten Locale für GroupDocs.Comparison repräsentieren.


Sie ermöglicht es Ihnen, das Gebietsschema für sprachspezifische Vorgänge anzugeben, wie z. B. das Formatieren und Anzeigen von Meldungen.


Weitere Informationen zu Gebietsschemas finden Sie in der Java Locale-Dokumentation:
[Java Locale](../https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Locale.html)


Beispielverwendung:

````

 final boolean localeSupported = SupportedLocales.isLocaleSupported(Locale.CANADA);
 
````


## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isLocaleSupported(String localeString)](#isLocaleSupported-java.lang.String-) | Bestimmt, ob das Gebietsschema unterstützt wird oder nicht. |
|
|  | [isLocaleSupported(Locale locale)](#isLocaleSupported-java.util.Locale-) | Bestimmt, ob das Gebietsschema unterstützt wird oder nicht. |
|
|  | [isLocaleSupported(CultureInfo culture)](#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-) | Bestimmt, ob das als CultureInfo dargestellte Gebietsschema unterstützt wird oder nicht. |
|
### isLocaleSupported(String localeString) {#isLocaleSupported-java.lang.String-}
```
public static boolean isLocaleSupported(String localeString)
```


Bestimmt, ob das Gebietsschema unterstützt wird oder nicht.
Das Format von localeString ist xx-YY oder xx_YY, Beispiele: en-US, en_US


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | localeString | java.lang.String | Das zu prüfende Gebietsschema, kann null sein |
|

**Returns:**
boolean - true, wenn unterstützt, sonst false

### isLocaleSupported(Locale locale) {#isLocaleSupported-java.util.Locale-}
```
public static boolean isLocaleSupported(Locale locale)
```


Bestimmt, ob das Gebietsschema unterstützt wird oder nicht.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | locale | java.util.Locale | Das zu prüfende Gebietsschema, nicht null |
|

**Returns:**
boolean - true, wenn unterstützt, sonst false

### isLocaleSupported(CultureInfo culture) {#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-}
```
public static boolean isLocaleSupported(CultureInfo culture)
```


Bestimmt, ob das als CultureInfo dargestellte Gebietsschema unterstützt wird oder nicht.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | culture | com.groupdocs.foundation.utils.CultureInfo | Die zu prüfende Kultur, nicht null |
|

**Returns:**
boolean - true, wenn unterstützt, sonst false


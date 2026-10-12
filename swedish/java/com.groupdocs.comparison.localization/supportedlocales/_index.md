---
title: "SupportedLocales"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Klassen SupportedLocales tillhandahåller konstanter som representerar de stödjade lokalerna för GroupDocs.Comparison."
type: docs
weight: 10
url: /sv/java/com.groupdocs.comparison.localization/supportedlocales/
---
**Inheritance:**
java.lang.Object
```
public class SupportedLocales
```

Klassen SupportedLocales tillhandahåller konstanter som representerar de stödjade lokalerna för GroupDocs.Comparison.


Den gör det möjligt att ange språkinställningen för språk‑specifika operationer, såsom formatering och visning av meddelanden.


För mer information om språkinställningar, se Java Locale-dokumentationen:
[Java Locale](../https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Locale.html)


Exempel på användning:

````

 final boolean localeSupported = SupportedLocales.isLocaleSupported(Locale.CANADA);
 
````


## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isLocaleSupported(String localeString)](#isLocaleSupported-java.lang.String-) | Bestämmer om språkinställningen stöds eller inte. |
|
|  | [isLocaleSupported(Locale locale)](#isLocaleSupported-java.util.Locale-) | Bestämmer om språkinställningen stöds eller inte. |
|
|  | [isLocaleSupported(CultureInfo culture)](#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-) | Bestämmer om språkinställningen, representerad som CultureInfo, stöds eller inte. |
|
### isLocaleSupported(String localeString) {#isLocaleSupported-java.lang.String-}
```
public static boolean isLocaleSupported(String localeString)
```


Bestämmer om språkinställningen stöds eller inte.
Formatet för localeString är  xx-YY  eller  xx_YY , exempel:  en-US ,  en_US


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | localeString | java.lang.String | Språkinställningen som ska kontrolleras, kan vara null |
|

**Returns:**
boolean - true om stöds, annars false

### isLocaleSupported(Locale locale) {#isLocaleSupported-java.util.Locale-}
```
public static boolean isLocaleSupported(Locale locale)
```


Bestämmer om språkinställningen stöds eller inte.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | locale | java.util.Locale | Språkinställningen som ska kontrolleras, får inte vara null |
|

**Returns:**
boolean - true om stöds, annars false

### isLocaleSupported(CultureInfo culture) {#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-}
```
public static boolean isLocaleSupported(CultureInfo culture)
```


Bestämmer om språkinställningen, representerad som CultureInfo, stöds eller inte.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | culture | com.groupdocs.foundation.utils.CultureInfo | Kulturen som ska kontrolleras, får inte vara null |
|

**Returns:**
boolean - true om stöds, annars false


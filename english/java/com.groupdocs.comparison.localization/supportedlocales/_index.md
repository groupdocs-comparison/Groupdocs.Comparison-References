---
title: SupportedLocales
second_title: GroupDocs.Comparison for Java API Reference
description: Class that provides methods for checking supported locales of GroupDocs.Comparison
type: docs
weight: 10
url: /java/com.groupdocs.comparison.localization/supportedlocales/
---
**Inheritance:**
java.lang.Object
```
public class SupportedLocales
```

Class that provides methods for checking supported locales of GroupDocs.Comparison
## Constructors

| Constructor | Description |
| --- | --- |
| [SupportedLocales()](#SupportedLocales--) |  |
## Methods

| Method | Description |
| --- | --- |
| [isLocaleSupported(String cultureString)](#isLocaleSupported-java.lang.String-) | Determines whether [is locale supported] [the specified culture]. |
| [isLocaleSupported(Locale locale)](#isLocaleSupported-java.util.Locale-) | Determines whether [is locale supported]. |
| [isLocaleSupported(CultureInfo culture)](#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-) | Determines whether [is locale supported] [the specified culture]. |
### SupportedLocales() {#SupportedLocales--}
```
public SupportedLocales()
```


### isLocaleSupported(String cultureString) {#isLocaleSupported-java.lang.String-}
```
public static boolean isLocaleSupported(String cultureString)
```


Determines whether [is locale supported] [the specified culture].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cultureString | java.lang.String | The culture. |

**Returns:**
boolean - true if supported
### isLocaleSupported(Locale locale) {#isLocaleSupported-java.util.Locale-}
```
public static boolean isLocaleSupported(Locale locale)
```


Determines whether [is locale supported].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| locale | java.util.Locale | The locale. |

**Returns:**
boolean - true if supported
### isLocaleSupported(CultureInfo culture) {#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-}
```
public static boolean isLocaleSupported(CultureInfo culture)
```


Determines whether [is locale supported] [the specified culture].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| culture | com.groupdocs.foundation.utils.CultureInfo | The culture. |

**Returns:**
boolean - true if supported

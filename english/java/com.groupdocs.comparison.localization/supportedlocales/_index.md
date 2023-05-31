---
title: SupportedLocales
second_title: GroupDocs.Comparison for Java API Reference
description: The SupportedLocales class provides constants representing the supported locales for GroupDocs.Comparison.
type: docs
weight: 10
url: /java/com.groupdocs.comparison.localization/supportedlocales/
---
**Inheritance:**
java.lang.Object
```
public class SupportedLocales
```

The SupportedLocales class provides constants representing the supported locales for GroupDocs.Comparison.

It allows you to specify the locale for language-specific operations, such as formatting and displaying messages.

For more information about locales, refer to the Java Locale documentation: [Java Locale][]

Example usage:

```

 final boolean localeSupported = SupportedLocales.isLocaleSupported(Locale.CANADA);
 
```


[Java Locale]: https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Locale.html
## Methods

| Method | Description |
| --- | --- |
| [isLocaleSupported(String localeString)](#isLocaleSupported-java.lang.String-) | Determines whether locale supported or not. |
| [isLocaleSupported(Locale locale)](#isLocaleSupported-java.util.Locale-) | Determines whether locale supported or not. |
| [isLocaleSupported(CultureInfo culture)](#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-) | Determines whether locale, represented as CultureInfo, supported or not. |
### isLocaleSupported(String localeString) {#isLocaleSupported-java.lang.String-}
```
public static boolean isLocaleSupported(String localeString)
```


Determines whether locale supported or not.

Format of localeString is  xx-YY  or  xx\_YY , examples:  en-US ,  en\_US 

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| localeString | java.lang.String | The locale to be checked, may be null |

**Returns:**
boolean - true if supported, otherwise false
### isLocaleSupported(Locale locale) {#isLocaleSupported-java.util.Locale-}
```
public static boolean isLocaleSupported(Locale locale)
```


Determines whether locale supported or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| locale | java.util.Locale | The locale to be checked, not null |

**Returns:**
boolean - true if supported, otherwise false
### isLocaleSupported(CultureInfo culture) {#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-}
```
public static boolean isLocaleSupported(CultureInfo culture)
```


Determines whether locale, represented as CultureInfo, supported or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| culture | com.groupdocs.foundation.utils.CultureInfo | The culture to be checked, not null |

**Returns:**
boolean - true if supported, otherwise false

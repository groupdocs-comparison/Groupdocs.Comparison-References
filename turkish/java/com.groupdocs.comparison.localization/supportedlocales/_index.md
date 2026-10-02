---
title: "SupportedLocales"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "SupportedLocales sınıfı, GroupDocs.Comparison için desteklenen yerel ayarları temsil eden sabitleri sağlar."
type: docs
weight: 10
url: /tr/java/com.groupdocs.comparison.localization/supportedlocales/
---
**Inheritance:**
java.lang.Object
```
public class SupportedLocales
```

SupportedLocales sınıfı, GroupDocs.Comparison için desteklenen yerel ayarları temsil eden sabitleri sağlar.


Yerelleştirilmiş işlemler, örneğin biçimlendirme ve mesaj gösterimi için yerel ayarı belirtmenizi sağlar.


Yereller hakkında daha fazla bilgi için Java Locale belgelerine bakın:
[Java Locale](../https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Locale.html)


Örnek kullanım:

````

 final boolean localeSupported = SupportedLocales.isLocaleSupported(Locale.CANADA);
 
````


## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isLocaleSupported(String localeString)](#isLocaleSupported-java.lang.String-) | Yerelin desteklenip desteklenmediğini belirler. |
|
|  | [isLocaleSupported(Locale locale)](#isLocaleSupported-java.util.Locale-) | Yerelin desteklenip desteklenmediğini belirler. |
|
|  | [isLocaleSupported(CultureInfo culture)](#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-) | CultureInfo olarak temsil edilen yerelin desteklenip desteklenmediğini belirler. |
|
### isLocaleSupported(String localeString) {#isLocaleSupported-java.lang.String-}
```
public static boolean isLocaleSupported(String localeString)
```


Yerelin desteklenip desteklenmediğini belirler.
localeString biçimi xx-YY veya xx_YY şeklindedir, örnekler: en-US, en_US


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | localeString | java.lang.String | Kontrol edilecek yerel ayar, null olabilir |
|

**Returns:**
boolean - destekleniyorsa true, aksi takdirde false

### isLocaleSupported(Locale locale) {#isLocaleSupported-java.util.Locale-}
```
public static boolean isLocaleSupported(Locale locale)
```


Yerelin desteklenip desteklenmediğini belirler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | locale | java.util.Locale | Kontrol edilecek yerel ayar, null olmamalı |
|

**Returns:**
boolean - destekleniyorsa true, aksi takdirde false

### isLocaleSupported(CultureInfo culture) {#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-}
```
public static boolean isLocaleSupported(CultureInfo culture)
```


CultureInfo olarak temsil edilen yerelin desteklenip desteklenmediğini belirler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | culture | com.groupdocs.foundation.utils.CultureInfo | Kontrol edilecek kültür, null olmamalı |
|

**Returns:**
boolean - destekleniyorsa true, aksi takdirde false


---
title: "SupportedLocales"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "توفر فئة SupportedLocales ثوابت تمثل اللغات المدعومة في GroupDocs.Comparison."
type: docs
weight: 10
url: /ar/java/com.groupdocs.comparison.localization/supportedlocales/
---
**Inheritance:**
java.lang.Object
```
public class SupportedLocales
```

توفر فئة SupportedLocales ثوابت تمثل اللغات المدعومة في GroupDocs.Comparison.


يتيح لك تحديد الإعداد الإقليمي للعمليات الخاصة باللغة، مثل التنسيق وعرض الرسائل.


لمزيد من المعلومات حول الإعدادات الإقليمية، راجع وثائق Java Locale:
[Java Locale](../https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Locale.html)


مثال على الاستخدام:

````

 final boolean localeSupported = SupportedLocales.isLocaleSupported(Locale.CANADA);
 
````


## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isLocaleSupported(String localeString)](#isLocaleSupported-java.lang.String-) | يحدد ما إذا كان الإعداد الإقليمي مدعومًا أم لا. |
|
|  | [isLocaleSupported(Locale locale)](#isLocaleSupported-java.util.Locale-) | يحدد ما إذا كان الإعداد الإقليمي مدعومًا أم لا. |
|
|  | [isLocaleSupported(CultureInfo culture)](#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-) | يحدد ما إذا كان الإعداد الإقليمي، الممثل كـCultureInfo، مدعومًا أم لا. |
|
### isLocaleSupported(String localeString) {#isLocaleSupported-java.lang.String-}
```
public static boolean isLocaleSupported(String localeString)
```


يحدد ما إذا كان الإعداد الإقليمي مدعومًا أم لا.
صيغة localeString هي xx-YY أو xx_YY، أمثلة: en-US، en_US


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | localeString | java.lang.String | الإعداد الإقليمي الذي سيتم التحقق منه، قد يكون فارغًا |
|

**Returns:**
منطقي - true إذا كان مدعومًا، وإلا false

### isLocaleSupported(Locale locale) {#isLocaleSupported-java.util.Locale-}
```
public static boolean isLocaleSupported(Locale locale)
```


يحدد ما إذا كان الإعداد الإقليمي مدعومًا أم لا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | locale | java.util.Locale | الإعداد الإقليمي الذي سيتم التحقق منه، غير فارغ |
|

**Returns:**
منطقي - true إذا كان مدعومًا، وإلا false

### isLocaleSupported(CultureInfo culture) {#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-}
```
public static boolean isLocaleSupported(CultureInfo culture)
```


يحدد ما إذا كان الإعداد الإقليمي، الممثل كـCultureInfo، مدعومًا أم لا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | culture | com.groupdocs.foundation.utils.CultureInfo | الثقافة التي سيتم التحقق منها، غير فارغة |
|

**Returns:**
منطقي - true إذا كان مدعومًا، وإلا false


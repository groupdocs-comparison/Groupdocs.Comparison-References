---
title: "SupportedLocales"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "SupportedLocales 클래스는 GroupDocs.Comparison에서 지원되는 로케일을 나타내는 상수를 제공합니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.comparison.localization/supportedlocales/
---
**Inheritance:**
java.lang.Object
```
public class SupportedLocales
```

SupportedLocales 클래스는 GroupDocs.Comparison에서 지원되는 로케일을 나타내는 상수를 제공합니다.


포맷팅 및 메시지 표시와 같은 언어별 작업을 위해 로케일을 지정할 수 있습니다.


로케일에 대한 자세한 내용은 Java Locale 문서를 참조하십시오:
[Java Locale](../https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Locale.html)


사용 예시:

````

 final boolean localeSupported = SupportedLocales.isLocaleSupported(Locale.CANADA);
 
````


## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isLocaleSupported(String localeString)](#isLocaleSupported-java.lang.String-) | 로케일이 지원되는지 여부를 결정합니다. |
|
|  | [isLocaleSupported(Locale locale)](#isLocaleSupported-java.util.Locale-) | 로케일이 지원되는지 여부를 결정합니다. |
|
|  | [isLocaleSupported(CultureInfo culture)](#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-) | CultureInfo로 표현된 로케일이 지원되는지 여부를 결정합니다. |
|
### isLocaleSupported(String localeString) {#isLocaleSupported-java.lang.String-}
```
public static boolean isLocaleSupported(String localeString)
```


로케일이 지원되는지 여부를 결정합니다.
localeString의 형식은 xx-YY 또는 xx_YY이며, 예시: en-US, en_US


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | localeString | java.lang.String | 확인할 로케일이며, null일 수 있습니다. |
|

**Returns:**
boolean - 지원되면 true, 그렇지 않으면 false

### isLocaleSupported(Locale locale) {#isLocaleSupported-java.util.Locale-}
```
public static boolean isLocaleSupported(Locale locale)
```


로케일이 지원되는지 여부를 결정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | locale | java.util.Locale | 확인할 로케일이며, null이 아닙니다. |
|

**Returns:**
boolean - 지원되면 true, 그렇지 않으면 false

### isLocaleSupported(CultureInfo culture) {#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-}
```
public static boolean isLocaleSupported(CultureInfo culture)
```


CultureInfo로 표현된 로케일이 지원되는지 여부를 결정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | culture | com.groupdocs.foundation.utils.CultureInfo | 확인할 문화 정보이며, null이 아닙니다. |
|

**Returns:**
boolean - 지원되면 true, 그렇지 않으면 false


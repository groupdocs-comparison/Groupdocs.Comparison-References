---
title: "SupportedLocales"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "SupportedLocales क्लास GroupDocs.Comparison के लिए समर्थित लोकैलों को दर्शाने वाले स्थिरांक प्रदान करती है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.comparison.localization/supportedlocales/
---
**Inheritance:**
java.lang.Object
```
public class SupportedLocales
```

SupportedLocales क्लास GroupDocs.Comparison के लिए समर्थित लोकैलों को दर्शाने वाले स्थिरांक प्रदान करती है।


यह आपको भाषा-विशिष्ट कार्यों के लिए लोकेल निर्दिष्ट करने की अनुमति देता है, जैसे फ़ॉर्मेटिंग और संदेशों को प्रदर्शित करना।


लोकेल के बारे में अधिक जानकारी के लिए, Java Locale दस्तावेज़ देखें:
[Java Locale](../https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Locale.html)


उदाहरण उपयोग:

````

 final boolean localeSupported = SupportedLocales.isLocaleSupported(Locale.CANADA);
 
````


## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [isLocaleSupported(String localeString)](#isLocaleSupported-java.lang.String-) | निर्धारित करता है कि लोकेल समर्थित है या नहीं। |
|
|  | [isLocaleSupported(Locale locale)](#isLocaleSupported-java.util.Locale-) | निर्धारित करता है कि लोकेल समर्थित है या नहीं। |
|
|  | [isLocaleSupported(CultureInfo culture)](#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-) | निर्धारित करता है कि CultureInfo के रूप में प्रतिनिधित्व किया गया लोकेल समर्थित है या नहीं। |
|
### isLocaleSupported(String localeString) {#isLocaleSupported-java.lang.String-}
```
public static boolean isLocaleSupported(String localeString)
```


निर्धारित करता है कि लोकेल समर्थित है या नहीं।
localeString का स्वरूप xx-YY या xx_YY है, उदाहरण: en-US, en_US


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | localeString | java.lang.String | जाँच के लिए लोकेल, यह null हो सकता है। |
|

**Returns:**
boolean - यदि समर्थित हो तो true, अन्यथा false

### isLocaleSupported(Locale locale) {#isLocaleSupported-java.util.Locale-}
```
public static boolean isLocaleSupported(Locale locale)
```


निर्धारित करता है कि लोकेल समर्थित है या नहीं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | locale | java.util.Locale | जाँच के लिए लोकेल, null नहीं होना चाहिए। |
|

**Returns:**
boolean - यदि समर्थित हो तो true, अन्यथा false

### isLocaleSupported(CultureInfo culture) {#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-}
```
public static boolean isLocaleSupported(CultureInfo culture)
```


निर्धारित करता है कि CultureInfo के रूप में प्रतिनिधित्व किया गया लोकेल समर्थित है या नहीं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | culture | com.groupdocs.foundation.utils.CultureInfo | जाँच के लिए संस्कृति, null नहीं होना चाहिए। |
|

**Returns:**
boolean - यदि समर्थित हो तो true, अन्यथा false


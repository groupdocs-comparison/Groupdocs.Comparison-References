---
title: "SupportedLocales"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "SupportedLocales 类提供表示 GroupDocs.Comparison 支持的地区设置的常量。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.comparison.localization/supportedlocales/
---
**Inheritance:**
java.lang.Object
```
public class SupportedLocales
```

SupportedLocales 类提供表示 GroupDocs.Comparison 支持的地区设置的常量。


它允许您指定用于语言特定操作的区域设置，例如格式化和显示消息。


有关区域设置的更多信息，请参阅 Java Locale 文档：
[Java Locale](../https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Locale.html)


示例用法：

````

 final boolean localeSupported = SupportedLocales.isLocaleSupported(Locale.CANADA);
 
````


## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isLocaleSupported(String localeString)](#isLocaleSupported-java.lang.String-) | 确定区域设置是否受支持。 |
|
|  | [isLocaleSupported(Locale locale)](#isLocaleSupported-java.util.Locale-) | 确定区域设置是否受支持。 |
|
|  | [isLocaleSupported(CultureInfo culture)](#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-) | 确定以 CultureInfo 表示的区域设置是否受支持。 |
|
### isLocaleSupported(String localeString) {#isLocaleSupported-java.lang.String-}
```
public static boolean isLocaleSupported(String localeString)
```


确定区域设置是否受支持。
localeString 的格式为 xx-YY 或 xx_YY，例如：en-US、en_US


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | localeString | java.lang.String | 要检查的区域设置，可能为 null |
|

**Returns:**
boolean - 如果受支持则为 true，否则为 false

### isLocaleSupported(Locale locale) {#isLocaleSupported-java.util.Locale-}
```
public static boolean isLocaleSupported(Locale locale)
```


确定区域设置是否受支持。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | locale | java.util.Locale | 要检查的区域设置，不能为空 |
|

**Returns:**
boolean - 如果受支持则为 true，否则为 false

### isLocaleSupported(CultureInfo culture) {#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-}
```
public static boolean isLocaleSupported(CultureInfo culture)
```


确定以 CultureInfo 表示的区域设置是否受支持。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | culture | com.groupdocs.foundation.utils.CultureInfo | 要检查的文化信息，不能为空 |
|

**Returns:**
boolean - 如果受支持则为 true，否则为 false


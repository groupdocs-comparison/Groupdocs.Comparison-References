---
title: "SupportedLocales"
second_title: "Java 用 GroupDocs.Comparison API リファレンス"
description: "SupportedLocales クラスは、GroupDocs.Comparison がサポートするロケールを表す定数を提供します。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.comparison.localization/supportedlocales/
---
**Inheritance:**
java.lang.Object
```
public class SupportedLocales
```

SupportedLocales クラスは、GroupDocs.Comparison がサポートするロケールを表す定数を提供します。


ロケールを指定できるようにします。これにより、書式設定やメッセージ表示など、言語固有の操作が可能になります。


ロケールに関する詳細情報は、Java の Locale ドキュメントを参照してください：
[Java Locale](../https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Locale.html)


使用例:

````

 final boolean localeSupported = SupportedLocales.isLocaleSupported(Locale.CANADA);
 
````


## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isLocaleSupported(String localeString)](#isLocaleSupported-java.lang.String-) | ロケールがサポートされているかどうかを判定します。 |
|
|  | [isLocaleSupported(Locale locale)](#isLocaleSupported-java.util.Locale-) | ロケールがサポートされているかどうかを判定します。 |
|
|  | [isLocaleSupported(CultureInfo culture)](#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-) | CultureInfo として表されるロケールがサポートされているかどうかを判定します。 |
|
### isLocaleSupported(String localeString) {#isLocaleSupported-java.lang.String-}
```
public static boolean isLocaleSupported(String localeString)
```


ロケールがサポートされているかどうかを判定します。
localeString の形式は xx-YY または xx_YY で、例: en-US、en_US


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | localeString | java.lang.String | チェックするロケールです。null の可能性があります。 |
|

**Returns:**
boolean - サポートされていれば true、そうでなければ false

### isLocaleSupported(Locale locale) {#isLocaleSupported-java.util.Locale-}
```
public static boolean isLocaleSupported(Locale locale)
```


ロケールがサポートされているかどうかを判定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | locale | java.util.Locale | チェックするロケール（null ではありません） |
|

**Returns:**
boolean - サポートされていれば true、そうでなければ false

### isLocaleSupported(CultureInfo culture) {#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-}
```
public static boolean isLocaleSupported(CultureInfo culture)
```


CultureInfo として表されるロケールがサポートされているかどうかを判定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | culture | com.groupdocs.foundation.utils.CultureInfo | チェックするカルチャ（null ではありません） |
|

**Returns:**
boolean - サポートされていれば true、そうでなければ false


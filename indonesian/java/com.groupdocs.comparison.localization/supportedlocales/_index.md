---
title: "SupportedLocales"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Kelas SupportedLocales menyediakan konstanta yang mewakili locale yang didukung untuk GroupDocs.Comparison."
type: docs
weight: 10
url: /id/java/com.groupdocs.comparison.localization/supportedlocales/
---
**Inheritance:**
java.lang.Object
```
public class SupportedLocales
```

Kelas SupportedLocales menyediakan konstanta yang mewakili locale yang didukung untuk GroupDocs.Comparison.


Ini memungkinkan Anda menentukan locale untuk operasi khusus bahasa, seperti pemformatan dan menampilkan pesan.


Untuk informasi lebih lanjut tentang locale, lihat dokumentasi Java Locale:
[Java Locale](../https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Locale.html)


Contoh penggunaan:

````

 final boolean localeSupported = SupportedLocales.isLocaleSupported(Locale.CANADA);
 
````


## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isLocaleSupported(String localeString)](#isLocaleSupported-java.lang.String-) | Menentukan apakah locale didukung atau tidak. |
|
|  | [isLocaleSupported(Locale locale)](#isLocaleSupported-java.util.Locale-) | Menentukan apakah locale didukung atau tidak. |
|
|  | [isLocaleSupported(CultureInfo culture)](#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-) | Menentukan apakah locale, yang direpresentasikan sebagai CultureInfo, didukung atau tidak. |
|
### isLocaleSupported(String localeString) {#isLocaleSupported-java.lang.String-}
```
public static boolean isLocaleSupported(String localeString)
```


Menentukan apakah locale didukung atau tidak.
Format localeString adalah xx-YY atau xx_YY, contoh: en-US, en_US


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | localeString | java.lang.String | Locale yang akan diperiksa, dapat bernilai null |
|

**Returns:**
boolean - true jika didukung, jika tidak false

### isLocaleSupported(Locale locale) {#isLocaleSupported-java.util.Locale-}
```
public static boolean isLocaleSupported(Locale locale)
```


Menentukan apakah locale didukung atau tidak.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | locale | java.util.Locale | Locale yang akan diperiksa, tidak null |
|

**Returns:**
boolean - true jika didukung, jika tidak false

### isLocaleSupported(CultureInfo culture) {#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-}
```
public static boolean isLocaleSupported(CultureInfo culture)
```


Menentukan apakah locale, yang direpresentasikan sebagai CultureInfo, didukung atau tidak.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | culture | com.groupdocs.foundation.utils.CultureInfo | Culture yang akan diperiksa, tidak null |
|

**Returns:**
boolean - true jika didukung, jika tidak false


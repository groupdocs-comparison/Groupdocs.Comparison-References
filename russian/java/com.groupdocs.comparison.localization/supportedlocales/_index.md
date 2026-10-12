---
title: "SupportedLocales"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Класс SupportedLocales предоставляет константы, представляющие поддерживаемые локали для GroupDocs.Comparison."
type: docs
weight: 10
url: /ru/java/com.groupdocs.comparison.localization/supportedlocales/
---
**Inheritance:**
java.lang.Object
```
public class SupportedLocales
```

Класс SupportedLocales предоставляет константы, представляющие поддерживаемые локали для GroupDocs.Comparison.


Позволяет указать локаль для языково-специфических операций, таких как форматирование и отображение сообщений.


Для получения дополнительной информации о локалях обратитесь к документации Java Locale:
[Java Locale](../https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Locale.html)


Пример использования:

````

 final boolean localeSupported = SupportedLocales.isLocaleSupported(Locale.CANADA);
 
````


## Методы

| Метод | Описание |
| --- | --- |
|  | [isLocaleSupported(String localeString)](#isLocaleSupported-java.lang.String-) | Определяет, поддерживается ли локаль. |
|
|  | [isLocaleSupported(Locale locale)](#isLocaleSupported-java.util.Locale-) | Определяет, поддерживается ли локаль. |
|
|  | [isLocaleSupported(CultureInfo culture)](#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-) | Определяет, поддерживается ли локаль, представленная как CultureInfo. |
|
### isLocaleSupported(String localeString) {#isLocaleSupported-java.lang.String-}
```
public static boolean isLocaleSupported(String localeString)
```


Определяет, поддерживается ли локаль.
Формат localeString — xx-YY или xx_YY, примеры: en-US, en_US


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | localeString | java.lang.String | Локаль для проверки, может быть null |
|

**Returns:**
boolean — true, если поддерживается, иначе false

### isLocaleSupported(Locale locale) {#isLocaleSupported-java.util.Locale-}
```
public static boolean isLocaleSupported(Locale locale)
```


Определяет, поддерживается ли локаль.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | locale | java.util.Locale | Локаль для проверки, не null |
|

**Returns:**
boolean — true, если поддерживается, иначе false

### isLocaleSupported(CultureInfo culture) {#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-}
```
public static boolean isLocaleSupported(CultureInfo culture)
```


Определяет, поддерживается ли локаль, представленная как CultureInfo.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | culture | com.groupdocs.foundation.utils.CultureInfo | Культура для проверки, не null |
|

**Returns:**
boolean — true, если поддерживается, иначе false


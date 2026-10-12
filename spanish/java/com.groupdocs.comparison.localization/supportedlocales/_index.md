---
title: "SupportedLocales"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "La clase SupportedLocales proporciona constantes que representan las configuraciones regionales admitidas para GroupDocs.Comparison."
type: docs
weight: 10
url: /es/java/com.groupdocs.comparison.localization/supportedlocales/
---
**Inheritance:**
java.lang.Object
```
public class SupportedLocales
```

La clase SupportedLocales proporciona constantes que representan las configuraciones regionales admitidas para GroupDocs.Comparison.


Permite especificar la configuración regional para operaciones específicas de idioma, como el formato y la visualización de mensajes.


Para obtener más información sobre configuraciones regionales, consulte la documentación de Java Locale:
[Java Locale](../https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Locale.html)


Ejemplo de uso:

````

 final boolean localeSupported = SupportedLocales.isLocaleSupported(Locale.CANADA);
 
````


## Métodos

| Método | Descripción |
| --- | --- |
|  | [isLocaleSupported(String localeString)](#isLocaleSupported-java.lang.String-) | Determina si la configuración regional es compatible o no. |
|
|  | [isLocaleSupported(Locale locale)](#isLocaleSupported-java.util.Locale-) | Determina si la configuración regional es compatible o no. |
|
|  | [isLocaleSupported(CultureInfo culture)](#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-) | Determina si la configuración regional, representada como CultureInfo, es compatible o no. |
|
### isLocaleSupported(String localeString) {#isLocaleSupported-java.lang.String-}
```
public static boolean isLocaleSupported(String localeString)
```


Determina si la configuración regional es compatible o no.
El formato de localeString es xx-YY o xx_YY, ejemplos: en-US, en_US


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | localeString | java.lang.String | La configuración regional a comprobar, puede ser nula |
|

**Returns:**
boolean - true si es compatible, de lo contrario false

### isLocaleSupported(Locale locale) {#isLocaleSupported-java.util.Locale-}
```
public static boolean isLocaleSupported(Locale locale)
```


Determina si la configuración regional es compatible o no.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | locale | java.util.Locale | La configuración regional a comprobar, no nula |
|

**Returns:**
boolean - true si es compatible, de lo contrario false

### isLocaleSupported(CultureInfo culture) {#isLocaleSupported-com.groupdocs.foundation.utils.CultureInfo-}
```
public static boolean isLocaleSupported(CultureInfo culture)
```


Determina si la configuración regional, representada como CultureInfo, es compatible o no.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | culture | com.groupdocs.foundation.utils.CultureInfo | La cultura a comprobar, no nula |
|

**Returns:**
boolean - true si es compatible, de lo contrario false


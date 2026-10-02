---
title: "Utils"
second_title: "GroupDocs.Comparison for Java API Referansı"
description: "Comparison API'si kullanılırken yararlı olabilecek ortak yardımcı yöntemler sağlayan yardımcı sınıf."
type: docs
weight: 11
url: /tr/java/com.groupdocs.comparison.common/utils/
---
**Inheritance:**
java.lang.Object
```
public class Utils
```

Comparison API'si kullanılırken yararlı olabilecek ortak yardımcı yöntemler sağlayan yardımcı sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Utils()](#Utils--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getMethodByTag(Class<?> clazz, String methodTag, boolean isGetter)](#getMethodByTag-java.lang.Class----java.lang.String-boolean-) |  |
|  | [closeStreams(Closeable[] closeables)](#closeStreams-java.io.Closeable...-) | Sağlanan tüm nesneleri sessizce kapatır, tüm IOException'ları yakalar ve kaydeder. |
|
|  | [closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)](#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-) | Belirtilen akışları kapatır, IOException kaydı veya işlenmesi sırasında oluşan tüm istisnaları bastırır. |
|
|  | [isText(String data)](#isText-java.lang.String-) | Giriş dizesinin herhangi bir dildeki tipik dizede izin verilen yalnızca karakterler içerdiğini kontrol eder. |
|
| [containsOnlyLatinCharsAndPunctuation(String data)](#containsOnlyLatinCharsAndPunctuation-java.lang.String-) |  |
| [toString(TextStyle textStyle)](#toString-com.aspose.note.TextStyle-) |  |
### Utils() {#Utils--}
```
public Utils()
```


### getMethodByTag(Class<?> clazz, String methodTag, boolean isGetter) {#getMethodByTag-java.lang.Class----java.lang.String-boolean-}
```
public static Optional<Method> getMethodByTag(Class<?> clazz, String methodTag, boolean isGetter)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| clazz | java.lang.Class<?> |  |
| methodTag | java.lang.String |  |
| isGetter | boolean |  |

**Returns:**
java.util.Optional<java.lang.reflect.Method>
### closeStreams(Closeable[] closeables) {#closeStreams-java.io.Closeable...-}
```
public static boolean closeStreams(Closeable[] closeables)
```


Sağlanan tüm nesneleri sessizce kapatır, tüm IOException'ları yakalar ve kaydeder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | closeables | java.io.Closeable[] | Closeable arayüzünü uygulayan herhangi bir nesne, null olabilir |
|

**Returns:**
boolean - tüm closeable nesneler istisna olmadan kapatıldıysa true, aksi takdirde false

### closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables) {#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-}
```
public static boolean closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)
```


Belirtilen akışları kapatır, IOException kaydı veya işlenmesi sırasında oluşan tüm istisnaları bastırır.
Akışlardan biri null ise veya kapatılırken bir istisna ile karşılaşırsa, yok sayılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | tüketici | java.util.function.BiConsumer<java.io.Closeable,java.io.IOException> | Kapatma sırasında istisna fırlatıldığında, her bir closeable ve IOException çifti için çağrılır, null olabilir. |
|
|  | closeables | java.io.Closeable[] | Closeable arayüzünü uygulayan herhangi bir nesne, null olabilir |
|

**Returns:**
boolean - tüm closeable nesneler istisna olmadan kapatıldıysa true, aksi takdirde false

### isText(String data) {#isText-java.lang.String-}
```
public static boolean isText(String data)
```


Giriş dizesinin herhangi bir dildeki tipik dizede izin verilen yalnızca karakterler içerdiğini kontrol eder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | java.lang.String |  |

**Returns:**
boolean
### containsOnlyLatinCharsAndPunctuation(String data) {#containsOnlyLatinCharsAndPunctuation-java.lang.String-}
```
public static boolean containsOnlyLatinCharsAndPunctuation(String data)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | java.lang.String |  |

**Returns:**
boolean
### toString(TextStyle textStyle) {#toString-com.aspose.note.TextStyle-}
```
public static void toString(TextStyle textStyle)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| textStyle | com.aspose.note.TextStyle |  |


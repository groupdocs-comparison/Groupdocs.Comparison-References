---
title: "Utils"
second_title: "Referensi API GroupDocs.Comparison untuk Java"
description: "Kelas utilitas yang menyediakan metode pembantu umum yang dapat berguna saat menggunakan API Comparison."
type: docs
weight: 11
url: /id/java/com.groupdocs.comparison.common/utils/
---
**Inheritance:**
java.lang.Object
```
public class Utils
```

Kelas utilitas yang menyediakan metode pembantu umum yang dapat berguna saat menggunakan API Comparison.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Utils()](#Utils--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getMethodByTag(Class<?> clazz, String methodTag, boolean isGetter)](#getMethodByTag-java.lang.Class----java.lang.String-boolean-) |  |
|  | [closeStreams(Closeable[] closeables)](#closeStreams-java.io.Closeable...-) | Menutup semua objek yang diberikan secara tenang sambil menangkap dan mencatat semua IOException. |
|
|  | [closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)](#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-) | Menutup aliran yang ditentukan, menekan setiap pengecualian yang terjadi saat mencatat atau memproses IOException |
|
|  | [isText(String data)](#isText-java.lang.String-) | Memeriksa bahwa string input hanya berisi karakter yang diizinkan dalam string biasa dari bahasa apa pun |
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
| Parameter | Tipe | Deskripsi |
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


Menutup semua objek yang diberikan secara tenang sambil menangkap dan mencatat semua IOException.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | closeables | java.io.Closeable[] | Objek apa pun yang mengimplementasikan antarmuka Closeable, dapat bernilai null |
|

**Returns:**
boolean - true jika semua objek closeable ditutup tanpa pengecualian, jika tidak false

### closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables) {#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-}
```
public static boolean closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)
```


Menutup aliran yang ditentukan, menekan setiap pengecualian yang terjadi saat mencatat atau memproses IOException
Jika salah satu aliran bernilai null atau mengalami pengecualian saat ditutup, maka akan diabaikan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | consumer | java.util.function.BiConsumer<java.io.Closeable,java.io.IOException> | Akan dipanggil untuk setiap pasangan closeable dan IOException ketika penutupan melempar pengecualian, dapat bernilai null |
|
|  | closeables | java.io.Closeable[] | Objek apa pun yang mengimplementasikan antarmuka Closeable, dapat bernilai null |
|

**Returns:**
boolean - true jika semua objek closeable ditutup tanpa pengecualian, jika tidak false

### isText(String data) {#isText-java.lang.String-}
```
public static boolean isText(String data)
```


Memeriksa bahwa string input hanya berisi karakter yang diizinkan dalam string biasa dari bahasa apa pun


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | java.lang.String |  |

**Returns:**
boolean
### containsOnlyLatinCharsAndPunctuation(String data) {#containsOnlyLatinCharsAndPunctuation-java.lang.String-}
```
public static boolean containsOnlyLatinCharsAndPunctuation(String data)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | java.lang.String |  |

**Returns:**
boolean
### toString(TextStyle textStyle) {#toString-com.aspose.note.TextStyle-}
```
public static void toString(TextStyle textStyle)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| textStyle | com.aspose.note.TextStyle |  |


---
title: "Utils"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Hjälpklass som tillhandahåller vanliga hjälpfunktioner som kan vara användbara när du använder Comparison API."
type: docs
weight: 11
url: /sv/java/com.groupdocs.comparison.common/utils/
---
**Inheritance:**
java.lang.Object
```
public class Utils
```

Hjälpklass som tillhandahåller vanliga hjälpfunktioner som kan vara användbara när du använder Comparison API.

## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [Utils()](#Utils--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getMethodByTag(Class<?> clazz, String methodTag, boolean isGetter)](#getMethodByTag-java.lang.Class----java.lang.String-boolean-) |  |
|  | [closeStreams(Closeable[] closeables)](#closeStreams-java.io.Closeable...-) | Stänger tyst alla tillhandahållna objekt, fångar och loggar alla IOException. |
|
|  | [closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)](#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-) | Stänger de angivna strömmarna och undertrycker eventuella undantag som uppstår vid loggning eller bearbetning av IOException. |
|
|  | [isText(String data)](#isText-java.lang.String-) | Kontrollerar att inmatningssträngen endast har tecken som är tillåtna i en vanlig sträng på vilket språk som helst |
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
| Parameter | Typ | Beskrivning |
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


Stänger tyst alla tillhandahållna objekt, fångar och loggar alla IOException.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | closeables | java.io.Closeable[] | Alla objekt som implementerar Closeable‑gränssnittet, kan vara null |
|

**Returns:**
boolean – true om alla closeable‑objekt stängdes utan undantag, annars false

### closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables) {#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-}
```
public static boolean closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)
```


Stänger de angivna strömmarna och undertrycker eventuella undantag som uppstår vid loggning eller bearbetning av IOException.
Om någon av strömmarna är null eller får ett undantag vid stängning, ignoreras den.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | consumer | java.util.function.BiConsumer<java.io.Closeable,java.io.IOException> | Kommer att anropas för varje par av closeable och IOException när stängning kastar undantaget, kan vara null |
|
|  | closeables | java.io.Closeable[] | Alla objekt som implementerar Closeable‑gränssnittet, kan vara null |
|

**Returns:**
boolean – true om alla closeable‑objekt stängdes utan undantag, annars false

### isText(String data) {#isText-java.lang.String-}
```
public static boolean isText(String data)
```


Kontrollerar att inmatningssträngen endast har tecken som är tillåtna i en vanlig sträng på vilket språk som helst


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | java.lang.String |  |

**Returns:**
boolean
### containsOnlyLatinCharsAndPunctuation(String data) {#containsOnlyLatinCharsAndPunctuation-java.lang.String-}
```
public static boolean containsOnlyLatinCharsAndPunctuation(String data)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | java.lang.String |  |

**Returns:**
boolean
### toString(TextStyle textStyle) {#toString-com.aspose.note.TextStyle-}
```
public static void toString(TextStyle textStyle)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| textStyle | com.aspose.note.TextStyle |  |


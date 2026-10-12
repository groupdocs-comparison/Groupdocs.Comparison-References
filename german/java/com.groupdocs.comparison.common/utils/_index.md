---
title: "Utils"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Hilfsklasse, die gängige Hilfsmethoden bereitstellt, die bei der Verwendung der Comparison API nützlich sein können."
type: docs
weight: 11
url: /de/java/com.groupdocs.comparison.common/utils/
---
**Inheritance:**
java.lang.Object
```
public class Utils
```

Hilfsklasse, die gängige Hilfsmethoden bereitstellt, die bei der Verwendung der Comparison API nützlich sein können.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Utils()](#Utils--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getMethodByTag(Class<?> clazz, String methodTag, boolean isGetter)](#getMethodByTag-java.lang.Class----java.lang.String-boolean-) |  |
|  | [closeStreams(Closeable[] closeables)](#closeStreams-java.io.Closeable...-) | Schließt leise alle bereitgestellten Objekte, fängt alle IOExceptions ab und protokolliert sie. |
|
|  | [closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)](#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-) | Schließt die angegebenen Streams und unterdrückt dabei alle Ausnahmen, die beim Protokollieren oder Verarbeiten von IOExceptions auftreten. |
|
|  | [isText(String data)](#isText-java.lang.String-) | Überprüft, ob die Eingabezeichenfolge nur Zeichen enthält, die in einer üblichen Zeichenkette jeder Sprache erlaubt sind. |
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
| Parameter | Typ | Beschreibung |
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


Schließt leise alle bereitgestellten Objekte, fängt alle IOExceptions ab und protokolliert sie.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | closeables | java.io.Closeable[] | Ein beliebiges Objekt, das das Closeable-Interface implementiert, kann null sein. |
|

**Returns:**
boolean – true, wenn alle Closeable-Objekte ohne Ausnahme geschlossen wurden, sonst false.

### closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables) {#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-}
```
public static boolean closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)
```


Schließt die angegebenen Streams und unterdrückt dabei alle Ausnahmen, die beim Protokollieren oder Verarbeiten von IOExceptions auftreten.
Wenn einer der Streams null ist oder beim Schließen eine Ausnahme auftritt, wird er ignoriert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | consumer | java.util.function.BiConsumer<java.io.Closeable,java.io.IOException> | Wird für jedes Paar aus Closeable und IOException aufgerufen, wenn beim Schließen eine Ausnahme geworfen wird; kann null sein. |
|
|  | closeables | java.io.Closeable[] | Ein beliebiges Objekt, das das Closeable-Interface implementiert, kann null sein. |
|

**Returns:**
boolean – true, wenn alle Closeable-Objekte ohne Ausnahme geschlossen wurden, sonst false.

### isText(String data) {#isText-java.lang.String-}
```
public static boolean isText(String data)
```


Überprüft, ob die Eingabezeichenfolge nur Zeichen enthält, die in einer üblichen Zeichenkette jeder Sprache erlaubt sind.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | java.lang.String |  |

**Returns:**
boolean
### containsOnlyLatinCharsAndPunctuation(String data) {#containsOnlyLatinCharsAndPunctuation-java.lang.String-}
```
public static boolean containsOnlyLatinCharsAndPunctuation(String data)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | java.lang.String |  |

**Returns:**
boolean
### toString(TextStyle textStyle) {#toString-com.aspose.note.TextStyle-}
```
public static void toString(TextStyle textStyle)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| textStyle | com.aspose.note.TextStyle |  |


---
title: Utils
second_title: GroupDocs.Comparison for Java API Reference
description: Utility class that provides common helper methods which can be useful when using Comparison API.
type: docs
weight: 11
url: /java/com.groupdocs.comparison.common/utils/
---
**Inheritance:**
java.lang.Object
```
public class Utils
```

Utility class that provides common helper methods which can be useful when using Comparison API.
## Constructors

| Constructor | Description |
| --- | --- |
| [Utils()](#Utils--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getMethodByTag(Class<?> clazz, String methodTag, boolean isGetter)](#getMethodByTag-java.lang.Class----java.lang.String-boolean-) |  |
| [closeStreams(Closeable[] closeables)](#closeStreams-java.io.Closeable...-) | Quietly closes all provided objects catching and logging all IOException. |
| [closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)](#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-) | Closes the specified streams, suppressing any exceptions that occur logging or processing IOException |
| [isText(String data)](#isText-java.lang.String-) | Checks that input string has only chars allowed in usual string of any language |
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
| Parameter | Type | Description |
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


Quietly closes all provided objects catching and logging all IOException.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| closeables | java.io.Closeable[] | Any object that implements Closeable interface, may be null |

**Returns:**
boolean - true if all closeable objects were closed without exception, otherwise false
### closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables) {#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-}
```
public static boolean closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)
```


Closes the specified streams, suppressing any exceptions that occur logging or processing IOException

If any of the streams is null or encounters an exception while closing, it is ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| consumer | java.util.function.BiConsumer<java.io.Closeable,java.io.IOException> | Will be called for each pair of closeable and IOException when closing throws the exception, may be null |
| closeables | java.io.Closeable[] | Any object that implements Closeable interface, may be null |

**Returns:**
boolean - true if all closeable objects were closed without exception, otherwise false
### isText(String data) {#isText-java.lang.String-}
```
public static boolean isText(String data)
```


Checks that input string has only chars allowed in usual string of any language

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | java.lang.String |  |

**Returns:**
boolean
### containsOnlyLatinCharsAndPunctuation(String data) {#containsOnlyLatinCharsAndPunctuation-java.lang.String-}
```
public static boolean containsOnlyLatinCharsAndPunctuation(String data)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | java.lang.String |  |

**Returns:**
boolean
### toString(TextStyle textStyle) {#toString-com.aspose.note.TextStyle-}
```
public static void toString(TextStyle textStyle)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textStyle | com.aspose.note.TextStyle |  |


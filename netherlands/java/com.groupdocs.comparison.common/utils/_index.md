---
title: "Utils"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "Hulpprogrammaklasse die algemene helpermethoden biedt die nuttig kunnen zijn bij het gebruik van de Comparison API."
type: docs
weight: 11
url: /nl/java/com.groupdocs.comparison.common/utils/
---
**Inheritance:**
java.lang.Object
```
public class Utils
```

Hulpprogrammaklasse die algemene helpermethoden biedt die nuttig kunnen zijn bij het gebruik van de Comparison API.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Utils()](#Utils--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getMethodByTag(Class<?> clazz, String methodTag, boolean isGetter)](#getMethodByTag-java.lang.Class----java.lang.String-boolean-) |  |
|  | [closeStreams(Closeable[] closeables)](#closeStreams-java.io.Closeable...-) | Sluit stilzwijgend alle opgegeven objecten, vangt en logt alle IOException. |
|
|  | [closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)](#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-) | Sluit de opgegeven streams, onderdrukt eventuele uitzonderingen die optreden bij het loggen of verwerken van IOException. |
|
|  | [isText(String data)](#isText-java.lang.String-) | Controleert of de invoerstring alleen tekens bevat die zijn toegestaan in een gebruikelijke string van elke taal |
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
| Parameter | Type | Beschrijving |
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


Sluit stilzwijgend alle opgegeven objecten, vangt en logt alle IOException.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | closeables | java.io.Closeable[] | Elk object dat de Closeable-interface implementeert, mag null zijn |
|

**Returns:**
boolean - true als alle closeable-objecten zonder uitzondering werden gesloten, anders false

### closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables) {#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-}
```
public static boolean closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)
```


Sluit de opgegeven streams, onderdrukt eventuele uitzonderingen die optreden bij het loggen of verwerken van IOException.
Als een van de streams null is of een uitzondering tegenkomt tijdens het sluiten, wordt deze genegeerd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | consumer | java.util.function.BiConsumer<java.io.Closeable,java.io.IOException> | Wordt aangeroepen voor elk paar van closeable en IOException wanneer het sluiten de uitzondering gooit, mag null zijn |
|
|  | closeables | java.io.Closeable[] | Elk object dat de Closeable-interface implementeert, mag null zijn |
|

**Returns:**
boolean - true als alle closeable-objecten zonder uitzondering werden gesloten, anders false

### isText(String data) {#isText-java.lang.String-}
```
public static boolean isText(String data)
```


Controleert of de invoerstring alleen tekens bevat die zijn toegestaan in een gebruikelijke string van elke taal


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | java.lang.String |  |

**Returns:**
boolean
### containsOnlyLatinCharsAndPunctuation(String data) {#containsOnlyLatinCharsAndPunctuation-java.lang.String-}
```
public static boolean containsOnlyLatinCharsAndPunctuation(String data)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | java.lang.String |  |

**Returns:**
boolean
### toString(TextStyle textStyle) {#toString-com.aspose.note.TextStyle-}
```
public static void toString(TextStyle textStyle)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| textStyle | com.aspose.note.TextStyle |  |


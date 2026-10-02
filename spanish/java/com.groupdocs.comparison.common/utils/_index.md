---
title: "Utils"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "Clase de utilidad que proporciona métodos auxiliares comunes que pueden ser útiles al usar la API de Comparison."
type: docs
weight: 11
url: /es/java/com.groupdocs.comparison.common/utils/
---
**Inheritance:**
java.lang.Object
```
public class Utils
```

Clase de utilidad que proporciona métodos auxiliares comunes que pueden ser útiles al usar la API de Comparison.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Utils()](#Utils--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getMethodByTag(Class<?> clazz, String methodTag, boolean isGetter)](#getMethodByTag-java.lang.Class----java.lang.String-boolean-) |  |
|  | [closeStreams(Closeable[] closeables)](#closeStreams-java.io.Closeable...-) | Cierra silenciosamente todos los objetos proporcionados capturando y registrando todas las IOException. |
|
|  | [closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)](#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-) | Cierra los flujos especificados, suprimiendo cualquier excepción que ocurra al registrar o procesar IOException |
|
|  | [isText(String data)](#isText-java.lang.String-) | Comprueba que la cadena de entrada solo contenga caracteres permitidos en una cadena habitual de cualquier idioma |
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
| Parámetro | Tipo | Descripción |
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


Cierra silenciosamente todos los objetos proporcionados capturando y registrando todas las IOException.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | closeables | java.io.Closeable[] | Cualquier objeto que implemente la interfaz Closeable, puede ser nulo |
|

**Returns:**
boolean - verdadero si todos los objetos closeable se cerraron sin excepción, de lo contrario falso

### closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables) {#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-}
```
public static boolean closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)
```


Cierra los flujos especificados, suprimiendo cualquier excepción que ocurra al registrar o procesar IOException
Si alguno de los flujos es nulo o encuentra una excepción al cerrarse, se ignora.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | consumer | java.util.function.BiConsumer<java.io.Closeable,java.io.IOException> | Se llamará para cada par de closeable e IOException cuando el cierre lance la excepción, puede ser nulo |
|
|  | closeables | java.io.Closeable[] | Cualquier objeto que implemente la interfaz Closeable, puede ser nulo |
|

**Returns:**
boolean - verdadero si todos los objetos closeable se cerraron sin excepción, de lo contrario falso

### isText(String data) {#isText-java.lang.String-}
```
public static boolean isText(String data)
```


Comprueba que la cadena de entrada solo contenga caracteres permitidos en una cadena habitual de cualquier idioma


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | java.lang.String |  |

**Returns:**
boolean
### containsOnlyLatinCharsAndPunctuation(String data) {#containsOnlyLatinCharsAndPunctuation-java.lang.String-}
```
public static boolean containsOnlyLatinCharsAndPunctuation(String data)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | java.lang.String |  |

**Returns:**
boolean
### toString(TextStyle textStyle) {#toString-com.aspose.note.TextStyle-}
```
public static void toString(TextStyle textStyle)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| textStyle | com.aspose.note.TextStyle |  |


---
title: "Utils"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "Classe di utilità che fornisce metodi di supporto comuni utili quando si utilizza l'API Comparison."
type: docs
weight: 11
url: /it/java/com.groupdocs.comparison.common/utils/
---
**Inheritance:**
java.lang.Object
```
public class Utils
```

Classe di utilità che fornisce metodi di supporto comuni utili quando si utilizza l'API Comparison.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Utils()](#Utils--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getMethodByTag(Class<?> clazz, String methodTag, boolean isGetter)](#getMethodByTag-java.lang.Class----java.lang.String-boolean-) |  |
|  | [closeStreams(Closeable[] closeables)](#closeStreams-java.io.Closeable...-) | Chiude silenziosamente tutti gli oggetti forniti catturando e registrando tutte le IOException. |
|
|  | [closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)](#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-) | Chiude i flussi specificati, sopprimendo eventuali eccezioni che si verificano durante il logging o l'elaborazione delle IOException |
|
|  | [isText(String data)](#isText-java.lang.String-) | Verifica che la stringa di input contenga solo caratteri consentiti in una stringa comune di qualsiasi lingua |
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
| Parametro | Tipo | Descrizione |
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


Chiude silenziosamente tutti gli oggetti forniti catturando e registrando tutte le IOException.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | closeables | java.io.Closeable[] | Qualsiasi oggetto che implementa l'interfaccia Closeable, può essere nullo |
|

**Returns:**
boolean - true se tutti gli oggetti closeable sono stati chiusi senza eccezione, altrimenti false

### closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables) {#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-}
```
public static boolean closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)
```


Chiude i flussi specificati, sopprimendo eventuali eccezioni che si verificano durante il logging o l'elaborazione delle IOException
Se uno qualsiasi dei flussi è nullo o genera un'eccezione durante la chiusura, viene ignorato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | consumer | java.util.function.BiConsumer<java.io.Closeable,java.io.IOException> | Verrà chiamato per ogni coppia di closeable e IOException quando la chiusura genera l'eccezione, può essere nullo |
|
|  | closeables | java.io.Closeable[] | Qualsiasi oggetto che implementa l'interfaccia Closeable, può essere nullo |
|

**Returns:**
boolean - true se tutti gli oggetti closeable sono stati chiusi senza eccezione, altrimenti false

### isText(String data) {#isText-java.lang.String-}
```
public static boolean isText(String data)
```


Verifica che la stringa di input contenga solo caratteri consentiti in una stringa comune di qualsiasi lingua


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | java.lang.String |  |

**Returns:**
boolean
### containsOnlyLatinCharsAndPunctuation(String data) {#containsOnlyLatinCharsAndPunctuation-java.lang.String-}
```
public static boolean containsOnlyLatinCharsAndPunctuation(String data)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | java.lang.String |  |

**Returns:**
boolean
### toString(TextStyle textStyle) {#toString-com.aspose.note.TextStyle-}
```
public static void toString(TextStyle textStyle)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| textStyle | com.aspose.note.TextStyle |  |


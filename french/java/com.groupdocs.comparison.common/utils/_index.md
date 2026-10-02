---
title: "Utils"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "Classe utilitaire qui fournit des méthodes d'aide communes pouvant être utiles lors de l'utilisation de l'API Comparison."
type: docs
weight: 11
url: /fr/java/com.groupdocs.comparison.common/utils/
---
**Inheritance:**
java.lang.Object
```
public class Utils
```

Classe utilitaire qui fournit des méthodes d'aide communes pouvant être utiles lors de l'utilisation de l'API Comparison.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Utils()](#Utils--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getMethodByTag(Class<?> clazz, String methodTag, boolean isGetter)](#getMethodByTag-java.lang.Class----java.lang.String-boolean-) |  |
|  | [closeStreams(Closeable[] closeables)](#closeStreams-java.io.Closeable...-) | Ferme silencieusement tous les objets fournis en capturant et en journalisant toutes les IOException. |
|
|  | [closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)](#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-) | Ferme les flux spécifiés, en supprimant toutes les exceptions qui surviennent lors de la journalisation ou du traitement des IOException |
|
|  | [isText(String data)](#isText-java.lang.String-) | Vérifie que la chaîne d'entrée ne contient que des caractères autorisés dans une chaîne habituelle de n'importe quelle langue |
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
| Paramètre | Type | Description |
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


Ferme silencieusement tous les objets fournis en capturant et en journalisant toutes les IOException.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | closeables | java.io.Closeable[] | Tout objet implémentant l'interface Closeable, peut être nul |
|

**Returns:**
booléen - vrai si tous les objets closeable ont été fermés sans exception, sinon faux

### closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables) {#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-}
```
public static boolean closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)
```


Ferme les flux spécifiés, en supprimant toutes les exceptions qui surviennent lors de la journalisation ou du traitement des IOException
Si l'un des flux est nul ou rencontre une exception lors de la fermeture, il est ignoré.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | consumer | java.util.function.BiConsumer<java.io.Closeable,java.io.IOException> | Sera appelé pour chaque paire de closeable et IOException lorsque la fermeture lève l'exception, peut être nul |
|
|  | closeables | java.io.Closeable[] | Tout objet implémentant l'interface Closeable, peut être nul |
|

**Returns:**
booléen - vrai si tous les objets closeable ont été fermés sans exception, sinon faux

### isText(String data) {#isText-java.lang.String-}
```
public static boolean isText(String data)
```


Vérifie que la chaîne d'entrée ne contient que des caractères autorisés dans une chaîne habituelle de n'importe quelle langue


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| data | java.lang.String |  |

**Returns:**
boolean
### containsOnlyLatinCharsAndPunctuation(String data) {#containsOnlyLatinCharsAndPunctuation-java.lang.String-}
```
public static boolean containsOnlyLatinCharsAndPunctuation(String data)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| data | java.lang.String |  |

**Returns:**
boolean
### toString(TextStyle textStyle) {#toString-com.aspose.note.TextStyle-}
```
public static void toString(TextStyle textStyle)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| textStyle | com.aspose.note.TextStyle |  |


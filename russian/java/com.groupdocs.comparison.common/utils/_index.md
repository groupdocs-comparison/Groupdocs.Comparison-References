---
title: "Utils"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Вспомогательный класс, предоставляющий общие вспомогательные методы, которые могут быть полезны при использовании Comparison API."
type: docs
weight: 11
url: /ru/java/com.groupdocs.comparison.common/utils/
---
**Inheritance:**
java.lang.Object
```
public class Utils
```

Вспомогательный класс, предоставляющий общие вспомогательные методы, которые могут быть полезны при использовании Comparison API.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Utils()](#Utils--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getMethodByTag(Class<?> clazz, String methodTag, boolean isGetter)](#getMethodByTag-java.lang.Class----java.lang.String-boolean-) |  |
|  | [closeStreams(Closeable[] closeables)](#closeStreams-java.io.Closeable...-) | Тихо закрывает все предоставленные объекты, перехватывая и записывая все IOException. |
|
|  | [closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)](#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-) | Закрывает указанные потоки, подавляя любые исключения, возникающие при записи или обработке IOException |
|
|  | [isText(String data)](#isText-java.lang.String-) | Проверяет, что входная строка содержит только символы, разрешённые в обычных строках любого языка |
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
| Параметр | Тип | Описание |
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


Тихо закрывает все предоставленные объекты, перехватывая и записывая все IOException.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | closeables | java.io.Closeable[] | Любой объект, реализующий интерфейс Closeable, может быть null |
|

**Returns:**
boolean - true, если все объекты closeable были закрыты без исключения, иначе false

### closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables) {#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-}
```
public static boolean closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)
```


Закрывает указанные потоки, подавляя любые исключения, возникающие при записи или обработке IOException
Если любой из потоков равен null или возникает исключение при закрытии, оно игнорируется.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | consumer | java.util.function.BiConsumer<java.io.Closeable,java.io.IOException> | Будет вызван для каждой пары closeable и IOException, когда при закрытии выбрасывается исключение, может быть null |
|
|  | closeables | java.io.Closeable[] | Любой объект, реализующий интерфейс Closeable, может быть null |
|

**Returns:**
boolean - true, если все объекты closeable были закрыты без исключения, иначе false

### isText(String data) {#isText-java.lang.String-}
```
public static boolean isText(String data)
```


Проверяет, что входная строка содержит только символы, разрешённые в обычных строках любого языка


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| data | java.lang.String |  |

**Returns:**
boolean
### containsOnlyLatinCharsAndPunctuation(String data) {#containsOnlyLatinCharsAndPunctuation-java.lang.String-}
```
public static boolean containsOnlyLatinCharsAndPunctuation(String data)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| data | java.lang.String |  |

**Returns:**
boolean
### toString(TextStyle textStyle) {#toString-com.aspose.note.TextStyle-}
```
public static void toString(TextStyle textStyle)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| textStyle | com.aspose.note.TextStyle |  |


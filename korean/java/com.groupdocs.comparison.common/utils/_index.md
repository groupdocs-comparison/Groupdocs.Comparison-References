---
title: "Utils"
second_title: "GroupDocs.Comparison for Java API 참조"
description: "Comparison API를 사용할 때 유용할 수 있는 일반 헬퍼 메서드를 제공하는 유틸리티 클래스."
type: docs
weight: 11
url: /ko/java/com.groupdocs.comparison.common/utils/
---
**Inheritance:**
java.lang.Object
```
public class Utils
```

Comparison API를 사용할 때 유용할 수 있는 일반 헬퍼 메서드를 제공하는 유틸리티 클래스.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Utils()](#Utils--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getMethodByTag(Class<?> clazz, String methodTag, boolean isGetter)](#getMethodByTag-java.lang.Class----java.lang.String-boolean-) |  |
|  | [closeStreams(Closeable[] closeables)](#closeStreams-java.io.Closeable...-) | 제공된 모든 객체를 조용히 닫고 모든 IOException을 포착하여 기록합니다. |
|
|  | [closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)](#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-) | 지정된 스트림을 닫으며, IOException을 기록하거나 처리하는 중 발생하는 모든 예외를 억제합니다. |
|
|  | [isText(String data)](#isText-java.lang.String-) | 입력 문자열이 모든 언어의 일반 문자열에서 허용되는 문자만 포함하는지 확인합니다 |
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
| 매개변수 | 형식 | 설명 |
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


제공된 모든 객체를 조용히 닫고 모든 IOException을 포착하여 기록합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | closeable 객체들 | java.io.Closeable[] | Closeable 인터페이스를 구현하는 객체이며, null일 수 있습니다 |
|

**Returns:**
boolean - 모든 closeable 객체가 예외 없이 닫혔으면 true, 그렇지 않으면 false

### closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables) {#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-}
```
public static boolean closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)
```


지정된 스트림을 닫으며, IOException을 기록하거나 처리하는 중 발생하는 모든 예외를 억제합니다.
스트림 중 하나가 null이거나 닫는 동안 예외가 발생하면 무시됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | consumer | java.util.function.BiConsumer<java.io.Closeable,java.io.IOException> | 닫는 동안 예외가 발생하면 closeable과 IOException의 각 쌍에 대해 호출되며, null일 수 있습니다. |
|
|  | closeable 객체들 | java.io.Closeable[] | Closeable 인터페이스를 구현하는 객체이며, null일 수 있습니다 |
|

**Returns:**
boolean - 모든 closeable 객체가 예외 없이 닫혔으면 true, 그렇지 않으면 false

### isText(String data) {#isText-java.lang.String-}
```
public static boolean isText(String data)
```


입력 문자열이 모든 언어의 일반 문자열에서 허용되는 문자만 포함하는지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | java.lang.String |  |

**Returns:**
boolean
### containsOnlyLatinCharsAndPunctuation(String data) {#containsOnlyLatinCharsAndPunctuation-java.lang.String-}
```
public static boolean containsOnlyLatinCharsAndPunctuation(String data)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | java.lang.String |  |

**Returns:**
boolean
### toString(TextStyle textStyle) {#toString-com.aspose.note.TextStyle-}
```
public static void toString(TextStyle textStyle)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| textStyle | com.aspose.note.TextStyle |  |


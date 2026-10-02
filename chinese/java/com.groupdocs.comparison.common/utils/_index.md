---
title: "Utils"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "提供常用辅助方法的实用类，在使用 Comparison API 时可能有用。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.comparison.common/utils/
---
**Inheritance:**
java.lang.Object
```
public class Utils
```

提供常用辅助方法的实用类，在使用 Comparison API 时可能有用。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Utils()](#Utils--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getMethodByTag(Class<?> clazz, String methodTag, boolean isGetter)](#getMethodByTag-java.lang.Class----java.lang.String-boolean-) |  |
|  | [closeStreams(Closeable[] closeables)](#closeStreams-java.io.Closeable...-) | 安静地关闭所有提供的对象，捕获并记录所有 IOException。 |
|
|  | [closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)](#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-) | 关闭指定的流，抑制在记录或处理 IOException 时发生的任何异常 |
|
|  | [isText(String data)](#isText-java.lang.String-) | 检查输入字符串仅包含任何语言常规字符串中允许的字符 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 类 | java.lang.Class<?> |  |
| 方法标签 | java.lang.String |  |
| 是否为Getter | boolean |  |

**Returns:**
java.util.Optional<java.lang.reflect.Method>
### closeStreams(Closeable[] closeables) {#closeStreams-java.io.Closeable...-}
```
public static boolean closeStreams(Closeable[] closeables)
```


安静地关闭所有提供的对象，捕获并记录所有 IOException。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 可关闭对象 | java.io.Closeable[] | 任何实现 Closeable 接口的对象，可能为 null |
|

**Returns:**
布尔型 - 如果所有可关闭对象均在没有异常的情况下关闭则为 true，否则为 false

### closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables) {#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-}
```
public static boolean closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)
```


关闭指定的流，抑制在记录或处理 IOException 时发生的任何异常
如果任何流为 null 或在关闭时遇到异常，则会被忽略。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 消费者 | java.util.function.BiConsumer<java.io.Closeable,java.io.IOException> | 在关闭抛出异常时，将针对每一对 closeable 和 IOException 调用此方法，可能为 null |
|
|  | 可关闭对象 | java.io.Closeable[] | 任何实现 Closeable 接口的对象，可能为 null |
|

**Returns:**
布尔型 - 如果所有可关闭对象均在没有异常的情况下关闭则为 true，否则为 false

### isText(String data) {#isText-java.lang.String-}
```
public static boolean isText(String data)
```


检查输入字符串仅包含任何语言常规字符串中允许的字符


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | java.lang.String |  |

**Returns:**
boolean
### containsOnlyLatinCharsAndPunctuation(String data) {#containsOnlyLatinCharsAndPunctuation-java.lang.String-}
```
public static boolean containsOnlyLatinCharsAndPunctuation(String data)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | java.lang.String |  |

**Returns:**
boolean
### toString(TextStyle textStyle) {#toString-com.aspose.note.TextStyle-}
```
public static void toString(TextStyle textStyle)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文本样式 | com.aspose.note.TextStyle |  |


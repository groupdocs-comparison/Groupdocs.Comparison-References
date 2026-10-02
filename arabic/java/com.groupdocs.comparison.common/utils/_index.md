---
title: "Utils"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "فئة مساعدة توفر طرق مساعدة شائعة يمكن أن تكون مفيدة عند استخدام واجهة برمجة تطبيقات Comparison."
type: docs
weight: 11
url: /ar/java/com.groupdocs.comparison.common/utils/
---
**Inheritance:**
java.lang.Object
```
public class Utils
```

فئة مساعدة توفر طرق مساعدة شائعة يمكن أن تكون مفيدة عند استخدام واجهة برمجة تطبيقات Comparison.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Utils()](#Utils--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getMethodByTag(Class<?> clazz, String methodTag, boolean isGetter)](#getMethodByTag-java.lang.Class----java.lang.String-boolean-) |  |
|  | [closeStreams(Closeable[] closeables)](#closeStreams-java.io.Closeable...-) | يغلق بهدوء جميع الكائنات المقدمة مع التقاط وتسجيل جميع استثناءات IOException. |
|
|  | [closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)](#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-) | يغلق التدفقات المحددة، مع قمع أي استثناءات تحدث أثناء تسجيل أو معالجة استثناء IOException. |
|
|  | [isText(String data)](#isText-java.lang.String-) | يتحقق من أن سلسلة الإدخال تحتوي فقط على الأحرف المسموح بها في السلسلة العادية لأي لغة |
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
| معامل | نوع | الوصف |
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


يغلق بهدوء جميع الكائنات المقدمة مع التقاط وتسجيل جميع استثناءات IOException.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | closeables | java.io.Closeable[] | أي كائن يطبق واجهة Closeable، قد يكون فارغًا (null) |
|

**Returns:**
منطقي - true إذا تم إغلاق جميع الكائنات القابلة للإغلاق دون استثناء، وإلا false

### closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables) {#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-}
```
public static boolean closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)
```


يغلق التدفقات المحددة، مع قمع أي استثناءات تحدث أثناء تسجيل أو معالجة استثناء IOException.
إذا كان أي من التدفقات null أو واجه استثناءً أثناء الإغلاق، يتم تجاهله.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | consumer | java.util.function.BiConsumer<java.io.Closeable,java.io.IOException> | سيتم استدعاؤه لكل زوج من closeable و IOException عندما يرمي الإغلاق استثناءً، وقد يكون null |
|
|  | closeables | java.io.Closeable[] | أي كائن يطبق واجهة Closeable، قد يكون فارغًا (null) |
|

**Returns:**
منطقي - true إذا تم إغلاق جميع الكائنات القابلة للإغلاق دون استثناء، وإلا false

### isText(String data) {#isText-java.lang.String-}
```
public static boolean isText(String data)
```


يتحقق من أن سلسلة الإدخال تحتوي فقط على الأحرف المسموح بها في السلسلة العادية لأي لغة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| data | java.lang.String |  |

**Returns:**
boolean
### containsOnlyLatinCharsAndPunctuation(String data) {#containsOnlyLatinCharsAndPunctuation-java.lang.String-}
```
public static boolean containsOnlyLatinCharsAndPunctuation(String data)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| data | java.lang.String |  |

**Returns:**
boolean
### toString(TextStyle textStyle) {#toString-com.aspose.note.TextStyle-}
```
public static void toString(TextStyle textStyle)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| textStyle | com.aspose.note.TextStyle |  |


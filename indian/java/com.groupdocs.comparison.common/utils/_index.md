---
title: "उपयोगिताएँ"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "उपयोगी क्लास जो सामान्य हेल्पर मेथड्स प्रदान करती है, जो Comparison API का उपयोग करते समय उपयोगी हो सकते हैं।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.comparison.common/utils/
---
**Inheritance:**
java.lang.Object
```
public class Utils
```

उपयोगी क्लास जो सामान्य हेल्पर मेथड्स प्रदान करती है, जो Comparison API का उपयोग करते समय उपयोगी हो सकते हैं।

## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Utils()](#Utils--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getMethodByTag(Class<?> clazz, String methodTag, boolean isGetter)](#getMethodByTag-java.lang.Class----java.lang.String-boolean-) |  |
|  | [closeStreams(Closeable[] closeables)](#closeStreams-java.io.Closeable...-) | सभी प्रदान किए गए ऑब्जेक्ट्स को चुपचाप बंद करता है, सभी IOException को पकड़ता और लॉग करता है। |
|
|  | [closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)](#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-) | निर्दिष्ट स्ट्रीम्स को बंद करता है, किसी भी अपवाद को दबाते हुए जो IOException को लॉग या प्रोसेस करते समय होते हैं |
|
|  | [isText(String data)](#isText-java.lang.String-) | जाँचता है कि इनपुट स्ट्रिंग में केवल उन अक्षरों का उपयोग किया गया है जो किसी भी भाषा की सामान्य स्ट्रिंग में अनुमति हैं |
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
| पैरामीटर | प्रकार | विवरण |
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


सभी प्रदान किए गए ऑब्जेक्ट्स को चुपचाप बंद करता है, सभी IOException को पकड़ता और लॉग करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | closeables | java.io.Closeable[] | कोई भी ऑब्जेक्ट जो Closeable इंटरफ़ेस को लागू करता है, null हो सकता है |
|

**Returns:**
boolean - true यदि सभी closeable ऑब्जेक्ट बिना अपवाद के बंद हो गए हों, अन्यथा false

### closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables) {#closeStreams-java.util.function.BiConsumer-java.io.Closeable-java.io.IOException--java.io.Closeable...-}
```
public static boolean closeStreams(BiConsumer<Closeable,IOException> consumer, Closeable[] closeables)
```


निर्दिष्ट स्ट्रीम्स को बंद करता है, किसी भी अपवाद को दबाते हुए जो IOException को लॉग या प्रोसेस करते समय होते हैं
यदि किसी भी स्ट्रीम का मान null है या बंद करते समय कोई अपवाद उत्पन्न होता है, तो उसे अनदेखा कर दिया जाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | consumer | java.util.function.BiConsumer<java.io.Closeable,java.io.IOException> | जब बंद करने पर अपवाद फेंका जाता है तो प्रत्येक closeable और IOException की जोड़ी के लिए इसे कॉल किया जाएगा, यह null भी हो सकता है |
|
|  | closeables | java.io.Closeable[] | कोई भी ऑब्जेक्ट जो Closeable इंटरफ़ेस को लागू करता है, null हो सकता है |
|

**Returns:**
boolean - true यदि सभी closeable ऑब्जेक्ट बिना अपवाद के बंद हो गए हों, अन्यथा false

### isText(String data) {#isText-java.lang.String-}
```
public static boolean isText(String data)
```


जाँचता है कि इनपुट स्ट्रिंग में केवल उन अक्षरों का उपयोग किया गया है जो किसी भी भाषा की सामान्य स्ट्रिंग में अनुमति हैं


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | java.lang.String |  |

**Returns:**
boolean
### containsOnlyLatinCharsAndPunctuation(String data) {#containsOnlyLatinCharsAndPunctuation-java.lang.String-}
```
public static boolean containsOnlyLatinCharsAndPunctuation(String data)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | java.lang.String |  |

**Returns:**
boolean
### toString(TextStyle textStyle) {#toString-com.aspose.note.TextStyle-}
```
public static void toString(TextStyle textStyle)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| textStyle | com.aspose.note.TextStyle |  |


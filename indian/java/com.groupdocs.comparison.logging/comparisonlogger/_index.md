---
title: "ComparisonLogger"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "लॉगिंग मेथड्स को लागू करता है और एकीकृत या उपयोगकर्ता-परिभाषित लॉगर को कॉन्फ़िगर करने का तरीका प्रदान करता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.comparison.logging/comparisonlogger/
---
**Inheritance:**
java.lang.Object
```
public class ComparisonLogger
```

लॉगिंग मेथड्स को लागू करता है और एकीकृत या उपयोगकर्ता-परिभाषित लॉगर को कॉन्फ़िगर करने का तरीका प्रदान करता है।


यह क्लास एकीकृत या कस्टम लॉगर सेट करने और लॉग संदेश लिखने की अनुमति देती है।


उदाहरण उपयोग:

````

 ComparisonLogger.setLogger(new com.groupdocs.comparison.logging.ConsoleLogger(false, true, true, true));
 ComparisonLogger.warning(exceptionObject, "Warning message with parameters: {}, {}", "parameter1", 2);
 
````


## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | ट्रेस संदेश को पूर्व-कॉन्फ़िगर किए गए लॉगर में लिखता है। |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | ट्रेस संदेश, स्टैक ट्रेस और अपवाद से प्राप्त संदेश को पूर्व-कॉन्फ़िगर किए गए लॉगर में लिखता है। |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | जाँचता है कि क्या ट्रेस लॉगिंग पूर्व-कॉन्फ़िगर किए गए लॉगर में सक्षम है। |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | डिबग संदेश को पूर्व-कॉन्फ़िगर किए गए लॉगर में लिखता है। |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | डिबग संदेश, स्टैक ट्रेस और अपवाद से प्राप्त संदेश को पूर्व-कॉन्फ़िगर किए गए लॉगर में लिखता है। |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | जाँचता है कि क्या डिबग लॉगिंग पूर्व-कॉन्फ़िगर किए गए लॉगर में सक्षम है। |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | चेतावनी संदेश को पूर्व-कॉन्फ़िगर किए गए लॉगर में लिखता है। |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | चेतावनी संदेश, स्टैक ट्रेस और अपवाद से प्राप्त संदेश को पूर्व-कॉन्फ़िगर किए गए लॉगर में लिखता है। |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | जाँचता है कि क्या चेतावनी लॉगिंग पूर्व-कॉन्फ़िगर किए गए लॉगर में सक्षम है। |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | त्रुटि संदेश को पूर्व-कॉन्फ़िगर किए गए लॉगर में लिखता है। |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | त्रुटि संदेश, स्टैक ट्रेस और अपवाद से प्राप्त संदेश को पूर्व-कॉन्फ़िगर किए गए लॉगर में लिखता है। |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | जाँचता है कि क्या त्रुटि लॉगिंग पूर्व-कॉन्फ़िगर किए गए लॉगर में सक्षम है। |
|
|  | [getLogger()](#getLogger--) | पूर्व-कॉन्फ़िगर किया गया लॉगर प्राप्त करता है जिसका उपयोग सभी प्रकार के लॉग लिखने के लिए किया जाएगा। |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | लॉगर सेट करता है जिसका उपयोग सभी प्रकार के लॉग लिखने के लिए किया जाएगा। |
|
### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


ट्रेस संदेश को पूर्व-कॉन्फ़िगर किए गए लॉगर में लिखता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | message | java.lang.String | संदेश, यदि null है तो व्यवहार लॉगर पर निर्भर करता है |
|
|  | arguments | java.lang.Object[] | संदेश में सम्मिलित करने के लिए तर्क, यदि null है तो व्यवहार लॉगर पर निर्भर करता है |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
```


ट्रेस संदेश, स्टैक ट्रेस और अपवाद से प्राप्त संदेश को पूर्व-कॉन्फ़िगर किए गए लॉगर में लिखता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | वह throwable ऑब्जेक्ट जो स्टैक ट्रेस प्राप्त करने के लिए उपयोग किया जाएगा, यदि null है तो व्यवहार लॉगर पर निर्भर करता है |
|
|  | message | java.lang.String | संदेश, यदि null है तो व्यवहार लॉगर पर निर्भर करता है |
|
|  | arguments | java.lang.Object[] | संदेश में सम्मिलित करने के लिए तर्क, यदि null है तो व्यवहार लॉगर पर निर्भर करता है |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public static boolean isTraceEnabled()
```


जाँचता है कि क्या ट्रेस लॉगिंग पूर्व-कॉन्फ़िगर किए गए लॉगर में सक्षम है।


**Returns:**
boolean - true यदि पूर्व-कॉन्फ़िगर किए गए लॉगर में सक्षम है, अन्यथा false

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


डिबग संदेश को पूर्व-कॉन्फ़िगर किए गए लॉगर में लिखता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | message | java.lang.String | संदेश, यदि null है तो व्यवहार लॉगर पर निर्भर करता है |
|
|  | arguments | java.lang.Object[] | संदेश में सम्मिलित करने के लिए तर्क, यदि null है तो व्यवहार लॉगर पर निर्भर करता है |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
```


डिबग संदेश, स्टैक ट्रेस और अपवाद से प्राप्त संदेश को पूर्व-कॉन्फ़िगर किए गए लॉगर में लिखता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | वह throwable ऑब्जेक्ट जो स्टैक ट्रेस प्राप्त करने के लिए उपयोग किया जाएगा, यदि null है तो व्यवहार लॉगर पर निर्भर करता है |
|
|  | message | java.lang.String | संदेश, यदि null है तो व्यवहार लॉगर पर निर्भर करता है |
|
|  | arguments | java.lang.Object[] | संदेश में सम्मिलित करने के लिए तर्क, यदि null है तो व्यवहार लॉगर पर निर्भर करता है |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public static boolean isDebugEnabled()
```


जाँचता है कि क्या डिबग लॉगिंग पूर्व-कॉन्फ़िगर किए गए लॉगर में सक्षम है।


**Returns:**
boolean - true यदि पूर्व-कॉन्फ़िगर किए गए लॉगर में सक्षम है, अन्यथा false

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


चेतावनी संदेश को पूर्व-कॉन्फ़िगर किए गए लॉगर में लिखता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | message | java.lang.String | संदेश, यदि null है तो व्यवहार लॉगर पर निर्भर करता है |
|
|  | arguments | java.lang.Object[] | संदेश में सम्मिलित करने के लिए तर्क, यदि null है तो व्यवहार लॉगर पर निर्भर करता है |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
```


चेतावनी संदेश, स्टैक ट्रेस और अपवाद से प्राप्त संदेश को पूर्व-कॉन्फ़िगर किए गए लॉगर में लिखता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | वह throwable ऑब्जेक्ट जो स्टैक ट्रेस प्राप्त करने के लिए उपयोग किया जाएगा, यदि null है तो व्यवहार लॉगर पर निर्भर करता है |
|
|  | message | java.lang.String | संदेश, यदि null है तो व्यवहार लॉगर पर निर्भर करता है |
|
|  | arguments | java.lang.Object[] | संदेश में सम्मिलित करने के लिए तर्क, यदि null है तो व्यवहार लॉगर पर निर्भर करता है |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public static boolean isWarningEnabled()
```


जाँचता है कि क्या चेतावनी लॉगिंग पूर्व-कॉन्फ़िगर किए गए लॉगर में सक्षम है।


**Returns:**
boolean - true यदि पूर्व-कॉन्फ़िगर किए गए लॉगर में सक्षम है, अन्यथा false

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


त्रुटि संदेश को पूर्व-कॉन्फ़िगर किए गए लॉगर में लिखता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | message | java.lang.String | संदेश, यदि null है तो व्यवहार लॉगर पर निर्भर करता है |
|
|  | arguments | java.lang.Object[] | संदेश में सम्मिलित करने के लिए तर्क, यदि null है तो व्यवहार लॉगर पर निर्भर करता है |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
```


त्रुटि संदेश, स्टैक ट्रेस और अपवाद से प्राप्त संदेश को पूर्व-कॉन्फ़िगर किए गए लॉगर में लिखता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | वह throwable ऑब्जेक्ट जो स्टैक ट्रेस प्राप्त करने के लिए उपयोग किया जाएगा, यदि null है तो व्यवहार लॉगर पर निर्भर करता है |
|
|  | message | java.lang.String | संदेश, यदि null है तो व्यवहार लॉगर पर निर्भर करता है |
|
|  | arguments | java.lang.Object[] | संदेश में सम्मिलित करने के लिए तर्क, यदि null है तो व्यवहार लॉगर पर निर्भर करता है |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public static boolean isErrorEnabled()
```


जाँचता है कि क्या त्रुटि लॉगिंग पूर्व-कॉन्फ़िगर किए गए लॉगर में सक्षम है।


**Returns:**
boolean - true यदि पूर्व-कॉन्फ़िगर किए गए लॉगर में सक्षम है, अन्यथा false

### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


पूर्व-कॉन्फ़िगर किया गया लॉगर प्राप्त करता है जिसका उपयोग सभी प्रकार के लॉग लिखने के लिए किया जाएगा।


**Returns:**
com.groupdocs.foundation.logging.ILogger - लॉगर

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


लॉगर सेट करता है जिसका उपयोग सभी प्रकार के लॉग लिखने के लिए किया जाएगा।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | लॉगर | com.groupdocs.foundation.logging.ILogger | लॉगर |
|


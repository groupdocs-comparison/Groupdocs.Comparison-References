---
title: "FileLogger"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "फ़ाइल में लॉग लिखने वाला लॉगर।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.comparison.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

फ़ाइल में लॉग लिखने वाला लॉगर।


के साथ मिलकर उपयोग किया जाना चाहिए [ComparisonLogger](../../com.groupdocs.comparison.logging/comparisonlogger).


उदाहरण उपयोग:

````

 ComparisonLogger.setLogger(new FileLogger("/path/to/file.log.txt", false, true, true, true));
 
````


## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [FileLogger(String filePath)](#FileLogger-java.lang.String-) | फ़ाइल पथ के साथ FileLogger क्लास का एक नया उदाहरण प्रारंभ करता है। |
|
|  | [FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | फ़ाइल पथ और लॉग स्तर कॉन्फ़िगरेशन के साथ FileLogger क्लास का एक नया उदाहरण प्रारंभ करता है। |
|
## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | फ़ाइल में ट्रेस संदेश लिखता है। |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | फ़ाइल में ट्रेस संदेश लिखता है। |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | जाँचता है कि ट्रेस लॉगिंग सक्षम है या नहीं। |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | फ़ाइल में डिबग संदेश लिखता है। |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | फ़ाइल में डिबग संदेश लिखता है। |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | जाँचता है कि डिबग लॉगिंग सक्षम है या नहीं। |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | फ़ाइल में चेतावनी संदेश लिखता है। |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | फ़ाइल में चेतावनी संदेश लिखता है। |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | जाँचता है कि चेतावनी लॉगिंग सक्षम है या नहीं। |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | फ़ाइल में त्रुटि संदेश लिखता है। |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | फ़ाइल में त्रुटि संदेश लिखता है। |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | जाँचता है कि त्रुटि लॉगिंग सक्षम है या नहीं। |
|
### FileLogger(String filePath) {#FileLogger-java.lang.String-}
```
public FileLogger(String filePath)
```


फ़ाइल पथ के साथ FileLogger क्लास का एक नया उदाहरण प्रारंभ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | लॉग लिखने के लिए उपयोग की जाने वाली फ़ाइल का पथ |
|

### FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String filePath, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


फ़ाइल पथ और लॉग स्तर कॉन्फ़िगरेशन के साथ FileLogger क्लास का एक नया उदाहरण प्रारंभ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | लॉग लिखने के लिए उपयोग की जाने वाली फ़ाइल का पथ |
|
|  | isTraceEnabled | boolean | ट्रेस लॉगिंग को सक्षम करने के लिए True, अन्यथा false |
|
|  | isDebugEnabled | boolean | डिबग लॉगिंग को सक्षम करने के लिए True, अन्यथा false |
|
|  | isWarningEnabled | boolean | वॉर्निंग लॉगिंग को सक्षम करने के लिए True, अन्यथा false |
|
|  | isErrorEnabled | boolean | एरर लॉगिंग को सक्षम करने के लिए True, अन्यथा false |
|

### MESSAGE {#MESSAGE}
```
public static final String MESSAGE
```


### EXCEPTION {#EXCEPTION}
```
public static final String EXCEPTION
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public void trace(String message, Object[] arguments)
```


फ़ाइल में ट्रेस संदेश लिखता है।


ट्रेस लॉग संदेश एप्लिकेशन प्रवाह के बारे में अधिकतम विस्तृत जानकारी प्रदान करते हैं।
संदेश में एक या कुछ {} हो सकते हैं जिन्हें संबंधित तर्कों द्वारा प्रतिस्थापित किया जाएगा।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | message | java.lang.String | संदेश। |
|
|  | arguments | java.lang.Object[] | तर्क, संदेश में {} को पास करने के क्रम में प्रतिस्थापित करते हैं, null को 'null' के रूप में लिखा जाएगा। |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


फ़ाइल में ट्रेस संदेश लिखता है।


ट्रेस लॉग संदेश एप्लिकेशन प्रवाह के बारे में अधिकतम विस्तृत जानकारी प्रदान करते हैं।
संदेश में एक या कुछ {} हो सकते हैं जिन्हें संबंधित तर्कों द्वारा प्रतिस्थापित किया जाएगा।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | वह throwable ऑब्जेक्ट जो स्टैकट्रेस प्राप्त करने के लिए उपयोग किया जाएगा |
|
|  | message | java.lang.String | संदेश। |
|
|  | arguments | java.lang.Object[] | तर्क, संदेश में {} को पास करने के क्रम में प्रतिस्थापित करते हैं, null को 'null' के रूप में लिखा जाएगा। |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


जाँचता है कि ट्रेस लॉगिंग सक्षम है या नहीं।


**Returns:**
boolean - सक्षम होने पर true, अन्यथा false

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


फ़ाइल में डिबग संदेश लिखता है।


डिबग लॉग संदेश एप्लिकेशन प्रवाह में विभिन्न प्रक्रियाओं के बारे में जानकारी प्रदान करते हैं।
संदेश में एक या कुछ {} हो सकते हैं जिन्हें संबंधित तर्कों द्वारा प्रतिस्थापित किया जाएगा।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | message | java.lang.String | संदेश। |
|
|  | arguments | java.lang.Object[] | तर्क, संदेश में {} को पास करने के क्रम में प्रतिस्थापित करते हैं, null को 'null' के रूप में लिखा जाएगा। |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


फ़ाइल में डिबग संदेश लिखता है।


डिबग लॉग संदेश एप्लिकेशन प्रवाह में विभिन्न प्रक्रियाओं के बारे में जानकारी प्रदान करते हैं।
संदेश में एक या कुछ {} हो सकते हैं जिन्हें संबंधित तर्कों द्वारा प्रतिस्थापित किया जाएगा।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | वह throwable ऑब्जेक्ट जो स्टैकट्रेस प्राप्त करने के लिए उपयोग किया जाएगा |
|
|  | message | java.lang.String | संदेश। |
|
|  | arguments | java.lang.Object[] | तर्क, संदेश में {} को पास करने के क्रम में प्रतिस्थापित करते हैं, null को 'null' के रूप में लिखा जाएगा। |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


जाँचता है कि डिबग लॉगिंग सक्षम है या नहीं।


**Returns:**
boolean - सक्षम होने पर true, अन्यथा false

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


फ़ाइल में चेतावनी संदेश लिखता है।


वॉर्निंग लॉग संदेश एप्लिकेशन प्रवाह में अप्रत्याशित और पुनर्प्राप्ति योग्य घटनाओं के बारे में जानकारी प्रदान करते हैं।
संदेश में एक या कुछ {} हो सकते हैं जिन्हें संबंधित तर्कों द्वारा प्रतिस्थापित किया जाएगा।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | message | java.lang.String | संदेश। |
|
|  | arguments | java.lang.Object[] | तर्क, संदेश में {} को पास करने के क्रम में प्रतिस्थापित करते हैं, null को 'null' के रूप में लिखा जाएगा। |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


फ़ाइल में चेतावनी संदेश लिखता है।


वॉर्निंग लॉग संदेश एप्लिकेशन प्रवाह में अप्रत्याशित और पुनर्प्राप्ति योग्य घटनाओं के बारे में जानकारी प्रदान करते हैं।
संदेश में एक या कुछ {} हो सकते हैं जिन्हें संबंधित तर्कों द्वारा प्रतिस्थापित किया जाएगा।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | वह throwable ऑब्जेक्ट जो स्टैकट्रेस प्राप्त करने के लिए उपयोग किया जाएगा |
|
|  | message | java.lang.String | संदेश। |
|
|  | arguments | java.lang.Object[] | तर्क, संदेश में {} को पास करने के क्रम में प्रतिस्थापित करते हैं, null को 'null' के रूप में लिखा जाएगा। |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


जाँचता है कि चेतावनी लॉगिंग सक्षम है या नहीं।


**Returns:**
boolean - सक्षम होने पर true, अन्यथा false

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


फ़ाइल में त्रुटि संदेश लिखता है।


एरर लॉग संदेश एप्लिकेशन प्रवाह में अपरिवर्तनीय घटनाओं के बारे में जानकारी प्रदान करते हैं।
संदेश में एक या कुछ {} हो सकते हैं जिन्हें संबंधित तर्कों द्वारा प्रतिस्थापित किया जाएगा।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | message | java.lang.String | संदेश। |
|
|  | arguments | java.lang.Object[] | तर्क, संदेश में {} को पास करने के क्रम में प्रतिस्थापित करते हैं, null को 'null' के रूप में लिखा जाएगा। |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


फ़ाइल में त्रुटि संदेश लिखता है।


एरर लॉग संदेश एप्लिकेशन प्रवाह में अपरिवर्तनीय घटनाओं के बारे में जानकारी प्रदान करते हैं।
संदेश में एक या कुछ {} हो सकते हैं जिन्हें संबंधित तर्कों द्वारा प्रतिस्थापित किया जाएगा।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | वह throwable ऑब्जेक्ट जो स्टैकट्रेस प्राप्त करने के लिए उपयोग किया जाएगा |
|
|  | message | java.lang.String | संदेश। |
|
|  | arguments | java.lang.Object[] | तर्क, संदेश में {} को पास करने के क्रम में प्रतिस्थापित करते हैं, null को 'null' के रूप में लिखा जाएगा। |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


जाँचता है कि त्रुटि लॉगिंग सक्षम है या नहीं।


**Returns:**
boolean - सक्षम होने पर true, अन्यथा false


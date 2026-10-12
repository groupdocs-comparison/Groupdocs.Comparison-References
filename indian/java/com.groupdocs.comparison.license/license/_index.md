---
title: "लाइसेंस"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "License क्लास GroupDocs.Comparison के लिए लाइसेंस सेट करने और लागू करने के मेथड प्रदान करती है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.comparison.license/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

License क्लास GroupDocs.Comparison के लिए लाइसेंस सेट करने और लागू करने के मेथड प्रदान करती है।


यह आपको लागू लाइसेंस के आधार पर लाइब्रेरी की विशिष्ट सुविधाओं को सक्षम या अक्षम करने की अनुमति देता है।

* More about GroupDocs.Comparison licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/comparisonjava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Comparison)


उदाहरण उपयोग:

````

 final License license = new License();
 license.setLicense("GroupDocs.License.lic");
 
````


## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [License()](#License--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [isValidLicense()](#isValidLicense--) | लाइसेंस सेट किया गया है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
|
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | इनपुट स्ट्रीम का उपयोग करके Comparison के लिए लाइसेंस सेट करता है। |
|
|  | [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | लाइसेंस फ़ाइल पथ का उपयोग करके Comparison के लिए लाइसेंस सेट करता है। |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | लाइसेंस फ़ाइल पथ का उपयोग करके Comparison के लिए लाइसेंस सेट करता है। |
|
### License() {#License--}
```
public License()
```


### isValidLicense() {#isValidLicense--}
```
public static boolean isValidLicense()
```


लाइसेंस सेट किया गया है या नहीं, यह दर्शाने वाला मान प्राप्त करता है।


**Returns:**
बूलियन - यदि लाइसेंस सफलतापूर्वक सेट किया गया हो तो true, अन्यथा false

### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


इनपुट स्ट्रीम का उपयोग करके Comparison के लिए लाइसेंस सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | लाइसेंस स्ट्रीम, null लाइसेंस को अनसेट करता है। |
|

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


लाइसेंस फ़ाइल पथ का उपयोग करके Comparison के लिए लाइसेंस सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | licensePath | java.nio.file.Path | लाइसेंस फ़ाइल पथ |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


लाइसेंस फ़ाइल पथ का उपयोग करके Comparison के लिए लाइसेंस सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | licensePath | java.lang.String | लाइसेंस फ़ाइल पथ |
|


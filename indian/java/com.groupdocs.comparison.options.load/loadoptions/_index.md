---
title: "LoadOptions"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "दस्तावेज़ लोड करते समय अतिरिक्त विकल्प निर्दिष्ट करने की अनुमति देता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.comparison.options.load/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

दस्तावेज़ लोड करते समय अतिरिक्त विकल्प निर्दिष्ट करने की अनुमति देता है।


उदाहरण उपयोग:

````

 final LoadOptions loadOptions = new LoadOptions();
 loadOptions.setPassword("passw");
 loadOptions.setFileType(FileType.PDF);

 try (Comparer comparer = new Comparer(sourceFile, loadOptions)) {
    comparer.add(targetFile);

    comparer.compare(resultFile);
 }
 
````


## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | LoadOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [LoadOptions(boolean isLoadText)](#LoadOptions-boolean-) | LoadOptions क्लास का नया इंस्टेंस एक फ़्लैग के साथ प्रारंभ करता है, जिसका अर्थ है कि इनपुट स्ट्रिंग तुलना के लिए टेक्स्ट है, पथ नहीं। |
|
|  | [LoadOptions(String password)](#LoadOptions-java.lang.String-) | LoadOptions क्लास का नया इंस्टेंस दस्तावेज़ लोड करने के लिए पासवर्ड के साथ प्रारंभ करता है। |
|
|  | [LoadOptions(boolean isLoadText, String password)](#LoadOptions-boolean-java.lang.String-) | LoadOptions क्लास का नया इंस्टेंस एक फ़्लैग के साथ प्रारंभ करता है, जिसका अर्थ है कि इनपुट स्ट्रिंग तुलना के लिए टेक्स्ट है और दस्तावेज़ लोड करने के लिए पासवर्ड है। |
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.comparison.result.FileType-) | LoadOptions क्लास का नया इंस्टेंस फ़ाइल के प्रकार के साथ प्रारंभ करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [isLoadText()](#isLoadText--) | फ़्लैग प्राप्त करता है जो दर्शाता है कि स्ट्रिंग जो [Comparer](../../com.groupdocs.comparison/comparer) कंस्ट्रक्टर या [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) मेथड को पास की गई है, वह तुलना टेक्स्ट है, फ़ाइल पाथ नहीं (केवल टेक्स्ट तुलना के लिए)। |
|
|  | [setLoadText(boolean value)](#setLoadText-boolean-) | फ़्लैग सेट करता है जो दर्शाता है कि स्ट्रिंग जो [Comparer](../../com.groupdocs.comparison/comparer) कंस्ट्रक्टर या [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) मेथड को पास की गई है, वह तुलना टेक्स्ट है, फ़ाइल पाथ नहीं (केवल टेक्स्ट तुलना के लिए)। |
|
|  | [getPassword()](#getPassword--) | दस्तावेज़ लोड करने के लिए उपयोग किया जाने वाला पासवर्ड प्राप्त करता है। |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | दस्तावेज़ लोड करने के लिए उपयोग किया जाने वाला पासवर्ड सेट करता है। |
|
|  | [getFontDirectories()](#getFontDirectories--) | दस्तावेज़ लोड करने के लिए फ़ॉन्ट फ़ाइलें जहाँ रखी गई हैं, उन निर्देशिकाओं की सूची प्राप्त करता है। |
|
|  | [setFontDirectories(List<String> value)](#setFontDirectories-java.util.List-java.lang.String--) | दस्तावेज़ लोड करने के लिए फ़ॉन्ट फ़ाइलें जहाँ रखी गई हैं, उन निर्देशिकाओं की सूची सेट करता है। |
|
|  | [getFileType()](#getFileType--) | लोड हो रही फ़ाइल के प्रकार को प्राप्त करता है। |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | लोड हो रही फ़ाइल का प्रकार सेट करता है। |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


LoadOptions क्लास का नया इंस्टेंस प्रारंभ करता है।


### LoadOptions(boolean isLoadText) {#LoadOptions-boolean-}
```
public LoadOptions(boolean isLoadText)
```


LoadOptions क्लास का नया इंस्टेंस एक फ़्लैग के साथ प्रारंभ करता है, जिसका अर्थ है कि इनपुट स्ट्रिंग तुलना के लिए टेक्स्ट है, पथ नहीं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | isLoadText | boolean | फ़्लैग जो दर्शाता है कि इनपुट स्ट्रिंग तुलना के लिए पाठ है, पथ नहीं। |
|

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


LoadOptions क्लास का नया इंस्टेंस दस्तावेज़ लोड करने के लिए पासवर्ड के साथ प्रारंभ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | पासवर्ड | java.lang.String | दस्तावेज़ लोड करने के लिए पासवर्ड |
|

### LoadOptions(boolean isLoadText, String password) {#LoadOptions-boolean-java.lang.String-}
```
public LoadOptions(boolean isLoadText, String password)
```


LoadOptions क्लास का नया इंस्टेंस एक फ़्लैग के साथ प्रारंभ करता है, जिसका अर्थ है कि इनपुट स्ट्रिंग तुलना के लिए टेक्स्ट है और दस्तावेज़ लोड करने के लिए पासवर्ड है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | isLoadText | boolean | फ़्लैग जो दर्शाता है कि इनपुट स्ट्रिंग तुलना के लिए पाठ है, पथ नहीं। |
|
|  | पासवर्ड | java.lang.String | दस्तावेज़ लोड करने के लिए पासवर्ड |
|

### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.comparison.result.FileType-}
```
public LoadOptions(FileType fileType)
```


LoadOptions क्लास का नया इंस्टेंस फ़ाइल के प्रकार के साथ प्रारंभ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | फ़ाइल का प्रकार |
|

### isLoadText() {#isLoadText--}
```
public boolean isLoadText()
```


फ़्लैग प्राप्त करता है जो दर्शाता है कि स्ट्रिंग जो [Comparer](../../com.groupdocs.comparison/comparer) कंस्ट्रक्टर या [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) मेथड को पास की गई है, वह तुलना टेक्स्ट है, फ़ाइल पाथ नहीं (केवल टेक्स्ट तुलना के लिए)।


**Returns:**
boolean - true यदि इनपुट स्ट्रिंग तुलना के लिए पाठ है, अन्यथा false

### setLoadText(boolean value) {#setLoadText-boolean-}
```
public void setLoadText(boolean value)
```


फ़्लैग सेट करता है जो दर्शाता है कि स्ट्रिंग जो [Comparer](../../com.groupdocs.comparison/comparer) कंस्ट्रक्टर या [Comparer.add(String)](../../com.groupdocs.comparison/comparer#add-String-) मेथड को पास की गई है, वह तुलना टेक्स्ट है, फ़ाइल पाथ नहीं (केवल टेक्स्ट तुलना के लिए)।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | true यदि इनपुट स्ट्रिंग तुलना के लिए पाठ है, अन्यथा false |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


दस्तावेज़ लोड करने के लिए उपयोग किया जाने वाला पासवर्ड प्राप्त करता है।


**Returns:**
java.lang.String - दस्तावेज़ लोड करने के लिए पासवर्ड

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


दस्तावेज़ लोड करने के लिए उपयोग किया जाने वाला पासवर्ड सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | दस्तावेज़ लोड करने के लिए पासवर्ड |
|

### getFontDirectories() {#getFontDirectories--}
```
public List<String> getFontDirectories()
```


दस्तावेज़ लोड करने के लिए फ़ॉन्ट फ़ाइलें जहाँ रखी गई हैं, उन निर्देशिकाओं की सूची प्राप्त करता है।


**Returns:**
java.util.List<java.lang.String> - फ़ॉन्ट फ़ाइलों वाले निर्देशिकाओं की सूची

### setFontDirectories(List<String> value) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> value)
```


दस्तावेज़ लोड करने के लिए फ़ॉन्ट फ़ाइलें जहाँ रखी गई हैं, उन निर्देशिकाओं की सूची सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.util.List<java.lang.String> | फ़ॉन्ट फ़ाइलों वाले निर्देशिकाओं की सूची |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


लोड हो रही फ़ाइल के प्रकार को प्राप्त करता है।


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType value)
```


लोड हो रही फ़ाइल का प्रकार सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.comparison.result/filetype) | फ़ाइल का प्रकार |
|


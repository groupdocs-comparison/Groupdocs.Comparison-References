---
title: "SaveOptions"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "दस्तावेज़ को सहेजते समय अतिरिक्त विकल्प निर्दिष्ट करने की अनुमति देता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.comparison.options.save/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

दस्तावेज़ को सहेजते समय अतिरिक्त विकल्प निर्दिष्ट करने की अनुमति देता है।


उदाहरण उपयोग:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    final SaveOptions saveOptions = new SaveOptions();
    saveOptions.setPassword("passw");

    comparer.compare(resultFile, saveOptions);
 }
 
````


## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [SaveOptions()](#SaveOptions--) | SaveOptions क्लास का एक नया उदाहरण प्रारंभ करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getCloneMetadataType()](#getCloneMetadataType--) | मेटाडेटा सहेजने वाले परिणाम दस्तावेज़ को प्रोसेस करने की रणनीति प्राप्त करता है। |
|
|  | [setCloneMetadataType(MetadataType value)](#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-) | मेटाडेटा सहेजने वाले परिणाम दस्तावेज़ को प्रोसेस करने की रणनीति सेट करता है। |
|
|  | [getFileAuthorMetadata()](#getFileAuthorMetadata--) | जब [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) को [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR) पर सेट किया जाता है, तब परिणाम दस्तावेज़ में सेट किया जाने वाला मेटाडेटा ऑब्जेक्ट प्राप्त करता है। |
|
|  | [setFileAuthorMetadata(FileAuthorMetadata value)](#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-) | जब [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) को [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR) पर सेट किया जाता है, तब परिणाम दस्तावेज़ में सेट किया जाना चाहिए ऐसा मेटाडेटा ऑब्जेक्ट सेट करता है। |
|
|  | [getPassword()](#getPassword--) | परिणाम दस्तावेज़ के लिए पासवर्ड प्राप्त करता है। |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | परिणाम दस्तावेज़ के लिए पासवर्ड सेट करता है। |
|
|  | [getFolderPath()](#getFolderPath--) | परिणाम छवियों को सहेजने के लिए फ़ोल्डर पथ प्राप्त करता है। |
|
|  | [setFolderPath(String value)](#setFolderPath-java.lang.String-) | परिणाम छवियों को सहेजने के लिए फ़ोल्डर पथ सेट करता है। |
|
|  | [setFolderPath(Path value)](#setFolderPath-java.nio.file.Path-) | परिणाम छवियों को सहेजने के लिए फ़ोल्डर पथ सेट करता है। |
|
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


SaveOptions क्लास का एक नया उदाहरण प्रारंभ करता है।


### getCloneMetadataType() {#getCloneMetadataType--}
```
public final MetadataType getCloneMetadataType()
```


मेटाडेटा सहेजने वाले परिणाम दस्तावेज़ को प्रोसेस करने की रणनीति प्राप्त करता है।
संभव मान enum [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) में हैं।


**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - the stragegy of processing metadata

### setCloneMetadataType(MetadataType value) {#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-}
```
public final void setCloneMetadataType(MetadataType value)
```


मेटाडेटा सहेजने वाले परिणाम दस्तावेज़ को प्रोसेस करने की रणनीति सेट करता है।
संभव मान enum [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) में हैं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) | मेटाडेटा प्रोसेसिंग की रणनीति |
|

### getFileAuthorMetadata() {#getFileAuthorMetadata--}
```
public final FileAuthorMetadata getFileAuthorMetadata()
```


जब [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) को [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR) पर सेट किया जाता है, तब परिणाम दस्तावेज़ में सेट किया जाने वाला मेटाडेटा ऑब्जेक्ट प्राप्त करता है।


**Returns:**
[FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) - the metadata object

### setFileAuthorMetadata(FileAuthorMetadata value) {#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-}
```
public final void setFileAuthorMetadata(FileAuthorMetadata value)
```


जब [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) को [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR) पर सेट किया जाता है, तब परिणाम दस्तावेज़ में सेट किया जाना चाहिए ऐसा मेटाडेटा ऑब्जेक्ट सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) | मेटाडेटा ऑब्जेक्ट |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


परिणाम दस्तावेज़ के लिए पासवर्ड प्राप्त करता है।


**Returns:**
java.lang.String - पासवर्ड

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


परिणाम दस्तावेज़ के लिए पासवर्ड सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | पासवर्ड |
|

### getFolderPath() {#getFolderPath--}
```
public final String getFolderPath()
```


परिणाम छवियों को सहेजने के लिए फ़ोल्डर पथ प्राप्त करता है।
केवल इमेजिंग तुलना के लिए उपयोग किया जाता है।


**Returns:**
java.lang.String - परिणाम छवियों को सहेजने के लिए फ़ोल्डर पथ

### setFolderPath(String value) {#setFolderPath-java.lang.String-}
```
public final void setFolderPath(String value)
```


परिणाम छवियों को सहेजने के लिए फ़ोल्डर पथ सेट करता है।
केवल इमेजिंग तुलना के लिए उपयोग किया जाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | परिणाम छवियों को सहेजने के लिए फ़ोल्डर पथ |
|

### setFolderPath(Path value) {#setFolderPath-java.nio.file.Path-}
```
public final void setFolderPath(Path value)
```


परिणाम छवियों को सहेजने के लिए फ़ोल्डर पथ सेट करता है।
केवल इमेजिंग तुलना के लिए उपयोग किया जाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.nio.file.Path | परिणाम छवियों को सहेजने के लिए फ़ोल्डर पथ |
|


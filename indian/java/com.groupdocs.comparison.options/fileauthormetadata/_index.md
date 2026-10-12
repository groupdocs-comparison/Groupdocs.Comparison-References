---
title: "FileAuthorMetadata"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "दस्तावेज़ के लेखक मेटाडेटा की जानकारी को कॉन्फ़िगर करने की अनुमति देता है।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.comparison.options/fileauthormetadata/
---
**Inheritance:**
java.lang.Object
```
public class FileAuthorMetadata
```

दस्तावेज़ के लेखक मेटाडेटा के बारे में जानकारी को कॉन्फ़िगर करने की अनुमति देता है।


उदाहरण उपयोग:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     SaveOptions saveOptions = new SaveOptions();
     saveOptions.setCloneMetadataType(MetadataType.FILE_AUTHOR);

     final FileAuthorMetadata fileAuthorMetadata = new FileAuthorMetadata();
     fileAuthorMetadata.setAuthor("Tom");
     fileAuthorMetadata.setCompany("GroupDocs");
     fileAuthorMetadata.setLastSaveBy("Jack");

     saveOptions.setFileAuthorMetadata(fileAuthorMetadata);

     comparer.compare(resultFile, saveOptions);
 }
 
````


## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [FileAuthorMetadata()](#FileAuthorMetadata--) | FileAuthorMetadata क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
|
## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
| [GROUP_DOCS](#GROUP-DOCS) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getAuthor()](#getAuthor--) | दस्तावेज़ के लेखक को प्राप्त करता है। |
|
|  | [setAuthor(String value)](#setAuthor-java.lang.String-) | दस्तावेज़ के लेखक को सेट करता है। |
|
|  | [getLastSaveBy()](#getLastSaveBy--) | दस्तावेज़ को अंतिम बार सहेजने वाले व्यक्ति का नाम प्राप्त करता है। |
|
|  | [setLastSaveBy(String value)](#setLastSaveBy-java.lang.String-) | दस्तावेज़ को अंतिम बार सहेजने वाले व्यक्ति का नाम सेट करता है। |
|
|  | [getCompany()](#getCompany--) | कंपनी का नाम प्राप्त करता है जिसकी दस्तावेज़ है। |
|
|  | [setCompany(String value)](#setCompany-java.lang.String-) | कंपनी का नाम सेट करता है जिसकी दस्तावेज़ है। |
|
### FileAuthorMetadata() {#FileAuthorMetadata--}
```
public FileAuthorMetadata()
```


FileAuthorMetadata क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।


### GROUP_DOCS {#GROUP-DOCS}
```
public static final String GROUP_DOCS
```


### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```


दस्तावेज़ के लेखक को प्राप्त करता है।


**Returns:**
java.lang.String - लेखक

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```


दस्तावेज़ के लेखक को सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | लेखक |
|

### getLastSaveBy() {#getLastSaveBy--}
```
public final String getLastSaveBy()
```


दस्तावेज़ को अंतिम बार सहेजने वाले व्यक्ति का नाम प्राप्त करता है।


**Returns:**
java.lang.String - नाम

### setLastSaveBy(String value) {#setLastSaveBy-java.lang.String-}
```
public final void setLastSaveBy(String value)
```


दस्तावेज़ को अंतिम बार सहेजने वाले व्यक्ति का नाम सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | व्यक्ति का नाम |
|

### getCompany() {#getCompany--}
```
public final String getCompany()
```


कंपनी का नाम प्राप्त करता है जिसकी दस्तावेज़ है।


**Returns:**
java.lang.String - कंपनी का नाम

### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```


कंपनी का नाम सेट करता है जिसकी दस्तावेज़ है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | कंपनी का नाम |
|


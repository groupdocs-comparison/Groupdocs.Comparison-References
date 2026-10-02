---
title: "RevisionInfo"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "दस्तावेज़ में एक संशोधन को दर्शाता है।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.comparison.words.revision/revisioninfo/
---
**Inheritance:**
java.lang.Object
```
public class RevisionInfo
```

दस्तावेज़ में एक संशोधन को दर्शाता है।


एक संशोधन दस्तावेज़ में किए गए संशोधन परिवर्तन के बारे में जानकारी समेटता है।
यह क्लास संशोधन के बारे में जानकारी प्राप्त करने के लिए विधियां प्रदान करती है, जैसे कि इसका प्रकार,
सामग्री, लेखक, आदि।

उदाहरण उपयोग:

````

 try (RevisionHandler revisionHandler = new RevisionHandler(sourceFile)) {
     List revisionList = revisionHandler.getRevisions();

     for (RevisionInfo revisionInfo : revisionList) {
         System.out.println("Revision Type: " + revisionInfo.getType());
         System.out.println("Text: " + revisionInfo.getText());
         System.out.println("Author: " + revisionInfo.getAuthor());
     }
 }
 
````


## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [RevisionInfo()](#RevisionInfo--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getAction()](#getAction--) | संशोधन से संबंधित क्रिया (स्वीकार या अस्वीकार) प्राप्त करता है। |
|
|  | [setAction(RevisionAction value)](#setAction-com.groupdocs.comparison.words.revision.RevisionAction-) | संशोधन से संबंधित मान (स्वीकार या अस्वीकार) सेट करता है। |
|
|  | [getText()](#getText--) | संशोधन की पाठ सामग्री प्राप्त करता है। |
|
|  | [setText(String value)](#setText-java.lang.String-) | संशोधन की मान सामग्री सेट करता है। |
|
|  | [getAuthor()](#getAuthor--) | संशोधन के लेखक को प्राप्त करता है। |
|
|  | [setAuthor(String value)](#setAuthor-java.lang.String-) | संशोधन का मान सेट करता है। |
|
|  | [getType()](#getType--) | संशोधन का प्रकार प्राप्त करता है, प्रकार के आधार पर क्रिया (स्वीकार या अस्वीकार) तर्क बदलता है। |
|
|  | [setType(RevisionType value)](#setType-com.groupdocs.comparison.words.revision.RevisionType-) | संशोधन का मान सेट करता है, मान के आधार पर क्रिया (स्वीकार या अस्वीकार) तर्क बदलता है। |
|
### RevisionInfo() {#RevisionInfo--}
```
public RevisionInfo()
```


### getAction() {#getAction--}
```
public RevisionAction getAction()
```


संशोधन से संबंधित क्रिया (स्वीकार या अस्वीकार) प्राप्त करता है। यह फ़ील्ड आपको संशोधन के प्रदर्शन को प्रभावित करने की अनुमति देता है।


**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the action associated with the revision.

### setAction(RevisionAction value) {#setAction-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setAction(RevisionAction value)
```


संशोधन से संबंधित मान (स्वीकार या अस्वीकार) सेट करता है। यह फ़ील्ड आपको संशोधन के प्रदर्शन को प्रभावित करने की अनुमति देता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | संशोधन से संबंधित मान। |
|

### getText() {#getText--}
```
public String getText()
```


संशोधन की पाठ सामग्री प्राप्त करता है।


**Returns:**
java.lang.String - संशोधन की पाठ सामग्री।

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


संशोधन की मान सामग्री सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | संशोधन की मान सामग्री। |
|

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


संशोधन के लेखक को प्राप्त करता है।


**Returns:**
java.lang.String - संशोधन का लेखक।

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


संशोधन का मान सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | संशोधन का मान। |
|

### getType() {#getType--}
```
public RevisionType getType()
```


संशोधन का प्रकार प्राप्त करता है, प्रकार के आधार पर क्रिया (स्वीकार या अस्वीकार) तर्क बदलता है।


**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - the type of the revision.

### setType(RevisionType value) {#setType-com.groupdocs.comparison.words.revision.RevisionType-}
```
public void setType(RevisionType value)
```


संशोधन का मान सेट करता है, मान के आधार पर क्रिया (स्वीकार या अस्वीकार) तर्क बदलता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) | संशोधन का मान। |
|


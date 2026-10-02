---
title: "PageInfo"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "PageInfo क्लास दस्तावेज़ में एक विशिष्ट पृष्ठ की जानकारी दर्शाती है।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.comparison.result/pageinfo/
---
**Inheritance:**
java.lang.Object
```
public class PageInfo
```

PageInfo क्लास दस्तावेज़ में एक विशिष्ट पृष्ठ की जानकारी दर्शाती है।


यह पृष्ठ संख्या, चौड़ाई, ऊँचाई और अन्य संबंधित गुणों जैसी विवरण प्रदान करता है।
तुलना प्रक्रिया के दौरान दस्तावेज़ में व्यक्तिगत पृष्ठों के बारे में जानकारी प्राप्त करने के लिए इस क्लास का उपयोग करें।


उदाहरण उपयोग:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare(resultFile);
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo change : changes) {
         final PageInfo pageInfo = change.getPageInfo();
         // Print the page information
         System.out.println("Page Number: " + pageInfo.getPageNumber());
         System.out.println("Page Width: " + pageInfo.getWidth());
         System.out.println("Page Height: " + pageInfo.getHeight());
     }
 }
 
````


## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [PageInfo(int pageNumber, int width, int height)](#PageInfo-int-int-int-) | PageInfo क्लास का नया उदाहरण प्रारंभ करता है, जिसमें pageNumber, चौड़ाई और ऊँचाई को कॉन्फ़िगर किया जाता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getWidth()](#getWidth--) | पृष्ठ की चौड़ाई प्राप्त करता है |
|
|  | [setWidth(int value)](#setWidth-int-) | पृष्ठ की चौड़ाई सेट करता है |
|
|  | [getHeight()](#getHeight--) | पृष्ठ की ऊँचाई प्राप्त करता है |
|
|  | [setHeight(int value)](#setHeight-int-) | पृष्ठ की ऊँचाई सेट करता है |
|
|  | [getPageNumber()](#getPageNumber--) | पृष्ठ संख्या प्राप्त करता है |
|
|  | [setPageNumber(int value)](#setPageNumber-int-) | पृष्ठ संख्या सेट करता है |
|
| [toString()](#toString--) |  |
### PageInfo(int pageNumber, int width, int height) {#PageInfo-int-int-int-}
```
public PageInfo(int pageNumber, int width, int height)
```


PageInfo क्लास का नया उदाहरण प्रारंभ करता है, जिसमें pageNumber, चौड़ाई और ऊँचाई को कॉन्फ़िगर किया जाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | pageNumber | int | पृष्ठ की संख्या |
|
|  | width | int | पृष्ठ की चौड़ाई |
|
|  | height | int | पृष्ठ की ऊँचाई |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


पृष्ठ की चौड़ाई प्राप्त करता है


**Returns:**
int - पृष्ठ की चौड़ाई

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


पृष्ठ की चौड़ाई सेट करता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | पृष्ठ की चौड़ाई |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


पृष्ठ की ऊँचाई प्राप्त करता है


**Returns:**
int - पृष्ठ की ऊँचाई

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


पृष्ठ की ऊँचाई सेट करता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | पृष्ठ की ऊँचाई |
|

### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


पृष्ठ संख्या प्राप्त करता है


**Returns:**
int - पृष्ठ का क्रमांक

### setPageNumber(int value) {#setPageNumber-int-}
```
public final void setPageNumber(int value)
```


पृष्ठ संख्या सेट करता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | पृष्ठ की संख्या |
|

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String

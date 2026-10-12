---
title: "IDocumentInfo"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "दस्तावेज़ गुणों तक पहुँच प्रदान करता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.comparison.interfaces/idocumentinfo/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface IDocumentInfo extends Closeable
```

दस्तावेज़ गुणों तक पहुँच प्रदान करता है।


इसके उपयोग के बारे में अधिक विवरण आप [Document.getDocumentInfo()](../../com.groupdocs.comparison/document#getDocumentInfo--) मेथड में या [documentation](../https://docs.groupdocs.com/comparison/java/get-file-info/) में पा सकते हैं।


उदाहरण उपयोग:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    try (IDocumentInfo documentInfo = comparer.getSource().getDocumentInfo()) {
      for (int i = 0; i < documentInfo.getPageCount(); i++) {
          System.out.printf("File type: %s%nNumber of pages: %d", documentInfo.getFileType().getFileFormat(), documentInfo.getPageCount());
      }
    }
 }
 
````


## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getFileType()](#getFileType--) | फ़ाइल के प्रकार को प्राप्त करता है जो [FileType](../../com.groupdocs.comparison.result/filetype) enum द्वारा दर्शाया गया है। |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | फ़ाइल का प्रकार सेट करता है [FileType](../../com.groupdocs.comparison.result/filetype) enum का उपयोग करके। |
|
|  | [getPageCount()](#getPageCount--) | फ़ाइल की गिनती प्राप्त करता है। |
|
|  | [setPageCount(int value)](#setPageCount-int-) | फ़ाइल की गिनती सेट करता है। |
|
|  | [getSize()](#getSize--) | फ़ाइल का आकार प्राप्त करता है। |
|
|  | [setSize(long value)](#setSize-long-) | फ़ाइल का आकार सेट करता है। |
|
|  | [getPagesInfo()](#getPagesInfo--) | फ़ाइल के प्रत्येक पृष्ठ की जानकारी प्राप्त करता है [PageInfo](../../com.groupdocs.comparison.result/pageinfo) क्लास का उपयोग करके। |
|
|  | [setPagesInfo(List<PageInfo> pageInfos)](#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--) | फ़ाइल के प्रत्येक पृष्ठ की जानकारी सेट करता है [PageInfo](../../com.groupdocs.comparison.result/pageinfo) क्लास का उपयोग करके। |
|
|  | [close()](#close--) | ऑब्जेक्ट को नष्ट करता है जिससे इस [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) इंस्टेंस का उपयोग करके दस्तावेज़ की जानकारी प्राप्त करना असंभव हो जाता है। |
|
### getFileType() {#getFileType--}
```
public abstract FileType getFileType()
```


फ़ाइल के प्रकार को प्राप्त करता है जो [FileType](../../com.groupdocs.comparison.result/filetype) enum द्वारा दर्शाया गया है।


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public abstract void setFileType(FileType value)
```


फ़ाइल का प्रकार सेट करता है [FileType](../../com.groupdocs.comparison.result/filetype) enum का उपयोग करके।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.comparison.result/filetype) | फ़ाइल का प्रकार |
|

### getPageCount() {#getPageCount--}
```
public abstract int getPageCount()
```


फ़ाइल की गिनती प्राप्त करता है।


**Returns:**
int - फ़ाइल की गिनती

### setPageCount(int value) {#setPageCount-int-}
```
public abstract void setPageCount(int value)
```


फ़ाइल की गिनती सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | फ़ाइल की गिनती |
|

### getSize() {#getSize--}
```
public abstract long getSize()
```


फ़ाइल का आकार प्राप्त करता है।


**Returns:**
long - फ़ाइल का आकार

### setSize(long value) {#setSize-long-}
```
public abstract void setSize(long value)
```


फ़ाइल का आकार सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | long | फ़ाइल का आकार |
|

### getPagesInfo() {#getPagesInfo--}
```
public abstract List<PageInfo> getPagesInfo()
```


फ़ाइल के प्रत्येक पृष्ठ की जानकारी प्राप्त करता है [PageInfo](../../com.groupdocs.comparison.result/pageinfo) क्लास का उपयोग करके।


**Returns:**
java.util.List<com.groupdocs.comparison.result.PageInfo> - फ़ाइल के प्रत्येक पृष्ठ की जानकारी

### setPagesInfo(List<PageInfo> pageInfos) {#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--}
```
public abstract void setPagesInfo(List<PageInfo> pageInfos)
```


फ़ाइल के प्रत्येक पृष्ठ की जानकारी सेट करता है [PageInfo](../../com.groupdocs.comparison.result/pageinfo) क्लास का उपयोग करके।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | pageInfos | java.util.List<com.groupdocs.comparison.result.PageInfo> | फ़ाइल के प्रत्येक पृष्ठ की जानकारी |
|

### close() {#close--}
```
public abstract void close()
```


ऑब्जेक्ट को नष्ट करता है जिससे इस [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) इंस्टेंस का उपयोग करके दस्तावेज़ की जानकारी प्राप्त करना असंभव हो जाता है।
अस्थायी फ़ाइलों को भी हटाता है और उपयोग किए गए संसाधनों को मुक्त करता है।



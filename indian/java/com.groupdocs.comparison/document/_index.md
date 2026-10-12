---
title: "Document"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "तुलना प्रक्रिया के लिए एक दस्तावेज़ का प्रतिनिधित्व करता है।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.comparison/document/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Document implements Closeable
```

तुलना प्रक्रिया के लिए एक दस्तावेज़ का प्रतिनिधित्व करता है।


Document क्लास तुलना प्रक्रिया के दौरान दस्तावेज़ लोड करने, प्रीव्यू छवियां बनाने और दस्तावेज़ों को संशोधित करने के लिए मेथड प्रदान करती है।


उदाहरण उपयोग:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     try (IDocumentInfo info = comparer.getSource().getDocumentInfo()) {
         System.out.println("File type: " + info.getFileType());
         System.out.println("Number of pages: " + info.getPageCount());
         System.out.println("Document size: " + info.getSize());
     }
 }
 
````


## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [Document(InputStream stream)](#Document-java.io.InputStream-) | निर्दिष्ट दस्तावेज़ स्ट्रीम के साथ Document क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [Document(String filePath)](#Document-java.lang.String-) | निर्दिष्ट दस्तावेज़ पथ के साथ Document क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [Document(Path filePath)](#Document-java.nio.file.Path-) | निर्दिष्ट दस्तावेज़ पथ के साथ Document क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [Document(Path filePath, String password)](#Document-java.nio.file.Path-java.lang.String-) | निर्दिष्ट दस्तावेज़ पथ और पासवर्ड के साथ Document क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [Document(Path filePath, LoadOptions loadOptions)](#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | निर्दिष्ट दस्तावेज़ पथ और लोड विकल्पों के साथ Document क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [Document(String filePath, String password)](#Document-java.lang.String-java.lang.String-) | निर्दिष्ट दस्तावेज़ पथ और पासवर्ड के साथ Document क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [Document(String filePath, LoadOptions loadOptions)](#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | निर्दिष्ट दस्तावेज़ पथ और लोड विकल्पों के साथ Document क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [Document(InputStream stream, String password)](#Document-java.io.InputStream-java.lang.String-) | निर्दिष्ट दस्तावेज़ स्ट्रीम और पासवर्ड के साथ Document क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [Document(String filePathOrTextContent, boolean isLoadText)](#Document-java.lang.String-boolean-) | निर्दिष्ट दस्तावेज़ पथ या टेक्स्ट कंटेंट और यह दर्शाने वाले फ़्लैग के साथ Document क्लास का नया इंस्टेंस इनिशियलाइज़ करता है कि क्या पास किया गया। |
|
|  | [Document(InputStream inputStream, LoadOptions loadOptions)](#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | निर्दिष्ट दस्तावेज़ स्ट्रीम और लोड विकल्पों के साथ Document क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getChanges()](#getChanges--) | [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) ऑब्जेक्ट्स की सूची प्राप्त करता है जो तुलना प्रक्रिया के दौरान पता लगाए गए परिवर्तन को दर्शाती है। |
|
|  | [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) ऑब्जेक्ट्स की सूची सेट करता है जो तुलना प्रक्रिया के दौरान पता लगाए गए परिवर्तन को दर्शाती है। |
|
|  | [getName()](#getName--) | दस्तावेज़ का नाम प्राप्त करता है। |
|
|  | [setName(String value)](#setName-java.lang.String-) | दस्तावेज़ का नाम सेट करता है। |
|
|  | [getFileType()](#getFileType--) | दस्तावेज़ का प्रकार प्राप्त करता है। |
|
|  | [setFileType(FileType fileType)](#setFileType-com.groupdocs.comparison.result.FileType-) | दस्तावेज़ का प्रकार सेट करता है। |
|
|  | [createStream()](#createStream--) | दस्तावेज़ सामग्री के साथ नई स्ट्रीम बनाता है। |
|
|  | [getStreamLength()](#getStreamLength--) | दस्तावेज़ का आकार प्राप्त करता है |
|
|  | [getPassword()](#getPassword--) | दस्तावेज़ का पासवर्ड प्राप्त करता है |
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.comparison.options.PreviewOptions-) | प्रदान किए गए [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) के आधार पर दस्तावेज़ प्रीव्यू बनाता है। |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | दस्तावेज़ के बारे में जानकारी प्राप्त करता है, जिसमें दस्तावेज़ प्रकार, पृष्ठ गिनती, पृष्ठ आकार और अधिक शामिल हैं। |
|
| [close()](#close--) |  |
### Document(InputStream stream) {#Document-java.io.InputStream-}
```
public Document(InputStream stream)
```


निर्दिष्ट दस्तावेज़ स्ट्रीम के साथ Document क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | स्ट्रीम | java.io.InputStream | दस्तावेज़ स्ट्रीम |
|

### Document(String filePath) {#Document-java.lang.String-}
```
public Document(String filePath)
```


निर्दिष्ट दस्तावेज़ पथ के साथ Document क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | दस्तावेज़ पथ |
|

### Document(Path filePath) {#Document-java.nio.file.Path-}
```
public Document(Path filePath)
```


निर्दिष्ट दस्तावेज़ पथ के साथ Document क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | दस्तावेज़ पथ |
|

### Document(Path filePath, String password) {#Document-java.nio.file.Path-java.lang.String-}
```
public Document(Path filePath, String password)
```


निर्दिष्ट दस्तावेज़ पथ और पासवर्ड के साथ Document क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | दस्तावेज़ पथ |
|
|  | पासवर्ड | java.lang.String | दस्तावेज़ पासवर्ड |
|

### Document(Path filePath, LoadOptions loadOptions) {#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(Path filePath, LoadOptions loadOptions)
```


निर्दिष्ट दस्तावेज़ पथ और लोड विकल्पों के साथ Document क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | दस्तावेज़ पथ |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | लोड विकल्प |
|

### Document(String filePath, String password) {#Document-java.lang.String-java.lang.String-}
```
public Document(String filePath, String password)
```


निर्दिष्ट दस्तावेज़ पथ और पासवर्ड के साथ Document क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | दस्तावेज़ पथ |
|
|  | पासवर्ड | java.lang.String | दस्तावेज़ पासवर्ड |
|

### Document(String filePath, LoadOptions loadOptions) {#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(String filePath, LoadOptions loadOptions)
```


निर्दिष्ट दस्तावेज़ पथ और लोड विकल्पों के साथ Document क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | दस्तावेज़ पथ |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | लोड विकल्प |
|

### Document(InputStream stream, String password) {#Document-java.io.InputStream-java.lang.String-}
```
public Document(InputStream stream, String password)
```


निर्दिष्ट दस्तावेज़ स्ट्रीम और पासवर्ड के साथ Document क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | स्ट्रीम | java.io.InputStream | दस्तावेज़ स्ट्रीम |
|
|  | पासवर्ड | java.lang.String | दस्तावेज़ पासवर्ड |
|

### Document(String filePathOrTextContent, boolean isLoadText) {#Document-java.lang.String-boolean-}
```
public Document(String filePathOrTextContent, boolean isLoadText)
```


निर्दिष्ट दस्तावेज़ पथ या टेक्स्ट कंटेंट और यह दर्शाने वाले फ़्लैग के साथ Document क्लास का नया इंस्टेंस इनिशियलाइज़ करता है कि क्या पास किया गया।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePathOrTextContent | java.lang.String | फ़ाइल पथ |
|
|  | isLoadText | boolean | लोड टेक्स्ट है |
|

### Document(InputStream inputStream, LoadOptions loadOptions) {#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(InputStream inputStream, LoadOptions loadOptions)
```


निर्दिष्ट दस्तावेज़ स्ट्रीम और लोड विकल्पों के साथ Document क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | inputStream | java.io.InputStream | दस्तावेज़ स्ट्रीम |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | लोड विकल्प |
|

### getChanges() {#getChanges--}
```
public final List<ChangeInfo> getChanges()
```


[ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) ऑब्जेक्ट्स की सूची प्राप्त करता है जो तुलना प्रक्रिया के दौरान पता लगाए गए परिवर्तन को दर्शाती है।


इस विधि का उपयोग स्रोत दस्तावेज़ और लक्ष्य दस्तावेज़(ओं) के बीच हुए परिवर्तनों के बारे में विस्तृत जानकारी प्राप्त करने के लिए करें।
प्रत्येक [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) ऑब्जेक्ट में परिवर्तन प्रकार, प्रभावित क्षेत्र आदि जैसी जानकारी होती है,
और परिवर्तन से पहले और बाद की सामग्री।


**Returns:**
java.util.List<com.groupdocs.comparison.result.ChangeInfo> - तुलना प्रक्रिया के दौरान पता लगाए गए परिवर्तनों को दर्शाने वाले [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) ऑब्जेक्ट्स की सूची

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


[ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) ऑब्जेक्ट्स की सूची सेट करता है जो तुलना प्रक्रिया के दौरान पता लगाए गए परिवर्तन को दर्शाती है।


इस विधि का उपयोग स्रोत दस्तावेज़ और लक्ष्य दस्तावेज़(ओं) के बीच हुए परिवर्तनों के बारे में विस्तृत जानकारी प्राप्त करने के लिए करें।
प्रत्येक [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) ऑब्जेक्ट में परिवर्तन प्रकार, प्रभावित क्षेत्र आदि जैसी जानकारी होती है,
और परिवर्तन से पहले और बाद की सामग्री।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | तुलना प्रक्रिया के दौरान पता लगाए गए परिवर्तनों को दर्शाने वाले [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) ऑब्जेक्ट्स की सूची |
|

### getName() {#getName--}
```
public final String getName()
```


दस्तावेज़ का नाम प्राप्त करता है।


**Returns:**
java.lang.String - दस्तावेज़ का नाम

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


दस्तावेज़ का नाम सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | दस्तावेज़ का नाम |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


दस्तावेज़ का प्रकार प्राप्त करता है।


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the document

### setFileType(FileType fileType) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType fileType)
```


दस्तावेज़ का प्रकार सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | दस्तावेज़ का प्रकार |
|

### createStream() {#createStream--}
```
public InputStream createStream()
```


दस्तावेज़ सामग्री के साथ नई स्ट्रीम बनाता है।


**Returns:**
java.io.InputStream - दस्तावेज़ सामग्री वाला स्ट्रीम

### getStreamLength() {#getStreamLength--}
```
public long getStreamLength()
```


दस्तावेज़ का आकार प्राप्त करता है


**Returns:**
long - दस्तावेज़ का आकार

### getPassword() {#getPassword--}
```
public String getPassword()
```


दस्तावेज़ का पासवर्ड प्राप्त करता है


**Returns:**
java.lang.String - दस्तावेज़ का पासवर्ड

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.comparison.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


प्रदान किए गए [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) के आधार पर दस्तावेज़ प्रीव्यू बनाता है।


यह विधि निर्दिष्ट विकल्पों के अनुसार, जैसे प्रीव्यू फ़ॉर्मेट, दस्तावेज़ पृष्ठों के प्रीव्यू बनाती है,
पृष्ठ संख्या, और आउटपुट स्ट्रीम प्रदाता। उत्पन्न प्रीव्यू को आवश्यकतानुसार सहेजा या आगे प्रोसेस किया जा सकता है।

* Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Generate+document+pages+preview)


उदाहरण उपयोग:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     PreviewOptions previewOptions = new PreviewOptions(
             pageNumber -> Files.newOutputStream(Paths.get("preview-image-page-" + pageNumber + ".png"))
     );
     previewOptions.setPreviewFormat(PreviewFormats.PNG);
     previewOptions.setPageNumbers(new int[]{1, 2});
     comparer.getSource().generatePreview(previewOptions);
 }
 
````



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) | फ़ॉर्मेट, पृष्ठ संख्या आदि निर्दिष्ट करने वाले प्रीव्यू विकल्प |
|

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


दस्तावेज़ के बारे में जानकारी प्राप्त करता है, जिसमें दस्तावेज़ प्रकार, पृष्ठ गिनती, पृष्ठ आकार और अधिक शामिल हैं।

* Learn more about document file type, page count, size, and other format-specific properties: [How to get document info using GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Get+file+info)


**Returns:**
[IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) - the document information

### close() {#close--}
```
public void close()
```





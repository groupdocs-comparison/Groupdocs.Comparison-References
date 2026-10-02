---
title: "RevisionHandler"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "एक क्लास को दर्शाता है जो संशोधनों के हैंडलिंग को नियंत्रित करती है।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.comparison.words.revision/revisionhandler/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class RevisionHandler implements Closeable
```

एक क्लास को दर्शाता है जो संशोधनों के हैंडलिंग को नियंत्रित करती है।


RevisionHandler क्लास आपको दस्तावेज़ों में संशोधनों के साथ काम करने की अनुमति देता है।
यह संशोधनों की सूची प्राप्त करने, संशोधनों पर परिवर्तन लागू करने, और संशोधित दस्तावेज़ को सहेजने के लिए मेथड प्रदान करता है।


उदाहरण उपयोग:

````

 try (RevisionHandler revisionHandler = new RevisionHandler(sourceFile)) {
     List revisionList = revisionHandler.getRevisions();

     for (RevisionInfo revisionInfo : revisionList) {
         if (revisionInfo.getType() == RevisionType.DELETION)
             // Set an action to be applied to the revision
             revisionInfo.setAction(RevisionAction.Accept);
     }
     // Create an instance of ApplyRevisionOptions
     ApplyRevisionOptions revisionChanges = new ApplyRevisionOptions();
     revisionChanges.setChanges(revisionList);
     // Apply the revisions using the options
     revisionHandler.applyRevisionChanges(resultFile, revisionChanges);
 }
 
````


## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [RevisionHandler(String filePath)](#RevisionHandler-java.lang.String-) | RevisionHandler क्लास का नया इंस्टेंस फ़ाइल के पथ के साथ प्रारंभ करता है जिसमें संशोधन शामिल हैं। |
|
|  | [RevisionHandler(Path filePath)](#RevisionHandler-java.nio.file.Path-) | RevisionHandler क्लास का नया इंस्टेंस फ़ाइल के पथ के साथ प्रारंभ करता है जिसमें संशोधन शामिल हैं। |
|
|  | [RevisionHandler(InputStream file, FileType fileType)](#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-) | RevisionHandler क्लास का नया इंस्टेंस संशोधन वाली फ़ाइल स्ट्रीम के साथ प्रारंभ करता है। |
|
|  | [RevisionHandler(Document document)](#RevisionHandler-com.aspose.words.Document-) | RevisionHandler क्लास का नया इंस्टेंस दस्तावेज़ के साथ प्रारंभ करता है। |
|
## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
| [SOURCE_PATH_IS_NULL](#SOURCE-PATH-IS-NULL) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getRevisions()](#getRevisions--) | सभी संशोधनों की सूची प्राप्त करता है। |
|
|  | [applyRevisionChanges(ApplyRevisionOptions changes)](#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | संशोधनों में परिवर्तन प्रोसेस करता है और उन्हें मूल फ़ाइल पर लागू करता है। |
|
|  | [applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | संशोधनों में परिवर्तन प्रोसेस करता है और परिणाम को निर्दिष्ट फ़ाइल में लिखता है। |
|
|  | [applyRevisionChanges(String filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | संशोधनों में परिवर्तन प्रोसेस करता है और परिणाम को निर्दिष्ट फ़ाइल में लिखता है। |
|
|  | [applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)](#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | संशोधनों में परिवर्तन प्रोसेस करता है और परिणाम को दस्तावेज़ स्ट्रीम में लिखता है। |
|
| [close()](#close--) |  |
### RevisionHandler(String filePath) {#RevisionHandler-java.lang.String-}
```
public RevisionHandler(String filePath)
```


RevisionHandler क्लास का नया इंस्टेंस फ़ाइल के पथ के साथ प्रारंभ करता है जिसमें संशोधन शामिल हैं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | फ़ाइल का पथ। |
|

### RevisionHandler(Path filePath) {#RevisionHandler-java.nio.file.Path-}
```
public RevisionHandler(Path filePath)
```


RevisionHandler क्लास का नया इंस्टेंस फ़ाइल के पथ के साथ प्रारंभ करता है जिसमें संशोधन शामिल हैं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | फ़ाइल का पथ। |
|

### RevisionHandler(InputStream file, FileType fileType) {#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-}
```
public RevisionHandler(InputStream file, FileType fileType)
```


RevisionHandler क्लास का नया इंस्टेंस संशोधन वाली फ़ाइल स्ट्रीम के साथ प्रारंभ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | फ़ाइल | java.io.InputStream | स्रोत दस्तावेज़ स्ट्रीम। |
|
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | फ़ाइल का प्रकार। |
|

### RevisionHandler(Document document) {#RevisionHandler-com.aspose.words.Document-}
```
public RevisionHandler(Document document)
```


RevisionHandler क्लास का नया इंस्टेंस दस्तावेज़ के साथ प्रारंभ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | com.aspose.words.Document | दस्तावेज़। |
|

### SOURCE_PATH_IS_NULL {#SOURCE-PATH-IS-NULL}
```
public static final String SOURCE_PATH_IS_NULL
```


### getRevisions() {#getRevisions--}
```
public List<RevisionInfo> getRevisions()
```


सभी संशोधनों की सूची प्राप्त करता है।


चूँकि संशोधन मूल रूप से एक समूह में क्रमबद्ध थे, संशोधनों को एक List से लेना आवश्यक है।
List में, एक संशोधन को समान सामान्य पाठ के साथ कई संशोधनों में विभाजित किया जा सकता है।
चूँकि List में समान सामान्य पाठ वाले संशोधन हो सकते हैं, उपयोगकर्ता के लिए संशोधनों की सूची बनाते समय इसे नियंत्रित करना आवश्यक है।
यह यहाँ List\<RevisionGroup\> समूहों का उपयोग करके नियंत्रित किया जाता है।


**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - संशोधनों की सूची।

### applyRevisionChanges(ApplyRevisionOptions changes) {#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(ApplyRevisionOptions changes)
```


संशोधनों में परिवर्तन प्रोसेस करता है और उन्हें मूल फ़ाइल पर लागू करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | बदलाव किए गए संशोधनों की सूची। |
|

### applyRevisionChanges(Path filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)
```


संशोधनों में परिवर्तन प्रोसेस करता है और परिणाम को निर्दिष्ट फ़ाइल में लिखता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | परिणाम फ़ाइल पथ। |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | बदलाव किए गए संशोधनों की सूची। |
|

### applyRevisionChanges(String filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(String filePath, ApplyRevisionOptions changes)
```


संशोधनों में परिवर्तन प्रोसेस करता है और परिणाम को निर्दिष्ट फ़ाइल में लिखता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | परिणाम फ़ाइल पथ। |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | बदलाव किए गए संशोधनों की सूची। |
|

### applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes) {#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)
```


संशोधनों में परिवर्तन प्रोसेस करता है और परिणाम को दस्तावेज़ स्ट्रीम में लिखता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | परिणाम दस्तावेज़ स्ट्रीम। |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | बदलाव किए गए संशोधनों की सूची। |
|

### close() {#close--}
```
public void close()
```





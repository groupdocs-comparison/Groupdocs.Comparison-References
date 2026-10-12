---
title: "PreviewOptions"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "तुलना प्रक्रिया में दस्तावेज़ पूर्वावलोकन बनाने के लिए विकल्प प्रदान करता है।"
type: docs
weight: 15
url: /hi/java/com.groupdocs.comparison.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

तुलना प्रक्रिया में दस्तावेज़ पूर्वावलोकन बनाने के लिए विकल्प प्रदान करता है।


उदाहरण उपयोग:

````

 try (Comparer comparer = new Comparer(sourceFile)) {

    PreviewOptions previewOptions = new PreviewOptions(
            pageNumber -> Files.newOutputStream(Paths.get(String.format("preview-page_%d.png", pageNumber)))
    );
    previewOptions.setPreviewFormat(PreviewFormats.PNG);
    previewOptions.setPageNumbers(new int[]{1, 2});

    comparer.getSource().generatePreview(previewOptions);
 }
 
````


## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [PreviewOptions(Delegates.CreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | Delegates.CreatePageStream फ़ंक्शन निर्दिष्ट करते हुए PreviewOptions क्लास का नया उदाहरण प्रारंभ करता है। |
|
|  | [PreviewOptions(CreatePageStreamFunction createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | PreviewOptions क्लास का नया उदाहरण प्रारंभ करता है, जिसमें [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) फ़ंक्शन निर्दिष्ट किया गया है। |
|
|  | [PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | Delegates.CreatePageStream और Delegates.ReleasePageStream फ़ंक्शन निर्दिष्ट करते हुए PreviewOptions क्लास का नया उदाहरण प्रारंभ करता है। |
|
|  | [PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | PreviewOptions क्लास का नया उदाहरण प्रारंभ करता है, जिसमें [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) और [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) फ़ंक्शन निर्दिष्ट किए गए हैं। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getCreatePageStream()](#getCreatePageStream--) | आउटपुट पेज प्रीव्यू स्ट्रीम बनाने के लिए फ़ंक्शन को प्राप्त करता है। |
|
|  | [setCreatePageStream(Delegates.CreatePageStream createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | आउटपुट पेज प्रीव्यू स्ट्रीम बनाने के लिए फ़ंक्शन को सेट करता है। |
|
|  | [setCreatePageStream(CreatePageStreamFunction createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | आउटपुट पेज प्रीव्यू स्ट्रीम बनाने के लिए फ़ंक्शन को सेट करता है। |
|
|  | [getReleasePageStream()](#getReleasePageStream--) | आउटपुट पेज प्रीव्यू स्ट्रीम रिलीज़ करने के लिए फ़ंक्शन को प्राप्त करता है। |
|
|  | [setReleasePageStream(Delegates.ReleasePageStream releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | आउटपुट पेज प्रीव्यू स्ट्रीम रिलीज़ करने के लिए फ़ंक्शन को प्राप्त करता है। |
|
|  | [setReleasePageStream(ReleasePageStreamFunction releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | आउटपुट पेज प्रीव्यू स्ट्रीम रिलीज़ करने के लिए फ़ंक्शन को सेट करता है। |
|
|  | [getWidth()](#getWidth--) | प्रिव्यू छवियों की चौड़ाई प्राप्त करता है। |
|
|  | [setWidth(int value)](#setWidth-int-) | प्रिव्यू छवियों की चौड़ाई सेट करता है। |
|
|  | [getHeight()](#getHeight--) | प्रिव्यू छवियों की ऊँचाई प्राप्त करता है। |
|
|  | [setHeight(int value)](#setHeight-int-) | प्रिव्यू छवियों की ऊँचाई सेट करता है। |
|
|  | [getPageNumbers()](#getPageNumbers--) | उन पृष्ठ संख्याओं की एक एरे प्राप्त करता है जिनके लिए प्रिव्यू छवियां उत्पन्न की जाएँगी। |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | उन पृष्ठ संख्याओं की एक एरे सेट करता है जिनके लिए प्रिव्यू छवियां उत्पन्न की जाएँगी। |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | प्रिव्यू छवियों का फ़ॉर्मेट प्राप्त करता है। |
|
|  | [setPreviewFormat(PreviewFormats value)](#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-) | प्रिव्यू छवियों का फ़ॉर्मेट सेट करता है। |
|
### PreviewOptions(Delegates.CreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream)
```


Delegates.CreatePageStream फ़ंक्शन निर्दिष्ट करते हुए PreviewOptions क्लास का नया उदाहरण प्रारंभ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | आउटपुट पेज प्रिव्यू स्ट्रीम बनाने का फ़ंक्शन। |
|

### PreviewOptions(CreatePageStreamFunction createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream)
```


PreviewOptions क्लास का नया उदाहरण प्रारंभ करता है, जिसमें [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) फ़ंक्शन निर्दिष्ट किया गया है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | आउटपुट पेज प्रिव्यू स्ट्रीम बनाने का फ़ंक्शन। |
|

### PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)
```


Delegates.CreatePageStream और Delegates.ReleasePageStream फ़ंक्शन निर्दिष्ट करते हुए PreviewOptions क्लास का नया उदाहरण प्रारंभ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | आउटपुट पेज प्रिव्यू स्ट्रीम बनाने का फ़ंक्शन। |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | आउटपुट पेज प्रिव्यू स्ट्रीम रिलीज़ करने का फ़ंक्शन। |
|

### PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)
```


PreviewOptions क्लास का नया उदाहरण प्रारंभ करता है, जिसमें [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) और [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) फ़ंक्शन निर्दिष्ट किए गए हैं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | आउटपुट पेज प्रिव्यू स्ट्रीम बनाने का फ़ंक्शन। |
|
|  | releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | आउटपुट पेज प्रिव्यू स्ट्रीम रिलीज़ करने का फ़ंक्शन। |
|

### getCreatePageStream() {#getCreatePageStream--}
```
public CreatePageStreamFunction getCreatePageStream()
```


आउटपुट पेज प्रीव्यू स्ट्रीम बनाने के लिए फ़ंक्शन को प्राप्त करता है।


**Returns:**
[CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) - the function to create output page preview stream.

### setCreatePageStream(Delegates.CreatePageStream createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public void setCreatePageStream(Delegates.CreatePageStream createPageStream)
```


आउटपुट पेज प्रीव्यू स्ट्रीम बनाने के लिए फ़ंक्शन को सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | आउटपुट पेज प्रिव्यू स्ट्रीम बनाने का फ़ंक्शन। |
|

### setCreatePageStream(CreatePageStreamFunction createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public void setCreatePageStream(CreatePageStreamFunction createPageStream)
```


आउटपुट पेज प्रीव्यू स्ट्रीम बनाने के लिए फ़ंक्शन को सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | आउटपुट पेज प्रिव्यू स्ट्रीम बनाने का फ़ंक्शन। |
|

### getReleasePageStream() {#getReleasePageStream--}
```
public ReleasePageStreamFunction getReleasePageStream()
```


आउटपुट पेज प्रीव्यू स्ट्रीम रिलीज़ करने के लिए फ़ंक्शन को प्राप्त करता है।


**Returns:**
[ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) - the function to release output page preview stream.

### setReleasePageStream(Delegates.ReleasePageStream releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public void setReleasePageStream(Delegates.ReleasePageStream releasePageStream)
```


आउटपुट पेज प्रीव्यू स्ट्रीम रिलीज़ करने के लिए फ़ंक्शन को प्राप्त करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | आउटपुट पेज प्रिव्यू स्ट्रीम रिलीज़ करने का फ़ंक्शन। |
|

### setReleasePageStream(ReleasePageStreamFunction releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public void setReleasePageStream(ReleasePageStreamFunction releasePageStream)
```


आउटपुट पेज प्रीव्यू स्ट्रीम रिलीज़ करने के लिए फ़ंक्शन को सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | आउटपुट पेज प्रिव्यू स्ट्रीम रिलीज़ करने का फ़ंक्शन। |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


प्रिव्यू छवियों की चौड़ाई प्राप्त करता है।


**Returns:**
int - प्रिव्यू छवियों की चौड़ाई।

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


प्रिव्यू छवियों की चौड़ाई सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | प्रिव्यू छवियों की चौड़ाई। |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


प्रिव्यू छवियों की ऊँचाई प्राप्त करता है।


**Returns:**
int - प्रिव्यू छवियों की ऊँचाई।

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


प्रिव्यू छवियों की ऊँचाई सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | प्रिव्यू छवियों की ऊँचाई। |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


उन पृष्ठ संख्याओं की एक एरे प्राप्त करता है जिनके लिए प्रिव्यू छवियां उत्पन्न की जाएँगी।


**Returns:**
int[] - पृष्ठ संख्याओं की एरे

### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


उन पृष्ठ संख्याओं की एक एरे सेट करता है जिनके लिए प्रिव्यू छवियां उत्पन्न की जाएँगी।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int[] | पृष्ठ संख्याओं की एरे |
|

### getPreviewFormat() {#getPreviewFormat--}
```
public final PreviewFormats getPreviewFormat()
```


प्रिव्यू छवियों का फ़ॉर्मेट प्राप्त करता है।


**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - preview images format

### setPreviewFormat(PreviewFormats value) {#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-}
```
public final void setPreviewFormat(PreviewFormats value)
```


प्रिव्यू छवियों का फ़ॉर्मेट सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) | प्रिव्यू छवियों का फ़ॉर्मेट |
|


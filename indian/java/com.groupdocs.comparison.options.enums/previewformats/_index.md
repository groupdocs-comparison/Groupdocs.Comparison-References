---
title: "PreviewFormats"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "दस्तावेज़ तुलना के लिए समर्थित प्रीव्यू फ़ॉर्मेट्स को सूचीबद्ध करता है।"
type: docs
weight: 15
url: /hi/java/com.groupdocs.comparison.options.enums/previewformats/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PreviewFormats extends Enum<PreviewFormats>
```

दस्तावेज़ तुलना के लिए समर्थित प्रीव्यू फ़ॉर्मेट्स को सूचीबद्ध करता है।
PreviewFormats enum उन फ़ॉर्मेट्स की सूची प्रदान करता है जिन्हें तुलना किए गए दस्तावेज़ों के पूर्वावलोकन बनाने के लिए उपयोग किया जा सकता है।

समर्थित फ़ॉर्मेट्स में शामिल हैं:

* #PNG.PNG - Portable Network Graphics (.png)
* #JPEG.JPEG - Joint Photographic Experts Group (.jpeg)
* #BMP.BMP - Bitmap Picture (.bmp)


उदाहरण उपयोग:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    PreviewOptions previewOptions = new PreviewOptions(
            pageNumber -> Files.newOutputStream(Paths.get(String.format("preview-page_%d.png", pageNumber)))
    );
    previewOptions.setPreviewFormat(PreviewFormats.PNG);

    comparer.getTargets().get(0).generatePreview(previewOptions);
 }
 
````


## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
|  | [PNG](#PNG) | PNG - यदि पृष्ठ में कई रंगीन ग्राफ़िक्स हों तो यह काफी डिस्क स्पेस या नेटवर्क ट्रैफ़िक का उपभोग कर सकता है। |
|
|  | [JPEG](#JPEG) | Jpeg - कम डिस्क स्पेस उपयोग और नेटवर्क ट्रैफ़िक के साथ तेज़ प्रोसेसिंग प्रदान करता है, लेकिन इससे छवि की गुणवत्ता कम हो सकती है। |
|
|  | [BMP](#BMP) | BMP - सर्वोत्तम छवि गुणवत्ता प्रदान करता है लेकिन अधिक डिस्क स्पेस उपयोग और नेटवर्क ट्रैफ़िक के साथ धीमी प्रोसेसिंग की आवश्यकता होती है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | PreviewFormats की स्ट्रिंग प्रतिनिधित्व को पार्स करके enum स्थिरांक प्राप्त करता है। |
|
|  | [toString()](#toString--) | PreviewFormats का स्ट्रिंग प्रतिनिधित्व। |
|
### PNG {#PNG}
```
public static final PreviewFormats PNG
```


PNG - यदि पृष्ठ में कई रंगीन ग्राफ़िक्स हों तो यह काफी डिस्क स्पेस या नेटवर्क ट्रैफ़िक का उपभोग कर सकता है। डिफ़ॉल्ट पूर्वावलोकन फ़ॉर्मेट।


### JPEG {#JPEG}
```
public static final PreviewFormats JPEG
```


Jpeg - कम डिस्क स्पेस उपयोग और नेटवर्क ट्रैफ़िक के साथ तेज़ प्रोसेसिंग प्रदान करता है, लेकिन इससे छवि की गुणवत्ता कम हो सकती है।


### BMP {#BMP}
```
public static final PreviewFormats BMP
```


BMP - सर्वोत्तम छवि गुणवत्ता प्रदान करता है लेकिन अधिक डिस्क स्पेस उपयोग और नेटवर्क ट्रैफ़िक के साथ धीमी प्रोसेसिंग की आवश्यकता होती है।


### values() {#values--}
```
public static PreviewFormats[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.PreviewFormats[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PreviewFormats valueOf(String name)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PreviewFormats fromString(String toStringValue)
```


PreviewFormats की स्ट्रिंग प्रतिनिधित्व को पार्स करके enum स्थिरांक प्राप्त करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | toStringValue | java.lang.String | PreviewFormats का स्ट्रिंग प्रतिनिधित्व |
|

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - PreviewFormats enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


PreviewFormats का स्ट्रिंग प्रतिनिधित्व।


**Returns:**
java.lang.String - enum स्थिरांक का स्ट्रिंग मान


---
title: "OriginalSize"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "तुलना परिणाम में दस्तावेज़ का मूल आकार दर्शाता है।"
type: docs
weight: 14
url: /hi/java/com.groupdocs.comparison.options/originalsize/
---
**Inheritance:**
java.lang.Object
```
public class OriginalSize
```

तुलना परिणाम में दस्तावेज़ का मूल आकार दर्शाता है।


मूल आकार में दस्तावेज़ के पृष्ठों की आयाम (चौड़ाई और ऊँचाई) शामिल हैं।


उदाहरण उपयोग:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     CompareOptions compareOptions = new CompareOptions();
     final OriginalSize originalSize = compareOptions.getOriginalSize();
     originalSize.setWidth(480);
     originalSize.setHeight(640);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [OriginalSize()](#OriginalSize--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getWidth()](#getWidth--) | दस्तावेज़ के पृष्ठों की चौड़ाई प्राप्त करता है। |
|
|  | [setWidth(int value)](#setWidth-int-) | दस्तावेज़ के पृष्ठों की चौड़ाई सेट करता है। |
|
|  | [getHeight()](#getHeight--) | दस्तावेज़ के पृष्ठों की ऊँचाई प्राप्त करता है। |
|
|  | [setHeight(int value)](#setHeight-int-) | दस्तावेज़ के पृष्ठों की ऊँचाई सेट करता है। |
|
### OriginalSize() {#OriginalSize--}
```
public OriginalSize()
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


दस्तावेज़ के पृष्ठों की चौड़ाई प्राप्त करता है।


**Returns:**
int - दस्तावेज़ के पृष्ठों की चौड़ाई।

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


दस्तावेज़ के पृष्ठों की चौड़ाई सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | दस्तावेज़ के पृष्ठों की चौड़ाई। |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


दस्तावेज़ के पृष्ठों की ऊँचाई प्राप्त करता है।


**Returns:**
int - दस्तावेज़ के पृष्ठों की ऊँचाई।

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


दस्तावेज़ के पृष्ठों की ऊँचाई सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | दस्तावेज़ के पृष्ठों की ऊँचाई। |
|


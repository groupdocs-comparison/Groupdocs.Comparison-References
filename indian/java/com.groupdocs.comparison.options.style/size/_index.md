---
title: "Size"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "तुलना में दस्तावेज़ के आकार को दर्शाता है।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.comparison.options.style/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

तुलना में दस्तावेज़ के आकार को दर्शाता है।


उदाहरण उपयोग:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final Size originalSize = new Size(100, 200);

     StyleSettings styleSettings = new StyleSettings();
     styleSettings.setOriginalSize(originalSize);

     final CompareOptions compareOptions = new CompareOptions();
     compareOptions.setInsertedItemStyle(styleSettings);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [Size()](#Size--) | Size क्लास का नया उदाहरण प्रारंभ करता है। |
|
|  | [Size(int width, int height)](#Size-int-int-) | Size क्लास का नया उदाहरण दस्तावेज़ की चौड़ाई और ऊँचाई के साथ प्रारंभ करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getWidth()](#getWidth--) | मूल दस्तावेज़ की चौड़ाई प्राप्त करता है। |
|
|  | [setWidth(int value)](#setWidth-int-) | मूल दस्तावेज़ की चौड़ाई सेट करता है। |
|
|  | [getHeight()](#getHeight--) | मूल दस्तावेज़ की ऊँचाई प्राप्त करता है। |
|
|  | [setHeight(int value)](#setHeight-int-) | मूल दस्तावेज़ की ऊँचाई सेट करता है। |
|
### Size() {#Size--}
```
public Size()
```


Size क्लास का नया उदाहरण प्रारंभ करता है।


### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Size क्लास का नया उदाहरण दस्तावेज़ की चौड़ाई और ऊँचाई के साथ प्रारंभ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | int |  |
| height | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


मूल दस्तावेज़ की चौड़ाई प्राप्त करता है।


**Returns:**
int - दस्तावेज़ की चौड़ाई

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


मूल दस्तावेज़ की चौड़ाई सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | दस्तावेज़ की चौड़ाई |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


मूल दस्तावेज़ की ऊँचाई प्राप्त करता है।


**Returns:**
int - दस्तावेज़ की ऊँचाई

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


मूल दस्तावेज़ की ऊँचाई सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | दस्तावेज़ की ऊँचाई |
|


---
title: "Rectangle"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Rectangle क्लास दस्तावेज़ पर बदलित क्षेत्र को दर्शाती है।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.comparison.result/rectangle/
---
**Inheritance:**
java.lang.Object
```
public final class Rectangle
```

Rectangle क्लास दस्तावेज़ पर बदलित क्षेत्र को दर्शाती है।


उदाहरण उपयोग:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare(resultFile);
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo change : changes) {
         final Rectangle box = change.getBox();
         // Print the changed area on page
         System.out.println("Changed area on a page: "
                 + box.getX() + ", " + box.getY() + ", " + box.getWidth() + ", " + box.getHeight());
     }
 }
 
````


## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [Rectangle()](#Rectangle--) | Rectangle क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [Rectangle(Rectangle other)](#Rectangle-com.groupdocs.comparison.result.Rectangle-) | निर्दिष्ट आयत की प्रतिलिपि वाला नया Rectangle ऑब्जेक्ट बनाता है। |
|
|  | [Rectangle(double x, double y, double width, double height)](#Rectangle-double-double-double-double-) | निर्दिष्ट x, y, चौड़ाई और ऊँचाई के साथ Rectangle क्लास का नया इंस्टेंस बनाता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getHeight()](#getHeight--) | आयत की ऊँचाई प्राप्त करता है। |
|
|  | [setHeight(double value)](#setHeight-double-) | आयत की ऊँचाई सेट करता है। |
|
|  | [getWidth()](#getWidth--) | आयत की चौड़ाई प्राप्त करता है। |
|
|  | [setWidth(double value)](#setWidth-double-) | आयत की चौड़ाई सेट करता है। |
|
|  | [getX()](#getX--) | आयत के शीर्ष-बाएँ कोने के x-निर्देशांक को प्राप्त करता है। |
|
|  | [setX(double value)](#setX-double-) | आयत के शीर्ष-बाएँ कोने के x-निर्देशांक को सेट करता है। |
|
|  | [getY()](#getY--) | आयत के शीर्ष-बाएँ कोने के y-निर्देशांक को प्राप्त करता है। |
|
|  | [setY(double value)](#setY-double-) | आयत के शीर्ष-बाएँ कोने के y-निर्देशांक को सेट करता है। |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | {@inheritDoc} |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
|  | [toString()](#toString--) | {@inheritDoc} |
|
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


Rectangle क्लास का नया इंस्टेंस प्रारंभ करता है।


### Rectangle(Rectangle other) {#Rectangle-com.groupdocs.comparison.result.Rectangle-}
```
public Rectangle(Rectangle other)
```


निर्दिष्ट आयत की प्रतिलिपि वाला नया Rectangle ऑब्जेक्ट बनाता है।

<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | other | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | कॉपी किए जाने वाला आयत |
|

### Rectangle(double x, double y, double width, double height) {#Rectangle-double-double-double-double-}
```
public Rectangle(double x, double y, double width, double height)
```


निर्दिष्ट x, y, चौड़ाई और ऊँचाई के साथ Rectangle क्लास का नया इंस्टेंस बनाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | x | double | आयत के ऊपर-बाएँ कोने का x-निर्देशांक |
|
|  | y | double | आयत के ऊपर-बाएँ कोने का y-निर्देशांक |
|
|  | width | double | आयत की चौड़ाई |
|
|  | height | double | आयत की ऊँचाई |
|

### getHeight() {#getHeight--}
```
public double getHeight()
```


आयत की ऊँचाई प्राप्त करता है।


**Returns:**
double - आयत की ऊँचाई

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


आयत की ऊँचाई सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | double | आयत की ऊँचाई |
|

### getWidth() {#getWidth--}
```
public double getWidth()
```


आयत की चौड़ाई प्राप्त करता है।


**Returns:**
double - आयत की चौड़ाई

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


आयत की चौड़ाई सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | double | आयत की चौड़ाई |
|

### getX() {#getX--}
```
public double getX()
```


आयत के शीर्ष-बाएँ कोने के x-निर्देशांक को प्राप्त करता है।


**Returns:**
double - आयत के ऊपर-बाएँ कोने का x-निर्देशांक

### setX(double value) {#setX-double-}
```
public void setX(double value)
```


आयत के शीर्ष-बाएँ कोने के x-निर्देशांक को सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | double | आयत के ऊपर-बाएँ कोने का x-निर्देशांक |
|

### getY() {#getY--}
```
public double getY()
```


आयत के शीर्ष-बाएँ कोने के y-निर्देशांक को प्राप्त करता है।


**Returns:**
double - आयत के ऊपर-बाएँ कोने का y-निर्देशांक

### setY(double value) {#setY-double-}
```
public void setY(double value)
```


आयत के शीर्ष-बाएँ कोने के y-निर्देशांक को सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | double | आयत के ऊपर-बाएँ कोने का y-निर्देशांक |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| o | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String

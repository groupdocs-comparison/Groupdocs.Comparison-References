---
title: "StyleChangeInfo"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "StyleChangeInfo क्लास तुलना किए गए दस्तावेज़ में शैली परिवर्तन की जानकारी दर्शाती है।"
type: docs
weight: 13
url: /hi/java/com.groupdocs.comparison.result/stylechangeinfo/
---
**Inheritance:**
java.lang.Object
```
public class StyleChangeInfo
```

StyleChangeInfo क्लास तुलना किए गए दस्तावेज़ में शैली परिवर्तन की जानकारी दर्शाती है।


यह बदलें हुए प्रॉपर्टी नाम, परिवर्तन से पहले और बाद के मान आदि जैसी विवरण प्रदान करता है।
दस्तावेज़ तुलना प्रक्रिया के दौरान स्टाइल परिवर्तन की जानकारी प्राप्त करने के लिए इस क्लास का उपयोग करें।


उदाहरण उपयोग:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare();
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo change : changes) {
         // Access the style change information
         final List styleChanges = change.getStyleChanges();
         for (StyleChangeInfo styleChange : styleChanges) {
             // Print the style change information
             System.out.println("PropertyName: " + styleChange.getPropertyName());
             System.out.println("OldValue: " + styleChange.getOldValue());
             System.out.println("NewValue: " + styleChange.getNewValue());
         }
     }
 }
 
````


## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [StyleChangeInfo()](#StyleChangeInfo--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getPropertyName()](#getPropertyName--) | बदलाए गए प्रॉपर्टी का नाम प्राप्त करता है। |
|
|  | [setPropertyName(String value)](#setPropertyName-java.lang.String-) | बदलाए गए प्रॉपर्टी का नाम सेट करता है। |
|
|  | [getNewValue()](#getNewValue--) | प्रॉपर्टी का नया मान प्राप्त करता है। |
|
|  | [setNewValue(Object value)](#setNewValue-java.lang.Object-) | प्रॉपर्टी का नया मान सेट करता है। |
|
|  | [getOldValue()](#getOldValue--) | प्रॉपर्टी का पुराना मान प्राप्त करता है। |
|
|  | [setOldValue(Object value)](#setOldValue-java.lang.Object-) | प्रॉपर्टी का पुराना मान सेट करता है। |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | {@inheritDoc} |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
### StyleChangeInfo() {#StyleChangeInfo--}
```
public StyleChangeInfo()
```


### getPropertyName() {#getPropertyName--}
```
public final String getPropertyName()
```


बदलाए गए प्रॉपर्टी का नाम प्राप्त करता है।


**Returns:**
java.lang.String - प्रॉपर्टी नाम

### setPropertyName(String value) {#setPropertyName-java.lang.String-}
```
public final void setPropertyName(String value)
```


बदलाए गए प्रॉपर्टी का नाम सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | प्रॉपर्टी नाम |
|

### getNewValue() {#getNewValue--}
```
public final Object getNewValue()
```


प्रॉपर्टी का नया मान प्राप्त करता है।


**Returns:**
java.lang.Object - प्रॉपर्टी का नया मान

### setNewValue(Object value) {#setNewValue-java.lang.Object-}
```
public final void setNewValue(Object value)
```


प्रॉपर्टी का नया मान सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.Object | प्रॉपर्टी का नया मान |
|

### getOldValue() {#getOldValue--}
```
public final Object getOldValue()
```


प्रॉपर्टी का पुराना मान प्राप्त करता है।


**Returns:**
java.lang.Object - प्रॉपर्टी का पुराना मान

### setOldValue(Object value) {#setOldValue-java.lang.Object-}
```
public final void setOldValue(Object value)
```


प्रॉपर्टी का पुराना मान सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.Object | प्रॉपर्टी का पुराना मान |
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

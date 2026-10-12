---
title: "ChangeType"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "ChangeType enum दस्तावेज़ तुलना प्रक्रिया के दौरान हो सकने वाले परिवर्तन प्रकारों को दर्शाता है।"
type: docs
weight: 14
url: /hi/java/com.groupdocs.comparison.result/changetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ChangeType extends Enum<ChangeType>
```

ChangeType enum दस्तावेज़ तुलना प्रक्रिया के दौरान हो सकने वाले परिवर्तन प्रकारों को दर्शाता है।


इस enum में प्रत्येक स्थिरांक परिवर्तन के एक विशिष्ट प्रकार का प्रतिनिधित्व करता है और एक मानव-पठनीय विवरण तथा एक संख्यात्मक मान प्रदान करता है।


उदाहरण उपयोग:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo changeInfo : changes) {
         // Get the ChangeType for a specific change
         final ChangeType changeType = changeInfo.getType();
         // Print the ChangeType information
         System.out.println("Description: " + changeType.toString());
         System.out.println("Value: " + changeType.toInt());
     }
 }
 
````


## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
|  | [NONE](#NONE) | कोई परिवर्तन नहीं दर्शाता है। |
|
|  | [MODIFIED](#MODIFIED) | संशोधित परिवर्तन को दर्शाता है। |
|
|  | [INSERTED](#INSERTED) | डाला गया परिवर्तन को दर्शाता है। |
|
|  | [DELETED](#DELETED) | हटाया गया परिवर्तन को दर्शाता है। |
|
|  | [ADDED](#ADDED) | जोड़ा गया परिवर्तन को दर्शाता है। |
|
|  | [NOT_MODIFIED](#NOT-MODIFIED) | अपरिवर्तित परिवर्तन को दर्शाता है। |
|
|  | [STYLE_CHANGED](#STYLE-CHANGED) | शैली बदलें हुए परिवर्तन को दर्शाता है। |
|
|  | [RESIZED](#RESIZED) | आकार बदला गया परिवर्तन का प्रतिनिधित्व करता है। |
|
|  | [MOVED](#MOVED) | स्थानांतरित परिवर्तन का प्रतिनिधित्व करता है। |
|
|  | [MOVED_AND_RESIZED](#MOVED-AND-RESIZED) | स्थानांतरित और आकार बदला गया परिवर्तन का प्रतिनिधित्व करता है। |
|
|  | [SHIFTED_AND_RESIZED](#SHIFTED-AND-RESIZED) | स्लाइड किए गए और आकार बदले गए परिवर्तन का प्रतिनिधित्व करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | ChangeType की स्ट्रिंग प्रतिनिधित्व को पार्स करके enum स्थिरांक प्राप्त करता है। |
|
|  | [fromInt(int intValue)](#fromInt-int-) | प्रदान किए गए संख्यात्मक मान का उपयोग करके enum ChangeType का नया स्थिरांक बनाता है। |
|
|  | [toString()](#toString--) | ChangeType की स्ट्रिंग प्रतिनिधित्व। |
|
|  | [toInt()](#toInt--) | ChangeType का संख्यात्मक प्रतिनिधित्व। |
|
### NONE {#NONE}
```
public static final ChangeType NONE
```


कोई परिवर्तन नहीं दर्शाता है।


### MODIFIED {#MODIFIED}
```
public static final ChangeType MODIFIED
```


संशोधित परिवर्तन को दर्शाता है।


### INSERTED {#INSERTED}
```
public static final ChangeType INSERTED
```


डाला गया परिवर्तन को दर्शाता है।


### DELETED {#DELETED}
```
public static final ChangeType DELETED
```


हटाया गया परिवर्तन को दर्शाता है।


### ADDED {#ADDED}
```
public static final ChangeType ADDED
```


जोड़ा गया परिवर्तन को दर्शाता है।


### NOT_MODIFIED {#NOT-MODIFIED}
```
public static final ChangeType NOT_MODIFIED
```


अपरिवर्तित परिवर्तन को दर्शाता है।


### STYLE_CHANGED {#STYLE-CHANGED}
```
public static final ChangeType STYLE_CHANGED
```


शैली बदलें हुए परिवर्तन को दर्शाता है।


### RESIZED {#RESIZED}
```
public static final ChangeType RESIZED
```


आकार बदला गया परिवर्तन का प्रतिनिधित्व करता है।


### MOVED {#MOVED}
```
public static final ChangeType MOVED
```


स्थानांतरित परिवर्तन का प्रतिनिधित्व करता है।


### MOVED_AND_RESIZED {#MOVED-AND-RESIZED}
```
public static final ChangeType MOVED_AND_RESIZED
```


स्थानांतरित और आकार बदला गया परिवर्तन का प्रतिनिधित्व करता है।


### SHIFTED_AND_RESIZED {#SHIFTED-AND-RESIZED}
```
public static final ChangeType SHIFTED_AND_RESIZED
```


स्लाइड किए गए और आकार बदले गए परिवर्तन का प्रतिनिधित्व करता है।


### values() {#values--}
```
public static ChangeType[] values()
```




**Returns:**
com.groupdocs.comparison.result.ChangeType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ChangeType valueOf(String name)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ChangeType fromString(String toStringValue)
```


ChangeType की स्ट्रिंग प्रतिनिधित्व को पार्स करके enum स्थिरांक प्राप्त करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | toStringValue | java.lang.String | ChangeType की स्ट्रिंग प्रतिनिधित्व |
|

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with input string

### fromInt(int intValue) {#fromInt-int-}
```
public static ChangeType fromInt(int intValue)
```


प्रदान किए गए संख्यात्मक मान का उपयोग करके enum ChangeType का नया स्थिरांक बनाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | intValue | int | ChangeType का संख्यात्मक प्रतिनिधित्व |
|

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with numeric value

### toString() {#toString--}
```
public String toString()
```


ChangeType की स्ट्रिंग प्रतिनिधित्व।


**Returns:**
java.lang.String - enum स्थिरांक का स्ट्रिंग मान

### toInt() {#toInt--}
```
public int toInt()
```


ChangeType का संख्यात्मक प्रतिनिधित्व।


**Returns:**
int - enum स्थिरांक का संख्यात्मक मान


---
title: "ComparisonAction"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "ComparisonAction enum दस्तावेज़ तुलना प्रक्रिया के दौरान परिवर्तन पर लागू की जा सकने वाली क्रियाओं को दर्शाता है।"
type: docs
weight: 15
url: /hi/java/com.groupdocs.comparison.result/comparisonaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonAction extends Enum<ComparisonAction>
```

ComparisonAction enum दस्तावेज़ तुलना प्रक्रिया के दौरान परिवर्तन पर लागू की जा सकने वाली क्रियाओं को दर्शाता है।


इस enum में प्रत्येक स्थिरांक एक विशिष्ट क्रिया का प्रतिनिधित्व करता है और एक मानव-पठनीय विवरण तथा एक संख्यात्मक मान प्रदान करता है।


उदाहरण उपयोग:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();

     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo changeInfo : changes) {
         if (changeInfo.getId() % 2 == 0) {
             changeInfo.setComparisonAction(ComparisonAction.REJECT);
         }
     }
     comparer.applyChanges(resultFile, changes);
 }
 
````


## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
|  | [NONE](#NONE) | कोई क्रिया नहीं दर्शाता है। |
|
|  | [ACCEPT](#ACCEPT) | स्वीकार क्रिया को दर्शाता है। |
|
|  | [REJECT](#REJECT) | अस्वीकार क्रिया को दर्शाता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | ComparisonAction की स्ट्रिंग प्रतिनिधित्व को पार्स करके enum स्थिरांक प्राप्त करता है। |
|
|  | [fromInt(int intValue)](#fromInt-int-) | प्रदान किए गए संख्यात्मक मान का उपयोग करके enum ComparisonAction का नया स्थिरांक बनाता है। |
|
|  | [toString()](#toString--) | ComparisonAction का स्ट्रिंग प्रतिनिधित्व। |
|
|  | [toInt()](#toInt--) | ComparisonAction का संख्यात्मक प्रतिनिधित्व। |
|
### NONE {#NONE}
```
public static final ComparisonAction NONE
```


कोई क्रिया नहीं दर्शाता है। परिवर्तन का कोई प्रभाव नहीं होगा।


### ACCEPT {#ACCEPT}
```
public static final ComparisonAction ACCEPT
```


स्वीकार क्रिया को दर्शाता है। परिवर्तन परिणाम फ़ाइल में दिखाई देगा।


### REJECT {#REJECT}
```
public static final ComparisonAction REJECT
```


अस्वीकार क्रिया को दर्शाता है। परिवर्तन परिणाम फ़ाइल में अदृश्य रहेगा।


### values() {#values--}
```
public static ComparisonAction[] values()
```




**Returns:**
com.groupdocs.comparison.result.ComparisonAction[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ComparisonAction valueOf(String name)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonAction fromString(String toStringValue)
```


ComparisonAction की स्ट्रिंग प्रतिनिधित्व को पार्स करके enum स्थिरांक प्राप्त करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | toStringValue | java.lang.String | ComparisonAction का स्ट्रिंग प्रतिनिधित्व |
|

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with input string

### fromInt(int intValue) {#fromInt-int-}
```
public static ComparisonAction fromInt(int intValue)
```


प्रदान किए गए संख्यात्मक मान का उपयोग करके enum ComparisonAction का नया स्थिरांक बनाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | intValue | int | ComparisonAction का संख्यात्मक प्रतिनिधित्व |
|

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with numeric value

### toString() {#toString--}
```
public String toString()
```


ComparisonAction का स्ट्रिंग प्रतिनिधित्व।


**Returns:**
java.lang.String - enum स्थिरांक का स्ट्रिंग मान

### toInt() {#toInt--}
```
public int toInt()
```


ComparisonAction का संख्यात्मक प्रतिनिधित्व।


**Returns:**
int - enum स्थिरांक का संख्यात्मक मान


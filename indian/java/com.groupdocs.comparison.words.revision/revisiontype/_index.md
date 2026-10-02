---
title: "RevisionType"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "दस्तावेज़ में संशोधनों के प्रकारों को दर्शाता है।"
type: docs
weight: 14
url: /hi/java/com.groupdocs.comparison.words.revision/revisiontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionType extends Enum<RevisionType>
```

दस्तावेज़ में संशोधनों के प्रकारों को दर्शाता है।


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


## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
|  | [INSERTION](#INSERTION) | दस्तावेज़ में नया सामग्री सम्मिलित होने पर एक प्रकार का प्रतिनिधित्व करता है। |
|
|  | [DELETION](#DELETION) | दस्तावेज़ से सामग्री हटाए जाने पर एक प्रकार का प्रतिनिधित्व करता है। |
|
|  | [FORMAT_CHANGE](#FORMAT-CHANGE) | पैरेंट नोड पर फ़ॉर्मेटिंग परिवर्तन लागू होने पर एक प्रकार का प्रतिनिधित्व करता है। |
|
|  | [STYLE_DEFINITION_CHANGE](#STYLE-DEFINITION-CHANGE) | पैरेंट शैली पर फ़ॉर्मेटिंग परिवर्तन लागू होने पर एक प्रकार का प्रतिनिधित्व करता है। |
|
|  | [MOVING](#MOVING) | दस्तावेज़ में सामग्री स्थानांतरित होने पर एक प्रकार का प्रतिनिधित्व करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromInt(int toIntValue)](#fromInt-int-) | प्रदान किए गए संख्यात्मक मान का उपयोग करके enum RevisionType का नया स्थिरांक बनाता है। |
|
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | enum स्थिरांक प्राप्त करने के लिए RevisionType की स्ट्रिंग प्रतिनिधित्व को पार्स करता है। |
|
|  | [toInt()](#toInt--) | RevisionType का संख्यात्मक प्रतिनिधित्व। |
|
|  | [toString()](#toString--) | RevisionType का स्ट्रिंग प्रतिनिधित्व। |
|
### INSERTION {#INSERTION}
```
public static final RevisionType INSERTION
```


दस्तावेज़ में नया सामग्री सम्मिलित होने पर एक प्रकार का प्रतिनिधित्व करता है।


### DELETION {#DELETION}
```
public static final RevisionType DELETION
```


दस्तावेज़ से सामग्री हटाए जाने पर एक प्रकार का प्रतिनिधित्व करता है।


### FORMAT_CHANGE {#FORMAT-CHANGE}
```
public static final RevisionType FORMAT_CHANGE
```


पैरेंट नोड पर फ़ॉर्मेटिंग परिवर्तन लागू होने पर एक प्रकार का प्रतिनिधित्व करता है।


### STYLE_DEFINITION_CHANGE {#STYLE-DEFINITION-CHANGE}
```
public static final RevisionType STYLE_DEFINITION_CHANGE
```


पैरेंट शैली पर फ़ॉर्मेटिंग परिवर्तन लागू होने पर एक प्रकार का प्रतिनिधित्व करता है।


### MOVING {#MOVING}
```
public static final RevisionType MOVING
```


दस्तावेज़ में सामग्री स्थानांतरित होने पर एक प्रकार का प्रतिनिधित्व करता है।


### values() {#values--}
```
public static RevisionType[] values()
```




**Returns:**
com.groupdocs.comparison.words.revision.RevisionType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static RevisionType valueOf(String name)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype)
### fromInt(int toIntValue) {#fromInt-int-}
```
public static RevisionType fromInt(int toIntValue)
```


प्रदान किए गए संख्यात्मक मान का उपयोग करके enum RevisionType का नया स्थिरांक बनाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | toIntValue | int | RevisionType का संख्यात्मक प्रतिनिधित्व |
|

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with numeric value

### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static RevisionType fromString(String toStringValue)
```


enum स्थिरांक प्राप्त करने के लिए RevisionType की स्ट्रिंग प्रतिनिधित्व को पार्स करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | toStringValue | java.lang.String | RevisionType का स्ट्रिंग प्रतिनिधित्व |
|

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with input string

### toInt() {#toInt--}
```
public int toInt()
```


RevisionType का संख्यात्मक प्रतिनिधित्व।


**Returns:**
int - enum स्थिरांक का संख्यात्मक मान

### toString() {#toString--}
```
public String toString()
```


RevisionType का स्ट्रिंग प्रतिनिधित्व।


**Returns:**
java.lang.String - enum स्थिरांक का स्ट्रिंग मान


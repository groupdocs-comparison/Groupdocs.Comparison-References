---
title: "GetChangeOptions"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "तुलना परिणाम से विशिष्ट परिवर्तन प्रकारों को प्राप्त करने के लिए फ़िल्टरिंग को कॉन्फ़िगर करने की अनुमति देता है।"
type: docs
weight: 13
url: /hi/java/com.groupdocs.comparison.options/getchangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class GetChangeOptions
```

तुलना परिणाम से विशिष्ट परिवर्तन प्रकारों को प्राप्त करने के लिए फ़िल्टरिंग को कॉन्फ़िगर करने की अनुमति देता है।


उदाहरण उपयोग:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();

     GetChangeOptions getChangeOptions = new GetChangeOptions();

     getChangeOptions.setFilter(ChangeType.DELETED);

     ChangeInfo[] changes = comparer.getChanges(getChangeOptions);
     System.out.println(Arrays.toString(changes));
 }
 
````


## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [GetChangeOptions()](#GetChangeOptions--) | GetChangeOptions क्लास का नया उदाहरण प्रारंभ करता है। |
|
|  | [GetChangeOptions(ChangeType filter)](#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-) | निर्दिष्ट फ़िल्टर प्रकार के लिए GetChangeOptions क्लास का नया उदाहरण प्रारंभ करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getFilter()](#getFilter--) | तुलना परिणाम से विशिष्ट परिवर्तन प्रकारों को प्राप्त करने के लिए फ़िल्टर को प्राप्त करता है। |
|
|  | [setFilter(ChangeType value)](#setFilter-com.groupdocs.comparison.result.ChangeType-) | तुलना परिणाम से विशिष्ट परिवर्तन प्रकारों को प्राप्त करने के लिए फ़िल्टर को सेट करता है। |
|
### GetChangeOptions() {#GetChangeOptions--}
```
public GetChangeOptions()
```


GetChangeOptions क्लास का नया उदाहरण प्रारंभ करता है।


### GetChangeOptions(ChangeType filter) {#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-}
```
public GetChangeOptions(ChangeType filter)
```


निर्दिष्ट फ़िल्टर प्रकार के लिए GetChangeOptions क्लास का नया उदाहरण प्रारंभ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filter | [ChangeType](../../com.groupdocs.comparison.result/changetype) |  |

### getFilter() {#getFilter--}
```
public final ChangeType getFilter()
```


तुलना परिणाम से विशिष्ट परिवर्तन प्रकारों को प्राप्त करने के लिए फ़िल्टर को प्राप्त करता है।


**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the filter specifying the types of changes to be retrieved.

### setFilter(ChangeType value) {#setFilter-com.groupdocs.comparison.result.ChangeType-}
```
public final void setFilter(ChangeType value)
```


तुलना परिणाम से विशिष्ट परिवर्तन प्रकारों को प्राप्त करने के लिए फ़िल्टर को सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [ChangeType](../../com.groupdocs.comparison.result/changetype) | फ़िल्टर जो प्राप्त किए जाने वाले परिवर्तन प्रकारों को निर्दिष्ट करता है। |
|


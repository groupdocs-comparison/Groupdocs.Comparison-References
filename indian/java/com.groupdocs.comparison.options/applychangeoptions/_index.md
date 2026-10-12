---
title: "ApplyChangeOptions"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "परिणामी दस्तावेज़ पर लागू करने से पहले परिवर्तन सूची को अपडेट करने की अनुमति देता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.comparison.options/applychangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyChangeOptions
```

परिणामी दस्तावेज़ पर लागू करने से पहले परिवर्तन सूची को अपडेट करने की अनुमति देता है।


उदाहरण उपयोग:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();
     ChangeInfo[] changes = comparer.getChanges();
     changes[0].setComparisonAction(ComparisonAction.REJECT);

     final ApplyChangeOptions applyChangeOptions = new ApplyChangeOptions(changes);

     comparer.applyChanges(resultFile, applyChangeOptions);
 }
 
````


## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [ApplyChangeOptions()](#ApplyChangeOptions--) | ApplyChangeOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [ApplyChangeOptions(List<ChangeInfo> changes)](#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | ApplyChangeOptions क्लास का नया इंस्टेंस परिवर्तनों की सूची के साथ इनिशियलाइज़ करता है। |
|
|  | [ApplyChangeOptions(ChangeInfo[] changes)](#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---) | ApplyChangeOptions क्लास का नया इंस्टेंस परिवर्तनों की एरे के साथ इनिशियलाइज़ करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getChanges()](#getChanges--) | परिणामी दस्तावेज़ पर लागू किए जाने वाले परिवर्तनों की एरे प्राप्त करता है। |
|
|  | [setChanges(ChangeInfo[] value)](#setChanges-com.groupdocs.comparison.result.ChangeInfo---) | परिणामी दस्तावेज़ पर लागू किए जाने वाले परिवर्तनों की एरे सेट करता है। |
|
|  | [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | परिणामी दस्तावेज़ पर लागू किए जाने वाले परिवर्तनों की सूची सेट करता है। |
|
|  | [isSaveOriginalState()](#isSaveOriginalState--) | एक फ़्लैग प्राप्त करता है जो निर्धारित करता है कि मूल स्थिति सहेजी जानी चाहिए या नहीं। |
|
|  | [setSaveOriginalState(boolean saveOriginalState)](#setSaveOriginalState-boolean-) | एक फ़्लैग सेट करता है जो निर्धारित करता है कि मूल स्थिति सहेजी जानी चाहिए या नहीं। |
|
### ApplyChangeOptions() {#ApplyChangeOptions--}
```
public ApplyChangeOptions()
```


ApplyChangeOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।


### ApplyChangeOptions(List<ChangeInfo> changes) {#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public ApplyChangeOptions(List<ChangeInfo> changes)
```


ApplyChangeOptions क्लास का नया इंस्टेंस परिवर्तनों की सूची के साथ इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | परिवर्तन | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | लागू किए जाने वाले परिवर्तनों की सूची |
|

### ApplyChangeOptions(ChangeInfo[] changes) {#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---}
```
public ApplyChangeOptions(ChangeInfo[] changes)
```


ApplyChangeOptions क्लास का नया इंस्टेंस परिवर्तनों की एरे के साथ इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | changes | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | लागू किए जाने वाले परिवर्तनों की सूची |
|

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


परिणामी दस्तावेज़ पर लागू किए जाने वाले परिवर्तनों की एरे प्राप्त करता है।


**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - लागू किए जाने वाले परिवर्तनों की एरे

### setChanges(ChangeInfo[] value) {#setChanges-com.groupdocs.comparison.result.ChangeInfo---}
```
public final void setChanges(ChangeInfo[] value)
```


परिणामी दस्तावेज़ पर लागू किए जाने वाले परिवर्तनों की एरे सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | लागू किए जाने वाले परिवर्तनों की एरे |
|

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


परिणामी दस्तावेज़ पर लागू किए जाने वाले परिवर्तनों की सूची सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | लागू किए जाने वाले परिवर्तनों की सूची |
|

### isSaveOriginalState() {#isSaveOriginalState--}
```
public boolean isSaveOriginalState()
```


एक फ़्लैग प्राप्त करता है जो निर्धारित करता है कि मूल स्थिति सहेजी जानी चाहिए या नहीं। डिफ़ॉल्ट मान: false.


**Returns:**
boolean - यदि मूल स्थिति सहेजी जानी चाहिए तो true, अन्यथा false

### setSaveOriginalState(boolean saveOriginalState) {#setSaveOriginalState-boolean-}
```
public void setSaveOriginalState(boolean saveOriginalState)
```


एक फ़्लैग सेट करता है जो निर्धारित करता है कि मूल स्थिति सहेजी जानी चाहिए या नहीं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | saveOriginalState | boolean | यदि मूल स्थिति सहेजी जानी चाहिए तो true, अन्यथा false |
|


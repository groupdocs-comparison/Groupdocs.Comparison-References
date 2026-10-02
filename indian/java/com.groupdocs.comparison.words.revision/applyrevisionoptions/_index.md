---
title: "ApplyRevisionOptions"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "ApplyRevisionOptions क्लास आपको अंतिम दस्तावेज़ पर लागू होने से पहले संशोधनों की स्थिति को अपडेट करने की अनुमति देती है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.comparison.words.revision/applyrevisionoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyRevisionOptions
```

ApplyRevisionOptions क्लास आपको अंतिम दस्तावेज़ पर लागू होने से पहले संशोधनों की स्थिति को अपडेट करने की अनुमति देती है।


यह संशोधन लागू करने की प्रक्रिया को अनुकूलित करने के लिए विभिन्न कंस्ट्रक्टर और प्रॉपर्टीज़ प्रदान करता है।


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


## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [ApplyRevisionOptions()](#ApplyRevisionOptions--) | ApplyRevisionOptions क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
|
|  | [ApplyRevisionOptions(List<RevisionInfo> changes)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | निर्दिष्ट संशोधनों की सूची के साथ एक नया ApplyRevisionOptions ऑब्जेक्ट बनाता है। |
|
|  | [ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-) | निर्दिष्ट संशोधनों की सूची और एक सामान्य संशोधन क्रिया के साथ एक नया ApplyRevisionOptions ऑब्जेक्ट बनाता है। |
|
|  | [ApplyRevisionOptions(RevisionAction revisionAction)](#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-) | एक सामान्य संशोधन क्रिया के साथ एक नया ApplyRevisionOptions ऑब्जेक्ट बनाता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getChanges()](#getChanges--) | लागू किए जाने वाले संशोधनों की सूची प्राप्त करता है। |
|
|  | [setChanges(List<RevisionInfo> changes)](#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | लागू किए जाने वाले संशोधनों की सूची सेट करता है। |
|
|  | [getCommonHandler()](#getCommonHandler--) | सभी संशोधनों पर लागू होने वाली सामान्य संशोधन क्रिया प्राप्त करता है। |
|
|  | [setCommonHandler(RevisionAction commonHandler)](#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-) | सभी संशोधनों पर लागू होने वाली सामान्य संशोधन क्रिया सेट करता है। |
|
### ApplyRevisionOptions() {#ApplyRevisionOptions--}
```
public ApplyRevisionOptions()
```


ApplyRevisionOptions क्लास का एक नया इंस्टेंस प्रारंभ करता है।


### ApplyRevisionOptions(List<RevisionInfo> changes) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public ApplyRevisionOptions(List<RevisionInfo> changes)
```


निर्दिष्ट संशोधनों की सूची के साथ एक नया ApplyRevisionOptions ऑब्जेक्ट बनाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | परिवर्तन | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | लागू किए जाने वाले संशोधनों की सूची |
|

### ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)
```


निर्दिष्ट संशोधनों की सूची और एक सामान्य संशोधन क्रिया के साथ एक नया ApplyRevisionOptions ऑब्जेक्ट बनाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | परिवर्तन | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | लागू किए जाने वाले संशोधनों की सूची |
|
|  | revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | सभी संशोधनों पर लागू होने वाली सामान्य संशोधन क्रिया |
|

### ApplyRevisionOptions(RevisionAction revisionAction) {#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(RevisionAction revisionAction)
```


एक सामान्य संशोधन क्रिया के साथ एक नया ApplyRevisionOptions ऑब्जेक्ट बनाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | सभी संशोधनों पर लागू होने वाली सामान्य संशोधन क्रिया |
|

### getChanges() {#getChanges--}
```
public List<RevisionInfo> getChanges()
```


लागू किए जाने वाले संशोधनों की सूची प्राप्त करता है।


**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - संशोधनों की सूची

### setChanges(List<RevisionInfo> changes) {#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public void setChanges(List<RevisionInfo> changes)
```


लागू किए जाने वाले संशोधनों की सूची सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | परिवर्तन | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | संशोधनों की सूची |
|

### getCommonHandler() {#getCommonHandler--}
```
public RevisionAction getCommonHandler()
```


सभी संशोधनों पर लागू होने वाली सामान्य संशोधन क्रिया प्राप्त करता है।


**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the common revision action

### setCommonHandler(RevisionAction commonHandler) {#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setCommonHandler(RevisionAction commonHandler)
```


सभी संशोधनों पर लागू होने वाली सामान्य संशोधन क्रिया सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | commonHandler | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | सामान्य संशोधन क्रिया |
|


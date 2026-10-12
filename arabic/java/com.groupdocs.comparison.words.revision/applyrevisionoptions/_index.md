---
title: "ApplyRevisionOptions"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "تسمح فئة ApplyRevisionOptions لك بتحديث حالة المراجعات قبل تطبيقها على المستند النهائي."
type: docs
weight: 10
url: /ar/java/com.groupdocs.comparison.words.revision/applyrevisionoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyRevisionOptions
```

تسمح فئة ApplyRevisionOptions لك بتحديث حالة المراجعات قبل تطبيقها على المستند النهائي.


توفر هذه الفئة مُنشئات وخصائص مختلفة لتخصيص عملية تطبيق التنقيح.


مثال على الاستخدام:

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


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [ApplyRevisionOptions()](#ApplyRevisionOptions--) | تهيئ نسخة جديدة من فئة ApplyRevisionOptions. |
|
|  | [ApplyRevisionOptions(List<RevisionInfo> changes)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | ينشئ كائنًا جديدًا من ApplyRevisionOptions مع القائمة المحددة من التنقيحات. |
|
|  | [ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)](#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-) | ينشئ كائنًا جديدًا من ApplyRevisionOptions مع قائمة المراجعات المحددة وإجراء مراجعة مشترك. |
|
|  | [ApplyRevisionOptions(RevisionAction revisionAction)](#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-) | ينشئ كائنًا جديدًا من ApplyRevisionOptions مع إجراء مراجعة مشترك. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getChanges()](#getChanges--) | يحصل على قائمة المراجعات التي سيتم تطبيقها. |
|
|  | [setChanges(List<RevisionInfo> changes)](#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--) | يضبط قائمة المراجعات التي سيتم تطبيقها. |
|
|  | [getCommonHandler()](#getCommonHandler--) | يحصل على إجراء المراجعة المشترك الذي سيتم تطبيقه على جميع المراجعات. |
|
|  | [setCommonHandler(RevisionAction commonHandler)](#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-) | يضبط إجراء المراجعة المشترك الذي سيتم تطبيقه على جميع المراجعات. |
|
### ApplyRevisionOptions() {#ApplyRevisionOptions--}
```
public ApplyRevisionOptions()
```


تهيئ نسخة جديدة من فئة ApplyRevisionOptions.


### ApplyRevisionOptions(List<RevisionInfo> changes) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public ApplyRevisionOptions(List<RevisionInfo> changes)
```


ينشئ كائنًا جديدًا من ApplyRevisionOptions مع القائمة المحددة من التنقيحات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | التغييرات | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | قائمة المراجعات التي سيتم تطبيقها |
|

### ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction) {#ApplyRevisionOptions-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(List<RevisionInfo> changes, RevisionAction revisionAction)
```


ينشئ كائنًا جديدًا من ApplyRevisionOptions مع قائمة المراجعات المحددة وإجراء مراجعة مشترك.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | التغييرات | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | قائمة المراجعات التي سيتم تطبيقها |
|
|  | revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | إجراء المراجعة المشترك الذي سيتم تطبيقه على جميع المراجعات |
|

### ApplyRevisionOptions(RevisionAction revisionAction) {#ApplyRevisionOptions-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public ApplyRevisionOptions(RevisionAction revisionAction)
```


ينشئ كائنًا جديدًا من ApplyRevisionOptions مع إجراء مراجعة مشترك.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | revisionAction | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | إجراء المراجعة المشترك الذي سيتم تطبيقه على جميع المراجعات |
|

### getChanges() {#getChanges--}
```
public List<RevisionInfo> getChanges()
```


يحصل على قائمة المراجعات التي سيتم تطبيقها.


**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - قائمة المراجعات

### setChanges(List<RevisionInfo> changes) {#setChanges-java.util.List-com.groupdocs.comparison.words.revision.RevisionInfo--}
```
public void setChanges(List<RevisionInfo> changes)
```


يضبط قائمة المراجعات التي سيتم تطبيقها.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | التغييرات | java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> | قائمة المراجعات |
|

### getCommonHandler() {#getCommonHandler--}
```
public RevisionAction getCommonHandler()
```


يحصل على إجراء المراجعة المشترك الذي سيتم تطبيقه على جميع المراجعات.


**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the common revision action

### setCommonHandler(RevisionAction commonHandler) {#setCommonHandler-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setCommonHandler(RevisionAction commonHandler)
```


يضبط إجراء المراجعة المشترك الذي سيتم تطبيقه على جميع المراجعات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | commonHandler | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | إجراء المراجعة المشترك |
|


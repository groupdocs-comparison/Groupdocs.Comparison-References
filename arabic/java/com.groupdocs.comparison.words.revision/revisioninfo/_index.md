---
title: "RevisionInfo"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "تمثل مراجعة في المستند."
type: docs
weight: 12
url: /ar/java/com.groupdocs.comparison.words.revision/revisioninfo/
---
**Inheritance:**
java.lang.Object
```
public class RevisionInfo
```

تمثل مراجعة في المستند.


التنقيح يضم معلومات حول التغيير الذي تم إجراؤه على المستند.
هذه الفئة توفر طرقًا لاسترجاع معلومات حول التنقيح، مثل نوعه،
المحتوى، المؤلف، وما إلى ذلك.

مثال على الاستخدام:

````

 try (RevisionHandler revisionHandler = new RevisionHandler(sourceFile)) {
     List revisionList = revisionHandler.getRevisions();

     for (RevisionInfo revisionInfo : revisionList) {
         System.out.println("Revision Type: " + revisionInfo.getType());
         System.out.println("Text: " + revisionInfo.getText());
         System.out.println("Author: " + revisionInfo.getAuthor());
     }
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
| [RevisionInfo()](#RevisionInfo--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getAction()](#getAction--) | يحصل على الإجراء المرتبط بالتنقيح (قبول أو رفض). |
|
|  | [setAction(RevisionAction value)](#setAction-com.groupdocs.comparison.words.revision.RevisionAction-) | يضبط القيمة المرتبطة بالتنقيح (قبول أو رفض). |
|
|  | [getText()](#getText--) | يحصل على محتوى النص للتنقيح. |
|
|  | [setText(String value)](#setText-java.lang.String-) | يضبط محتوى القيمة للتنقيح. |
|
|  | [getAuthor()](#getAuthor--) | يحصل على مؤلف التنقيح. |
|
|  | [setAuthor(String value)](#setAuthor-java.lang.String-) | يضبط قيمة التنقيح. |
|
|  | [getType()](#getType--) | يحصل على نوع التنقيح، اعتمادًا على النوع تتغير منطق الإجراء (قبول أو رفض). |
|
|  | [setType(RevisionType value)](#setType-com.groupdocs.comparison.words.revision.RevisionType-) | يضبط قيمة التنقيح، اعتمادًا على القيمة تتغير منطق الإجراء (قبول أو رفض). |
|
### RevisionInfo() {#RevisionInfo--}
```
public RevisionInfo()
```


### getAction() {#getAction--}
```
public RevisionAction getAction()
```


يحصل على الإجراء المرتبط بالتنقيح (قبول أو رفض). يتيح لك هذا الحقل التأثير على عرض التنقيح.


**Returns:**
[RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) - the action associated with the revision.

### setAction(RevisionAction value) {#setAction-com.groupdocs.comparison.words.revision.RevisionAction-}
```
public void setAction(RevisionAction value)
```


يضبط القيمة المرتبطة بالتنقيح (قبول أو رفض). يتيح لك هذا الحقل التأثير على عرض التنقيح.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [RevisionAction](../../com.groupdocs.comparison.words.revision/revisionaction) | القيمة المرتبطة بالتنقيح. |
|

### getText() {#getText--}
```
public String getText()
```


يحصل على محتوى النص للتنقيح.


**Returns:**
java.lang.String - محتوى النص للتنقيح.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


يضبط محتوى القيمة للتنقيح.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.lang.String | محتوى القيمة للتنقيح. |
|

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


يحصل على مؤلف التنقيح.


**Returns:**
java.lang.String - مؤلف التنقيح.

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


يضبط قيمة التنقيح.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.lang.String | قيمة التنقيح. |
|

### getType() {#getType--}
```
public RevisionType getType()
```


يحصل على نوع التنقيح، اعتمادًا على النوع تتغير منطق الإجراء (قبول أو رفض).


**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - the type of the revision.

### setType(RevisionType value) {#setType-com.groupdocs.comparison.words.revision.RevisionType-}
```
public void setType(RevisionType value)
```


يضبط قيمة التنقيح، اعتمادًا على القيمة تتغير منطق الإجراء (قبول أو رفض).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) | قيمة التنقيح. |
|


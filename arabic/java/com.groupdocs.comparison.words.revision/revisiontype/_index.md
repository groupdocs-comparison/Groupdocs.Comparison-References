---
title: "RevisionType"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "يمثل أنواع المراجعات في المستند."
type: docs
weight: 14
url: /ar/java/com.groupdocs.comparison.words.revision/revisiontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionType extends Enum<RevisionType>
```

يمثل أنواع المراجعات في المستند.


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


## الحقول

| حقل | الوصف |
| --- | --- |
|  | [INSERTION](#INSERTION) | يمثل نوعًا عندما تم إدراج محتوى جديد في المستند. |
|
|  | [DELETION](#DELETION) | يمثل نوعًا عندما تم إزالة المحتوى من المستند. |
|
|  | [FORMAT_CHANGE](#FORMAT-CHANGE) | يمثل نوعًا عندما تم تطبيق تغيير تنسيق على العقدة الأصلية. |
|
|  | [STYLE_DEFINITION_CHANGE](#STYLE-DEFINITION-CHANGE) | يمثل نوعًا عندما تم تطبيق تغيير تنسيق على النمط الأصلي. |
|
|  | [MOVING](#MOVING) | يمثل نوعًا عندما تم نقل المحتوى في المستند. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromInt(int toIntValue)](#fromInt-int-) | ينشئ ثابتًا جديدًا من تعداد RevisionType باستخدام القيمة الرقمية المقدمة. |
|
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | يحلل تمثيل السلسلة لـ RevisionType للحصول على ثابت التعداد. |
|
|  | [toInt()](#toInt--) | التمثيل الرقمي لـ RevisionType. |
|
|  | [toString()](#toString--) | التمثيل النصي لـ RevisionType. |
|
### INSERTION {#INSERTION}
```
public static final RevisionType INSERTION
```


يمثل نوعًا عندما تم إدراج محتوى جديد في المستند.


### DELETION {#DELETION}
```
public static final RevisionType DELETION
```


يمثل نوعًا عندما تم إزالة المحتوى من المستند.


### FORMAT_CHANGE {#FORMAT-CHANGE}
```
public static final RevisionType FORMAT_CHANGE
```


يمثل نوعًا عندما تم تطبيق تغيير تنسيق على العقدة الأصلية.


### STYLE_DEFINITION_CHANGE {#STYLE-DEFINITION-CHANGE}
```
public static final RevisionType STYLE_DEFINITION_CHANGE
```


يمثل نوعًا عندما تم تطبيق تغيير تنسيق على النمط الأصلي.


### MOVING {#MOVING}
```
public static final RevisionType MOVING
```


يمثل نوعًا عندما تم نقل المحتوى في المستند.


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
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype)
### fromInt(int toIntValue) {#fromInt-int-}
```
public static RevisionType fromInt(int toIntValue)
```


ينشئ ثابتًا جديدًا من تعداد RevisionType باستخدام القيمة الرقمية المقدمة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | toIntValue | int | التمثيل الرقمي لـ RevisionType |
|

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with numeric value

### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static RevisionType fromString(String toStringValue)
```


يحلل تمثيل السلسلة لـ RevisionType للحصول على ثابت التعداد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | toStringValue | java.lang.String | التمثيل النصي لـ RevisionType |
|

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype) - RevisionType enum constant associated with input string

### toInt() {#toInt--}
```
public int toInt()
```


التمثيل الرقمي لـ RevisionType.


**Returns:**
int - القيمة الرقمية لثابت التعداد

### toString() {#toString--}
```
public String toString()
```


التمثيل النصي لـ RevisionType.


**Returns:**
java.lang.String - القيمة النصية لثابت التعداد


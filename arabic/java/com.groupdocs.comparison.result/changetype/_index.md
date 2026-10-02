---
title: "ChangeType"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "يمثل تعداد ChangeType أنواع التغييرات التي يمكن أن تحدث أثناء عملية مقارنة المستندات."
type: docs
weight: 14
url: /ar/java/com.groupdocs.comparison.result/changetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ChangeType extends Enum<ChangeType>
```

يمثل تعداد ChangeType أنواع التغييرات التي يمكن أن تحدث أثناء عملية مقارنة المستندات.


كل ثابت في هذا التعداد يمثل نوعًا محددًا من التغيير ويوفر وصفًا قابلاً للقراءة للإنسان وقيمة رقمية.


مثال على الاستخدام:

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


## الحقول

| حقل | الوصف |
| --- | --- |
|  | [NONE](#NONE) | يمثل عدم وجود تغيير. |
|
|  | [MODIFIED](#MODIFIED) | يمثل تغييرًا معدلًا. |
|
|  | [INSERTED](#INSERTED) | يمثل تغييرًا مُدرجًا. |
|
|  | [DELETED](#DELETED) | يمثل تغييرًا محذوفًا. |
|
|  | [ADDED](#ADDED) | يمثل تغييرًا مضافًا. |
|
|  | [NOT_MODIFIED](#NOT-MODIFIED) | يمثل تغييرًا غير معدل. |
|
|  | [STYLE_CHANGED](#STYLE-CHANGED) | يمثل تغييرًا في النمط. |
|
|  | [RESIZED](#RESIZED) | يمثل تغييرًا تم إعادة تحجيمه. |
|
|  | [MOVED](#MOVED) | يمثل تغييرًا تم تحريكه. |
|
|  | [MOVED_AND_RESIZED](#MOVED-AND-RESIZED) | يمثل تغييرًا تم تحريكه وإعادة تحجيمه. |
|
|  | [SHIFTED_AND_RESIZED](#SHIFTED-AND-RESIZED) | يمثل تغييرًا تم إزاحته وإعادة تحجيمه. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | يقوم بتحليل تمثيل السلسلة لـ ChangeType للحصول على ثابت التعداد. |
|
|  | [fromInt(int intValue)](#fromInt-int-) | ينشئ ثابتًا جديدًا لتعداد ChangeType باستخدام القيمة الرقمية المقدمة. |
|
|  | [toString()](#toString--) | تمثيل السلسلة لـ ChangeType. |
|
|  | [toInt()](#toInt--) | تمثيل رقمي لـ ChangeType. |
|
### NONE {#NONE}
```
public static final ChangeType NONE
```


يمثل عدم وجود تغيير.


### MODIFIED {#MODIFIED}
```
public static final ChangeType MODIFIED
```


يمثل تغييرًا معدلًا.


### INSERTED {#INSERTED}
```
public static final ChangeType INSERTED
```


يمثل تغييرًا مُدرجًا.


### DELETED {#DELETED}
```
public static final ChangeType DELETED
```


يمثل تغييرًا محذوفًا.


### ADDED {#ADDED}
```
public static final ChangeType ADDED
```


يمثل تغييرًا مضافًا.


### NOT_MODIFIED {#NOT-MODIFIED}
```
public static final ChangeType NOT_MODIFIED
```


يمثل تغييرًا غير معدل.


### STYLE_CHANGED {#STYLE-CHANGED}
```
public static final ChangeType STYLE_CHANGED
```


يمثل تغييرًا في النمط.


### RESIZED {#RESIZED}
```
public static final ChangeType RESIZED
```


يمثل تغييرًا تم إعادة تحجيمه.


### MOVED {#MOVED}
```
public static final ChangeType MOVED
```


يمثل تغييرًا تم تحريكه.


### MOVED_AND_RESIZED {#MOVED-AND-RESIZED}
```
public static final ChangeType MOVED_AND_RESIZED
```


يمثل تغييرًا تم تحريكه وإعادة تحجيمه.


### SHIFTED_AND_RESIZED {#SHIFTED-AND-RESIZED}
```
public static final ChangeType SHIFTED_AND_RESIZED
```


يمثل تغييرًا تم إزاحته وإعادة تحجيمه.


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
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ChangeType fromString(String toStringValue)
```


يقوم بتحليل تمثيل السلسلة لـ ChangeType للحصول على ثابت التعداد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | toStringValue | java.lang.String | تمثيل السلسلة لـ ChangeType |
|

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with input string

### fromInt(int intValue) {#fromInt-int-}
```
public static ChangeType fromInt(int intValue)
```


ينشئ ثابتًا جديدًا لتعداد ChangeType باستخدام القيمة الرقمية المقدمة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | intValue | int | التمثيل الرقمي لـ ChangeType |
|

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with numeric value

### toString() {#toString--}
```
public String toString()
```


تمثيل السلسلة لـ ChangeType.


**Returns:**
java.lang.String - القيمة النصية لثابت التعداد

### toInt() {#toInt--}
```
public int toInt()
```


تمثيل رقمي لـ ChangeType.


**Returns:**
int - القيمة الرقمية لثابت التعداد


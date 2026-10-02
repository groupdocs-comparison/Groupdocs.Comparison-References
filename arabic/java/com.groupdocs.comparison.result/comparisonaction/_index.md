---
title: "ComparisonAction"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "يمثل تعداد ComparisonAction الإجراءات التي يمكن تطبيقها على تغيير أثناء عملية مقارنة المستندات."
type: docs
weight: 15
url: /ar/java/com.groupdocs.comparison.result/comparisonaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonAction extends Enum<ComparisonAction>
```

يمثل تعداد ComparisonAction الإجراءات التي يمكن تطبيقها على تغيير أثناء عملية مقارنة المستندات.


كل ثابت في هذا التعداد يمثل إجراءً محددًا ويوفر وصفًا قابلاً للقراءة للإنسان وقيمة رقمية.


مثال على الاستخدام:

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


## الحقول

| حقل | الوصف |
| --- | --- |
|  | [NONE](#NONE) | يمثل عدم وجود إجراء. |
|
|  | [ACCEPT](#ACCEPT) | يمثل إجراء قبول. |
|
|  | [REJECT](#REJECT) | يمثل إجراء رفض. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | يقوم بتحليل تمثيل السلسلة لـ ComparisonAction للحصول على ثابت التعداد. |
|
|  | [fromInt(int intValue)](#fromInt-int-) | ينشئ ثابتًا جديدًا من تعداد ComparisonAction باستخدام القيمة الرقمية المقدمة. |
|
|  | [toString()](#toString--) | تمثيل السلسلة لـ ComparisonAction. |
|
|  | [toInt()](#toInt--) | تمثيل رقمي لـ ComparisonAction. |
|
### NONE {#NONE}
```
public static final ComparisonAction NONE
```


يمثل عدم وجود إجراء. التغيير لن يكون له أي تأثير.


### ACCEPT {#ACCEPT}
```
public static final ComparisonAction ACCEPT
```


يمثل إجراء قبول. سيكون التغيير مرئيًا في ملف النتيجة.


### REJECT {#REJECT}
```
public static final ComparisonAction REJECT
```


يمثل إجراء رفض. سيكون التغيير غير مرئي في ملف النتيجة.


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
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonAction fromString(String toStringValue)
```


يقوم بتحليل تمثيل السلسلة لـ ComparisonAction للحصول على ثابت التعداد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | toStringValue | java.lang.String | تمثيل السلسلة لـ ComparisonAction |
|

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with input string

### fromInt(int intValue) {#fromInt-int-}
```
public static ComparisonAction fromInt(int intValue)
```


ينشئ ثابتًا جديدًا من تعداد ComparisonAction باستخدام القيمة الرقمية المقدمة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | intValue | int | التمثيل الرقمي لـ ComparisonAction |
|

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - ComparisonAction enum constant associated with numeric value

### toString() {#toString--}
```
public String toString()
```


تمثيل السلسلة لـ ComparisonAction.


**Returns:**
java.lang.String - القيمة النصية لثابت التعداد

### toInt() {#toInt--}
```
public int toInt()
```


تمثيل رقمي لـ ComparisonAction.


**Returns:**
int - القيمة الرقمية لثابت التعداد


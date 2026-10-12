---
title: "PasswordSaveOption"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "يسرد الخيارات لحفظ معلومات كلمة المرور في مستند أثناء عملية المقارنة."
type: docs
weight: 14
url: /ar/java/com.groupdocs.comparison.options.enums/passwordsaveoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PasswordSaveOption extends Enum<PasswordSaveOption>
```

يسرد الخيارات لحفظ معلومات كلمة المرور في مستند أثناء عملية المقارنة.


مثال على الاستخدام:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPasswordSaveOption(PasswordSaveOption.SOURCE);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## الحقول

| حقل | الوصف |
| --- | --- |
|  | [NONE](#NONE) | لا تقم بحفظ كلمة المرور. |
|
|  | [SOURCE](#SOURCE) | استخدم كلمة المرور من المستند المصدر. |
|
|  | [TARGET](#TARGET) | استخدم كلمة المرور من المستند الهدف. |
|
|  | [USER](#USER) | \* استخدم كلمة المرور التي قدمها المستخدم. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | يحلل تمثيل السلسلة لـ PasswordSaveOption للحصول على ثابت التعداد. |
|
|  | [toString()](#toString--) | تمثيل السلسلة لـ PasswordSaveOption. |
|
### NONE {#NONE}
```
public static final PasswordSaveOption NONE
```


لا تقم بحفظ كلمة المرور.


### SOURCE {#SOURCE}
```
public static final PasswordSaveOption SOURCE
```


استخدم كلمة المرور من المستند المصدر.


### TARGET {#TARGET}
```
public static final PasswordSaveOption TARGET
```


استخدم كلمة المرور من المستند الهدف.


### USER {#USER}
```
public static final PasswordSaveOption USER
```


\* استخدم كلمة المرور التي قدمها المستخدم.


### values() {#values--}
```
public static PasswordSaveOption[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.PasswordSaveOption[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PasswordSaveOption valueOf(String name)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PasswordSaveOption fromString(String toStringValue)
```


يحلل تمثيل السلسلة لـ PasswordSaveOption للحصول على ثابت التعداد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | toStringValue | java.lang.String | تمثيل السلسلة لـ PasswordSaveOption |
|

**Returns:**
[PasswordSaveOption](../../com.groupdocs.comparison.options.enums/passwordsaveoption) - PasswordSaveOption enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


تمثيل السلسلة لـ PasswordSaveOption.


**Returns:**
java.lang.String - القيمة النصية لثابت التعداد


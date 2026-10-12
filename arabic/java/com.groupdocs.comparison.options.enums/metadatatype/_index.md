---
title: "MetadataType"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "يحدد من أين سيأخذ مستند النتيجة معلومات البيانات الوصفية."
type: docs
weight: 12
url: /ar/java/com.groupdocs.comparison.options.enums/metadatatype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MetadataType extends Enum<MetadataType>
```

يحدد من أين سيأخذ مستند النتيجة معلومات البيانات الوصفية.


مثال على الاستخدام:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    SaveOptions saveOptions = new SaveOptions();
    saveOptions.setCloneMetadataType(MetadataType.FILE_AUTHOR);

    comparer.compare(resultFile, saveOptions);
 }
 
````


## الحقول

| حقل | الوصف |
| --- | --- |
|  | [DEFAULT](#DEFAULT) | ستُترك البيانات الوصفية كما هي. |
|
|  | [SOURCE](#SOURCE) | سيتم أخذ Metedata من المستند المصدر. |
|
|  | [TARGET](#TARGET) | سيتم أخذ Metedata من المستند الهدف. |
|
|  | [FILE_AUTHOR](#FILE-AUTHOR) | سيتم تعيين Metedata بواسطة المستخدم. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | يقوم بتحليل تمثيل السلسلة لـMetadataType للحصول على ثابت التعداد. |
|
|  | [toString()](#toString--) | تمثيل النص لـ MetadataType. |
|
### DEFAULT {#DEFAULT}
```
public static final MetadataType DEFAULT
```


ستُترك البيانات الوصفية كما هي.


### SOURCE {#SOURCE}
```
public static final MetadataType SOURCE
```


سيتم أخذ Metedata من المستند المصدر.


### TARGET {#TARGET}
```
public static final MetadataType TARGET
```


سيتم أخذ Metedata من المستند الهدف.


### FILE_AUTHOR {#FILE-AUTHOR}
```
public static final MetadataType FILE_AUTHOR
```


سيتم تعيين Metedata بواسطة المستخدم.


### values() {#values--}
```
public static MetadataType[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.MetadataType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static MetadataType valueOf(String name)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static MetadataType fromString(String toStringValue)
```


يقوم بتحليل تمثيل السلسلة لـMetadataType للحصول على ثابت التعداد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | toStringValue | java.lang.String | تمثيل النص لـ MetadataType |
|

**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - MetadataType enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


تمثيل النص لـ MetadataType.


**Returns:**
java.lang.String - القيمة النصية لثابت التعداد


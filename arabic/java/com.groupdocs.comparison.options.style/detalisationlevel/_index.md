---
title: "DetalisationLevel"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "يحدد مستوى تفاصيل المقارنة."
type: docs
weight: 13
url: /ar/java/com.groupdocs.comparison.options.style/detalisationlevel/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetalisationLevel extends Enum<DetalisationLevel>
```

يحدد مستوى تفاصيل المقارنة.


مثال على الاستخدام:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setDetectStyleChanges(false);
    compareOptions.setDetalisationLevel(DetalisationLevel.HIGH);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## الحقول

| حقل | الوصف |
| --- | --- |
|  | [LOW](#LOW) | يمثل مستوى المقارنة المنخفض. |
|
|  | [MIDDLE](#MIDDLE) | يمثل مستوى المقارنة المتوسط. |
|
|  | [HIGH](#HIGH) | يمثل مستوى المقارنة العالي. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | يحلل تمثيل السلسلة لـ DetalisationLevel للحصول على ثابت التعداد. |
|
|  | [toString()](#toString--) | تمثيل النص لمستوى DetalisationLevel. |
|
### LOW {#LOW}
```
public static final DetalisationLevel LOW
```


يمثل مستوى المقارنة المنخفض.


المستوى "Low" يوفر أسرع سرعة للمقارنات لكنه يضحي بجودة المقارنة.
يتم إجراء المقارنة كلمةً بكلمة.


### MIDDLE {#MIDDLE}
```
public static final DetalisationLevel MIDDLE
```


يمثل مستوى المقارنة المتوسط.


المستوى "Middle" هو حل وسط معقول بين سرعة المقارنة والجودة.
يتم إجراء المقارنة حرفًا بحرف، مع تجاهل حالة الأحرف وعدد المسافات.


### HIGH {#HIGH}
```
public static final DetalisationLevel HIGH
```


يمثل مستوى المقارنة العالي.


المستوى "High" هو أفضل جودة للمقارنة، لكنه الأبطأ في السرعة.
يتم إجراء المقارنة حرفًا بحرف مع مراعاة حالة الأحرف وعدد المسافات.


### values() {#values--}
```
public static DetalisationLevel[] values()
```




**Returns:**
com.groupdocs.comparison.options.style.DetalisationLevel[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static DetalisationLevel valueOf(String name)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static DetalisationLevel fromString(String toStringValue)
```


يحلل تمثيل السلسلة لـ DetalisationLevel للحصول على ثابت التعداد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | toStringValue | java.lang.String | تمثيل النص لسمة DetalisationLevel |
|

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel) - DetalisationLevel enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


تمثيل النص لمستوى DetalisationLevel.


**Returns:**
java.lang.String - القيمة النصية لثابت التعداد


---
title: "ComparisonType"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "يمثل نوع المقارنة التي سيتم إجراؤها."
type: docs
weight: 10
url: /ar/java/com.groupdocs.comparison.options.enums/comparisontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonType extends Enum<ComparisonType>
```

يمثل نوع المقارنة التي سيتم إجراؤها.


مثال على الاستخدام:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setComparisonType(ComparisonType.CELLS);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## الحقول

| حقل | الوصف |
| --- | --- |
|  | [TEXT](#TEXT) | يجب مقارنة الملفات كمستندات نصية. |
|
|  | [SLIDES](#SLIDES) | يجب مقارنة الملفات كمستندات عرض تقديمي. |
|
|  | [WORDS](#WORDS) | يجب مقارنة الملفات كمستندات Word. |
|
|  | [CELLS](#CELLS) | يجب مقارنة الملفات كمستندات Excel. |
|
|  | [PDF](#PDF) | يجب مقارنة الملفات كمستندات PDF. |
|
|  | [IMAGING](#IMAGING) | يجب مقارنة الملفات كمستندات صورة. |
|
|  | [EMAIL](#EMAIL) | يجب مقارنة الملفات كمستندات بريد إلكتروني. |
|
|  | [NOTE](#NOTE) | يجب مقارنة الملفات كمستندات ملاحظة. |
|
|  | [HTML](#HTML) | يجب مقارنة الملفات كمستندات HTML. |
|
|  | [DIAGRAM](#DIAGRAM) | يجب مقارنة الملفات كمستندات مخطط. |
|
|  | [DIFFERENT](#DIFFERENT) | يجب مقارنة الملفات كمستندات بصيغ مختلفة. |
|
|  | [SVG](#SVG) | يجب مقارنة الملفات كمستندات SVG. |
|
|  | [UNDEFINED](#UNDEFINED) | للاستخدام الداخلي. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | يحلل تمثيل السلسلة لنوع ComparisonType للحصول على ثابت التعداد. |
|
|  | [toString()](#toString--) | تمثيل السلسلة لنوع ComparisonType. |
|
### TEXT {#TEXT}
```
public static final ComparisonType TEXT
```


يجب مقارنة الملفات كمستندات نصية.


### SLIDES {#SLIDES}
```
public static final ComparisonType SLIDES
```


يجب مقارنة الملفات كمستندات عرض تقديمي.


### WORDS {#WORDS}
```
public static final ComparisonType WORDS
```


يجب مقارنة الملفات كمستندات Word.


### CELLS {#CELLS}
```
public static final ComparisonType CELLS
```


يجب مقارنة الملفات كمستندات Excel.


### PDF {#PDF}
```
public static final ComparisonType PDF
```


يجب مقارنة الملفات كمستندات PDF.


### IMAGING {#IMAGING}
```
public static final ComparisonType IMAGING
```


يجب مقارنة الملفات كمستندات صورة.


### EMAIL {#EMAIL}
```
public static final ComparisonType EMAIL
```


يجب مقارنة الملفات كمستندات بريد إلكتروني.


### NOTE {#NOTE}
```
public static final ComparisonType NOTE
```


يجب مقارنة الملفات كمستندات ملاحظة.


### HTML {#HTML}
```
public static final ComparisonType HTML
```


يجب مقارنة الملفات كمستندات HTML.


### DIAGRAM {#DIAGRAM}
```
public static final ComparisonType DIAGRAM
```


يجب مقارنة الملفات كمستندات مخطط.


### DIFFERENT {#DIFFERENT}
```
public static final ComparisonType DIFFERENT
```


يجب مقارنة الملفات كمستندات بصيغ مختلفة.


### SVG {#SVG}
```
public static final ComparisonType SVG
```


يجب مقارنة الملفات كمستندات SVG.


### UNDEFINED {#UNDEFINED}
```
public static final ComparisonType UNDEFINED
```


للاستخدام الداخلي.


### values() {#values--}
```
public static ComparisonType[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.ComparisonType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ComparisonType valueOf(String name)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonType fromString(String toStringValue)
```


يحلل تمثيل السلسلة لنوع ComparisonType للحصول على ثابت التعداد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | toStringValue | java.lang.String | تمثيل السلسلة لنوع ComparisonType |
|

**Returns:**
[ComparisonType](../../com.groupdocs.comparison.options.enums/comparisontype) - ComparisonType enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


تمثيل السلسلة لنوع ComparisonType.


**Returns:**
java.lang.String - القيمة النصية لثابت التعداد


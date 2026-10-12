---
title: "PaperSize"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "يمثل خيارات حجم الورق لمقارنة المستندات."
type: docs
weight: 13
url: /ar/java/com.groupdocs.comparison.options.enums/papersize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PaperSize extends Enum<PaperSize>
```

يمثل خيارات حجم الورق لمقارنة المستندات.


مثال على الاستخدام:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    CompareOptions compareOptions = new CompareOptions();
    compareOptions.setPaperSize(PaperSize.A6);

    comparer.compare(resultFile, compareOptions);
 }
 
````


## الحقول

| حقل | الوصف |
| --- | --- |
|  | [DEFAULT](#DEFAULT) | حجم الورق الافتراضي. |
|
|  | [A0](#A0) | حجم الورق القياسي A0 (841مم × 1189مم). |
|
|  | [A1](#A1) | حجم الورق القياسي A1 (594مم × 841مم). |
|
|  | [A2](#A2) | حجم الورق القياسي A2 (420مم × 594مم). |
|
|  | [A3](#A3) | حجم الورق القياسي A3 (297مم × 420مم). |
|
|  | [A4](#A4) | حجم الورق القياسي A4 (210مم × 297مم). |
|
|  | [A5](#A5) | حجم الورق القياسي A5 (148مم × 210مم). |
|
|  | [A6](#A6) | حجم الورق القياسي A6 (105مم × 148مم). |
|
|  | [A7](#A7) | حجم الورق القياسي A7 (74مم × 105مم). |
|
|  | [A8](#A8) | حجم الورق القياسي A8 (52مم × 74مم). |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | يقوم بتحليل تمثيل السلسلة لـ PaperSize للحصول على ثابت التعداد. |
|
|  | [toString()](#toString--) | تمثيل السلسلة لـ PaperSize. |
|
### DEFAULT {#DEFAULT}
```
public static final PaperSize DEFAULT
```


حجم الورق الافتراضي.


### A0 {#A0}
```
public static final PaperSize A0
```


حجم الورق القياسي A0 (841مم × 1189مم).


### A1 {#A1}
```
public static final PaperSize A1
```


حجم الورق القياسي A1 (594مم × 841مم).


### A2 {#A2}
```
public static final PaperSize A2
```


حجم الورق القياسي A2 (420مم × 594مم).


### A3 {#A3}
```
public static final PaperSize A3
```


حجم الورق القياسي A3 (297مم × 420مم).


### A4 {#A4}
```
public static final PaperSize A4
```


حجم الورق القياسي A4 (210مم × 297مم).


### A5 {#A5}
```
public static final PaperSize A5
```


حجم الورق القياسي A5 (148مم × 210مم).


### A6 {#A6}
```
public static final PaperSize A6
```


حجم الورق القياسي A6 (105مم × 148مم).


### A7 {#A7}
```
public static final PaperSize A7
```


حجم الورق القياسي A7 (74مم × 105مم).


### A8 {#A8}
```
public static final PaperSize A8
```


حجم الورق القياسي A8 (52مم × 74مم).


### values() {#values--}
```
public static PaperSize[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.PaperSize[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PaperSize valueOf(String name)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PaperSize fromString(String toStringValue)
```


يقوم بتحليل تمثيل السلسلة لـ PaperSize للحصول على ثابت التعداد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | toStringValue | java.lang.String | تمثيل السلسلة لـ PaperSize |
|

**Returns:**
[PaperSize](../../com.groupdocs.comparison.options.enums/papersize) - PaperSize enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


تمثيل السلسلة لـ PaperSize.


**Returns:**
java.lang.String - القيمة النصية لثابت التعداد


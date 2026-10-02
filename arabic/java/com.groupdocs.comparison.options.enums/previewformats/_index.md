---
title: "PreviewFormats"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "يسرد صيغ المعاينة المدعومة لمقارنة المستندات."
type: docs
weight: 15
url: /ar/java/com.groupdocs.comparison.options.enums/previewformats/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PreviewFormats extends Enum<PreviewFormats>
```

يسرد صيغ المعاينة المدعومة لمقارنة المستندات.
يقدم تعداد PreviewFormats قائمة بالتنسيقات التي يمكن استخدامها لإنشاء معاينات للمستندات المقارنة.

تشمل التنسيقات المدعومة:

* #PNG.PNG - Portable Network Graphics (.png)
* #JPEG.JPEG - Joint Photographic Experts Group (.jpeg)
* #BMP.BMP - Bitmap Picture (.bmp)


مثال على الاستخدام:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    PreviewOptions previewOptions = new PreviewOptions(
            pageNumber -> Files.newOutputStream(Paths.get(String.format("preview-page_%d.png", pageNumber)))
    );
    previewOptions.setPreviewFormat(PreviewFormats.PNG);

    comparer.getTargets().get(0).generatePreview(previewOptions);
 }
 
````


## الحقول

| حقل | الوصف |
| --- | --- |
|  | [PNG](#PNG) | PNG - قد يستهلك مساحة تخزين كبيرة أو حركة مرور شبكة إذا كانت الصفحة تحتوي على رسومات ملونة عديدة. |
|
|  | [JPEG](#JPEG) | Jpeg - يوفر معالجة أسرع مع استخدام أقل لمساحة التخزين وحركة مرور الشبكة، لكن قد ينتج جودة صورة أقل. |
|
|  | [BMP](#BMP) | BMP - يقدم أفضل جودة صورة لكنه يتطلب معالجة أبطأ مع استخدام أعلى لمساحة التخزين وحركة مرور الشبكة. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | يحلل تمثيل السلسلة لـ PreviewFormats للحصول على ثابت التعداد. |
|
|  | [toString()](#toString--) | تمثيل السلسلة لـ PreviewFormats. |
|
### PNG {#PNG}
```
public static final PreviewFormats PNG
```


PNG - قد يستهلك مساحة تخزين كبيرة أو حركة مرور شبكة إذا كانت الصفحة تحتوي على رسومات ملونة عديدة. تنسيق المعاينة الافتراضي.


### JPEG {#JPEG}
```
public static final PreviewFormats JPEG
```


Jpeg - يوفر معالجة أسرع مع استخدام أقل لمساحة التخزين وحركة مرور الشبكة، لكن قد ينتج جودة صورة أقل.


### BMP {#BMP}
```
public static final PreviewFormats BMP
```


BMP - يقدم أفضل جودة صورة لكنه يتطلب معالجة أبطأ مع استخدام أعلى لمساحة التخزين وحركة مرور الشبكة.


### values() {#values--}
```
public static PreviewFormats[] values()
```




**Returns:**
com.groupdocs.comparison.options.enums.PreviewFormats[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PreviewFormats valueOf(String name)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static PreviewFormats fromString(String toStringValue)
```


يحلل تمثيل السلسلة لـ PreviewFormats للحصول على ثابت التعداد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | toStringValue | java.lang.String | تمثيل السلسلة لـ PreviewFormats |
|

**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - PreviewFormats enum constant associated with input string

### toString() {#toString--}
```
public String toString()
```


تمثيل السلسلة لـ PreviewFormats.


**Returns:**
java.lang.String - القيمة النصية لثابت التعداد


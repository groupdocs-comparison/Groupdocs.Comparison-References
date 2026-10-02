---
title: "PreviewOptions"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "يوفر خيارات لإنشاء معاينات المستندات في عملية المقارنة."
type: docs
weight: 15
url: /ar/java/com.groupdocs.comparison.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

يوفر خيارات لإنشاء معاينات المستندات في عملية المقارنة.


مثال على الاستخدام:

````

 try (Comparer comparer = new Comparer(sourceFile)) {

    PreviewOptions previewOptions = new PreviewOptions(
            pageNumber -> Files.newOutputStream(Paths.get(String.format("preview-page_%d.png", pageNumber)))
    );
    previewOptions.setPreviewFormat(PreviewFormats.PNG);
    previewOptions.setPageNumbers(new int[]{1, 2});

    comparer.getSource().generatePreview(previewOptions);
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [PreviewOptions(Delegates.CreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | يُهيئ نسخة جديدة من فئة PreviewOptions مع تحديد الدالة Delegates.CreatePageStream. |
|
|  | [PreviewOptions(CreatePageStreamFunction createPageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | يُهيئ نسخة جديدة من فئة PreviewOptions مع تحديد الدالة [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction). |
|
|  | [PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | يُهيئ نسخة جديدة من فئة PreviewOptions مع تحديد الدالتين Delegates.CreatePageStream و Delegates.ReleasePageStream. |
|
|  | [PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)](#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | يُهيئ نسخة جديدة من فئة PreviewOptions مع تحديد الدالتين [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) و [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction). |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getCreatePageStream()](#getCreatePageStream--) | يحصل على دالة لإنشاء تدفق معاينة صفحة الإخراج. |
|
|  | [setCreatePageStream(Delegates.CreatePageStream createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-) | يضبط دالة لإنشاء تدفق معاينة صفحة الإخراج. |
|
|  | [setCreatePageStream(CreatePageStreamFunction createPageStream)](#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-) | يضبط دالة لإنشاء تدفق معاينة صفحة الإخراج. |
|
|  | [getReleasePageStream()](#getReleasePageStream--) | يحصل على دالة لإطلاق تدفق معاينة صفحة الإخراج. |
|
|  | [setReleasePageStream(Delegates.ReleasePageStream releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-) | يحصل على دالة لإطلاق تدفق معاينة صفحة الإخراج. |
|
|  | [setReleasePageStream(ReleasePageStreamFunction releasePageStream)](#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-) | يضبط دالة لإطلاق تدفق معاينة صفحة الإخراج. |
|
|  | [getWidth()](#getWidth--) | يحصل على عرض صور المعاينة. |
|
|  | [setWidth(int value)](#setWidth-int-) | يضبط عرض صور المعاينة. |
|
|  | [getHeight()](#getHeight--) | يحصل على ارتفاع صور المعاينة. |
|
|  | [setHeight(int value)](#setHeight-int-) | يضبط ارتفاع صور المعاينة. |
|
|  | [getPageNumbers()](#getPageNumbers--) | يحصل على مصفوفة أرقام الصفحات التي سيتم إنشاء صور المعاينة لها. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | يضبط مصفوفة أرقام الصفحات التي سيتم إنشاء صور المعاينة لها. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | يحصل على تنسيق صور المعاينة. |
|
|  | [setPreviewFormat(PreviewFormats value)](#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-) | يضبط تنسيق صور المعاينة. |
|
### PreviewOptions(Delegates.CreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream)
```


يُهيئ نسخة جديدة من فئة PreviewOptions مع تحديد الدالة Delegates.CreatePageStream.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | الدالة لإنشاء تدفق معاينة صفحة الإخراج. |
|

### PreviewOptions(CreatePageStreamFunction createPageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream)
```


يُهيئ نسخة جديدة من فئة PreviewOptions مع تحديد الدالة [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | الدالة لإنشاء تدفق معاينة صفحة الإخراج. |
|

### PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public PreviewOptions(Delegates.CreatePageStream createPageStream, Delegates.ReleasePageStream releasePageStream)
```


يُهيئ نسخة جديدة من فئة PreviewOptions مع تحديد الدالتين Delegates.CreatePageStream و Delegates.ReleasePageStream.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | الدالة لإنشاء تدفق معاينة صفحة الإخراج. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | الدالة لإطلاق تدفق معاينة صفحة الإخراج. |
|

### PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream) {#PreviewOptions-com.groupdocs.comparison.common.function.CreatePageStreamFunction-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public PreviewOptions(CreatePageStreamFunction createPageStream, ReleasePageStreamFunction releasePageStream)
```


يُهيئ نسخة جديدة من فئة PreviewOptions مع تحديد الدالتين [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) و [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | الدالة لإنشاء تدفق معاينة صفحة الإخراج. |
|
|  | releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | الدالة لإطلاق تدفق معاينة صفحة الإخراج. |
|

### getCreatePageStream() {#getCreatePageStream--}
```
public CreatePageStreamFunction getCreatePageStream()
```


يحصل على دالة لإنشاء تدفق معاينة صفحة الإخراج.


**Returns:**
[CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) - the function to create output page preview stream.

### setCreatePageStream(Delegates.CreatePageStream createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.delegates.Delegates.CreatePageStream-}
```
public void setCreatePageStream(Delegates.CreatePageStream createPageStream)
```


يضبط دالة لإنشاء تدفق معاينة صفحة الإخراج.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.comparison.common.delegates/createpagestream) | الدالة لإنشاء تدفق معاينة صفحة الإخراج. |
|

### setCreatePageStream(CreatePageStreamFunction createPageStream) {#setCreatePageStream-com.groupdocs.comparison.common.function.CreatePageStreamFunction-}
```
public void setCreatePageStream(CreatePageStreamFunction createPageStream)
```


يضبط دالة لإنشاء تدفق معاينة صفحة الإخراج.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | createPageStream | [CreatePageStreamFunction](../../com.groupdocs.comparison.common.function/createpagestreamfunction) | الدالة لإنشاء تدفق معاينة صفحة الإخراج. |
|

### getReleasePageStream() {#getReleasePageStream--}
```
public ReleasePageStreamFunction getReleasePageStream()
```


يحصل على دالة لإطلاق تدفق معاينة صفحة الإخراج.


**Returns:**
[ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) - the function to release output page preview stream.

### setReleasePageStream(Delegates.ReleasePageStream releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.delegates.Delegates.ReleasePageStream-}
```
public void setReleasePageStream(Delegates.ReleasePageStream releasePageStream)
```


يحصل على دالة لإطلاق تدفق معاينة صفحة الإخراج.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.comparison.common.delegates/releasepagestream) | الدالة لإطلاق تدفق معاينة صفحة الإخراج. |
|

### setReleasePageStream(ReleasePageStreamFunction releasePageStream) {#setReleasePageStream-com.groupdocs.comparison.common.function.ReleasePageStreamFunction-}
```
public void setReleasePageStream(ReleasePageStreamFunction releasePageStream)
```


يضبط دالة لإطلاق تدفق معاينة صفحة الإخراج.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | releasePageStream | [ReleasePageStreamFunction](../../com.groupdocs.comparison.common.function/releasepagestreamfunction) | الدالة لإطلاق تدفق معاينة صفحة الإخراج. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


يحصل على عرض صور المعاينة.


**Returns:**
int - عرض صور المعاينة.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


يضبط عرض صور المعاينة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | int | عرض صور المعاينة. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


يحصل على ارتفاع صور المعاينة.


**Returns:**
int - ارتفاع صور المعاينة.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


يضبط ارتفاع صور المعاينة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | int | ارتفاع صور المعاينة. |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


يحصل على مصفوفة أرقام الصفحات التي سيتم إنشاء صور المعاينة لها.


**Returns:**
int[] - مصفوفة أرقام الصفحات

### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


يضبط مصفوفة أرقام الصفحات التي سيتم إنشاء صور المعاينة لها.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | int[] | مصفوفة أرقام الصفحات |
|

### getPreviewFormat() {#getPreviewFormat--}
```
public final PreviewFormats getPreviewFormat()
```


يحصل على تنسيق صور المعاينة.


**Returns:**
[PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) - preview images format

### setPreviewFormat(PreviewFormats value) {#setPreviewFormat-com.groupdocs.comparison.options.enums.PreviewFormats-}
```
public final void setPreviewFormat(PreviewFormats value)
```


يضبط تنسيق صور المعاينة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [PreviewFormats](../../com.groupdocs.comparison.options.enums/previewformats) | تنسيق صور المعاينة |
|


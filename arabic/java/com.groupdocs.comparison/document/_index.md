---
title: "مستند"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "يمثل مستندًا لعملية المقارنة."
type: docs
weight: 12
url: /ar/java/com.groupdocs.comparison/document/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Document implements Closeable
```

يمثل مستندًا لعملية المقارنة.


توفر فئة Document طرقًا لتحميل، وإنشاء صور معاينة، ومعالجة المستندات أثناء عملية المقارنة.


مثال على الاستخدام:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     try (IDocumentInfo info = comparer.getSource().getDocumentInfo()) {
         System.out.println("File type: " + info.getFileType());
         System.out.println("Number of pages: " + info.getPageCount());
         System.out.println("Document size: " + info.getSize());
     }
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [Document(InputStream stream)](#Document-java.io.InputStream-) | يُنشئ مثيلًا جديدًا من فئة Document باستخدام تدفق المستند المحدد. |
|
|  | [Document(String filePath)](#Document-java.lang.String-) | يُنشئ مثيلًا جديدًا من فئة Document باستخدام مسار المستند المحدد. |
|
|  | [Document(Path filePath)](#Document-java.nio.file.Path-) | يُنشئ مثيلًا جديدًا من فئة Document باستخدام مسار المستند المحدد. |
|
|  | [Document(Path filePath, String password)](#Document-java.nio.file.Path-java.lang.String-) | يُنشئ مثيلًا جديدًا من فئة Document باستخدام مسار المستند المحدد وكلمة مرور. |
|
|  | [Document(Path filePath, LoadOptions loadOptions)](#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-) | يُنشئ مثيلًا جديدًا من فئة Document باستخدام مسار المستند المحدد وخيارات التحميل. |
|
|  | [Document(String filePath, String password)](#Document-java.lang.String-java.lang.String-) | يُنشئ مثيلًا جديدًا من فئة Document باستخدام مسار المستند المحدد وكلمة مرور. |
|
|  | [Document(String filePath, LoadOptions loadOptions)](#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-) | يُنشئ مثيلًا جديدًا من فئة Document باستخدام مسار المستند المحدد وخيارات التحميل. |
|
|  | [Document(InputStream stream, String password)](#Document-java.io.InputStream-java.lang.String-) | يُنشئ مثيلًا جديدًا من فئة Document باستخدام تدفق المستند المحدد وكلمة مرور. |
|
|  | [Document(String filePathOrTextContent, boolean isLoadText)](#Document-java.lang.String-boolean-) | يُنشئ مثيلًا جديدًا من فئة Document باستخدام مسار المستند أو محتوى النص المحدد وعلمًا يوضح ما تم تمريره. |
|
|  | [Document(InputStream inputStream, LoadOptions loadOptions)](#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-) | يُنشئ مثيلًا جديدًا من فئة Document باستخدام تدفق المستند المحدد وخيارات التحميل. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getChanges()](#getChanges--) | يحصل على قائمة من كائنات [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) التي تمثل التغييرات المكتشفة أثناء عملية المقارنة. |
|
|  | [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | يضبط قائمة من كائنات [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) التي تمثل التغييرات المكتشفة أثناء عملية المقارنة. |
|
|  | [getName()](#getName--) | يحصل على اسم المستند. |
|
|  | [setName(String value)](#setName-java.lang.String-) | يضبط اسم المستند. |
|
|  | [getFileType()](#getFileType--) | يحصل على نوع المستند. |
|
|  | [setFileType(FileType fileType)](#setFileType-com.groupdocs.comparison.result.FileType-) | يضبط نوع المستند. |
|
|  | [createStream()](#createStream--) | ينشئ تدفقًا جديدًا بمحتوى المستند. |
|
|  | [getStreamLength()](#getStreamLength--) | يحصل على حجم المستند |
|
|  | [getPassword()](#getPassword--) | يحصل على كلمة مرور المستند |
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.comparison.options.PreviewOptions-) | ينشئ معاينات المستند بناءً على [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) المقدمة. |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | يحصل على معلومات حول المستند، بما في ذلك نوع المستند، عدد الصفحات، أحجام الصفحات، وأكثر. |
|
| [close()](#close--) |  |
### Document(InputStream stream) {#Document-java.io.InputStream-}
```
public Document(InputStream stream)
```


يُنشئ مثيلًا جديدًا من فئة Document باستخدام تدفق المستند المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | تدفق | java.io.InputStream | تدفق المستند |
|

### Document(String filePath) {#Document-java.lang.String-}
```
public Document(String filePath)
```


يُنشئ مثيلًا جديدًا من فئة Document باستخدام مسار المستند المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار المستند |
|

### Document(Path filePath) {#Document-java.nio.file.Path-}
```
public Document(Path filePath)
```


يُنشئ مثيلًا جديدًا من فئة Document باستخدام مسار المستند المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | مسار المستند |
|

### Document(Path filePath, String password) {#Document-java.nio.file.Path-java.lang.String-}
```
public Document(Path filePath, String password)
```


يُنشئ مثيلًا جديدًا من فئة Document باستخدام مسار المستند المحدد وكلمة مرور.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | مسار المستند |
|
|  | كلمة مرور | java.lang.String | كلمة مرور المستند |
|

### Document(Path filePath, LoadOptions loadOptions) {#Document-java.nio.file.Path-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(Path filePath, LoadOptions loadOptions)
```


يُنشئ مثيلًا جديدًا من فئة Document باستخدام مسار المستند المحدد وخيارات التحميل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | مسار المستند |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | خيارات التحميل |
|

### Document(String filePath, String password) {#Document-java.lang.String-java.lang.String-}
```
public Document(String filePath, String password)
```


يُنشئ مثيلًا جديدًا من فئة Document باستخدام مسار المستند المحدد وكلمة مرور.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار المستند |
|
|  | كلمة مرور | java.lang.String | كلمة مرور المستند |
|

### Document(String filePath, LoadOptions loadOptions) {#Document-java.lang.String-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(String filePath, LoadOptions loadOptions)
```


يُنشئ مثيلًا جديدًا من فئة Document باستخدام مسار المستند المحدد وخيارات التحميل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار المستند |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | خيارات التحميل |
|

### Document(InputStream stream, String password) {#Document-java.io.InputStream-java.lang.String-}
```
public Document(InputStream stream, String password)
```


يُنشئ مثيلًا جديدًا من فئة Document باستخدام تدفق المستند المحدد وكلمة مرور.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | تدفق | java.io.InputStream | تدفق المستند |
|
|  | كلمة مرور | java.lang.String | كلمة مرور المستند |
|

### Document(String filePathOrTextContent, boolean isLoadText) {#Document-java.lang.String-boolean-}
```
public Document(String filePathOrTextContent, boolean isLoadText)
```


يُنشئ مثيلًا جديدًا من فئة Document باستخدام مسار المستند أو محتوى النص المحدد وعلمًا يوضح ما تم تمريره.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePathOrTextContent | java.lang.String | مسار الملف |
|
|  | isLoadText | boolean | نص التحميل |
|

### Document(InputStream inputStream, LoadOptions loadOptions) {#Document-java.io.InputStream-com.groupdocs.comparison.options.load.LoadOptions-}
```
public Document(InputStream inputStream, LoadOptions loadOptions)
```


يُنشئ مثيلًا جديدًا من فئة Document باستخدام تدفق المستند المحدد وخيارات التحميل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | inputStream | java.io.InputStream | تدفق المستند |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.comparison.options.load/loadoptions) | خيارات التحميل |
|

### getChanges() {#getChanges--}
```
public final List<ChangeInfo> getChanges()
```


يحصل على قائمة من كائنات [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) التي تمثل التغييرات المكتشفة أثناء عملية المقارنة.


استخدم هذه الطريقة للحصول على معلومات مفصلة حول التغييرات بين المستند المصدر والمستند الهدف (المستندات).
كل كائن [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) يحتوي على معلومات مثل نوع التغيير، المنطقة المتأثرة،
والمحتوى قبل وبعد التغيير.


**Returns:**
java.util.List<com.groupdocs.comparison.result.ChangeInfo> - قائمة من كائنات [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) تمثل التغييرات المكتشفة أثناء عملية المقارنة

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


يضبط قائمة من كائنات [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) التي تمثل التغييرات المكتشفة أثناء عملية المقارنة.


استخدم هذه الطريقة للحصول على معلومات مفصلة حول التغييرات بين المستند المصدر والمستند الهدف (المستندات).
كل كائن [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) يحتوي على معلومات مثل نوع التغيير، المنطقة المتأثرة،
والمحتوى قبل وبعد التغيير.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | قائمة من كائنات [ChangeInfo](../../com.groupdocs.comparison.result/changeinfo) تمثل التغييرات المكتشفة أثناء عملية المقارنة |
|

### getName() {#getName--}
```
public final String getName()
```


يحصل على اسم المستند.


**Returns:**
java.lang.String - اسم المستند

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


يضبط اسم المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.lang.String | اسم المستند |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


يحصل على نوع المستند.


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the document

### setFileType(FileType fileType) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public void setFileType(FileType fileType)
```


يضبط نوع المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | نوع المستند |
|

### createStream() {#createStream--}
```
public InputStream createStream()
```


ينشئ تدفقًا جديدًا بمحتوى المستند.


**Returns:**
java.io.InputStream - الدفق الذي يحتوي على محتوى المستند

### getStreamLength() {#getStreamLength--}
```
public long getStreamLength()
```


يحصل على حجم المستند


**Returns:**
long - حجم المستند

### getPassword() {#getPassword--}
```
public String getPassword()
```


يحصل على كلمة مرور المستند


**Returns:**
java.lang.String - كلمة مرور المستند

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.comparison.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


ينشئ معاينات المستند بناءً على [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) المقدمة.


هذه الطريقة تُنشئ معاينات لصفحات المستند وفقًا للخيارات المحددة، مثل تنسيق المعاينة،
أرقام الصفحات، ومزود تدفق الإخراج. يمكن حفظ المعاينات المُنشأة أو معالجتها لاحقًا حسب الحاجة.

* Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Generate+document+pages+preview)


مثال على الاستخدام:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     PreviewOptions previewOptions = new PreviewOptions(
             pageNumber -> Files.newOutputStream(Paths.get("preview-image-page-" + pageNumber + ".png"))
     );
     previewOptions.setPreviewFormat(PreviewFormats.PNG);
     previewOptions.setPageNumbers(new int[]{1, 2});
     comparer.getSource().generatePreview(previewOptions);
 }
 
````



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.comparison.options/previewoptions) | خيارات المعاينة التي تحدد التنسيق، أرقام الصفحات وما إلى ذلك |
|

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


يحصل على معلومات حول المستند، بما في ذلك نوع المستند، عدد الصفحات، أحجام الصفحات، وأكثر.

* Learn more about document file type, page count, size, and other format-specific properties: [How to get document info using GroupDocs.Comparison](../https://docs.groupdocs.com/display/comparisonjava/Get+file+info)


**Returns:**
[IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo) - the document information

### close() {#close--}
```
public void close()
```





---
title: "RevisionHandler"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "تمثل فئة تتحكم في معالجة المراجعات."
type: docs
weight: 11
url: /ar/java/com.groupdocs.comparison.words.revision/revisionhandler/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class RevisionHandler implements Closeable
```

تمثل فئة تتحكم في معالجة المراجعات.


تسمح لك فئة RevisionHandler بالعمل مع المراجعات في المستندات.
توفر طرقًا لاسترجاع قائمة المراجعات، وتطبيق التغييرات على المراجعات، وحفظ المستند المعدل.


مثال على الاستخدام:

````

 try (RevisionHandler revisionHandler = new RevisionHandler(sourceFile)) {
     List revisionList = revisionHandler.getRevisions();

     for (RevisionInfo revisionInfo : revisionList) {
         if (revisionInfo.getType() == RevisionType.DELETION)
             // Set an action to be applied to the revision
             revisionInfo.setAction(RevisionAction.Accept);
     }
     // Create an instance of ApplyRevisionOptions
     ApplyRevisionOptions revisionChanges = new ApplyRevisionOptions();
     revisionChanges.setChanges(revisionList);
     // Apply the revisions using the options
     revisionHandler.applyRevisionChanges(resultFile, revisionChanges);
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [RevisionHandler(String filePath)](#RevisionHandler-java.lang.String-) | يُهيئ نسخة جديدة من فئة RevisionHandler باستخدام مسار الملف الذي يحتوي على المراجعات. |
|
|  | [RevisionHandler(Path filePath)](#RevisionHandler-java.nio.file.Path-) | يُهيئ نسخة جديدة من فئة RevisionHandler باستخدام مسار الملف الذي يحتوي على المراجعات. |
|
|  | [RevisionHandler(InputStream file, FileType fileType)](#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-) | يُهيئ نسخة جديدة من فئة RevisionHandler باستخدام تدفق ملف يحتوي على المراجعات. |
|
|  | [RevisionHandler(Document document)](#RevisionHandler-com.aspose.words.Document-) | يُهيئ نسخة جديدة من فئة RevisionHandler باستخدام مستند. |
|
## الحقول

| حقل | الوصف |
| --- | --- |
| [SOURCE_PATH_IS_NULL](#SOURCE-PATH-IS-NULL) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getRevisions()](#getRevisions--) | يحصل على قائمة جميع المراجعات. |
|
|  | [applyRevisionChanges(ApplyRevisionOptions changes)](#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | يعالج التغييرات في المراجعات ويطبقها على الملف الأصلي. |
|
|  | [applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | يعالج التغييرات في المراجعات ويكتب النتيجة إلى الملف المحدد. |
|
|  | [applyRevisionChanges(String filePath, ApplyRevisionOptions changes)](#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | يعالج التغييرات في المراجعات ويكتب النتيجة إلى الملف المحدد. |
|
|  | [applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)](#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-) | يعالج التغييرات في المراجعات ويكتب النتيجة إلى تدفق المستند. |
|
| [close()](#close--) |  |
### RevisionHandler(String filePath) {#RevisionHandler-java.lang.String-}
```
public RevisionHandler(String filePath)
```


يُهيئ نسخة جديدة من فئة RevisionHandler باستخدام مسار الملف الذي يحتوي على المراجعات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار الملف. |
|

### RevisionHandler(Path filePath) {#RevisionHandler-java.nio.file.Path-}
```
public RevisionHandler(Path filePath)
```


يُهيئ نسخة جديدة من فئة RevisionHandler باستخدام مسار الملف الذي يحتوي على المراجعات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | مسار الملف. |
|

### RevisionHandler(InputStream file, FileType fileType) {#RevisionHandler-java.io.InputStream-com.groupdocs.comparison.result.FileType-}
```
public RevisionHandler(InputStream file, FileType fileType)
```


يُهيئ نسخة جديدة من فئة RevisionHandler باستخدام تدفق ملف يحتوي على المراجعات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | ملف | java.io.InputStream | دفق مستند المصدر. |
|
|  | fileType | [FileType](../../com.groupdocs.comparison.result/filetype) | نوع الملف. |
|

### RevisionHandler(Document document) {#RevisionHandler-com.aspose.words.Document-}
```
public RevisionHandler(Document document)
```


يُهيئ نسخة جديدة من فئة RevisionHandler باستخدام مستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مستند | com.aspose.words.Document | المستند. |
|

### SOURCE_PATH_IS_NULL {#SOURCE-PATH-IS-NULL}
```
public static final String SOURCE_PATH_IS_NULL
```


### getRevisions() {#getRevisions--}
```
public List<RevisionInfo> getRevisions()
```


يحصل على قائمة جميع المراجعات.


نظرًا لأن المراجعات كانت مرتبة أصلاً في مجموعة، يجب أخذ المراجعات من قائمة.
في القائمة، يمكن تقسيم مراجعة واحدة إلى مراجعات متعددة بنفس النص العام.
نظرًا لأن القائمة قد تحتوي على مراجعات بنفس النص العام، يجب التحكم في ذلك عند إنشاء قائمة بالمراجعات للمستخدم.
يتم التحكم في ذلك هنا باستخدام مجموعات List\<RevisionGroup\>.


**Returns:**
java.util.List<com.groupdocs.comparison.words.revision.RevisionInfo> - قائمة المراجعات.

### applyRevisionChanges(ApplyRevisionOptions changes) {#applyRevisionChanges-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(ApplyRevisionOptions changes)
```


يعالج التغييرات في المراجعات ويطبقها على الملف الأصلي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | قائمة المراجعات المتغيرة. |
|

### applyRevisionChanges(Path filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.nio.file.Path-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(Path filePath, ApplyRevisionOptions changes)
```


يعالج التغييرات في المراجعات ويكتب النتيجة إلى الملف المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | مسار ملف النتيجة. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | قائمة المراجعات المتغيرة. |
|

### applyRevisionChanges(String filePath, ApplyRevisionOptions changes) {#applyRevisionChanges-java.lang.String-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(String filePath, ApplyRevisionOptions changes)
```


يعالج التغييرات في المراجعات ويكتب النتيجة إلى الملف المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار ملف النتيجة. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | قائمة المراجعات المتغيرة. |
|

### applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes) {#applyRevisionChanges-java.io.OutputStream-com.groupdocs.comparison.words.revision.ApplyRevisionOptions-}
```
public void applyRevisionChanges(OutputStream outputStream, ApplyRevisionOptions changes)
```


يعالج التغييرات في المراجعات ويكتب النتيجة إلى تدفق المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | outputStream | java.io.OutputStream | دفق مستند النتيجة. |
|
|  | changes | [ApplyRevisionOptions](../../com.groupdocs.comparison.words.revision/applyrevisionoptions) | قائمة المراجعات المتغيرة. |
|

### close() {#close--}
```
public void close()
```





---
title: "SaveOptions"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "يسمح بتحديد خيارات إضافية عند حفظ مستند."
type: docs
weight: 10
url: /ar/java/com.groupdocs.comparison.options.save/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

يسمح بتحديد خيارات إضافية عند حفظ مستند.


مثال على الاستخدام:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    comparer.add(targetFile);

    final SaveOptions saveOptions = new SaveOptions();
    saveOptions.setPassword("passw");

    comparer.compare(resultFile, saveOptions);
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [SaveOptions()](#SaveOptions--) | يُهيئ نسخة جديدة من فئة SaveOptions. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getCloneMetadataType()](#getCloneMetadataType--) | يحصل على استراتيجية معالجة حفظ بيانات التعريف للمستند الناتج. |
|
|  | [setCloneMetadataType(MetadataType value)](#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-) | يضبط استراتيجية معالجة حفظ بيانات التعريف للمستند الناتج. |
|
|  | [getFileAuthorMetadata()](#getFileAuthorMetadata--) | يحصل على كائن بيانات التعريف الذي سيتم تعيينه في مستند النتيجة عندما يتم تعيين [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) إلى [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR). |
|
|  | [setFileAuthorMetadata(FileAuthorMetadata value)](#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-) | يضبط كائن بيانات التعريف الذي يجب تعيينه في مستند النتيجة عندما يتم تعيين [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) إلى [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR). |
|
|  | [getPassword()](#getPassword--) | يحصل على كلمة مرور للمستند الناتج. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | يضبط كلمة مرور للمستند الناتج. |
|
|  | [getFolderPath()](#getFolderPath--) | يحصل على مسار المجلد الذي سيتم حفظ صور النتيجة فيه. |
|
|  | [setFolderPath(String value)](#setFolderPath-java.lang.String-) | يضبط مسار المجلد الذي يجب حفظ صور النتيجة فيه. |
|
|  | [setFolderPath(Path value)](#setFolderPath-java.nio.file.Path-) | يضبط مسار المجلد الذي يجب حفظ صور النتيجة فيه. |
|
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


يُهيئ نسخة جديدة من فئة SaveOptions.


### getCloneMetadataType() {#getCloneMetadataType--}
```
public final MetadataType getCloneMetadataType()
```


يحصل على استراتيجية معالجة حفظ بيانات التعريف للمستند الناتج.
القيم الممكنة موجودة في تعداد [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)


**Returns:**
[MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) - the stragegy of processing metadata

### setCloneMetadataType(MetadataType value) {#setCloneMetadataType-com.groupdocs.comparison.options.enums.MetadataType-}
```
public final void setCloneMetadataType(MetadataType value)
```


يضبط استراتيجية معالجة حفظ بيانات التعريف للمستند الناتج.
القيم الممكنة موجودة في تعداد [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [MetadataType](../../com.groupdocs.comparison.options.enums/metadatatype) | استراتيجية معالجة بيانات التعريف |
|

### getFileAuthorMetadata() {#getFileAuthorMetadata--}
```
public final FileAuthorMetadata getFileAuthorMetadata()
```


يحصل على كائن بيانات التعريف الذي سيتم تعيينه في مستند النتيجة عندما يتم تعيين [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) إلى [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR).


**Returns:**
[FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) - the metadata object

### setFileAuthorMetadata(FileAuthorMetadata value) {#setFileAuthorMetadata-com.groupdocs.comparison.options.FileAuthorMetadata-}
```
public final void setFileAuthorMetadata(FileAuthorMetadata value)
```


يضبط كائن بيانات التعريف الذي يجب تعيينه في مستند النتيجة عندما يتم تعيين [setCloneMetadataType(MetadataType)](../../com.groupdocs.comparison.options.save/saveoptions#setCloneMetadataType-MetadataType-) إلى [MetadataType.FILE_AUTHOR](../../com.groupdocs.comparison.options.enums/metadatatype#FILE-AUTHOR).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [FileAuthorMetadata](../../com.groupdocs.comparison.options/fileauthormetadata) | كائن بيانات التعريف |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


يحصل على كلمة مرور للمستند الناتج.


**Returns:**
java.lang.String - كلمة المرور

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


يضبط كلمة مرور للمستند الناتج.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.lang.String | كلمة المرور |
|

### getFolderPath() {#getFolderPath--}
```
public final String getFolderPath()
```


يحصل على مسار المجلد الذي سيتم حفظ صور النتيجة فيه.
يُستخدم لمقارنة الصور فقط.


**Returns:**
java.lang.String - مسار المجلد لحفظ صور النتيجة

### setFolderPath(String value) {#setFolderPath-java.lang.String-}
```
public final void setFolderPath(String value)
```


يضبط مسار المجلد الذي يجب حفظ صور النتيجة فيه.
يُستخدم لمقارنة الصور فقط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.lang.String | مسار المجلد لحفظ صور النتيجة |
|

### setFolderPath(Path value) {#setFolderPath-java.nio.file.Path-}
```
public final void setFolderPath(Path value)
```


يضبط مسار المجلد الذي يجب حفظ صور النتيجة فيه.
يُستخدم لمقارنة الصور فقط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.nio.file.Path | مسار المجلد لحفظ صور النتيجة |
|


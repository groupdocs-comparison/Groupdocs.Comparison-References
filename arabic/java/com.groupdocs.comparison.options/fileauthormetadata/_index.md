---
title: "FileAuthorMetadata"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "يسمح بتكوين معلومات حول البيانات الوصفية لمؤلف المستند."
type: docs
weight: 12
url: /ar/java/com.groupdocs.comparison.options/fileauthormetadata/
---
**Inheritance:**
java.lang.Object
```
public class FileAuthorMetadata
```

يسمح بتكوين معلومات بيانات تعريف مؤلف المستند.


مثال على الاستخدام:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     SaveOptions saveOptions = new SaveOptions();
     saveOptions.setCloneMetadataType(MetadataType.FILE_AUTHOR);

     final FileAuthorMetadata fileAuthorMetadata = new FileAuthorMetadata();
     fileAuthorMetadata.setAuthor("Tom");
     fileAuthorMetadata.setCompany("GroupDocs");
     fileAuthorMetadata.setLastSaveBy("Jack");

     saveOptions.setFileAuthorMetadata(fileAuthorMetadata);

     comparer.compare(resultFile, saveOptions);
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [FileAuthorMetadata()](#FileAuthorMetadata--) | ينشئ مثيلاً جديداً من الفئة FileAuthorMetadata. |
|
## الحقول

| حقل | الوصف |
| --- | --- |
| [GROUP_DOCS](#GROUP-DOCS) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getAuthor()](#getAuthor--) | يحصل على مؤلف المستند. |
|
|  | [setAuthor(String value)](#setAuthor-java.lang.String-) | يضبط مؤلف المستند. |
|
|  | [getLastSaveBy()](#getLastSaveBy--) | يحصل على اسم الشخص الذي حفظ المستند لآخر مرة. |
|
|  | [setLastSaveBy(String value)](#setLastSaveBy-java.lang.String-) | يضبط اسم الشخص الذي حفظ المستند لآخر مرة. |
|
|  | [getCompany()](#getCompany--) | يحصل على اسم الشركة التي ينتمي إليها المستند. |
|
|  | [setCompany(String value)](#setCompany-java.lang.String-) | يضبط اسم الشركة التي ينتمي إليها المستند. |
|
### FileAuthorMetadata() {#FileAuthorMetadata--}
```
public FileAuthorMetadata()
```


ينشئ مثيلاً جديداً من الفئة FileAuthorMetadata.


### GROUP_DOCS {#GROUP-DOCS}
```
public static final String GROUP_DOCS
```


### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```


يحصل على مؤلف المستند.


**Returns:**
java.lang.String - المؤلف

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```


يضبط مؤلف المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.lang.String | المؤلف |
|

### getLastSaveBy() {#getLastSaveBy--}
```
public final String getLastSaveBy()
```


يحصل على اسم الشخص الذي حفظ المستند لآخر مرة.


**Returns:**
java.lang.String - الاسم

### setLastSaveBy(String value) {#setLastSaveBy-java.lang.String-}
```
public final void setLastSaveBy(String value)
```


يضبط اسم الشخص الذي حفظ المستند لآخر مرة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.lang.String | اسم الشخص |
|

### getCompany() {#getCompany--}
```
public final String getCompany()
```


يحصل على اسم الشركة التي ينتمي إليها المستند.


**Returns:**
java.lang.String - اسم الشركة

### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```


يضبط اسم الشركة التي ينتمي إليها المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.lang.String | اسم الشركة |
|


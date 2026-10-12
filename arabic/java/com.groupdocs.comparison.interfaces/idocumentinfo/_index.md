---
title: "IDocumentInfo"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "يوفر الوصول إلى خصائص المستند."
type: docs
weight: 10
url: /ar/java/com.groupdocs.comparison.interfaces/idocumentinfo/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface IDocumentInfo extends Closeable
```

يوفر الوصول إلى خصائص المستند.


يمكن العثور على مزيد من التفاصيل حول استخدامها في طريقة [Document.getDocumentInfo()](../../com.groupdocs.comparison/document#getDocumentInfo--) أو في [وثائق](../https://docs.groupdocs.com/comparison/java/get-file-info/).


مثال على الاستخدام:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
    try (IDocumentInfo documentInfo = comparer.getSource().getDocumentInfo()) {
      for (int i = 0; i < documentInfo.getPageCount(); i++) {
          System.out.printf("File type: %s%nNumber of pages: %d", documentInfo.getFileType().getFileFormat(), documentInfo.getPageCount());
      }
    }
 }
 
````


## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFileType()](#getFileType--) | يحصل على نوع الملف الممثل بتعداد [FileType](../../com.groupdocs.comparison.result/filetype). |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.comparison.result.FileType-) | يضبط نوع الملف باستخدام تعداد [FileType](../../com.groupdocs.comparison.result/filetype). |
|
|  | [getPageCount()](#getPageCount--) | يحصل على عدد الملف. |
|
|  | [setPageCount(int value)](#setPageCount-int-) | يضبط عدد الملف. |
|
|  | [getSize()](#getSize--) | يحصل على حجم الملف. |
|
|  | [setSize(long value)](#setSize-long-) | يضبط حجم الملف. |
|
|  | [getPagesInfo()](#getPagesInfo--) | يحصل على معلومات كل صفحة من الملف باستخدام الفئة [PageInfo](../../com.groupdocs.comparison.result/pageinfo). |
|
|  | [setPagesInfo(List<PageInfo> pageInfos)](#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--) | يضبط معلومات كل صفحة من الملف باستخدام الفئة [PageInfo](../../com.groupdocs.comparison.result/pageinfo). |
|
|  | [close()](#close--) | يدمر الكائن مما يجعل من المستحيل الحصول على معلومات المستند باستخدام هذه النسخة من كائن [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo). |
|
### getFileType() {#getFileType--}
```
public abstract FileType getFileType()
```


يحصل على نوع الملف الممثل بتعداد [FileType](../../com.groupdocs.comparison.result/filetype).


**Returns:**
[FileType](../../com.groupdocs.comparison.result/filetype) - the type of the file

### setFileType(FileType value) {#setFileType-com.groupdocs.comparison.result.FileType-}
```
public abstract void setFileType(FileType value)
```


يضبط نوع الملف باستخدام تعداد [FileType](../../com.groupdocs.comparison.result/filetype).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.comparison.result/filetype) | نوع الملف |
|

### getPageCount() {#getPageCount--}
```
public abstract int getPageCount()
```


يحصل على عدد الملف.


**Returns:**
int - عدد الملف

### setPageCount(int value) {#setPageCount-int-}
```
public abstract void setPageCount(int value)
```


يضبط عدد الملف.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | int | عدد الملف |
|

### getSize() {#getSize--}
```
public abstract long getSize()
```


يحصل على حجم الملف.


**Returns:**
long - حجم الملف

### setSize(long value) {#setSize-long-}
```
public abstract void setSize(long value)
```


يضبط حجم الملف.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | long | حجم الملف |
|

### getPagesInfo() {#getPagesInfo--}
```
public abstract List<PageInfo> getPagesInfo()
```


يحصل على معلومات كل صفحة من الملف باستخدام الفئة [PageInfo](../../com.groupdocs.comparison.result/pageinfo).


**Returns:**
java.util.List<com.groupdocs.comparison.result.PageInfo> - معلومات لكل صفحة من الملف

### setPagesInfo(List<PageInfo> pageInfos) {#setPagesInfo-java.util.List-com.groupdocs.comparison.result.PageInfo--}
```
public abstract void setPagesInfo(List<PageInfo> pageInfos)
```


يضبط معلومات كل صفحة من الملف باستخدام الفئة [PageInfo](../../com.groupdocs.comparison.result/pageinfo).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | pageInfos | java.util.List<com.groupdocs.comparison.result.PageInfo> | معلومات لكل صفحة من الملف |
|

### close() {#close--}
```
public abstract void close()
```


يدمر الكائن مما يجعل من المستحيل الحصول على معلومات المستند باستخدام هذه النسخة من كائن [IDocumentInfo](../../com.groupdocs.comparison.interfaces/idocumentinfo).
كما يحذف الملفات المؤقتة ويحرر الموارد المستخدمة.



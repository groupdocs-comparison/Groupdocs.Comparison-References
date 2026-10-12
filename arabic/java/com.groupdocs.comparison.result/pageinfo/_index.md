---
title: "PageInfo"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "تمثل فئة PageInfo معلومات حول صفحة محددة في المستند."
type: docs
weight: 11
url: /ar/java/com.groupdocs.comparison.result/pageinfo/
---
**Inheritance:**
java.lang.Object
```
public class PageInfo
```

تمثل فئة PageInfo معلومات حول صفحة محددة في المستند.


يوفر تفاصيل مثل رقم الصفحة والعرض والارتفاع وغيرها من الخصائص ذات الصلة.
استخدم هذه الفئة لاسترجاع معلومات حول الصفحات الفردية في مستند أثناء عملية المقارنة.


مثال على الاستخدام:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare(resultFile);
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo change : changes) {
         final PageInfo pageInfo = change.getPageInfo();
         // Print the page information
         System.out.println("Page Number: " + pageInfo.getPageNumber());
         System.out.println("Page Width: " + pageInfo.getWidth());
         System.out.println("Page Height: " + pageInfo.getHeight());
     }
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [PageInfo(int pageNumber, int width, int height)](#PageInfo-int-int-int-) | ينشئ مثيلاً جديداً من فئة PageInfo مع تكوين رقم الصفحة والعرض والارتفاع. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getWidth()](#getWidth--) | يحصل على عرض الصفحة |
|
|  | [setWidth(int value)](#setWidth-int-) | يضبط عرض الصفحة |
|
|  | [getHeight()](#getHeight--) | يحصل على ارتفاع الصفحة |
|
|  | [setHeight(int value)](#setHeight-int-) | يضبط ارتفاع الصفحة |
|
|  | [getPageNumber()](#getPageNumber--) | يحصل على رقم الصفحة |
|
|  | [setPageNumber(int value)](#setPageNumber-int-) | يضبط رقم الصفحة |
|
| [toString()](#toString--) |  |
### PageInfo(int pageNumber, int width, int height) {#PageInfo-int-int-int-}
```
public PageInfo(int pageNumber, int width, int height)
```


ينشئ مثيلاً جديداً من فئة PageInfo مع تكوين رقم الصفحة والعرض والارتفاع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | pageNumber | int | رقم الصفحة |
|
|  | العرض | int | عرض الصفحة |
|
|  | الارتفاع | int | ارتفاع الصفحة |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


يحصل على عرض الصفحة


**Returns:**
int - عرض الصفحة

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


يضبط عرض الصفحة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | int | عرض الصفحة |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


يحصل على ارتفاع الصفحة


**Returns:**
int - ارتفاع الصفحة

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


يضبط ارتفاع الصفحة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | int | ارتفاع الصفحة |
|

### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


يحصل على رقم الصفحة


**Returns:**
int - رقم الصفحة

### setPageNumber(int value) {#setPageNumber-int-}
```
public final void setPageNumber(int value)
```


يضبط رقم الصفحة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | int | رقم الصفحة |
|

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String

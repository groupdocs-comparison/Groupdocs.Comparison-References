---
title: "OriginalSize"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "يمثل الحجم الأصلي لمستند في نتيجة المقارنة."
type: docs
weight: 14
url: /ar/java/com.groupdocs.comparison.options/originalsize/
---
**Inheritance:**
java.lang.Object
```
public class OriginalSize
```

يمثل الحجم الأصلي لمستند في نتيجة المقارنة.


الحجم الأصلي يتضمن أبعاد (العرض والارتفاع) لصفحات المستند.


مثال على الاستخدام:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     CompareOptions compareOptions = new CompareOptions();
     final OriginalSize originalSize = compareOptions.getOriginalSize();
     originalSize.setWidth(480);
     originalSize.setHeight(640);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
| [OriginalSize()](#OriginalSize--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getWidth()](#getWidth--) | يحصل على عرض صفحات المستند. |
|
|  | [setWidth(int value)](#setWidth-int-) | يضبط عرض صفحات المستند. |
|
|  | [getHeight()](#getHeight--) | يحصل على ارتفاع صفحات المستند. |
|
|  | [setHeight(int value)](#setHeight-int-) | يضبط ارتفاع صفحات المستند. |
|
### OriginalSize() {#OriginalSize--}
```
public OriginalSize()
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


يحصل على عرض صفحات المستند.


**Returns:**
int - عرض صفحات المستند.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


يضبط عرض صفحات المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | int | عرض صفحات المستند. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


يحصل على ارتفاع صفحات المستند.


**Returns:**
int - ارتفاع صفحات المستند.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


يضبط ارتفاع صفحات المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | int | ارتفاع صفحات المستند. |
|


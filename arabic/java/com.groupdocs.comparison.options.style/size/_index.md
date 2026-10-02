---
title: "الحجم"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "يمثل حجم المستند في المقارنة."
type: docs
weight: 11
url: /ar/java/com.groupdocs.comparison.options.style/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

يمثل حجم المستند في المقارنة.


مثال على الاستخدام:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final Size originalSize = new Size(100, 200);

     StyleSettings styleSettings = new StyleSettings();
     styleSettings.setOriginalSize(originalSize);

     final CompareOptions compareOptions = new CompareOptions();
     compareOptions.setInsertedItemStyle(styleSettings);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [Size()](#Size--) | ينشئ مثيلًا جديدًا من الفئة Size. |
|
|  | [Size(int width, int height)](#Size-int-int-) | ينشئ مثيلًا جديدًا من الفئة Size بعرض وارتفاع المستند. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getWidth()](#getWidth--) | يحصل على عرض المستند الأصلي. |
|
|  | [setWidth(int value)](#setWidth-int-) | يضبط عرض المستند الأصلي. |
|
|  | [getHeight()](#getHeight--) | يحصل على ارتفاع المستند الأصلي. |
|
|  | [setHeight(int value)](#setHeight-int-) | يضبط ارتفاع المستند الأصلي. |
|
### Size() {#Size--}
```
public Size()
```


ينشئ مثيلًا جديدًا من الفئة Size.


### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


ينشئ مثيلًا جديدًا من الفئة Size بعرض وارتفاع المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | int |  |
| الارتفاع | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


يحصل على عرض المستند الأصلي.


**Returns:**
int - عرض المستند

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


يضبط عرض المستند الأصلي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | int | عرض المستند |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


يحصل على ارتفاع المستند الأصلي.


**Returns:**
int - ارتفاع المستند

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


يضبط ارتفاع المستند الأصلي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | int | ارتفاع المستند |
|


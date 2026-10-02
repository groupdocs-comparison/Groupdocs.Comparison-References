---
title: "GetChangeOptions"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "يسمح بتكوين التصفية لاسترجاع أنواع تغييرات محددة من نتيجة المقارنة."
type: docs
weight: 13
url: /ar/java/com.groupdocs.comparison.options/getchangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class GetChangeOptions
```

يسمح بتكوين التصفية لاسترجاع أنواع تغييرات محددة من نتيجة المقارنة.


مثال على الاستخدام:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();

     GetChangeOptions getChangeOptions = new GetChangeOptions();

     getChangeOptions.setFilter(ChangeType.DELETED);

     ChangeInfo[] changes = comparer.getChanges(getChangeOptions);
     System.out.println(Arrays.toString(changes));
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [GetChangeOptions()](#GetChangeOptions--) | يُهيئ نسخة جديدة من فئة GetChangeOptions. |
|
|  | [GetChangeOptions(ChangeType filter)](#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-) | يُهيئ نسخة جديدة من فئة GetChangeOptions لنوع الفلتر المحدد. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFilter()](#getFilter--) | يحصل على الفلتر لاسترجاع أنواع التغييرات المحددة من نتيجة المقارنة. |
|
|  | [setFilter(ChangeType value)](#setFilter-com.groupdocs.comparison.result.ChangeType-) | يضبط الفلتر لاسترجاع أنواع التغييرات المحددة من نتيجة المقارنة. |
|
### GetChangeOptions() {#GetChangeOptions--}
```
public GetChangeOptions()
```


يُهيئ نسخة جديدة من فئة GetChangeOptions.


### GetChangeOptions(ChangeType filter) {#GetChangeOptions-com.groupdocs.comparison.result.ChangeType-}
```
public GetChangeOptions(ChangeType filter)
```


يُهيئ نسخة جديدة من فئة GetChangeOptions لنوع الفلتر المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filter | [ChangeType](../../com.groupdocs.comparison.result/changetype) |  |

### getFilter() {#getFilter--}
```
public final ChangeType getFilter()
```


يحصل على الفلتر لاسترجاع أنواع التغييرات المحددة من نتيجة المقارنة.


**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the filter specifying the types of changes to be retrieved.

### setFilter(ChangeType value) {#setFilter-com.groupdocs.comparison.result.ChangeType-}
```
public final void setFilter(ChangeType value)
```


يضبط الفلتر لاسترجاع أنواع التغييرات المحددة من نتيجة المقارنة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [ChangeType](../../com.groupdocs.comparison.result/changetype) | الفلتر الذي يحدد أنواع التغييرات التي سيتم استرجاعها. |
|


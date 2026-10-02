---
title: "StyleChangeInfo"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "تمثل فئة StyleChangeInfo معلومات حول تغيير النمط في مستند تم مقارنته."
type: docs
weight: 13
url: /ar/java/com.groupdocs.comparison.result/stylechangeinfo/
---
**Inheritance:**
java.lang.Object
```
public class StyleChangeInfo
```

تمثل فئة StyleChangeInfo معلومات حول تغيير النمط في مستند تم مقارنته.


يوفر تفاصيل مثل اسم الخاصية التي تم تغييرها، القيم قبل وبعد التغيير، وما إلى ذلك.
استخدم هذه الفئة لاسترجاع معلومات حول تغييرات النمط أثناء عملية مقارنة المستندات.


مثال على الاستخدام:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare();
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo change : changes) {
         // Access the style change information
         final List styleChanges = change.getStyleChanges();
         for (StyleChangeInfo styleChange : styleChanges) {
             // Print the style change information
             System.out.println("PropertyName: " + styleChange.getPropertyName());
             System.out.println("OldValue: " + styleChange.getOldValue());
             System.out.println("NewValue: " + styleChange.getNewValue());
         }
     }
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
| [StyleChangeInfo()](#StyleChangeInfo--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPropertyName()](#getPropertyName--) | يحصل على اسم الخاصية التي تم تغييرها. |
|
|  | [setPropertyName(String value)](#setPropertyName-java.lang.String-) | يضبط اسم الخاصية التي تم تغييرها. |
|
|  | [getNewValue()](#getNewValue--) | يحصل على القيمة الجديدة للخاصية. |
|
|  | [setNewValue(Object value)](#setNewValue-java.lang.Object-) | يضبط القيمة الجديدة للخاصية. |
|
|  | [getOldValue()](#getOldValue--) | يحصل على القيمة القديمة للخاصية. |
|
|  | [setOldValue(Object value)](#setOldValue-java.lang.Object-) | يضبط القيمة القديمة للخاصية. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | {@inheritDoc} |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
### StyleChangeInfo() {#StyleChangeInfo--}
```
public StyleChangeInfo()
```


### getPropertyName() {#getPropertyName--}
```
public final String getPropertyName()
```


يحصل على اسم الخاصية التي تم تغييرها.


**Returns:**
java.lang.String - اسم الخاصية

### setPropertyName(String value) {#setPropertyName-java.lang.String-}
```
public final void setPropertyName(String value)
```


يضبط اسم الخاصية التي تم تغييرها.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.lang.String | اسم الخاصية |
|

### getNewValue() {#getNewValue--}
```
public final Object getNewValue()
```


يحصل على القيمة الجديدة للخاصية.


**Returns:**
java.lang.Object - القيمة الجديدة للخاصية

### setNewValue(Object value) {#setNewValue-java.lang.Object-}
```
public final void setNewValue(Object value)
```


يضبط القيمة الجديدة للخاصية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.lang.Object | القيمة الجديدة للخاصية |
|

### getOldValue() {#getOldValue--}
```
public final Object getOldValue()
```


يحصل على القيمة القديمة للخاصية.


**Returns:**
java.lang.Object - القيمة القديمة للخاصية

### setOldValue(Object value) {#setOldValue-java.lang.Object-}
```
public final void setOldValue(Object value)
```


يضبط القيمة القديمة للخاصية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.lang.Object | القيمة القديمة للخاصية |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| o | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int

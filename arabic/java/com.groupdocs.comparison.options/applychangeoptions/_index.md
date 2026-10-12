---
title: "ApplyChangeOptions"
second_title: "GroupDocs.Comparison لـ Java API Reference"
description: "يسمح بتحديث قائمة التغييرات قبل تطبيقها على المستند الناتج."
type: docs
weight: 10
url: /ar/java/com.groupdocs.comparison.options/applychangeoptions/
---
**Inheritance:**
java.lang.Object
```
public class ApplyChangeOptions
```

يسمح بتحديث قائمة التغييرات قبل تطبيقها على المستند الناتج.


مثال على الاستخدام:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();
     ChangeInfo[] changes = comparer.getChanges();
     changes[0].setComparisonAction(ComparisonAction.REJECT);

     final ApplyChangeOptions applyChangeOptions = new ApplyChangeOptions(changes);

     comparer.applyChanges(resultFile, applyChangeOptions);
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [ApplyChangeOptions()](#ApplyChangeOptions--) | ينشئ مثيلاً جديداً من الفئة ApplyChangeOptions. |
|
|  | [ApplyChangeOptions(List<ChangeInfo> changes)](#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | ينشئ مثيلاً جديداً من الفئة ApplyChangeOptions مع قائمة التغييرات. |
|
|  | [ApplyChangeOptions(ChangeInfo[] changes)](#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---) | ينشئ مثيلاً جديداً من الفئة ApplyChangeOptions مع مصفوفة التغييرات. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getChanges()](#getChanges--) | يحصل على مصفوفة من التغييرات التي يجب تطبيقها على المستند الناتج. |
|
|  | [setChanges(ChangeInfo[] value)](#setChanges-com.groupdocs.comparison.result.ChangeInfo---) | يضبط مصفوفة من التغييرات التي يجب تطبيقها على المستند الناتج. |
|
|  | [setChanges(List<ChangeInfo> value)](#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--) | يضبط قائمة من التغييرات التي يجب تطبيقها على المستند الناتج. |
|
|  | [isSaveOriginalState()](#isSaveOriginalState--) | يحصل على علم يحدد ما إذا كان يجب حفظ الحالة الأصلية. |
|
|  | [setSaveOriginalState(boolean saveOriginalState)](#setSaveOriginalState-boolean-) | يضبط علم يحدد ما إذا كان يجب حفظ الحالة الأصلية. |
|
### ApplyChangeOptions() {#ApplyChangeOptions--}
```
public ApplyChangeOptions()
```


ينشئ مثيلاً جديداً من الفئة ApplyChangeOptions.


### ApplyChangeOptions(List<ChangeInfo> changes) {#ApplyChangeOptions-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public ApplyChangeOptions(List<ChangeInfo> changes)
```


ينشئ مثيلاً جديداً من الفئة ApplyChangeOptions مع قائمة التغييرات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | التغييرات | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | قائمة التغييرات التي سيتم تطبيقها |
|

### ApplyChangeOptions(ChangeInfo[] changes) {#ApplyChangeOptions-com.groupdocs.comparison.result.ChangeInfo---}
```
public ApplyChangeOptions(ChangeInfo[] changes)
```


ينشئ مثيلاً جديداً من الفئة ApplyChangeOptions مع مصفوفة التغييرات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | changes | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | قائمة التغييرات التي سيتم تطبيقها |
|

### getChanges() {#getChanges--}
```
public final ChangeInfo[] getChanges()
```


يحصل على مصفوفة من التغييرات التي يجب تطبيقها على المستند الناتج.


**Returns:**
com.groupdocs.comparison.result.ChangeInfo[] - مصفوفة التغييرات التي سيتم تطبيقها

### setChanges(ChangeInfo[] value) {#setChanges-com.groupdocs.comparison.result.ChangeInfo---}
```
public final void setChanges(ChangeInfo[] value)
```


يضبط مصفوفة من التغييرات التي يجب تطبيقها على المستند الناتج.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [ChangeInfo\[\]](../../com.groupdocs.comparison.result/changeinfo) | مصفوفة التغييرات التي سيتم تطبيقها |
|

### setChanges(List<ChangeInfo> value) {#setChanges-java.util.List-com.groupdocs.comparison.result.ChangeInfo--}
```
public final void setChanges(List<ChangeInfo> value)
```


يضبط قائمة من التغييرات التي يجب تطبيقها على المستند الناتج.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.util.List<com.groupdocs.comparison.result.ChangeInfo> | قائمة التغييرات التي سيتم تطبيقها |
|

### isSaveOriginalState() {#isSaveOriginalState--}
```
public boolean isSaveOriginalState()
```


يحصل على علم يحدد ما إذا كان يجب حفظ الحالة الأصلية. القيمة الافتراضية: false.


**Returns:**
boolean - true إذا كان يجب حفظ الحالة الأصلية، وإلا false

### setSaveOriginalState(boolean saveOriginalState) {#setSaveOriginalState-boolean-}
```
public void setSaveOriginalState(boolean saveOriginalState)
```


يضبط علم يحدد ما إذا كان يجب حفظ الحالة الأصلية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | saveOriginalState | boolean | True إذا كان يجب حفظ الحالة الأصلية، وإلا false |
|

